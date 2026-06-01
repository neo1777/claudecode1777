## 37bc2e19 · PROJECT1777: Guide to Claude Projects and Technical MVP Development — [graphify] · 94 fonti

---

### graphify - AI Agents on GitHub (51k) | SkillsLLM
- **source_id:** 100c9fc5-f41f-4e26-ae4d-a0b4e53a15c8 · **tipo:** url
- **sostanza:** Scheda di graphify su SkillsLLM, marketplace di skill AI open source. Descrive graphify come skill per assistenti AI (Claude Code, Codex, Cursor, Gemini CLI ecc.) che converte codice, doc, PDF, immagini e video in knowledge graph interrogabile. 52k stelle, installazione via `uv tool install graphifyy`, security report "PASSED" del 16 aprile 2026.
- **keyword/entità:** graphify · SkillsLLM · safishamsi · knowledge-graph · leiden · tree-sitter · AI coding assistant · skill marketplace · 52k stars

---

### graphifyy 0.8.15 on PyPI - Libraries.io
- **source_id:** b49a4a09-945a-402f-9815-3e977eea4bc8 · **tipo:** url
- **sostanza:** Pagina Libraries.io del pacchetto PyPI `graphifyy` alla release 0.8.16. Elenca tutte le dipendenze (networkx, tree-sitter, graspologic condizionale a Python<3.13), 133 release totali, 51.8k stelle, 52 contributors. Conferma che graspologic/Leiden è disponibile solo su Python<3.13 (problema di incompatibilità con 3.13+ già noto).
- **keyword/entità:** graphifyy · PyPI · Libraries.io · graspologic · leiden · networkx · tree-sitter · dipendenze · release 0.8.16 · Python 3.13

---

### in allegato un idea, una bozza per un app, una piattaforma
- **source_id:** 9db9d16d-3db4-462e-b851-aa4b624fafec · **tipo:** text
- **sostanza:** Sessione NotebookLM in cui Neo chiede documentazione tecnica per una piattaforma "overlay" di peer-review per articoli tecnici AI/workflow. La risposta articola PRD, UX spec multipiattaforma (Flutter/Dart preferito), sezioni principali (Home/Discover, Submit, Review Queue, Article Workspace, Profiles, Editor Console), MVP con funzioni reali vs simulate, integrazione dati pubblici italiani, stack da scegliere in seconda fase.
- **keyword/entità:** peer-review platform · overlay review · MVP · Flutter · Dart · multipiattaforma · articoli tecnici AI · PRD · UX spec · localizzazione Italia

---

### issue_body(1).md
- **source_id:** ea77dacd-c316-430c-9729-cec900cd20b9 · **tipo:** text
- **sostanza:** Corpo della issue #919 su safishamsi/graphify (versione v2, rivista). Diagnostica Community 0 con 86 nodi e cohesion 0.05 causata da due super-hub (src/components/ui/index.tsx degree 44, useRBAC() degree 32) su codebase React/TypeScript. Propone tre opzioni CLI: `--exclude-hubs <percentile>`, `--algorithm leiden|louvain --resolution N`, `--edge-weight-mode`. Segnala bug rounding in cohesion_score() come side observation.
- **keyword/entità:** issue #919 · graphify · super-hub · Community 0 · cohesion · Leiden · --exclude-hubs · --edge-weight-mode · cluster.py · rounding bug · React TypeScript

---

### issue_body.md
- **source_id:** c7dc3b87-7b5a-4294-9bf9-c26b28fab603 · **tipo:** text
- **sostanza:** Corpo della issue #919 (versione v1 originale). Stessa diagnosi dei due super-hub su React/TypeScript codebase ~1500 nodi. Stessa struttura e segnalazione del bug di rounding. Usa threshold assoluta anziché percentile (piccola variante rispetto alla v2). Duplicato funzionale di ea77dacd.
- **keyword/entità:** issue #919 · graphify · super-hub · cohesion 0.05 · --exclude-hubs · cluster.py:166 · rounding bug · React · Firebase PWA · duplicato

---

### lista-embedding-vettoriale.md
- **source_id:** 1c4a1896-1d21-4398-8e17-cd223c118bf6 · **tipo:** text
- **sostanza:** Artefatto metodo OSS1777: lista di chunk semantici densi (8-40 parole) per database vettoriale RAG, derivata dalla lista-raw. Versione v2 verificata sul sorgente live cluster.py v8 HEAD. Copre 9 aree: problema tecnico Community 0, tre opzioni issue #919, stato implementazione (exclude_hubs implementato, edge-weight-mode no), arco contributo, qualità del fix, principi di metodo (verify-before-modify, measure-before-cutting, honest-reporting).
- **keyword/entità:** lista-embedding-vettoriale · RAG · vector DB · chunk semantico · cluster.py · super-hub · OSS1777 · verify-before-modify · metodo · arco contributo

---

### lista-google-search.md
- **source_id:** b4f4ef0f-9113-4e30-8346-ea73ca0e0c62 · **tipo:** text
- **sostanza:** Artefatto metodo OSS1777: liste di query per motori di ricerca (2-6 parole) derivate dalla lista-raw. Categorie: graspologic/clustering (leiden documentation, weight_attribute, louvain_communities), graphify tool, workflow open source GitHub, concetti analisi grafi, stack marzio1777, metodo (metaprompt, vector database). Filtrate rimuovendo identificatori interni e termini generici.
- **keyword/entità:** lista-google-search · query SEO · graspologic · leiden · graphify CLI · community detection · GitHub workflow · marzio1777 · metaprompt

---

### lista-raw.md
- **source_id:** 7b012243-be3d-427f-87a9-58b32b16162a · **tipo:** text
- **sostanza:** Vocabolario integrale del corpus OSS1777, versione v2. Estratto empiricamente con grep dagli 8 file del corpus. 9 categorie: A) graphify e analisi grafi, B) clustering algoritmi (con identificatori reali di cluster.py verificati su v8 HEAD), C) bug/rounding, D) workflow open source GitHub, E) arco #919→#934→#942, F) metodo artefatti e prompt, G) principi e disciplina, H) marzio1777 dominio tecnico, I) persone repository entità. Base della lista-google e lista-embedding.
- **keyword/entità:** lista-raw · vocabolario OSS1777 · cluster.py · issue #919 · PR #942 · exclude_hubs_percentile · neo1777 · safishamsi · MAPPA_OSS1777

---

### mi serve un registratore, vocale, universale (1).md
- **source_id:** c8d9e11d-4e60-49eb-87a7-f703124c2bc8 · **tipo:** text
- **sostanza:** Sessione (v1) su ricerca completa di soluzioni di registrazione vocale universale. Risposta con mappa Markdown: wearable AI (Plaud, BOYA Notra, Bee, Sonal AI, Vocci Ring, FoCase, HiDock, Limitless), software meeting (Otter, Cube ACR, tl;dv, Fireflies), app smartphone, mini/spy recorder, Rewind.ai, form factor futuristici. Tabella privacy SÌ/NO, valutazioni economiche CAPEX vs OPEX. Default Italia.
- **keyword/entità:** registratore vocale · wearable AI · Plaud · BOYA Notra · privacy · Otter.ai · Rewind.ai · form factor · cloud vs locale · CAPEX OPEX

---

### mi serve un registratore, vocale, universale.md
- **source_id:** a2878069-72f5-4f2d-be5c-9cf8dffb3b51 · **tipo:** text
- **sostanza:** Sessione (v2) identica per contenuto alla versione (1) sullo stesso tema registratori vocali. Duplicato funzionale completo: stesso report Markdown con tabelle wearable AI, software AI, app smartphone, form factor futuristici, analisi economica. Stessa fonte boyamic.com come riferimento principale.
- **keyword/entità:** registratore vocale · wearable AI · mappa-registratori-2026 · privacy · duplicato · BOYA Notra · Plaud · Limitless

---

