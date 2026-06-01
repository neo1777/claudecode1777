# Indice di contenuto profondo — account NotebookLM 1777 — parte 2/6
> Sessione 2026-06-01 · provenienza/metodo nella parte 1/6 · 975 voci totali su 48 notebook · layer di contenuto complementare al catalogo strutturale.

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

---

## NB8 — pushout1777 (1df81168)

### 05_articolo_medium_IT.md — articolo italiano $60
- **source_id:** 2a663f17 · **tipo:** text
- **sostanza:** Articolo italiano per Medium: "Ho speso $60 in Perplexity Pro e ho ottenuto 140k parole di ricerca". Descrive il workflow in 4 step (query esplorativa → audit → buchi → chiusura), 6 principi epistemologici della ricerca profonda, output ~140k parole totali, moduli template riutilizzabili.
- **keyword/entità:** Medium · italiano · $60 · Perplexity-Pro · 4-step · 140k-parole · epistemologia · template

### Chiamata API Perplexity — sessione ricerca graphify
- **source_id:** 9ccf1c0d · **tipo:** text
- **sostanza:** Dump completo della chiamata API Perplexity con sessione di ricerca su graphify/neo1777: analisi issue #919, verifica delle 3 feature implementate in v0.8.10, gap analysis contributori, roadmap identificata (PR#1 rounding fix). Materiale grezzo della ricerca profonda.
- **keyword/entità:** Perplexity-API · graphify · neo1777 · issue-919 · v0.8.10 · gap-analysis · roadmap · PR#1

### Ho speso $60.md — versione italiana rifinita
- **source_id:** 984eeb3d · **tipo:** text
- **sostanza:** Versione rifinita dell'articolo italiano con numeri corretti e prosa migliorata. Stessa struttura del precedente ma con revisioni editoriali: statistiche aggiornate, flusso narrativo ottimizzato, call-to-action finale.
- **keyword/entità:** articolo · italiano · versione-rifinita · numeri-corretti · call-to-action

### I Spent $60 PDF — versione inglese
- **source_id:** bd4c4fad · **tipo:** pdf
- **sostanza:** Versione inglese dell'articolo da Medium in formato PDF. Contiene diversi URL di immagini googleusercontent embedded nel testo. Stessa struttura dell'italiano: workflow 4-step, principi epistemologici, output metrics.
- **keyword/entità:** inglese · PDF · Medium · $60 · workflow · epistemological-principles · EN

### L'Architetto Ombra — documento di validazione
- **source_id:** 0dfbf598 · **tipo:** text
- **sostanza:** Documento che applica il metodo pushout1777 al caso graphify come validazione del metodo stesso. Calcola ROI della ricerca profonda, definisce la struttura del secondo articolo, dimostra la replicabilità del workflow su un soggetto tecnico complesso.
- **keyword/entità:** Architetto-Ombra · validazione · ROI · graphify · secondo-articolo · replicabilità

### analizza le fonti — chat di sintesi
- **source_id:** bd8a9d58 · **tipo:** text
- **sostanza:** Trascrizione di una chat in cui vengono analizzate e sintetizzate tutte le fonti del notebook pushout1777 in preparazione del secondo articolo. Identifica pattern, conferma dati chiave, e definisce l'angolo editoriale per la pubblicazione successiva.
- **keyword/entità:** sintesi · fonti · secondo-articolo · pattern · angolo-editoriale · preparazione

### pushout1777_materiale immagine 1
- **source_id:** f26e0b82 · **tipo:** image
- **sostanza:** Immagine di supporto per il materiale visivo di pushout1777. Provenienza: googleusercontent. Probabilmente screenshot o grafico a supporto degli articoli.
- **keyword/entità:** immagine · materiale-visivo · pushout1777 · screenshot

### pushout1777_materiale immagine 2
- **source_id:** 0a828712 · **tipo:** image
- **sostanza:** Immagine di supporto per il materiale visivo di pushout1777. Provenienza: googleusercontent. Probabilmente screenshot o grafico a supporto degli articoli.
- **keyword/entità:** immagine · materiale-visivo · pushout1777 · screenshot

---

## 2265fb40 · Graphify — raffinamento pesi e algoritmi — [graphify,ondata-2] · 1 fonte

