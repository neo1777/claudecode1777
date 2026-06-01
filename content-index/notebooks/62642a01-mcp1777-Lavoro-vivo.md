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
