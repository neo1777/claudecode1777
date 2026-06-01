## 1736dca0 · Securing the Model Context Protocol: Enterprise Defense Framework — [mcp] · 67 fonti

---

### Claude Agent SDK — Overview
- **source_id:** 88b8f8ed-7891-4ccf-a6fd-7bdd98be5e19 · **tipo:** url
- **sostanza:** Documentazione ufficiale dell'Anthropic Agent SDK: espone la funzione `query()` come generatore asincrono che emette eventi strutturati, gestione di tools, sessioni persistenti, subagenti e supporto nativo MCP come livello di integrazione. Copre il pattern programmatico per costruire agenti Claude embedded in applicazioni Python.
- **keyword/entità:** Claude Agent SDK · query() · async generator · tools · sessioni · subagents · MCP · Python · Anthropic

---

### Agent Skills in the Claude Agent SDK
- **source_id:** 81759650-d4a5-41c7-a77c-cd1fa6e47d5f · **tipo:** url
- **sostanza:** Guida ufficiale sull'integrazione delle Skills nel Claude Agent SDK: file SKILL.md come vettore di istruzioni, parametro `settingSources` per iniettare contenuto in session settings, opzione `skills` per attivare skill a livello programmatico. Distingue skills globali, di progetto e locali.
- **keyword/entità:** Agent Skills · SKILL.md · settingSources · skills option · Claude Agent SDK · session settings

---

### Analisi sintetica — bug di graph partitioning in graphify (Issue #919, #934, PR #942)
- **source_id:** 554067bd-c4cb-4c17-a89a-7e0e4a40be97 · **tipo:** text
- **sostanza:** Documento sintetico che analizza tre difetti correlati nel clustering di graphify: coesione delle community degradata da super-hub, crash FileNotFoundError di `cluster-only` quando `graphify-out/` non esiste, e il PR #942 che corregge con `out.mkdir()`. Propone anche un terzo approccio (edge-weight mode) per attaccare il super-hub da un'angolazione diversa.
- **keyword/entità:** graphify · Leiden · super-hub · cluster-only · Issue #919 · Issue #934 · PR #942 · --exclude-hubs · --resolution · edge-weight mode · neo1777

---

### Issue #305 — ValueError on MultiGraph edge access
- **source_id:** 4ff6203a-7f93-416a-8aab-8e5c56ebe0bb · **tipo:** url
- **sostanza:** Issue GitHub su graphify: accesso a edge data su un MultiGraph con la notazione standard `G[u][v]` restituisce un dizionario di dizionari (keyed by edge key) invece del dict di attributi, causando ValueError. Descrive il contesto e suggerisce fix con `G[u][v][key]` o iterazione esplicita sugli edge.
- **keyword/entità:** graphify · MultiGraph · ValueError · edge access · NetworkX · bug · Issue #305

---

### Build an MCP server (TypeScript) — Tutorial ufficiale
- **source_id:** 71dca4dc-0c00-4c74-9f73-e26e3ce64607 · **tipo:** url
- **sostanza:** Tutorial ufficiale modelcontextprotocol.io per costruire un MCP server in TypeScript da zero: uso di `McpServer`, schema tools con Zod, trasporto stdio, test con mcp-inspector, integrazione con Claude Desktop tramite configurazione JSON. Esempio weather server con tool `get-forecast`.
- **keyword/entità:** MCP server · TypeScript · McpServer · Zod · stdio · mcp-inspector · Claude Desktop · JSON-RPC · tool definition

---

### Build an MCP server (multi-language quickstart) — Docs ufficiali
- **source_id:** fd4f43e3-5b9f-42c4-95c9-16527fd476e2 · **tipo:** url
- **sostanza:** Documentazione ufficiale MCP per costruire un server weather in TypeScript, Python e Kotlin; copre StdioServerTransport, handler per `list_tools` e `call_tool`, integrazione con Claude Desktop. File di testo di 96KB con tutorial completo multi-linguaggio.
- **keyword/entità:** MCP · TypeScript · Python · Kotlin · weather server · StdioServerTransport · list_tools · call_tool · Claude Desktop

---

### Build with Agent Skills — Docs Claude Code
- **source_id:** 7ba5b592-1e25-4fc4-bfc9-2e6cc47c6be2 · **tipo:** url
- **sostanza:** Guida ufficiale Claude Code su come costruire e usare le Agent Skills: struttura SKILL.md con frontmatter YAML, campo `context: fork`, `allowed-tools`, `when_to_use`, `disable-model-invocation`. Spiega MCPB bundles e come le skills si compongono con subagents e hook.
- **keyword/entità:** Agent Skills · SKILL.md · YAML frontmatter · context fork · allowed-tools · MCPB bundles · Claude Code

---

### TypeScript vs Python MCP server Hello World — Blog comparison
- **source_id:** a9baedff-92cf-4e44-862a-b78d39c88f27 · **tipo:** url
- **sostanza:** Post blog che confronta la scrittura di un MCP server minimale Hello World in TypeScript (SDK ufficiale) e Python (FastMCP). Evidenzia differenze sintattiche, verbosità, decoratori `@mcp.tool()` in Python vs classe McpServer in TypeScript, e workflow di test.
- **keyword/entità:** MCP server · TypeScript SDK · Python · FastMCP · Hello World · @mcp.tool() · McpServer · confronto

---

