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
