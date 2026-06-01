## 519ffe52 · Claude Code — [reference] · 79 fonti

### Agent Skills API Docs
- **source_id:** b89e9cbd-... · **tipo:** text
- **sostanza:** Documentazione ufficiale Anthropic sull'architettura Skills tramite API. Descrive i 3 livelli di progressive disclosure (~100 token metadata, <5k SKILL.md, risorse on-demand), skill ufficiali per pptx/xlsx/docx/pdf, e come creare skill personalizzate con frontmatter YAML.
- **keyword/entità:** Skills API · progressive disclosure · SKILL.md · pptx · xlsx · docx · pdf · frontmatter

### Analisi Architetturale CLI v2.1.145+ (NLM)
- **source_id:** 39a2850e-... · **tipo:** text
- **sostanza:** Documento NLM in italiano che analizza la tassonomia completa dei comandi Claude Code: built-in, bundled (skill ufficiali) e custom. Tratta /ultraplan, /ultrareview e i 3 tipi di subagenti (Explore 575tk, Plan 715tk, General 285tk).
- **keyword/entità:** CLI v2.1.145 · /ultraplan · /ultrareview · subagenti · tassonomia comandi · bundled skills

### Architettura /goal (NLM)
- **source_id:** 3e091211-... · **tipo:** text
- **sostanza:** Documento NLM in italiano sull'architettura del comando /goal: modello esecutore+evaluator (Haiku), ciclo autonomo multi-turn, casi studio reali (sessione 91min e 9h27min con 41 subagents), flag stop_hook_active per evitare loop infiniti.
- **keyword/entità:** /goal · evaluator Haiku · stop_hook_active · ciclo autonomo · subagents · 9h27min

### Archivio Tecnico Totale (NLM)
- **source_id:** eb699d9a-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con piano operativo per analisi sistematica di Claude Code. Elenca variabili ENV nascoste da estrarre, fasi dell'analisi, e obiettivi di ricerca per ricostruire l'architettura completa del tool.
- **keyword/entità:** ENV vars · piano operativo · analisi tecnica · variabili nascoste · architettura

### Reddit r/ClaudeAI — Skills e slash commands unificati
- **source_id:** 67840109-... · **tipo:** url
- **sostanza:** Post Reddit in cui Boris Cherny (autore di Claude Code) conferma che in v2.1.1 skills e slash commands sono stati unificati: entrambi creano comandi /nome accessibili dall'interfaccia. Discussione sulla compatibilità tra .claude/commands/ (legacy) e .claude/skills/ (nuovo).
- **keyword/entità:** Boris Cherny · v2.1.1 · skills unificati · slash commands · .claude/commands/ · .claude/skills/

### CLI reference ufficiale (A)
- **source_id:** 9eadb727-... · **tipo:** text
- **sostanza:** Riferimento CLI ufficiale Claude Code con tutti i flag (--print, --output-format, --allowedTools, --max-turns, --model, --resume, --continue, --dangerously-skip-permissions, --bare) e sottocomandi: claude agents, attach, daemon, logs, mcp, plugin, ultrareview.
- **keyword/entità:** CLI flags · --bare · --dangerously-skip-permissions · --max-turns · claude agents · claude mcp · ultrareview

### CLI reference ufficiale (B)
- **source_id:** befc0c61-... · **tipo:** text
- **sostanza:** Duplicato identico della CLI reference ufficiale (9eadb727). Stessa lista completa di flag e sottocomandi.
- **keyword/entità:** CLI flags · --bare · --dangerously-skip-permissions · --max-turns · claude agents · claude mcp

### Changelog ufficiale Claude Code Docs
- **source_id:** 49f60f1f-... · **tipo:** text
- **sostanza:** Changelog completo ufficiale di Claude Code (371k chars), 296 release dalla v0.x alla v2.1.150. Documenta ogni modifica: nuove funzionalità, bug fix, breaking changes, nuovi hook events, nuovi flag CLI, aggiornamenti modelli.
- **keyword/entità:** changelog · v0.x → v2.1.150 · 296 release · release notes · breaking changes

### Jiří Dolejš — /goal v2.1.139
- **source_id:** e5243c55-... · **tipo:** url
- **sostanza:** Articolo tecnico su /goal introdotto in v2.1.139 (11 maggio 2026). Analizza l'evaluator Haiku che opera transcript-only, il hard cap "stop after 40 turns", e il meccanismo stop_hook_active per prevenire loop. Include snippet del sistema prompt dell'evaluator.
- **keyword/entità:** /goal · v2.1.139 · evaluator Haiku · transcript-only · 40 turns cap · stop_hook_active

### Shipyard — Claude Code Cheatsheet
- **source_id:** 9fd57ce8-... · **tipo:** url
- **sostanza:** Cheatsheet completo per Claude Code: installazione npm, modelli disponibili (Sonnet/Haiku/Opus 4.6), configurazione settings.json, struttura CLAUDE.md, hooks lifecycle, skills, subagents con esempi pratici di configurazione.
- **keyword/entità:** cheatsheet · npm install · settings.json · CLAUDE.md · Sonnet 4.6 · Haiku 4.6 · Opus 4.6

