# Indice di contenuto profondo — account NotebookLM 1777 — parte 6/6
> Sessione 2026-06-01 · provenienza/metodo nella parte 1/6 · 975 voci totali su 48 notebook · layer di contenuto complementare al catalogo strutturale.

### Reddit r/AI_Agents — Karpathy LLM-Wiki pattern
- **source_id:** 51e8f808 · **tipo:** url
- **sostanza:** Thread Reddit su r/AI_Agents che discute il pattern LLM-Wiki di Karpathy e la sua implementazione open source llm-wiki-compiler (repo atomicstrata). La community discute pro/contro rispetto a RAG classico, casi d'uso, e integrazioni possibili.
- **keyword/entità:** Reddit · r/AI_Agents · Karpathy · LLM-Wiki · llm-wiki-compiler · atomicstrata · RAG · community discussion

### atomicstrata/llm-wiki-compiler — GitHub
- **source_id:** 884c60bf · **tipo:** url
- **sostanza:** README del repo GitHub atomicstrata/llm-wiki-compiler (1.4k stelle, Node.js, MIT). CLI a due fasi (compile + query), SHA-256 per rilevare cambiamenti nelle sorgenti, MCP server integrato, eval harness per valutare qualità della wiki generata. Versione v0.8.0.
- **keyword/entità:** llm-wiki-compiler · atomicstrata · Node.js · CLI · SHA-256 · MCP server · eval harness · knowledge compilation · GitHub · 1.4k stars

### Prompt Deep Research Master — documento interno
- **source_id:** 827f5acd · **tipo:** text
- **sostanza:** Prompt interno per deep research su libri/competenze: guida un agente LLM a estrarre struttura, concetti chiave, skill acquisibili e applicazioni pratiche da un testo. Usato come metodologia per trasformare sorgenti raw in knowledge strutturata.
- **keyword/entità:** deep research · prompt · skill extraction · book analysis · LLM agent · metodologia

### Capco — Knowledge Graphs (PDF con immagini)
- **source_id:** aba28df9 · **tipo:** pdf
- **sostanza:** Documento PDF di Capco sui knowledge graphs in ambito enterprise/finanziario. Tratta ETL vs virtualizzazione per l'integrazione dati, architetture di knowledge graph, e applicazioni nel settore finanziario. Il PDF contiene molte immagini con testo embedded.
- **keyword/entità:** Capco · knowledge graph · ETL · virtualizzazione · enterprise · finanza · integrazione dati

### Towards AI — Karpathy LLM Wiki (Cloudflare blocked)
- **source_id:** dfe7cc23 · **tipo:** url
- **sostanza:** Articolo su Towards AI riguardante l'LLM Wiki di Karpathy. Contenuto non accessibile: la pagina restituisce solo la verifica Cloudflare (~510 caratteri). Tematica inferita dal titolo: LLM Wiki, knowledge compilation, Karpathy.
- **keyword/entità:** Towards AI · Karpathy · LLM Wiki · Cloudflare · knowledge compilation [contenuto non accessibile]

### Towards AI — LLM Wiki (seconda copia, Cloudflare blocked)
- **source_id:** 5edfd951 · **tipo:** url
- **sostanza:** Seconda copia di articolo Towards AI sull'LLM Wiki. Identico blocco Cloudflare (~510 caratteri). Contenuto non leggibile.
- **keyword/entità:** Towards AI · LLM Wiki · Cloudflare [contenuto non accessibile]

### APKC — A Priori Knowledge Compilation (OpenReview / ICLR 2026)
- **source_id:** 73bf7aff · **tipo:** url
- **sostanza:** Pagina OpenReview del paper "Curing the Transitivity Curse: Shortcut Logical Reasoning via A Priori Knowledge Compilation" (Mo, Pan, Hou et al.), submission ICLR 2026 poi ritirata dagli autori. Affronta la "Transitivity Curse" degli LLM (incapacità di dedurre P→R da P→Q ∧ Q→R). APKC è un meccanismo plug-in in due fasi: backward analysis goal-oriented per isolare un sottografo rilevante, poi forward-chaining per sintetizzare fatti derivati e regole composite ("shortcut reasoning"). Include 4 review (rating 2-4, criticati motivazione non dimostrata e related work datato).
- **keyword/entità:** APKC · transitivity curse · shortcut reasoning · knowledge compilation · forward-chaining · SymbCoT · ICLR 2026 · OpenReview · withdrawn

### Partial Compilation of Strategic Knowledge — AAAI 1987 (Altman & Buchanan)
- **source_id:** 25a2849f · **tipo:** text
- **sostanza:** Paper AAAI-87 di Russ B. Altman e Bruce G. Buchanan (Knowledge Systems Laboratory, Stanford) sulla compilazione parziale della conoscenza strategica. Propone un paradigma a 3 fasi (opportunistic → partial plan → procedure) per trasformare conoscenza di controllo dichiarativa in procedure efficienti, usando il sistema PROTEAN (determinazione struttura proteica via constraint satisfaction su blackboard BB1, azioni ANCHOR/YOKE/APPEND/CONSOLIDATE). Caso d'uso: T4 Lysozyme. È la fonte primaria del concetto "knowledge compilation" applicato a PROTEAN.
- **keyword/entità:** Altman · Buchanan · Stanford KSL · AAAI 1987 · partial compilation · strategic knowledge · PROTEAN · BB1 · constraint satisfaction · ACCORD · T4 Lysozyme

### I.M.P.A.K.T. — Large Scale Skill Matching (SisInfLab, Politecnico Bari)
- **source_id:** e4fc1b59 · **tipo:** text
- **sostanza:** Paper di Tinelli, Colucci, Giannini, Di Sciascio, Donini (SisInfLab Politecnico Bari + Univ. Tuscia) su skill matching automatico via knowledge compilation. Una KB in Description Logics (FL0(D), ~5000 concetti) viene tradotta off-line in un database relazionale (CCNF), così il matching avviene on-line con query SQL standard. Implementato nel sistema I.M.P.A.K.T. con Strict Match e Soft Match, ranking spiegabile e test di scalabilità su PostgreSQL (datasets 500-5500 profili).
- **keyword/entità:** I.M.P.A.K.T. · SisInfLab · Politecnico Bari · skill matching · knowledge compilation · Description Logics · FL0(D) · CCNF · SQL · PostgreSQL · HR

### Memoriki — LLM Wiki + MemPalace (GitHub)
- **source_id:** 29fe5017 · **tipo:** url
- **sostanza:** [API non disponibile dopo 3 tentativi — contenuto non recuperato] Repository GitHub AyanbekDos/memoriki: "LLM Wiki + MemPalace, personal knowledge base with real memory" (~105 stelle, Python). Da fonti collaterali nel notebook: combina ingestione markdown + compilazione directory Obsidian con un MCP server MemPalace che sovrappone indicizzazione vettoriale semantica alla wiki strutturata; wikilink bidirezionali, log append-only, index.md automatico.
- **keyword/entità:** Memoriki · AyanbekDos · MemPalace · LLM Wiki · MCP · Obsidian · semantic vector · BM25 · GitHub [non letto: API error]

### LLM Wiki v2 — rohitg00 GitHub Gist (agentmemory)
- **source_id:** 554441e6 · **tipo:** url
- **sostanza:** Gist rohitg00/llm-wiki.md (fork di Karpathy, ~1310 stelle): "LLM Wiki v2" che estende il pattern con lezioni da agentmemory. Aggiunge il layer mancante del memory lifecycle (confidence scoring, supersession, forgetting curve di Ebbinghaus, tier working/episodic/semantic/procedural), knowledge graph tipizzato con entity extraction, hybrid search (BM25+vector+graph con RRF), automazione event-driven (hook), quality scoring/self-healing, multi-agent sync e privacy/governance. I commenti includono critiche dure (false precision dei confidence score, decay sugli errori, LLM inaffidabili come writer).
- **keyword/entità:** LLM Wiki v2 · rohitg00 · agentmemory · GitHub Gist · memory lifecycle · confidence scoring · supersession · Ebbinghaus · knowledge graph · hybrid search · RRF · BM25

### Comparative Analysis of Agentic Knowledge Compilation (documento interno)
- **source_id:** 40c86eb1 · **tipo:** text
- **sostanza:** Lungo report di sintesi (deep research) che confronta il paradigma della knowledge compilation con il RAG stateless. Copre l'analogia col compilatore software (raw=sorgente, agente=compiler, wiki=binario), audit delle implementazioni open source (Synthadoc, obsidian-llm-wiki, llm-wiki-compiler, memoriki) con tabelle, workflow strutturali a 3 tier, benchmark quantitativi (WiCER/LLM-Wiki: KV cache vs RAG, compilation gap, CEGAR, Transitivity Curse) e analisi avversariale dei failure mode (hallucination propagation, concept drift, scale boundary). Include bibliografia di ~38 fonti, molte coincidenti con quelle del notebook.
- **keyword/entità:** knowledge compilation · agentic · RAG · compilation gap · WiCER · CEGAR · transitivity curse · hallucination propagation · Synthadoc · benchmark · deep research

### Andrej Karpathy's LLM Wiki — r/CreatorsAI (Reddit)
- **source_id:** 58296d32 · **tipo:** url
- **sostanza:** Thread r/CreatorsAI: uno sviluppatore costruisce l'LLM Wiki di Karpathy in un weekend e riferisce risultati misti. Le domande di sintesi cross-documento funzionano (es. collegare il Bitter Lesson di Sutton e Software 2.0 di Karpathy, già compilato in fase di ingest); ma le allucinazioni introdotte durante l'ingest si propagano come fatti, il lint è non negoziabile e l'ingest è costoso. Conclusione: LLM Wiki e RAG non sono concorrenti ma strumenti per problemi diversi (Wiki per <200 fonti curate; RAG per >1000 fonti ad alto churn).
- **keyword/entità:** Reddit · r/CreatorsAI · Karpathy · LLM Wiki · synthesis · hallucination propagation · lint · RAG · ingest cost

### Architetti del Sapere — Professioni e Skill per l'IA Navigabile (nota interna)
- **source_id:** cc60e73c · **tipo:** text
- **sostanza:** Nota di sintesi (NotebookLM) che, a partire dalle fonti del notebook, delinea le figure professionali e le skill per la knowledge compilation/LLM Wiki: ruolo centrale del Knowledge Engineer (agente come "compilatore"), ricercatori/analisti, esperti di dominio, sviluppatori, bibliotecari (richiamo al Memex di Bush). Skill minori: bookkeeping, visual thinking (Excalidraw skill), linting/health check, curation come quality gate, multi-modal capture, prompt engineering di sistema (CLAUDE.md).
- **keyword/entità:** knowledge engineer · skill · book-to-skill · Memex · bookkeeping · visual thinking · Excalidraw · linting · curation · CLAUDE.md

### CLAUDE.md — LLM Wiki Agent (SamurAIGPT, GitHub)
- **source_id:** a68d03d0 · **tipo:** url
- **sostanza:** File CLAUDE.md del repo SamurAIGPT/llm-wiki-agent (2.8k stelle): schema e istruzioni di workflow per una wiki mantenuta interamente da Claude Code, senza API key né script Python. Definisce slash command (/wiki-ingest, /wiki-query, /wiki-health, /wiki-lint, /wiki-graph), layout directory (raw/ immutabile + wiki/ con sources/entities/concepts/syntheses), formato frontmatter, workflow di ingest a 10 step, query, lint, health (zero LLM call) e graph. Auto-conversione di 20+ formati via markitdown.
- **keyword/entità:** SamurAIGPT · llm-wiki-agent · CLAUDE.md · Claude Code · slash commands · ingest workflow · health vs lint · knowledge graph · markitdown

### Competenze lavorative 2026 — Challenge Network
- **source_id:** ad7f6fea · **tipo:** url
- **sostanza:** Articolo Challenge Network sulle skill più richieste nel 2026. Cita il Future of Jobs Report 2025 (WEF: ~44% delle competenze chiave in trasformazione, ~60% della forza lavoro da riqualificare) e lo Stanford AI Index 2025 (>75% aziende usano AI). Tratta AI/digital fluency come competenza trasversale, cybersecurity come responsabilità condivisa, leadership/decision making nei contesti complessi, change mindset e competenze ibride (digitale + pensiero critico + leadership umana).
- **keyword/entità:** Challenge Network · competenze 2026 · WEF Future of Jobs · Stanford AI Index · digital fluency · cybersecurity · leadership · reskilling · competenze ibride

