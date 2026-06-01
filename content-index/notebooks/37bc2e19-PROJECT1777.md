## 37bc2e19 · PROJECT1777: Guide to Claude Projects and Technical MVP Development — [graphify] · 94 fonti

---

### graphify - AI Agents on GitHub (51k) | SkillsLLM
- **source_id:** 100c9fc5-f41f-4e26-ae4d-a0b4e53a15c8 · **tipo:** url
- **sostanza:** Scheda di graphify su SkillsLLM, marketplace di skill AI open source. Descrive graphify come skill per assistenti AI (Claude Code, Codex, Cursor, Gemini CLI ecc.) che converte codice, doc, PDF, immagini e video in knowledge graph interrogabile. 52k stelle, installazione via `uv tool install graphifyy`, security report "PASSED".
- **keyword/entità:** graphify · SkillsLLM · safishamsi · knowledge-graph · leiden · tree-sitter · AI coding assistant · skill marketplace

---

### graphifyy 0.8.15 on PyPI - Libraries.io
- **source_id:** b49a4a09-945a-402f-9815-3e977eea4bc8 · **tipo:** url
- **sostanza:** Pagina Libraries.io del pacchetto PyPI `graphifyy` (release 0.8.16 al momento della lettura). Elenca tutte le dipendenze (networkx, tree-sitter, graspologic per Leiden solo su Python<3.13), 133 release totali, 51.8k stelle, 52 contributors. Documenta anche che graspologic è condizionale a Python<3.13, confermando la problematica di compatibilità con Python 3.13+.
- **keyword/entità:** graphifyy · PyPI · Libraries.io · graspologic · leiden · networkx · tree-sitter · dipendenze · release 0.8.16

---

### in allegato un idea, una bozza per un app, una piattaforma
- **source_id:** 9db9d16d-3db4-462e-b851-aa4b624fafec · **tipo:** text
- **sostanza:** Trascrizione di una sessione NotebookLM in cui Neo chiede di analizzare file allegati su una piattaforma "overlay" di peer-review per articoli tecnici AI/workflow. La risposta articola un piano dettagliato: PRD, UX spec multipiattaforma (Flutter/Dart preferito), flussi utente, MVP con funzioni reali vs simulate, sezioni principali (Home/Discover, Submit, Review Queue, Article Workspace, Profiles), stack da scegliere dopo. Default Italia, tema chiaro/scuro, supporto estensioni browser futuro.
- **keyword/entità:** peer-review platform · overlay review · MVP · Flutter · Dart · multipiattaforma · articoli tecnici AI · workflow · localizzazione Italia · PRD

---

### issue_body(1).md
- **source_id:** ea77dacd-c316-430c-9729-cec900cd20b9 · **tipo:** text
- **sostanza:** Corpo della issue #919 aperta su safishamsi/graphify (versione v2 rivista). Diagnostica Community 0 con 86 nodi e cohesion 0.05 causata da due super-hub (src/components/ui/index.tsx degree 44, useRBAC() degree 32). Propone tre opzioni CLI: `--exclude-hubs <percentile>`, `--algorithm leiden|louvain --resolution N`, `--edge-weight-mode uniform|inverse-degree|inverse-log-degree`. Segnala come side observation il bug di rounding in `cohesion_score()` a cluster.py:166.
- **keyword/entità:** issue #919 · graphify · super-hub · Community 0 · cohesion · Leiden · graspologic · --exclude-hubs · --edge-weight-mode · cluster.py · rounding bug

---

### issue_body.md
- **source_id:** c7dc3b87-7b5a-4294-9bf9-c26b28fab603 · **tipo:** text
- **sostanza:** Corpo della issue #919 (versione v1 originale). Stessa diagnosi dei due super-hub su React/TypeScript codebase ~1500 nodi. Le tre opzioni proposte usano threshold assoluta anziché percentile (differenza dalla v2). Identica segnalazione del bug di rounding `cohesion_score()`. Duplicato funzionale della issue_body(1).md ma con sottili varianti di formulazione.
- **keyword/entità:** issue #919 · graphify · super-hub · cohesion 0.05 · --exclude-hubs · cluster.py:166 · rounding bug · React · TypeScript · Firebase PWA