### prompt-definitivo-v4.md
- **source_id:** 0d06cb60-d2b4-45df-8fbf-c37e72041aeb · **tipo:** text
- **sostanza:** Versione v4 del prompt multi-step per analisi di file con estrazione liste keyword. Incorpora fix N1-N10 e principio di ricorsività ("stepN.0 – rilettura critica"). Produce tre artefatti: lista-raw (vocabolario integrale), lista-google-search (query motori), lista-embedding-vettoriale (chunk RAG). Regole: "verificato" solo dopo verifica reale, accenti in forma originale, bash portabile con radice configurabile, doublecheck obbligatorio.
- **keyword/entità:** prompt-definitivo-v4 · metaprompt · estrazione liste · lista-raw · step ricorsivi · fix N1-N10 · RAG · bash portabile · sedimento conoscitivo

---

### prompt_bidirezionalita_palantir(1).md
- **source_id:** e473a987-4492-41ba-810f-83f26529f516 · **tipo:** text
- **sostanza:** Prompt per Claude Code per rendere bidirezionale l'arsenale di skill di neo1777: aggiungere a ogni SKILL.md delle 10 skill operative la sezione "Quando il compito sfora questa skill" che rimanda a palantir1777. Passi: 0) sicurezza git, 1) aggiunta idempotente, 2) versionamento opzionale 6 skill con metadata, 3) aggiornamento bullet bidirezionalità in palantir1777. Criteri di accettazione precisi.
- **keyword/entità:** palantir1777 · bidirezionalità skill · arsenale neo1777 · SKILL.md · guardia anti-loop · skill operative · versionamento YAML

---

### prompt_bidirezionalita_palantir.md
- **source_id:** 1fa804b9-070d-4062-9759-41186609cf1d · **tipo:** text
- **sostanza:** Versione identica del prompt per la bidirezionalità dell'arsenale. Duplicato completo di e473a987: stessa struttura, stessi passi 0-3, stessi criteri di accettazione, stesso testo della sezione da aggiungere a ogni SKILL.md.
- **keyword/entità:** palantir1777 · bidirezionalità skill · arsenale neo1777 · SKILL.md · duplicato

---

### rohitg00/agentmemory: #1 Persistent memory - GitHub
- **source_id:** 5474e873-907a-4c00-bca0-2e760f7de9aa · **tipo:** url
- **sostanza:** Repository GitHub di agentmemory (rohitg00), sistema di memoria persistente #1 per agenti AI coding basato su benchmark reali. MCP server (`npx @agentmemory/mcp`) integrabile in Cursor, Claude Desktop, Cline, Roo Code, Windsurf, Gemini CLI, OpenClaw tramite blocco uniforme `mcpServers`. Supporta deployment locale e remoto. 34 contributors, TypeScript 81.4%, v0.9.21.
- **keyword/entità:** agentmemory · rohitg00 · persistent memory · MCP server · Claude Desktop · Cursor · Cline · agenti AI · mcpServers

---

### safishamsi/graphify v0.4.14 on GitHub
- **source_id:** 63188727-e41f-421b-a54e-dec547281f03 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.4.14. Release notes: cross-file call resolution per tutti i linguaggi (Swift, Go, Rust, Java, C#, Kotlin…), PHP static method calls e constant references, wiki flag implementato (`to_wiki()`), performance betweenness centrality su grafi >5000 nodi, OpenCode plugin, cache root fix, Windows stability.
- **keyword/entità:** graphify v0.4.14 · NewReleases.io · cross-file call resolution · betweenness centrality · wiki flag · OpenCode · Windows stability · PHP extractor

---

### safishamsi/graphify v0.8.1 on GitHub
- **source_id:** 1a338a73-f48a-4c09-9168-a1a70a0e92e1 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.1. Release notes: Bash e JSON indexing via tree-sitter (senza LLM, no token), Mermaid architecture diagrams con auto-regeneration su git commit, bug fix per coverage/snapshot/Storybook build dirs, hook install in git linked worktrees, .graphifyignore per sidecar files, incremental update fix, Windows path fix.
- **keyword/entità:** graphify v0.8.1 · Bash indexing · JSON indexing · tree-sitter · Mermaid callflow · git hook · graphifyignore · NewReleases.io

---

### safishamsi/graphify v0.8.14 on GitHub
- **source_id:** 3c641eae-073f-4666-bc6c-f8bc8bb796f4 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.14. Fix: wiki crash su stale node IDs, .gitignore fallback quando assente .graphifyignore, nuovo flag --exclude, .worktrees/ skipped durante indexing, NAT64 SSRF false-positive fixato per host come arxiv.org su IPv6-only network.
- **keyword/entità:** graphify v0.8.14 · --exclude flag · .gitignore fallback · wiki crash · NAT64 SSRF · .worktrees · NewReleases.io

---

### source: claude-share [1]
- **source_id:** 0dbaecb9-37a9-48cd-95cc-42b544502077 · **tipo:** url
- **sostanza:** Trascrizione Claude share (102k char, url: f71a4cc9) della sessione "Analisi grafo architetturale con graphify". Neo presenta i risultati di graphify su marzio1777 (1501 nodi, 2200 edges, 147 comunità, 27 hyperedges). Analisi god nodes (useAuth() 42 edges, db 34, useRBAC() 32), identificazione Community 0 sospetta con super-hub, proposta bundle analysis Vite, consiglio di aprire issue su graphify e splittare ui/index.tsx. Prepara strategia per nuova chat con cluster.py baseline.
- **keyword/entità:** marzio1777 · graphify · Community 0 · super-hub · god nodes · Vite bundle · cluster.py baseline · issue #919 · analisi grafo architetturale

---

### source: claude-share [2]
- **source_id:** 4d7549a7-1b23-4795-a14f-a38c7d2ca3c8 · **tipo:** url
- **sostanza:** Trascrizione Claude share (102k char, url: 281040b5) della stessa sessione "Analisi grafo architetturale con graphify". Contenuto quasi identico a [1] — stessi risultati graphify su marzio1777, stesso percorso diagnostico Community 0/super-hub, stesso consiglio issue graphify, stessa conclusione su cluster.py per la nuova chat. Probabile versione parallela/duplicato della sessione precedente.
- **keyword/entità:** marzio1777 · graphify · Community 0 · super-hub · cluster.py · issue graphify · bundle Vite · duplicato sessione

---

### source: claude-share [3]
- **source_id:** 83f8587e-b85f-40f1-9282-5fa4b83fdc0c · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: ddb340a7) della sessione "ARCHIVIO OSS1777 ricerca". Chat esplorativa del Project OSS1777 che costruisce MAPPA_OSS1777_v3 dopo lettura integrale delle due trascrizioni (1072 + 11841 righe). Documenta tre archi: A (contributo graphify #919→#942), B (costruzione metodo: metaprompt→template→prompt-madre→skill), C (PIANO_kit). Fili aperti: ondata 2 (--edge-weight-mode) e PIANO_kit.
- **keyword/entità:** MAPPA_OSS1777_v3 · OSS1777 · Arco A/B/C · trascrizioni · PIANO_kit · ondata 2 · issue #919 · PR #942 · metaprompt

---

### source: claude-share [4]
- **source_id:** 89bb21da-0918-4e4d-9697-b605acfc38eb · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: 61efc73f) della sessione "prompt immagini html palantir1777". Neo chiede 4 prompt per immagini per la trilogia palantir1777. La risposta genera prompt dettagliati con palette specifica (#15120d, #e0913f, #ece3d0, #7ba0b5, #caa564), soggetti simbolici (palantír in tre stati, bilancia, martello, lime, raggi), istruzioni per Nano Banana 2 con descrizione dei tre file HTML della trilogia.
- **keyword/entità:** palantir1777 · prompt immagini · trilogia · Nano Banana 2 · palette Tolkien · concilio · forgiato · epilogo · image generation

---

### source: claude-share [5]
- **source_id:** 8d9f264d-994e-4301-aaca-a84afecd5c2c · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: 1275fd92) della sessione "SKILLS Project OSS1777". Chat di valutazione delle skill per il Project: analisi skill esistenti (spiegazione-tecnica, marketing), filtro "ricorre + non banale + non già coperto". Risultato: una sola skill candidata (contributo-oss), costruita e caricata nella stessa sessione. Skill attiva con 4 file: SKILL.md + 3 reference (issue #919, #934, PR #942 verbatim).
- **keyword/entità:** OSS1777 · skill valutazione · contributo-oss · SKILL.md · spiegazione-tecnica · marketing · issue #919 · PR #942 · skill-creator

---

### source: claude-share [6]
- **source_id:** b52890aa-a25a-413a-a86a-7657d2940827 · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: 5979d4a9) della sessione "Mappatura esplorativa del Project OSS1777". Prima chat esplorativa che genera MAPPA_OSS1777_v2. Identifica: arco #919→#942 chiuso, ondata 2 aperta, buchi (cluster.py mancante dal knowledge, spiegazione-tecnica senza SKILL.md). Evolve il prompt esplorativo con fix anti-saturazione del contesto (COME LEGGERE, leggere-e-annotare a blocchi). Discute strategia "blind" per sessione gemella.
- **keyword/entità:** MAPPA_OSS1777_v2 · OSS1777 · mappatura esplorativa · cluster.py · prompt esplorativo · anti-saturazione · COME LEGGERE · sessione gemella · blind