### Raffinamento pesi e algoritmi — schermata chat 1
- **source_id:** 5beaf46f · **tipo:** image
- **sostanza:** Source composto da URL googleusercontent (screenshot di chat/interfaccia). Il contenuto testuale (~3.633 caratteri) è costituito da URL di immagini hosted su googleusercontent che mostrano schermate di discussione sul raffinamento dei pesi e degli algoritmi nell'ambito del progetto Graphify ondata-2. Non è presente testo leggibile oltre ai metadati degli URL immagine.
- **keyword/entità:** Graphify · ondata-2 · raffinamento pesi · algoritmi · screenshot · chat · googleusercontent

---

## 2e1b10f0 · 📚 mcp1777 — Chat pulite L1/L2/L3 — [mcp] · 14 fonti

### 2026-05-25 — Claude web vs Claude Code via Telegram bridge (L2)
- **source_id:** 060a5321 · **tipo:** text
- **sostanza:** Sessione L2 del 25/05: confronto tabellare tra Claude Code e Claude web riguardo ai server MCP disponibili. Claude Code ha Telegram-MCP e NotebookLM-MCP; Claude web accede a GitHub, Drive, Gmail, Notion, Figma, Supabase via connettori. Elencate le 14 skill del bot.
- **keyword/entità:** Claude Code · Claude web · Telegram-MCP · NotebookLM-MCP · 14 skill

### 2026-05-25 — Claude web vs Claude Code via Telegram bridge (L3)
- **source_id:** 31dc5d1f · **tipo:** text
- **sostanza:** Versione in prosa della stessa sessione L3. Approfondisce la distinzione di perimetro tra le superfici e offre verifica concreta su marzio1777 via GitHub MCP.
- **keyword/entità:** perimetro · marzio1777 · GitHub MCP · Claude web · prosa

### 2026-05-25 — mcp1777 genesi 3 superfici (L1)
- **source_id:** 8059bc39 · **tipo:** text
- **sostanza:** L1 della sessione madre del 25/05 (84K caratteri). Documenta il setup completo: installazione notebooklm-mcp, configurazione Telegram bot (@notebookllm1777_bot), cloudflared tunnel, FastMCP Telegram-MCP. Prima sessione fondativa del progetto mcp1777.
- **keyword/entità:** notebooklm-mcp · FastMCP · cloudflared · Telegram bot · sessione fondativa

### 2026-05-25 — mcp1777 genesi 3 superfici (L2)
- **source_id:** c2c044ec · **tipo:** text
- **sostanza:** Riordinato per argomento (26K). Diagnosi del setup, vincolo localhost/cloud, bot Telegram (ID 8871712358, 296 righe), tool workspace_* confinati, documento "a 3 voci", start-all.sh.
- **keyword/entità:** localhost · workspace_* · start-all.sh · bot.py · sessione riordinata

### 2026-05-25 — mcp1777 genesi 3 superfici (L3)
- **source_id:** b82e9760 · **tipo:** text
- **sostanza:** Prosa completa (21K). Fix bug DNS-rebinding in FastMCP (TransportSecuritySettings con enable_dns_rebinding_protection=False). Debiti aperti: rigenerare token Telegram.
- **keyword/entità:** DNS-rebinding · TransportSecuritySettings · FastMCP · token Telegram · bug fix

### 2026-05-26 — comandi hacker Claude Code (L1)
- **source_id:** 54092470 · **tipo:** text
- **sostanza:** Deep research comandi avanzati Claude Code via NotebookLM (28K). Censimento di 7 comandi hacker: /loki-mode, /agento-patronum, /fractal, /skills-janitor, --bare, --dangerously-skip-permissions, /btw. Include tabella HTML e ENV_VARS consolidate.
- **keyword/entità:** /loki-mode · /agento-patronum · /fractal · --dangerously-skip-permissions · ENV_VARS

### 2026-05-26 — comandi hacker Claude Code (L2)
- **source_id:** e6b80d7f · **tipo:** text
- **sostanza:** Versione riordinata (12K). Pattern di selezione fonti in 3 round, output: 7 hacker commands, tabella claude_commands.html, piano All-In 4 fasi, ENV_VARS consolidate.
- **keyword/entità:** claude_commands.html · piano All-In · 3 round · ENV_VARS · hacker commands

### 2026-05-26 — comandi hacker Claude Code (L3)
- **source_id:** a6c4ce40 · **tipo:** text
- **sostanza:** Prosa (10K). La Fase 4 (Troubleshooting) resta aperta come debito operativo della sessione.
- **keyword/entità:** Fase 4 · Troubleshooting · debito operativo · prosa · Claude Code

