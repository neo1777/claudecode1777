## a0c74710 · estrazione1777 — webtomd + RustDesk MCP (occhi e mani) — [estrazione,mcp] · 6 fonti

### Corpus interno — MCP server, computer-use, sicurezza, pattern RustDesk-like (28 mag 2026)
- **source_id:** 58a97fa5-ffc4-4a99-b510-d418b0b8dd93 · **tipo:** text (~3.7k char)
- **sostanza:** Sintesi cross-notebook (da Claude Code arch, Securing MCP, mcp1777) su come costruire un
  MCP server (FastMCP/TS SDK, trasporti stdio/HTTP, schema tool), computer-use e automazione GUI
  (Playwright/Stagehand, Hermes Agent, AT-SPI, vision/OCR), modello sicurezza Zero Trust (Deny→Ask→
  Allow, sandboxing, hook), pattern mcp1777 a 4 fasi e ponte MCP per app GUI tipo RustDesk.
- **keyword/entità:** FastMCP · stdio/HTTP · computer-use · AT-SPI · Zero Trust · PreToolUse hook ·
  mcp1777 4 fasi · MCP Inspector · blast radius

### PROMPT-GOAL estrazione1777 (sintesi e puntatore al doc completo)
- **source_id:** fd182b22-a639-433e-acd7-8f5442bb9854 · **tipo:** text (~2.4k char)
- **sostanza:** Prompt operativo per Claude Code con due goal sequenziali: GOAL #1 web2md1777 (sistemare
  l'estrazione su casi che falliscono — thinking espandibili `<details>`, shadow DOM, iframe, virtualized);
  GOAL #2 RustDesk+MCP come esplorazione di fattibilità (dossier GO/NO-GO, non codice). Con metodo Neo,
  criteri di accettazione e vincoli "NON fare".
- **keyword/entità:** /goal · web2md1777 · fix/estrazione-completa · thinking espandibile · RustDesk dossier ·
  GO/NO-GO/PIVOT · agora

### PROMPT-GOAL v2 — aggiornamento dopo chat app Agorà (28 mag 2026 sera)
- **source_id:** 83de4c9d-55e9-4a74-b2af-ea3b4af02261 · **tipo:** text (~2.1k char)
- **sostanza:** Aggiornamento v2 del prompt-goal dopo la chat sull'app Agorà: inquadra l'ecosistema a
  4 piani (skill agora1777, app Agorà, infrastruttura estrazione web2md/estrazione1777, RustDesk+MCP).
  Aggiunge dati estetici sull'app desktop Claude (Electron, non Flutter; font Tiempos/Styrene B
  commerciali da non usare; palette terracotta) come riferimento — non template — per Agorà-app.
- **keyword/entità:** ecosistema 4 piani · app desktop Claude Electron · Tiempos/Styrene B · terracotta
  #da7756 · principi UI riusabili · Opus 4.8 da verificare

### PROMPT-GOAL v3 — riscrittura completa con 8 correzioni (28 mag 2026)
- **source_id:** ae5b8097-0f1f-42bd-a7d9-6c094ec42ed7 · **tipo:** text (~2.5k char)
- **sostanza:** Riscrittura v3 (345 righe) con 8 correzioni di Neo: rinomina webtomd→web2md1777, goal
  senza slash, GOAL #1 ora è RICOSTRUZIONE da capo in Flutter/Dart con decisione architetturale esplicita
  (Chrome extension vs Flutter standalone vs Tauri), sezione "usa tutte le skill", notebook di riferimento
  ampliati. Caso emblematico: esportare in Markdown una chat LLM catturando tutto il thinking nascosto.
- **keyword/entità:** v3 · web2md1777 · ricostruzione Flutter/Dart · Chrome extension vs Tauri ·
  decisione architetturale · export chat LLM · skill composte

### Perplexity research — fattibilità web-to-md + RustDesk+MCP (28 mag 2026)
- **source_id:** 1431b036-0bbc-40bd-8b39-95931d9ac375 · **tipo:** text (~3.2k char)
- **sostanza:** Ricerca Perplexity di partenza: repo plausibile AnswerDotAI/web2md, ma senza il repo
  reale di Neo il prompt resta astratto. Su RustDesk+MCP raccomanda di partire da esplorazione (non piano):
  il nodo non è MCP ma il grado di osservabilità/azionabilità in RustDesk; per i casi "DOM non basta"
  servirà vision/OCR, non solo browser headed.
- **keyword/entità:** AnswerDotAI/web2md · Firecrawl · markdowner · esplorazione vs piano · osservabilità ·
  vision/OCR · 2 domande di Claude

### Ricerca web — Estrazione DOM, RustDesk arch, Computer-Use (3 filoni, 28 mag 2026)
- **source_id:** b3c1cb83-6f2d-4dc9-9848-256b2ddc1cbf · **tipo:** text (~5.7k char)
- **sostanza:** Ricerca web a 3 filoni: (A) estrazione DOM — web2md.org (Chrome ext client-side, $9) vs
  Firecrawl (server-side, $188/mo) vs headless browser; (B) architettura RustDesk per wrapper MCP —
  librerie enigo (input) e scrap (capture) riusabili, headless mode, sctgdesk-api-server, 3 strade MCP;
  (C) Anthropic Computer Use API (screenshot/click/key, agent loop al chiamante, RustDesk compatibile).
- **keyword/entità:** web2md.org client-side · Firecrawl · enigo/scrap · sctgdesk-api-server ·
  Computer Use API · agent loop · Browserless+Playwright · 3 strade MCP-su-RustDesk