### safishamsi/graphify — GitHub Actions CI workflow runs
- **source_id:** 972d5f49-0f75-4db2-9ed3-f73c25c7e869 · **tipo:** url
- **sostanza:** Pagina GitHub Actions di safishamsi/graphify con oltre 1057 run CI elencati; mostra lo storico di build, test e release del progetto. Dà visibilità sulla cadenza di sviluppo e sull'infrastruttura di CI usata (Ubuntu, matrix Python, pytest).
- **keyword/entità:** graphify · GitHub Actions · CI · pytest · Ubuntu · release cadenza · safishamsi

---

### Claude Agent SDK — Subagents, sessioni, query() patterns (blog Kyle Redelinghuys)
- **source_id:** f0c18857-5562-418b-a0bc-bc85dae9d46d · **tipo:** url
- **sostanza:** Blog post tecnico sull'Agent SDK: pattern di uso di `query()` come generatore asincrono, gestione sessioni con session_id, creazione subagenti, esempi di streaming eventi. Illustra come costruire pipeline multi-agente con Claude programmaticamente.
- **keyword/entità:** Claude Agent SDK · query() · subagents · session_id · streaming · multi-agent · Kyle Redelinghuys

---

### Claude Code Auto-Memory — Milvus blog
- **source_id:** 687ce154-f1a6-4823-bf8f-5dc4c0f3a29e · **tipo:** url
- **sostanza:** Articolo Milvus che spiega il sistema di memoria di Claude Code: CLAUDE.md come memoria dichiarativa, Auto Memory (MEMORY.md 200 righe/25KB), Auto Dream, architettura KAIROS per memory management, integrazione con memsearch (Zilliz/Milvus) per ricerca cross-agent vettoriale.
- **keyword/entità:** Claude Code · CLAUDE.md · Auto Memory · MEMORY.md · Auto Dream · KAIROS · memsearch · Milvus · Zilliz · vector search

---

### Skills vs Subagents — DEV.to
- **source_id:** 632eef4e-6f37-4c0a-b28b-9491af16b1d9 · **tipo:** url
- **sostanza:** Articolo DEV.to che confronta Skills e Subagents in Claude Code con l'analogia "ricette vs colleghi". Skills aggiungono expertise al contesto corrente; Subagents hanno finestre di contesto separate. Include albero decisionale per scegliere l'approccio corretto.
- **keyword/entità:** Skills · Subagents · Claude Code · context window · albero decisionale · ricette vs colleghi

---

### Skills vs Spawned Subagents — Reddit r/ClaudeCode
- **source_id:** ff8d97d2-a21a-4dce-ae50-d7ef97a9c87f · **tipo:** url
- **sostanza:** Thread Reddit su r/ClaudeCode che discute le differenze pratiche tra skills e subagents spawned; introduce il concetto di architettura filesystem-hub e come i subagents con file-based AGENT.md possono ora usare `skills:` in frontmatter.
- **keyword/entità:** Skills · Subagents · Claude Code · filesystem-hub · AGENT.md · r/ClaudeCode · frontmatter skills

---

### Claude Code vs Claude Agent SDK — Augment Code
- **source_id:** c19348d3-7acb-415a-97c0-aa7ea8ef4e0f · **tipo:** url
- **sostanza:** Articolo Augment Code che chiarisce la relazione tra Claude Code CLI e il Claude Agent SDK: condividono lo stesso harness agentico (agentic loop), con la differenza che Claude Code è la CLI consumer-facing e l'SDK è la libreria per uso programmatico embedded.
- **keyword/entità:** Claude Code · Claude Agent SDK · agentic loop · CLI · libreria · Augment Code · harness

---

### Claude Code vs GitHub Copilot — Milvus
- **source_id:** 7e4a928e-e2cb-4dbd-a3d9-0c7d41ab4e85 · **tipo:** url
- **sostanza:** Confronto Milvus tra Claude Code (agente autonomo da terminale) e GitHub Copilot (assistente IDE-native). Analizza capacità di esecuzione autonoma, gestione contesto, integrazione MCP, stili di interazione e casi d'uso ottimali per ciascuno.
- **keyword/entità:** Claude Code · GitHub Copilot · autonomo · IDE-native · MCP · confronto · Milvus

---

### Connect Claude Code to MCP servers — Docs ufficiali
- **source_id:** 1e0d2cf1-6c78-4af0-a57e-b4c218bb5a37 · **tipo:** url
- **sostanza:** Documentazione ufficiale Claude Code per connettere server MCP: scopes (local/project/user), precedenza delle configurazioni, timeout, gestione degli errori. File ~54KB con istruzioni complete su claude mcp add, configurazione JSON e ambienti.
- **keyword/entità:** Claude Code · MCP · scopes · precedenza · timeout · claude mcp add · configurazione JSON

---

### Connect Claude Code to MCP servers — Docs ufficiali [duplicato]
- **source_id:** 842c030f-3284-4c78-9cf8-40f3b0cefd7a · **tipo:** url
- **sostanza:** Contenuto identico a `1e0d2cf1`: documentazione ufficiale su come connettere Claude Code a server MCP, scopes, configurazioni e timeout. Presente due volte nel notebook con ID diverso.
- **keyword/entità:** Claude Code · MCP · scopes · timeout · duplicato di 1e0d2cf1

---