---

### source: claude-share [7]
- **source_id:** ca94ec37-9c55-4edf-88c3-8e78774c79c0 · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: 672b9c79) della sessione "Skill orchestratrice centrale Palantir1777". Neo descrive la skill palantir; la chat spiega limiti tecnici ("sempre vigile" è illusione), poi esegue incarico formale: legge tutte le 11 skill, corregge bug `--check` in scansiona_skill.py, implementa Piano B (modello-stato-flusso.md), consegna palantir1777 v1.1.0 come pacchetto .skill.
- **keyword/entità:** palantir1777 · v1.1.0 · skill orchestratrice · bidirezionalità · arsenale neo1777 · scansiona_skill.py · Piano B · modello-stato-flusso · skill-creator

---

### source: claude-share [8]
- **source_id:** cb04ff0d-d294-44f4-b3ca-8b9154e84b40 · **tipo:** url
- **sostanza:** Trascrizione Claude share (url: 31d17407) della sessione "Palantir skill con stile fantasy e workflow intelligente". Tre parti: 1) correzione refusi del prompt originale, 2) GDR con 7 lettori internazionali che valutano il prompt (verdetto ponderato 6.4/10, studio controllato sull'effetto-alone degli errori), 3) prompt indurito come spec con contratto di output. Epilogo: palantir1777 pronunciata, trilogia completata, Neo sposta la chat nel Project.
- **keyword/entità:** palantir1777 · GDR valutazione prompt · anti-sycophancy · verdetto 6.4/10 · contratto di output · prompt-engineering · trilogia · effetto-alone · neo1777

---

---

> Le seguenti voci (fonti ~1–70) sono state lette nelle sessioni precedenti. I source_id completi sono ricostruiti dalla lista notebook_get del notebook 37bc2e19.

---

### CHANGELOG.md (graphify)
- **source_id:** [oversized — campionato da file persistito] · **tipo:** text
- **sostanza:** CHANGELOG completo di graphify dalla v0.1.0 (2026-04-03) alle versioni v0.4.x e oltre (58k chars). Documenta ogni release con feature, bug fix e breaking change. Traccia l'evoluzione dal proof-of-concept iniziale fino a versioni mature con cross-file call resolution, wiki, Mermaid, MCP server, clustering avanzato e supporto multi-platform per 18+ IDE/agenti.
- **keyword/entità:** CHANGELOG · graphify · release history · v0.1.0 · v0.4.x · feature roadmap · bug fix

---

### Mappa id [1]
- **source_id:** 0bf5a5a6-[...] · **tipo:** text
- **sostanza:** Trascrizione completa (862k chars) della sessione principale OSS1777 (claude.ai/share/2957f1e2). Copre l'intero arco: analisi di marzio1777 con graphify → issue #919 (feature request, 3 opzioni, accolta in 3 ore con v0.8.10) → issue #934 (FileNotFoundError su cluster-only) → PR #942 (fix mkdir 1 riga, chiusa non mergeata, reimplementata da Saif). Include poi la costruzione del metodo: METAPROMPT1777, template, prompt-madre, genesi del Project.
- **keyword/entità:** OSS1777 · trascrizione completa · issue #919 · issue #934 · PR #942 · marzio1777 · prompt-madre · Project · METAPROMPT1777

---

### Mappa id [2]
- **source_id:** 258d40de-[...] · **tipo:** text
- **sostanza:** Duplicato confermato di Mappa id [1]. Stesso contenuto di 862k chars, stessa URL claude.ai/share/2957f1e2. Fonte identica, versione parallela caricata nel notebook.
- **keyword/entità:** duplicato · OSS1777 · trascrizione · issue #919 · PR #942

---

### safishamsi/graphify (README principale)
- **source_id:** 67556189-b3c9-44a3-8d13-c98bc6037780 · **tipo:** url
- **sostanza:** README ufficiale del repository safishamsi/graphify. Descrive graphify come AI coding assistant skill che trasforma qualsiasi cartella (codice, doc, PDF, immagini, video) in knowledge graph interrogabile. Funziona in Claude Code, Codex, OpenCode, Cursor, Gemini CLI, GitHub Copilot CLI e altri. Output: graph.html, GRAPH_REPORT.md, graph.json. Include installazione, configurazione per piattaforma, extras opzionali, comandi avanzati (PR dashboard, export callflow-html, merge-graphs).
- **keyword/entità:** graphify · README · safishamsi · knowledge graph · /graphify · graph.html · GRAPH_REPORT.md · AI coding assistant · multi-platform

---

### graphify GitHub (issues/discussions overview)
- **source_id:** 3043a604-[...] · **tipo:** url
- **sostanza:** URL claude-world.com bloccata da Cloudflare al momento del fetch. Contenuto non recuperato.
- **keyword/entità:** Cloudflare blocked · URL non recuperata

---

### blog.gopenai.com (graphify article)
- **source_id:** a327ca1c-[...] · **tipo:** url
- **sostanza:** URL blog.gopenai.com bloccata da Cloudflare al momento del fetch. Contenuto non recuperato.
- **keyword/entità:** Cloudflare blocked · URL non recuperata

---

### graphify Issue #290 (graspologic Python 3.13 incompatibility)
- **source_id:** [da sessione precedente] · **tipo:** url
- **sostanza:** Issue su safishamsi/graphify che segnala l'incompatibilità di graspologic con Python 3.13+ (ModuleNotFoundError). La soluzione implementata è un fallback automatico a Louvain di networkx quando graspologic non è disponibile. Documenta il cambio architetturale che ha reso la dipendenza graspologic opzionale e condizionale a Python<3.13.
- **keyword/entità:** graphify · issue #290 · graspologic · Python 3.13 · Louvain fallback · networkx · incompatibilità

---

### graphify Issue #563 (rationale-node leakage + calls direction)
- **source_id:** [da sessione precedente] · **tipo:** url
- **sostanza:** Issue su safishamsi/graphify che segnala due bug: 1) leakage di rationale-node (nodi creati per annotazioni WHY:/NOTE: che finiscono nel clustering alterando le comunità), 2) inversione della direzione degli archi calls (A chiama B vs B chiama A). Documenta la diagnostica e propone fix per entrambi.
- **keyword/entità:** graphify · issue #563 · rationale-node leakage · calls direction inversion · clustering · edge direction · bug

---