### Converti Libri in Skills di Claude — video/trascrizione (book-to-skill)
- **source_id:** 66b8ba62 · **tipo:** text
- **sostanza:** Trascrizione di un video italiano che presenta uno strumento "book-to-skill": converte un libro tecnico (anche 400 pagine) in una skill per agenti AI (Claude Code, Codex). Spiega la differenza tra RAG (cerca) e skill (ragiona/conoscenza pronta), il flusso di compilazione (skill.md con mappa mentale + indice, file per capitolo, glossary.md, patterns.md, cheat-sheet.md), la scelta docink vs pdf-to-text in base a documento tecnico/text-heavy, i comandi slash e una demo pratica (Atomic Habits, 4 leggi del comportamento).
- **keyword/entità:** book-to-skill · Claude Code · skill · RAG vs skill · knowledge compilation · docink · pdf-to-text · glossary · patterns · cheat-sheet · Atomic Habits

### Curing the Transitivity Curse — OpenReview (vedi APKC)
- **source_id:** vedi 73bf7aff (stessa pagina OpenReview, già indicizzata sopra come APKC)
- **nota:** source_id 73bf7aff corrisponde a questa pagina; entry completa sopra in "APKC — A Priori Knowledge Compilation".

### Dal digital curator al data librarian — Biblioteche oggi (Editrice Bibliografica)
- **source_id:** 9568507e · **tipo:** url
- **sostanza:** Articolo di Maria Cassella (Univ. Torino) su Biblioteche oggi (2016). Definisce il "data librarian" come nuovo ruolo professionale, specializzazione del digital curator, e lo distingue dagli altri ruoli di data management (data creator, manager, scientist). Propone un nucleo di competenze su 5 macroaree: biblioteconomia/scienza dell'informazione, comunicazione scientifica, tecnologia, diritti di proprietà intellettuale, gestione. Testo completo dietro paywall (qui solo abstract IT/EN).
- **keyword/entità:** data librarian · digital curator · Maria Cassella · biblioteconomia · data management · data curation · competenze · Biblioteche oggi

### GitHub - crazynomad/skills (Green Train Skills)
- **source_id:** 0fc1f5dc · **tipo:** url
- **sostanza:** README del repo crazynomad/skills "Green Train Skills" (24 stelle, MIT): agent skills per media/content processing pensate per non-coder, installabili in Claude Code. Include doc-mindmap (converte office docs in Markdown, summary via Ollama locale, classificazione symlink topic/usage/client — testato su 4000+ PPT), disk-cleaner, file-organizer, downloader (YouTube/podcast/Twitter), tts, e una metodologia PPT "think-before-you-slide" (ppt-classify, research-setup, narrative-review, visual-deck).
- **keyword/entità:** crazynomad · Green Train Skills · Claude Code · doc-mindmap · Ollama · knowledge base · PPT · media processing · markitdown · MIT

### Guida all'Integrazione di Book-to-Skill — nota interna
- **source_id:** 2bf9e849 · **tipo:** text
- **sostanza:** Nota interna (NotebookLM) che propone come scaricare e analizzare il repository "book-to-skill" citato nelle fonti: offre un'opzione di deep research per trovare il repo GitHub ufficiale e un prompt pronto per analizzarne l'architettura (logica di estrazione docink vs pdf-to-text, pipeline di compilazione verso skill.md/patterns.md/glossary.md/cheat-sheet.md, gestione del contesto on-the-fly, mapping dei comandi slash).
- **keyword/entità:** book-to-skill · deep research · prompt · GitHub · docink · pdf-to-text · skill compilation · NotebookLM

### How to Build Karpathy's LLM Wiki — Starmorph
- **source_id:** 98e5121e · **tipo:** url
- **sostanza:** [API non disponibile dopo 3 tentativi — contenuto non recuperato] Articolo del blog Starmorph "How to Build Karpathy's LLM Wiki: The Complete Guide to AI-Maintained Knowledge Bases". Guida completa all'implementazione del pattern LLM Wiki di Karpathy come knowledge base mantenuta da AI (riferito da altre fonti del notebook come guida pratica step-by-step).
- **keyword/entità:** Starmorph · Karpathy · LLM Wiki · knowledge base · guida · AI-maintained [non letto: API error]

### Ingegneria della conoscenza — Okpedia
- **source_id:** 04557821 · **tipo:** url
- **sostanza:** Voce Okpedia sull'ingegneria della conoscenza (knowledge engineering): disciplina della rappresentazione della conoscenza in cui l'ingegnere analizza un dominio per costruirne una rappresentazione formale (oggetti e relazioni), abilitando basi di conoscenza e sistemi esperti. Descrive la figura del knowledge engineer (nata negli anni '90), che coordina lo sviluppo dei sistemi esperti lavorando con i domain expert nella concettualizzazione, analisi e formalizzazione.
- **keyword/entità:** ingegneria della conoscenza · knowledge engineer · rappresentazione della conoscenza · sistemi esperti · base di conoscenza · domain expert · Okpedia

### Ingegneria della conoscenza — Wikipedia
- **source_id:** ad693d69 · **tipo:** url
- **sostanza:** Voce Wikipedia (it) sull'ingegneria della conoscenza: disciplina che integra la conoscenza in sistemi informatici per risolvere problemi complessi che richiedono alta specializzazione umana; riguarda costruzione, manutenzione e sviluppo di sistemi basati sulla conoscenza. Correlata a ingegneria del software, intelligenza artificiale, basi di dati, data mining, sistemi esperti, logica matematica e scienze cognitive. Voce breve, segnalata come priva di fonti sufficienti.
- **keyword/entità:** ingegneria della conoscenza · knowledge engineering · sistemi basati sulla conoscenza · IA · data mining · sistemi esperti · logica matematica · Wikipedia

### Karpathy's LLM Wiki vs Tiago Forte — r/PKMS (Reddit)
- **source_id:** edd2e443 · **tipo:** url
- **sostanza:** Thread r/PKMS che sostiene che l'LLM Wiki di Karpathy sia una versione peggiore del workflow CODE (Capture-Organize-Distill-Express) di Tiago Forte (Building a Second Brain, 2017). Critica 3 problemi: scalabilità (directory piatta cede oltre ~5000 fonti), manutenzione/drift dei doc compilati, capture multi-modale assente. Suggerisce strumenti esistenti (Recall, Mem, NotebookLM, Obsidian+Smart Connections). I commenti dibattono il "generation effect" (delegare la distillazione all'LLM fa perdere la comprensione) e chiariscono che il punto di Karpathy è ottimizzare il contesto PER l'AI, non sostituire il PKM umano.
- **keyword/entità:** Reddit · r/PKMS · Karpathy · LLM Wiki · Tiago Forte · CODE · Building a Second Brain · generation effect · scalabilità · Recall · Mem · Obsidian

### Karpathy's LLM Wiki — Hermes Agent (Nous Research)
- **source_id:** a5befb4d · **tipo:** url
- **sostanza:** Documentazione della skill "llm-wiki" (v2.1.0, MIT) del framework Hermes Agent di Nous Research, che bundla il pattern Karpathy. Riporta l'intero SKILL.md: architettura a 3 layer (raw/ immutabile, wiki/ con entities/concepts/comparisons/queries, SCHEMA.md), procedura di orientamento obbligatoria a inizio sessione (leggi SCHEMA+index+log), inizializzazione, template SCHEMA/frontmatter (con provenance marker, sha256, confidence/contested), soglie di pagina, operazioni ingest/query/lint, e integrazione Obsidian (anche headless via Obsidian Sync su server).
- **keyword/entità:** Hermes Agent · Nous Research · llm-wiki skill · Karpathy · SCHEMA.md · frontmatter · sha256 · provenance · ingest/query/lint · Obsidian headless · MIT

### Knowledge Representation in AI — GeeksforGeeks
- **source_id:** cdb8dc87 · **tipo:** url
- **sostanza:** Articolo didattico GeeksforGeeks sulla rappresentazione della conoscenza (KR) nell'AI. Definisce i tipi di conoscenza (dichiarativa, procedurale, meta, euristica, strutturale) e il legame conoscenza-intelligenza, poi descrive le 4 tecniche principali di KR con pro/contro: logical representation (logica proposizionale/predicati), semantic network (nodi/archi, IS-A), frame (slot/valori), production rules (IF-THEN). Applicazioni: sistemi esperti, NLP, robotica, semantic web; sfide: complessità, ambiguità, scalabilità, knowledge acquisition.
- **keyword/entità:** knowledge representation · GeeksforGeeks · dichiarativa/procedurale · logical representation · semantic network · frame · production rules · sistemi esperti · NLP

### La differenza tra Gestione dei documenti e Gestione della conoscenza — REWO
- **source_id:** 0dc89659 · **tipo:** url
- **sostanza:** Articolo REWO (VIAR) che distingue Document Management (DM) da Knowledge Management (KM). Il DM riguarda acquisizione, archiviazione e recupero di documenti elettronici (DMS) con sicurezza, controllo accessi e ricerca. Il KM è il processo di acquisizione, distribuzione e uso efficace della conoscenza: va oltre la gestione delle informazioni fornendo insight, know-how, esperienza e guida ("mentorship in forma scritta"), come componente integrale della strategia aziendale.
- **keyword/entità:** REWO · VIAR · document management · DMS · knowledge management · gestione della conoscenza · information management · know-how

### Nuove professioni e competenze nell'era dell'IA — SD Digital Lab
- **source_id:** 49ec89e8 · **tipo:** url
- **sostanza:** Articolo SD Digital Lab (Davide Saglimbeni) sulle nuove professioni create dall'IA. Profila figure emergenti: AI Manager (ponte tra tecnologia e business), Prompt Engineer (progettazione di input strategici per LLM), Automation Specialist (marketing automation, chatbot, funnel), AI Content Strategist (AI+SEO+analisi). Competenze chiave 2026: pensiero critico, capacità analitica, data literacy, strategia digitale, comunicazione evoluta, comprensione etica dell'AI. Tesi: non sostituzione ma trasformazione/evoluzione delle professioni.
- **keyword/entità:** SD Digital Lab · nuove professioni · AI Manager · Prompt Engineer · Automation Specialist · AI Content Strategist · data literacy · competenze · trasformazione

### WiCER — arXiv 2605.07068 (full text)
- **source_id:** d323e56e · **tipo:** url
- **sostanza:** Testo completo del paper WiCER (Juan M. Huerta, Zinnia Tech Solutions). Caratterizza il "compilation gap" del pattern LLM Wiki su 17 domini RepLiQA (6.800 domande): full-context KV cache batte RAG su conoscenza curata (4,38 vs 4,08; TTFT 7,3× più veloce) ma degrada su scala per attention dilution; la compilazione "cieca" fallisce (53–60% catastrophic failure). WiCER è un algoritmo iterativo ispirato a CEGAR che valuta la wiki contro probe diagnostiche, individua fatti scartati e ne forza la conservazione: 1–2 iterazioni recuperano l'80% della qualità persa.
- **keyword/entità:** WiCER · Juan M. Huerta · compilation gap · CEGAR · KV cache · RepLiQA · attention dilution · catastrophic failure · arXiv 2605.07068

### WiCER — arXiv HTML (seconda copia)
- **source_id:** 90cc86e4 · **tipo:** url
- **sostanza:** Seconda copia (versione HTML arXiv) dello stesso paper WiCER, con table-of-contents completo: Introduzione, Related Work (RAG, KV cache optimization/sharing, knowledge compilation, cache-augmented generation, LLM-as-Judge), Experimental Setup (corpora Policygenius curato + RepLiQA raw multi-dominio, generazione QA). Contenuto sostanziale identico alla copia full-text.
- **keyword/entità:** WiCER · arXiv HTML · KV cache · cache-augmented generation · Policygenius · RepLiQA · LLM-as-Judge

### WiCER — abstract page arXiv
- **source_id:** 49834753 · **tipo:** url
- **sostanza:** Pagina abstract di arXiv [2605.07068], inviata l'8 maggio 2026, autore Juan M. Huerta (cs.CL/cs.AI). Riporta solo l'abstract di WiCER (stesse metriche: 4,38 vs 4,08, 7,3× TTFT, recupero 80% qualità in 1–2 iterazioni, +0,95 da diagnosi mirata vs +0,16 da pinning generico) più link a PDF/HTML/TeX e metadati di citazione.
- **keyword/entità:** WiCER · arXiv abstract · 2605.07068 · Juan M. Huerta · cs.CL · diagnosi mirata · pinning

### Typology of knowledge, skills and competences — Cedefop
- **source_id:** 0c7b659f · **tipo:** url
- **sostanza:** Studio Cedefop (European Centre for the Development of Vocational Training, Thessaloniki) "Typology of knowledge, skills and competences — Clarification of the concept and prototype". Chiarisce concetti e tassonomie usate negli Stati membri per il trasferimento di crediti (learning outcomes). Mostra che il termine "competence" è ambiguo e propone di distinguere competenza cognitiva, funzionale e meta-competenza (personale/sociale-attitudinale), aggiungendo knowledge e skills.
- **keyword/entità:** Cedefop · knowledge · skills · competences · learning outcomes · credit transfer · cognitive/functional/meta-competence · VET