### Create custom subagents — Docs ufficiali Claude Code
- **source_id:** 53e24af2-1cbc-4e0c-887f-7b86b15e4f59 · **tipo:** url
- **sostanza:** Documentazione ufficiale Claude Code per creare subagenti custom: struttura AGENT.md in `.claude/agents/<name>/`, campi frontmatter (description, tools, skills, allowed-tools), contesti isolati, permessi. File ~74KB con esempi di subagenti specializzati e pattern di orchestrazione.
- **keyword/entità:** Claude Code · subagents · AGENT.md · .claude/agents/ · frontmatter · tool permissions · orchestrazione · context isolation

---

### Flutter Dart MCP server — Docs ufficiali Flutter
- **source_id:** 7f43f08b-e7f4-4d44-87bd-00ef92a27eec · **tipo:** url
- **sostanza:** Documentazione ufficiale Flutter/Dart sul server MCP integrato: comando `dart mcp-server`, configurazione con Gemini, Cursor, VS Code Copilot. Descrive le capabilities esposte (file system, pub, flutter tools) e come registrarlo nei vari ambienti di sviluppo.
- **keyword/entità:** Flutter · Dart · MCP server · dart mcp-server · Gemini · Cursor · VS Code Copilot · pub

---

### Architettura Claude Code — Documento sintetico completo
- **source_id:** ac776e45-cfef-4660-b0ef-1d97f20f3498 · **tipo:** text
- **sostanza:** Documento sintetico completo sull'architettura di Claude Code: Agent SDK loop (gather→act→verify), primitivi MCP (Tools/Resources/Prompts), Skills vs Subagents, pattern multi-agent, gerarchia memoria (CLAUDE.md, MEMORY.md, .claude/rules/), hooks, settings layers.
- **keyword/entità:** Claude Code · Agent SDK · agentic loop · MCP · Skills · Subagents · CLAUDE.md · MEMORY.md · hooks · settings layers · multi-agent

---

### Enterprise-Grade MCP Security — arXiv paper (Narajala/Habler)
- **source_id:** 01ec67da-4ade-4a1a-929d-41a9e7c8c1b8 · **tipo:** url
- **sostanza:** Paper arXiv di Narajala e Habler su sicurezza MCP enterprise: catalogo attacchi (tool poisoning, prompt injection, data exfiltration), architettura Zero Trust applicata a MCP, difesa in profondità (input validation, output sanitization, permission scoping, monitoring), framework di valutazione del rischio.
- **keyword/entità:** MCP security · tool poisoning · Zero Trust · prompt injection · defense-in-depth · arXiv · Narajala · Habler · enterprise · risk framework

---

### Extend Claude Code — Overview docs
- **source_id:** 972aa619-2e49-4a1f-97f8-4da7e226a3e0 · **tipo:** url
- **sostanza:** Panoramica ufficiale di tutte le modalità di estensione di Claude Code: CLAUDE.md per memoria progetto, Skills, Subagents, Agent teams, MCP come livello di integrazione esterna, Hooks per eventi del ciclo agentico, Plugins. Pagina indice con link a tutte le guide specifiche.
- **keyword/entità:** Claude Code · CLAUDE.md · Skills · Subagents · Agent teams · MCP · Hooks · Plugins · estensione

---

### Extend Claude with skills — Guida completa
- **source_id:** 14610704-b44c-460e-a1c9-bb9e6fc10985 · **tipo:** url
- **sostanza:** Guida completa ufficiale su come estendere Claude Code con skills: struttura frontmatter YAML di SKILL.md, campi `context` (fork/include), `allowed-tools`, `when_to_use`, `disable-model-invocation`, installazione via `graphify install`, composizione con subagents. File ~50KB.
- **keyword/entità:** Claude Code · Skills · SKILL.md · YAML frontmatter · context fork · allowed-tools · when_to_use · installazione · composizione

---

### Issue #919 — Feature request: CLI flags super-hub clustering
- **source_id:** 0a2f03e6-86cd-4d1c-b1e8-d81abd4ab47e · **tipo:** url
- **sostanza:** Issue GitHub graphify #919 aperta da neo1777: richiesta di flag CLI per gestire community a bassa coesione causate da super-hub. Propone `--exclude-hubs P` (esclude nodi con grado > percentile P dal partizionamento Leiden) e `--resolution N` per granularità. Implementato in v0.8.10.
- **keyword/entità:** graphify · Issue #919 · super-hub · --exclude-hubs · --resolution · Leiden · clustering · neo1777 · v0.8.10

---

### Issue #919 — Feature request: CLI flags super-hub clustering [duplicato]
- **source_id:** c2d78e2e-44fa-4a93-beeb-5af3af15d73a · **tipo:** url
- **sostanza:** Contenuto identico a `0a2f03e6`: Issue #919 graphify su CLI flags per super-hub clustering. Presente due volte nel notebook con ID diverso.
- **keyword/entità:** graphify · Issue #919 · super-hub · --exclude-hubs · --resolution · duplicato di 0a2f03e6

---

### NousResearch/hermes-agent — GitHub repository
- **source_id:** 10a4b00e-ca74-45c6-9e6d-c6ac27f94c6d · **tipo:** url
- **sostanza:** Repository GitHub di hermes-agent (NousResearch): agente autonomo persistente multi-piattaforma (Telegram, Discord, Slack, WhatsApp, Signal) con memoria persistente, sandboxing Docker/SSH/Singularity, generazione automatica di skills, architettura modulare a subagenti. MIT license, Python. Versione v0.9.0+ con notify_on_complete, MiMo v2 Pro backend.
- **keyword/entità:** hermes-agent · NousResearch · autonomous agent · persistent memory · Telegram · Discord · Docker · SSH · Singularity · skills generation · multi-platform · MIT