### Gradually AI — Changelog maggio 2026
- **source_id:** 0e572208-... · **tipo:** url
- **sostanza:** Aggregazione di 296 versioni complete di Claude Code da v0.x alla v2.1.150 (107k chars). Fonte terza parte che raccoglie sistematicamente tutti i release notes ufficiali con date e dettagli tecnici.
- **keyword/entità:** changelog · 296 versioni · v2.1.150 · Gradually AI · release history

### claudefa.st — Changelog 2026
- **source_id:** 478f8942-... · **tipo:** url
- **sostanza:** Changelog completo da claudefa.st (164k chars), Code Kit v5.3. Raccoglie tutte le versioni di Claude Code con descrizioni dettagliate per ogni release, organizzate cronologicamente dal 2025 al 2026.
- **keyword/entità:** claudefa.st · Code Kit v5.3 · changelog · 2026 · release history

### GitHub Gist — Claude Code Cheat Sheet
- **source_id:** 8f9d321d-... · **tipo:** url
- **sostanza:** Cheat sheet compatto su GitHub Gist con keyboard shortcuts (Ctrl+B per background, Esc+Esc per rewind), i "Big 5" comandi essenziali, e i permission modes (default, acceptEdits, plan, auto, dontAsk, bypassPermissions).
- **keyword/entità:** keyboard shortcuts · Ctrl+B · Esc+Esc · Big 5 · permission modes · bypassPermissions

### Blake Crosley — Cheat Sheet 2026
- **source_id:** 32b23181-... · **tipo:** text
- **sostanza:** Cheat sheet aggiornato a v2.1.150 (46k chars) con riferimento completo hooks, nuovi campi duration_ms e updatedToolOutput negli eventi hook, lista completa slash commands, flag CLI, e struttura .claude/.
- **keyword/entità:** v2.1.150 · duration_ms · updatedToolOutput · hooks · cheat sheet · 2026

### DataCamp — Tutorial Hooks
- **source_id:** 421ac734-... · **tipo:** url
- **sostanza:** Guida pratica (55k chars) alla creazione di hooks con esempi Python: security checks per bloccare comandi pericolosi, TDD enforcement per richiedere test prima di modifiche, cost tracking per monitorare token spesi, formatting automatico.
- **keyword/entità:** hooks tutorial · Python · security check · TDD enforcement · cost tracking · PreToolUse · PostToolUse

### Kyle Redelinghuys — Hooks come git hooks per AI
- **source_id:** 6bff1d76-... · **tipo:** url
- **sostanza:** Articolo che introduce i Claude Code hooks come equivalenti dei git hooks applicati agli agenti AI. Descrive 15 lifecycle events, 3 tipi di handler (script, command, inline), e casi d'uso pratici per controllo comportamento agente.
- **keyword/entità:** hooks · git hooks · lifecycle events · 15 eventi · handler types · AI agent control

### claudefa.st — Hooks Guide
- **source_id:** 59732328-... · **tipo:** url
- **sostanza:** Guida hooks di claudefa.st con 12 lifecycle events tabellati, spiegazione exit codes (0=successo, 2=blocco fisico, altri=warning non bloccante), 4 tipi di handler, e introduzione degli async hooks di gennaio 2026.
- **keyword/entità:** hooks · exit codes · 0/2/other · async hooks · Jan 2026 · 12 lifecycle events

### prg.sh — Slash Commands
- **source_id:** 6324e488-... · **tipo:** url
- **sostanza:** Articolo su slash commands di Claude Code (gennaio 2026): lista completa built-in, come creare custom commands in .claude/commands/, frontmatter options (description, allowed-tools, disallowed-tools), uso di argomenti $ARGUMENTS e riferimenti @file.
- **keyword/entità:** slash commands · .claude/commands/ · frontmatter · $ARGUMENTS · @file · built-in commands

### claudefa.st — Stop Hook
- **source_id:** cddd1222-... · **tipo:** url
- **sostanza:** Articolo dedicato allo Stop hook: pattern "test gate" per bloccare completamento se i test falliscono, "build validation" per verificare build prima di terminare, pattern "Ralph Wiggum" per loop persistenti, flag stop_hook_active per prevenire ricorsione infinita.
- **keyword/entità:** Stop hook · test gate · build validation · Ralph Wiggum · stop_hook_active · loop persistente

### Releasebot — Claude Code May 2026
- **source_id:** bd48cc0d-... · **tipo:** url
- **sostanza:** Aggregazione degli aggiornamenti Anthropic di maggio 2026 (60k chars). Documenta le release di Claude Code durante il mese con changelog dettagliati, nuove funzionalità, fix e breaking changes.
- **keyword/entità:** maggio 2026 · Anthropic · release notes · changelog · aggiornamenti

### VentureBeat — /goals feature
- **source_id:** 74c58808-... · **tipo:** url
- **sostanza:** BLOCKED — La pagina restituisce un Vercel security checkpoint (326 chars). Contenuto inaccessibile.
- **keyword/entità:** VentureBeat · /goals · Vercel security · inaccessibile

### NLM — Analisi fonti (A)
- **source_id:** 05afc6da-... · **tipo:** text
- **sostanza:** Documento NLM in italiano che analizza le fonti del notebook, suggerisce quali fonti tenere, quali scartare per ridondanza, e come ottimizzare il set di riferimenti per l'analisi di Claude Code.
- **keyword/entità:** analisi fonti · NotebookLM · selezione · ridondanza · ottimizzazione

