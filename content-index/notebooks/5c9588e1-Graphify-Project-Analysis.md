# Graphify Project Analysis and Contributor Integration Strategy — indice di contenuto
> notebook_id: 5c9588e1-8978-41bc-8565-6663fa315d6e · 13 fonti · sessione 2026-06-01 · ri-verificato alla fonte

### Discussion #532 — per-tool plugins (chiusa, duplicato di #146)
- **source_id:** d813c1f2-ac8a-4a4d-9b8a-fe09c3b8b38b  ·  **tipo:** url
- **sostanza:** Discussion GitHub aperta da serithemage (23 apr) su come strutturare le integrazioni per-tool di graphify: continuare a fondere tutto in `graphify/__main__.py` (~65 KB, `_PLATFORM_CONFIG` su 9+ tool) o spostarle in plugin Claude separati che dipendono da `graphifyy`. Descrive un'integrazione three-tier (Passive/Auto/Active) con hook `UserPromptSubmit` e MCP in `.mcp.json`. Chiusa il 24 apr come duplicato di #146.
- **keyword/entità:** serithemage · Claude plugin · three-tier · UserPromptSubmit · .mcp.json · #146

### Guida Tecnica e Strategica — report originale (copia di nota colmata)
- **source_id:** 6dee78d4-8d00-42b7-8353-4f79443604c7  ·  **tipo:** text
- **sostanza:** Frammento (troncato) di una guida per i contributi di neo1777 a graphify. Conferma l'attività recente di Neo collegandolo all'Issue #934 ("cluster-only crashes with FileNotFoundError") e al debugging del core engine. Indica gli standard: `pytest tests/ -q` deve passare prima di una PR, e convenzione di commit `fix:` (testo interrotto).
- **keyword/entità:** neo1777 · Issue #934 · cluster-only · pytest · commit convention · contributing

### Issue #146 — Native Claude Plugin / MCP integration (aperta, impl pronta in v5)
- **source_id:** e9c4fd34-c428-4751-b722-937a85d5c635  ·  **tipo:** url
- **sostanza:** Feature request di vimoxshah (9 apr, aperta) per supporto nativo Claude Plugin / MCP server con tool come `build_graph`, `query_graph`, `update_graph`, `export_graph`, `explain_architecture`. Nei commenti JoyCal000Gold motiva il taglio dei token (`search_nodes`/`get_community`/`find_path` < 200 token); serithemage presenta un'implementazione v5-rebased (30 unit test + E2E) e due path: PR contro v5 o plugin separato `graphify-claude-plugin`. 5 like.
- **keyword/entità:** vimoxshah · MCP server · zero-setup · query_graph · serithemage · token reduction

### Issue #290 — leiden/all fail Python 3.13+ graspologic (chiusa, v0.4.9)
- **source_id:** 673d2ea4-6a56-43fe-a67b-fadbf64b9492  ·  **tipo:** url
- **sostanza:** Bug report di 3esmit: gli extra `.[leiden]` e `.[all]` si installano su Python 3.10-3.12 (graspologic 3.4.4) ma falliscono su 3.13+ perché pip risolve graspologic 0.3.1 → gensim vecchio che rompe la metadata-generation. graphify ha già fallback runtime a NetworkX Louvain; la richiesta è restringere `requires-python` a `>=3.10,<3.13` e documentarlo. Chiusa da safishamsi "Fixed in v0.4.9".
- **keyword/entità:** 3esmit · graspologic · gensim · Python 3.13 · Leiden · Louvain fallback · v0.4.9

### Issue #341 — graphify update O(V×E) betweenness_centrality (chiusa, v0.4.14)
- **source_id:** 3312e1ed-21a4-4b36-8e2e-54b9f03a5c5e  ·  **tipo:** url
- **sostanza:** loktarjugg segnala che `graphify update` è lentissimo su monorepo grandi (450k nodi, 690k archi): `suggest_questions()` in analyze.py chiama `nx.betweenness_centrality(G)` che è O(V×E) — 114 min senza completare su un Xeon 96-core. Propone soglia/approssimazione/flag `--skip-report`. Risolto in v0.4.14.
- **keyword/entità:** loktarjugg · betweenness_centrality · O(V×E) · suggest_questions · monorepo · v0.4.14