---

### morrolinux/morros — Custom bootc Fedora distro
- **source_id:** ff8cf618-3d2a-4b05-8d49-0e81c6ddb14b · **tipo:** url
- **sostanza:** Repository GitHub morrolinux/morros: distro Linux immutabile personalizzata basata su Fedora Atomic e Universal Blue. Usa OCI image (bootc), Containerfile per build, Justfile per automazione, cosign per firma delle immagini. Base: Origami Linux.
- **keyword/entità:** morrolinux · bootc · Fedora Atomic · Universal Blue · OCI image · Containerfile · Justfile · cosign · Origami Linux · immutable distro

---

### safishamsi/graphify — README principale
- **source_id:** 1a93fc49-07ba-4e82-a2d3-b13dfdc6d5c0 · **tipo:** url
- **sostanza:** README completo di graphify (53k stelle): skill AI per coding assistant che converte interi codebase in knowledge graph interrogabile. Copre installazione (uv/pipx), piattaforme supportate (Claude Code, Codex, Cursor, Gemini CLI, ecc.), comandi (extract, cluster-only, query, explain, path, prs), server MCP stdio, privacy policy.
- **keyword/entità:** graphify · knowledge graph · AI skill · tree-sitter · Leiden · MCP server · graphify prs · privacy · uv · pipx · 53k stars

---

### zeroclaw-labs/zeroclaw — GitHub repository
- **source_id:** 022bbb92-d2ff-4e2d-9c45-a1e4bed3febc · **tipo:** url
- **sostanza:** Repository GitHub zeroclaw-labs/zeroclaw: infrastruttura Rust per assistente personale AI autonomo, multi-OS, multi-piattaforma. Architettura multi-agent runtime con schema V3, supporto build selettivo per canali (features Cargo), Dockerfile per deploy. "Deploy anywhere, swap anything."
- **keyword/entità:** zeroclaw · Rust · autonomous AI · multi-agent runtime · schema V3 · Cargo · Docker · cross-platform · zeroclaw-labs

---

### Claude Code Glossario — Docs ufficiali
- **source_id:** eb544dcf-94f6-4a6e-9a7e-2e4d41bc0a61 · **tipo:** url
- **sostanza:** Glossario ufficiale Claude Code con definizioni di: agentic loop, compaction, CLAUDE.md, hooks, MCP, MCP Tool Search, subagent, skill, session, settings layers (project/user/local/enterprise). Fonte autorevole per terminologia ufficiale del sistema.
- **keyword/entità:** Claude Code · glossario · agentic loop · compaction · CLAUDE.md · hooks · MCP Tool Search · subagent · skill · settings layers

---

### GoPenAI — Graphify article
- **source_id:** e57d27b5-d2b6-415c-b78f-6ebb34b2c24e · **tipo:** url
- **sostanza:** Articolo GoPenAI su graphify — contenuto bloccato da Cloudflare challenge page (508 caratteri ricevuti). Titolo suggerisce una panoramica del tool, ma il contenuto effettivo non è accessibile.
- **keyword/entità:** graphify · GoPenAI · Cloudflare blocked · non accessibile

---

### Hermes Agent — Landing page NousResearch
- **source_id:** e32f0e84-7f2e-4a34-adef-2ed5b1f3e2a3 · **tipo:** url
- **sostanza:** Landing page pubblica di Hermes Agent (NousResearch): agente autonomo MIT con interfacce multi-piattaforma (Telegram/Discord/Slack/WhatsApp/Signal), sandboxing Docker/SSH/Singularity, memoria persistente e generazione automatica di skills. Enfasi su autonomia e crescita dell'agente nel tempo.
- **keyword/entità:** Hermes Agent · NousResearch · MIT · Telegram · Discord · Docker · persistent memory · auto-generated skills · autonomy

---

### Transcript — Sessione GDR 1777 + scambio sulla tastiera (YouTube)
- **source_id:** 8aaf54e4-7432-49e8-808c-4a8e0bd0edc8 · **tipo:** youtube
- **sostanza:** Trascrizione del video di morrolinux "Ho creato LA MIA DISTRO" (italiano): racconta la creazione di una distro Fedora immutabile custom basata su Origami Linux con window manager Niri e DunK Material Shell, pipeline di build con bootc/OCI e GitHub Actions per rebuild giornaliero automatico.
- **keyword/entità:** morrolinux · Origami Linux · Fedora immutabile · bootc · OCI · Niri · DunK Material Shell · GitHub Actions · rebuild automatico · distro custom

---

### How Claude Code works — Docs ufficiali
- **source_id:** 285d66d6-f6fd-474b-9d52-bca0dd6abc46 · **tipo:** url
- **sostanza:** Documentazione ufficiale su come funziona Claude Code: ciclo agentico (gather→act→verify), categorie di tool (bash, file read/write, MCP, search), gestione sessioni, context window, checkpoints, sistema di permessi per azioni distruttive.
- **keyword/entità:** Claude Code · agentic loop · gather act verify · tools · sessioni · context window · checkpoints · permessi

---

### How Claude remembers your project — Docs ufficiali
- **source_id:** f3b11da0-de6b-4d03-b1ae-2c74c91f5b04 · **tipo:** url
- **sostanza:** Documentazione ufficiale sulla gerarchia di memoria di Claude Code: CLAUDE.md managed/user/project/local, CLAUDE.local.md per esclusione da git, `.claude/rules/` per regole path-specifiche, Auto Memory (MEMORY.md, cap 200 righe/25KB).
- **keyword/entità:** CLAUDE.md · CLAUDE.local.md · .claude/rules/ · Auto Memory · MEMORY.md · 200 righe · 25KB · project memory · path-specific rules