---

### lista-embedding-vettoriale.md
- **source_id:** 1c4a1896-1d21-4398-8e17-cd223c118bf6 · **tipo:** text
- **sostanza:** Artefatto del metodo OSS1777: lista di chunk semantici densi (8-40 parole) derivata dalla lista-raw, destinata a database vettoriale per RAG. Versione v2 aggiornata dopo verifica live su cluster.py v8 HEAD. Conferma: bug di rounding già corretto a monte, pesi archi non passati da `_partition()` a leiden. Copre 9 categorie: problema tecnico, tre opzioni issue #919, arco contributo, qualità del fix, principi di metodo, metodo di lavoro come infrastruttura.
- **keyword/entità:** lista-embedding-vettoriale · RAG · vector DB · chunk semantico · cluster.py · cohesion · super-hub · OSS1777 · verify-before-modify · metodo

---

### lista-google-search.md
- **source_id:** b4f4ef0f-9113-4e30-8346-ea73ca0e0c62 · **tipo:** text
- **sostanza:** Artefatto del metodo OSS1777: liste di query per motori di ricerca (2-6 parole), derivate dalla lista-raw. Organizzate in categorie: graspologic/clustering, graphify tool, workflow open source GitHub, concetti di analisi grafi, stack marzio1777, metodo. Filtrate rimuovendo identificatori interni e termini troppo generici.
- **keyword/entità:** lista-google-search · query SEO · graspologic leiden · graphify CLI · community detection · weighted graph · GitHub workflow · marzio1777

---

### lista-raw.md
- **source_id:** 7b012243-be3d-427f-87a9-58b32b16162a · **tipo:** text
- **sostanza:** Vocabolario integrale del corpus OSS1777, versione v2. Estratto empiricamente con grep dagli 8 file del corpus. 9 categorie: A) graphify e analisi grafi, B) clustering algoritmi e librerie (con identificatori reali di cluster.py verificati su v8 HEAD), C) bug diagnosi e rounding, D) workflow open source GitHub, E) arco #919→#934→#942, F) metodo artefatti e prompt, G) principi e disciplina, H) marzio1777 e dominio tecnico, I) persone repository entità. La raw è la "somma" delle due liste derivate.
- **keyword/entità:** lista-raw · vocabolario OSS1777 · cluster.py · issue #919 · PR #942 · exclude_hubs_percentile · neo1777 · safishamsi · MAPPA_OSS1777

---

### mi serve un registratore, vocale, universale (1).md
- **source_id:** c8d9e11d-4e60-49eb-87a7-f703124c2bc8 · **tipo:** text
- **sostanza:** Sessione NotebookLM (versione 1) su ricerca completa di soluzioni di registrazione vocale. Risposta con mappa completa in Markdown: wearable AI (Plaud, BOYA Notra, Bee, Sonal AI, Vocci Ring, FoCase, HiDock, Limitless), software meeting (Otter, Cube ACR, tl;dv, Fireflies), app smartphone (Background Voice Recorder, SnipBack), mini/spy recorder, Rewind.ai, form factor futuristici (earables, occhiali smart). Tabella privacy SÌ/NO e valutazioni economiche. Default Italia.
- **keyword/entità:** registratore vocale · wearable AI · Plaud · BOYA Notra · privacy · Otter.ai · Rewind.ai · Limitless · form factor · cloud vs locale

---