### OSS1777 Project (setup/overview document)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento di setup del Project OSS1777 su claude.ai. Descrive il progetto come contributo open source a graphify di safishamsi. Definisce la struttura del Project, le skill installate (spiegazione-tecnica, marketing, contributo-oss), le trascrizioni caricate come knowledge base, e le istruzioni operative per le chat. Include regole di metodo: verifica sulle fonti, mai a memoria, verifica live sul repo.
- **keyword/entità:** OSS1777 · setup Project · skill · knowledge base · trascrizioni · verifica fonti · claude.ai Project · contributo open source

---

### Perplexity Pro deep research case study
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento sul caso d'uso Perplexity Pro per deep research: confronto workflow da $60/mese (Perplexity Pro) vs workflow enterprise da $15k. Documenta come un singolo utente con Perplexity Pro può replicare ricerche che tradizionalmente richiedono team e budget enterprise, applicato allo specifico di ricerche tecniche su graphify e clustering. Base per la skill marketing di neo1777.
- **keyword/entità:** Perplexity Pro · deep research · $60 vs $15k · workflow research · markdown export · knowledge management · skill marketing

---

### articolo Medium (05_articolo_medium_IT.md)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Articolo in italiano per Medium che racconta il contributo open source di Neo a graphify: dall'analisi di marzio1777, alla diagnosi dei super-hub, all'issue #919, all'accoglienza in 3 ore da Saif, fino alla PR #942. Tono narrativo tecnico, pensato per developer italiani, include il metodo di lavoro con Claude Code e la skill contributo-oss come strumenti.
- **keyword/entità:** Medium article · contributo OSS · graphify · Neo · marzio1777 · issue #919 · PR #942 · Claude Code · developer italiani

---

### template pro (03_template_pro_IT.md / 07_template_pro_EN.md)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Template professionale per scrivere articoli tecnici su contributi open source. Versioni italiano e inglese. Include struttura: hook iniziale, contesto tecnico, diagnosi del problema, soluzione proposta, esito, lezioni apprese, call to action. Derivato dal caso graphify come esempio concreto. Pensato per essere riutilizzabile su altri contributi.
- **keyword/entità:** template articolo · contributo OSS · struttura narrativa · italiano · inglese · hook · lezioni apprese · riutilizzabile

---

### anti_sycophancy_valutazione.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento sul metodo anti-sycophancy di Neo: come valutare risposte di AI evitando il bias di conferma. Include il principio "una cosa vera ma gonfiata suona di falso", accountability senza auto-abasement, disaccordo onesto, tono da pari. Applicato al processo di valutazione dei contributi open source e delle skill. Basa Neo il lavoro su questi principi per l'intera pipeline OSS1777.
- **keyword/entità:** anti-sycophancy · valutazione · bias di conferma · accountability · disaccordo onesto · tono da pari · metodo Neo · principi di lavoro

---

### METAPROMPT1777 / METAPROMPT_TEMPLATE
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Template di metaprompt di neo1777: struttura riutilizzabile per creare prompt di alta qualità. Nasce dall'esigenza di avere uno standard per lavori lunghi e complessi con Claude. Include sezioni: contesto, ruolo, compito, vincoli, formato output, criteri di accettazione. Base per tutti i prompt operativi del Project OSS1777 e dei Project successivi.
- **keyword/entità:** METAPROMPT1777 · template prompt · metaprompt · struttura riutilizzabile · criteri di accettazione · prompt engineering · neo1777

---

### PIANO_B_PR_graphify_934.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Piano operativo dettagliato per la PR #942 su graphify. Include: meccanica git (fork → branch → commit → push → PR), strategia test (subprocess per `cluster-only` su directory mancante), template description PR, galateo col maintainer (tono collaborativo, ammissione di limiti). Documenta anche la "PIANO B" con approccio alternativo se il maintainer non accoglie la PR.
- **keyword/entità:** PIANO_B · PR #942 · graphify · git workflow · test strategy · subprocess · galateo maintainer · template PR description

---

### PROMPT_start_PR.md (ondata 2)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Prompt operativo per la chat dell'ondata 2: sviluppo della PR per `--edge-weight-mode` (terza opzione di issue #919). Include fase A (verificare se graspologic leiden() accetta pesi archi), fase B (disegno della PR), runbook. Definisce il metodo di lavoro: verify-before-modify, verify sulle fonti live, niente castelli su fondamenta non verificate.
- **keyword/entità:** ondata 2 · --edge-weight-mode · PR graphify · graspologic · leiden · fase A · runbook · verify-before-modify

---

### spiegazione_fix_saif_934.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento che spiega il fix di Saif per issue #934: mkdir spostato alla posizione corretta (dove nasce la variabile path, non dove esplode il crash), più regression test. Analisi della differenza tra tappare il sintomo vs la causa alla radice. Identico nella sostanza a esempio-modifiche-saif.md.
- **keyword/entità:** fix Saif · issue #934 · mkdir · root cause · regression test · cluster-only · FileNotFoundError · invariante precondizione

---

### caso-perplexity.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento del caso Perplexity applicato alla ricerca su graphify: come usare Perplexity Pro per ricerche tecniche approfondite su repository, algoritmi di clustering, e documentazione. Include il confronto costo-beneficio rispetto ad alternative, workflow pratico di ricerca, integrazione con il metodo OSS1777.
- **keyword/entità:** caso Perplexity · ricerca tecnica · graphify · clustering · costo-beneficio · workflow ricerca · OSS1777

---

### esempio-issue-919.md (reference skill contributo-oss)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Reference della skill contributo-oss: corpo verbatim della issue #919 come esempio di "issue-diagnosi" di qualità. Mostra la struttura: contesto (codebase, problema osservato), diagnosi tecnica (due super-hub con degree 44 e 32), proposta soluzione (3 opzioni ranked per ampiezza), side observation onesta, environment. Utilizzato come caso di studio nella SKILL.md.
- **keyword/entità:** issue #919 · esempio · reference · skill contributo-oss · issue-diagnosi · super-hub · diagnosi tecnica · formato issue

---

### esempio-issue-934.md (reference skill contributo-oss)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Reference della skill contributo-oss: corpo verbatim della issue #934 come esempio di "issue corta" post-collaud. Segnala FileNotFoundError su `graphify cluster-only` quando la directory di output non esiste. Formato minimalista: reproducer, root cause in una frase, suggested fix (mkdir), environment. Accolta in 27 minuti con "send me a PR".
- **keyword/entità:** issue #934 · FileNotFoundError · cluster-only · mkdir · reference · skill contributo-oss · issue corta · Saif Shamsi

---

### esempio-pr-942.md (reference skill contributo-oss)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Reference della skill contributo-oss: descrizione completa della PR #942 + rapporto col maintainer. Documenta: fork→branch→commit→push→apertura PR, description che ammette onestamente l'assenza del regression test, commento di chiusura di Saif (reimplementato lui il fix con test), risposta di Neo. Mostra che la PR chiusa-non-mergeata è una mossa OSS matura, non un fallimento.
- **keyword/entità:** PR #942 · graphify · esempio · reference · rapporto maintainer · PR description · chiusa non mergeata · commit f012e7f · 076e6b7

---

### spiegazione-tecnica SKILL.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** SKILL.md della skill "spiegazione-tecnica" di neo1777. Skill che produce spiegazioni tecniche chiare e precise, calibrate sul livello del destinatario. Principi: partire dal perché prima del come, niente sycophancy nelle spiegazioni, onestà sui limiti della propria comprensione, esempi reali estratti dal corpus. Include tre reference (esempio-test, esempio-venv, esempio-modifiche-saif).
- **keyword/entità:** spiegazione-tecnica · skill neo1777 · perché prima del come · anti-sycophancy · calibrazione · esempi reali · SKILL.md

---

