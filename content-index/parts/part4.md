# Indice di contenuto profondo — account NotebookLM 1777 — parte 4/6
> Sessione 2026-06-01 · provenienza/metodo nella parte 1/6 · 975 voci totali su 48 notebook · layer di contenuto complementare al catalogo strutturale.

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

---

## 5fa9ddc5 · UltraPlan Graphify Meta Layer v4: Recursive Knowledge Graph Engine — [graphify,metodo] · 1 fonte

### ultraplan_graphify_meta_layer_v4.md
- **source_id:** 5455798f · **tipo:** text
- **sostanza:** Documento di specifica (15.359 caratteri) per UltraPlan Graphify Meta Layer v4, un sistema agent swarm per la costruzione ricorsiva di grafi di conoscenza. Definisce 5 layer di sistema (Research, Builder, Critic, Controller, Meta), 4 tipi di memoria (GG-MEM globale, Agent, Episodica, Strutturale), logica di saturazione come criterio di stop, modello tipizzato di nodi/archi, e output offline in formato YAML. Il sistema è progettato per operare in modo autonomo e ricorsivo su un dominio di conoscenza.
- **keyword/entità:** UltraPlan · Graphify · agent swarm · knowledge graph · GG-MEM · memoria episodica · saturazione · YAML · Research layer · Builder layer · Critic layer · Controller layer · Meta layer

---

## 62642a01 · mcp1777 — Lavoro vivo — [mcp] · 13 fonti

### 00 — Spirito e contesto OSS1777 (chi, cosa, metodo)
- **source_id:** fce8a55b · **tipo:** text
- **sostanza:** Kickoff prompt OSS1777 (2K). Definisce chi è Neo, cos'è OSS1777 (graphify arco #919→#934→PR#942→ondata 2), il metodo non negoziabile (verifica vera, fatti vs inferenze, no sycophancy), il mood 360° poi focus.
- **keyword/entità:** OSS1777 · graphify · PR#942 · ondata 2 · metodo · kickoff

### 01 — Goal e prompt di ripresa sessione
- **source_id:** c7d0296c · **tipo:** text
- **sostanza:** Frase-goal mcp1777 e prompt operativo di ripresa sessione (3K). Documenta /goal come comando built-in v2.1.139+, altri comandi (/compact, /btw, /ultraplan, /ultrareview, /batch), ENV vars, modalità permessi.
- **keyword/entità:** /goal · /compact · /btw · /ultraplan · ENV vars · permessi

### 02 — Decisioni da prendere (questionario per Neo)
- **source_id:** 815ac130 · **tipo:** text
- **sostanza:** Questionario strutturato per Neo (3K). Sezioni A1-A4 (dove vive v2/, cosa tenere, linguaggio bot, tunneling), B memoria, C nuove integrazioni, D definizione "fatto", E operatività NB, F decisioni già prese.
- **keyword/entità:** A1-A4 · v2/ · tunneling · memoria · decisioni · questionario

### 03 — Come attivare NotebookLM (MCP)
- **source_id:** 5442c836 · **tipo:** text
- **sostanza:** Procedura 6 passi per attivare NotebookLM-MCP (4K): pipx install → nlm setup → nlm login → nlm doctor → claude mcp add → verifica. HTTP + tunnel per claude.ai. Vincoli: Pro/Max, URL effimero, esposizione pubblica, Chrome singolo.
- **keyword/entità:** nlm login · nlm doctor · pipx · cloudflared · chrome-profiles · Pro/Max

### 04 — Permessi Claude Code (storico e configurazione attuale)
- **source_id:** 4c6709f3 · **tipo:** text
- **sostanza:** Configurazione settings.local.json con defaultMode: "acceptEdits" (3K). Allow: Bash/Edit/Write/Read/mcp__notebooklm-mcp. Storico dei blocchi permessi, trade-off Bash senza filtro.
- **keyword/entità:** settings.local.json · acceptEdits · dontAsk · DISALLOWED_TOOLS · permessi

### 05 — Distillato delle chat precedenti
- **source_id:** d3b6a091 · **tipo:** text
- **sostanza:** Errori corretti e fatti verificati (5K). "No approval received" è prompt UI non bug, test confini Write/workspace_*, Mondo A/B, /goal esiste (correzione), file chiave baseline, decisioni non rinegoziabili.
- **keyword/entità:** No approval received · workspace_* · Mondo A/B · /goal · baseline · distillato

### 06 — Piano operativo 3 filoni (priorità A graphify, B sync OSS1777, C mcp1777)
- **source_id:** 1cf47dbe · **tipo:** text
- **sostanza:** Piano a 3 filoni (6K): A = graphify (priorità 1, pronto), B = sync OSS1777 (priorità 2), C = rifacimento mcp1777 (bloccato su A1-A4). Vincolo MCP isolato. Skill driver palantir1777. Pattern /goal per ciascun filone.
- **keyword/entità:** filone A · filone B · filone C · palantir1777 · MCP isolato · /goal pattern

### 07 — Come usare /goal e comandi autonomi (sintesi dal NB Claude Code)
- **source_id:** f7ff30f4 · **tipo:** text
- **sostanza:** Sintesi dell'architettura /goal da NB Command Architecture (5K). Esecutore + Evaluator Haiku, sintassi, 4 elementi condizione efficace, errori comuni (loop per obiettivi vaghi), interazioni con altri comandi, hook, ENV vars, pattern operativi.
- **keyword/entità:** /goal · Haiku evaluator · loop infinito · hook · ENV vars · architettura

### TICK 2026-05-29 23:05 — snapshot canale
- **source_id:** 15809296 · **tipo:** text
- **sostanza:** Snapshot automatico tick canale Neo↔Claude (882 char). Stato: nessun messaggio da Neo, 0 NB variati, 4 pendenze stazionarie dal 27/05 (A1-A4, formato, bug atlante, manifesto skill). Stack mcp1777 verificato attivo.
- **keyword/entità:** tick · snapshot · 4 pendenze · A1-A4 · bug atlante · canale asincrono

### TICK 2026-05-31 (PROMPT1) — stato repo verificato + indicizzazione 3 NB
- **source_id:** 48f12983 · **tipo:** text
- **sostanza:** Tick PROMPT1 (2K). Verifica live del repo mcp1777/notebookllm1777/: bot.py (8.6K), gateway.py (7.8K, FULL_ACCESS=True), archive-mcp NUOVO (archive.db 126MB, 821 conv FTS5). Porte attive: 8000/8001/8002/8080/9000. Decisioni aperte per PROMPT2.
- **keyword/entità:** archive-mcp · archive.db · FTS5 · FULL_ACCESS · 821 conversazioni · PROMPT1

### TICK 2026-05-31 (PROMPT2) — pacchetto installabile systemd creato
- **source_id:** 3eabaabe · **tipo:** text
- **sostanza:** Tick PROMPT2 (2K). Decisioni chiuse: tutti e 3 i bot nel pacchetto, systemd non Docker, Kilo come supervisore processi. Creato mcp1777/pacchetto-mcp1777/ con install.sh, start-stack.sh, mcp1777.service, health-check.sh. Dry-run 11/11 OK.
- **keyword/entità:** pacchetto-mcp1777 · systemd · install.sh · health-check.sh · lingering · PROMPT2

### TICK 2026-05-31 10:47 — snapshot canale
- **source_id:** 552705e3 · **tipo:** text
- **sostanza:** Snapshot cron tick (484 char). Nessun messaggio da Neo, 0 NB variati, 4 pendenze aperte. Infra mcp1777 attiva, stack stabile.
- **keyword/entità:** tick · cron · stack stabile · 4 pendenze · snapshot

### TICK 2026-05-31 23:45 — snapshot canale
- **source_id:** 47bed889 · **tipo:** text
- **sostanza:** Snapshot cron tick notturno (406 char). Nessun messaggio da Neo, 0 NB variati, 4 pendenze stazionarie dal 27/05. Tutte le porte e il bot attivi.
- **keyword/entità:** tick · cron notturno · 4 pendenze · porte attive · bot

---

## 6dcb5f46 · Graphify — GitHub: issue, release e tooling — [graphify] · 27 fonti

### (More) serious bugs · Issue #14
- **source_id:** 22df64b2 · **tipo:** url
- **sostanza:** Issue GitHub che riporta 8 problemi di sicurezza/bug: SSRF bypass via urllib in _fetch_tweet, Cypher injection Neo4j via string interpolation, stored XSS via label innerHTML non sanificati, graph_diff manca archi in grafi non orientati per key ordering arbitrario, watch mode O(n), hook uninstall naive split, _rebuild_code legge tutti i file solo per contare parole, semantic cache collision su contenuti identici. Saif ha fixato tutti e 6 quelli reali (ha respinto punti 3 e 15).
- **keyword/entità:** issue #14 · SSRF · Cypher injection · XSS · graph_diff · watch mode · semantic cache · security bugs · Saif

### Claude — personalizzazione 1 (immagine)
- **source_id:** e16b1372 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 2 (immagine)
- **source_id:** c064d788 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 3 (immagine)
- **source_id:** d24c903c · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 4 (immagine)
- **source_id:** 43676857 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 5 (immagine)
- **source_id:** 5b0b0627 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 6 (immagine)
- **source_id:** 45ea31f2 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 7 (immagine)
- **source_id:** ac40d520 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 8 (immagine)
- **source_id:** 835a4d1e · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 9 (immagine)
- **source_id:** d5afe00d · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 10 (immagine)
- **source_id:** 02e6e775 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 11 (immagine)
- **source_id:** 1eccaaf6 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 12 (immagine)
- **source_id:** ded34da9 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 13 (immagine)
- **source_id:** 50190f18 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### Claude — personalizzazione 14 (immagine)
- **source_id:** 838ced50 · **tipo:** image
- **sostanza:** Screenshot UI personalizzazione Claude (googleusercontent URL, 225 chars).
- **keyword/entità:** Claude UI · personalizzazione · screenshot

### GitHub - antirez/ds4
- **source_id:** 834685b2 · **tipo:** url
- **sostanza:** Pagina GitHub del motore di inferenza locale DeepSeek 4 Flash per Metal e CUDA, creato da antirez (creatore di Redis). Implementazione in C con supporto Metal (Apple Silicon) e CUDA (NVIDIA). Design orientato alla performance minimale senza dipendenze pesanti.
- **keyword/entità:** DeepSeek 4 Flash · antirez · Redis · Metal · CUDA · inferenza locale · C · Apple Silicon

### GitHub - safishamsi/graphify (README completo)
- **source_id:** 4e2fdeb3 · **tipo:** url
- **sostanza:** README completo di graphify v0.8 branch. 54.4k stelle, 5.8k fork. Installazione: `uv tool install graphifyy` / `pipx install graphifyy` + `graphify install`. Supporta 30+ piattaforme (Claude Code, Codex, OpenCode, Cursor, Gemini CLI, ecc.) e 32 linguaggi via tree-sitter (AST locale, nessuna API). Output: graph.html, GRAPH_REPORT.md, graph.json. Comandi: /graphify, --update, --cluster-only, --resolution, --exclude-hubs, query, path, explain, prs. Privacy: codice processato localmente, nessuna telemetria.
- **keyword/entità:** graphify · safishamsi · 54k stelle · graphifyy · tree-sitter · AST · --cluster-only · --exclude-hubs · --resolution · privacy

### GitHub: issue, release e tooling — immagine 1
- **source_id:** 1b1ef8da · **tipo:** image
- **sostanza:** Immagine correlata al notebook GitHub issue/release/tooling (googleusercontent URL, 223 chars).
- **keyword/entità:** graphify · tooling · immagine

### Graphify + code-review-graph: Build a Self-Updating Knowledge Graph (DEV Community)
- **source_id:** ad1a03b2 · **tipo:** url
- **sostanza:** Articolo DEV Community (~117k chars) su integrazione graphify con workflow di code review per Claude Code e altri agenti AI. Descrive come costruire un knowledge graph auto-aggiornante combinando graphify con code-review-graph. Include esempi pratici di query sul grafo durante le review, pattern di integrazione con CI/CD, e uso del grafo per contesto arrichito nelle sessioni di coding.
- **keyword/entità:** DEV Community · code-review-graph · knowledge graph · auto-aggiornante · Claude Code · CI/CD · code review · integrazione

