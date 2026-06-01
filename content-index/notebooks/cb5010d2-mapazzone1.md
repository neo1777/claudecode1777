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