### NLM — Analisi fonti (B)
- **source_id:** d984bde6-... · **tipo:** text
- **sostanza:** Duplicato identico di 05afc6da. Stesso documento NLM che analizza le fonti del notebook e suggerisce selezione/scarto.
- **keyword/entità:** analisi fonti · NotebookLM · selezione · ridondanza

### Commands — Claude Code Docs (A)
- **source_id:** 1bd37a52-... · **tipo:** text
- **sostanza:** Lista completa ufficiale di circa 80 comandi Claude Code: built-in (/help, /clear, /compact, /model, /cost, /status, /resume, /bug, /memory, /pr-comments, /vim, /doctor, /login, /logout) e bundled skills (docx, pdf, pptx, xlsx, commit-push-pr, security-guidance, typescript-lsp).
- **keyword/entità:** comandi built-in · bundled skills · /compact · /model · /resume · /memory · /pr-comments · /doctor

### Commands — Claude Code Docs (B)
- **source_id:** 45b4ef01-... · **tipo:** text
- **sostanza:** Duplicato identico di 1bd37a52. Stessa lista completa di comandi built-in e bundled skills ufficiali.
- **keyword/entità:** comandi built-in · bundled skills · /compact · /model · /resume

### Commands — Claude Code Docs (C)
- **source_id:** 49f67071-... · **tipo:** text
- **sostanza:** Duplicato identico di 1bd37a52 e 45b4ef01. Stessa lista ufficiale comandi.
- **keyword/entità:** comandi built-in · bundled skills · /compact · /model

### ComposioHQ/awesome-claude-skills
- **source_id:** 20b1c3b7-... · **tipo:** url
- **sostanza:** Repository GitHub curated list (72k chars) di skill per Claude Code. Organizzato per categorie: development, productivity, research, security. Include istruzioni per installazione via /plugin marketplace add e contribuzione nuove skill.
- **keyword/entità:** awesome-claude-skills · ComposioHQ · curated list · skill categorie · /plugin marketplace · installazione

### Create custom subagents — Claude Code Docs
- **source_id:** 8760615b-... · **tipo:** text
- **sostanza:** Documentazione ufficiale subagents (74k chars): come creare subagenti personalizzati con file .md in .claude-plugin/agents/, frontmatter YAML (name, description, tools, model), isolamento contesto, tipi di subagente (Explore/Plan/General) con token budget differenziati.
- **keyword/entità:** subagents · .claude-plugin/agents/ · frontmatter YAML · isolamento contesto · Explore · Plan · General · token budget

### Create plugins — Claude Code Docs
- **source_id:** b7f4240f-... · **tipo:** text
- **sostanza:** Documentazione ufficiale sulla creazione di plugin: struttura .claude-plugin/plugin.json come manifest, componenti (skills, agents, hooks, MCP servers, LSP servers), pubblicazione su marketplace ufficiale, versionamento e distribuzione.
- **keyword/entità:** plugin · .claude-plugin/plugin.json · manifest · marketplace · MCP servers · LSP servers · distribuzione

### SFEIR Institute — Cheatsheet
- **source_id:** a6b1f0f9-... · **tipo:** url
- **sostanza:** Cheatsheet tecnico SFEIR Institute su Claude Code: custom slash commands con .claude/commands/, skills con .claude/skills/, subagents isolati, hooks lifecycle, configurazione MCP in settings.json, keyboard shortcuts principali.
- **keyword/entità:** SFEIR Institute · cheatsheet · slash commands · skills · subagents · hooks · MCP config · keyboard shortcuts

### Bozhidar Batsov — Skills vs Slash Commands
- **source_id:** 18b79ba2-... · **tipo:** url
- **sostanza:** Articolo che chiarisce la distinzione tra skills (nuovo sistema raccomandato) e slash commands (legacy .claude/commands/), elenca le built-in skills ufficiali, e discute i comandi più utili per workflow quotidiano.
- **keyword/entità:** skills · slash commands · built-in skills · distinzione · .claude/commands/ legacy · workflow

### Extend Claude with skills (A)
- **source_id:** 16fc21eb-... · **tipo:** text
- **sostanza:** Documentazione ufficiale skills (52k chars): architettura progressive disclosure a 3 livelli, struttura SKILL.md con frontmatter, argomenti $ARGUMENTS/$1/$2, riferimenti @file, bash execution con !`cmd`, condivisione via plugin, differenza skills/commands legacy.
- **keyword/entità:** skills · SKILL.md · progressive disclosure · $ARGUMENTS · @file · bash execution · frontmatter

### Extend Claude with skills (B)
- **source_id:** 85d737b0-... · **tipo:** text
- **sostanza:** Duplicato identico di 16fc21eb. Stessa documentazione ufficiale skills con progressive disclosure, SKILL.md, argomenti e condivisione.
- **keyword/entità:** skills · SKILL.md · progressive disclosure · $ARGUMENTS · @file