### What Is Andrej Karpathy's LLM Wiki — MindStudio
- **source_id:** 7ee77839 · **tipo:** url
- **sostanza:** Guida MindStudio (apr 2026) che spiega l'LLM Wiki di Karpathy come workflow (non prodotto): file markdown strutturati interrogati da Claude Code. Argomenta perché il markdown è il formato giusto (portabile, letto nativamente dagli LLM, forza chiarezza, no lock-in), descrive l'architettura minima (cartella .md + struttura consistente + Claude Code come interfaccia), setup passo-passo in Obsidian, best practice (summary line, terminologia consistente, wikilink, note focalizzate) e accenno a semantic search/RAG a scala.
- **keyword/entità:** MindStudio · Karpathy · LLM Wiki · markdown · Claude Code · Obsidian · second brain · semantic search · LlamaIndex

### What's the deal with the hype — Reddit r/ObsidianMD
- **source_id:** 671942c1 · **tipo:** url
- **sostanza:** Thread r/ObsidianMD (post stickied/locked) scettico: l'OP vede l'LLM Wiki come "zettelkasten generato da AI" e dubita della sostenibilità a 10K+ note (hallucination, costi token, manutenzione). I commenti chiariscono il punto di Karpathy (organizzare i dati PER l'AI, non l'inverso; vault separato AI-managed; efficienza token via indici), citano il rischio di corruzione documenti (paper Microsoft), e segnalano l'uso di git per "swappare" knowledge base tematiche; alcuni lo trovano molto utile per memoria condivisa di team.
- **keyword/entità:** Reddit r/ObsidianMD · Karpathy · LLM Wiki · zettelkasten · hallucination · token efficiency · git · second brain · manutenzione

### Your Knowledge Base Is Rotting? — Mono Software
- **source_id:** b6b9bd9d · **tipo:** url
- **sostanza:** Articolo di Denis Susac (Mono Software, apr 2026): i sistemi PKM falliscono per ragioni architetturali, non di disciplina. L'LLM Wiki di Karpathy è un fix strutturale: un agente sintetizza in continuo le fonti in una wiki mantenuta (stateful), contro RAG stateless. Rifiuta il framing "RAG is dead": propone architettura a 3 layer (wiki pages → raw vault files → LLM general knowledge) con vector search tra layer 1 e 2. Descrive l'implementazione reale (_wiki/, SCHEMA.md, index.md, workflow di ingest a 9 step, /ingest, routing wiki-first) e i quality gate manuali.
- **keyword/entità:** Mono Software · Denis Susac · PKM · LLM Wiki · RAG stateless · layered retrieval · SCHEMA.md · ingest workflow · Dokko · PARA · quality gate

### eXplainable AI: Why and How — CNRS
- **source_id:** ca415f04 · **tipo:** url
- **sostanza:** Slide della conferenza di Pierre Marquis (Univ. Artois, CNRS, CRIL; IUF), Le Croisic, giugno 2024. Introduzione alla XAI: limiti del ML (black box, garbage-in/garbage-out, mancanza di common sense), casi di AI "andata male" (Watson Health, PredPol, COMPAS), spiegazioni globali vs locali, feature importance (LIME, Anchor, saliency maps), e Formal XAI basata su knowledge compilation: alberi di decisione come circuiti, spiegazioni abduttive/contrastive, sufficient reason, interpretabilità computazionale, chair EXPEKCTATION e tool PyXAI.
- **keyword/entità:** XAI · Pierre Marquis · CNRS · CRIL · knowledge compilation · decision trees · LIME · Anchor · abductive/contrastive explanation · sufficient reason · COMPAS · EXPEKCTATION · PyXAI

### enterprise-solutions · GitHub Topics
- **source_id:** 1665e357 · **tipo:** url
- **sostanza:** Pagina GitHub Topics filtrata per linguaggio Python sul tag "enterprise-solutions" (23 repo Python su 124 totali). Elenca repository per soluzioni enterprise AI: workshop AI-apps (Mastery-AI-Apps-Dev), agenti SQL schema-aware con RBAC/RLS, RAG enterprise (MQNotebook, Synapse, blue di megagonlabs), orchestratori multi-agente (ForgeFlow con LangGraph/MCP), infra Terraform per agenti AI. Pagina indice senza contenuto tematico unitario oltre al tag.
- **keyword/entità:** GitHub Topics · enterprise-solutions · Python · agentic RAG · multi-agent · LangGraph · MCP · RBAC · LLM enterprise

### green-dalii/obsidian-llm-wiki — GitHub
- **source_id:** 119e6df2 · **tipo:** url
- **sostanza:** README del plugin Obsidian "Karpathy LLM Wiki Plugin" di green-dalii: knowledge base strutturata AI-powered che ingerisce le note e genera una wiki connessa con pagine entity/concept e query conversazionale, basata sul gist di Karpathy. Punteggio ufficiale Obsidian 95/100, supporto nativo a 8 lingue, manutenzione attiva. Multi-page knowledge generation.
- **keyword/entità:** green-dalii · obsidian-llm-wiki · Karpathy · Obsidian plugin · entity/concept pages · conversational query · multilingua · 95/100

### introduzione — AI e diagnostica medica (tesi PDF)
- **source_id:** 0dff443c · **tipo:** pdf
- **sostanza:** Tesi in italiano (PDF ~416K caratteri) su "L'intelligenza artificiale e la diagnostica medica: premesse di ordine tecnico ed etico". L'indice copre: definizione di IA per le istituzioni europee, branche dell'IA, sistemi simbolici/esperti (MYCIN come sistema esperto diagnostico per eccellenza), sistemi connessionisti e machine learning (Watson for Oncology: architettura e funzionamento), differenza tra sistema esperto e rete neurale, aggiornamento dei sistemi IA, ed etica dell'IA (robot, bot, prospettiva etica uomo-IA).
- **keyword/entità:** IA · diagnostica medica · sistemi esperti · MYCIN · sistemi connessionisti · Watson for Oncology · reti neurali · etica IA · tesi

### jyyang621/DailyArXiv — GitHub
- **source_id:** 8b66abc7 · **tipo:** url
- **sostanza:** Repository GitHub DailyArXiv (jyyang621, fork di zezhishao/DailyArXiv): aggregatore che aggiorna automaticamente paper arXiv tramite main.py/utils.py e li raccoglie in README. Il dump (~494K caratteri) contiene liste di paper arXiv recenti per keyword/filtri tematici, aggiornati quotidianamente.
- **keyword/entità:** DailyArXiv · jyyang621 · zezhishao · arXiv · paper aggregator · automazione · GitHub Actions

### kytmanov/obsidian-llm-wiki-local — GitHub
- **source_id:** 19566a52 · **tipo:** url
- **sostanza:** README di obsidian-llm-wiki-local (kytmanov, MIT): implementazione di Karpathy's LLM Wiki 100% locale con Ollama (anche endpoint OpenAI-compatibili: Groq, Together, LM Studio, vLLM, Azure). Si rilascia un file markdown in una cartella, la pipeline estrae concetti e crea/aggiorna articoli wiki interlinkati; il feedback umano (reject + motivazione) migliora la compilazione successiva. Ora in maintenance mode, con percorso di migrazione al successore Synto.
- **keyword/entità:** kytmanov · obsidian-llm-wiki-local · Karpathy · Ollama · local-first · OpenAI-compatible · feedback loop · Synto · MIT

### praneybehl/llm-wiki-plugin — GitHub
- **source_id:** a258dd60 · **tipo:** url
- **sostanza:** README di llm-wiki-plugin (praneybehl, MIT, 43 stelle): il pattern LLM Wiki di Karpathy come plugin Claude Code, progettato per scalare a migliaia di pagine senza diventare un context bottleneck. Pacchettizza skill + comandi slash (/wiki:init, ingest, query, lint, stats, graph, upgrade) e script Python stdlib (BM25, lint, stats, layer grafo opzionale con SQLite/GraphML). Architettura a 3 layer (raw/wiki/schema) + 3 operazioni; scaling via pagine atomiche (cap 400/800 righe), indici shardati, frontmatter YAML, edit chirurgici str_replace. Compatibile con Codex, Cursor, Pi via agentskills.io.
- **keyword/entità:** praneybehl · llm-wiki-plugin · Karpathy · Claude Code · slash commands · BM25 · graph layer · scaling · atomic pages · sharded index · agentskills.io · MIT

### rag-alternative · GitHub Topics
- **source_id:** 186ada80 · **tipo:** url
- **sostanza:** Pagina GitHub Topics "rag-alternative" (60 repository, ordine per stelle). Elenca i principali progetti alternativi a RAG: Astro-Han/karpathy-llm-wiki (936★), kytmanov/obsidian-llm-wiki-local (670★), axoviq-ai/synthadoc (300★), AyanbekDos/memoriki (105★), knolo-core (knowledge base deterministica per SLM, no embeddings), nub (compressione testo), sp-context (Git+BM25), e vari memory engine brain-inspired (TLCM, SCE, hce). Tema unitario: knowledge compilation / memoria persistente senza vector DB.
- **keyword/entità:** GitHub Topics · rag-alternative · karpathy-llm-wiki · synthadoc · memoriki · knolo-core · BM25 · no vector DB · LLM wiki · agent memory

### synthadoc/docs/design.md — GitHub
- **source_id:** b1e86d01 · **tipo:** url
- **sostanza:** Documento di design di Synthadoc v0.5.0 (rilasciato 2026-05-21; owner Paul Chen, William Johnason). Spiega in dettaglio l'architettura del motore di knowledge compilation: Overview, Core Concepts, System Architecture, Agents, Skills System, Storage, HTTP API, Obsidian Plugin, CLI, Configuration, Hook System, Cache System, Cost Guard, Job Queue, Observability/Logging. Rivolto a utenti e sviluppatori che aggiungono feature, skill e plugin.
- **keyword/entità:** Synthadoc · design doc · v0.5.0 · Paul Chen · agents · skills system · HTTP API · Obsidian plugin · CLI · hook · cache · cost guard · job queue

### synthadoc/docs/user-quick-start-guide.md — GitHub
- **source_id:** e5b234c3 · **tipo:** url
- **sostanza:** Guida rapida utente del repo axoviq-ai/synthadoc (Public, 300 stelle, 35 fork). Pagina GitHub del file docs/user-quick-start-guide.md del progetto Synthadoc, motore open-source di knowledge compilation che trasforma documenti raw in wiki strutturate local-first come alternativa trasparente al RAG. Contenuto orientato all'onboarding rapido (installazione e primo uso).
- **keyword/entità:** Synthadoc · axoviq-ai · quick start · knowledge compilation · local-first · RAG alternative · onboarding · GitHub

### wiki · GitHub Topics
- **source_id:** 3e62c2fd · **tipo:** url
- **sostanza:** Pagina GitHub Topics "wiki" (4.587 repository, ordine recently-updated). Definisce il concetto di wiki (popolarizzato da Wikipedia, MediaWiki) ed elenca repo eterogenei, molti dei quali implementazioni LLM Wiki di Karpathy per agenti AI: lorekit, ai-longterm-wiki-memory-OpenClaw, yopedia ("wiki per umani e agenti"), noosphere (memory/wiki layer per agenti), ctx (grafo LLM-wiki da 102K nodi), llm_wiki_agent, OmegaWiki, oltre a docmost e altri wiki tradizionali.
- **keyword/entità:** GitHub Topics · wiki · MediaWiki · Wikipedia · LLM Wiki · Karpathy · knowledge base · ai-agent · yopedia · noosphere · docmost

### I.M.P.A.K.T. — SisInfLab (logic-based HR skill matching)
- **source_id:** (letto in sessione precedente) · **tipo:** url
- **sostanza:** Sistema I.M.P.A.K.T. del SisInfLab (Politecnico di Bari) per il matching di competenze HR tramite knowledge compilation su DB relazionale. Usa logica formale per mappare skill di candidati a requisiti di job description, compilando la conoscenza in strutture relazionali interrogabili.
- **keyword/entità:** I.M.P.A.K.T. · SisInfLab · Politecnico Bari · HR · skill matching · knowledge compilation · logica formale · database relazionale

### Memoriki — LLM Wiki + MemPalace (MCP server)
- **source_id:** (letto in sessione precedente) · **tipo:** url
- **sostanza:** Progetto Memoriki: MCP server che combina LLM Wiki con MemPalace per la ricerca semantica e il grafo di entità. Permette agli agenti AI di accedere a una wiki strutturata con ricerca ibrida BM25+vettoriale e navigazione del grafo di entità.
- **keyword/entità:** Memoriki · LLM Wiki · MemPalace · MCP server · ricerca semantica · entity graph · BM25 · vettoriale