### Issue #369 — Team workflow with committed graphs (chiusa, v0.4.19)
- **source_id:** ed2b3cc3-5ea4-41b7-89f5-241ecd8de873  ·  **tipo:** url
- **sostanza:** fakesmallcc chiede il workflow di team per grafi committati. safishamsi risponde: il grafo è un build artifact (come un binario compilato), un solo maintainer/CI lo rigenera, gli altri lo consumano via query. La non-determinismo LLM è by design; `manifest.json` va in .gitignore (mtime drift); la cache content-addressed (fix #311) fa la vera deduplicazione e può essere committata. Sezione "Team workflow" aggiunta al README in v0.4.19.
- **keyword/entità:** fakesmallcc · build artifact · LLM non-determinism · manifest.json · cache #311 · CI · v0.4.19

### Issue #422 — KeyError 'total_files' in cluster-only (chiusa, fix v0.4.21)
- **source_id:** 130d77c4-c30d-43f0-bc81-b3d3e92d72fa  ·  **tipo:** url
- **sostanza:** fitliferepo: `cluster-only` salta la fase detect, quindi lo stats dict non contiene `total_files` e report.py crasha alla generazione del markdown. graph.json viene scritto correttamente prima del crash (il rebuild funziona, fallisce solo il report). Workaround: usare `graphify update`. Fixato in v0.4.21. neo1777 ha menzionato questa issue collegandola a #934 (FileNotFoundError, stesso modulo cluster-only).
- **keyword/entità:** fitliferepo · cluster-only · KeyError total_files · report.py · neo1777 · #934 · v0.4.21

### MCP — Architecture overview (background, non graphify-specifico)
- **source_id:** 55c11b30-a794-4a75-92cc-c936cacb34f6  ·  **tipo:** url
- **sostanza:** Pagina ufficiale modelcontextprotocol.io sull'architettura MCP: modello client-server (Host/Client/Server), due layer (data layer JSON-RPC 2.0 e transport layer stdio/Streamable HTTP), e i primitivi server (tools, resources, prompts) e client (sampling, elicitation, logging). Include walkthrough JSON-RPC di initialize, tools/list, tools/call e notifiche. Materiale di background, non parla di graphify.
- **keyword/entità:** MCP · JSON-RPC 2.0 · host/client/server · tools/resources/prompts · stdio · Streamable HTTP

### MCP — Neo4j integrations (background)
- **source_id:** c5c0c68e-2fa2-42c5-9bca-b2a69e23772e  ·  **tipo:** url
- **sostanza:** Developer guide Neo4j sulle integrazioni MCP: panoramica del protocollo (Anthropic, nov 2024) e catalogo dei server Neo4j — MCP ufficiale (schema, Cypher read/write, GDS), mcp-neo4j-cypher, mcp-neo4j-memory, Aura Manager, Data-Modeling, GDS-Agent (algoritmi di centralità/path/community detection inclusi Leiden e Louvain), Sandbox, Google MCP Toolbox. Background, non graphify-specifico.
- **keyword/entità:** Neo4j · Cypher · GDS-Agent · mcp-neo4j-memory · Aura · Leiden/Louvain · Google MCP Toolbox

### README @ v8 — safishamsi/graphify (repo principale)
- **source_id:** 3a25291e-3129-4e9f-92b9-2b4a8be7dd7a  ·  **tipo:** url
- **sostanza:** README v8 del repo (vista corti.com): `/graphify` mappa un progetto in un knowledge graph (graph.html, GRAPH_REPORT.md, graph.json). Branch v8, 54.4k stelle, 5.8k fork, 554 commit, ultima release v0.8.20. Pacchetto PyPI `graphifyy` (doppia y), CLI `graphify`. Supporta 32 linguaggi e 18+ piattaforme; estrazione codice locale via tree-sitter, video/audio via faster-whisper, docs via LLM. Sezioni: extra opzionali, MCP server, hook git, team setup, troubleshooting, layer enterprise Penpax.
- **keyword/entità:** README v8 · graphifyy · 54.4k stars · v0.8.20 · tree-sitter · faster-whisper · MCP · Penpax · 32 linguaggi

### Rapporto Graphify e neo1777 — aggiornato post fact-check (2026-05-27)
- **source_id:** b80cb9fb-d5f9-439d-aee8-21b7c7607a3c  ·  **tipo:** text
- **sostanza:** Rapporto consolidato (sostituisce il research log iniziale) che corregge il primo report AI con i fatti dalle 12 fonti: panoramica graphify, i tre pass, community detection Leiden + confidence tags, benchmark token (71.5x/5.4x/~1x), MCP e three-tier integration (#146/#532). Su neo1777: ha un fork (~508 commit), ha aperto Issue #919 + una PR "accettata", collegato a #934 via #422, "non contributor per un soffio". Segnala discrepanza linguaggi 25 (docs) vs 32 (README).
- **keyword/entità:** fact-check · neo1777 · Issue #919 · fork 508 commit · 71.5x · three-tier · 25 vs 32 linguaggi · Safi Shamsi

### Testo incollato — research log iniziale Neo + AI (rimpiazzato da v.aggiornata)
- **source_id:** 1339d3d8-4b72-44b3-896d-eca4ac4a4317  ·  **tipo:** text
- **sostanza:** JSON di una sessione "advanced-deep-research" (request payload con messaggi user/assistant). Contiene il primo rapporto AI su graphify e neo1777, poi corretto: afferma erroneamente 63 contributori e che neo1777 "non ha aperto issue/PR né commenti". Neo replica nell'ultimo messaggio di aver fatto la Issue #919 e una PR "accettata", "non contributor per un soffio". Rimpiazzato dalla versione fact-checked.
- **keyword/entità:** research log · deep-research JSON · 63 contributori (errato) · neo1777 · Issue #919 · Karpathy

### docs/how-it-works.md @ v8 — documentazione ufficiale tre passaggi
- **source_id:** cb4093b9-1695-498f-8002-aeff23a75b49  ·  **tipo:** url
- **sostanza:** Documentazione ufficiale v8 dei tre pass: Pass 1 code structure via tree-sitter (25 linguaggi, locale, no API; SQL deterministico; Pass 3 skippato se solo codice), Pass 2 video/audio via faster-whisper (prompt seedato sui god nodes), Pass 3 docs/papers/images via subagenti Claude. Community detection Leiden (no embedding); confidence tags EXTRACTED/INFERRED (rubrica 0.55-0.95)/AMBIGUOUS; benchmark 71.5x/5.4x/~1x; cache SHA256; formato graph.json NetworkX node-link.
- **keyword/entità:** how-it-works · 3 pass · tree-sitter (25 lang) · faster-whisper · Leiden · confidence rubric · 71.5x · NetworkX node-link