### Find bugs with ultrareview
- **source_id:** ec1f0b5a-... · **tipo:** url
- **sostanza:** Pagina ufficiale /ultrareview: review multi-agente cloud-based del codice, analisi approfondita bug e vulnerabilità, pricing ($5-20 per review), uso da CLI con claude ultrareview, output con commenti strutturati per categoria.
- **keyword/entità:** /ultrareview · multi-agente · cloud · bug review · pricing $5-20 · CLI · sicurezza

### Genesi e Architettura Ecosistema Claude Code (NLM)
- **source_id:** fa11b8fb-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con prompt di ricerca totale sull'ecosistema. Documenta comandi avanzati: /loki-mode (37 agenti specializzati), /fractal (decomposizione ricorsiva task), /agento-patronum (orchestrazione), flag --bare (skip auto-discovery), variabile CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS=1.
- **keyword/entità:** /loki-mode · /fractal · /agento-patronum · --bare · CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS · 37 agenti

### travisvn/awesome-claude-skills
- **source_id:** 01813fdf-... · **tipo:** url
- **sostanza:** Repository GitHub curated list (12.9k stars) di skill ufficiali e community. Include skill ufficiali Anthropic (docx/pdf/pptx/xlsx), Trail of Bits Security, progressive disclosure spiegato con esempi, FAQ su installazione e compatibilità, link al marketplace.
- **keyword/entità:** awesome-claude-skills · 12.9k stars · Trail of Bits · skill ufficiali · progressive disclosure · FAQ · marketplace

### Glossary — Claude Code Docs
- **source_id:** 87bfece4-... · **tipo:** text
- **sostanza:** Glossario ufficiale Claude Code con definizioni complete: agent teams, agentic coding, hooks, MCP Tool Search, subagent, surface, teleport, worktree isolation; include anche termini deprecati con note di migrazione verso la nuova terminologia.
- **keyword/entità:** glossario · agent teams · agentic coding · MCP Tool Search · teleport · worktree isolation · termini deprecati

### Guida Definitiva ai Comandi Hacker (NLM)
- **source_id:** b5618054-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con tabella HTML filtrabile di tutti i comandi avanzati ("hacker"). Documenta /loki-mode (37 agenti), /agento-patronum, /fractal, /skills-janitor, --bare, --dangerously-skip-permissions, /btw (side questions), con versioni, descrizioni e note di sicurezza.
- **keyword/entità:** /loki-mode · /agento-patronum · /fractal · /skills-janitor · --bare · /btw · tabella HTML filtrabile

### Guida Operativa e Ricerca Comandi (NLM)
- **source_id:** e07006b1-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con prompt ottimizzati per usare Deep Research di NotebookLM per trovare sistematicamente tutti i comandi Claude Code. Include istruzioni metodologiche per estrarre e verificare ogni comando dalle fonti.
- **keyword/entità:** Deep Research · NotebookLM · prompt ricerca · comandi · metodologia · estrazione sistematica

### Guida ai Comandi e Prompt di Ricerca (NLM)
- **source_id:** 0a9aad6f-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con analisi delle fonti disponibili e prompt ottimizzato per ricerca comandi nella versione v2.1.145+. Guida alla classificazione delle fonti per affidabilità e copertura dei comandi.
- **keyword/entità:** v2.1.145 · prompt ottimizzato · classificazione fonti · affidabilità · copertura comandi

### Guida alla Classificazione e Selezione Comandi (NLM)
- **source_id:** 24dc660e-... · **tipo:** text
- **sostanza:** Documento NLM in italiano che classifica le fonti disponibili in categorie per utilità nell'estrazione della lista comandi: ufficiali, community, cheatsheet, articoli. Include criteri di selezione e peso da attribuire a ciascuna categoria.
- **keyword/entità:** classificazione fonti · criteri selezione · ufficiali · community · cheatsheet · lista comandi

### Reddit r/ClaudeAI — 50+ slash commands (A)
- **source_id:** b1b9423b-... · **tipo:** url
- **sostanza:** Post Reddit con breakdown per categoria di 50+ slash commands. Distingue built-in, bundled skills (docx/pdf/pptx/xlsx), e custom skills installabili in ~/.claude/skills/. Include discussione su quale sistema preferire e limitazione 77 skill visibili.
- **keyword/entità:** 50+ slash commands · breakdown categorie · ~/.claude/skills/ · 77 skill limit · bundled skills

### Reddit r/ClaudeAI — 50+ slash commands (B)
- **source_id:** b40b62c0-... · **tipo:** url
- **sostanza:** Duplicato identico di b1b9423b. Stesso post Reddit sui 50+ slash commands con breakdown per categoria.
- **keyword/entità:** 50+ slash commands · categorie · ~/.claude/skills/ · built-in · bundled

### Reddit r/ClaudeAI — 50+ slash commands (C)
- **source_id:** c02de129-... · **tipo:** url
- **sostanza:** Duplicato identico di b1b9423b e b40b62c0. Stesso post Reddit sui 50+ slash commands.
- **keyword/entità:** 50+ slash commands · categorie · ~/.claude/skills/

