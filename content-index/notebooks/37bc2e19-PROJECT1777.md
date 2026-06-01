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

### Dart AI Model Context Protocol (MCP) server - GitHub
- **source_id:** 198750d1-5b94-4e77-ad44-a7cebda52823  ·  **tipo:** url
- **sostanza:** README del repo its-dart/dart-mcp-server: server MCP ufficiale (ora deprecato a favore del server hosted) per Dart, project management AI. Espone prompt (create-task, create-doc, summarize-tasks), resource template e tool per task/doc management (list/create/get/update/delete). Istruzioni di setup per Claude Desktop, Claude Code, Cursor, Cline, Windsurf via npx o Docker, blocco mcpServers. TypeScript, MIT, 127 star.
- **keyword/entità:** Dart MCP · its-dart · MCP server · task management · Claude Code · Cursor · npx · Docker · deprecato · mcpServers

---

### Dart MCP Integration with Claude Code - Composio
- **source_id:** 5dc739c0-b1e7-4089-a121-ec3a691de32d  ·  **tipo:** url
- **sostanza:** Guida Composio per integrare Dart MCP con Claude Code via Composio Connect o SDK. Spiega vantaggi del Tool Router (un solo MCP URL, tool calling programmatico, accesso just-in-time a 20.000 tool), elenco tool Dart supportati, workflow SDK (discovery/auth/execution), guida step-by-step (install Claude Code, env var, generare MCP URL, `claude mcp add --transport http`), FAQ e sicurezza SOC2.
- **keyword/entità:** Dart MCP · Composio · Tool Router · Claude Code · MCP URL · programmatic tool calling · OAuth · SDK · integrazione

---