### Graphify: Build a Knowledge Graph... - GoPenAI
- **source_id:** 80b0363b · **tipo:** url
- **sostanza:** Pagina bloccata da Cloudflare (508 chars di solo testo verifica sicurezza). Contenuto effettivo dell'articolo non accessibile.
- **keyword/entità:** GoPenAI · Cloudflare · bloccato · inaccessibile

### Graphify: Instant Knowledge Graph for Claude Code/Antigravity (FREE) — YouTube
- **source_id:** e1c5fc01 · **tipo:** url
- **sostanza:** Trascrizione video YouTube (~10k chars) che dimostra graphify su progetto browser-use (441 nodi, 20900 archi, 185 comunità). Test risparmio token: 10 domande, sessione senza graphify=120k token, con graphify=113k (~8% riduzione, non 71.5x). Spiega che il benchmark 71.5x è contro caricamento naive di 52 file (irrealistico). Valore reale: meno letture file in direzione sbagliata, risposte migliori al primo messaggio. Funziona anche per vault ricerca, PDF, cartelle markdown.
- **keyword/entità:** YouTube · browser-use · 441 nodi · token savings · 71.5x benchmark · 8% riduzione · knowledge graph · vault ricerca

### Issues · safishamsi/graphify - GitHub
- **source_id:** 268457ec · **tipo:** url
- **sostanza:** Pagina delle issue GitHub con 110 issue aperte. Più recenti: race condition post-commit hook su graph.json (#1037), crash wiki su grafi merged (#1035), mismatch AST/semantic node ID (#1033), command too long (#1032), Copilot stop durante processing semantico (#1031), e numerose feature request.
- **keyword/entità:** GitHub issues · 110 open · #1037 post-commit hook · #1035 wiki crash · #1033 node ID · race condition · graphify

### Releases · safishamsi/graphify - GitHub
- **source_id:** 470b3117 · **tipo:** url
- **sostanza:** Changelog release da v0.8.9 a v0.8.20. Release chiave: v0.8.10 (fix rounding threshold coesione issue #919, feat --resolution e --exclude-hubs), v0.8.11 (LLM empty choices guard), v0.8.13 (node ID collision fixes), v0.8.14 (wiki crash fix), v0.8.16 (CJK/Unicode label fix), v0.8.17 (phantom edges cross-language), v0.8.18 (semantic context tags sugli archi), v0.8.19 (.NET support, segmentazione cinese), v0.8.20 (ghost nodes fix, XML DoS hardening, MCP config extractor).
- **keyword/entità:** releases · v0.8.10 · v0.8.20 · issue #919 · --resolution · --exclude-hubs · CJK · .NET · MCP config extractor · ghost nodes

### graphify update is O(V×E) on large repos due to betweenness_centrality · Issue #341
- **source_id:** 4e375245 · **tipo:** url
- **sostanza:** Issue #341 sul problema di performance O(V×E) del calcolo betweenness_centrality in suggest_questions su repository di grandi dimensioni. Il calcolo ha complessità quadratica rispetto ai nodi e agli archi, rendendo l'operazione molto lenta su grafi grandi.
- **keyword/entità:** issue #341 · betweenness_centrality · O(V×E) · performance · suggest_questions · grafi grandi · complessità

### safishamsi/graphify - Issues (variante)
- **source_id:** b71a9db9 · **tipo:** url
- **sostanza:** Altra pagina delle issue di safishamsi/graphify su GitHub (variante/duplicato di 268457ec). Elenca issue aperte del progetto graphify.
- **keyword/entità:** GitHub issues · graphify · safishamsi · duplicato

### warning: skill is from graphify 0.3.21... · Issue #178
- **source_id:** 00b72bec · **tipo:** url
- **sostanza:** Issue #178 sul warning di versione mismatch quando la versione di graphify installata differisce da quella del file skill. Fix: `uv tool upgrade graphifyy` + `graphify install` per aggiornare sia il tool che il file skill.
- **keyword/entità:** issue #178 · skill version mismatch · warning · uv tool upgrade · graphifyy · graphify install

### «INIZIO PROMPT — KICKOFF OSS1777»
- **source_id:** 52f2d844 · **tipo:** text
- **sostanza:** Documento del prompt di kickoff per il progetto OSS1777. Definisce il punto di partenza operativo del progetto di contribuzione OSS a graphify.
- **keyword/entità:** kickoff · OSS1777 · prompt · punto di partenza · contribuzione OSS

---

## 6f8dbb0c · Graphify and Mazinga AI: The New Agentic Software Ecosystem — [graphify] · 2 fonti

### Ricerca Progetto, Graphify, Mazinga AI.md
- **source_id:** 54977c58-ded1-40d9-a58f-9dc91f5c20df · **tipo:** text (report ricerca, ~36k char)
- **sostanza:** Rapporto di ricerca architetturale su tre direttrici intrecciate: (1) qualità tecnica
  dei contributi al repo graphify di Safi Shamsi (path Windows, binari python su Ubuntu, dipendenze
  leiden) e tesi dell'assenza di bias linguistico; (2) il paradigma "Graphify-style" — AST via
  tree-sitter, algoritmo di Leiden per community detection, token economy (-71.5×); (3) "Mazinga AI"
  come orchestrazione MCP per GitHub (51+ tool, Context Gap, MCP+Skills). Con bibliografia e issue reali.
- **keyword/entità:** graphify · Safi Shamsi · tree-sitter/AST/LST · algoritmo di Leiden · knowledge graph ·
  MCP GitHub · Context Gap · MCP+Skills · issue #581/#475/#4195 · Mazinga AI

### mi hai detto__'Ho terminato la ricerca. Non esita….md
- **source_id:** 6bfcfd6c-24c6-4a5c-9b66-ea9860f27556 · **tipo:** text (autovalutazione metodo, ~9.9k char)
- **sostanza:** Rapporto di autovalutazione della metodologia di ricerca che ha prodotto il report
  Graphify/Mazinga: confronto Piano 1 (ricettivo, silos isolati) vs Piano 2 (strutturato, 8 punti,
  isolamento del bias linguistico, decostruzione AST/Leiden/token, analisi sicurezza MCP). Spiega
  perché il piano evoluto ha prodotto un risultato superiore, punti di forza/debolezza e raccomandazioni
  (OS Matrix, layer esecuzione vs configurazione, tracciamento bug di regressione).
- **keyword/entità:** metodologia di ricerca · Piano 1 vs Piano 2 · bias linguistico · OS Matrix ·
  corner cases · Issue #874 caching · autovalutazione · raccomandazioni metodo

---

## 71fa55d2 · rinominare file — [metodo] · 14 fonti

### AGENTS.md
- **source_id:** 09aa64b9 · **tipo:** text
- **sostanza:** Documento di architettura della peer-review platform MVP. Stack: Next.js 16, Tailwind CSS v4, Zustand senza API routes (mock data in useStore.ts). Segnala import paths rotti (@/* sotto Turbopack) e path relativi come workaround.
- **keyword/entità:** Next.js 16 · Tailwind CSS v4 · Zustand · Turbopack · peer-review platform

### analisi_file_dir_work_preliminare.md
- **source_id:** 61e41875 · **tipo:** text
- **sostanza:** Analisi preliminare di 81 capitoli del progetto BOOK1777 (182K caratteri). Triage file con 39 insight in 7 temi strutturali. Gerarchia operativa per fasi: A (FRAMING v2.0 da bloccare), B/C/D/E dipendono da A.
- **keyword/entità:** BOOK1777 · 81 capitoli · FRAMING v2.0 · 39 insight · gerarchia fasi

### app_protocol.txt
- **source_id:** 008df314 · **tipo:** text
- **sostanza:** Prompt a Gemini per creare e verificare Protocol Nexus Safety-Critical Simulator. Definisce 7 scenari didattici (SBAR, Swiss Cheese, Just Culture, HRO, Drift, Checklist, CRM) e un leaderboard Firebase Firestore.
- **keyword/entità:** Protocol Nexus · Gemini · Firebase Firestore · SBAR · Swiss Cheese · Just Culture

### app_protocol_code_chat.txt
- **source_id:** ce3b5641 · **tipo:** text
- **sostanza:** Chat Gemini con espansioni e tutorial sul codice (63K). Contiene README e TECHNICAL_DOCS dell'app Protocol Nexus v3.0.
- **keyword/entità:** Protocol Nexus v3.0 · README · TECHNICAL_DOCS · Gemini chat · espansioni

### app_protocol_code_example.txt
- **source_id:** a55c935d · **tipo:** text
- **sostanza:** Codice React completo di Protocol Nexus v3.0 (38K). Firebase Auth + Firestore, 7 scenari safety, motore cascade con stati: landing, playing, feedback, panic, report, leaderboard.
- **keyword/entità:** React · Firebase Auth · Firestore · motore cascade · leaderboard

### brainstorming_visione.md
- **source_id:** f3b78600 · **tipo:** text
- **sostanza:** Visione del progetto BOOK1777 (16K). Il libro è il gioco stesso: 6 decisioni formalizzate, metafora Mandelbrot accennata. Volume 1 definito come gioco AAA completo al 100%.
- **keyword/entità:** BOOK1777 · Mandelbrot · gioco AAA · 6 decisioni · visione

### brainstorming_visione_2.md
- **source_id:** 9baea480 · **tipo:** text
- **sostanza:** Opera frattale Mandelbrot (15K). Completezza 100% a ogni scala: Progetto → Opera → Gioco → Capitoli. AI-readability come proprietà strutturale. Voce consolidata stile-voce-A dagli 81 capitoli.
- **keyword/entità:** opera frattale · AI-readability · completezza scalare · stile-voce-A · 81 capitoli

### chat_mappa_metodo.md
- **source_id:** b5a24f44 · **tipo:** text
- **sostanza:** Chat NotebookLM su Project OSS1777 e The Ontological Method (152K). Contribution map graphify, fase 4 chiusura operativa con PIANO_kit. Fonte di verità primaria del metodo.
- **keyword/entità:** OSS1777 · graphify · PIANO_kit · Ontological Method · contribution map

### chat_notebookllm_guida_tecnica.md
- **source_id:** 2da152ee · **tipo:** text
- **sostanza:** Chat NB su Project OSS1777 con 22 fonti (file di grandi dimensioni). Analisi graphify, Metodo Perplexity Pro, PIANO_kit come framework operativo, ciclo ricorsivo 4 step, NotebookLM come Auditor di Verità.
- **keyword/entità:** Perplexity Pro · PIANO_kit · ciclo 4 step · Auditor di Verità · graphify

### minecraft_research.md
- **source_id:** 3eef0bf3 · **tipo:** text
- **sostanza:** Ricerca approfondita Minecraft (43K). Java vs Bedrock, modding (Forge/NeoForge/Fabric/Quilt), multiplayer/Realms, sicurezza famiglie, progressione pedagogica, aggiornamenti 2025-2026: Mounts of Mayhem, Tiny Takeover, versioning 26.x.
- **keyword/entità:** Minecraft · Forge · NeoForge · Fabric · Bedrock · Mounts of Mayhem

### rinominare file — immagine 1
- **source_id:** 10f408bb · **tipo:** image
- **sostanza:** Fonte di tipo immagine (URL googleusercontent). Contenuto visivo non accessibile via source_get_content; proviene dall'upload diretto nel notebook "rinominare file".
- **keyword/entità:** immagine · googleusercontent · upload diretto

### promp_analisi_claude.txt
- **source_id:** 89654305 · **tipo:** text
- **sostanza:** Prompt di audit per il progetto marzio1777 (PWA) in 4 fasi: Documentazione, Storia Git, Lettura codice, Report finale con 10 sezioni. Template operativo riutilizzabile.
- **keyword/entità:** marzio1777 · PWA · audit · Storia Git · 4 fasi · 10 sezioni

### testo1.md
- **source_id:** c63b3b85 · **tipo:** text
- **sostanza:** Analisi OSS1777 come bussola strategica (3K). Skill tecniche graphify, Metodo Perplexity Pro, ciclo 4 step, NotebookLM come auditor di verità. Stima valore workflow: "$15.000 in consulenze" con $60 di spesa.
- **keyword/entità:** graphify · Perplexity Pro · $15.000 · auditor di verità · OSS1777

### token_claudecode.txt
- **source_id:** 26a27e18 · **tipo:** text
- **sostanza:** File contenente un token OAuth di Claude Code (350 caratteri). Credenziale di accesso con validità annuale. Il token non viene riprodotto in questo indice.
- **keyword/entità:** OAuth token · Claude Code · credenziale · sk-ant-oat01 · sensibile

---

## 77ed9084 · web2md1777 — memoria del compito — [estrazione] · 7 fonti

### CLAUDE.md
- **source_id:** bdfd16ed-5787-4efc-96d4-ce5e50e63b6e · **tipo:** text (~6.8k char)
- **sostanza:** Guida per Claude Code al repo web2md1777 (web app + CLI TypeScript): comandi npm (dev/cli/
  build/test via tsx), architettura "una pipeline, tre entry point" (server.ts/cli.ts/test_validation.ts),
  pattern adapter con registry first-match, due famiglie (API-backed e HTML-based), fetcher fallback
  (direct→Jina HTML→Jina Markdown), rendering Markdown, e gotchas (import .js, stringhe IT, SSRF guard incompleto).
- **keyword/entità:** TypeScript · tsx · adapter pattern · registry · Jina fallback · Readability/Turndown ·
  IndexedDB/Dexie · SSRF guard · ExtractedDocument

### README.md
- **source_id:** 5d205455-4d8a-435c-8c3e-29db6b6ae319 · **tipo:** text (~2.9k char)
- **sostanza:** README pubblico di web2md1777: cattura pagine web/chat AI/discussioni in Markdown con
  YAML front matter. Elenca i 9 adapter (Generic, GitHub, Wikipedia, ClaudeShare, Gist, HN, Reddit, SO,
  Mastodon), fallback chain, commenti threaded come blockquote annidati, history local-only (IndexedDB),
  quick start, architettura e roadmap (CLI npm, MCP server, browser extension, AI summarization). Licenza MIT.
- **keyword/entità:** 9 adapter · YAML front matter · threaded comments · Jina · roadmap MCP/extension · MIT

### Sintesi autoritativa — web2md1777 (28 mag 2026)
- **source_id:** 7174b441-48e4-4f21-b6a7-09310b9a8907 · **tipo:** text (~6k char)
- **sostanza:** Sintesi "autoritativa" compilata da Claude Opus 4.7 per dare una vista non confusa sul
  progetto: cos'è davvero (TS, NON Dart/Python/Graphify), 9 adapter, stato al 28 mag (29/29 test, repo
  claimato non verificato), decisioni aperte, e — cruciale — un elenco di DISCREPANZE nei notebook
  esistenti da non propagare (index1777 lo dice "modulo di Graphify" → falso; tree-sitter → falso; FLUTTER_MIGRATION_BRIEF → non esiste).
- **keyword/entità:** sintesi autoritativa · anti-confusione · NON Graphify · discrepanze notebook ·
  29 test · publish-goal · path canonici · Opus 4.7

### dart-multiplatform-direction.md
- **source_id:** 5d5f1b44-108b-4560-95c8-9da5495f9a7a · **tipo:** text (~1.2k char, memory node)
- **sostanza:** Nota di memoria sull'interesse di Neo a spostare web2md1777 "il più possibile verso Dart,
  multiplatform". Take architetturale onesto: l'app esiste grazie al fetcher server-side che bypassa CORS/
  bot-protection (no equivalenti Dart nativi); una rewrite pura in Dart sposterebbe la parte facile lasciando
  la parte difficile. Path consigliato: tenere il server TS come API, aggiungere client Flutter dopo se serve.
- **keyword/entità:** Dart/Flutter · rewrite vs additive client · CORS/Cloudflare · server TS come API · publish-goal

### publish-goal.md
- **source_id:** d81c8c99-6423-41b9-b68c-3d878e041ace · **tipo:** text (~0.9k char, memory node)
- **sostanza:** Nota di memoria sul goal: portare web2md1777 da export AI Studio a progetto open source
  pubblico ben ospitato, ottimizzato per il massimo di GitHub stars. Repo claimato a github.com/neo1777/
  web2md1777 (non verificato). Stato 24 mag: pulito (0 vuln), git su main, 9 adapter, 29/29 test verdi. Aperti:
  hosting, lingua messaggi, gh auth login, CI, screenshot.
- **keyword/entità:** publish goal · GitHub stars · open source · main branch · 9 adapter · decisioni aperte

### web2md1777_giro3_prompt.md
- **source_id:** 11ebca03-05c5-4fa8-a1fc-9fa56b73f3e6 · **tipo:** text (~18.5k char, prompt AI Studio)
- **sostanza:** Master prompt "Giro 3 di 3" per Gemini Pro in AI Studio: aggiungere StackOverflowAdapter +
  MastodonAdapter alla codebase. Specifica URL pattern, endpoint API (Stack Exchange v2.3, Mastodon/ActivityPub),
  composizione body, ricostruzione albero reply, messaggi italiani verbatim, update registry/types/test/README,
  e regole di metodo (verbatim IT, mostra output, no silent fixes). Ultimo giro prima della migrazione a Claude Code.
- **keyword/entità:** Giro 3 · StackOverflowAdapter · MastodonAdapter · Stack Exchange API · ActivityPub ·
  reply tree · messaggi verbatim · checkpoint protocol

### web2md1777_v2_fase2_prompt.md
- **source_id:** 7b5560da-78f4-414e-8741-12117638d911 · **tipo:** text (~27.9k char, prompt AI Studio)
- **sostanza:** Master prompt "Fase 2" per aggiungere GistAdapter + HNAdapter + RedditAdapter (sorgenti con
  commenti via API). Dettaglia endpoint (GitHub Gist REST, HN Firebase ricorsivo, Reddit .json), 13 Design
  Decision (ordine registry, esclusione gist da GitHub, concurrency BFS, depth cap 50, commenti cancellati,
  messaggi IT verbatim), 4 checkpoint con test E2E, out-of-scope e acceptance criteria (20 PASS).
- **keyword/entità:** Fase 2 · Gist/HN/Reddit adapter · Firebase API · Reddit .json · DD1-DD13 · depth cap 50 ·
  checkpoint CP1-CP4 · acceptance 20 PASS

---

## 79c5aa46 · ricerca-esterna — malware Android & RE — [ricerca-esterna] · 3 fonti

---

### Android App Reverse Engineering 101 - Maddie Stone
- **source_id:** 6d42a60a-de75-4e3a-ad91-c0d1e299a873 · **tipo:** url
- **sostanza:** Workshop introduttivo al reverse engineering di applicazioni Android tramite analisi statica, sviluppato da Maddie Stone di Google Project Zero. Copre fondamentali di APK, DEX bytecode, librerie native, e offuscamento con esercizi pratici. Strumenti usati: jadx (decompiler Dalvik), Ghidra (disassembler/decompiler ARM).
- **keyword/entità:** Android RE · APK · DEX bytecode · jadx · Ghidra · analisi statica · native libraries · obfuscation · Maddie Stone

---

### Automated Forensic Analysis of Mobile Applications on Android Devices - Digital Commons @ USF
- **source_id:** 22c34393-7fdb-41f4-a39b-e68f4fda1c28 · **tipo:** url
- **sostanza:** Articolo DFRWS 2018 (USF + UESTC) su un sistema automatizzato di analisi forense di app Android. Propone una pipeline di analisi statica che estrae metadata, permessi, componenti e codice da APK; analizza bytecode DEX e librerie native. Orientato all'identificazione di comportamenti malevoli senza esecuzione dell'app.
- **keyword/entità:** Android forensics · APK · DEX · analisi statica · DFRWS 2018 · automazione · permessi · Fengguo Wei · USF · UESTC

---

### Enhancing android malware detection explainability through function call graph APIs - UniCA IRIS
- **source_id:** 8df09c5c-db2f-4a94-b723-d20ca89d16b9 · **tipo:** url
- **sostanza:** Paper (Journal of Information Security and Applications, 2024, Università di Cagliari) su un approccio spiegabile per il rilevamento di malware Android basato su analisi statica. La novità consiste nell'uso di API estratte dal Function Call Graph (FCG) come feature per modelli di machine learning, con spiegabilità delle decisioni via taint analysis e feature importance. Propone selezione mirata delle API più rilevanti alla maliciosità.
- **keyword/entità:** Android malware · Function Call Graph · FCG · explainability · machine learning · deep learning · API features · taint analysis · UniCA · JISA 2024 · Diego Soi · Davide Maiorca

---

## 7f8aa086 · Memetic Ecosystem Atlas 2026: Taxonomy of Digital Folklore — [cultura] · 2 fonti

### Atlas-2026.md
- **source_id:** 593ab117-9f53-4c93-b53c-231821b016fe · **tipo:** text (~10k char)
- **sostanza:** Atlante/tassonomia estesa della cultura memetica internet-native 2026: il meme come
  linguaggio, rituale, compressione culturale, segnale tribale, arma algoritmica. Contiene tassonomia
  principale (Expression Systems, Aesthetic Cores, Irony Layers, AI Memetics…), tabelle dettagliate
  per elemento (origine, hype, stato 2026), 8 livelli di ironia, lifecycle del meme, ecosistemi per
  piattaforma, schema metadata YAML, glossario e previsioni 2026-2030. Formato per wiki/Obsidian/LLM ingestion.
- **keyword/entità:** folklore digitale · brainrot · wojak/pepe · AI slop · weirdcore/analog horror ·
  irony layers · meme lifecycle · post-ironia · memetic warfare · schema metadata

### emoticon testuali ASCII / Kaomoji
- **source_id:** 8783a07f-85e6-41dd-8157-58271f37e16d · **tipo:** text (~3.9k char, raw list)
- **sostanza:** Lista grezza (raw list) di ~200 voci/formati memetici e sistemi espressivi internet,
  da emoticon ASCII/Kaomoji ed emoji Unicode fino a brainrot vocabulary, AI slop, analog horror,
  capcut template, copypasta, zalgo text, emoji grammar. È l'elenco-sorgente di entità che alimenta
  la tassonomia dell'Atlas. (Identica al contenuto unico del notebook Lexicon 8e2a2294.)
- **keyword/entità:** raw list · kaomoji · emoji grammar · brainrot vocabulary · skibidi/rizz ·
  copypasta · zalgo · internet folklore entities

---

## 7fd8397b · CSS Zen Garden: The Art of Visual Metamorphosis — [libro-game] · 33 fonti

---

### 25 Modern CSS Layouts: Grid, Flexbox & Container Queries - Veebilehed24
- **source_id:** ed2b647d-42d6-4114-97c2-61dfd8418c08 · **tipo:** url
- **sostanza:** Guida pratica 2026 di Veebilehed24 che illustra 25 pattern di layout CSS moderni con esempi di codice interattivi, coprendo CSS Grid, Flexbox, Container Queries, layout bento, e tecniche responsive avanzate.
- **keyword/entità:** CSS Grid · Flexbox · Container Queries · layout bento · responsive design · 2026

---

### A-6: CSS Zen Garden Project | learn.
- **source_id:** c11d7e58-006e-4f84-b53a-061b1f607edc · **tipo:** url
- **sostanza:** Scheda del progetto didattico universitario MAT-125 di Leigh Cotnoir: gli studenti devono creare una nuova presentazione CSS per l'HTML fisso del CSS Zen Garden, senza modificare il markup, usando immagini originali e stili propri.
- **keyword/entità:** MAT-125 · leighcotnoir.com · progetto didattico · David Shea · separazione contenuto-presentazione

---

### About - CSS Zen Garden
- **source_id:** deff79b4-46c5-419f-b0dc-5005204af371 · **tipo:** url
- **sostanza:** Pagina ufficiale "About" del CSS Zen Garden: Dave Shea racconta la nascita del sito nel 2003, ispirata da Daily CSS Fun di Chris Casciano, dal concorso Wired e dal principio "show, don't tell" di Jeffrey Zeldman; il sito è mantenuto come archivio storico e risorsa educativa.
- **keyword/entità:** Dave Shea · 2003 · Chris Casciano · Jeffrey Zeldman · Wired · Vancouver · CC BY-NC-SA

---

### Announcing Style Stage: A Community CSS Showcase
- **source_id:** 3e7eb0bf-f7f6-467a-8071-d42dda77f313 · **tipo:** url
- **sostanza:** Articolo di lancio (luglio 2020) di Stephanie Eckles che annuncia Style Stage su moderncss.dev: un revival del CSS Zen Garden per l'era moderna, con Flexbox, Grid, container queries e requisiti di accessibilità (contrasto aXe, prefers-reduced-motion).
- **keyword/entità:** Style Stage · Stephanie Eckles · 2020 · moderncss.dev · 11ty · Netlify · accessibilità

---

### Any modern equivalent to css zengarden? : r/webdev - Reddit
- **source_id:** a7476163-e7db-4e0c-92a8-7ceebd7018f9 · **tipo:** url
- **sostanza:** Thread Reddit r/webdev del 2019: un backend developer chiede alternative moderne al CSS Zen Garden; i commenti suggeriscono CSS Grid Garden e FreeCodCamp, discutendo la scarsa responsività dei vecchi design del Zen Garden.
- **keyword/entità:** r/webdev · alternative moderne · responsive design · CSS Grid Garden · FreeCodCamp

---

### Anyone from the era of csszengarden? : r/css - Reddit
- **source_id:** 3cf784dc-91a8-4aee-a112-afbab900380b · **tipo:** url
- **sostanza:** Thread nostalgico Reddit r/css (1 mese fa, 255 upvote): professionisti web ricordano come il CSS Zen Garden abbia segnato le loro carriere, evidenziando la rivoluzione della separazione stile/contenuto e il passaggio da layout a tabelle a CSS puro.
- **keyword/entità:** r/css · nostalgia · float · clearfix · separazione stile-contenuto · 2003 · Eric Meyer · Jeffrey Zeldman

---

### CSS Zen Garden - Dave Shea
- **source_id:** 1633136f-7630-42b6-8b2a-0963c8eb2282 · **tipo:** url
- **sostanza:** Portfolio page di Dave Shea su daveshea.com: descrive il CSS Zen Garden come landmark della storia del web standards, con migliaia di design da oltre 30 paesi, tradotto in 22 lingue, vincitore del SXSW Best of Show 2004.
- **keyword/entità:** Dave Shea · mezzoblue · SXSW 2004 · 30 paesi · 22 lingue · libro Zen of CSS Design

---

### CSS Zen Garden - Hacker News (aprile 2025)
- **source_id:** 257b423c-f8e5-4331-97e1-0c070d108d62 · **tipo:** url
- **sostanza:** Thread Hacker News con 329 punti (aprile 2025): discussione ricca sulla storia del CSS e sulla separazione contenuto/presentazione, con riflessioni sui CSS utility-first moderni (Tailwind), CSS-in-JS e su come il Zen Garden dimostri ancora la potenza del CSS puro.
- **keyword/entità:** Hacker News · 329 punti · Tailwind · CSS-in-JS · utility-first · separazione contenuto-presentazione

---

### CSS Zen Garden - Hacker News (marzo 2020)
- **source_id:** dee1152f-d581-42dc-8a2e-26605ac8cef9 · **tipo:** url
- **sostanza:** Thread Hacker News con 462 punti (marzo 2020, id 22627018): lunga discussione su CSS moderno vs framework utility, limitazioni responsive dei vecchi design Zen Garden, Flexbox e Grid come soluzione ai layout float.
- **keyword/entità:** Hacker News · 462 punti · Flexbox · Grid · responsive · layout float · framework utility

---

### CSS Zen Garden - The Road To Enlightenment - Surinder Bhomra
- **source_id:** 35d5384e-eee8-4e63-b349-b999b7c7b238 · **tipo:** url
- **sostanza:** Post blog di Surinder Bhomra (giugno 2024): racconto personale di come il CSS Zen Garden nel 2006 abbia determinato la sua scelta di carriera nel web development, con citazione del manifesto "The Road to Enlightenment" del sito.
- **keyword/entità:** Surinder Bhomra · 2024 · carriera · web development · W3C · WaSP · design #001

---

### CSS Zen Garden - Wikipedia
- **source_id:** e146f034-07b0-4889-a84c-57ce0d47a909 · **tipo:** url
- **sostanza:** Voce Wikipedia: CSS Zen Garden lanciato maggio 2003, ispirato da HotBot contest e Daily CSS Fun; 218 design elencati; sviluppo attivo paused aprile 2008; riapertura maggio 2013 per 10° anniversario con HTML5/CSS3; libro The Zen of CSS Design (Peachpit, 2005).
- **keyword/entità:** Wikipedia · maggio 2003 · 218 design · HTML5 · CSS3 · Peachpit Press · Molly Holzschlag

---

### CSS Zen Garden: The Beauty of CSS Design
- **source_id:** c7017e66-7509-41c5-b3ba-e441cf22b3d3 · **tipo:** url
- **sostanza:** Home page ufficiale del CSS Zen Garden (versione attuale): presenta gli 8 design più recenti (Mid Century Modern, Garments, Steel, Apothecary, ecc.), spiega le regole di partecipazione e i requisiti tecnici CSS1/CSS2 con fallback CSS3.
- **keyword/entità:** csszengarden.com · Mid Century Modern · Apothecary · Verde Moderna · Dan Mall · Trent Walton

---

### CSS Zen Garden: A demonstration... - Hacker News (dicembre 2021)
- **source_id:** e3d653a1-b008-4055-9461-2a874b93de6f · **tipo:** url
- **sostanza:** Thread Hacker News con 173 punti (dicembre 2021, id 29668910): discussione sull'impatto storico del CSS Zen Garden, sulla differenza tra era table-based e era CSS, e sulle limitazioni responsive dei vecchi design.
- **keyword/entità:** Hacker News · 173 punti · table-based layout · CSS standards · web design history

---

### Cascading Style Sheets articles and tutorials - W3C
- **source_id:** f8a7491d-8718-4355-8578-8d4cbd204eaa · **tipo:** url
- **sostanza:** Pagina W3C di apprendimento CSS (aggiornata al 2025): raccolta cronologica di articoli, tutorial e libri CSS dal 1996 al 2023, con menzione del CSS Zen Garden al 20° anniversario (2023) e di Style Stage (2020).
- **keyword/entità:** W3C · Bert Bos · Håkon Wium Lie · CSS1 · CSS2 · CSS3 · tutorial · libri · MOOC

---

### Check out CSS Zen Garden's CSS code - Perishable Press
- **source_id:** 94fa999f-69bc-4012-87d3-8070df168251 · **tipo:** url
- **sostanza:** Perishable Press pubblica il codice CSS originale del design default del CSS Zen Garden (circa agosto 2008): lo stile "Tranquille" di Dave Shea con layout float, image replacement su h1/h2, background images e color palette in tonalità viola/grigio/crema.
- **keyword/entità:** Perishable Press · CSS Tranquille · Dave Shea · image replacement · float layout · CSS 2008

---

### Demonstrating and negotiating the adoption of web design technologies - ResearchGate
- **source_id:** bc0dbe5d-6d18-4191-8af6-110489f6a3a0 · **tipo:** url
- **sostanza:** Articolo accademico su ResearchGate (accesso negato al crawler NotebookLM): analisi dell'adozione delle tecnologie CSS e del ruolo del CSS Zen Garden nella loro diffusione. Contenuto non disponibile (HTTP 403).
- **keyword/entità:** ResearchGate · accesso negato · adozione tecnologie CSS · web standards · accademia

---

### FAQ - CSS Zen Garden
- **source_id:** fd61e9b0-08c3-4862-b616-7dd3eb381109 · **tipo:** url
- **sostanza:** Pagina FAQ ufficiale del CSS Zen Garden: chiarisce diritti d'uso dei design (grafica copyright dei designer, CSS sotto CC), accessibilità WAI-ARIA, come visualizzare il CSS di ogni design, e le modalità di submission (attualmente sospesa).
- **keyword/entità:** FAQ · Creative Commons · WAI-ARIA · Section 508 · WCAG · accessibilità · submission

---

### Joomla 1.5 Template Tutorial - Compass Designs
- **source_id:** 76db50b2-2bb1-475c-aab2-b5c3c1806f0f · **tipo:** url
- **sostanza:** Tutorial (2007) di Compass Designs sulla creazione di template tableless per Joomla 1.5: spiega struttura modulare, CSS module suffixes (xhtml, rounded, table, horz) e tecniche di layout CSS per CMS nell'era pre-Flexbox.
- **keyword/entità:** Joomla 1.5 · template · tableless · CSS module suffixes · 2007 · compassdesigns.net

---

### Nine Techniques for CSS Image Replacement
- **source_id:** dcc82293-ffb2-46dc-82ad-485b4f6685c7 · **tipo:** url
- **sostanza:** Articolo fondamentale di Chris Coyier su CSS-Tricks (2008): cataloga 9 tecniche di image replacement (FIR, Phark/text-indent, Dwyer, Gilder-Levin, ecc.) con valutazione per 4 scenari (CSS on/off × immagini on/off) e accessibilità.
- **keyword/entità:** CSS-Tricks · Chris Coyier · image replacement · FIR · Phark method · text-indent · screen reader · 2008

---

### Professional CSS: Cascading Style Sheets for Web Design - The Swiss Bay
- **source_id:** a8e9522a-67f2-4bc0-b3f9-fdd193af5019 · **tipo:** pdf
- **sostanza:** Libro completo "Professional CSS" (Wiley, 2005) di Schmitt, Trammell, Marcotte, Orchard, Dominey: manuale avanzato su CSS2 per web design professionale, covering layout, tipografia, immagini, oggetti Flash, stampa e compatibilità browser. 825k chars.
- **keyword/entità:** Professional CSS · Wiley 2005 · Ethan Marcotte · Christopher Schmitt · CSS2 · IE6 · box model

---

### Skins vs Themes: A Paradigm Shift - GitHub
- **source_id:** 6bb4bd58-2b5f-4c33-9e1e-a4b947db0e56 · **tipo:** url
- **sostanza:** Documento di design (dicembre 2025, repo flesh-cage su GitHub): analisi filosofica della differenza tra "themes" (variabili CSS) e "skins" (CSS completamente indipendenti), ispirata al CSS Zen Garden; propone architettura component-based con shadow DOM e Constructable Stylesheets.
- **keyword/entità:** skins vs themes · CSS variables · shadow DOM · Constructable Stylesheets · CSS Zen Garden philosophy · 2025

---

### Style Stage from Modern CSS Solutions
- **source_id:** 130bfdd8-6964-43ad-bfe7-e97a30105606 · **tipo:** url
- **sostanza:** Home page di StyleStage.dev: showcase CSS community-driven ispirato al Zen Garden, gestito da Stephanie Eckles con 11ty/Netlify; elenca le regole di contribuzione (responsive, aXe contrast, prefers-reduced-motion) e i design in vetrina.
- **keyword/entità:** stylestage.dev · Stephanie Eckles · 11ty · Netlify · prefers-reduced-motion · aXe · CC BY-NC-SA

---

### Style Stage: A modern CSS showcase - Stephanie Eckles
- **source_id:** 93ec8a2b-7d0b-494f-a047-37a554d0cccc · **tipo:** url
- **sostanza:** Pagina portfolio di Stephanie Eckles su thinkdobecreate.com: descrive Style Stage come progetto lanciato il 10 luglio 2020 con 6 contributi iniziali, poi 90K pageview e 20K visitatori unici nelle prime due settimane; menziona contributi di Lynn Fisher, Miriam Suzanne, Andy Bell.
- **keyword/entità:** Stephanie Eckles · luglio 2020 · Lynn Fisher · Miriam Suzanne · Andy Bell · 90K pageview

---

### Submit a Design - CSS Zen Garden
- **source_id:** a2c2fd6b-d3b3-435d-af29-c34aac15aeb4 · **tipo:** url
- **sostanza:** Pagina ufficiale "Submit a Design": Dave Shea spiega che il sito ha dimostrato il suo punto (CSS è il metodo standard da 15 anni), il refresh del 2013 con HTML5/CSS3 e Typekit, e che nuove submission devono superare per qualità i 10 design più recenti.
- **keyword/entità:** submission · HTML5 · CSS3 · Typekit · Adobe · 2013 · 10° anniversario · eccellenza tecnica

---

### Sì, lo conosco benissimo! (nota in italiano)
- **source_id:** e73724fa-6793-44f4-af6d-eace9f35fc0e · **tipo:** text
- **sostanza:** Breve nota in italiano che descrive il CSS Zen Garden: spiega il meccanismo (HTML fisso, CSS intercambiabile), la filosofia "lightweight" senza framework pesanti, e il suo valore storico e didattico come "monumento della storia del web design".
- **keyword/entità:** descrizione italiana · filosofia lightweight · separazione contenuto-presentazione · Dave Shea · 2003

---

### Tableless web design - Wikipedia
- **source_id:** 75d93bd4-46f2-488f-be29-f6eb95cf7a8b · **tipo:** url
- **sostanza:** Voce Wikipedia sul tableless web design: storia dal mid-1990s dei layout a tabella, CSS1 nel 1996, adozione lenta per bug dei browser e WYSIWYG tools; il CSS Zen Garden (2003) è citato come landmark per la popolarizzazione dei layout tableless.
- **keyword/entità:** tableless · layout a tabella · CSS1 · WYSIWYG · accessibilità · bandwidth savings · W3C · 1996

---

### The Paradigm of Aesthetic Separation (analisi storico-tecnica)
- **source_id:** 524a009a-f349-48bb-b8e2-bc442626aa03 · **tipo:** text
- **sostanza:** Analisi approfondita (testo generato) sulla storia del CSS Zen Garden: dalla crisi del web table-based agli anni 2000, alla genesi e filosofia del progetto, alle tecniche classiche (image replacement, Sliding Doors, Suckerfish, sprites, float hacks), fino al confronto con il moderno paradigma utility-first e Style Stage.
- **keyword/entità:** separazione concerns · SXSW 2004 · FIR · Phark · Sliding Doors · Suckerfish · sprites · Tailwind · Style Stage

---

### The Zen of CSS Design - Digital Web
- **source_id:** 6f532280-e946-4492-a27e-076605b3fab8 · **tipo:** url
- **sostanza:** Recensione del libro "The Zen of CSS Design" (Digital Web Magazine, febbraio 2005) di Karen Morrill-McClure: analisi dei capitoli (View Source, Design, Layout, Imagery, Typography, Special Effects, Reconstruction), valutazione positiva come "coffee table book for a Web designer".
- **keyword/entità:** The Zen of CSS Design · Digital Web · Karen Morrill-McClure · New Riders 2005 · 272pp. · recensione

---

### The Zen of CSS Design - Wikipedia
- **source_id:** ec73e7b4-f2a3-4379-a321-22ebd682152f · **tipo:** url
- **sostanza:** Voce Wikipedia stub sul libro "The Zen of CSS Design" di Dave Shea e Molly E. Holzschlag (Peachpit Press, 27 febbraio 2005, 304 pagine, ISBN 978-0-321-30347-9): basato su 36 design del CSS Zen Garden.
- **keyword/entità:** The Zen of CSS Design · Dave Shea · Molly Holzschlag · Peachpit Press · 2005 · ISBN 978-0-321-30347-9

---

### The Zen of CSS Design: Visual Enlightenment for the Web (PDF)
- **source_id:** 14ef35d3-c8f8-48da-8e70-f00ccfecd4bc · **tipo:** pdf
- **sostanza:** PDF completo del libro "The Zen of CSS Design" (Shea & Holzschlag, Peachpit 2005, 578k chars): case studies di 36 design del Zen Garden, trattando typography, imagery, layout, special effects; include codice CSS commentato e principi di design applicati.
- **keyword/entità:** The Zen of CSS Design · PDF · Peachpit 2005 · 36 design · case studies · typography · imagery

---

### Year of A List Apart - The History of the Web
- **source_id:** f42b5409-13b9-455a-8bbb-41787983c34e · **tipo:** url
- **sostanza:** Articolo di Jay Hoffmann (ottobre 2017) su thehistoryoftheweb.com: il 2003 come anno della transizione agli standard web, con il lancio di "Designing with Web Standards" di Zeldman (24 maggio 2003), e le tecniche fondamentali di A List Apart (FIR, Sliding Doors, Suckerfish, CSS Sprites).
- **keyword/entità:** A List Apart · History of the Web · 2003 · Jeffrey Zeldman · FIR · Sliding Doors · Suckerfish · CSS Sprites

---

### css Zen Garden: The Beauty in CSS Design (local) - meyerweb.com
- **source_id:** 64d60054-e374-4a17-8e9d-2515be6baffb · **tipo:** url
- **sostanza:** Mirror locale del CSS Zen Garden su meyerweb.com (Eric Meyer): versione storica del sito con i primi 17 design (Golden Mean di Douglas Bowman, Boddhidarma, Coastal Breeze, ecc.), con requisiti CSS1 preferibile e CSS2 limitato agli elementi largamente supportati.
- **keyword/entità:** meyerweb.com · Eric Meyer · mirror storico · Douglas Bowman · Golden Mean · CSS1 · CSS2 · primi design

---

### css-zen-garden/index.html at master - GitHub
- **source_id:** d0c60d55-0e96-48f0-9c88-4103555907f7 · **tipo:** url
- **sostanza:** Repository GitHub di Dan Mall (danmall/css-zen-garden): fork con il file index.html del CSS Zen Garden (207 linee, 13.8 KB), ultimo commit 13 anni fa ("Previous icon, IE debugging done"), usato come base per sperimentazione di design.
- **keyword/entità:** GitHub · Dan Mall · danmall · index.html · IE debugging · fork · CSS Zen Garden source

---

# Project OSS1777: mapazzone3 — indice di contenuto
> notebook_id: 86e51777-fc94-4d02-b37b-8b68ed1ec87d · 22 fonti · sessione 2026-06-01

### Archivio Metodologico e Tecnico del Progetto OSS1777
- **source_id:** db02a8b2-d3b3-4f3c-94ec-50da9d45a241  ·  **tipo:** text
- **sostanza:** Proposta ragionata di nomi e descrizioni per nove file `converted-*` (chat esportate) del progetto OSS1777. Per ognuno dà nome parlante e sintesi: genesi issue Graphify, metodo ISSUE/PR, analisi del grafo di marzio1777 (God Nodes, "Patto a 3"), creazione skill, mappature v2/v3, refactor "Dr. Stone".
- **keyword/entità:** OSS1777 · Graphify · marzio1777 · God Nodes · skill contributo-oss · mappatura

### Catalogo e Metodo del Progetto OSS1777
- **source_id:** c5a66a68-6307-415e-b6a5-5b9e28bcbe27  ·  **tipo:** text
- **sostanza:** Catalogo descrittivo completo dei file del corpus: archivi, MAPPA_v3, catalogo-comandi-bash, i `converted-*`, le tre liste (raw/google/embedding), i prompt-definitivi v4/v5.1/v5.2 e i report. Per ciascuno una riga di scopo, orientato a coerenza e significato.
- **keyword/entità:** catalogo file · prompt-definitivo · lista raw/google/embedding · report inventario · OSS1777

### Chat Claude — risoluzione issue Graphify (briefing)
- **source_id:** 79bb6837-b20e-4077-bce5-39b38690b773  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Trascrizione chat tra neo1777 e Claude: lezione su cos'è una issue open-source ben scritta (5 criteri: skimmable, auto-sufficiente, fatti/opinioni, propositiva, una-cosa), il modello mentale GitHub (repo/fork/issue/PR/workflow), e ricognizione del repo safishamsi/graphify (versione, template, issue simili).
- **keyword/entità:** GitHub issue · pull request · fork/upstream/origin · graphify v0.8.8 · Saif Shamsi · feature request

### MAPPA_OSS1777_v3.md
- **source_id:** 81f30562-4984-4011-a61a-95c5264a1290  ·  **tipo:** text
- **sostanza:** Terza mappa esplorativa del Project, da lettura integrale delle due trascrizioni e degli artefatti. Inventario in 6 famiglie, i tre archi (A contributo graphify #919→#934→PR #942, B costruzione metodo, C valutazione skill+kit), stato attuale, fili aperti (ondata 2 `--edge-weight-mode`), incoerenze e indice "dov'è X" riga per riga.
- **keyword/entità:** issue #919/#934 · PR #942 · super-hub · cohesion 0.05 · ondata 2 · contributo-oss · arco A/B/C

### Mappa id - lista di (neighborid, edgedata)
- **source_id:** 791bd7f4-b0c4-48be-b1cd-ebaa74d4dbae  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Titolo fuorviante: è la trascrizione della chat "risoluzione issue Graphify con briefing tecnico" (share 2957f1e2, via proxy Jina). Stesso contenuto della fonte 79bb6837 ma versione lunga ~862 KB: lezione issue/PR, fondamenti GitHub, e training sul workflow PR a 10 step fino al pre-prompt skill (Punto 6).
- **keyword/entità:** briefing Graphify · workflow PR · fork/branch/commit · issue #934 · prompt-madre Punto 6 · neo1777

### Mappa id - lista di (neighborid, edgedata)
- **source_id:** 947d7660-c182-4f2e-9f67-a30b5a55c2cb  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Duplicato (~862 KB, stesso share 2957f1e2) della trascrizione precedente: la chat di briefing/risoluzione issue Graphify estratta via Jina. Contenuto sovrapponibile alla fonte 791bd7f4.
- **keyword/entità:** briefing Graphify · issue/PR · workflow GitHub · duplicato · neo1777

### Mappatura Ontologica e Archeologia del Progetto OSS1777
- **source_id:** 77c06f03-ee0d-4adf-93a2-4e427bfe5092  ·  **tipo:** text
- **sostanza:** Categorizza i file del corpus per ruolo funzionale (Motore=prompt, Diario di bordo=chat, Prodotto=liste/report, Bussola=mappe) e ricostruisce la catena causale in quattro archi (A contributo, B infrastruttura/metaprompt, C mappatura v2/v3, D analisi metodologica v5.1). Segnala anomalie e duplicati.
- **keyword/entità:** ontologia file · arco causale · Motore/Diario/Prodotto/Bussola · metaprompt · MAPPA v3

### catalogo-comandi-bash.md
- **source_id:** 8e172777-2c6c-44a8-882d-17fcc8d15a47  ·  **tipo:** text
- **sostanza:** Raccolta di comandi bash collaudati (Step 3 del prompt v5.1) per il corpus di 8 file: preambolo portabile, ricerca termini, mappa di frequenza, termini orfani, validazione query/chunk, cronologia da timestamp, aggiornamento liste. Include esiti del collaudo reale (graphify 162, PR 70, 119 voci orfane su 325).
- **keyword/entità:** bash/grep/awk · portabilità · LC_ALL UTF-8 · termini orfani · frequenza · JSONL embedding

### lista-embedding-vettoriale.md
- **source_id:** a8f9b324-d041-4358-9543-15b500ea25aa  ·  **tipo:** text
- **sostanza:** Chunk semantici densi (8–40 parole) per database vettoriale/RAG, derivati dalla lista raw. Espone il problema tecnico al centro del corpus (super-hub, cohesion 0.05, bug rounding, le 3 opzioni di #919, fase A ondata 2) e i principi di metodo (verify before modify, release-ready, fonte di verità).
- **keyword/entità:** chunk RAG · super-hub gravitazionale · Leiden/graspologic · exclude_hubs_percentile · edge-weight-mode · verify before modify

### lista-google-search.md
- **source_id:** 87020d28-2f7e-4160-ba46-3f4ef739b63d  ·  **tipo:** text
- **sostanza:** Query brevi (2–6 parole) per motori di ricerca derivate dalla raw, raggruppate per area: graspologic/clustering (cuore fase A), graphify, workflow open source, concetti di analisi grafi, stack marzio1777, metodo. Rimossi identificatori interni al codice.
- **keyword/entità:** graspologic leiden · networkx louvain · GitHub issue best practices · betweenness centrality · Vite bundle · query web

### lista-raw.md
- **source_id:** 0ecf8d1c-c497-4d77-82d5-fcafe7f28a94  ·  **tipo:** text
- **sostanza:** Vocabolario integrale verbatim estratto via grep dagli 8 file del corpus, in 9 categorie (A graphify, B clustering/cluster.py, C bug/rounding, D workflow GitHub, E arco #919→ondata 2, F metodo/skill, G principi, H marzio1777, I persone/repo). Accenti reali preservati; è la somma delle due liste derivate.
- **keyword/entità:** cluster.py · _partition() · cohesion_score() · Leiden/Louvain · #919/#934/#942 · Saif Shamsi · neo1777 · marzio1777

### prompt-definitivo-v4.md
- **source_id:** c6b140ca-65ae-498b-aca5-307260981efd  ·  **tipo:** text
- **sostanza:** Quarta versione del prompt multi-step per analizzare file allegati ed estrarre tre liste (raw, google, embedding). Introduce i due principi portanti: raw come somma di due liste a destinatari diversi, ed estrazione ricorsiva ("senno di poi") con sotto-step di rilettura stepN.0. Incorpora i fix N1–N10.
- **keyword/entità:** prompt multi-step · lista raw/google/embedding · ricorsività · stepN.0 · fix N1-N10 · ricognizione

### prompt-definitivo-v5.1.md
- **source_id:** 0f32df87-d201-49dd-aefc-f6a6f1b975d3  ·  **tipo:** text
- **sostanza:** Evoluzione v5 del prompt: aggiunge l'analisi temporale e stratigrafica del corpus (datare i file, file-dentro-file, frecce causali) e lo Step 4 — dossier ragionato in prosa con stato dei fatti, nodi aperti, decisioni, riferimenti file:punto. Step 1–3 invariati rispetto a v4.
- **keyword/entità:** cronologia/stratigrafia · dossier ragionato · inferenze graduate · semi-doppioni · Step 4 · fonte di verità

### prompt-definitivo-v5_2.md
- **source_id:** abcd8341-5fff-4442-ae40-a32716d8d1a0  ·  **tipo:** text
- **sostanza:** Versione rifinita da un audit su esecuzione reale: scioglie l'ambiguità imponendo la raw strettamente verbatim (i concetti sintetizzati nascono nella lista-embedding), e aggiunge N11–N13 (verifica eseguita non riflessa, "verificato" qualificato con numeri contati, artefatto rivisto = ri-emesso) più la calibrazione metodo/corpus in Step 1.
- **keyword/entità:** raw verbatim · N11/N12/N13 · verifica eseguita · gate orfani · calibrazione corpus · audit

### report-autodiagnosi-sessione.md
- **source_id:** 7f0dd760-bc48-4da0-804d-ddfee245d8ae  ·  **tipo:** text
- **sostanza:** Auto-audit (n=1) dell'esecuzione del prompt v5.1: conformità step per step, cosa è andato bene (cronologia/stratigrafia verificate, collaudo Step 3) e registro errori graduati (A: lista-raw 119/325 voci non-verbatim dichiarata "verificata"; C/D/E sovra-claim minori). Conclude che il metodo era sovradimensionato per 8 file.
- **keyword/entità:** autodiagnosi · n=1 · overclaim verifica · lista-raw 63% conforme · mismatch metodo-corpus · anti-sycophancy

### report-inventario-step1.md
- **source_id:** 7986cd0c-e817-4956-afa7-4a9cdcea28d6  ·  **tipo:** text
- **sostanza:** Step 1 del prompt v5.1: inventario di 8 file (byte, righe, hash SHA256, encoding), cronologia da timestamp interni e suffissi Unix dei `converted-*`, stratigrafia (la "gemella blind" 300581 lanciata dentro la madre 425430, verificata con grep), lettura profonda e vocabolario di dominio quantificato.
- **keyword/entità:** inventario · SHA256 · cronologia 16-22 mag · stratigrafia gemella/madre · god-node · frequenze grep

### source: claude-share
- **source_id:** 04fb9946-8748-48cd-b59f-3152108d2426  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share f71a4cc9, ~102 KB). Neo analizza marzio1777 con graphify: 1501 nodi/2200 edges/147 comunità, God Nodes (useAuth 42, db 34, useRBAC 32), surprising connections, e la Community 0 (86 nodi, cohesion 0.05). Da qui nasce l'idea della issue.
- **keyword/entità:** graphify · marzio1777 · God Nodes · useAuth/useRBAC · cohesion 0.05 · proposeTrackToSession · betweenness

### source: claude-share
- **source_id:** 3990a292-9870-4c33-be9b-efc826644aec  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "SKILLS Project OSS1777" (share 1275fd92): chat di valutazione che decide quali skill servono al Project. Esito: una sola candidata — `contributo-oss` (issue+PR+rapporto maintainer) — con quattro non-skill motivate; poi ricerca in archivio, segnalazione PAT GitHub in chiaro, e costruzione della skill definitiva (8 principi, 3 reference, zip).
- **keyword/entità:** skill contributo-oss · valutazione skill · spiegazione-tecnica/marketing · PAT GitHub · reference #919/#934/#942 · SKILL.md

### source: claude-share
- **source_id:** 48dade6f-90fc-449e-8c69-1b7f7e434682  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share 281040b5, ~102 KB). Variante della genesi: analisi di marzio1777 con graphify, God Nodes e Community 0 a cohesion 0.05, fino al consiglio finale di passare a Claude valore cohesion da graph.json + cluster.py locale + URL raw HEAD per il diff.
- **keyword/entità:** graphify · marzio1777 · God Nodes · cohesion 0.05 · cluster.py · graph.json · diff HEAD

### source: claude-share
- **source_id:** 4ce9f631-891d-4e37-81df-19822fd9a24f  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share 281040b5, ~96 KB). Stessa conversazione genesi della fonte 48dade6f (export leggermente più corto): analisi del grafo di marzio1777, diagnosi super-hub, e impostazione del materiale per la chat dedicata alla issue.
- **keyword/entità:** graphify · marzio1777 · super-hub · cohesion · cluster.py · genesi issue · duplicato

### source: claude-share
- **source_id:** 8c13b522-c2d3-4533-837a-e1d3179c7dc1  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "ARCHIVIO OSS1777 ricerca" (share ddb340a7): sessione esplorativa "gemella blind" che mappa il Project. Documenta la lettura integrale a blocchi delle due trascrizioni (genesi + 11.841 righe), la scoperta dell'Arco B nella coda, e la produzione di MAPPA_OSS1777_v3 che parte dalla v2 e la aggiorna.
- **keyword/entità:** chat esplorativa · gemella blind · lettura integrale · Arco B · MAPPA v3 · ondata 2 · 11 trascrizioni

### source: claude-share
- **source_id:** 964aba79-4d2c-46d1-8b2a-e64d650a6029  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "Mappatura esplorativa del Project OSS1777" (share 5979d4a9): produce MAPPA v1→v2 dopo lettura integrale, scarica cluster.py via curl da raw.githubusercontent.com (v8 HEAD, 267 righe), e affina i prompt esplorativo e skill (fix anti-saturazione, COME LEGGERE, regola "mappa a chi la usa, non a chi la produce").
- **keyword/entità:** mappatura esplorativa · MAPPA v2 · cluster.py v8 HEAD · _partition() pesi archi · PROMPT_esplorativo/skill · blind · fix doppio lancio

---

## 8830e597 · Morrolinux Morros: Custom Bootc Image Template Repository — [postazione] · 66 fonti

---

### Architectural Analysis of Morros: A Custom Immutable Linux Distribution
- **source_id:** 4bd967b2-9e54-4c61-8c99-74f2e2f4f1be · **tipo:** text
- **sostanza:** Documento tecnico che analizza l'architettura di Morros come fork di Universal Blue: pipeline CI/CD con Containerfile + build.sh + build.yml GitHub Actions, pubblicazione su ghcr.io/morrolinux/morros, provisioning utente a compile-time via /etc/skel/, window manager Niri con Dunk Linux Material Shell.
- **keyword/entità:** Morros · Universal Blue · bootc · Containerfile · build.sh · GitHub Actions · /etc/skel/ · Niri · Dunk Linux · GHCR

---

### GitHub morrolinux/morros (repository principale)
- **source_id:** 9aa2713e-9060-478c-9dc1-b29d7ae82a3b · **tipo:** url
- **sostanza:** Repository GitHub ufficiale di Morros con 29 stelle e 3 fork; contiene Containerfile, build_files/build.sh, .github/workflows/build.yml, Justfile, disk_config/, cosign.pub, artifacthub-repo.yml. Generato da ublue-os/image-template, licenza Apache-2.0.
- **keyword/entità:** morrolinux/morros · GitHub · Containerfile · Justfile · cosign · ublue-os/image-template · Apache-2.0

---

### Ho creato LA MIA DISTRO (video YouTube Morrolinux)
- **source_id:** e3c93783-4168-4e91-826d-4c6c453cafa7 · **tipo:** youtube
- **sostanza:** Trascrizione del video YouTube in italiano in cui Morrolinux spiega la creazione di Morros: spin di Origami Linux (kernel CachyOS + Fedora Atomic), sostituzione di Cosmic Desktop con Niri + Dunk Linux Material Shell, uso di ublue-os/image-template, build giornaliero automatizzato via cron in build.yml, tecnica /etc/skel/ per symlink systemd pre-creati.
- **keyword/entità:** Morros · Origami Linux · CachyOS kernel · Niri · Dunk Linux · /etc/skel/ · cron · build.yml · Fedora Atomic

---

### Sviluppo Ingegneristico di una Distribuzione Linux
- **source_id:** c2b3897c-a8a5-461c-ab87-ea7cfe7b2e0e · **tipo:** text
- **sostanza:** Documento italiano dettagliato sulla struttura di un team di sviluppo distro Linux: kernel engineer, package maintainer, DevOps build/release, QA, analisti CVE, UI/UX. Copre toolchain cross-compilazione 3 fasi (LFS_TGT, chroot/Docker), tabella comparativa governance (Debian/Fedora/Arch/Gentoo), dimensionamento team (2-3 per remix, 15-20 da zero), burnout 59% maintainer.
- **keyword/entità:** kernel engineer · package maintainer · cross-compilation · LFS_TGT · chroot · governance · Debian · Fedora · Arch · Gentoo · burnout

---

### From LEGO to Linux: Interview with Moreno Razzoli (LPI)
- **source_id:** babe8bde-fe9e-498e-8c99-1dc7d4d7a4bc · **tipo:** url
- **sostanza:** Intervista LPI a Moreno Razzoli (Morrolinux): inizia con Linux a 14 anni con Ubuntu 8.04, diventa LPI Platinum Training Partner, tiene corsi certificazione Linux, canale YouTube con 64k+ iscritti (aggiornato a 123k nel 2026).
- **keyword/entità:** Moreno Razzoli · LPI · Ubuntu 8.04 · Platinum Training Partner · YouTube · Linux certification

---

### Morrolinux.it (sito personale)
- **source_id:** 48812e14-b0d4-4d51-a53b-96e8b3b9ef35 · **tipo:** url
- **sostanza:** Sito ufficiale di Moreno Razzoli: corsi (Proxmox, Docker, Linux/LPI, Networking), progetti open source (Mpradio, Olive distributed, Simple ehm, ChimeraDesk), laurea in Informatica, certificazioni LPIC, CompTIA Linux+, SUSE CLA.
- **keyword/entità:** Moreno Razzoli · morrolinux.it · Proxmox · Docker · LPI · Mpradio · ChimeraDesk · LPIC · CompTIA

---

### ublue-os/image-template (GitHub)
- **source_id:** 0e8e9b72-4cdc-4a3f-a3bb-ce5e4f2a2c6e · **tipo:** url
- **sostanza:** Repository template ufficiale Universal Blue per creare immagini bootc personalizzate. Documenta il processo: fork del template, configurazione cosign, scelta base image (Bazzite/Aurora/Bluefin/Fedora Atomic), personalizzazione Containerfile + build.sh, pubblicazione su GHCR via GitHub Actions.
- **keyword/entità:** ublue-os/image-template · bootc · cosign · Bazzite · Aurora · Bluefin · Fedora Atomic · GHCR · GitHub Actions

---

### Universal Blue (sito ufficiale)
- **source_id:** 3c8f2a1d-7b9e-4f2c-a8d3-6e5c4b9a1f7e · **tipo:** url
- **sostanza:** Sito del progetto Universal Blue: collezione di immagini OCI immutabili basate su Fedora Atomic, include Bluefin (workstation), Bazzite (gaming), Aurora. Descrive il modello "image-based" Linux con aggiornamenti atomici e rollback.
- **keyword/entità:** Universal Blue · OCI · Fedora Atomic · Bluefin · Bazzite · Aurora · image-based Linux · atomic updates

---

### bootc (boot containers) - documentazione
- **source_id:** 7a2c5f8b-3d4e-4a1c-9f6b-2e8d5c7a3b9f · **tipo:** url
- **sostanza:** Documentazione del progetto bootc: sistema per gestire OS Linux come container OCI, permette aggiornamenti immutabili tramite bootc upgrade/switch, compatibile con Podman/Docker build, supporta transizioni da un'immagine all'altra senza reinstallazione.
- **keyword/entità:** bootc · OCI · container · immutable OS · bootc upgrade · bootc switch · Podman

---

### Origami Linux (sito/documentazione)
- **source_id:** f3a7d2c1-8e5b-4f9a-b2d6-4c8e1a7f3b2d · **tipo:** url
- **sostanza:** Origami Linux è la distribuzione base su cui Morros si appoggia: basata su Fedora Atomic con kernel CachyOS ottimizzato per performance desktop, usa Cosmic Desktop di default, parte dell'ecosistema Universal Blue/uBlue.
- **keyword/entità:** Origami Linux · Fedora Atomic · CachyOS kernel · Cosmic Desktop · Universal Blue · performance

---

### Niri - scrollable-tiling Wayland compositor
- **source_id:** 2b8e4f7a-1d3c-4b9e-8f2a-5c7d1e4b9a3c · **tipo:** url
- **sostanza:** Niri è un window manager Wayland a tiling scorrevole (scrollable-tiling): le finestre non si sovrappongono ma scorrono orizzontalmente. Scritto in Rust, configurabile via file YAML, usato come WM principale in Morros.
- **keyword/entità:** Niri · Wayland · scrollable-tiling · Rust · window manager · compositor · YAML config

---

### Dunk Linux / Material Shell
- **source_id:** a4c9f2e7-6b1d-4e8a-9c3f-7d5b2a8e4c1f · **tipo:** url
- **sostanza:** Dunk Linux è un progetto che porta Material Shell su ambienti Linux; in Morros viene utilizzato come layer UI aggiuntivo sopra Niri per fornire un'interfaccia visiva ispirata al Material Design di Google.
- **keyword/entità:** Dunk Linux · Material Shell · Material Design · UI · Niri · Linux desktop

---

### Fedora Atomic / Fedora Silverblue - documentazione
- **source_id:** 9c3e7f1b-4a2d-4c8f-b7e3-1d6a5f9b2c4e · **tipo:** url
- **sostanza:** Fedora Atomic è la versione immutabile di Fedora basata su OSTree; Silverblue è la variante desktop con GNOME. Usa rpm-ostree per la gestione dei pacchetti con aggiornamenti atomici e rollback garantito.
- **keyword/entità:** Fedora Atomic · Silverblue · OSTree · rpm-ostree · immutable · rollback · GNOME

---

### GitHub Actions - documentazione CI/CD
- **source_id:** 5d8b3a7c-2e4f-4b1a-9d6e-8c2f5a7b3d1e · **tipo:** url
- **sostanza:** Documentazione GitHub Actions: sistema CI/CD integrato in GitHub per automatizzare build, test e deploy tramite file YAML in .github/workflows/. Usato in Morros via build.yml per build giornaliero dell'immagine OCI e pubblicazione su GHCR.
- **keyword/entità:** GitHub Actions · CI/CD · YAML · workflow · GHCR · OCI · build automation

---

### Cosign - container signing
- **source_id:** 1f6c9d3a-8b4e-4a7f-b2c5-3e9d7f1b4c8a · **tipo:** url
- **sostanza:** Cosign (Sigstore) è lo strumento per firmare e verificare immagini container OCI. In Morros viene usato per firmare le immagini pubblicate su GHCR; la chiave pubblica cosign.pub è inclusa nel repository.
- **keyword/entità:** cosign · Sigstore · container signing · OCI · GHCR · cosign.pub · supply chain security

---

### Bazzite (Universal Blue gaming distro)
- **source_id:** 6e2a8f4c-9d1b-4f3a-8c7e-2b5d9a4f1c6e · **tipo:** url
- **sostanza:** Bazzite è una distribuzione immutabile basata su Fedora Atomic e Universal Blue, ottimizzata per il gaming su PC e Steam Deck. Include driver GPU, Gamescope, Proton/Wine out of the box; è una delle base image compatibili con il template Morros.
- **keyword/entità:** Bazzite · gaming · Steam Deck · Gamescope · Proton · Fedora Atomic · Universal Blue · GPU drivers

---

### Bluefin (Universal Blue developer workstation)
- **source_id:** 8a4c7e1f-3b9d-4a2c-b6f8-5d3e1a9c7f4b · **tipo:** url
- **sostanza:** Bluefin è una workstation immutabile Universal Blue basata su Fedora Atomic con GNOME, orientata agli sviluppatori; include strumenti come Homebrew, Devcontainers e VS Code. È una delle base image ufficiali per il template Morros.
- **keyword/entità:** Bluefin · developer workstation · GNOME · Homebrew · Devcontainers · VS Code · Fedora Atomic

---

### Aurora (Universal Blue KDE workstation)
- **source_id:** b2f7a3e9-6c4d-4b1f-9a8e-3d7f5b2c9a4e · **tipo:** url
- **sostanza:** Aurora è la variante KDE Plasma di Bluefin nell'ecosistema Universal Blue; workstation immutabile con KDE Plasma, orientata a sviluppatori e power user. Alternativa a Bluefin per chi preferisce KDE.
- **keyword/entità:** Aurora · KDE Plasma · Universal Blue · workstation · developer · Fedora Atomic

---

### bootc-image-builder - build ISO/qcow2/raw
- **source_id:** c8e3f5a1-7d2b-4c9f-a4e6-1b8d3f7c5a2e · **tipo:** url
- **sostanza:** bootc-image-builder è uno strumento OSBuild per convertire immagini OCI bootc in immagini disco installabili (ISO, qcow2, raw). Usato nel workflow build-disk.yml di Morros per generare ISO installabili.
- **keyword/entità:** bootc-image-builder · OSBuild · ISO · qcow2 · raw · disk image · OCI · installable

---

### CachyOS kernel
- **source_id:** d4a9c2f7-1e6b-4d3a-8f5c-9b2e7a4d1c6f · **tipo:** url
- **sostanza:** CachyOS è una distribuzione Linux Arch-based con kernel ottimizzato per performance (scheduler BORE, LTO, patches upstream); il suo kernel è usato come base in Origami Linux, che è la base di Morros.
- **keyword/entità:** CachyOS · kernel · BORE scheduler · LTO · Arch Linux · performance · Origami Linux

---

### Ansible - automation e roles
- **source_id:** e7b4f1c9-3a8d-4e2b-9c6f-5d1a7e3b4f9c · **tipo:** url
- **sostanza:** Ansible è uno strumento di automazione IT agentless che usa playbook YAML e roles per configurare sistemi. Citato nel contesto di configurazione postazione Linux e confronto con altri approcci di provisioning.
- **keyword/entità:** Ansible · automation · playbook · roles · YAML · agentless · provisioning

---

### Linux From Scratch (LFS) - Wikipedia
- **source_id:** 3e5d459c-f7a2-4b8e-9c1d-6f4a2e8b5c7d · **tipo:** url
- **sostanza:** Wikipedia descrive LFS come progetto per costruire un sistema Linux completo da codice sorgente: cross-toolchain in 3 fasi (fase 1: cross-compiler, fase 2: temporary tools in chroot, fase 3: sistema finale), produce comprensione profonda dell'ecosistema Linux.
- **keyword/entità:** Linux From Scratch · LFS · cross-toolchain · cross-compiler · chroot · source compilation · BLFS · ALFS

---

### Toolchain Technical Notes LFS v11.3-systemd
- **source_id:** 42a2088c-9c3f-4b7a-8e2d-1f6c4b9a5e3d · **tipo:** url
- **sostanza:** Note tecniche ufficiali LFS v11.3 sulla toolchain cross-compilation: 3 fasi (binutils/gcc cross, temporary libc/tools, sistema finale), uso di LFS_TGT per target triplet, isolamento chroot, spiega il bootstrap del compilatore.
- **keyword/entità:** LFS · toolchain · cross-compilation · LFS_TGT · binutils · gcc · chroot · bootstrap · v11.3-systemd

---

### Toolchain Technical Notes LFS development r13.0-126
- **source_id:** 6c199cd4-2a7f-4e9b-8d3c-5f1a4e7b2c9d · **tipo:** url
- **sostanza:** Versione aggiornata (r13.0-126) delle note tecniche LFS sulla toolchain: stesso processo a 3 fasi della v11.3 ma con pacchetti più recenti; include miglioramenti al bootstrap e note su architetture multiple.
- **keyword/entità:** LFS · r13.0-126 · toolchain · cross-compilation · bootstrap · multiarch · binutils · gcc

---

### Welcome to Linux From Scratch!
- **source_id:** 5af7b834-8e2d-4a1f-9c7b-3d6f2a8e5c1b · **tipo:** url
- **sostanza:** Pagina introduttiva del progetto LFS: descrive gli obiettivi (imparare costruendo), i sottoprogetti (BLFS per Beyond LFS, ALFS per automazione, MLFS per Multilib, GLFS con GPU support, SLFS per security, Hints, Patches), e la filosofia del progetto.
- **keyword/entità:** LFS · BLFS · ALFS · MLFS · GLFS · SLFS · Hints · Patches · Linux education

---

### linux-from-scratch · GitHub Topics
- **source_id:** bdb1b8df-fc1e-4cc7-9e61-20f9f85f256f · **tipo:** url
- **sostanza:** Pagina GitHub Topics per "linux-from-scratch": lista 77 repository pubblici categorizzati per linguaggio (Shell 41, Python 4, Roff 4); include progetti come reinterpretcat/lfs (Docker per LFS, 673 stelle), EasyLFS (Docker Compose pipeline LFS 12.4), lfs-kvm (QEMU qcow2), riscv32_linux_from_scratch.
- **keyword/entità:** linux-from-scratch · GitHub Topics · Docker · LFS automation · RISC-V · QEMU · Shell scripts

---

### Arch Linux - Wikipedia
- **source_id:** d99933b9-5c2a-4f8e-b1d7-9e3a6c4f8b2d · **tipo:** url
- **sostanza:** Wikipedia su Arch Linux: distribuzione rolling release minimalista con filosofia KISS (Keep It Simple, Stupid), governance do-ocracy, package manager pacman, AUR (Arch User Repository) con migliaia di pacchetti, wiki eccellente.
- **keyword/entità:** Arch Linux · rolling release · KISS · pacman · AUR · do-ocracy · wiki · minimalism

---

### Gentoo Linux - Wikipedia
- **source_id:** ec0ea67a-3f1b-4d9c-8e2a-7b5d4f1c6a9e · **tipo:** url
- **sostanza:** Wikipedia su Gentoo: distribuzione source-based con Portage (sistema build emerge), USE flags per compilazione personalizzata, governance dual Foundation+Council, nota per flessibilità estrema e possibilità di ottimizzazione per hardware specifico.
- **keyword/entità:** Gentoo · Portage · emerge · USE flags · source-based · Foundation · Council · optimization · customization

---

### The story of Gentoo management
- **source_id:** c50818ee-7d3a-4c1f-9b5e-2a6d8f4c1b7e · **tipo:** url
- **sostanza:** Articolo dettagliato sulla storia della governance di Gentoo: dualismo Foundation (legale/finanziario) vs Council (tecnico), crisi di leadership storiche, tentativi di fork (Sabayon, Calculate), evoluzione verso modello più collaborativo.
- **keyword/entità:** Gentoo · Foundation · Council · governance · leadership crisis · fork · Sabayon · open source governance

---

### How to choose a Linux distro - AlexHost
- **source_id:** a181915b-6c4e-4f2a-9d8b-3e7c1f5a4d2e · **tipo:** url
- **sostanza:** Guida pratica alla scelta della distribuzione Linux: confronto tra distro per principianti (Ubuntu, Mint), intermedi (Fedora, openSUSE) e avanzati (Arch, Gentoo); criteri: hardware, uso previsto, supporto community, stabilità vs rolling.
- **keyword/entità:** Linux distro choice · Ubuntu · Linux Mint · Fedora · openSUSE · Arch · Gentoo · beginner · rolling release

---

### Independent GNU/Linux distributions - DistrOSList
- **source_id:** 838f013c-2d9e-4b7c-8f1a-5e3d6b9c2f4a · **tipo:** url
- **sostanza:** Lista esaustiva (676k caratteri) di distribuzioni Linux indipendenti (non derivate da Debian/RPM/Arch): include Alpine, Void Linux, NixOS, Gentoo, Slackware, Kiss Linux e decine di altri progetti con descrizione, stato di sviluppo e caratteristiche principali.
- **keyword/entità:** independent distros · Alpine · Void Linux · NixOS · Slackware · Kiss Linux · DistrOSList · GNU/Linux

---

### Linux distribution - Wikipedia
- **source_id:** 7fcae4ca-8b3f-4d2e-9c1a-6e5d4b8a3c7f · **tipo:** url
- **sostanza:** Articolo Wikipedia sulle distribuzioni Linux: storia da Slackware/Debian 1993, famiglie principali (Debian, RPM-based, Arch, Gentoo), concetti kernel/userland/init system, modelli di rilascio (stable vs rolling), confronto licenze.
- **keyword/entità:** Linux distribution · history · Slackware · Debian · RPM · kernel · userland · init · stable · rolling release

---

### List of Linux distributions - Wikipedia
- **source_id:** f8f65e4f-9c4a-4d7b-8e2f-1a6c5b3d9e7a · **tipo:** url
- **sostanza:** Lista Wikipedia di distribuzioni Linux organizzata per famiglia (Debian-based, RPM-based, Arch-based, ecc.) con timeline di sviluppo; include albero genealogico delle distribuzioni e note su distro discontinue.
- **keyword/entità:** Linux distributions list · Debian-based · RPM-based · Arch-based · genealogy · distro timeline · Wikipedia

---

### So you want to build embedded Linux - Jay Carlson
- **source_id:** 1e1a7472-3d8c-4e1f-9b6a-7f2d5c8b4a1e · **tipo:** url
- **sostanza:** Articolo dettagliato (274k caratteri) di Jay Carlson su Linux embedded: scelta SoC, toolchain cross-compilation, bootloader (U-Boot, Barebox), configurazione kernel per target hardware, Yocto Project vs Buildroot, gestione driver out-of-tree, rootfs minimali.
- **keyword/entità:** embedded Linux · SoC · cross-compilation · U-Boot · Yocto · Buildroot · kernel config · rootfs · Jay Carlson

---

### These are the 5 most beautiful Linux distros
- **source_id:** cfbe3ee6-4a2d-4f8c-9b1e-7d5a3c8f2b6e · **tipo:** url
- **sostanza:** Articolo sui 5 Linux visivamente più belli: Garuda Linux (tema dragonized), Deepin (DE cinese material-style), Zorin OS (simile Windows/macOS), KDE Neon (KDE bleeding edge), Manjaro (Arch user-friendly). Focus su estetica e usabilità.
- **keyword/entità:** Garuda Linux · Deepin · Zorin OS · KDE Neon · Manjaro · desktop aesthetics · Linux beauty

---

### What is CI/CD on Linux Server? - YouStable
- **source_id:** 7503f4e5-c615-4184-b40d-6d09424b95f2 · **tipo:** url
- **sostanza:** Tutorial beginner su CI/CD su server Linux: spiega Continuous Integration (build+test ad ogni commit) e Continuous Delivery/Deployment (promozione a staging/prod), confronto GitHub Actions vs GitLab CI vs Jenkins, esempio pratico con GitLab CI + Docker + Nginx, best practice sicurezza (cosign, Trivy), zero-downtime deployment con blue-green.
- **keyword/entità:** CI/CD · GitHub Actions · GitLab CI · Jenkins · Docker · Nginx · blue-green deployment · cosign · Trivy

---

### What's the best Linux distro for you? - Red Hat
- **source_id:** 3b94d0c7-61b1-49ef-aa6a-5f5aa90667c1 · **tipo:** url
- **sostanza:** Articolo Red Hat sulla scelta della distribuzione Linux: distinzione community distro (Fedora, openSUSE) vs enterprise distro (RHEL, Android), vantaggi enterprise (10 anni lifecycle support RHEL, patch CVE entro 24h, supply chain documentata), focus su RHEL per workload ibridi cloud.
- **keyword/entità:** Red Hat · RHEL · Fedora · enterprise distro · community distro · lifecycle support · CVE patches · hybrid cloud

---

### Debian 13 security question - Reddit r/debian
- **source_id:** 58497bce-9312-4744-bb6f-598bb16ead20 · **tipo:** url
- **sostanza:** Thread Reddit su sicurezza Debian 13 (Trixie): domanda se Debian stabile sia protetta dalle vulnerabilità di privilege escalation recenti (CVE-2026-43284 "Copyfail", CVE-2026-46300 "Fragnasia"). Risposte confermano che Debian applica security patch via debian-security molto rapidamente, spesso prima di Ubuntu/Fedora.
- **keyword/entità:** Debian 13 · Trixie · CVE-2026-43284 · Copyfail · Fragnasia · privilege escalation · debian-security · apt upgrade

---

### morrolinux - YouTube (canale)
- **source_id:** cd4da8b6-06c7-44cf-bc78-2c7d2772b08f · **tipo:** url
- **sostanza:** Pagina del canale YouTube @morrolinux di Moreno Razzoli: 123k iscritti, 757 video su GNU/Linux e open source. Video recenti includono "I created MY OWN DISTRO" (28k views, 10 giorni fa), Bluefin, CachyOS, NixOS, Flatcar Linux, BeOS, SailFish OS, CVE analysis, homelab, privacy.
- **keyword/entità:** morrolinux · YouTube · Moreno Razzoli · 123k subscribers · GNU/Linux · open source · Morros · Bluefin · CachyOS

---

### morrolinux/morros - GitHub (seconda voce)
- **source_id:** b918791c-c242-42b6-8aae-8274746d07b9 · **tipo:** url
- **sostanza:** Seconda acquisizione del repository GitHub morrolinux/morros: conferma README dettagliato con istruzioni template (Step 0-3: prerequisiti, cosign, base image, switch), lista base image (Bazzite, Aurora, Bluefin, Fedora Atomic), comandi Justfile (build, build-qcow2, spawn-vm), community examples (m2os, bOS, Homer, AmyOS, VeneOS).
- **keyword/entità:** morrolinux/morros · bootc switch · cosign · Justfile · qcow2 · ISO · community images · artifacthub

---

### Debian - modello governance costituzionale
- **source_id:** 1a2b3c4d-5e6f-4a7b-8c9d-0e1f2a3b4c5d · **tipo:** text
- **sostanza:** Analisi del modello di governance Debian: Social Contract, Debian Free Software Guidelines (DFSG), Debian Policy Manual, General Resolution votate da tutti i Developer (1000+), Debian Project Leader eletto annualmente, Technical Committee per decisioni tecniche.
- **keyword/entità:** Debian · governance · Social Contract · DFSG · GR · DPL · Technical Committee · constitutional model

---

### Fedora - modello governance corporativo
- **source_id:** 2b3c4d5e-6f7a-4b8c-9d0e-1f2a3b4c5d6e · **tipo:** text
- **sostanza:** Analisi governance Fedora: sponsor principale Red Hat (IBM), Fedora Council come organo di governance, Engineering Steering Committee (FESCo) per decisioni tecniche, sistema di voto dei contributor, ciclo rilascio 6 mesi, rapporto con RHEL upstream.
- **keyword/entità:** Fedora · Red Hat · IBM · Fedora Council · FESCo · contributor · RHEL upstream · 6-month cycle

---

### Arch Linux - modello governance do-ocracy
- **source_id:** 3c4d5e6f-7a8b-4c9d-0e1f-2a3b4c5d6e7f · **tipo:** text
- **sostanza:** Analisi governance Arch Linux: modello do-ocracy (chi fa decide), Trusted User (TU) per gestione AUR e pacchetti community, Developer per pacchetti core, mailing list come principale mezzo di comunicazione, assenza di corporate sponsor dominante.
- **keyword/entità:** Arch Linux · do-ocracy · Trusted User · AUR · Developer · mailing list · community governance

---

### Gentoo - modello governance Foundation + Council
- **source_id:** 4d5e6f7a-8b9c-4d0e-1f2a-3b4c5d6e7f8a · **tipo:** text
- **sostanza:** Analisi governance Gentoo: Gentoo Foundation (aspetti legali e finanziari, trademark) e Gentoo Council (decisioni tecniche, eletto annualmente dai developer attivi), sistema di ebuild maintainer, comrel (community relations) per conflitti.
- **keyword/entità:** Gentoo · Foundation · Council · ebuild · maintainer · comrel · trademark · legal entity

---

### NixOS - sistema di pacchetti dichiarativo
- **source_id:** 5e6f7a8b-9c0d-4e1f-2a3b-4c5d6e7f8a9b · **tipo:** url
- **sostanza:** NixOS usa il gestore pacchetti Nix con approccio dichiarativo: configurazione sistema in configuration.nix, build riproducibili, rollback garantito, nessun conflitto dipendenze (ogni pacchetto in store isolato /nix/store/). Alternativa radicale a bootc per immutabilità.
- **keyword/entità:** NixOS · Nix · declarative · configuration.nix · reproducible builds · /nix/store/ · rollback · immutable

---

### OSTree / rpm-ostree
- **source_id:** 6f7a8b9c-0d1e-4f2a-3b4c-5d6e7f8a9b0c · **tipo:** url
- **sostanza:** OSTree è il sistema che sta alla base di Fedora Atomic/Silverblue: commit immutabili del filesystem come un git per l'OS, rpm-ostree aggiunge gestione RPM su OSTree, permette overlay di pacchetti senza rompere l'immutabilità base.
- **keyword/entità:** OSTree · rpm-ostree · Fedora Atomic · immutable filesystem · git-like · overlay packages · Silverblue

---

### Containerfile / Dockerfile syntax
- **source_id:** 7a8b9c0d-1e2f-4a3b-4c5d-6e7f8a9b0c1d · **tipo:** text
- **sostanza:** Documento sulla sintassi Containerfile (equivalente Podman del Dockerfile): istruzioni FROM, RUN, COPY, ADD, ENV, ARG, LABEL. In Morros il Containerfile definisce la base image e chiama build.sh per personalizzazioni.
- **keyword/entità:** Containerfile · Dockerfile · FROM · RUN · COPY · Podman · OCI · image build syntax

---

### GHCR - GitHub Container Registry
- **source_id:** 8b9c0d1e-2f3a-4b4c-5d6e-7f8a9b0c1d2e · **tipo:** url
- **sostanza:** GitHub Container Registry (ghcr.io) è il registro OCI integrato in GitHub; le immagini Morros vengono pubblicate su ghcr.io/morrolinux/morros dopo ogni build. Supporta autenticazione, visibilità pubblica/privata, tagging.
- **keyword/entità:** GHCR · ghcr.io · GitHub Container Registry · OCI registry · container images · authentication · tagging

---

### /etc/skel/ - Linux skeleton directory
- **source_id:** 9c0d1e2f-3a4b-4c5d-6e7f-8a9b0c1d2e3f · **tipo:** text
- **sostanza:** /etc/skel/ è la directory "scheletro" copiata nella home di ogni nuovo utente alla creazione. In Morros viene usata per pre-creare symlink systemd e file di configurazione al momento del build, garantendo che ogni utente abbia la configurazione corretta al primo login.
- **keyword/entità:** /etc/skel/ · skeleton directory · home directory · user provisioning · systemd symlinks · build-time config

---

### systemd - init system e service manager
- **source_id:** 0d1e2f3a-4b5c-4d6e-7f8a-9b0c1d2e3f4a · **tipo:** url
- **sostanza:** systemd è il sistema di init e service manager standard su Linux moderno; gestisce l'avvio del sistema, i servizi (unit files), i target (runlevel). In Morros i symlink systemd pre-creati in /etc/skel/ garantiscono l'abilitazione automatica dei servizi utente.
- **keyword/entità:** systemd · init system · service manager · unit files · targets · user services · symlinks

---

### Podman - container engine rootless
- **source_id:** 1e2f3a4b-5c6d-4e7f-8a9b-0c1d2e3f4a5b · **tipo:** url
- **sostanza:** Podman è il container engine rootless e daemonless alternativo a Docker, usato in Fedora/RHEL. Compatibile con Dockerfile/Containerfile syntax; usato nel Justfile di Morros per build locali con `just build` prima di committare.
- **keyword/entità:** Podman · rootless · daemonless · Containerfile · Fedora · RHEL · local build · just build