### Reddit r/ClaudeAI — Custom Skills vs MCP
- **source_id:** 016626ee-... · **tipo:** url
- **sostanza:** Post Reddit "Why I Built Custom Skills Instead of MCP" con esempi pratici: skill Playwright per browser automation, skill Nano Banana per gestione immagini, skill Telegram, skill AWS CLI. Discute il limite 77 skill visibili e il meccanismo MCP Tool Search come soluzione.
- **keyword/entità:** custom skills · MCP · Playwright · Nano Banana · Telegram · AWS CLI · 77 skill limit · MCP Tool Search

### Hooks reference — Claude Code Docs
- **source_id:** c187bc1c-... · **tipo:** text
- **sostanza:** Documentazione ufficiale completa hooks (167k chars): tutti i 25+ hook events (SessionStart, UserPromptSubmit, PreToolUse, PermissionRequest, PostToolUse, PostToolUseFailure, PostToolBatch, Stop, StopFailure, Notification, SubagentStart, SubagentStop, TaskCreated, TaskCompleted, TeammateIdle, InstructionsLoaded, ConfigChange, CwdChanged, FileChanged, WorktreeCreate, WorktreeRemove, PreCompact, PostCompact, Elicitation, ElicitationResult, SessionEnd), schema JSON input/output per ciascuno, exit codes, esempi.
- **keyword/entità:** hooks reference · 25+ eventi · SessionStart · PreToolUse · PostToolUse · Stop · SessionEnd · exit codes · schema JSON

### How Claude Code works
- **source_id:** 3a015bdb-... · **tipo:** text
- **sostanza:** Documentazione ufficiale sul funzionamento interno: agentic loop in 3 fasi (gather context/act/verify), lista completa tool disponibili (Read, Write, Edit, Bash, WebSearch, WebFetch, TodoWrite, Task), ambienti di esecuzione supportati, permission modes con esempi d'uso.
- **keyword/entità:** agentic loop · gather/act/verify · tools · Read · Write · Bash · WebSearch · TodoWrite · permission modes

### How Claude Code works (duplicato)
- **source_id:** 4c0594a1-... · **tipo:** text
- **sostanza:** Duplicato identico di 3a015bdb. Stessa documentazione ufficiale sull'agentic loop e strumenti disponibili.
- **keyword/entità:** agentic loop · tools · permission modes · gather/act/verify

### Reddit r/ClaudeCode — 9-hour /goal session
- **source_id:** 6eb6d3e8-... · **tipo:** url
- **sostanza:** Post Reddit di horos55 che documenta una sessione /goal di 9 ore e 27 minuti: costruzione di un Go data orchestrator con 41 subagents, 45 commits, 14.259 LOC scritte autonomamente, SQLite ledger per tracking, tassonomia degli stop hook usati per garantire qualità.
- **keyword/entità:** /goal · 9h27min · 41 subagents · 45 commits · 14.259 LOC · Go orchestrator · SQLite · stop hook taxonomy

### MindStudio — How to Use Claude Code Skills
- **source_id:** aaa38623-... · **tipo:** url
- **sostanza:** Guida pratica MindStudio sulla creazione e uso di skills: custom slash commands step-by-step, hooks per automazione, integrazione MCP, chaining di skill multiple, scheduling headless per esecuzione automatica senza interfaccia utente.
- **keyword/entità:** MindStudio · skills · slash commands · hooks · MCP · chaining · headless scheduling

### MindStudio — /compact command guide
- **source_id:** 715f1024-... · **tipo:** url
- **sostanza:** Guida completa al comando /compact: problema "context rot" (degrado qualità con contesto pieno), regola del 60% (compattare quando context window raggiunge 60-70%), 4 categorie di informazioni preservate durante compattazione, best practices per sessioni lunghe.
- **keyword/entità:** /compact · context rot · 60% rule · context window · compattazione · sessioni lunghe