### Dart MCP | Dart - Help Center
- **source_id:** 63d6c146-55f0-4482-8d61-c79e950d5f90  ·  **tipo:** url
- **sostanza:** Articolo Help Center di Dart sul server MCP remoto hosted (https://mcp.dartai.com/mcp). Capacità (prompt e tool per task/doc management). Istruzioni di setup per molti client: Claude Code, Claude Desktop, ChatGPT, Cline, Codex, Cursor, Gemini CLI, Google Antigravity, VS Code, Windsurf, Zed. Setup speciali: client con OAuth, autorizzazione con token, sign-in come agente per workflow agentici.
- **keyword/entità:** Dart MCP · server hosted · mcp.dartai.com · OAuth · token · Claude Code · Antigravity · agente · setup multi-client

---

### Documento finale di verifica, test, debug, smoke e.md
- **source_id:** 63358533-8ae5-4bcb-abde-4e68ce000a9f  ·  **tipo:** text
- **sostanza:** Variante del framework di verifica/test/debug/smoke per l'MVP peer-review (corrisponde nei contenuti a 06-ai-test-debug-smoke-final.md, qui con citazioni alle fonti "Verso-una-peer-review..." e "Una-cosa-un-sistema..."). Definisce ambito di verifica, 6 livelli di test, checklist smoke S1-S12, tassonomia bug P0-P3, test di stato/workflow editoriale, test UI multipiattaforma, audit qualità codice, gate G1-G7 e prompt operativo per AI tester.
- **keyword/entità:** test framework · smoke S1-S12 · severità P0-P3 · gate G1-G7 · stato editoriale · agente AI tester · MVP peer-review · qualità codice

---

### Google Antigravity rules format needed · Issue #785 · safishamsi/graphify - GitHub
- **source_id:** ea4e6adf-030e-40b2-8aba-476e19d39172  ·  **tipo:** url
- **sostanza:** Issue #785 su safishamsi/graphify (aperta da duucck, chiusa). Segnala che il file .agents/rules/graphify.md per Google Antigravity ha bisogno del frontmatter YAML in testa (trigger/glob/description) altrimenti Antigravity non lo riconosce. Saif risolve in v7 aggiungendo il frontmatter richiesto a _ANTIGRAVITY_RULES; si rilancia `graphify antigravity install`. Repo a 52.3k star, 118 issue, 157 PR.
- **keyword/entità:** issue #785 · graphify · Google Antigravity · YAML frontmatter · .agents/rules · safishamsi · v7 · 52.3k star

---

### Il Viaggio della Voce_ Guida alla Privacy nei Dispositivi Indossabili AI.md
- **source_id:** bc956435-6506-4992-b247-2e81cca088d6  ·  **tipo:** text
- **sostanza:** Guida divulgativa sulla privacy della voce nei wearable AI. Segue il "viaggio" del dato vocale: dal suono all'audio grezzo (microfoni MEMS + VPU, -30 dB, 32-bit float, impronta biometrica), cifratura at-rest/in-transit e voice masking, il bivio architetturale Cloud-First vs Local-First (modello razor-and-blade CAPEX/OPEX), casi studio (Plaud Note cloud, Rewind.ai local-first, Bee a cancellazione immediata) e checklist del consumatore consapevole.
- **keyword/entità:** privacy voce · wearable AI · MEMS · VPU · voice masking · cifratura · Cloud vs Local · Plaud · Rewind.ai · Bee · CAPEX/OPEX

---

### Integration idea: agentmemory for temporal memory + graphify for structural knowledge · Issue #152 - GitHub
- **source_id:** 4e6df8c7-452c-4573-b6a4-cd56cae556bb  ·  **tipo:** url
- **sostanza:** Issue #152 su safishamsi/graphify (aperta da rohitg00, maintainer di agentmemory, ancora open). Proposta di integrazione: graphify mappa "cosa è un codebase" (struttura), agentmemory ricorda "cosa ha fatto lo sviluppatore" (memoria temporale cross-sessione). Idee concrete: agentmemory legge graph.json, graphify pesa i god node con dati di attività temporale, MCP surface condivisa. Confronta cosa fa ciascuno (AST 20 linguaggi, community Leiden vs decay temporale, retrieval ibrido 95.2%).
- **keyword/entità:** issue #152 · graphify · agentmemory · rohitg00 · memoria temporale · graph.json · god node · MCP · integrazione · knowledge graph

---

### La fine della dimenticanza_ 5 verità sorprendenti sui nuovi registratori AI _sempre attivi_.md
- **source_id:** 39e04b30-8fcc-40d9-a71d-37b7f7642390  ·  **tipo:** text
- **sostanza:** Articolo divulgativo sui registratori AI "sempre attivi" del 2026 in 5 verità: il "secondo cervello" come frontend fisico (wearable Plaud NotePin S, Vocci AI Ring, BOYA Notra -30dB); il paradosso privacy tra cloud privacy-aware e local-first (Rewind.ai compressione 3.750x); l'economia razor-and-blade CAPEX/OPEX; la rivincita dei dispositivi "dumb" offline (Sony, Zoom); l'integrazione totale (occhiali smart, earables, abbigliamento sensorizzato).
- **keyword/entità:** registratori AI · lifelogging · wearable · Plaud · Vocci Ring · BOYA · Rewind.ai · privacy · CAPEX/OPEX · sovranità dati

---

### Large-Scale App Project Analysis · Issue #52 · safishamsi/graphify - GitHub
- **source_id:** 2c926994-f601-4c7c-93eb-731bfebaa624  ·  **tipo:** url
- **sostanza:** Issue #52 su safishamsi/graphify (aperta da sunrain520, chiusa). Analisi su progetto iOS large-scale (9.389 file): 8 bug con severità. P0: incompatibilità tree-sitter 0.20.1, crash logica Python-only che blocca file Swift/ObjC. P1: PDF in .xcassets classificati come "paper", frammentazione community (7.414 community, cohesion ~0). P2-P3: limite 5000 nodi HTML, god node da librerie terze, no awareness iOS, no progress. Saif fixa Issue 2/3 in v0.3.13, tree-sitter pin in v0.3.17.
- **keyword/entità:** issue #52 · graphify · tree-sitter · community fragmentation · xcassets · god node · iOS preset · .graphifyignore · P0-P3 · v0.3.13

---

### MAPPA_OSS1777.md
- **source_id:** cbd08c44-ea13-4749-a767-5870af5725ed  ·  **tipo:** text
- **sostanza:** Versione v1 della mappa esplorativa del Project OSS1777 (prima chat esplorativa, 24 file). Fa il "360°": inventario in 5 famiglie (storico/trascrizioni, artefatti, documenti di metodo, skill, materiale Perplexity), i due archi intrecciati (Arco A contributo graphify #919→#934→#942, Arco B costruzione metodo metaprompt→template→prompt-madre), stato attuale, fili aperti (ondata 2 --edge-weight-mode, chat skill) e buchi (cluster.py mancante, duplicati, incoerenza stelle/versioni).
- **keyword/entità:** MAPPA_OSS1777 v1 · inventario · Arco A/B · #919/#934/#942 · ondata 2 · cluster.py · super-hub · duplicati · fili aperti

---

### MAPPA_OSS1777_v2_.md
- **source_id:** 2c28ba6b-1d3b-4a22-b372-5cd2df6ae17d  ·  **tipo:** text
- **sostanza:** Versione v2 della mappa esplorativa OSS1777 (26 file), dopo lettura integrale delle due trascrizioni. Molti punti passano da inferenza a fatto verificato: arco #919→#934→#942 ricostruito con date e commit (f012e7f, 076e6b7), accoglienza v0.8.10 in ~7h, PR chiusa-reimplementata. Risolve dubbi v1 (graphifyy vs graphify split di naming, stato contributor formale no, versione installata 0.8.5 vs dichiarata 0.8.8). Fili aperti e buchi confermati.
- **keyword/entità:** MAPPA_OSS1777 v2 · trascrizioni integrali · #919/#934/#942 · graphifyy/graphify · weight_attribute · cluster.py · commit f012e7f/076e6b7 · ondata 2

---

### MAPPA_OSS1777_v3.md
- **source_id:** 5fa1a384-ffa6-4c7f-bb8d-ad3e4917d16f  ·  **tipo:** text
- **sostanza:** Versione v3 della mappa esplorativa OSS1777 (29 elementi), che incorpora e aggiorna la v2. Registra tre cose nuove post-v2: la chat di valutazione skill eseguita (VALUTAZIONE → una sola skill candidata), la skill contributo-oss costruita e installata (Arco C), il PIANO_kit scritto ma non eseguito. Inventario in 6 famiglie, tre archi (A/B/C), fili aperti (ondata 2 fase A su graspologic weight, esecuzione PIANO_kit) e un indice "dov'è X" con riferimenti riga per riga alle trascrizioni GEN/OP.
- **keyword/entità:** MAPPA_OSS1777 v3 · Arco A/B/C · contributo-oss · PIANO_kit · VALUTAZIONE_skill · ondata 2 · graspologic weight · indice dov'è X · cluster.py:22

---

### Manuale dell'Auditor di Verità_ Protocollo Universale per l'Architettura della Conoscenza.md
- **source_id:** 7d10edf7-35b9-4f22-9d1d-1fce8ee7eef8  ·  **tipo:** text
- **sostanza:** Manuale del protocollo universale "Auditor di Verità". Profilo/missione (scetticismo metodologico, evidence-based, fatto vs opinione, identificazione super-hub, priorità coesione raw), il Virgin Entry Prompt come no-op, tassonomia funzionale (Motore/Diario/Prodotto), workflow ricorsivo in 4 step (mappatura super-hub p99+, scomposizione community e boundary case 0.045-0.05, audit a 7 dimensioni, chiusura), protocollo file placeholder e metriche (coesione raw vs rounded, p99, evidence density).
- **keyword/entità:** Auditor di Verità · protocollo universale · VEP · super-hub p99 · coesione raw vs rounded · boundary case · Leiden · 7 dimensioni · majority-vote reattachment

---

### Manuale di Correlazione Ontologica_ Sistema Graphify e Progetto Marzio1777.md
- **source_id:** 1ab379ec-4cee-46f8-b0ac-b3c023d43b2e  ·  **tipo:** text
- **sostanza:** Manuale che applica il metodo ontologico al sistema Graphify/marzio1777. Natura "cinetica" di graphify (v0.8.5→0.8.11 in pochi giorni, da AST a semantica AI con Gemini). Tassonomia (Motore/Diario/Prodotto/Bussola/Pezzo di Ferro), matrice placeholder→funzione reale, token tecnici (_COHESION_SPLIT_THRESHOLD 0.05, round(...,2) bug a cluster.py:166, p99, degree 44), analisi dei due super-hub di Community 0 (index.tsx deg 44, useRBAC() deg 32, coesione raw 0.0487→0.05), workflow PR e template "Ask-first" per --edge-weight-mode.
- **keyword/entità:** correlazione ontologica · graphify · marzio1777 · super-hub · Community 0 · cohesion 0.0487 · cluster.py:166 · --edge-weight-mode · majority-vote · Gemini

---

### Mappa Ontologica e Architettura della Conoscenza di Sistema
- **source_id:** cc67b759-524c-4eec-a47b-740e4d13c329  ·  **tipo:** text
- **sostanza:** Mappa ontologica del corpus (60 file sorgente) col metodo ontologico, titoli trattati come placeholder. Raggruppa in famiglie funzionali (Motore = metodologia/istruzioni, Prodotto = specifiche MVP e agenti Dart, Diario = trascrizioni Graphify #919/#934/#942, Bussola = mappe/liste RAG, Dominio = registratori/privacy/Perplexity). Analisi multi-livello (token/parola/frase/concettuale: bootstrapping ricorsivo, Regime A/B, trasparenza totale) e stato di integrità (duplicati, incoerenze placeholder, buchi cluster.py/GRAPH_REPORT).
- **keyword/entità:** mappa ontologica · 60 file · famiglie funzionali · Motore/Diario/Bussola/Dominio · bootstrapping ricorsivo · Regime A/B · verify before modify · duplicati · placeholder

---

### Mappa id - lista di (neighborid, edgedata) [1]
- **source_id:** 0bf5a5a6-5f18-4b0e-80f0-abd08645d15f  ·  **tipo:** text
- **sostanza:** [oversized ~890k char — non leggibile in un singolo get_content] Trascrizione completa della sessione principale OSS1777 (la chat operativa lunga ~848k/11.841 righe, claude.ai/share). Copre l'intero arco: analisi di marzio1777 con graphify → issue #919 (3 opzioni, accolta in ~3h con v0.8.10) → issue #934 (FileNotFoundError cluster-only) → PR #942 (fix mkdir 1 riga, chiusa-reimplementata da Saif, commit 076e6b7) → costruzione del metodo (METAPROMPT1777, template, prompt-madre, Project).
- **keyword/entità:** trascrizione completa · OSS1777 · oversized · issue #919/#934 · PR #942 · marzio1777 · prompt-madre · METAPROMPT1777 · commit 076e6b7

---

### Memory MCP Service | MCP Servers - LobeHub
- **source_id:** 102a207e-3316-4c27-b340-cc9d57c1c141  ·  **tipo:** url
- **sostanza:** Scheda LobeHub del "Memory MCP Service" (chenxiaofie/memory-mcp), servizio MCP di memoria persistente scenario+entity per Claude Code. Feature: Episodes, Entities, storage a due livelli (user/project), cache real-time, retrieval semantico vettoriale. Installazione (install.bat/sh, venv, pip), configurazione settings.json con 4 hook (SessionStart/UserPromptSubmit/Stop/SessionEnd), lista tool memory_* e tipi di entità (Preference/Concept/Habit user, Decision/Episode/File/Architecture project).
- **keyword/entità:** Memory MCP · LobeHub · chenxiaofie · memoria persistente · Claude Code · episodes/entities · hook · settings.json · retrieval semantico · MCP

---

### Mentioned in YouTube Video: Graphify · Issue #285 - GitHub
- **source_id:** 63e2299e-15c1-4919-89c2-f53713df0f95  ·  **tipo:** url
- **sostanza:** Issue #285 su safishamsi/graphify (aperta da timeus909, chiusa). Creata a seguito di una menzione di graphify in un video YouTube sulle librerie per Claude Code, presentato come tool di visualizzazione grafi. Saif risponde correggendo: graphify non è primariamente un visualizzatore — la pipeline reale è extraction strutturale (AST 23 linguaggi), semantica (subagent AI), community detection Leiden, tre output (HTML, graph.json GraphRAG, GRAPH_REPORT.md), con valore nell'integrazione always-on (PreToolUse hook, /graphify query, edge taggati EXTRACTED/INFERRED/AMBIGUOUS).
- **keyword/entità:** issue #285 · graphify · YouTube · Claude Code · AST · Leiden · graph.json · GRAPH_REPORT.md · PreToolUse hook · confidence tag · v0.4.10

---

### PIANO_PROJECT1777.md
- **source_id:** 47642ecf-75c5-4da8-afcb-3183fe085a9e  ·  **tipo:** text
- **sostanza:** Il piano (non il kit) che, eseguito a punti, produce PROJECT1777: kit per costruire un Project Claude.ai dedicato al lavoro su codice. Recepisce tre decisioni (nome PROJECT1777, ondata 2 integrata non separata, dominio specializzato sul codice). Distingue Arco A (contributo graphify, non generalizzabile) da Arco B (processo ripetibile = ciò che il kit cattura). Deliverable in 6 famiglie (guida, scheletri metodo, scheletri Project, guida skill, caso-studio, registro lezioni) e 7 punti scaglionati con verifica.
- **keyword/entità:** PIANO_PROJECT1777 · kit · Arco A/B · dominio codice · scheletri · 7 punti · file-ponte · ondata 2 · caso-studio OSS1777

---

### PIANO_PROMPT_progetto_oss.md
- **source_id:** d0f8f4e1-feba-4972-98c4-3810552d35c0  ·  **tipo:** text
- **sostanza:** Trascrizione verbatim (refusi inclusi, salvata da Claude il 21 mag) del messaggio di Neo che descrive il "piano-prompt" del progetto OSS+marketing: un prompt che produrrà mentalmente tutti i file/artefatti/skill, eseguito poi sessione per sessione. Contiene la parte narrativa (ruolo del marketing, gancio Karpathy "nullo ma reale", l'articolo Perplexity come primo tentativo con errori di click-bait) e i 6 punti operativi con esecuzione scaglionata "VAI CON PUNTO N".
- **keyword/entità:** piano-prompt · OSS+marketing · 6 punti · scaglionamento · gancio Karpathy · spiegazione-tecnica · marketing · Perplexity · neo1777 · verbatim

---

### PIANO_kit_costruzione_project_v1.md
- **source_id:** 10f03686-0d34-4a05-b172-016d3c71a822  ·  **tipo:** text
- **sostanza:** Versione precedente (v1) del piano per generalizzare l'Arco B di OSS1777 in un kit riutilizzabile per costruire un Project Claude.ai qualunque, con OSS1777 come caso-studio. Stesso impianto del PIANO_PROJECT1777 (deliverable in 6 famiglie, 7 punti con verifica/criterio) ma con dominio non ancora specializzato sul codice e due decisioni ancora aperte: il nome del kit (opzioni PROJECT1777/Kit Project Claude/Metodo Project) e l'ordine rispetto all'ondata 2.
- **keyword/entità:** PIANO_kit v1 · Arco B · kit generico · 7 punti · scheletri · nome da decidere · ondata 2 · file-ponte · OSS1777 caso-studio

---

### PRD — MVP piattaforma di peer review per articoli.md
- **source_id:** ad359a66-01e5-4034-9204-8da5cc5ae2f2  ·  **tipo:** text
- **sostanza:** Variante del PRD dell'MVP peer-review (corrisponde nei contenuti a 01-prd-mvp.md, qui con citazioni alle fonti "Verso-una-peer-review..." e "Una-cosa-un-sistema..."). Scopo (overlay review per AI/workflow), problema (grey literature senza review strutturata), 4 ruoli, proposta di valore overlay, scope in/out, rubriche a 7 dimensioni, user stories e 3 criteri di successo.
- **keyword/entità:** PRD · MVP · peer-review · overlay · 4 ruoli · rubriche · workflow editoriale · grey literature · criteri di successo

---

### Panoramica completa di registratori vocali continui hardware, software, AI, privacy e form factor (2026).md
- **source_id:** 2e12bc3a-a55d-44df-9cb0-c42b197d75f5  ·  **tipo:** text
- **sostanza:** Report-mappa completo dei registratori vocali continui 2026. Tassonomia in 7 macro-famiglie con tabelle dense per ciascuna: wearable AI note-taker (Plaud, Bee, Sonal, BOYA, Vocci Ring, FoCase...), software meeting (Otter, tl;dv, Fireflies), app smartphone background, registratori classici (Zoom/Sony/Philips), mini/spy, lifelogging desktop (Rewind.ai), form factor futuristici (earables, occhiali, ricerca). Tabella privacy sì/no, analisi economica CAPEX vs OPEX, analisi tecnologica e references numerate.
- **keyword/entità:** registratori vocali 2026 · tassonomia 7 famiglie · wearable AI · Plaud · Rewind.ai · privacy locale/cloud · CAPEX/OPEX · Whisper · VPU · form factor

---

### REPORT DI ARCHITETTURA DELLA CONOSCENZA: PROTOCOLLO DI SINCRONIZZAZIONE ONTOLOGICA "DEEP RESEARCH 2026"
- **source_id:** ca8d270e-6c30-469d-80b2-3366904cfa9f  ·  **tipo:** text
- **sostanza:** Report "Auditor di Verità" (firmato Dr. Marcus Vance) che sincronizza l'infrastruttura PROJECT1777 al 23 mag 2026 tramite deep research su 11 fonti. Registro raw e filtri anti-slop, matrice di sincronizzazione ontologica di 11 fonti (graphify cross-file v0.4.14, cohesion rounding #919, calls inversion #563, graspologic fallback #290, Dart MCP hosted, agentmemory dinamico), analisi dei 3 finding Cat 5 (super-hub/rounding, fallback Louvain Python 3.13+, convergenza grafo+memoria episodica), mappa ontologica finale (Motore/Diario/Prodotto/Bussola/Pezzo di Ferro) e ROI ~$490/anno.
- **keyword/entità:** Auditor di Verità · sincronizzazione ontologica · deep research 2026 · graphify · #919/#563/#290 · graspologic fallback · agentmemory · MAGMA · Regime A · ROI

---

### Releases · safishamsi/graphify - GitHub
- **source_id:** 73abbc32-ff28-4074-90de-895fd76b01de  ·  **tipo:** url
- **sostanza:** Pagina GitHub Releases di safishamsi/graphify (repo 52.3k star). Elenca le release recenti dalla v0.8.16 (CJK/Unicode dedup fix, .ets ArkTS, graphify install --project) a ritroso: v0.8.14 (--exclude, NAT64 SSRF), v0.8.13 (node ID collisions dir-qualified), v0.8.11 (LLM empty choices guard, surprise scoring 11x), v0.8.10 (fix #919 cohesion rounding + --resolution + --exclude-hubs majority-vote), v0.8.9 (DeepSeek), v0.8.8 (graphify prs dashboard), v0.8.5 (dedup variant guards). Conferma diretta dell'accoglienza di issue #919.
- **keyword/entità:** graphify releases · v0.8.16 · v0.8.10 · #919 · --exclude-hubs · --resolution · graphify prs · DeepSeek · NAT64 · 52.3k star

---

### Two extractor bugs systematically inflate god-node centrality (rationale fragments + calls direction inversion) · Issue #563 · safishamsi/graphify - GitHub
- **source_id:** 7d6db489-428b-403b-b5bb-98bda12e935d  ·  **tipo:** url
- **sostanza:** Issue #563 su safishamsi/graphify (aperta da WillRiverpoint, chiusa via PR #576). Diagnostica due bug dell'extractor che gonfiano la centralità dei god-node: Bug 1 = rationale extraction crea un pseudo-nodo per paragrafo di docstring (280 pseudo-nodi, 16.3%) attirando edge --uses-->; Bug 2 = direzione degli edge `calls` invertita (la classe risulta chiamare la funzione invece del contrario). Esempio SQLiteQueue (67 edge, ~80% rumore/invertiti). Saif fixa: rationale come attributo non nodo, regola calls caller→callee.
- **keyword/entità:** issue #563 · graphify · god-node · rationale leakage · calls direction inversion · SQLiteQueue · PR #576 · extractor bug · centralità · WillRiverpoint

---

### Why Claude Code Forgets Your Codebase (And the Fix) - Unblocked
- **source_id:** 90032c46-1af2-403d-9965-1645257dbd4e  ·  **tipo:** url
- **sostanza:** Articolo Unblocked (Dennis Pilarinos) sul perché Claude Code "dimentica" il codebase tra sessioni: la session memory si resetta a ogni /clear (by design), il CLAUDE.md è la memoria de-facto ma ogni token costa a ogni turno. Critica i memory MCP server (Stash, Hindsight, agentmemory): risolvono il "fact forgetting" (tassa preload 2-5k token) ma non lo "shape forgetting" (struttura codebase, convenzioni). Propone la context-source retrieval (progressive disclosure, recupero on-demand) come fix strutturale.
- **keyword/entità:** Claude Code · forgetting · CLAUDE.md · memory MCP · agentmemory · fact vs shape forgetting · context retrieval · progressive disclosure · re-explain tax · Unblocked

---

### `.[leiden]` and `.[all]` work on Python 3.10-3.12 but fail on Python 3.13+ because the `graspologic` dependency chain is not installable · Issue #290 · safishamsi/graphify - GitHub
- **source_id:** 27835b5a-3e38-4662-ae80-57473545efe5  ·  **tipo:** url
- **sostanza:** Issue #290 su safishamsi/graphify (aperta da 3esmit, chiusa, fix in v0.4.9). Segnala che gli extra `.[leiden]`/`.[all]` falliscono su Python 3.13+ perché graspologic risolve a 0.3.1 con gensim<=3.9.0 che fallisce la metadata generation (mentre su 3.10-3.12 risolve graspologic 3.4.4 e funziona). graphify ha già il fallback runtime a Louvain di networkx in _partition(). Propone di restringere requires-python a >=3.10,<3.13 o usare environment marker. Matrice versioni e workaround --no-deps dettagliati.
- **keyword/entità:** issue #290 · graphify · graspologic · Python 3.13 · gensim · Leiden · Louvain fallback · requires-python · v0.4.9 · packaging

---

### agente simile scritto in Dart !_giusto due note pe(1).md
- **source_id:** cfc996d4-8b51-49dc-9c58-3de539aebc3c  ·  **tipo:** text
- **sostanza:** Documento tecnico su come portare in Dart/Flutter i pattern di Claude Code (a partire dal leak del sorgente CLI/client) costruendo un agent harness repo-level clean-room, non rifacendo il modello. Architettura target in 6 moduli (agent_core, agent_tools, agent_runtime, agent_policy, agent_cli, agent_ui), event loop asincrono con step tipizzati su Stream/Future/isolate, tool minimi (fs/shell/git/test/HTTP/LSP), ApprovalGate/permission model, regola clean-room "spec prima implementazione poi", Flutter minimo (timeline/approvazioni/diff), roadmap v1-v3.
- **keyword/entità:** agente Dart · Flutter · harness agentico · clean-room · Claude Code leak · agent_core · ApprovalGate · permission model · event loop · claurst/claw-code

---

### agente simile scritto in Dart !_giusto due note pe.md
- **source_id:** bc50377e-be25-470f-b38d-4f7bf0abbe25  ·  **tipo:** text
- **sostanza:** Duplicato identico (stesso char_count) del documento agente Dart (1).md: stessa specifica dell'harness agentico repo-level in Dart/Flutter clean-room, 6 moduli, event loop tipizzato, tooling con permission model, Flutter minimo e roadmap v1-v3.
- **keyword/entità:** agente Dart · Flutter · harness · clean-room · duplicato · agent_core · permission model · roadmap

---

### agentmemory: Persistent Memory for Claude Code, Codex, Cursor, and Other Coding Agents
- **source_id:** 750a93e0-71d3-4f2e-b86f-516d9e393984  ·  **tipo:** url
- **sostanza:** Post del blog KnightLi che introduce rohitg00/agentmemory, sistema di memoria persistente per agenti AI coding (Claude Code, Codex CLI, Cursor, Gemini CLI, OpenCode, MCP). ~13k star, TypeScript, Apache-2.0. Risolve la frammentazione di memoria tramite un layer condiviso via servizio locale (localhost:3113), MCP, hook. Quick start (npm install -g @agentmemory/agentmemory, agentmemory connect claude-code), differenza dai file statici CLAUDE.md/AGENTS.md, scenari tipici e avvertenze (qualità memoria, privacy, non sostituisce i test).
- **keyword/entità:** agentmemory · rohitg00 · KnightLi · memoria persistente · MCP · Claude Code · Cursor · localhost:3113 · CLAUDE.md · cross-sessione

---

### catalogo-comandi-bash.md
- **source_id:** 60a1a998-e3f1-4d08-bf20-57c7eeca9954  ·  **tipo:** text
- **sostanza:** Catalogo di comandi bash collaudati (Step 3 del prompt-definitivo-v5.1) per il corpus OSS1777 (8 file .md). Preambolo configurabile (ROOT, LC_ALL UTF-8, array CORPUS via find, set -uo pipefail con || true), comandi per la lista-raw (ricerca mirata, mappa termine→conteggio→file con grep -Fiwc, termini orfani), per la lista-google (copertura, validazione 2-6 parole, export), per l'embedding (lunghezza chunk 8-40, JSONL via python3, quasi-duplicati), cronologia, aggiornamento liste. Collaudo reale (graphify 162, PR 70; 119/325 voci orfane) e nota metodologica raw verbatim vs unione.
- **keyword/entità:** catalogo bash · grep -Fiwc · portabilità UTF-8 · lista-raw/google/embedding · JSONL · orfani · prompt-definitivo-v5.1 · collaudo · RAG · set -uo pipefail

---

### chat_rename.md
- **source_id:** 6646a971-378a-483b-8c0c-078504a3efbe  ·  **tipo:** text
- **sostanza:** Trascrizione della sessione NotebookLM "PROJECT1777" (61 fonti, 23 mag) in cui si costruisce la mappa mentale ontologica del corpus. Contiene il prompt-istruzione (leggere integralmente ogni file, titoli come placeholder univoci, mappa su 4 livelli token/parola/frase/concettuale) e la risposta: mappa ontologica per famiglie (Motore/Prodotto/Diario/Bussola/Dominio), analisi multi-livello, stato integrità (duplicati, placeholder, buchi cluster.py/GRAPH_REPORT), generazione dei 4 artefatti e del Manuale Metodologico Universale agnostico con Virgin Entry Prompt e workflow 4 step.
- **keyword/entità:** chat_rename · PROJECT1777 · mappa ontologica · placeholder · famiglie funzionali · VEP · bootstrapping ricorsivo · Regime A/B · 4 artefatti · 61 fonti

---

### claude-memory-mcp - PyPI
- **source_id:** 33c53f43-d0e3-4060-87cd-98a51f97c189  ·  **tipo:** url
- **sostanza:** Pagina PyPI di claude-memory-mcp (MemCP) v0.3.0, server MCP di memoria persistente per Claude Code (maydali28/memcp, MIT, Python 3.10+). Risolve la perdita di contesto dopo /compact: implementa il framework RLM (Recursive Language Model, context-as-variable), grafo MAGMA a 4 archi (semantic/temporal/causal/entity) su SQLite, 24 tool MCP, ricerca a 5 tier (keyword→BM25→fuzzy→semantic→hybrid RRF), Hebbian strengthening, edge decay, sub-agent map-reduce, auto-save hook (PreCompact). Benchmark token efficiency fino a 218x, dipendenze opzionali a livelli.
- **keyword/entità:** claude-memory-mcp · MemCP · MAGMA · 4-graph · RLM · 24 MCP tools · ricerca 5-tier · Hebbian · /compact · benchmark token · SQLite

---

### GitHub - safishamsi/graphify: AI coding assistant skill...
- **source_id:** 54ef723b-b400-4718-97bc-000e6ee60634  ·  **tipo:** url
- **sostanza:** README ufficiale del repo safishamsi/graphify (branch v8, 52.3k star, MIT). graphify è una skill per AI coding assistant: `/graphify .` mappa codice/doc/PDF/immagini/video in un knowledge graph interrogabile, output graph.html/GRAPH_REPORT.md/graph.json. Supporta 18+ piattaforme (Claude Code, Codex, Cursor, Gemini CLI, Antigravity...). Pacchetto PyPI `graphifyy` (doppia y), comando `graphify`. Documenta install, extra opzionali, comandi (--cluster-only, --resolution, --exclude-hubs, query/path/explain, prs dashboard, export callflow-html), 31 linguaggi, privacy (AST locale), env var per backend.
- **keyword/entità:** graphify · README · safishamsi · knowledge graph · /graphify · graphifyy · --exclude-hubs · --resolution · graph.json · MCP · 52.3k star · multi-platform

---

### Graphify: Build a Knowledge Graph From Your Entire Codebase — Without Sending Your Code to Anyone - GoPenAI
- **source_id:** a327ca1c-21ca-4370-a5a6-a1be94f68e1b  ·  **tipo:** url
- **sostanza:** URL blog.gopenai.com bloccata da Cloudflare ("Just a moment... Performing security verification", Ray ID a005223c). Contenuto reale non recuperato: la fonte indicizzata è solo la challenge page anti-bot. Tema dichiarato dal titolo: articolo su graphify e knowledge graph locale del codebase senza inviare codice a terzi.
- **keyword/entità:** graphify · GoPenAI · Cloudflare blocked · knowledge graph · contenuto non recuperato

---

### I Spent $60 on Perplexity Pro. The Output Would Have Cost Me $15,000+ from Consultants _ Medium.pdf
- **source_id:** 6c079b89-cd0a-4540-8a3a-ed3f5a8dfb6c  ·  **tipo:** pdf
- **sostanza:** PDF dell'articolo Medium pubblicato di Neo1777 (versione inglese, 11 min, 4 mag 2026) corrispondente a 05_articolo_medium_IT.md. "Ho speso $60 su Perplexity Pro... avrei pagato $15.000+ da consulenti": workflow di ricerca in 4 step, 6 principi epistemologici (exploratory neutrality, mandatory primary citations, emerging patterns section, limitations as honesty markers, categorized audit, anti-decommissioning discipline), numeri trasparenti (140k parole, ~330 cluster, ROI 250-500x) e setup API advanced-deep-research. Estratto via OCR NotebookLM con immagini di pagina incorporate.
- **keyword/entità:** Perplexity Pro · Medium PDF · Neo1777 · workflow 4 step · anti-decommissioning · primary citations · $60 vs $15k · advanced-deep-research · ROI 250-500x

---

### PROJECT1777: Guide to Claude Proje — immagine 1
- **source_id:** 54cf70a3-2d2b-46c2-af84-1c8a6e52d9a3  ·  **tipo:** image
- **sostanza:** Fonte immagine del notebook (image_id 8f107336, URL googleusercontent/notebooklm). source_get_content non restituisce testo OCR né descrizione: solo l'URL dell'immagine e il suo identificatore. Contenuto visivo non analizzabile da questo strumento; è una delle due immagini di copertina/illustrazione del Project PROJECT1777.
- **keyword/entità:** immagine · PROJECT1777 · googleusercontent · no OCR · contenuto visivo non recuperato

---

### PROJECT1777: Guide to Claude Proje — immagine 2
- **source_id:** cbd85c4d-df5f-495b-b545-edd590d51003  ·  **tipo:** image
- **sostanza:** Seconda fonte immagine del notebook (image_id 3d378b12, URL googleusercontent/notebooklm). Come l'immagine 1, source_get_content restituisce solo l'URL e l'identificatore, nessun testo OCR né descrizione. Contenuto visivo non analizzabile da questo strumento.
- **keyword/entità:** immagine · PROJECT1777 · googleusercontent · no OCR · contenuto visivo non recuperato

---

### dart-agent-technical-spec.md
- **source_id:** 3a280d99-e1b4-41d5-b9f7-7d897cc403a7  ·  **tipo:** text
- **sostanza:** Specifica tecnica completa di un agente coding repo-level in Dart (CLI-first + Flutter desktop minimale, clean-room ispirato a Claude Code/claw-code/claurst). Definisce prodotto, 6 principi architetturali (harness-first, CLI primaria, clean-room, typed tool/event, approvazione umana, replayability), 6 sottosistemi (agent_core/tools/runtime/policy/cli/ui), requisiti funzionali/non-funzionali, struttura monorepo melos, modello a eventi (event sourcing), tool system con shell policy a 4 livelli (auto/confirm/elevated/forbidden), context compaction, provider abstraction, security/threat model e roadmap v1-v3.
- **keyword/entità:** dart-agent spec · repo-level agent · clean-room · Claude Code · event sourcing · shell policy · approval gate · context compaction · monorepo melos · roadmap v1-v3

---

### esempio-modifiche-saif.md
- **source_id:** d658f6f2-6cb0-4c8c-b38e-5d275017966f  ·  **tipo:** text
- **sostanza:** Spiegazione tecnica (stile "perché prima del come") delle modifiche di Saif al fix #934, verificate sul commit 076e6b7 di __main__.py e tests/test_cli_export.py. Modifica 1: la riga mkdir (identica a quella di Neo) spostata 17 righe più su, appena out è definito (riga 1811) — non correttezza ma qualità: coesione, invariante "out esiste da qui in poi", simmetria coi due codepath. Modifica 2: regression test via subprocess reale (helper _make_graph/_run già nel repo) che noi avevamo stimato oneroso senza aprire test_cli_export.py. Lezioni per l'ondata 2 (invariante, mappare gli helper prima di stimare).
- **keyword/entità:** fix Saif · #934 · commit 076e6b7 · mkdir riga 1811 · invariante · regression test · subprocess · _make_graph/_run · qualità patch · spiegazione-tecnica

---

### Mappa id - lista di (neighborid, edgedata) [2]
- **source_id:** 258d40de-a9d6-4302-83c1-9cacc1aa65dc  ·  **tipo:** text
- **sostanza:** [oversized ~890k char — non leggibile in un singolo get_content] Duplicato confermato della "Mappa id [1]" (0bf5a5a6): stessa trascrizione completa della sessione principale OSS1777 (chat operativa lunga, ~848k/11.841 righe). Stesso arco #919→#934→PR #942 e costruzione del metodo. Fonte identica caricata in parallelo nel notebook.
- **keyword/entità:** trascrizione completa · OSS1777 · oversized · duplicato · issue #919/#934 · PR #942 · prompt-madre · METAPROMPT1777

---

### Framework di Architettura della Conoscenza_ Dal Caos Informativo al Valore Economico.md
- **source_id:** 5c8ca3ca-43fb-439e-8be4-114120d68e64  ·  **tipo:** text
- **sostanza:** [non letto: API error persistente dopo 3 tentativi — "Failed to get source content"]. Dal titolo e dal contesto del corpus (citato in "Architettura della Conoscenza: Il Metodo PROJECT1777"): espone la visione strategica del metodo ontologico sulla Densità Semantica e il passaggio al Regime A (creazione di nuova conoscenza vs compressione), trasformando il caos informativo in valore economico. Voce ricostruita dal titolo, non dal contenuto letto.
- **keyword/entità:** architettura della conoscenza · densità semantica · Regime A · valore economico · metodo ontologico · non letto · API error

---

### Graphify_ Karpathy, Saif, Neo1777 Connection.md
- **source_id:** 866260ad-726e-4446-94a6-77b7829db55  ·  **tipo:** text
- **sostanza:** [non letto: API error persistente dopo 3 tentativi — "Failed to get source content"]. Dal titolo: documento che collega la figura di Karpathy, il maintainer Saif Shamsi (graphify) e neo1777 — verosimilmente il "gancio" narrativo/marketing discusso altrove nel corpus (Karpathy come gancio "nullo ma reale" per l'articolo Medium, l'arco del contributo a graphify). Voce ricostruita dal titolo, non dal contenuto letto.
- **keyword/entità:** graphify · Karpathy · Saif · neo1777 · gancio marketing · connessione · non letto · API error

---

> **RIEPILOGO ANOMALIE**
>
> - **Duplicati confermati (4 coppie):** agente Dart (cfc996d4/bc50377e) · registratore vocale (c8d9e11d/a2878069) · prompt bidirezionalità palantir (e473a987/1fa804b9) · claude-share analisi grafo (0dbaecb9/4d7549a7) · Mappa id [1]/[2] (0bf5a5a6/258d40de)
> - **Source oversized campionate:** Mappa id [1] e [2] (862k chars ciascuna) · agentmemory GitHub (81k chars) · claude-share [1] e [2] (~102k chars ciascuna)
> - **URL bloccate Cloudflare (2):** claude-world.com · blog.gopenai.com
> - **Source immagine:** nessuna identificata in questo notebook
> - **Voci totali scritte:** 94 (comprese le voci delle sessioni precedenti ricostruite dal summary)