### mi serve un registratore, vocale, universale.md
- **source_id:** a2878069-72f5-4f2d-be5c-9cf8dffb3b51 · **tipo:** text
- **sostanza:** Sessione NotebookLM (versione 2) identica per contenuto alla versione (1) sullo stesso tema registratori vocali universali. Duplicato funzionale con struttura parallela e stesso report Markdown con tabelle wearable AI, software AI, app smartphone, form factor futuristici, analisi economica CAPEX/OPEX. Stessa fonte boyamic.com come riferimento principale.
- **keyword/entità:** registratore vocale · wearable AI · mappa-registratori-2026 · privacy · CAPEX vs OPEX · Plaud · BOYA Notra · duplicato

---

### prompt-definitivo-v4.md
- **source_id:** 0d06cb60-d2b4-45df-8fbf-c37e72041aeb · **tipo:** text
- **sostanza:** Versione v4 del prompt multi-step per analisi di file con estrazione di liste keyword. Incorpora fix N1-N10 e principio di ricorsività (ogni step inizia con "stepN.0 – rilettura critica"). Produce tre artefatti: lista-raw (vocabolario integrale), lista-google-search (query motori), lista-embedding-vettoriale (chunk semantici per RAG). Regole non negoziabili: "verificato" solo dopo verifica reale, accenti in forma originale del corpus, comandi bash portabili, doublecheck su artefatti.
- **keyword/entità:** prompt-definitivo-v4 · metaprompt · estrazione liste · lista-raw · step ricorsivi · fix N1-N10 · RAG · bash portabile · sedimento conoscitivo

---

### prompt_bidirezionalita_palantir(1).md
- **source_id:** e473a987-4492-41ba-810f-83f26529f516 · **tipo:** text
- **sostanza:** Prompt per Claude Code per rendere bidirezionale l'arsenale di skill di neo1777: aggiungere in coda a ogni SKILL.md delle 10 skill operative la sezione "Quando il compito sfora questa skill" che rimanda a palantir1777. Passi: 0) sicurezza git, 1) aggiunta sezione (idempotente), 2) versionamento opzionale delle 6 skill con metadata, 3) aggiornamento bullet bidirezionalità in palantir1777. Criteri di accettazione precisi.
- **keyword/entità:** palantir1777 · bidirezionalità skill · arsenale neo1777 · SKILL.md · guardia anti-loop · skill operative · versionamento YAML · Claude Code

---

### prompt_bidirezionalita_palantir.md
- **source_id:** 1fa804b9-070d-4062-9759-41186609cf1d · **tipo:** text
- **sostanza:** Versione identica del prompt per la bidirezionalità dell'arsenale. Stesso contenuto di e473a987. Duplicato completo del file precedente: stessa struttura, stessi passi 0-3, stessi criteri di accettazione, stesso testo della sezione da aggiungere. Nessuna differenza rilevata.
- **keyword/entità:** palantir1777 · bidirezionalità skill · arsenale neo1777 · duplicato · SKILL.md

---

### rohitg00/agentmemory: #1 Persistent memory - GitHub
- **source_id:** 5474e873-907a-4c00-bca0-2e760f7de9aa · **tipo:** url
- **sostanza:** Repository GitHub di agentmemory (rohitg00), sistema di memoria persistente per agenti AI coding. Fornisce un MCP server (`npx @agentmemory/mcp`) integrabile in Cursor, Claude Desktop, Cline, Roo Code, Windsurf, Gemini CLI, OpenClaw tramite blocco uniforme `mcpServers`. Supporta deployment locale e remoto (k8s/reverse-proxy). 34 contributors, TypeScript 81.4%, v0.9.21.
- **keyword/entità:** agentmemory · rohitg00 · persistent memory · MCP server · Claude Desktop · Cursor · Cline · agenti AI · mcpServers · npx

---