---

### How to Use MCP with Flutter and Dart — freeCodeCamp
- **source_id:** e35045e2-9e64-4e2b-8bfb-0f1e63e98fe6 · **tipo:** url
- **sostanza:** Tutorial freeCodeCamp sull'implementazione di MCP con Flutter/Dart: pacchetto `dart_mcp`, classe `MCPServer` con mixin `ToolsSupport`/`ResourcesSupport`, `StdioServerTransport`, `registerTool`, connessione client con `MCPClient.connectStdioServer`. Esempio pratico completo.
- **keyword/entità:** Flutter · Dart · dart_mcp · MCPServer · ToolsSupport · ResourcesSupport · StdioServerTransport · registerTool · MCPClient · freeCodeCamp

---

### Claude Code Auto-Memory in automation workflows — XDA Developers
- **source_id:** ffb75980-7ad2-45f3-b8e6-e37dc6476c77 · **tipo:** url
- **sostanza:** Articolo XDA su come Claude Code memory (Auto Memory + CLAUDE.md) può essere sfruttata in workflow di automazione tipo n8n; discute anche l'uso del CLI Claude Code in pipeline automatizzate e l'alternativa MCP per l'accesso alla memoria.
- **keyword/entità:** Claude Code · Auto Memory · CLAUDE.md · n8n · automazione · MCP · workflow · XDA Developers

---

### Il Palantír del Codice — Mappatura RPG/GDR dei progetti
- **source_id:** 6140f025-c1a0-46c9-8b0c-74b6ba39ba63 · **tipo:** text
- **sostanza:** Documento narrativo in italiano che mappa i progetti software OSS1777/BOOK1777/Aurora1777 come personaggi in un GDR fantasy ispirato a Tolkien, con sistema GiRSA/MERP, seed 1777, Issue #919 come "mito fondante". Usa la metafora del doppio metaverso (realtà + Tolkien) per documentare l'architettura di progetto.
- **keyword/entità:** GDR · Tolkien · MERP · GiRSA · seed 1777 · OSS1777 · BOOK1777 · Aurora1777 · Issue #919 · doppio metaverso · narrativa

---

### Introducing MCP — Blog Anthropic (novembre 2024)
- **source_id:** 23095fad-d9bf-4ca7-9e7a-b5a43ec5e2c4 · **tipo:** url
- **sostanza:** Post ufficiale Anthropic che annuncia MCP come standard aperto (novembre 2024): server pre-costruiti per Google Drive, Slack, GitHub, PostgreSQL, Puppeteer; early adopters Block e Apollo; supporto da Zed, Replit, Codeium, Sourcegraph. Prima presentazione pubblica del protocollo.
- **keyword/entità:** MCP · Anthropic · annuncio · Google Drive · Slack · GitHub · PostgreSQL · Block · Apollo · Zed · Replit · Codeium · Sourcegraph · open standard

---

### What is MCP — modelcontextprotocol.io intro
- **source_id:** 386642f2-a77d-4b5d-8e75-00b5aadebb3c · **tipo:** url
- **sostanza:** Pagina introduttiva ufficiale di modelcontextprotocol.io: analogia USB-C, tre primitivi (Tools/Resources/Prompts), ruoli clients/servers/hosts, ecosistema in crescita. Punto di ingresso canonico per chi si avvicina a MCP.
- **keyword/entità:** MCP · USB-C analogy · Tools · Resources · Prompts · clients · servers · hosts · ecosistema

---

### MCP Explained — CodiLime
- **source_id:** a2fc04b6-49f3-45d6-8cca-8e59eb8b3614 · **tipo:** url
- **sostanza:** Articolo tecnico CodiLime (~54KB) che spiega MCP in dettaglio: architettura client/server, flusso dei messaggi con diagrammi, feature di elicitation (richiesta info aggiuntive al runtime), JSON-RPC come trasporto, human-in-the-loop come principio di sicurezza.
- **keyword/entità:** MCP · CodiLime · elicitation · JSON-RPC · message flow · client/server · human-in-the-loop · architettura

---

### Claude Code Docs Overview — Installazione e superfici
- **source_id:** 38f28f4b-0e55-4059-a9d8-f8da07fef024 · **tipo:** url
- **sostanza:** Pagina overview della documentazione Claude Code: installazione (curl/Homebrew/WinGet), superfici disponibili (terminale, VS Code, desktop, web, JetBrains), lista di capacità, integrazione MCP, skills, hooks, subagents, agent teams.
- **keyword/entità:** Claude Code · installazione · curl · Homebrew · WinGet · VS Code · JetBrains · MCP · skills · hooks · subagents · agent teams

---