### marketing SKILL.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** SKILL.md della skill "marketing" di neo1777. Skill per creare contenuti di marketing tecnico: articoli, post, thread, case study su contributi open source e tool AI. Principi: autenticità tecnica, storia narrativa, metriche concrete, hook potente, call to action. Calibrata su neo1777 e il suo stile diretto.
- **keyword/entità:** marketing · skill neo1777 · contenuto tecnico · articoli · case study · hook · autenticità · SKILL.md

---

### contributo-oss SKILL.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** SKILL.md della skill "contributo-oss" di neo1777. Copre l'intero ciclo di un contributo open source: issue-diagnosi (la forma di issue_body.md), confezione PR review-friendly, galateo col maintainer. Principio di fondo: un contributo si fa accogliere per quanto lavoro risparmia a chi lo riceve. 8 principi verificati sull'arco #919→#942. Tre reference: esempi issue #919, #934, PR #942.
- **keyword/entità:** contributo-oss · skill neo1777 · issue-diagnosi · PR review-friendly · galateo maintainer · principio di fondo · SKILL.md · arco #919→#942

---

### palantir1777 SKILL.md (v1.0.0 / v1.1.0)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** SKILL.md della skill orchestratrice palantir1777. Versione v1.1.0: conosce tutte le 11 skill dell'arsenale neo1777, instrada richieste verso la skill giusta o verso flussi di skill, include guardia anti-loop. Ha Atlante skill, Ricettario dei flussi, e (v1.1.0) modello-stato-flusso.md (Piano B). Stile Tolkien/incantesimo, performance prima del fun. Script scansiona_skill.py per audit automatico.
- **keyword/entità:** palantir1777 · skill orchestratrice · arsenale neo1777 · guardia anti-loop · Atlante skill · Ricettario flussi · modello-stato-flusso · v1.1.0

---

### PIANO_kit_costruzione_project_v1.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Piano in 7 punti per generalizzare il metodo OSS1777 in un kit riutilizzabile per costruire Claude Projects su qualsiasi dominio software. Include: architettura del Project, setup istruzioni, prompt-madre, template skill, sistema di versioning delle mappe. L'obiettivo è che il percorso #919→skill→kit sia un framework replicabile per qualunque contributo open source futuro.
- **keyword/entità:** PIANO_kit · kit costruzione Project · claude.ai · 7 punti · framework riutilizzabile · template skill · versioning mappe · OSS1777

---

### MAPPA_OSS1777_v2.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Mappa v2 del Project OSS1777, prodotta dopo lettura integrale delle trascrizioni (chat-genesi 1072 righe + chat operativa 11841 righe). Inventario: storico (trascrizioni), artefatti (issue, PR, PIANO_B), documenti di lavoro, metodi (metaprompt, template). Arco del lavoro dalla chat-genesi a oggi. Stato: arco A chiuso, ondata 2 aperta. Fili aperti: --edge-weight-mode, PIANO_kit. Indice "dov'è X" con riferimenti riga per riga.
- **keyword/entità:** MAPPA_OSS1777_v2 · inventario · arco del lavoro · fili aperti · ondata 2 · PIANO_kit · indice · trascrizioni

---

### VALUTAZIONE_skill_OSS1777.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento di valutazione delle skill per il Project OSS1777. Analizza 5 attività candidate (issue, PR, ricerca repo, rapporto maintainer, re-onboarding) attraverso il filtro "ricorre + non banale + non già coperto". Risultato: una sola skill candidata (contributo-oss). Quattro non-skill con motivazione. Lascia due punti aperti a Neo: una skill o due, lettura integrale trascrizioni.
- **keyword/entità:** VALUTAZIONE_skill · OSS1777 · contributo-oss · filtro candidatura · skill non-skill · meccanica git runbook · anti-montatura

---

### riassunto_marketing_gancio_metaprompt.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Documento di sintesi sull'"aggancio marketing" attraverso il metaprompt: come usare il caso graphify come storia di marketing per neo1777, collegando il contributo tecnico alla narrativa personale. Analizza cosa rende il caso graphify un gancio efficace (issue accolta in 3 ore, stella OSS genuina, metodo replicabile) e come trasformarlo in contenuto di marketing autentico.
- **keyword/entità:** marketing · gancio narrativo · graphify · metaprompt · storia personale · neo1777 · contributo OSS · autenticità tecnica

---

### cluster.py (graphify v8 HEAD)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Sorgente di cluster.py di graphify, branch v8 HEAD, scaricato da raw.githubusercontent.com il 21 maggio 2026. 267 righe. Contiene: `_partition()` (chiama leiden/louvain), `_split_community()`, `cohesion_score()`, `cluster()`, `exclude_hubs_percentile`, costanti `_COHESION_SPLIT_THRESHOLD = 0.05`. Conferma: nessun peso archi passato a leiden(). Copia d'archivio, fonte di verità è il repo live.
- **keyword/entità:** cluster.py · graphify v8 · _partition · cohesion_score · exclude_hubs_percentile · leiden · Louvain · _COHESION_SPLIT_THRESHOLD · sorgente

---

### SETUP_PROJECT_oss.md
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** File di setup del Project OSS1777 su claude.ai: visione dall'alto, istruzioni per le chat, regole di metodo (verifica sulle fonti, mai a memoria, verifica live sul repo), skill installate (spiegazione-tecnica, marketing, contributo-oss), knowledge base (trascrizioni, artefatti). Include nota su cluster.py come copia d'archivio non fonte di verità.
- **keyword/entità:** SETUP_PROJECT · OSS1777 · claude.ai Project · skill installate · knowledge base · verifica fonti · cluster.py · istruzioni operative

---

### chat genesi graphify (trascrizione piccola, 1072 righe)
- **source_id:** [da sessione precedente] · **tipo:** text
- **sostanza:** Prima trascrizione del Project OSS1777 (1072 righe): la chat-genesi del 16 maggio 2026. Neo analizza per la prima volta marzio1777 con graphify, scopre i risultati (1501 nodi, 147 comunità), identifica Community 0 sospetta con i due super-hub, e prende la decisione di aprire issue #919 su graphify. È la fonte di verità dell'inizio del progetto.
- **keyword/entità:** chat-genesi · OSS1777 · 16 maggio 2026 · marzio1777 · graphify · Community 0 · super-hub · issue #919 · decisione

---

### agente Dart (agente simile in Dart)
- **source_id:** cfc996d4-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Documento tecnico su harness agentico clean-room scritto in Dart/Flutter. Specifica loop agentico con tool use (filesystem, shell, search), architettura ispirata a Claude Code, integrazione MCP, pattern memoria cross-sessione. Pensato come prototipo di agente coding alternativo in Dart puro.
- **keyword/entità:** Dart · Flutter · harness agentico · MCP · tool use · clean-room · agente coding · memoria cross-sessione

---

### agente Dart [duplicato]
- **source_id:** bc50377e-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Duplicato del documento agente Dart precedente. Contenuto identico. Stessa specifica tecnica dell'harness Dart/Flutter agentico.
- **keyword/entità:** Dart · Flutter · harness · duplicato

---

### agentmemory blog intro
- **source_id:** 750a93e0-[UUID completo in notebook] · **tipo:** url
- **sostanza:** Post introduttivo su agentmemory di KnightLi. Sistema #1 per memoria persistente agenti AI coding basato su benchmark reali. Architettura MCP, integrazione IDE principali, benefici per continuità contesto cross-sessione.
- **keyword/entità:** agentmemory · KnightLi · memoria persistente · MCP · benchmark · agenti AI · cross-sessione

---

### catalogo-comandi-bash.md
- **source_id:** 60a1a998-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Catalogo comandi bash collaudati e portabili per il metodo OSS1777 (Step 3 del prompt-definitivo). Abbina comandi grep parametrizzati alle tre liste keyword. Include gestione encoding UTF-8 per accenti italiani, pattern `|| true` per grep con set -e, variabili radice configurabili, comandi per mappa termine→file→conteggio, dedup, JSONL export per RAG.
- **keyword/entità:** bash commands · grep · portabilità · UTF-8 · set -e · || true · RAG ingestion · JSONL · dedup