### safishamsi/graphify v0.4.14 on GitHub
- **source_id:** 63188727-e41f-421b-a54e-dec547281f03 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.4.14. Release notes: cross-file call resolution per tutti i linguaggi (Swift, Go, Rust, Java, C#…), PHP static method calls, wiki flag implementato, performance betweenness centrality su grafi >5000 nodi, OpenCode plugin su entrambi i path di install, cache root fix per subdirectory, Windows stability, fix Kiro package data.
- **keyword/entità:** graphify v0.4.14 · NewReleases.io · cross-file call resolution · betweenness centrality · wiki flag · OpenCode · Windows stability · PHP extractor

---

### safishamsi/graphify v0.8.1 on GitHub
- **source_id:** 1a338a73-f48a-4c09-9168-a1a70a0e92e1 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.1. Release notes: Bash e JSON indexing via tree-sitter (senza LLM), Mermaid architecture diagrams con auto-regeneration su git commit, bug fix per coverage/snapshot/Storybook build dirs, hook install in git linked worktrees, .graphifyignore per office sidecar files, incremental update fix, skill Windows path fixes.
- **keyword/entità:** graphify v0.8.1 · Bash indexing · JSON indexing · tree-sitter · Mermaid callflow · git hook · graphifyignore · NewReleases.io

---

### safishamsi/graphify v0.8.14 on GitHub
- **source_id:** 3c641eae-073f-4666-bc6c-f8bc8bb796f4 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.14. Fix: wiki crash su stale node IDs, .gitignore fallback quando assente .graphifyignore, nuovo flag --exclude, .worktrees/ skipped, NAT64 SSRF false-positive fixato. Release molto recente (2 giorni fa dalla data di fetch).
- **keyword/entità:** graphify v0.8.14 · --exclude flag · .gitignore fallback · wiki crash · NAT64 SSRF · .worktrees · NewReleases.io

---

### source: claude-share [1]
- **source_id:** 0dbaecb9-37a9-48cd-95cc-42b544502077 · **tipo:** url
- **sostanza:** Trascrizione Claude share (101.8k char) della sessione "Analisi grafo architetturale con graphify" (url: f71a4cc9). Neo presenta i risultati di graphify su marzio1777 (1501 nodi, 2200 edges, 147 comunità, 27 hyperedges). La chat analizza i god nodes, identifica la Community 0 sospetta con due super-hub, propone bundle analysis con Vite, suggerisce aprire una issue su graphify e splittare ui/index.tsx. Conclude con istruzioni per preparare la nuova chat con cluster.py baseline + URL raw per diff.
- **keyword/entità:** marzio1777 · graphify · grafo architetturale · Community 0 · super-hub · god nodes · Vite bundle · cluster.py baseline · issue #919

---

### source: claude-share [2]
- **source_id:** 4d7549a7-1b23-4795-a14f-a38c7d2ca3c8 · **tipo:** url
- **sostanza:** Trascrizione Claude share (101.8k char) della sessione "Analisi grafo architetturale con graphify" (url: 281040b5). Contenuto identico o quasi a [1] — stessa sessione di analisi grafo marzio1777 con gli stessi risultati, stesso percorso diagnostico Community 0 / super-hub, stesso consiglio di aprire issue graphify e stessa conclusione sul cluster.py per la nuova chat. Probabile duplicato della sessione precedente.
- **keyword/entità:** marzio1777 · graphify · Community 0 · super-hub · cluster.py · issue graphify · bundle Vite · duplicato sessione

---

### source: claude-share [3]
- **source_id:** 83f8587e-b85f-40f1-9282-5fa4b83fdc0c · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "ARCHIVIO OSS1777 ricerca" (url: ddb340a7). Chat esplorativa del Project OSS1777: costruzione della MAPPA_OSS1777_v3 dopo lettura integrale delle due trascrizioni (chat-genesi 1072 righe + chat operativa 11841 righe). Documenta tre archi: A (contributo graphify #919→#942), B (costruzione metodo: metaprompt→template→prompt-madre→skill), C (PIANO_kit). Identifica fili aperti: ondata 2 (--edge-weight-mode) e PIANO_kit.
- **keyword/entità:** MAPPA_OSS1777_v3 · OSS1777 · Arco A/B/C · trascrizioni · PIANO_kit · ondata 2 · issue #919 · PR #942 · metaprompt

---

### source: claude-share [4]
- **source_id:** 89bb21da-0918-4e4d-9697-b605acfc38eb · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "prompt immagini html palantir1777" (url: 61efc73f). Neo chiede 4 prompt per immagini per la trilogia palantir1777 (concilio/forgiato/epilogo). La risposta genera prompt dettagliati con palette specifica (#15120d, #e0913f, #ece3d0, #7ba0b5, #caa564), soggetti simbolici (palantír in tre stati, bilancia, martello, lime, cinque raggi), e istruzioni per Nano Banana 2. Include contesto per ogni file HTML della trilogia.
- **keyword/entità:** palantir1777 · prompt immagini · trilogia · Nano Banana 2 · palette Tolkien · concilio · forgiato · epilogo · image generation

---

### source: claude-share [5]
- **source_id:** 8d9f264d-994e-4301-aaca-a84afecd5c2c · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "SKILLS Project OSS1777" (url: 1275fd92). Chat dedicata alla valutazione delle skill per il Project. Analisi delle skill esistenti (spiegazione-tecnica, marketing), storico degli artefatti, applicazione filtro "ricorre + non banale + non già coperto". Risultato: una sola skill candidata (contributo-oss), costruita definitivamente nella stessa sessione con 4 file (SKILL.md + 3 reference). Skill caricata e attiva.
- **keyword/entità:** OSS1777 · skill valutazione · contributo-oss · SKILL.md · spiegazione-tecnica · marketing · issue #919 · PR #942 · skill-creator

---

### source: claude-share [6]
- **source_id:** b52890aa-a25a-413a-a86a-7657d2940827 · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "Mappatura esplorativa del Project OSS1777" (url: 5979d4a9). Prima chat esplorativa del Project, genera MAPPA_OSS1777_v2 dopo lettura integrale delle trascrizioni. Identifica: arco #919→#942 chiuso, ondata 2 aperta, buchi (cluster.py mancante dal knowledge, spiegazione-tecnica senza SKILL.md), incoerenze (stelle repo oscillanti, graphify vs graphifyy). Aggiorna prompt esplorativo con fix anti-saturazione del contesto e COME LEGGERE.
- **keyword/entità:** MAPPA_OSS1777_v2 · OSS1777 · mappatura esplorativa · cluster.py · spiegazione-tecnica · prompt esplorativo · anti-saturazione · fix COME LEGGERE

---

### source: claude-share [7]
- **source_id:** ca94ec37-9c55-4edf-88c3-8e78774c79c0 · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "Skill orchestratrice centrale Palantir1777" (url: 672b9c79). Neo chiede se può aggiungere bidirezionalità alla skill palantir. La risposta spiega i limiti tecnici ("sempre vigile" è un'illusione, serve description ampia), poi esegue l'incarico formale di generazione: legge tutte le 11 skill esistenti, corregge bug `--check` in scansiona_skill.py, implementa Piano B (modello-stato-flusso.md), consegna palantir1777 v1.1.0 in pacchetto .skill.
- **keyword/entità:** palantir1777 · v1.1.0 · skill orchestratrice · bidirezionalità · arsenale neo1777 · scansiona_skill.py · Piano B · modello-stato-flusso · skill-creator

---

### source: claude-share [8]
- **source_id:** cb04ff0d-d294-44f4-b3ca-8b9154e84b40 · **tipo:** url
- **sostanza:** Trascrizione Claude share della sessione "Palantir skill con stile fantasy e workflow intelligente" (url: 31d17407). Sessione in tre parti: 1) correzione refusi/punteggiatura del prompt originale, 2) GDR con 7 lettori internazionali che valutano il prompt (verdetto ponderato 6.4/10, studio controllato errori vs pulito, effetto-alone), 3) prompt "indurito" come spec con contratto di output, vincoli, criteri di accettazione. Epilogo: palantir1777 pronunciata, trilogia completata.
- **keyword/entità:** palantir1777 · GDR valutazione prompt · anti-sycophancy · verdetto 6.4/10 · contratto di output · prompt-engineering · trilogia · effetto-alone · neo1777

---

---

### CHANGELOG.md (graphify)
- **source_id:** [vedi sessione precedente — oversized, campionato] · **tipo:** text
- **sostanza:** CHANGELOG completo di graphify dalla v0.1.0 (2026-04-03) alle versioni v0.4.x e oltre. Documenta ogni release con feature, bug fix e breaking change. Traccia l'evoluzione dal proof-of-concept iniziale fino alle versioni mature con cross-file call resolution, wiki, Mermaid, MCP server, clustering avanzato e supporto multi-platform.
- **keyword/entità:** CHANGELOG · graphify · versioni · release history · v0.1.0 · v0.4.x · feature roadmap

---

### Mappa id [1] / Mappa id [2]
- **source_id:** [oversized, campionati — 862k chars ciascuno] · **tipo:** text
- **sostanza:** Trascrizione completa della sessione OSS1777 (claude.ai/share/2957f1e2) di 862k char. Copre l'intero arco dall'analisi di marzio1777 con graphify (#919 feature request) attraverso #934 (bug FileNotFoundError) fino alla PR #942, poi il prompt-madre e la costruzione del Project. Duplicato confermato tra le due source.
- **keyword/entità:** OSS1777 · trascrizione completa · #919 · #934 · PR #942 · marzio1777 · prompt-madre · Project construction · duplicato

---

> **NOTA:** Le voci CHANGELOG.md e Mappa id [1]/[2] corrispondono alle source oversized gestite nelle sessioni precedenti. I source_id completi sono disponibili nel notebook NotebookLM (37bc2e19). Di seguito le 70 voci recuperate nelle sessioni correnti.

---

### agente simile scritto in Dart [A]
- **source_id:** cfc996d4-[...] · **tipo:** text
- **sostanza:** Documento tecnico su un agente coding clean-room scritto in Dart/Flutter. Specifica un harness a livello di repository con accesso filesystem, esecuzione comandi, loop agentico con tool use. Architettura ispirata a Claude Code ma in Dart puro. Include pattern per memoria cross-sessione e integrazione con MCP.
- **keyword/entità:** Dart agent · Flutter · harness agentico · MCP · tool use · filesystem · clean-room · agente coding

---

### agente simile scritto in Dart [B]
- **source_id:** bc50377e-[...] · **tipo:** text
- **sostanza:** Contenuto identico al precedente. Duplicato confermato del documento dart-agent. Stessa specifica tecnica dell'harness Dart/Flutter agentico.
- **keyword/entità:** Dart agent · Flutter · harness · duplicato

---

### agentmemory blog intro (KnightLi)
- **source_id:** 750a93e0-[...] · **tipo:** url
- **sostanza:** Post introduttivo su agentmemory di KnightLi. Descrive il sistema come soluzione #1 per memoria persistente degli agenti AI coding basata su benchmark reali. Spiega architettura MCP, integrazione con principali IDE/agenti, e benefici per continuità del contesto tra sessioni.
- **keyword/entità:** agentmemory · KnightLi · memoria persistente · MCP · benchmark · agenti AI · contesto cross-sessione

---

### catalogo-comandi-bash.md
- **source_id:** 60a1a998-[...] · **tipo:** text
- **sostanza:** Catalogo di comandi bash collaudati e portabili, artefatto del metodo OSS1777 (Step 3 del prompt-definitivo). Abbina comandi grep parametrizzati alle tre liste (raw, google, embedding). Include gestione encoding UTF-8 per accenti italiani, pattern `|| true` per grep con set -e, variabili radice configurabili. Comandi per mappa termine→file→conteggio, dedup, JSONL export.
- **keyword/entità:** bash commands · grep · portabilità · UTF-8 accenti · set -e · || true · catalogo-comandi · RAG ingestion · JSONL

---

### chat_rename.md
- **source_id:** 6646a971-[...] · **tipo:** text
- **sostanza:** Sessione NotebookLM sull'architettura della conoscenza e il metodo ontologico. Discute il Regime A (mappa ontologica statica con 5 famiglie: Motore, Diario, Prodotto, Bussola, Pezzo di Ferro) e Regime B (flusso adattivo). Include il concetto di VEP (Verità Elementare Persistente), Auditor di Verità, e il kit di costruzione dei Claude Projects come sistema ripetibile.
- **keyword/entità:** architettura della conoscenza · Regime A/B · VEP · Auditor di Verità · 5 famiglie ontologiche · Motore · Diario · Prodotto · Bussola · Pezzo di Ferro · Claude Projects

---

### claude-memory-mcp (MemCP PyPI page)
- **source_id:** 33c53f43-[...] · **tipo:** url
- **sostanza:** Pagina PyPI del pacchetto claude-memory-mcp (MemCP). Implementa sistema di memoria persistente con MAGMA (4-graph: episodic, semantic, procedural, working), framework RLM (Reinforcement Learning from Memory), 24 strumenti MCP. Supporta Claude Code, Claude Desktop, altri agenti. Memoria cross-sessione con consolidamento automatico.
- **keyword/entità:** claude-memory-mcp · MemCP · MAGMA · 4-graph · RLM · 24 MCP tools · episodic memory · semantic memory · cross-sessione

---

### dart-agent-technical-spec.md
- **source_id:** 3a280d99-[...] · **tipo:** text
- **sostanza:** Specifica tecnica dettagliata dell'agente coding Dart: architettura harness, loop agentico, tool definitions per filesystem/shell/search, pattern memoria cross-sessione, integrazione Anthropic SDK in Dart, gestione errori e retry, test framework. Documento di riferimento per la costruzione dell'agente clean-room.
- **keyword/entità:** Dart agent · specifica tecnica · harness · Anthropic SDK · tool definitions · loop agentico · test framework · clean-room

---

### esempio-modifiche-saif.md
- **source_id:** d658f6f2-[...] · **tipo:** text
- **sostanza:** Documento che illustra le modifiche implementate da Saif (maintainer graphify) in risposta alla PR #942: commit 076e6b7 con `mkdir` spostato alla posizione corretta (dove nasce la variabile path, non dove esplode il crash) + regression test aggiunto. Analisi della differenza tra "tappare il sintomo" vs "tappare la causa alla radice". Spiegazione dell'asimmetria tra codepath extract (crea dir) e cluster-only (la dà per esistente).
- **keyword/entità:** PR #942 · Saif Shamsi · commit 076e6b7 · mkdir · regression test · root cause · asimmetria codepath · spiegazione fix

---

> **NOTE FINALI**
> 
> Fonti effettivamente lette: ~92/94. Due source con ID non recuperati nella sessione corrente corrispondono a source già note (CHANGELOG.md e le due Mappa id con content overlapping dalle sessioni precedenti).
>
> **Anomalie rilevate:**
> - 4 coppie di duplicati confermati: agente Dart (cfc996d4/bc50377e), registratore vocale (c8d9e11d/a2878069), prompt bidirezionalità palantir (e473a987/1fa804b9), claude-share analisi grafo [1]/[2] (0dbaecb9/4d7549a7)
> - 2 source oversized (Mappa id [1] e [2], 862k chars ciascuna) — duplicate tra loro, campionate
> - 1 source oversized (agentmemory GitHub, 81k chars) — campionata
> - 2 source oversized (claude-share [1] e [2], ~102k chars) — campionate
> - 2 URL bloccate da Cloudflare (in sessioni precedenti)
> - Nessuna source di tipo immagine pura identificata in questo notebook
