## NB1 — Graphify Project Analysis (5c9588e1)

### graphify README (main)
- **source_id:** (da sessione precedente, titolo ricostruito) · **tipo:** url
- **sostanza:** README principale del repo safishamsi/graphify su GitHub. Descrive il tool per la costruzione di knowledge graph da codebase; pipeline 3-pass (tree-sitter AST locale → faster-whisper locale → estrazione semantica LLM); supporto 31 linguaggi, 18+ piattaforme; 53.5k+ stelle; nome pacchetto `graphifyy` (doppia y).
- **keyword/entità:** graphify · knowledge-graph · tree-sitter · faster-whisper · MCP · Neo4j · 53.5k stars

### Architecture docs / 3-pass pipeline
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Documentazione architetturale della pipeline 3-pass: primo pass estrazione AST locale (tree-sitter), secondo pass trascrizione audio/commenti (faster-whisper), terzo pass estrazione semantica tramite LLM. Leiden community detection per raggruppamento nodi. Riduzione token 500x rispetto a context raw.
- **keyword/entità:** 3-pass · AST · Leiden · community-detection · token-reduction · 500x

### Issue #919 — edge-weight-mode
- **source_id:** (da sessione precedente) · **tipo:** url
- **sostanza:** Issue GitHub #919 propone tre miglioramenti: modalità `edge-weight-mode` (confidence vs degree vs hybrid), super-hub clustering per nodi ad alta connettività, e normalizzazione pesi. Tutte e tre le proposte sono state implementate in v0.8.10 con tag #919.
- **keyword/entità:** edge-weight-mode · super-hub · v0.8.10 · PR#919 · peso-archi

### Contributor analysis
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Analisi della rete contributori di graphify: gap di copertura nelle lingue meno supportate, distribuzione commit concentrata su pochi maintainer, opportunità per contributi OSS mirati (web2md1777, estrazione1777).
- **keyword/entità:** contributori · OSS · gap-analysis · maintainer · commit-distribution

### Neo4j integration patterns
- **source_id:** (da sessione precedente) · **tipo:** url
- **sostanza:** Pattern di integrazione graphify-Neo4j: esportazione del grafo in Cypher, query semantiche su codebase, visualizzazione nodi/archi con Neo4j Browser. Usato in combinazione con MCP server per query contestuali.
- **keyword/entità:** Neo4j · Cypher · visualizzazione · MCP-server · integrazione

### MCP server patterns
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Configurazione del MCP server di graphify tramite `.mcp.json`; esposizione del grafo come tool chiamabile da Claude/Cursor/altri AI coding assistant; git hooks per aggiornamento automatico del grafo ad ogni commit.
- **keyword/entità:** MCP · .mcp.json · git-hooks · AI-coding-assistant · Cursor

### safishamsi/graphify at corti.com
- **source_id:** 4b2ab825 · **tipo:** url
- **sostanza:** Pagina GitHub principale di graphify: 53.5k stelle, versione 0.8.18, riferimento completo comandi CLI, supporto 31 linguaggi, 16+ piattaforme. Descrive la filosofia "ottimizza per la scoperta" e il layer enterprise Penpax.
- **keyword/entità:** graphify · 0.8.18 · CLI · Penpax · enterprise · 31 linguaggi

### README.it-IT.md at v8
- **source_id:** 1599a2b9 · **tipo:** url
- **sostanza:** README in italiano per il branch v8 di graphify. Cita riduzione token 71.5x, pipeline 3-pass, layer enterprise Penpax. Versione localizzata con stessa struttura del README inglese.
- **keyword/entità:** italiano · v8 · 71.5x · Penpax · localizzazione

### Security GitHub (SECURITY.md)
- **source_id:** 934b13a6 · **tipo:** url
- **sostanza:** File SECURITY.md ufficiale di graphify: mitigazione SSRF, protezione XSS, nessun telemetry, versioni supportate dalla 0.3.x in poi. Linee guida per segnalazione vulnerabilità.
- **keyword/entità:** SECURITY · SSRF · XSS · no-telemetry · versioni-supportate

### GitHub Gist — setup guide
- **source_id:** fb352263 · **tipo:** url
- **sostanza:** Guida completa setup graphify + code-review-graph: installazione, configurazione `.mcp.json`, git hooks per aggiornamento automatico, risparmio 500x token. Esempi pratici per Cursor e Claude.
- **keyword/entità:** setup · code-review-graph · git-hooks · 500x · Cursor · Claude

### KnightLi blog — graphify overview
- **source_id:** f12d6042 · **tipo:** url
- **sostanza:** Articolo blog che recensisce graphify: evidenzia le 50k stelle, la pipeline 3-pass, integrazione MCP e Neo4j, riduzione token 500x. Consigliato per team che lavorano su codebase grandi.
- **keyword/entità:** blog · recensione · 50k-stelle · pipeline · riduzione-token

### Java2Graph Reddit
- **source_id:** 64b40876 · **tipo:** url
- **sostanza:** Post Reddit su parser Java → grafo semantico usando graphify. Mostra uso con ladybugDB e query Cypher per navigare la codebase Java. Caso d'uso pratico enterprise.
- **keyword/entità:** Java · Reddit · ladybugDB · Cypher · enterprise · parser

### From 50 Files to One Graph (bloccato)
- **source_id:** d0a48537 · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare challenge (512 chars di contenuto reale). Titolo suggerisce articolo su consolidamento di 50 file in un unico knowledge graph con graphify. Contenuto non leggibile.
- **keyword/entità:** Cloudflare-blocked · knowledge-graph · consolidamento
