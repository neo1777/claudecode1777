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