### LLM Wiki v2 — rohitg00 (GitHub)
- **source_id:** (letto in sessione precedente) · **tipo:** url
- **sostanza:** Repository GitHub rohitg00/llm-wiki che estende il pattern Karpathy con: lifecycle management, confidence scoring, supersession di voci obsolete, ricerca ibrida BM25+vettoriale+grafo. Aggiunge robustezza e gestione del ciclo di vita delle voci wiki.
- **keyword/entità:** LLM Wiki v2 · rohitg00 · GitHub · lifecycle · confidence scoring · supersession · BM25 · vettoriale · grafo

### PROTEAN — Stanford 1987 (protein structure / blackboard)
- **source_id:** (letto in sessione precedente) · **tipo:** text
- **sostanza:** Documento sul sistema PROTEAN sviluppato a Stanford nel 1987 per la determinazione della struttura proteica tramite architettura blackboard (BBl). Sistema a 3 fasi di compilazione strategica della conoscenza: pianificazione, esecuzione, valutazione. Uno dei primi esempi di knowledge compilation sistematica.
- **keyword/entità:** PROTEAN · Stanford · 1987 · protein structure · blackboard · BBl · knowledge compilation · sistemi esperti · 3-phase

---

## b152146c · Sbroglio chat — catalogazione NotebookLM — [meta] · 5 fonti

> Le 5 fonti sono **screenshot PNG** di una stessa chat claude.ai (id `b7ced362-4344-4ba3-bae2-a2b9fadaed3b`,
> catturata 2026-05-31), divisa in 5 parti. `source_get_content` su immagini restituisce solo l'URL
> dell'immagine (nessun testo estraibile via OCR): la sostanza non è verificabile dal contenuto testuale,
> solo dalla provenienza dichiarata (chat di catalogazione NotebookLM, "sbroglio" delle chat).

### AwesomeScreenshot … 2026-05-31_5_53_part1.png → part5.png
- **source_id:** 653390c4 (p1) · 48aa28e4 (p2) · 89090435 (p3) · acb2a277 (p4) · 25e1a2b0 (p5) · **tipo:** image (PNG)
- **sostanza:** Cinque ritagli sequenziali (part1–part5) di una singola conversazione claude.ai del
  31 mag 2026 dedicata allo "sbroglio"/catalogazione dei notebook NotebookLM. Contenuto testuale non
  estraibile dal gateway (le immagini tornano come URL googleusercontent); voce basata sulla provenienza verificata, non sul testo.
- **keyword/entità:** screenshot claude.ai · chat b7ced362 · catalogazione NotebookLM · sbroglio chat · 5 parti

---

## ba098eec · mcp1777 — Mappa del progetto — [mcp] · 9 fonti

### 00 — Spirito e contesto OSS1777 (chi, cosa, metodo)
- **source_id:** 5a69dd14 · **tipo:** text
- **sostanza:** Kickoff prompt condiviso con NB Lavoro vivo (2K). Identità Neo (IT senior, handle neo1777), cos'è OSS1777 (graphify, arco issue #919→PR#942→ondata 2). Metodo non negoziabile: verifica vera, fatti vs inferenze, no sycophancy, accountability. Mood 360°.
- **keyword/entità:** OSS1777 · graphify · neo1777 · PR#942 · metodo · kickoff

### 01 — Overview: tre superfici, MCP condivisi
- **source_id:** fa524e80 · **tipo:** text
- **sostanza:** Architettura a tre superfici che condividono lo stesso backend MCP (3K): Bot Telegram (@notebookllm1777_bot, claude -p, zero costo API), Claude Code (stdio locale, full read-write), Claude web (connettori cloudflared trycloudflare.com). Account NotebookLM: antigravity1777@gmail.com.
- **keyword/entità:** tre superfici · claude -p · cloudflared · trycloudflare · antigravity1777 · stdio

### 02 — Mappa dei moduli (baseline da rifare)
- **source_id:** 6f41cc95 · **tipo:** text
- **sostanza:** Descrizione modulo per modulo della baseline esistente (5K): telegram-bridge (bot1, sessioni per chat_id), telegram-mcp (FastMCP, workspace_*, HTTP port 8001, fix DNS-rebinding), telegram-frontend (bot2 sociale, HITL requests.jsonl), bot2 (GDR, login a stati), gateway (default-deny), ops/squid, ops/systemd, agenti (5 ruoli + watcher.py).
- **keyword/entità:** telegram-bridge · FastMCP · workspace_* · gateway · squid · systemd · 5 agenti

### 02b — Mappa dei moduli (stato VERIFICATO 2026-05-31) — supera la baseline
- **source_id:** c5c25a5a · **tipo:** text
- **sostanza:** Albero verificato live del repo (2K): bot.py 8.6KB, gateway.py 7.8KB FULL_ACCESS=True, server.py Telegram-MCP 10.8KB, archive-mcp NUOVO (server.py 11KB, index_build.py 7.4KB, archive.db ~126MB 821 conv). Dashboard fuori dal repo in ~/.local/share/mcp1777/.
- **keyword/entità:** archive-mcp · archive.db · FULL_ACCESS · dashboard · repo verificato · 2026-05-31

### 03 — Le quattro fasi del piano di sicurezza
- **source_id:** 2a0be81d · **tipo:** text
- **sostanza:** Scaletta delle 4 fasi di sicurezza (4K): Fase 1 base (infra + bot + MCP), Fase 2 gateway default-deny (allowlist lettura, NotebookLM read-only pubblicamente), Fase 3 Squid egress firewall (allowlist domini, no MITM), Fase 4 frontend bot sociale (privilegi quasi-zero, HITL). Ordine consigliato: 1→3→2→4.
- **keyword/entità:** gateway default-deny · Squid · egress firewall · HITL · 4 fasi sicurezza

### 04 — Modello di sicurezza e perimetro
- **source_id:** 01ca57a9 · **tipo:** text
- **sostanza:** Modello di sicurezza dettagliato (4K): ALLOWED_USER_IDS stretta, DISALLOWED_TOOLS (Supabase, GitHub write, Drive, Calendar, Notion, Gmail write), blocco Bash/Write/WebFetch/WebSearch dal bot. Vettore esfiltrazione esplicitamente chiuso. workspace_* confinati. Verdetto 5/5: filesystem autoritativo su NotebookLM per agenti.
- **keyword/entità:** ALLOWED_USER_IDS · DISALLOWED_TOOLS · WebFetch · esfiltrazione · vettore · workspace_*

### 05 — Catalogo del server MCP NotebookLM
- **source_id:** 4f9b52d1 · **tipo:** text
- **sostanza:** Riferimento completo dei tool mcp__notebooklm-mcp__* (5K): gestione notebook, source_add (text/file/url/drive), note (create/list/update/delete), notebook_query, cross_notebook_query, studio_create (audio/video/infographic/slides), label/tag, sharing, auth (nlm login/refresh_auth), pipeline/batch.
- **keyword/entità:** source_add · notebook_query · cross_notebook_query · studio_create · nlm login · catalogo MCP

### 06 — INDICE delle fonti (bussola per PROMPT2) — agg. 2026-05-31
- **source_id:** f64b1ab9 · **tipo:** text
- **sostanza:** Mappa "dove sta cosa" nei 3 NB del cluster mcp1777 (2K): NB Lavoro vivo = diario (00-07 + TICK), NB Mappa = indice (00-06), NB dashboard+Kilo = deposito file codice. Materiale locale prodotto da PROMPT1 in mcp1777/plan_migration/. Prossimo: PROMPT2 assembla pacchetto Telegram.
- **keyword/entità:** cluster mcp1777 · plan_migration/ · bussola PROMPT2 · indice · dashboard+Kilo

### 07 — Pacchetto installabile (systemd) — agg. 2026-05-31
- **source_id:** 826d9482 · **tipo:** text
- **sostanza:** Esito di PROMPT2 (1K): modulo pacchetto-mcp1777/ creato. install.sh (DRY-RUN, idempotente, 11/11 deps OK), start-stack.sh/stop-stack.sh, mcp1777.service (Restart=on-failure), health-check.sh (5 porte + bot). Aperto: Flutter dashboard N1777, named tunnel, frontend bot, lancio reale install.
- **keyword/entità:** pacchetto-mcp1777 · install.sh · mcp1777.service · health-check.sh · Flutter N1777

---

## NB2 — BOOK_GAME1777 (bce2ae58)

### METHODOLOGY_Audit_BOOK_GAME1777.md
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Audit metodologico di un libro AAA game dev in 81+ capitoli. Rating complessivo 6.8/10. Definisce roadmap in 7 fasi (A–G) per miglioramento: struttura narrativa, esempi pratici, integrazione Unity/Unreal, casi studio reali, esercizi, appendici tecniche.
- **keyword/entità:** BOOK_GAME1777 · 81-capitoli · audit · 6.8/10 · roadmap · AAA-game-dev

### NEXUS_Simulator_Dev_Log.txt
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Dev log del simulatore "Protocol Nexus Safety-Critical" sviluppato con Gemini Spark. Documenta 7 scenari HRO (High-Reliability Organization): aviation, nuclear, medical, rail, chemical, maritime, space. Ogni scenario ha parametri di fault injection e metriche di affidabilità.
- **keyword/entità:** Protocol-Nexus · HRO · safety-critical · Gemini-Spark · fault-injection · 7-scenari

### ONTOLOGY_Method_Framework.md
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Framework completo del Metodo Ontologico NotebookLM: ciclo ricerca in 4 passi, framework VEP (Validità-Evidenza-Pertinenza), Regime A (esplorazione) e Regime B (consolidamento). Definisce come usare NotebookLM come strumento epistemologico strutturato per ricerca profonda.
- **keyword/entità:** Metodo-Ontologico · VEP · Regime-A · Regime-B · 4-step · NotebookLM · epistemologia

### ONTOLOGY_NotebookLM_Operational_Guide.md
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Guida operativa per l'uso del Metodo Ontologico in NotebookLM nell'ambito del progetto OSS1777. Descrive procedure concrete per ciclo VEP, gestione delle fonti, creazione annotazioni strutturate, e integrazione con il workflow di contribuzione OSS.
- **keyword/entità:** guida-operativa · OSS1777 · VEP · annotazioni · workflow · NotebookLM

### INFRA_Claude_Code_Token.txt
- **source_id:** ebf41ccf · **tipo:** text
- **sostanza:** File infrastrutturale contenente una credenziale OAuth di Claude Code (token `sk-ant-oat01-...`). Documento di tipo infrastrutturale/segreto, non contiene contenuto narrativo. Il valore del token non viene riprodotto per sicurezza.
- **keyword/entità:** infrastruttura · credenziale · OAuth · Claude-Code · token · [REDACTED]

### Capitoli book (struttura)
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Struttura dettagliata dei capitoli del libro BOOK_GAME1777: organizzazione per sezioni tematiche (fondamentali, gameplay, grafica, audio, networking, monetizzazione, publishing). Include outline per ogni capitolo con obiettivi di apprendimento.
- **keyword/entità:** capitoli · struttura · gameplay · grafica · audio · networking · publishing

### Revisione narrativa libro
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Documento di revisione narrativa che analizza il flusso dei contenuti tra capitoli, individua gap tematici, suggerisce riorganizzazione per migliorare la progressione didattica del libro AAA.
- **keyword/entità:** revisione · narrativa · gap · progressione · didattica

### Casi studio AAA
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Raccolta di casi studio da titoli AAA reali (non specificati per NDA): analisi delle decisioni di design, problemi di scaling, scelte tecnologiche, lezioni apprese. Materiale di supporto per i capitoli del libro.
- **keyword/entità:** casi-studio · AAA · design · scaling · NDA · lezioni

### Esercizi pratici
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Set di esercizi pratici per ogni sezione del libro: implementazioni Unity/Unreal, mini-progetti, challenge di ottimizzazione. Progettati per consolidare i concetti teorici con pratica hands-on.
- **keyword/entità:** esercizi · Unity · Unreal · hands-on · ottimizzazione · mini-progetti

### Appendici tecniche
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Appendici di riferimento tecnico: shader cheat sheet, profiling guide, versione minima engine/API, glossario terminologia AAA, link a risorse esterne aggiornate.
- **keyword/entità:** appendici · shader · profiling · glossario · AAA · engine

### Feedback alpha readers
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Raccolta feedback da lettori alpha del libro: punti di forza (profondità tecnica, esempi concreti), punti deboli (troppo denso in alcuni capitoli, mancanza di immagini/diagrammi), suggerimenti prioritari.
- **keyword/entità:** alpha-readers · feedback · profondità · diagrammi · suggerimenti

