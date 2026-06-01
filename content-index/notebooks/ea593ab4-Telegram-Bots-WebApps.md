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