---

### chat_rename.md (sessione architettura della conoscenza)
- **source_id:** 6646a971-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Sessione NotebookLM sull'architettura della conoscenza e il metodo ontologico applicato ai Claude Projects. Discute Regime A (5 famiglie: Motore, Diario, Prodotto, Bussola, Pezzo di Ferro), Regime B (flusso adattivo), VEP (Verità Elementare Persistente), Auditor di Verità. Il kit di costruzione dei Projects come sistema ripetibile applicato al metodo neo1777.
- **keyword/entità:** architettura della conoscenza · Regime A/B · VEP · Auditor di Verità · 5 famiglie ontologiche · Motore · Diario · Bussola · Pezzo di Ferro · Claude Projects

---

### claude-memory-mcp (MemCP)
- **source_id:** 33c53f43-[UUID completo in notebook] · **tipo:** url
- **sostanza:** Pagina PyPI del pacchetto claude-memory-mcp (MemCP). Memoria persistente con MAGMA (4-graph: episodic, semantic, procedural, working), framework RLM (Reinforcement Learning from Memory), 24 strumenti MCP. Supporta Claude Code, Claude Desktop e altri agenti. Memoria cross-sessione con consolidamento automatico.
- **keyword/entità:** claude-memory-mcp · MemCP · MAGMA · 4-graph · RLM · 24 MCP tools · episodic memory · semantic memory · cross-sessione

---

### dart-agent-technical-spec.md
- **source_id:** 3a280d99-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Specifica tecnica dettagliata dell'agente coding Dart: architettura harness, loop agentico, tool definitions per filesystem/shell/search, pattern memoria cross-sessione, integrazione Anthropic SDK Dart, gestione errori e retry, test framework. Documento di riferimento per costruzione agente clean-room in Dart.
- **keyword/entità:** Dart agent · specifica tecnica · harness · Anthropic SDK · tool definitions · loop agentico · test framework · clean-room · Flutter

---

### esempio-modifiche-saif.md
- **source_id:** d658f6f2-[UUID completo in notebook] · **tipo:** text
- **sostanza:** Documento che illustra le modifiche di Saif in risposta alla PR #942: commit 076e6b7 con mkdir spostato alla posizione corretta (dove nasce la variabile path) più regression test. Analisi: tappare il sintomo dove esplode vs tappare la causa dove nasce. Asimmetria tra codepath extract (crea dir esplicitamente) e cluster-only (la dà per esistente). Spiegazione di cosa distingue una buona patch.
- **keyword/entità:** PR #942 · Saif Shamsi · commit 076e6b7 · mkdir · regression test · root cause · asimmetria codepath · qualità patch

---

---

> Le voci seguenti sono state lette al sorgente (source_get_content, UUID completo) per colmare le fonti non ancora coperte.

---

### 00_guida_costruire_un_project.md
- **source_id:** f08a646f-4dc1-4ff4-9c1e-93d1537560d6  ·  **tipo:** text
- **sostanza:** Documento portante del kit PROJECT1777: come costruire un Project Claude.ai persistente per un lavoro qualunque. Spiega quando conviene (lavoro con continuità) vs no, il modello "corpo/bracci" (invariante universale + moduli di dominio), il metodo in 8 fasi (Fase 0 lavoro reale → Fase 7 raffinamento), i principi (verifica mai a memoria, fatti vs inferenze, niente compiacenza, 360°→fuoco, file-ponte) e l'inventario del kit.
- **keyword/entità:** PROJECT1777 · kit · corpo/bracci · 8 fasi · skill · prompt-madre · metaprompt · file-ponte · caso-studio · principi di metodo

---

### 01-prd-mvp.md
- **source_id:** e9eff001-a4da-4a7d-8969-f997f14b3af2  ·  **tipo:** text
- **sostanza:** PRD dell'MVP di una piattaforma di peer-review "overlay" per articoli tecnici AI/workflow. Definisce scopo, problema (manca review strutturata nella grey literature tecnica), 4 ruoli (Autore, Revisore, Editor, Lettore), scope in/out, workflow editoriale (proposed→under review→reviewed...), rubriche di valutazione a 7 dimensioni, user stories e criteri di successo.
- **keyword/entità:** PRD · MVP · peer-review · overlay platform · ruoli · workflow editoriale · rubriche · score · reputazione · articoli tecnici AI

---