### Piano pubblicazione
- **source_id:** (da sessione precedente) · **tipo:** text
- **sostanza:** Piano editoriale per la pubblicazione di BOOK_GAME1777: timeline milestone, scelta piattaforma (Amazon KDP / Leanpub), strategia marketing, pricing, ISBN, versione PDF e ePub.
- **keyword/entità:** pubblicazione · KDP · Leanpub · marketing · ISBN · ePub · pricing

---

## c59171c2 · Architecting Knowledge: The Ontological Method for NotebookLM — [metodo] · 2 fonti

### chat_mappa_metodo.md
- **source_id:** b44d4950-5181-4c10-86ed-6eee22e2229c · **tipo:** text (export chat NotebookLM, ~152k char)
- **sostanza:** Export di una chat NotebookLM (8 fonti, 23 mag 2026) sul "Metodo Ontologico":
  framework professionale di Architettura della Conoscenza che trasforma masse disordinate di
  documenti ("caos organizzato") in infrastrutture di valore. Tratta il Virgin Entry Prompt
  (categorizzare i file per funzione logica: motori/bussole/prodotti), le fasi ricognizione→audit→
  riparazione workflow, l'AI come "auditor di verità", e la distinzione Regime A (produzione di
  conoscenza) vs Regime B (riassunto). Chiusura operativa via PIANO_kit, PR, articolo Medium.
- **keyword/entità:** Metodo Ontologico · Virgin Entry Prompt · Regime A/B · auditor di verità ·
  ricognizione ontologica · PIANO_kit · Ondata 2 graphify · densità semantica · $15.000

### chat_notebookllm_guida_tecnica.md
- **source_id:** 60300b94-d668-4fcc-b6dd-4db8191255f4 · **tipo:** text (export sessione NotebookLM, ~49k char)
- **sostanza:** Export di una sessione NotebookLM che mescola l'onboarding/UX dello strumento
  (pannello fonti, fast/deep research, Studio: Audio Overview, mappe mentali, quiz, infografiche,
  flashcard) con il tema tecnico dell'Ondata 2 di graphify (prossimo obiettivo tecnico, "tappare
  sintomo vs risolvere causa", come contribuire all'open source). Genera la guida procedurale
  "Dalla Massa Disordinata alla Struttura" sul Metodo Ontologico.
- **keyword/entità:** NotebookLM Studio · Audio Overview · deep research · Ondata 2 · sintomo vs causa ·
  guida procedurale · flashcard regole d'oro · onboarding fonti

---

## NB6 — OSS1777 roadmap (c9b7436a)

### Allow logging output — PROMPT_ondata2_definitivo.md
- **source_id:** 5c418bc0 · **tipo:** text
- **sostanza:** Prompt operativo compilato (365k chars) per la seconda ondata di contribuzioni PR a graphify. Definisce una procedura in 6 fasi "test-before-write": analisi issue, lettura codebase, test esistenti, implementazione, test nuovi, PR. Include la BASE_CONOSCENZA completa e la strategia di implementazione per `edge-weight-mode`, super-hub clustering, e normalizzazione pesi. Mappa di tutti i file rilevanti del repo.
- **keyword/entità:** PROMPT_ondata2 · PR · test-before-write · 6-fasi · edge-weight-mode · super-hub · BASE_CONOSCENZA · graphify

### schermata chat 1
- **source_id:** 3f01d539 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 2
- **source_id:** 587eadd3 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 3
- **source_id:** e9ca7a05 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 4
- **source_id:** 6d75f81f · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 5
- **source_id:** 0351bda6 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 6
- **source_id:** 0a32c469 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 7
- **source_id:** 17205b91 · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

### schermata chat 8
- **source_id:** 08c0c45e · **tipo:** image
- **sostanza:** Screenshot della sessione di lavoro OSS1777. Provenienza: googleusercontent. Documenta visivamente una fase del processo di contribuzione OSS.
- **keyword/entità:** screenshot · OSS1777 · contribuzione · PR

---

## c9deb55b · The Perplexity Pro Research Template: Professional Edition — [metodo] · 17 fonti

---

### 07_template_pro_IT.md
- **source_id:** efcf64ae-d2c9-4191-b597-6b05312ab462 · **tipo:** unknown
- **sostanza:** Template professionale per Perplexity Pro in italiano, structured prompt per ricerche approfondite con output formattati, sezioni dedicate a framing, contesto, deliverable e parametri di qualità.
- **keyword/entità:** Perplexity Pro · template di ricerca · prompt engineering · ricerca professionale · output strutturato

---