### 2026-05-27 — kickoff OSS1777 (L1)
- **source_id:** 5ba2cd65 · **tipo:** text
- **sostanza:** Kickoff OSS1777 (13K). Metodo di lavoro codificato, censimento 7 chat (tutte su mcp1777, nessuna su graphify), decisione meta "usa sempre agenti". Prima sessione su OSS1777.
- **keyword/entità:** OSS1777 · kickoff · graphify · agenti · censimento chat

### 2026-05-27 — kickoff OSS1777 (L2)
- **source_id:** 5c28866c · **tipo:** text
- **sostanza:** Riordinato (7K). 3 verdetti onesti: Telegram non attivo (server non risponde), link claude.ai/code non leggibili da NB, metodologia verificata.
- **keyword/entità:** verdetti · Telegram non attivo · claude.ai/code · link · riordinato

### 2026-05-27 — kickoff OSS1777 (L3)
- **source_id:** a56cadf9 · **tipo:** text
- **sostanza:** Prosa (7K). Sessione chiusa con domanda aperta: avvio Telegram-MCP o continuare su Claude Code.
- **keyword/entità:** domanda aperta · Telegram-MCP · continuazione · prosa · OSS1777

### 2026-05-27 — mcp1777 setup memoria (L1)
- **source_id:** f5d4ef52 · **tipo:** text
- **sostanza:** L1 della sessione memoria NotebookLM (93K). Documenta saga permessi Claude Code, auto-memory come surrogato dei permessi, 14 skill del sistema, 9 doc metodo. Bug atlante palantir1777 in ASCII.
- **keyword/entità:** saga permessi · auto-memory · 14 skill · atlante ASCII · bug palantir1777

### 2026-05-27 — mcp1777 setup memoria (L2)
- **source_id:** 148497b3 · **tipo:** text
- **sostanza:** Completo per argomento (29K). Moduli baseline elencati, saga permessi, 8 file auto-memory, cartella dir1777/, INDEX-MEMORIA 7 sezioni, side-quest Graphify, /memoria-aggiorna, vincolo MCP isolato, arsenale 14 skill + 9 doc, bug atlante, handover.
- **keyword/entità:** baseline · dir1777/ · INDEX-MEMORIA · /memoria-aggiorna · handover

### 2026-05-27 — mcp1777 setup memoria (L3)
- **source_id:** 30f18df7 · **tipo:** text
- **sostanza:** Prosa lineare (29K). Decisioni aperte: A1-A4 questionario Neo, pulizia NB ridondanti, MCP isolato, bug atlante. Sessione pronta per /compact.
- **keyword/entità:** A1-A4 · pulizia NB · MCP isolato · /compact · decisioni aperte

---

## 2ee6045c · Graphify — ondata 2 (sviluppo) — [graphify,ondata-2] · 9 fonti

### chat testo grezzo
- **source_id:** 7b738fdd · **tipo:** text
- **sostanza:** Prompt operativo compilato per la chat dell'ondata 2 di OSS1777 (95K). Fusione di PROMPT_start_PR potenziato e template ricognizione-corpus. La chat scopre che gli archi di graphify hanno già un attributo weight (1.0/0.8/0.5 correlato a confidence EXTRACTED/INFERRED/AMBIGUOUS). Verifica architettura peso-archi, mappatura test esistenti, consolidamento disegno PR --edge-weight-mode.
- **keyword/entità:** --edge-weight-mode · weight · confidence · EXTRACTED · graspologic · graphify · PR ondata 2

### ondata 2 (sviluppo) — schermata chat 1
- **source_id:** eaed358b · **tipo:** image
- **sostanza:** Fonte di tipo immagine (URL googleusercontent, 14 URL di screenshot nel contenuto). Schermate della chat di sviluppo ondata 2 — contiene screenshot multipli della sessione di lavoro sulla PR graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine · graphify

### ondata 2 (sviluppo) — schermata chat 2
- **source_id:** 1376c215 · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 3
- **source_id:** 60d07c12 · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 4
- **source_id:** d63597f2 · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 5
- **source_id:** 1f509bfc · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 6
- **source_id:** de1c1e3d · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 7
- **source_id:** 14b7e44a · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 225 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

### ondata 2 (sviluppo) — schermata chat 8
- **source_id:** d5505bf8 · **tipo:** image
- **sostanza:** Fonte di tipo immagine (singolo URL googleusercontent, 223 char). Screenshot della chat di sviluppo ondata 2 graphify.
- **keyword/entità:** screenshot · chat ondata 2 · googleusercontent · immagine

---

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