### Reddit r/ClaudeCode — Stop hook discussion
- **source_id:** 695929d9-... · **tipo:** url
- **sostanza:** Thread Reddit (172 upvotes) sugli usi dello Stop hook: esempi community (TTS text-to-speech all'avvio, dado D20 per completamento, notifica vocale), verifica exit code, pattern avanzati, discussion su sicurezza e best practices.
- **keyword/entità:** Stop hook · TTS · D20 · notifica vocale · exit code · 172 upvotes · community examples

### Reddit r/ClaudeCode — AI Scientist skill pack
- **source_id:** fbbf1af5-... · **tipo:** url
- **sostanza:** Post Reddit su "AI Scientist" skill pack: 13 skill per accesso a database accademici e scientifici (PubMed 37M+ papers, ArXiv 2.5M+ preprint, ChEMBL 2M+ composti chimici, DrugBank, ClinicalTrials.gov, FDA databases). Installabile via /plugin marketplace add yorkeccak/scientific-skills.
- **keyword/entità:** AI Scientist · PubMed · ArXiv · ChEMBL · DrugBank · ClinicalTrials · FDA · /plugin marketplace · 13 skill

### Interactive mode — Claude Code Docs
- **source_id:** 62aea123-... · **tipo:** text
- **sostanza:** Documentazione ufficiale modalità interattiva: tutti i keyboard shortcuts (Ctrl+B background bash, Ctrl+O apri editor esterno, Ctrl+T task list, Esc+Esc rewind conversation), modalità vim per editing, /btw per domande laterali senza perdere contesto, task list con Ctrl+T, session recap, PR review status.
- **keyword/entità:** interactive mode · Ctrl+B · Ctrl+T · Esc+Esc · vim mode · /btw · task list · keyboard shortcuts · PR review

### Introduction to subagents — Anthropic Courses
- **source_id:** 3885da33-... · **tipo:** url
- **sostanza:** BLOCKED — La pagina restituisce 403 CloudFront error. Contenuto inaccessibile (corso ufficiale Anthropic sui subagenti).
- **keyword/entità:** subagents · Anthropic Courses · 403 · CloudFront · inaccessibile

### Keep Claude working toward a goal (A)
- **source_id:** 4319d6e5-... · **tipo:** text
- **sostanza:** Documentazione ufficiale /goal (v2.1.139+): sintassi completa, come scrivere condizioni efficaci (measurable end state + stated check + constraints, max 4000 chars), come verificare status in corso, come interrompere, esecuzione non-interattiva, meccanismo interno (Stop hook + evaluator Haiku).
- **keyword/entità:** /goal · v2.1.139 · measurable end state · 4000 chars · stop hook · evaluator Haiku · non-interattivo

### Keep Claude working toward a goal (B)
- **source_id:** 4604c226-... · **tipo:** text
- **sostanza:** Duplicato identico di 4319d6e5. Stessa documentazione ufficiale /goal con sintassi, best practices per condizioni efficaci e meccanismo interno.
- **keyword/entità:** /goal · v2.1.139 · measurable end state · evaluator Haiku · stop hook

### SKM — Managing Skills (Front2BackDev)
- **source_id:** 5d041d4a-... · **tipo:** url
- **sostanza:** Articolo di Front2BackDev su SKM (Skill Manager): problema "skill sprawl" con skill sparse tra progetti, soluzione con repository git personale come libreria centralizzata. Comandi /SKM list, /SKM install, /SKM save per gestire skill tra progetti multipli.
- **keyword/entità:** SKM · Skill Manager · skill sprawl · git repository · /SKM list · /SKM install · /SKM save · Front2BackDev

### Matrice Tecnica Totale Claude Code HTML 2.0 (NLM)
- **source_id:** fe7e3c61-... · **tipo:** text
- **sostanza:** Documento NLM con tabella HTML interattiva e filtrabile di comandi e variabili ENV. Include /goal, /compact, /ultraplan, /batch, /run, /loki-mode, /agento-patronum, /btw; variabili CLAUDE_CODE_SIMPLE, MAX_THINKING_TOKENS, --dangerously-skip-permissions; interpol $ARGUMENTS; exit code 2 come "blocco fisico" del tool.
- **keyword/entità:** tabella HTML filtrabile · CLAUDE_CODE_SIMPLE · MAX_THINKING_TOKENS · exit code 2 · $ARGUMENTS · /batch · /run

### Njengah/claude-code-cheat-sheet
- **source_id:** fb274f51-... · **tipo:** url
- **sostanza:** Cheat sheet GitHub (1.7k stars) con 10 livelli di complessità (basic → enterprise). Include installazione (curl/brew/winget), tutti i CLI flags, slash commands per categoria, best practices di workflow. Aggiornato a maggio 2026 con le ultime funzionalità.
- **keyword/entità:** cheat sheet · 1.7k stars · 10 livelli · curl/brew/winget · enterprise · maggio 2026

### Piano Operativo Consolidamento Motore Tecnico (NLM)
- **source_id:** 26947b8d-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con piano 4 fasi per consolidare conoscenza tecnica. Elenca variabili ENV documentate: CLAUDE_CODE_SIMPLE, MAX_THINKING_TOKENS, CLAUDE_AUTOCOMPACT_PCT_OVERRIDE, CLAUDE_CODE_DISABLE_BACKGROUND_TASKS, CLAUDE_CODE_STOP_HOOK_BLOCK_CAP, CLAUDE_CODE_NO_FLICKER, CLAUDE_CODE_FORK_SUBAGENT. Include script PreToolUse (security_gate.py) e Stop hook (goal_alert.sh).
- **keyword/entità:** ENV vars · CLAUDE_AUTOCOMPACT_PCT_OVERRIDE · CLAUDE_CODE_STOP_HOOK_BLOCK_CAP · CLAUDE_CODE_FORK_SUBAGENT · security_gate.py · goal_alert.sh

### Plan in the cloud with ultraplan
- **source_id:** 9fd98b23-... · **tipo:** text
- **sostanza:** Documentazione ufficiale /ultraplan (v2.1.91+): prompt inviato al cloud (Opus), output visualizzato nel browser con commenti inline, emoji reactions, sidebar outline. Flusso completo: CLI → cloud → browser → approve → execute on web (PR) o teleport back al terminale. Non disponibile su Bedrock/Vertex/Foundry.
- **keyword/entità:** /ultraplan · v2.1.91 · cloud · Opus · browser · inline comments · teleport · Bedrock · Vertex

### Plugins reference — Claude Code Docs
- **source_id:** df3bf9d2-... · **tipo:** text
- **sostanza:** Documentazione ufficiale plugins reference (61k chars): componenti di plugin.json (skills/SKILL.md, agents/.md, hooks/hooks.json, MCP servers, LSP servers), regole path behavior (replace vs add to default), schema userConfig per configurazione utente, namespace e distribuzione.
- **keyword/entità:** plugins reference · plugin.json · SKILL.md · hooks.json · MCP servers · LSP servers · userConfig · namespace

### Prompt ricerca architettura Claude Code [API] (NLM)
- **source_id:** cdb5cade-... · **tipo:** text
- **sostanza:** Documento NLM con risposta Deep Research sull'architettura interna. Copre: evoluzione system prompts v1.x→v2.0, 25+ hook events, Agent Teams (SendMessageTool, TeammateTool), autoDream (4 fasi, 3 gate di qualità), KAIROS (always-on daemon), variabili nascoste (USER_TYPE=ant per undercover mode Anthropic, CLAUDE_CODE_STOP_HOOK_BLOCK_CAP, CLAUDE_CODE_ABLATION_BASELINE), 100+ ENV vars, 108 feature flags, leak sorgente marzo 2026 (512k righe).
- **keyword/entità:** architettura interna · autoDream · KAIROS · USER_TYPE=ant · Agent Teams · SendMessageTool · 108 feature flags · leak marzo 2026

### Quickstart — Claude Code Docs
- **source_id:** f4df019b-... · **tipo:** text
- **sostanza:** Guida quickstart ufficiale: installazione con curl/brew/winget/apt/dnf, autenticazione con chiave API Anthropic, prime sessioni di lavoro, comandi base (claude -p, -c, -r per print/continue/resume), operazioni Git assistite, best practices iniziali.
- **keyword/entità:** quickstart · curl · brew · winget · apt · autenticazione · -p · -c · -r · Git operations

### Release notes — Claude Help Center
- **source_id:** 5a6f5a23-... · **tipo:** url
- **sostanza:** Note di rilascio mensili del Claude Help Center (ago 2025 - mag 2026). Documenta rilascio nuovi modelli: Sonnet 4.5 (set 2025), Haiku 4.5 (ott 2025), Opus 4.5 (nov 2025), Sonnet 4.6 (feb 2026), Opus 4.6 (feb 2026), Opus 4.7 (apr 2026). Include Cowork GA, Claude Design, Computer Use, Skills for organizations, Claude Compliance API.
- **keyword/entità:** release notes · Sonnet 4.5/4.6 · Haiku 4.5 · Opus 4.5/4.6/4.7 · Cowork GA · Computer Use · Claude Compliance API

### Slash Commands in the SDK (A)
- **source_id:** 1a2db67f-... · **tipo:** text
- **sostanza:** Documentazione SDK su slash commands: /compact e /clear built-in, confronto .claude/commands/ (legacy) vs .claude/skills/<name>/SKILL.md (raccomandato), argomenti posizionali $1/$2 e $ARGUMENTS, bash execution con !`cmd`, file references con @file, namespacing con subdirectory.
- **keyword/entità:** slash commands SDK · /compact · /clear · $1/$2 · $ARGUMENTS · !`cmd` · @file · namespacing

### Slash Commands in the SDK (B)
- **source_id:** 7f7aee94-... · **tipo:** text
- **sostanza:** Duplicato identico di 1a2db67f. Stessa documentazione SDK su slash commands, argomenti e namespace.
- **keyword/entità:** slash commands SDK · $ARGUMENTS · !`cmd` · @file · legacy vs raccomandato

### Studio Architetturale e Guida Tecnica (NLM)
- **source_id:** 51dbd0ef-... · **tipo:** text
- **sostanza:** Documento NLM in italiano con analisi matematica della context window (formula T_disp, T_buffer=33k, soglia η≥0.60 per context rot), tabella 50+ slash commands con versione di introduzione, hook lifecycle table con 10 eventi, CLI flags completi, novità v2.1.139-v2.1.150 (continueOnBlock, args: string, PowerShell escape fix, CLAUDE_PROJECT_DIR per MCP stdio).
- **keyword/entità:** context window formula · T_buffer · η≥0.60 · continueOnBlock · CLAUDE_PROJECT_DIR · PowerShell · v2.1.139-v2.1.150

### The Complete Claude Code Power User Guide (DEV.to)
- **source_id:** 3c26da10-... · **tipo:** url
- **sostanza:** Guida completa su DEV.to per power user: CLAUDE.md come "constitution" del progetto, distinzione commands legacy vs skills raccomandati, hooks come regole mandatory (vs advisory di CLAUDE.md), subagents per isolamento contesto, MCP per integrazioni esterne, plugins per bundle condivisibili, discipline di sessione con /clear e /compact.
- **keyword/entità:** power user guide · CLAUDE.md constitution · hooks mandatory · subagents isolation · MCP · plugins bundle · session discipline

### Tim Dietrich — Developer Guide (A)
- **source_id:** a1608fab-... · **tipo:** url
- **sostanza:** Guida sviluppatore di Tim Dietrich con comandi avanzati: /compact, /clear, /model, /diff, /resume, /fork (branch conversazionale), /rewind ("Rewind code only"), /plan (Plan Mode), /insights (report HTML uso mensile), /security-review, /simplify (pipeline 3 agenti), /batch (worktrees paralleli), /btw, /remote-control; CLI --print/-p, --worktree/-w, --allowedTools, --max-turns, --agents.
- **keyword/entità:** Tim Dietrich · /fork · /rewind · /insights · /simplify · /batch · /remote-control · /btw · --worktree · --agents

### Tim Dietrich — Developer Guide (B)
- **source_id:** e25aedf8-... · **tipo:** url
- **sostanza:** Duplicato identico di a1608fab. Stessa guida Tim Dietrich con comandi avanzati e flag CLI.
- **keyword/entità:** Tim Dietrich · /fork · /rewind · /insights · /simplify · /batch · /remote-control

### Reddit r/ClaudeAI — 28 official Claude Code plugins
- **source_id:** b8b1096f-... · **tipo:** url
- **sostanza:** Post Reddit (49k chars) con lista 50+ plugin ufficiali trovati in ~/.claude/plugins/marketplaces/claude-plugins-official/plugins/. I più utili segnalati: typescript-lsp (Language Server Protocol), security-guidance (Trail of Bits), context7 (documentazione aggiornata), playwright (browser automation).
- **keyword/entità:** plugin ufficiali · typescript-lsp · security-guidance · context7 · playwright · ~/.claude/plugins/ · marketplace

### MindStudio — What Is the /goal Command
- **source_id:** ac7790b1-... · **tipo:** url
- **sostanza:** Guida MindStudio al comando /goal come agentic loop autonomo: fasi (planning → iterative execution → observe-act-observe loop), quando usare /goal vs regular prompting, come scrivere prompt efficaci (scope, success criteria, constraints, context), considerazioni di sicurezza (version control, frequenza interruzioni, review prima di merge).
- **keyword/entità:** /goal · agentic loop · planning · success criteria · sicurezza · version control · interruption frequency

### bug-fix | ClaudePluginHub
- **source_id:** 04e38bd7-... · **tipo:** url
- **sostanza:** BLOCKED — La pagina restituisce un Vercel security checkpoint (326 chars). Contenuto inaccessibile (pagina bug-fix del Claude Plugin Hub).
- **keyword/entità:** ClaudePluginHub · bug-fix · Vercel security · inaccessibile

### claude-code-ultimate-guide hooks README (GitHub)
- **source_id:** 3fc75af6-... · **tipo:** url
- **sostanza:** README con 32+ hook scripts categorizzati per evento (4.5k stars repo). Include: dangerous-actions-blocker.sh (blocca rm -rf, fork bomb, DROP DATABASE, git push --force), security-check.sh, prompt-injection-detector.sh, output-secrets-scanner.sh, session-summary.sh v3 (15 sezioni configurabili, JSONL log), auto-format.sh, notification.sh (macOS sound alerts contestuali), pre-commit-evaluator.sh (LLM-as-Judge), velocity-governor.sh.
- **keyword/entità:** ultimate-guide · 32+ hook scripts · dangerous-actions-blocker · prompt-injection-detector · secrets-scanner · LLM-as-Judge · velocity-governor

### claude-code-ultimate-guide cheatsheet.md (GitHub)
- **source_id:** b1848ea4-... · **tipo:** url
- **sostanza:** Cheatsheet v3.41.0 (4.5k stars, maggio 2026) con 50+ comandi, keyboard shortcuts, struttura .claude/, workflow tipico, soglie context management (70%=compact/85%=clear), tabella costi modelli (Opus 4.7 $5/$25, Sonnet 4.6 $3/$15, Haiku 4.5 $0.80/$4), MCP servers (Serena, grepai, Context7, Playwright), Tasks API v2.1.16+, remote control, community tools (ccusage, RTK, claude-code-viewer).
- **keyword/entità:** cheatsheet v3.41.0 · Opus 4.7 $5/$25 · Sonnet 4.6 $3/$15 · Haiku 4.5 $0.80/$4 · Tasks API · ccusage · Serena · Context7

### commit-push-pr.md (anthropics/claude-code)
- **source_id:** 1c8db198-... · **tipo:** url
- **sostanza:** File comando ufficiale Anthropic nel repository claude-code: skill built-in per creare branch + commit + push + PR in singolo messaggio. Usa !`git status`, !`git diff HEAD`, !`git branch --show-current` e gh pr create per automazione completa del workflow Git.
- **keyword/entità:** commit-push-pr · built-in skill · Anthropic · gh pr create · !`git status` · !`git diff HEAD` · workflow Git

### rohitg00/awesome-claude-code-toolkit (GitHub)
- **source_id:** 42d58d5e-... · **tipo:** url
- **sostanza:** Repository GitHub comprehensivo (194 contributors, v0.5.0 maggio 2026): 135 agenti categorizzati (core development, research-analysis, QA, security ecc.), 35 curated skills, 42 comandi, 176+ plugin, 20 hooks, 15 rules, 7 templates, 14 MCP configs, 26 companion apps, 52 ecosystem entries. Include agentk CLI (zero-config, 20+ tools, Ollama) e qa-orchestra (10 agenti QA specializzati). Skill accessibili via SkillKit marketplace (400.000+ skill).
- **keyword/entità:** awesome-claude-code-toolkit · 135 agenti · 176+ plugin · SkillKit · 400k skill · agntk CLI · qa-orchestra · 194 contributors