### Chat Claude — risoluzione issue Graphify (briefing) [copia 3]
- **source_id:** 5b6ce4e1-ebf9-4049-b385-33655280b4b1 · **tipo:** unknown
- **sostanza:** Trascrizione di sessione Claude sul progetto open-source Graphify: analisi del repository, strategia per apertura issue (#919) con tre opzioni ranked per super-hub, contributo PR #942 e gestione del feedback del maintainer.
- **keyword/entità:** graphify · issue #919 · PR #942 · super-hub · Saif · open-source · marzio1777

---

### I Spent $60 on Perplexity Pro. The Output Would Have Cost Me $15,000+ from Consultants (Medium PDF)
- **source_id:** 72fa8256-0452-47ee-ba85-fce5d49ed482 · **tipo:** unknown
- **sostanza:** Articolo Medium (PDF) che documenta un workflow reale con Perplexity Pro: l'autore ha ottenuto output paragonabili a consulenze da $15k+ spendendo $60, con dettagli su prompt, fonti e struttura delle ricerche.
- **keyword/entità:** Perplexity Pro · ROI · consulenza · workflow AI · ricerca strutturata · $60 · $15k

---

### Mappa id - lista di (neighborid, edgedata)
- **source_id:** 8bd4b2c8-f624-4e08-bb63-0e2b73ec7de1 · **tipo:** unknown
- **sostanza:** Dataset JSON di grandi dimensioni (889k caratteri) contenente una mappa di adiacenza del grafo Graphify: ogni nodo con lista di neighbor ID e dati degli archi (peso, tipo), generato dall'analisi di marzio1777.
- **keyword/entità:** grafo · adiacenza · edge data · neighbor · Graphify · marzio1777 · JSON

---

### Mappa id - lista di (neighborid, edgedata) [duplicato]
- **source_id:** bd645b0a-269a-46df-aa7e-d4527abfc9ee · **tipo:** unknown
- **sostanza:** Copia identica del dataset JSON della mappa di adiacenza Graphify (889k caratteri); probabile duplicato della source 8bd4b2c8, stesso contenuto strutturale.
- **keyword/entità:** grafo · adiacenza · Graphify · duplicato · edge data

---

### Panoramica completa di registratori vocali continui hardware, software, AI, privacy e form factor (2026).md
- **source_id:** e563dd99-dcda-43f4-8de7-645220585699 · **tipo:** unknown
- **sostanza:** Report 2026 sui registratori vocali continui: confronto tra soluzioni hardware (wearable, USB), software (app mobile, desktop), piattaforme AI (Otter, Fireflies, Plaud) con analisi di privacy, battery life e form factor.
- **keyword/entità:** registratori vocali · wearable · AI trascrizione · privacy · Otter · Fireflies · Plaud · 2026

---

### Sto cercando informazioni accurate e aggiornate su(1).md
- **source_id:** 7e9626ed-b01f-45ab-9f3c-c8b112477ca9 · **tipo:** unknown
- **sostanza:** Ricerca approfondita su Claude Projects: funzionamento della knowledge base, RAG, memoria persistente, gestione del contesto e istruzioni personalizzate per progetti a lungo termine.
- **keyword/entità:** Claude Projects · knowledge base · RAG · memoria · contesto persistente · istruzioni

---

### Sto cercando informazioni accurate e aggiornate su.md
- **source_id:** 71250d85-52b1-4244-a82f-0e80350ae231 · **tipo:** unknown
- **sostanza:** Ricerca su Claude Agent Skills (SKILL.md): struttura del file di skill, invocazione, parametri, esempi pratici e integrazione con Claude Code per workflow automatizzati.
- **keyword/entità:** Claude Agent Skills · SKILL.md · skill invocation · Claude Code · workflow

---

### Technical Specification — Dart Repo-Level Coding Agent
- **source_id:** ea8aa4a0-b552-48ea-b054-daca1bf9c3dc · **tipo:** unknown
- **sostanza:** Specifica tecnica per un agente di coding repo-level scritto in Dart con UI Flutter minimale: architettura clean-room ispirata a Claude Code, sei sottosistemi (agent_core, tools, runtime, policy, cli, ui), modello event-sourced, gate di approvazione per azioni rischiose, tre fasi di rilascio.
- **keyword/entità:** Dart · Flutter · repo-level agent · Claude Code · clean-room · event sourcing · tool registry · approvazione · claw-code · claurst

---

### Verso una peer review per articoli tecnici AI e workflow
- **source_id:** de608cfd-390d-450a-9536-75cf21672335 · **tipo:** unknown
- **sostanza:** Report accademico su modelli di peer review per articoli tecnici AI/workflow: analisi di overlay journal, open peer review, F1000, rOpenSci, requisiti per una piattaforma verticale con score multi-dimensionale, ruoli autore/revisore/editor e roadmap MVP.
- **keyword/entità:** peer review · overlay journal · open peer review · F1000 · rOpenSci · articoli tecnici · AI workflow · score · reputazione

---

### dart-agent-technical-spec.md
- **source_id:** b5addc8d-a5a0-4a29-b102-37965d79d83d · **tipo:** unknown
- **sostanza:** Specifica tecnica alternativa (con [cite:] inline) per lo stesso agente Dart repo-level: struttura identica alla ea8aa4a0 ma con sistema di citazioni bibliografiche aggiunto, probabilmente versione aggiornata o derivata.
- **keyword/entità:** Dart · agente · repo-level · citazioni · Claude Code · Flutter · versione annotata

---

### prompt-definitivo-v5_2.md
- **source_id:** 5e399ada-3f0d-49ce-98db-e2e856bb1470 · **tipo:** unknown
- **sostanza:** Prompt multi-step definitivo v5.2 per analisi di corpus con estrazione liste: tre principi (raw verbatim, ricorsività, stratigrafia), quattro step (inventario, liste, comandi bash, dossier), regole di verifica ESEGUITA e artefatti da consegnare.
- **keyword/entità:** prompt engineering · lista raw · lista embedding · lista google search · corpus analysis · stratigrafia · ricorsività · bash · v5.2

---

### source: claude-share (5de4b130)
- **source_id:** 5de4b130-19f5-4da3-b8a0-a4d024e9e7f6 · **tipo:** unknown
- **sostanza:** Sessione Claude condivisa (url: claude.ai/share/f71a4cc9): conversazione su issue Graphify, strategia per contributo open source su graphify, gestione di issue #919 e #934, briefing su PR #942 e importanza del track record per open-source.
- **keyword/entità:** Graphify · issue #919 · PR #942 · open source · track record · neo1777 · marzio1777

---

### source: claude-share (9e28e14a) — Project OSS1777 Esplorativo v1
- **source_id:** 9e28e14a-3a1e-423f-92b4-4db63b6493dd · **tipo:** unknown
- **sostanza:** Sessione esplorativa del Project OSS1777 (url: claude.ai/share/281040b5): mappa del materiale Graphify, arco #919→#934→#942, stato attuale con ondata 2 (--edge-weight-mode), buchi nel knowledge (cluster.py mancante, SKILL.md spiegazione-tecnica), analisi semi-doppioni e stratigrafia.
- **keyword/entità:** OSS1777 · Graphify · cluster.py · --edge-weight-mode · ondata 2 · SKILL.md · mappa del progetto · neo1777

---

### source: claude-share (f48ea3b8) — Project OSS1777 Esplorativo v2
- **source_id:** f48ea3b8-d1e2-4879-9993-0eee0cacb3b4 · **tipo:** unknown
- **sostanza:** Seconda sessione esplorativa OSS1777 (url: claude.ai/share/281040b5, stessa share): rilancio del prompt esplorativo con lettura integrale delle trascrizioni, mappa v2 con fatti verificati (graphifyy/graphify naming, stato PR #942), evoluzione del PROMPT_esplorativo.md con fix anti-saturazione.
- **keyword/entità:** OSS1777 · mappa v2 · PROMPT_esplorativo · lettura integrale · graphifyy · PR #942 · anti-saturazione · Arco B

---

### source: claude-share (fa283d31) — OSS1777 Esplorativo + PROMPT skill
- **source_id:** fa283d31-4acf-4bf5-be3c-77f674eae7de · **tipo:** unknown
- **sostanza:** Sessione OSS1777 (url: claude.ai/share/5979d4a9): prima chat esplorativa del project, mappatura completa del materiale Graphify, verifica PROMPT_skill.md, aggiornamento con riferimento alla mappa, discussione sull'ordine di allegare la mappa alla chat gemella, decisione di non darla a priori per preservare il blind.
- **keyword/entità:** OSS1777 · PROMPT_skill · mappa · blind · chat gemella · spiegazione-tecnica · marketing skill · neo1777

---

### web2md1777_v2_fase2_prompt.md
- **source_id:** 10f8dfdb-08fa-43cb-a52a-11468d78a3bd · **tipo:** unknown
- **sostanza:** Master prompt per lo sviluppo di Web2MD1777 v2 Fase 2: aggiunge GistAdapter, HNAdapter, RedditAdapter all'architettura esistente con API pubbliche (GitHub REST, HN Firebase, Reddit .json), design decisions per registry, concorrenza BFS, messaggi italiani verbatim, checkpoint protocol e acceptance criteria.
- **keyword/entità:** web2md1777 · GistAdapter · HNAdapter · RedditAdapter · GitHub API · Hacker News Firebase · Reddit JSON · adapter pattern · checkpoint · Phase 2

---

## cb5010d2 · Project OSS1777: mapazzone1 — [graphify] · 22 fonti

### 03_template_pro.md
- **source_id:** c34ace24 · **tipo:** text
- **sostanza:** Template EN Pro Edition per ricerca Perplexity in 8 sezioni: 3 case study, troubleshooting guide, advanced patterns, API config reference (POST api.perplexity.ai/v1/responses, preset advanced-deep-research, max_output_tokens 128000, reasoning.effort high), cost optimization, adaptation notes. Distingue regime A (esplorazione) da regime B (produzione).
- **keyword/entità:** Perplexity API · advanced-deep-research · max_output_tokens · reasoning.effort · web_search · fetch_url · regime A/B · cost optimization

### 05_articolo_medium_IT.md
- **source_id:** 253170ae · **tipo:** text
- **sostanza:** Articolo Medium in italiano "Ho speso $60 su Perplexity Pro." Descrive un workflow in 4 step (pass esplorativo → audit metodico → identificazione gap → closing research) e 6 principi epistemologici: framing neutro, citazioni primarie obbligatorie, sezione "emerging patterns", disclaimer come marcatori di onestà, audit categorizzato 1-5, disciplina anti-derubricazione. Dati: ~140k parole, ~330 H2, ~1100 H3, ~80 finding categoria 5.
- **keyword/entità:** Perplexity Pro · workflow 4 step · audit · framing neutro · anti-derubricazione · disciplina epistemologica · categoria 5

### 07_template_pro_IT.md
- **source_id:** 1524381c · **tipo:** text
- **sostanza:** Traduzione italiana del template Pro Edition (03_template_pro.md). Struttura identica: 8 sezioni, stessa configurazione API, stesse istruzioni. Serve come artefatto operativo per utenti italiani del flusso Perplexity.
- **keyword/entità:** Perplexity · template italiano · Pro Edition · API config · regime A/B · artefatto operativo

### Chat — preparare PDF/Doc con immagini per NotebookLM
- **source_id:** 2f4ee936 · **tipo:** text
- **sostanza:** Trascrizione di chat che spiega come preparare documenti con immagine + descrizione per NotebookLM. Contiene trascrizione di un meme "OSS Read Games" parodia di Squid Game con 4 pannelli: luce verde=leggi il codice, luce rossa=ban; regola=chi non legge viene eliminato; scegli il tuo issue; solo chi legge sopravvive.
- **keyword/entità:** NotebookLM · immagini per NLM · OSS Read Games · Squid Game parody · meme · preparazione documento

### I Spent $60 on Perplexity Pro... Medium.pdf
- **source_id:** 834ce5c7 · **tipo:** pdf
- **sostanza:** PDF dell'articolo Medium pubblicato in inglese da Neo1777 (4 maggio 2026). Stesso contenuto di 05_articolo_medium_IT.md ma in inglese, con immagini embed via googleusercontent. Workflow 4 step, 6 principi epistemologici, metriche ~140k parole.
- **keyword/entità:** Perplexity Pro · Medium · Neo1777 · $60 · workflow 4 step · PDF · EN

### MAPPA_OSS1777_v2.md
- **source_id:** d7eefbeb · **tipo:** text
- **sostanza:** Seconda mappa esplorativa del progetto OSS1777. Inventaria 26 file in 5 famiglie. Arco A: issue #919 (super-hub diagnosis, 3 opzioni, accettata in ~7h, v0.8.10 rilasciata) → issue #934 FileNotFoundError → PR #942 (fix mkdir one-liner, chiusa non merged, Saif reimplementò con commit 076e6b7). Arco B: metaprompt → PROMPT_MADRE → 4 artefatti. Risolve: graphifyy vs graphify naming, badge contributor (solo riconoscimento umano), telephone-game versione 0.8.5 vs 0.8.8.
- **keyword/entità:** OSS1777 · issue #919 · issue #934 · PR #942 · v0.8.10 · graphifyy naming · commit 076e6b7 · super-hub · arco A/B

### MAPPA_OSS1777_v3.md
- **source_id:** 27873feb · **tipo:** text
- **sostanza:** Terza mappa esplorativa (29 elementi). Aggiunge Arco C: valutazione skill eseguita → VALUTAZIONE_skill_OSS1777.md → skill contributo-oss costruita e installata (8 principi, 3 riferimenti) → PIANO_kit_costruzione_project_v1.md scritto ma non ancora eseguito. Include §6 indice "dove è X" con riferimenti riga per riga alle trascrizioni GEN e OP.
- **keyword/entità:** OSS1777 · arco C · skill contributo-oss · PIANO_kit · VALUTAZIONE_skill · indice dove-è-X · trascrizioni GEN/OP

### Manuale Operativo NotebookLM
- **source_id:** 30ef97a2 · **tipo:** text
- **sostanza:** Manuale operativo per uso di NotebookLM con metodo ontologico. "Virgin Entry Prompt" per assegnazione ruoli categoriali (Motore/Diario/Prodotto/Bussola/Anomalia). Adatta il metodo Perplexity 4-step a NotebookLM. Guida strumenti: Audio Overview=vibe check, Tailored Report=dossier, Slide Deck=pitch, Infografica=stratigrafia, Flashcards=estrazione skill. Checklist sanity 3 domande (Regime A/B? Skill esistente? Dignità di Prodotto?).
- **keyword/entità:** NotebookLM · metodo ontologico · Virgin Entry Prompt · Motore/Diario/Prodotto · Audio Overview · regime A/B · checklist sanity

### PROMPT_esplorativo_e_ricerca_v2.md
- **source_id:** 90e9906b · **tipo:** text
- **sostanza:** Artefatto Punto 4 (prompt-madre). Prompt per chat esplorativa OSS1777. Vincoli chiave: lettura integrale delle trascrizioni in blocchi consecutivi (mai campionamento), dichiarare cosa è stato letto e in che misura, produrre mappa navigabile .md con riferimenti precisi per query "dove è X". Aggiunge sezione COME LEGGERE per prevenire mappature-castello.
- **keyword/entità:** PROMPT_esplorativo · lettura integrale · mappa navigabile · dove-è-X · anti-campionamento · COME LEGGERE · trascrizioni

### PROMPT_skill_update.md
- **source_id:** c0a26fbb · **tipo:** text
- **sostanza:** Artefatto Punto 6. Prompt per chat di valutazione skill. Valuta quali skill sono necessarie (non le costruisce). Percorso: leggi mappa → leggi skill esistenti (spiegazione-tecnica, marketing) → leggi trascrizioni per metodi ricorrenti → applica criterio. Vincolo esplicito: nessuna skill costruita in questa chat.
- **keyword/entità:** PROMPT_skill_update · valutazione skill · spiegazione-tecnica · marketing · skill contributo-oss · criteri

### PROMPT_start_PR.md
- **source_id:** c613aec8 · **tipo:** text
- **sostanza:** Artefatto Punto 5. Prompt operativo per ondata 2 PR (--edge-weight-mode). Percorso: ricognizione 360° → focus edge-weight-mode → ricerca mirata. Fase A: verificare se graspologic leiden() accetta edge weights (attualmente cluster.py passa solo random_seed/trials/resolution, nessun argomento weight). Nessun fork/PR prima che fase A sia chiara.
- **keyword/entità:** PROMPT_start_PR · ondata 2 · edge-weight-mode · graspologic · leiden() · cluster.py · fase A · PR

### SETUP_PROJECT_oss.md
- **source_id:** 41fe271c · **tipo:** text
- **sostanza:** Documento di setup del Project OSS1777. Opzioni nome (raccomanda OSS1777). Testo descrizione e istruzioni pronti da copiare (ruolo=collaboratrice, italiano, metodo 360°→focus, verifica mai da memoria, no sycophancy, no dramatizzazione). Nucleo memoria (4 bullet). Architettura 4 parti: istruzioni, knowledge, skill come ZIP, memoria. Ordine operativo: raccogli artefatti → crea Project → carica knowledge → carica skill → apri chat.
- **keyword/entità:** OSS1777 · Project Claude.ai · setup · istruzioni · skill ZIP · knowledge · memoria · architettura

### catalogo-comandi-bash.md
- **source_id:** e0a6a4fa · **tipo:** text
- **sostanza:** Catalogo completo dei comandi bash per analisi corpus OSS1777. Preambolo con setup ROOT/LC_ALL/CORPUS/voci(). Blocco 1: lista raw (grep, frequenze, orfani, categorie, contesto esteso). Blocco 2: lista google (copertura, validazione formato, export batch). Blocco 3: lista embedding (lunghezza chunk, quasi-duplicati, conversione JSONL, raggruppamento sezioni). Blocco 4: cronologia (date filesystem+interne). Blocco 5: manutenzione lista. Finding chiave: graphify=162, PR=70, skill=64, issue=50 nel corpus; 119/325 termini raw sono orfani (by design).
- **keyword/entità:** bash · corpus OSS1777 · lista raw · lista embedding · lista google · frequenze · orfani · JSONL · cronologia

### esempio-modifiche-saif.md
- **source_id:** 322e5c58 · **tipo:** text
- **sostanza:** Spiegazione tecnica dettagliata della reimplementazione del fix #934 da parte di Saif. Modifica 1: `out.mkdir(parents=True, exist_ok=True)` spostato 17 righe sopra a riga 1811 (subito dopo definizione di `out`) — stabilisce invariante vs sintomo; garantisce coesione, robustezza, simmetria con codepath extract. Modifica 2: test di regressione 23 righe `test_cluster_only_creates_output_dir_when_missing` in test_cli_export.py usando helper `_make_graph()` e `_run()` già nel repo.
- **keyword/entità:** fix #934 · out.mkdir · parents=True · exist_ok · riga 1811 · test regressione · test_cli_export.py · _make_graph() · _run()

### lista-embedding-vettoriale.md
- **source_id:** f16d7793 · **tipo:** text
- **sostanza:** Chunk v2 per vector DB/RAG. Sezioni: problema tecnico (metriche graphify, diagnosi community 0, super-hub gravitational attraction, bug rounding fixato a HEAD), tre opzioni #919 (exclude-hubs, algorithm+resolution, edge-weight-mode non ancora implementato), fase A ondata 2 (leiden() senza weight arg), arco del contributo, qualità del fix, principi di metodo (verifica prima di modificare, misura prima di tagliare, reporting onesto), metodo di lavoro.
- **keyword/entità:** vector DB · RAG · embedding chunks · community 0 · super-hub · rounding bug · leiden() · edge-weight-mode · principi metodo

### lista-google-search.md
- **source_id:** cf3030a8 · **tipo:** text
- **sostanza:** Lista v1 di query Google per ricerca mirata. Categorie: graspologic/clustering (core fase A), graphify tool, OSS workflow, graph analysis concepts, stack marzio1777 (background), method (bassa priorità). Serve come input per ricerca pre-PR ondata 2.
- **keyword/entità:** Google search · graspologic · graphify · OSS workflow · graph analysis · query list · fase A

### lista-raw.md
- **source_id:** 2a14590b · **tipo:** text
- **sostanza:** Vocabolario verbatim completo v2. 9 categorie: A=graphify tool/graph analysis, B=clustering algorithms/librerie (tutte le funzioni cluster.py: `_partition()`, `cohesion_score()`, `score_all()`, `remap_communities_to_previous()`, `_suppress_output()`), C=diagnosi bug/rounding, D=OSS workflow, E=arco #919→#934→#942→ondata2, F=artefatti metodo, G=principi di lavoro, H=stack marzio1777, I=persone/repo.
- **keyword/entità:** lista raw · vocabolario verbatim · cluster.py · _partition() · cohesion_score() · score_all() · OSS arco · marzio1777

### prompt-definitivo-v5_2.md
- **source_id:** 1b031108 · **tipo:** text
- **sostanza:** Versione v5.2 del prompt multi-step (4 step). Concetto A: lista raw è fonte verbatim-only; lista embedding compone chunk da essa (non viceversa). Concetto B: estrazione ricorsiva (stepN.0 = rilettura critica con verifica eseguita). Concetto C: il corpus ha storia (tempo+stratigrafia). Step 1: inventario+metadati+cronologia+stratigrafia+deep reading. Step 2: tre artefatti. Step 3: catalogo bash. Step 4: dossier ragionato. Regole N1-N13.
- **keyword/entità:** prompt v5.2 · 4 step · lista raw verbatim · estrazione ricorsiva · stratigrafia corpus · regole N1-N13 · prompt-madre

### source: claude-share (Analisi grafo architetturale — sessione GENESIS)
- **source_id:** 5a020893 · **tipo:** url
- **sostanza:** Sessione GENESIS: Neo analizza marzio1777 con graphify (1501 nodi, 2200 archi, 147 comunità, 27 hyperedge). God nodes: useAuth() 42 archi, db 34, useRBAC() 32. Community 0: 86 nodi, coesione 0.05. Identificato problema gravitational attraction dei super-hub. Discussione bundle optimization (split ui/index.tsx, misurazione bundle). Decisione di aprire issue graphify in sessione dedicata.
- **keyword/entità:** graphify · marzio1777 · 1501 nodi · community 0 · super-hub · useAuth() · gravitational attraction · issue #919 · GENESIS session

### source: claude-share (Prima chat esplorativa OSS1777)
- **source_id:** 2f8341b3 · **tipo:** url
- **sostanza:** Prima chat esplorativa OSS1777. Primo pass di mappatura Claude (trovato cluster.py mancante), secondo pass integrale dopo istruzione "leggi integralmente" → produce MAPPA_OSS1777_v2. Discute PROMPT_skill update, aggiorna PROMPT_esplorativo a v2 con COME LEGGERE + fix anti-saturazione + DOPO LA MAPPA. Discussione sessione twin: non dare mappa a sessione blind in anticipo.
- **keyword/entità:** chat esplorativa · MAPPA_OSS1777_v2 · cluster.py · COME LEGGERE · sessione twin · anti-saturazione · lettura integrale

### source: claude-share (Sessione ARCHIVIO OSS1777 ricerca — twin blind)
- **source_id:** ddf91ffe · **tipo:** url
- **sostanza:** Sessione blind twin esplorativa. Usa PROMPT_esplorativo_e_ricerca_v2 aggiornato. Claude legge trascrizioni integralmente (1a completa, 2a interrotta a riga 9990), riporta onestamente cosa manca, chiede come procedere. Con istruzione procedi (a) + info coda è Arco B: completa lettura, produce MAPPA_OSS1777_v3 (nota VALUTAZIONE_skill e skill contributo-oss come aggiunte rispetto a v2).
- **keyword/entità:** sessione blind · PROMPT_esplorativo v2 · MAPPA_OSS1777_v3 · lettura integrale · riga 9990 · arco B · contributo-oss

### spiegazione_fix_saif_934.md
- **source_id:** a1f3536f · **tipo:** text
- **sostanza:** Contenuto identico a esempio-modifiche-saif.md (duplicato confermato). Stessa spiegazione tecnica della reimplementazione Saif: `out.mkdir(parents=True, exist_ok=True)` a riga 1811, test regressione 23 righe in test_cli_export.py.
- **keyword/entità:** fix #934 · out.mkdir · duplicato · spiegazione_fix_saif · test regressione · test_cli_export.py

---

## dbd1d848 · AgoraWork1777 — Project Memory — [agora] · 2 fonti

### AgoraWork1777 — Decisions & Research Brief
- **source_id:** e411cdfb-4492-4802-a8ab-d3c6a3e937b7 · **tipo:** text (brief, EN)
- **sostanza:** Project brief dell'open-core AgoraWork1777: bot Telegram + Mini-App dashboard per
  coordinamento/decisioni di team (≠ Agora1777). Decisioni d'architettura motivate: branch non è
  isolamento (privacy via cifratura app-level per-utente), Git non è un DB (memoria documentale a
  bassa frequenza), LLM-opzionale dietro adapter, tre memorie distinte. Ricerche mag 2026 (Bot API 9.4, Mini Apps, Televerse).
- **keyword/entità:** open-core · Apache 2.0 · Televerse Dart · Telegram Mini App/PWA ·
  app-level encryption · LLM-optional adapter · single-upstream governance · tre memorie

### AgoraWork1777 — Goal-prompt (full spec)
- **source_id:** 2a220e02-00de-42fe-a689-99e15ae8b795 · **tipo:** text (goal-prompt, EN)
- **sostanza:** Spec completa per /goal in Claude Code: costruire la base open-core pubblicabile nel
  repo agorawork1777. Stack Dart+Televerse, dashboard Flutter web (Mini App + PWA), memoria su repo
  GitHub privato cifrato. Bivi bloccati (single repo + namespace + encryption; LLM adapter stub),
  struttura cartelle, branding come config, criteri di accettazione e diary di processo.
- **keyword/entità:** /goal · MVP v1 · extension points · EXTENDING.md · namespace per-utente ·
  callback_data menu:... · branding parametrico · acceptance criteria

---

## e8ec06ec · mcp1777 — pacchetto Telegram: dashboard + Kilo — [mcp,telegram] · 19 fonti

---

### 00 — Dossier di compito (dal contesto claude.ai)
- **source_id:** 8dccb71b-912c-4e62-a034-074cb3a46391 · **tipo:** text
- **sostanza:** Documento di briefing creato il 31 maggio 2026 per passare il contesto da claude.ai a Claude Code: descrive lo scopo del compito (impacchettare mcp1777 in versione scoped ai soli bot Telegram con base Kilo), l'architettura a tre superfici (Telegram, Claude Code, claude.ai), i moduli già presenti al 27 maggio, e i bivi aperti da chiarire con Neo (quali bot, ruolo Kilo, stack dashboard, forma del pacchetto). Applica il "Metodo 1777": verifica sulla fonte, fatti distinti dalle inferenze.
- **keyword/entità:** mcp1777 · briefing · Kilo Code · bot Telegram · architettura · Metodo 1777 · bivi aperti

---

### 01 — Aspetto dashboard (N1777/setaccio) + delta mappa
- **source_id:** afa324de-77ec-4d9e-a353-6e4dda8c5e75 · **tipo:** text
- **sostanza:** Specifica visiva della dashboard mcp1777: design system N1777 "ottone su inchiostro" (#0E1116 fondo, #D6A24C accento unico ottone), tipografia Fraunces/Archivo/JetBrains Mono, componenti del kit "setaccio" (Btn, Pill, Stat, tabella). Target runtime: Flutter desktop+mobile. Mappa come gli allarmi, le metriche e le animazioni del percorso messaggi si traducono in componenti concreti. Aggiunge puntatori mancanti al dossier 00: masterIndex1777 e archivioClaude1777.
- **keyword/entità:** N1777 · ottone su inchiostro · Flutter · setaccio · design system · dashboard · Fraunces · JetBrains Mono

---

### ISTRUZIONI-MCP-ARCHIVE.md
- **source_id:** 5f72412f-5079-44bc-8b37-92e826c53084 · **tipo:** text
- **sostanza:** Guida completa all'installazione e uso dell'MCP "archive": indicizza 821 conversazioni dell'export Claude.ai (283 MB) in un database SQLite+FTS5 (~120 MB), espone 7 tool (archive_stats, search_conversations, list_conversations, get_conversation, get_message_context, get_memory, list_projects). Documenta come aggiungere il server via Claude Code (stdio) e come collegarlo a claude.ai via gateway+tunnel. Avverte del cambio URL trycloudflare a ogni riavvio.
- **keyword/entità:** archive-mcp · SQLite · FTS5 · 821 conversazioni · 7 tool · gateway · trycloudflare

---

### README.md
- **source_id:** 572e752e-d967-4669-836f-59fb4b42f487 · **tipo:** text
- **sostanza:** README principale del workspace mcp1777: descrive l'architettura "workspace unico" con tre superfici (bot Telegram @notebookllm1777_bot, Claude Code, claude.ai) che condividono gli stessi MCP (NotebookLM, Telegram custom, GitHub, Gmail, Drive, Calendar, Notion, Supabase, Figma). Documenta avvio/stop, comandi Telegram, tool MCP disponibili, modello di sicurezza (allowlist, DISALLOWED_TOOLS, workspace confinato) e troubleshooting.
- **keyword/entità:** workspace unico · @notebookllm1777_bot · tre superfici · MCP condivisi · allowlist · DISALLOWED_TOOLS · cloudflared

---

### TEST-PLAN.md
- **source_id:** 6ceb4218-b375-4ffa-9974-d583ca984326 · **tipo:** text
- **sostanza:** Piano di test strutturato in 3 parti per verificare il sistema: Parte 1 testa claude.ai (discovery MCP, lettura NotebookLM, invio Telegram cross-superficie); Parte 2 testa il bot Telegram (sanity, query NotebookLM, altri MCP in lettura, hardening SQL blokkato); Parte 3 dimostra il "ponte" bidirezionale via PAROLA-PONTE-4242 tra Telegram e claude.ai. Include la verifica del test di hardening (2.5: Supabase execute_sql DEVE essere rifiutato).
- **keyword/entità:** test · hardening · cross-superficie · PAROLA-PONTE-4242 · claude.ai · Telegram · NotebookLM · execute_sql

---

### codice — archive-mcp index_build.py (indicizzatore FTS5)
- **source_id:** 72625995-3a12-4aed-8f6b-5a766208de32 · **tipo:** text
- **sostanza:** Codice Python dell'indicizzatore SQLite+FTS5 per l'export Claude.ai: parsing in streaming del file conversations.json (283 MB, 821 conversazioni) senza caricare tutto in memoria; crea tabelle conversations, messages, fts (FTS5), projects, project_docs, memories; mappa conv→progetto solo per i design-chat (l'unico legame presente nell'export); tokenizzazione unicode61 con rimozione diacritici.
- **keyword/entità:** Python · SQLite · FTS5 · streaming parsing · conversations.json · unicode61 · index_build

---

### codice — archive-mcp server.py (MCP archivio, 8 tool)
- **source_id:** 4ff7361b-abb1-427b-94af-67cb35164aa1 · **tipo:** text
- **sostanza:** Server MCP FastMCP per l'archivio Claude.ai: espone 8 tool in sola lettura su SQLite/FTS5 precostruito (archive_stats, search_conversations, list_conversations, get_conversation, get_message_context, get_memory, list_projects, get_project). Supporta trasporto stdio (Claude Code) e streamable-http (gateway→claude.ai). Include query FTS5 robusta con AND implicito, frasi esatte, prefissi e operatori OR.
- **keyword/entità:** FastMCP · 8 tool · sola lettura · stdio · streamable-http · FTS5 · get_project

---

### codice — dashboard.py (FastAPI :9000)
- **source_id:** 7c942160-a3da-413e-a5dd-7bcf703ce0f4 · **tipo:** text
- **sostanza:** Dashboard FastAPI locale su porta 9000: cruscotto operatore per mcp1777 con filesystem explorer sandboxato (4 root: lettore, progetto, memory, skills), log viewer live via SSE, pannello moduli con start/stop/status di 8 componenti (dashboard, notebooklm-mcp, telegram-mcp, bot-1, frontend-bot, bot2-gdr, watcher, gateway), query JSON-RPC verso MCP locali, rendering Markdown con wikilink, ricerca file con anteprima. CSS design system interno.
- **keyword/entità:** FastAPI · dashboard · SSE · log viewer · pannello moduli · sandbox · :9000 · wikilink

---

### codice — gateway.py (multi-MCP :8080, path-SECRET)
- **source_id:** 69b4d8be-f8cc-4417-aaad-bd79936f4995 · **tipo:** text
- **sostanza:** Gateway Starlette su porta 8080: proxy default-deny davanti ai tre MCP locali (notebooklm :8000, telegram :8001, archive :8002). Autenticazione via path segreto nell'URL; routing multi-MCP su singola porta pubblica. Implementa filtro a tre livelli: READ_TOOLS (solo lettura), WRITE_TOOLS (scritture additive consentite), DENY_PUBLIC (distruttivi/bypass/auth bloccati). Flag FULL_ACCESS=True per apertura completa su scelta esplicita.
- **keyword/entità:** gateway · Starlette · :8080 · path-SECRET · default-deny · READ_TOOLS · DENY_PUBLIC · FULL_ACCESS

---

### codice — telegram-bridge bot.py (bot bridge)
- **source_id:** 7df94f63-ebe0-44e2-be4c-bbdc8932d349 · **tipo:** text
- **sostanza:** Bot Telegram principale (@notebookllm1777_bot): ponte tra Telegram e Claude via `claude -p` (abbonamento Max, zero costi API). Ogni messaggio viene inoltrato a Claude con sessione persistente per chat_id; gestisce allegati (scaricati in workspace/incoming/), pulsanti inline con marcatore `[[btn: Label | payload]]`, logging JSONL condiviso col Telegram-MCP. Sicurezza: allowlist ID, DISALLOWED_TOOLS, workspace confinato, timeout 240s.
- **keyword/entità:** bot bridge · claude -p · sessione per chat_id · allowlist · DISALLOWED_TOOLS · messages.jsonl · inline keyboard

---

### codice — telegram-frontend frontend_bot.py (bot2 gdr)
- **source_id:** 61e24fe8-387a-46b8-aca5-8a0cead375e5 · **tipo:** text
- **sostanza:** Bot frontend Telegram (Fase 4, bot sociale per gruppi): privilegi quasi-zero, sola lettura, non chiama Claude né usa MCP. Comandi: /start, /help, /rules, /dice, /poll, /quiz, /ask. Il comando /ask mette la richiesta in coda human-in-the-loop (requests.jsonl) per valutazione dell'owner senza eseguire nulla. Usa un token diverso dal bot bridge (FRONTEND_BOT_TOKEN).
- **keyword/entità:** frontend bot · human-in-the-loop · requests.jsonl · FRONTEND_BOT_TOKEN · sola lettura · gruppi Telegram

---

### codice — telegram-mcp server.py (MCP Telegram)
- **source_id:** 7d51947b-2f1a-4e16-9f73-d4867ac0ef25 · **tipo:** text
- **sostanza:** Server MCP custom FastMCP per Telegram: espone 8 tool (telegram_send, telegram_send_file, telegram_recent, telegram_list_chats, workspace_list, workspace_read, workspace_write, workspace_append). Invio limitato a chat in allowlist; in modalità --http (canale pubblico) i tool di scrittura sono automaticamente disabilitati (READONLY_HTTP=True). Workspace confinata con guardia anti-traversal che blocca .env/.pem/.key.
- **keyword/entità:** telegram-mcp · FastMCP · 8 tool · READONLY_HTTP · workspace · anti-traversal · allowlist

---

### docker-vs-systemd-1777.md
- **source_id:** 199e408a-7592-44e4-a51f-40fc7afbe8e9 · **tipo:** text
- **sostanza:** Documento di scelta tecnologica per la persistenza di mcp1777: spiega Docker (container ≠ VM, niente push automatico al Docker Hub) e Kubernetes (orchestratore per cluster, sovradimensionato per un singolo PC); argomenta perché per questo progetto si è scelto systemd --user: lo stack è già installato nativo, l'autenticazione Google vive nell'utente locale, systemd dà riavvio automatico e boot-persistence gratis senza modifiche al codice.
- **keyword/entità:** Docker · Kubernetes · systemd · container · Docker Hub · lingering · decisione architetturale

---

### pacchetto — README.md
- **source_id:** f0fd7e8d-8320-4447-a4fb-89ac04707aaf · **tipo:** text
- **sostanza:** README del pacchetto di installazione mcp1777: descrive i componenti dello stack (MCP NotebookLM :8000, MCP Telegram :8001, MCP Archive :8002, Gateway :8080, Dashboard :9000, bot bridge, bot frontend, bot2), installazione in spazio utente con `bash install.sh` / `CONFIRM=yes bash install.sh`, gestione con systemctl --user. Segnala il limite onesto: URL tunnel cambia a ogni riavvio (quick-tunnel trycloudflare).
- **keyword/entità:** pacchetto · install.sh · systemd --user · stack completo · quick-tunnel · URL instabile

---

### pacchetto — health-check.sh
- **source_id:** 00da1b02-0f53-4499-a22b-d16a77dcafc7 · **tipo:** text
- **sostanza:** Script bash di health check per l'intero stack mcp1777: verifica le 5 porte (8000, 8001, 8002, 8080, 9000) via curl/JSON-RPC initialize, controlla che il bot bridge stia facendo polling (getUpdates entro 200 secondi), verifica lo stato di frontend bot e bot2 via pgrep, stampa l'URL corrente del tunnel cloudflared. Exit 0 se tutto ok.
- **keyword/entità:** health-check · bash · 5 porte · polling getUpdates · pgrep · exit 0 · curl

---

### pacchetto — install.sh (installer systemd, dry-run default)
- **source_id:** 80969e53-3731-4d63-8df0-55018575119a · **tipo:** text
- **sostanza:** Installer bash idempotente per mcp1777: verifica 7 dipendenze (python3, systemctl, venv telegram-mcp, cloudflared, notebooklm-mcp, dashboard-venv, i 4 file .env), installa l'unit in ~/.config/systemd/user/, esegue daemon-reload + enable + start, attiva loginctl enable-linger per persistenza al reboot. Default DRY-RUN: nessuna modifica finché non si passa CONFIRM=yes.
- **keyword/entità:** install.sh · DRY-RUN · systemd --user · loginctl enable-linger · dipendenze · idempotente

---

### pacchetto — mcp1777.service (systemd --user unit)
- **source_id:** 657ebe1d-2e06-43d7-8d3a-3da8490db417 · **tipo:** text
- **sostanza:** Unit file systemd --user per mcp1777: Type=simple, After=network-online.target, ExecStart=start-stack.sh, ExecStop=stop-stack.sh, Restart=on-failure con RestartSec=5, TimeoutStartSec=180. I path assoluti vengono riscritti dall'installer con il repo reale. WantedBy=default.target per avvio automatico utente.
- **keyword/entità:** systemd · unit file · Restart=on-failure · network-online.target · start-stack.sh · stop-stack.sh

---

### pacchetto — start-stack.sh (avvio completo)
- **source_id:** fc49b3b7-ab17-4239-9cca-eb03f21169ac · **tipo:** text
- **sostanza:** Script bash di avvio idempotente dell'intero stack mcp1777: avvia in ordine i 9 componenti (MCP NotebookLM :8000, MCP Telegram :8001, MCP Archive :8002, gateway :8080, tunnel cloudflared, dashboard :9000, bot bridge, bot frontend, bot2) solo se la porta/processo non è già attivo. Al termine fa `exec tail -f gateway-run.log` per mantenere il processo in foreground sotto systemd Type=simple.
- **keyword/entità:** start-stack.sh · idempotente · 9 componenti · nohup · cloudflared · tail -f · systemd foreground

---

### pacchetto — stop-stack.sh
- **source_id:** 0c1a934b-a04f-48f6-a161-c97e21bce711 · **tipo:** text
- **sostanza:** Script bash di stop dell'intero stack mcp1777: itera una lista di 9 pattern (bot bridge, frontend bot, bot2, cloudflared, gateway, archive-mcp, telegram-mcp, notebooklm-mcp, uvicorn dashboard) e invia SIGTERM a ogni processo trovato via pkill -f. Usato come ExecStop dell'unit systemd.
- **keyword/entità:** stop-stack.sh · pkill · SIGTERM · 9 pattern · ExecStop · systemd

---

## NB7 — Telegram Bots WebApps (ea593ab4)

### Esempio 01 HTML — Mini App skeleton
- **source_id:** acf681ff · **tipo:** text
- **sostanza:** Scheletro HTML5 completo di una Telegram Mini App: inizializzazione `window.Telegram.WebApp`, chiamata `tg.expand()` per modalità fullscreen, `sendData()` per inviare dati al bot, uso delle variabili CSS del tema Telegram per il theming automatico.
- **keyword/entità:** HTML5 · Mini-App · WebApp · sendData · tg.expand · CSS-theme-vars · Telegram

### Esempio 02 validazione — HMAC-SHA256
- **source_id:** 53fbba12 · **tipo:** text
- **sostanza:** Implementazione Python di `verify_init_data()` per validare l'`initData` ricevuto da Telegram WebApp. Usa HMAC-SHA256, include protezione anti-replay tramite controllo timestamp, e confronto constant-time per prevenire timing attacks.
- **keyword/entità:** HMAC-SHA256 · verify_init_data · Python · anti-replay · constant-time · sicurezza · initData

### Esempio 03 Bot Python — python-telegram-bot
- **source_id:** 95597904 · **tipo:** text
- **sostanza:** Implementazione bot Python con `python-telegram-bot` v20+: 3 metodi di apertura della Mini App (inline button, menu button, direct link), gestione del filtro `WEB_APP_DATA` per ricevere i dati inviati dalla web app tramite `sendData`.
- **keyword/entità:** python-telegram-bot · v20 · WEB_APP_DATA · inline-button · menu-button · handler

### Esempio 04 Game — Gaming Platform
- **source_id:** 52a4c153 · **tipo:** text
- **sostanza:** Implementazione completa di un gioco Telegram: `sendGame` + `setGameScore` per il leaderboard nativo, configurazione tramite `@BotFather /newgame`, integrazione `TelegramGameProxy.shareScore()` lato client per condivisione punteggi.
- **keyword/entità:** Gaming-Platform · sendGame · setGameScore · BotFather · TelegramGameProxy · leaderboard

### Esempio 05 Cheatsheet — decision table
- **source_id:** f507ace0 · **tipo:** text
- **sostanza:** Cheatsheet decisionale: tabella comparativa Web App vs Game Platform (quando usare quale), opzioni di hosting (Vercel, Railway, VPS), lista errori comuni con soluzioni. Riferimento rapido per lo sviluppo Telegram.
- **keyword/entità:** cheatsheet · Web-App-vs-Game · hosting · Vercel · Railway · errori-comuni

### Gaming Platform — docs ufficiali
- **source_id:** 5a9eed05 · **tipo:** url
- **sostanza:** Documentazione ufficiale Telegram per la Gaming Platform HTML5: flusso completo createGame → sendGame → pulsante Play → URL gioco → setGameScore. Include requisiti tecnici e limiti della piattaforma.
- **keyword/entità:** Gaming-Platform · createGame · sendGame · setGameScore · HTML5 · docs-ufficiali

### Telegram Bot API — riferimento completo
- **source_id:** 84cf672e · **tipo:** url
- **sostanza:** Riferimento API ufficiale completo del Bot API Telegram (568k chars). Documenta tutti i metodi, oggetti, update types, inline mode, payments, Stars, media, callback query, inline keyboard, e recenti aggiornamenti API.
- **keyword/entità:** Bot-API · metodi · oggetti · inline-mode · payments · Stars · update-types · Telegram

### Telegram Bot Features — funzionalità complete
- **source_id:** b2453db7 · **tipo:** url
- **sostanza:** Documentazione ufficiale delle funzionalità bot Telegram (67k chars): Mini Apps, pagamenti, Stars, comandi, menu personalizzati, modalità inline, gruppi/canali, gestione file. Include sezione dedicata alla sicurezza dei Mini Apps.
- **keyword/entità:** bot-features · Mini-Apps · pagamenti · Stars · inline-mode · sicurezza · comandi

### Telegram Mini Apps — riferimento ufficiale
- **source_id:** 18b8e1a5 · **tipo:** url
- **sostanza:** Riferimento ufficiale completo Telegram Mini Apps (126k chars): API JavaScript, ciclo di vita, theming, haptic feedback, biometria, metodi di pagamento, CloudStorage, viewport management. Aggiornato ad aprile 2026 con le ultime modifiche.
- **keyword/entità:** Mini-Apps · JavaScript-API · theming · haptic · biometria · CloudStorage · viewport · aprile-2026

---

## eb1f871b · masterIndex1777 — [meta] · 1 fonte

> Questo notebook **è** il catalogo strutturale. La sua unica source non viene
> re-indicizzata come contenuto: è il layer strutturale stesso, qui referenziato.

### Catalogo account — 2026-06-01 (strutturale, sync agora)
- **source_id:** ab054329-8180-484d-a5ff-95fc9c4f11fa · **tipo:** text
- **sostanza:** Il catalogo strutturale dell'account NotebookLM, sync 2026-06-01 da
  sessione agora: 48 notebook (47 lavoro + master), 926 fonti di lavoro. Elenca ogni
  notebook per tag (id breve · titolo · tag · n.fonti) e i conteggi per tag. Dichiara
  esplicitamente che il layer di CONTENUTO profondo è in carico a Claude Code (questo job).
- **keyword/entità:** masterIndex · catalogo strutturale · 48 notebook · 926 fonti ·
  tag (graphify 14, metodo 7, mcp 6…) · notebook fantasma 42a71b95 · sync atomico · provenienza

---