### Protocollo Coding Wizard — SKILL.md Dart/Flutter
- **source_id:** 8e7581ba-e0e1-489e-97e8-0e6f5c45cbae · **tipo:** text
- **sostanza:** File SKILL.md personalizzato per un subagente senior Dart/Flutter con `context: fork`, `allowed-tools`, integrazione dart_mcp, e direttiva speciale per gestire il "rumore hardware" (refusi di tastiera dell'utente come errori fisici non semantici).
- **keyword/entità:** SKILL.md · Dart · Flutter · context fork · allowed-tools · dart_mcp · hardware noise · typos · senior developer · subagent

---

### Protocollo Game Master — SKILL.md RPG/codice
- **source_id:** c1881db1-a0ad-4a97-9b44-64793c6b1c7e · **tipo:** text
- **sostanza:** File SKILL.md per un Game Master RPG che mappa progetti software su personaggi GDR (sistema GiRSA/MERP), con seed 1777, metafora doppio mondo (realtà + Tolkien), argomenti `sistema_gioco` e `metaverso`. Usato per sessioni narrative/creative integrate con il codebase.
- **keyword/entità:** SKILL.md · GDR · GiRSA · MERP · seed 1777 · Tolkien · Game Master · sistema_gioco · metaverso · narrativa

---

### safishamsi/graphify — Changelog releases v0.8.7–v0.8.18
- **source_id:** b6e510ee-e7ab-44be-ae13-3b78aa5b9819 · **tipo:** url
- **sostanza:** Pagina GitHub releases di graphify dal v0.8.7 al v0.8.18: aggiunta subcommand `graphify prs` (dashboard PR con CI state, review, worktrees), flag `--conflicts` e `--triage`, tools MCP `list_prs`/`get_pr_impact`/`triage_prs`, fix C++, fix Leiden, backend DeepSeek, `--resolution` e `--exclude-hubs` in v0.8.10.
- **keyword/entità:** graphify · releases · graphify prs · --conflicts · --triage · MCP tools · list_prs · get_pr_impact · --resolution · --exclude-hubs · v0.8.10 · v0.8.18

---

### Safi Shamsi — GitHub Profile
- **source_id:** f8decdf8-5b11-4fae-bbb6-4fc34ee7a72e · **tipo:** url
- **sostanza:** Profilo GitHub di Safi Shamsi (safishamsi): AI Research Engineer, MSc Data Science (Distinction) University of Birmingham, presentazione orale MICAD 2025, autore di graphify (53k stelle, 450k+ download PyPI), primo posto hackathon FirstSight, progetto mycetoma-kg-rag, libro "The Memory Layer", graphifylabs.ai.
- **keyword/entità:** Safi Shamsi · AI Research Engineer · Birmingham · MICAD 2025 · graphify · 450k downloads · mycetoma-kg-rag · The Memory Layer · graphifylabs.ai · FirstSight hackathon

---

### Issue #92 — ModuleNotFoundError con pipx (graphify)
- **source_id:** a55f09bc-4dfe-4b82-8b82-84d23dc64dca · **tipo:** url
- **sostanza:** Issue GitHub #92 di graphify: la pulizia di `.graphify_python` nel passo 9 del processo di estrazione causa `ModuleNotFoundError` nelle invocazioni successive quando si usa pipx. Risolto in v0.3.16 non eliminando il file tra le esecuzioni.
- **keyword/entità:** graphify · Issue #92 · pipx · ModuleNotFoundError · .graphify_python · v0.3.16 · fix

---

### Flutter/Dart MCP Server — Blog Flutter (Cloudflare blocked)
- **source_id:** 1c482b48-c04c-4bc7-aae3-5b4f8d12f9f6 · **tipo:** url
- **sostanza:** Articolo blog Flutter/Dart sull'MCP Server — contenuto bloccato da Cloudflare challenge page (508 caratteri ricevuti). Il titolo suggerisce una trattazione del server MCP per Flutter/Dart, ma il contenuto effettivo non è accessibile.
- **keyword/entità:** Flutter · Dart · MCP Server · Cloudflare blocked · non accessibile

---

### Ultimate Guide MCP Part 4 — Python FastMCP Tutorial (Sid Bharath)
- **source_id:** 6ec9a0b8-1fb3-4d7c-a6ae-9d2cef35af83 · **tipo:** url
- **sostanza:** Quarta parte della serie MCP di Sid Bharath: tutorial pratico con FastMCP in Python per creare NoteKeeper server con SQLite, esposizione di tools e resources, test con mcp-inspector, connessione a Claude Desktop/Code. Confronto SDK Python vs TypeScript.
- **keyword/entità:** MCP · FastMCP · Python · NoteKeeper · SQLite · tools · resources · mcp-inspector · Sid Bharath · SDK confronto

---

### Skills vs Subagents — Reddit r/ClaudeAI
- **source_id:** 7f2f1553-7d53-4e13-9f26-90a14f3d7e9b · **tipo:** url
- **sostanza:** Thread Reddit r/ClaudeAI: skills aggiungono expertise al contesto principale dell'agente; subagents sono worker con finestra di contesto separata. Nota WillieWang: i subagents file-based con AGENT.md possono ora dichiarare `skills:` in frontmatter per combinare i due approcci.
- **keyword/entità:** Skills · Subagents · Claude Code · r/ClaudeAI · context window · AGENT.md · skills frontmatter · WillieWang

---

### Use Claude Code features in SDK — Docs ufficiali
- **source_id:** 18bbcd18-39ab-4e90-9b0c-6f1afe0a0a50 · **tipo:** url
- **sostanza:** Documentazione ufficiale su come usare le feature di Claude Code tramite SDK: tabella settingSources (project/user/local), posizioni di caricamento CLAUDE.md, uso skills nell'SDK (`skills="all"`), hooks programmatici (HookMatcher, PreToolUse, esempio audit_bash), confronto hooks filesystem vs programmatici.
- **keyword/entità:** Claude Code · SDK · settingSources · CLAUDE.md · skills SDK · HookMatcher · PreToolUse · programmatic hooks · audit_bash

---

### What Is Claude Code Auto-Memory — MindStudio
- **source_id:** b685b36c-1ca2-4a74-9c03-f0e39b17c51b · **tipo:** url
- **sostanza:** Articolo MindStudio che spiega il sistema Auto-Memory di Claude Code: CLAUDE.md come "briefing document", tre scope (project/local/user), ciclo di write-back automatico, criteri di selezione (ricorrenza, inferabilità, stabilità, specificità al progetto), distinzione tra context window e file di memoria.
- **keyword/entità:** Claude Code · Auto Memory · CLAUDE.md · briefing document · write-back · ricorrenza · stabilità · specificità progetto · MindStudio · context window

---

### What Is MCP and How It Works — Descope
- **source_id:** 35a771cc-c8f2-43cd-9b82-f17e7b588fcb · **tipo:** url
- **sostanza:** Guida completa Descope su MCP: problema NxM, architettura client/server/host, flusso di una richiesta (handshake, permission request, tool call, result return), nuove funzionalità (sampling, elicitation, roots), ecosistema client (Claude Desktop, Cursor, VS Code, JetBrains, Xcode, Eclipse), considerazioni di sicurezza OAuth 2.1, PKCE, progressive scoping.
- **keyword/entità:** MCP · Descope · NxM problem · sampling · elicitation · roots · OAuth 2.1 · PKCE · progressive scoping · client ecosystem · sicurezza

---

### What is MCP — IBM Think
- **source_id:** 90e0915c-4ae3-458a-9500-414aacba0876 · **tipo:** url
- **sostanza:** Articolo IBM Think su MCP: analogia circuito elettrico/switchboard, architettura host/client/server, trasporti stdio e SSE, primitivi Resources/Tools/Prompts, JSON-RPC 2.0, compatibilità con orchestration framework (LangChain, LangGraph, BeeAI, crewAI). Inquadra MCP come livello di standardizzazione, non come framework agente.
- **keyword/entità:** MCP · IBM · switchboard analogy · stdio · SSE · JSON-RPC 2.0 · Resources · Tools · Prompts · LangChain · LangGraph · BeeAI · crewAI

---

### What is MCP — Google Cloud guide
- **source_id:** 64652321-2a8b-4a8c-9203-289c10d8b269 · **tipo:** url
- **sostanza:** Guida Google Cloud su MCP (~96KB): architettura dettagliata, confronto MCP vs RAG, benefici, sicurezza (OAuth Resource Server, RFC 8707 Resource Indicators), guida alla costruzione e deploy di applicazioni MCP-powered, scelta del server MCP appropriato, ruolo dell'open source.
- **keyword/entità:** MCP · Google Cloud · MCP vs RAG · OAuth Resource Server · RFC 8707 · deploy · open source · sicurezza

---

### cluster-only FileNotFoundError — Issue #934 graphify
- **source_id:** b9ba3c4d-a8ea-4e84-9aab-f9ca53ee134b · **tipo:** url
- **sostanza:** Issue GitHub #934 graphify aperta da neo1777: `cluster-only` crasha con `FileNotFoundError` quando `graphify-out/` non esiste prima dell'invocazione. Root cause: codepath `cluster-only` non chiama `out.mkdir()` prima di scrivere `GRAPH_REPORT.md`, a differenza del codepath `extract`. Fix suggerito: una riga `out.mkdir(parents=True, exist_ok=True)`. Risolto nel commit 076e6b7.
- **keyword/entità:** graphify · Issue #934 · cluster-only · FileNotFoundError · out.mkdir · GRAPH_REPORT.md · neo1777 · v0.8.11

---

### cluster-only FileNotFoundError — Issue #934 graphify [duplicato]
- **source_id:** ed534bc2-380d-4949-9fe3-d04091a55ac0 · **tipo:** url
- **sostanza:** Contenuto identico a `b9ba3c4d`: Issue #934 di graphify su FileNotFoundError in cluster-only. Presente due volte nel notebook con ID diverso.
- **keyword/entità:** graphify · Issue #934 · cluster-only · FileNotFoundError · duplicato di b9ba3c4d

---

### PR #942 — fix cluster-only mkdir (graphify)
- **source_id:** 8ea92ee9-58c2-427f-821a-615761d8047b · **tipo:** url
- **sostanza:** Pull Request #942 di graphify inviata da neo1777: aggiunge `out.mkdir(parents=True, exist_ok=True)` prima del primo write nel codepath `cluster-only`. Merged con miglioramento: mkdir spostata prima ancora della read `labels_path.exists()`. Regression test aggiunto da safishamsi. PR di un first-time contributor.
- **keyword/entità:** graphify · PR #942 · cluster-only · out.mkdir · regression test · neo1777 · safishamsi · first-time contributor

---

### graphify su SkillsLLM
- **source_id:** ac2169a1-f8c9-4fbb-bcd0-36af588b0b2b · **tipo:** url
- **sostanza:** Scheda di graphify sulla piattaforma SkillsLLM (marketplace di AI skills): 52.6k stelle, categoria AI Agents, security report PASSED (pipAuditRan, npmAuditRan), tag (antigravity, claude-code, codex, gemini, graphrag, knowledge-graph, leiden, openclaw, rag, skills, tree-sitter), guida installazione, corsi correlati.
- **keyword/entità:** graphify · SkillsLLM · marketplace · AI Agents · security report · PASSED · knowledge-graph · leiden · 52.6k stars

---

### leehack/flutter-mcp-ai-chat — GitHub repository
- **source_id:** bb814ccd-79f0-4e4d-a1d1-71b1f1fa3757 · **tipo:** url
- **sostanza:** Repository GitHub flutter-mcp-ai-chat (leehack): demo Flutter che implementa un MCP Client in un'app desktop/mobile. Usa il pacchetto `mcp_dart` (pub.dev), gestione API key Gemini, configurazione server MCP stdio multipli con variabili d'ambiente, UI chat con toggle per code block visibility.
- **keyword/entità:** Flutter · MCP Client · mcp_dart · Gemini · stdio · API key · chat app · leehack · GitHub demo

---

### neo1777 — GitHub repositories
- **source_id:** 2b5c550a-67d2-470b-9921-35dc81dc5e75 · **tipo:** url
- **sostanza:** Profilo GitHub di neo1777: lista repository pubblici incluso fork di graphify, hermes-agent, caveman, ai-agents-for-beginners (Microsoft), prototype_brutto (dungeon crawler C++), marzio1777 (TypeScript), bot1777, ftxgridbot1777 (Dart). Identificato come contributor di graphify (Issue #919, #934, PR #942).
- **keyword/entità:** neo1777 · GitHub profile · graphify fork · hermes-agent · caveman · prototype_brutto · C++ · Dart · #IAmDecentralized

---

### graphify Star History — Global Rank #398
- **source_id:** 114f8a77-4dbe-4a1a-9280-229473210926 · **tipo:** url
- **sostanza:** Pagina star-history.com per safishamsi/graphify: 52.1k stelle, rank globale #398 GitHub, creato il 3 aprile 2026, 51 contributor, MIT license, lingua Python. Mostra i primi 42 stargazers e andamento temporale delle stelle.
- **keyword/entità:** graphify · star-history · 52.1k stars · rank #398 · 51 contributors · MIT · Python · Bytebase

---

### safishamsi/graphify (referral corti.com) — README completo
- **source_id:** 5c59ff4d-69b1-44eb-b230-670d9366f670 · **tipo:** url
- **sostanza:** README completo di graphify su GitHub (referral da corti.com): stesso contenuto del README principale con tutti i comandi, piattaforme, extras, privacy, troubleshooting, contributing guide, ARCHITECTURE.md, Penpax (graphifylabs.ai). Versione corrente v0.8.18 con 536 commit sul branch v8.
- **keyword/entità:** graphify · v0.8.18 · README · Penpax · graphifylabs.ai · ARCHITECTURE.md · v8 branch · corti.com referral

---

### graphify v0.8.10 — NewReleases.io
- **source_id:** f615f765-a51e-4521-9d58-47bcedb0b4b0 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.10: changelog include fix git hooks phantom directory (#907), fix save_manifest incremental data loss (#917), fix C++ class inheritance edges (#915), fix cohesion split threshold (#919), fix Rust cross-crate spurious edges (#908), feat `--resolution` e `--exclude-hubs` (#919).
- **keyword/entità:** graphify · v0.8.10 · --resolution · --exclude-hubs · #919 · #917 · #915 · #907 · Rust · C++ · NewReleases.io

---

### graphify v0.8.11 — NewReleases.io
- **source_id:** e0af11fb-4f60-44a3-b1a7-61d764b06783 · **tipo:** url
- **sostanza:** Pagina NewReleases.io per graphify v0.8.11: fix LLM empty choices/None message guard per Gemini e altri provider (#924), fix OpenCode skill invalid agent reference (#911/#825), fix Codex skill con graph artifacts dirty in worktree (#913/#860), perf: precompute degrees in surprise scoring (~11x speedup, #914).
- **keyword/entità:** graphify · v0.8.11 · LLM empty choices · Gemini · OpenCode · Codex · surprise scoring · 11x speedup · #924 · #914

---

### transcript_1777_L1.md — Sessione GDR 1777 + tastiera
- **source_id:** d4f86d52-1b8f-4c5d-a18e-40d8ef79aa74 · **tipo:** text
- **sostanza:** Trascrizione ripulita (livello 1 lossless) di una sessione di conversazione tra Neo e Claude: Neo chiede di mappare i propri progetti software come personaggi GDR in un doppio metaverso (realtà + Tolkien), Claude genera schede personaggio con dadi GiRSA usando seed 1777. Include dichiarazione esplicita sui refusi hardware come rumore non semantico.
- **keyword/entità:** transcript_1777 · GDR · Tolkien · seed 1777 · GiRSA · Neo · Claude · doppio metaverso · refusi hardware · schede personaggio

---

### Issue #1 — v3: semantic query with embeddings (graphify)
- **source_id:** 44633473-5b49-4137-96c6-f447fcf0028e · **tipo:** url
- **sostanza:** Issue #1 di graphify (ancora aperta): proposta di sostituire la ricerca BFS keyword con ricerca semantica basata su embeddings (sentence-transformers, all-MiniLM-L6-v2, cosine similarity). Discussione su architettura LLM-as-librarian vs embedding layer, PR #424 in corso. Collegata a issue successive su cross-language INFERRED edges e case-insensitive call resolution.
- **keyword/entità:** graphify · Issue #1 · semantic query · embeddings · sentence-transformers · all-MiniLM-L6-v2 · cosine similarity · BFS · PR #424 · architettura