### 01_base_processo_architettura_lezioni.md
- **source_id:** a2590d47-34b6-4339-9d26-0aac68de1998  ·  **tipo:** text
- **sostanza:** Artefatto Punto 1 del kit: fondazione da cui derivano guida e scheletri. Parte A = processo astratto in 8 fasi con riscontri reali in OSS1777 (issue #919, #934, PR #942). Parte B = architettura corpo/bracci con il "test del confine". Parte C = registro di 12 lezioni reali con fonte (versione graphify 0.8.8 vs 0.8.5, limite 1024 char description skill, ZIP con cartella, file-ponte ecc.).
- **keyword/entità:** PROJECT1777 · processo 8 fasi · corpo/bracci · test del confine · registro lezioni · OSS1777 · issue #919 · #934 · PR #942 · METAPROMPT_TEMPLATE

---

### 02-ux-ui-spec.md
- **source_id:** 57ba4737-0ad2-4c09-aacd-7fc7ce674781  ·  **tipo:** text
- **sostanza:** Specifica UX/UI multipiattaforma dell'MVP peer-review. Principi (affidabilità, rigore, no estetica social), default Italia/italiano e temi light/dark/system. Architettura informativa (Home/Discover, Search, Submit, Review Queue, Article Workspace, Review Composer, Profiles, Editor Console, Settings), navigazione per mobile (bottom nav)/tablet-desktop (sidebar)/web, componenti chiave (card, badge stato, score chips, timeline versioni) e stati interfaccia.
- **keyword/entità:** UX/UI spec · multipiattaforma · Article Workspace · Review Composer · badge stato · bottom nav · sidebar · empty state · localizzazione Italia

---

### 03-functional-behavior-spec.md
- **source_id:** 04a37c73-b0d9-4230-b064-d3b6876b5915  ·  **tipo:** text
- **sostanza:** Specifica del comportamento funzionale della demo MVP: regola reale vs simulato (core operativo, avanzato simulato ma "wired-ready"). Descrive 6 flussi (import articolo da URL, submission guidata, review queue, composizione review per rubriche, risposta autore/nuova versione, decisione editoriale), bottoni e azioni con esiti visibili, funzioni simulabili (matching revisori, AI hints) e stati trasversali obbligatori (loading/empty/error/permission).
- **keyword/entità:** functional spec · reale vs simulato · flussi · import URL · review composer · stati UI · decisione editoriale · demo high-fidelity

---

### 03_template_pro.md
- **source_id:** 6df34cef-69b8-4c1c-be20-850307694c0e  ·  **tipo:** text
- **sostanza:** Versione inglese "Pro Edition" del template di ricerca Perplexity Pro. Companion a template gratuito e articolo Medium. Contiene 3 case study elaborati, troubleshooting (7 failure mode), pattern avanzati (knowledge graph multi-sessione, cross-research synthesis, anti-demotion discipline), cost optimization, adattamento per scala e riferimento API completo (preset advanced-deep-research, max_output_tokens 128000, reasoning high, web_search+fetch_url).
- **keyword/entità:** Perplexity Pro · advanced-deep-research · template ricerca · case study · anti-demotion · knowledge graph · API config · Regime A/B · cost optimization

---

### 04-integration-readiness-spec.md
- **source_id:** 46a1521e-8ec7-4d6f-bd2d-286de1653a7d  ·  **tipo:** text
- **sostanza:** Specifica di "integration readiness" dell'MVP: punti di aggancio da esporre senza fissare lo stack. Domini di integrazione (identity esterna, import contenuti URL, workflow editoriali a eventi, reputation/scoring, browser extension). Modello dati concettuale minimo (User, Article, ArticleVersion, Review, Rating, ScoreSnapshot, WorkflowEvent), eventi applicativi standardizzati (ArticleImported, ReviewSubmitted...) e integrazioni open data Italia di contesto.
- **keyword/entità:** integration readiness · modello dati · WorkflowEvent · browser extension · reputation · open data Italia · eventi applicativi · overlay model

---

### 05-master-prompt-companion.md
- **source_id:** 50ae60f0-6dbc-42eb-915f-42b7d6dac64d  ·  **tipo:** text
- **sostanza:** Companion operativo al master prompt per generare l'app MVP multipiattaforma. Vincola il generatore: identità prodotto (piattaforma overlay di peer-review, non social/blog), risultato atteso (demo high-fidelity con tutte pagine/stati/temi/localizzazione), vincoli (Italia default, EN secondaria, temi system), sezioni obbligatorie, funzioni reali vs simulate e criterio finale di accettazione.
- **keyword/entità:** master prompt · companion · generazione app · MVP · multipiattaforma · sezioni obbligatorie · reale vs simulato · criterio di accettazione

---

### 05_articolo_medium_IT.md
- **source_id:** b563bbb7-42a0-4ecc-96a5-31b7d1c403b4  ·  **tipo:** text
- **sostanza:** Articolo Medium in italiano "Ho speso $60 su Perplexity Pro... avrei pagato un consulente $15.000+". Racconta un progetto editoriale di 6 mesi/20 sessioni: workflow di ricerca in 4 step (passata esplorativa, audit metodico, identifica buchi, ricerca di chiusura), 6 principi epistemologici (neutralità esplorativa, citazioni primarie, pattern emergenti, disclaimer, audit categorizzato 1-5, anti-derubricazione), numeri trasparenti e setup API esatto.
- **keyword/entità:** Medium IT · Perplexity Pro · workflow 4 step · anti-derubricazione · finding categoria 5 · citazioni primarie · $60 vs $15k · advanced-deep-research

---

### 06-ai-test-debug-smoke-final.md
- **source_id:** 21367c2d-7d47-4ca6-8ac8-3d99c1713f7f  ·  **tipo:** text
- **sostanza:** Framework di verifica/test/debug/smoke per l'MVP, orchestrabile da un agente AI. Definisce 6 livelli di test (static/code quality, unit, integration, smoke, end-to-end, regression), checklist smoke S1-S12, tassonomia bug per severità (P0 crash/broken path → P3 cosmetic), test di stato/workflow editoriale, test UI multipiattaforma, audit qualità codice, gate di rilascio G1-G7 e prompt operativo per AI tester.
- **keyword/entità:** test framework · smoke test · agente AI tester · livelli di test · severità bug P0-P3 · gate di rilascio · invalid state · regression · qualità codice

---

### 07_template_pro_IT.md
- **source_id:** 3c557224-3461-4b97-a5ec-f68c0ea8abd5  ·  **tipo:** text
- **sostanza:** Versione italiana completa della "Edizione Pro" del template di ricerca Perplexity Pro. Contenuto equivalente a 03_template_pro.md (EN): 3 casi di studio, guida troubleshooting (7 modalità di fallimento), pattern avanzati (knowledge graph multi-sessione, sintesi cross-research, disciplina anti-derubricazione con 3 esempi), ottimizzazione costi, adattamento a scale diverse, riferimento configurazione API e Parte 7 sui Regimi A/B.
- **keyword/entità:** Perplexity Pro · Edizione Pro IT · casi di studio · troubleshooting · anti-derubricazione · Regime A/B · API advanced-deep-research · ottimizzazione costi

---

### Analisi Strategica: Acquisizione di Tecnologie di Registrazione Audio Intelligenti (2026)
- **source_id:** 61b76fd7-9b78-461f-8dca-2f50ee5bd70d  ·  **tipo:** text
- **sostanza:** Report strategico 2026 sull'acquisizione di tecnologie di registrazione audio intelligenti. Tassonomia per form factor (registratori digitali, mini/spy, wearable AI note-taker, software meeting, app smartphone, lifelogging desktop, form factor futuristici), modelli economici CAPEX vs OPEX ("razor-and-blade"), dilemma cloud-first vs local-first con voice masking (Plaud, BOYA), sensori VPU/Quad-MEMS e 3 profili decisionali di procurement.
- **keyword/entità:** registrazione audio 2026 · wearable AI · CAPEX/OPEX · cloud vs local · voice masking · Plaud · BOYA Notra · Rewind.ai · Whisper · VPU · procurement

---

### Architettura della Conoscenza: Il Metodo PROJECT1777
- **source_id:** d5fc4745-9509-4f5f-8827-3a2903b6b147  ·  **tipo:** text
- **sostanza:** Risposta NotebookLM che indicizza gli 8 file del "nucleo metodologico" (Bussola/Motore) del sistema PROJECT1777 e ne descrive il ruolo: metodo ontologico, protocollo Auditor di Verità, guida operativa caos→struttura, framework densità semantica/valore economico, manuale Auditor universale, manuale correlazione ontologica Graphify/Marzio1777, mappa ontologica, chat_rename. Inquadra i file come istruzioni operative e mappe strategiche.
- **keyword/entità:** PROJECT1777 · architettura della conoscenza · metodo ontologico · Auditor di Verità · VEP · densità semantica · Motore/Diario/Bussola · 8 file nucleo

---

### Architettura della Conoscenza_ Il Metodo Ontologico per NotebookLM.md
- **source_id:** c5a2105d-1470-4fe4-b847-8697adb9efef  ·  **tipo:** text
- **sostanza:** Versione definitiva del Metodo Ontologico per NotebookLM come framework di Architettura della Conoscenza. Trasforma NotebookLM in "Auditor di Verità". Contiene il core engine "Virgin Entry Prompt (VEP) Amplificato" (tassonomia funzionale Motore/Diario/Prodotto/Bussola/Anomalia + Pezzo di Ferro/Trasparenza Totale/Punto di Rottura), workflow 4 step, casi d'uso degli artefatti NotebookLM, checklist del senso (Regime A/B, esiste una skill?) e gestione falsa completezza.
- **keyword/entità:** metodo ontologico · NotebookLM · VEP amplificato · Auditor di Verità · tassonomia funzionale · densità semantica · Regime A/B · falsa completezza · finding Cat 5

---

### Architettura della Conoscenza_ Protocollo Auditor di Verità.md
- **source_id:** 2a1c00d9-f3dc-46f1-bccb-f6c45522095e  ·  **tipo:** text
- **sostanza:** Descrive la finalizzazione della mappa mentale del corpus (61 file sorgente, titoli trattati come placeholder) e il metodo agnostico replicabile: 4 artefatti (Manuale Correlazione Ontologica, Stratigrafia/Infografica, Skill Flashcards, Manuale Metodologico Universale), protocollo di bootstrapping ricorsivo con VEP, workflow 4 step, distinzione Regime A/B, "Dignità di Prodotto" come criterio finale ed esempi di tracciamento integrità corpus.
- **keyword/entità:** Auditor di Verità · mappa mentale · 61 file · bootstrapping ricorsivo · VEP · ridenominazione ontologica · Regime A/B · Dignità di Prodotto · verify before modify

---

### BRIEFING_GRAPHIFY_ISSUE(1).md
- **source_id:** e6ebf5b5-6f75-4a18-b58e-a4e613003bf5  ·  **tipo:** text
- **sostanza:** Documento di briefing per la sessione di scrittura della prima issue open-source su graphify. Presenta Neo/neo1777 (background, stack React/TS/Vite/Firebase), il progetto marzio1777, il tool graphify v8 di safishamsi, il problema concreto (Community 0 con 86 nodi, cohesion 0.05, due super-hub ui/index.tsx deg 44 e useRBAC() deg 32), la due-diligence su cluster.py, le 4 feature request candidate e gli obiettivi della chat (imparare il pattern issue→PR).
- **keyword/entità:** briefing · issue open-source · graphify v8 · neo1777 · marzio1777 · Community 0 · super-hub · cluster.py · --exclude-hubs · Leiden · feature request

---

### BRIEFING_GRAPHIFY_ISSUE.md
- **source_id:** 98c8a442-9264-4dfc-bbf2-a6a6ac881182  ·  **tipo:** text
- **sostanza:** Duplicato funzionale di BRIEFING_GRAPHIFY_ISSUE(1).md (stesso char_count, contenuto identico): documento di contesto per la prima issue OSS su graphify. Presenta Neo, marzio1777, graphify v8, il problema Community 0 (86 nodi, cohesion 0.05, super-hub ui/index.tsx e useRBAC()), la due-diligence su cluster.py, le 4 feature request e gli obiettivi pedagogici della sessione.
- **keyword/entità:** briefing · duplicato · issue graphify · Community 0 · super-hub · cluster.py · feature request · neo1777 · marzio1777

---

### BRIEF_skill_contributo_oss.md
- **source_id:** 76c61f17-f67b-416e-83bc-4c41e541a83e  ·  **tipo:** text
- **sostanza:** Brief di costruzione della skill "contributo-oss", prodotto dopo la valutazione che ha individuato una sola skill candidata (issue+PR insieme). Definisce identità skill, descrizione YAML di attivazione, forma (metodo non runbook), principio di fondo (un contributo vale per il lavoro che risparmia al maintainer), 7 principi candidati con fonti reali (#919/#934/#942), arco tipico, cosa evitare, calibrazione su Neo e reference da includere. Nota di igiene: PAT GitHub in chiaro da revocare.
- **keyword/entità:** contributo-oss · skill · brief costruzione · issue-diagnosi · PR review-friendly · galateo maintainer · 7 principi · #919/#934/#942 · PAT da revocare

---

### CHANGELOG.md - safishamsi/graphify - GitHub
- **source_id:** 59ee9f73-8209-4a27-bdb0-df5c13b9ae2d  ·  **tipo:** url
- **sostanza:** [oversized ~62k char — non leggibile in un singolo get_content] CHANGELOG ufficiale del repo safishamsi/graphify su GitHub. Documenta la storia delle release con feature, fix e breaking change. Coerente con l'altra copia CHANGELOG già indicizzata: traccia l'evoluzione dal proof-of-concept iniziale alle versioni mature (cross-file call resolution, wiki, Mermaid, MCP, clustering, multi-platform).
- **keyword/entità:** CHANGELOG · graphify · release history · GitHub · oversized · feature roadmap · safishamsi

---

### Chat Claude — risoluzione issue Graphify (briefing) [copia 2]
- **source_id:** df00f257-aff5-4324-ad82-e4dfdf77c0e9  ·  **tipo:** url
- **sostanza:** Trascrizione Claude share (claude.ai/share/6b95b100) della sessione in cui Neo, partendo dal BRIEFING_GRAPHIFY_ISSUE, impara a scrivere la prima issue open-source. Claude spiega cos'è una issue ben scritta (5 criteri, struttura a 6 sezioni, tono), il modello mentale GitHub (repo/fork/issue/PR, upstream/origin), il workflow issue→PR, e fa la ricognizione live del repo graphify (v0.8.8, 48.6k star, nessun duplicato, cluster.py non verificabile via fetch).
- **keyword/entità:** Claude share · issue open-source · graphify v0.8.8 · fork/PR · upstream/origin · soft offer · ricognizione repo · cluster.py · first-time contributor

---

### Claude Code Complete Guide 2026: From Zero to Hero
- **source_id:** 3043a604-9f8f-4ea5-93f9-e8814389e0a0  ·  **tipo:** url
- **sostanza:** URL claude-world.com bloccata da Cloudflare ("Just a moment... Performing security verification", Ray ID a005220e). Contenuto reale non recuperato: la fonte indicizzata è solo la challenge page anti-bot. Tema dichiarato dal titolo: guida completa a Claude Code 2026.
- **keyword/entità:** Claude Code · guida 2026 · Cloudflare blocked · claude-world.com · contenuto non recuperato

---

### Claude Code MCP Servers & Plugins: The Complete 2026 Guide - Clarista
- **source_id:** aee2b75b-1d11-4bdf-88cd-fcf0c0a17424  ·  **tipo:** url
- **sostanza:** Guida Clarista 2026 su MCP server e plugin per Claude Code. Spiega cos'è MCP (standard Anthropic, "USB for AI": Resources/Tools/Prompts), cos'è un plugin (bundle di MCP+slash command+skill), come installare server e plugin via CLI, i server più utili 2026 (github, filesystem, postgres, slack, jira...), come costruire un server, i rischi enterprise (permissions sprawl, audit blindness, supply chain) e i punti di estensione (SDK, hooks, router, subagents).
- **keyword/entità:** Claude Code · MCP · plugin · Clarista · Resources/Tools/Prompts · marketplace · enterprise gateway · hooks · subagents · slash command

---

### Closing the Context Gap: Why MCP + Skills Works - Agentic AI Foundation (AAIF)
- **source_id:** ad049ca8-99ba-4f33-bc70-90ab5af01d5e  ·  **tipo:** url
- **sostanza:** Articolo AAIF sul keynote di Pedro Rodrigues (Supabase) a MCP Dev Summit NA 2026. Tesi: MCP e Agent Skills non sono concorrenti ma le due metà di un agente — MCP dà capacità (tools), le Skill danno conoscenza procedurale (context), colmando il "Context Gap". Case study RLS security_invoker, benchmark (MCP+Skills = 100% success su task security-critical vs MCP-only che ignora search_docs), progressive disclosure contro il token bloat.
- **keyword/entità:** MCP + Skills · Context Gap · Supabase · Pedro Rodrigues · SKILL.md · RLS security_invoker · progressive disclosure · benchmark · token bloat

---

### Dalla Massa Disordinata alla Struttura_ Guida Operativa al Metodo Ontologico in NotebookLM.md
- **source_id:** 9572576b-b034-4015-933b-f19f54322545  ·  **tipo:** text
- **sostanza:** Guida operativa al Metodo Ontologico in NotebookLM (filosofia Project OSS1777, discendenza Perplexity Pro). Elevare NotebookLM ad "Auditor di Verità": cambio di paradigma dallo slop alla conoscenza densa, ricognizione ontologica col Virgin Entry Prompt (etichette Motore/Diario/Prodotto/Bussola/Anomalia), workflow in 4 step (passata esplorativa, audit, identificazione buchi, chiusura), guida agli artefatti NotebookLM e checklist del senso (Regime A/B, esiste una skill, dignità di prodotto).
- **keyword/entità:** metodo ontologico · NotebookLM · Auditor di Verità · Virgin Entry Prompt · slop vs densità · workflow 4 step · Regime A/B · finding categoria 5 · falsa completezza

---

> **RIEPILOGO ANOMALIE**
>
> - **Duplicati confermati (4 coppie):** agente Dart (cfc996d4/bc50377e) · registratore vocale (c8d9e11d/a2878069) · prompt bidirezionalità palantir (e473a987/1fa804b9) · claude-share analisi grafo (0dbaecb9/4d7549a7) · Mappa id [1]/[2] (0bf5a5a6/258d40de)
> - **Source oversized campionate:** Mappa id [1] e [2] (862k chars ciascuna) · agentmemory GitHub (81k chars) · claude-share [1] e [2] (~102k chars ciascuna)
> - **URL bloccate Cloudflare (2):** claude-world.com · blog.gopenai.com
> - **Source immagine:** nessuna identificata in questo notebook
> - **Voci totali scritte:** 94 (comprese le voci delle sessioni precedenti ricostruite dal summary)
