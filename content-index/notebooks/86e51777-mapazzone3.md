# Project OSS1777: mapazzone3 — indice di contenuto
> notebook_id: 86e51777-fc94-4d02-b37b-8b68ed1ec87d · 22 fonti · sessione 2026-06-01

### Archivio Metodologico e Tecnico del Progetto OSS1777
- **source_id:** db02a8b2-d3b3-4f3c-94ec-50da9d45a241  ·  **tipo:** text
- **sostanza:** Proposta ragionata di nomi e descrizioni per nove file `converted-*` (chat esportate) del progetto OSS1777. Per ognuno dà nome parlante e sintesi: genesi issue Graphify, metodo ISSUE/PR, analisi del grafo di marzio1777 (God Nodes, "Patto a 3"), creazione skill, mappature v2/v3, refactor "Dr. Stone".
- **keyword/entità:** OSS1777 · Graphify · marzio1777 · God Nodes · skill contributo-oss · mappatura

### Catalogo e Metodo del Progetto OSS1777
- **source_id:** c5a66a68-6307-415e-b6a5-5b9e28bcbe27  ·  **tipo:** text
- **sostanza:** Catalogo descrittivo completo dei file del corpus: archivi, MAPPA_v3, catalogo-comandi-bash, i `converted-*`, le tre liste (raw/google/embedding), i prompt-definitivi v4/v5.1/v5.2 e i report. Per ciascuno una riga di scopo, orientato a coerenza e significato.
- **keyword/entità:** catalogo file · prompt-definitivo · lista raw/google/embedding · report inventario · OSS1777

### Chat Claude — risoluzione issue Graphify (briefing)
- **source_id:** 79bb6837-b20e-4077-bce5-39b38690b773  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Trascrizione chat tra neo1777 e Claude: lezione su cos'è una issue open-source ben scritta (5 criteri: skimmable, auto-sufficiente, fatti/opinioni, propositiva, una-cosa), il modello mentale GitHub (repo/fork/issue/PR/workflow), e ricognizione del repo safishamsi/graphify (versione, template, issue simili).
- **keyword/entità:** GitHub issue · pull request · fork/upstream/origin · graphify v0.8.8 · Saif Shamsi · feature request

### MAPPA_OSS1777_v3.md
- **source_id:** 81f30562-4984-4011-a61a-95c5264a1290  ·  **tipo:** text
- **sostanza:** Terza mappa esplorativa del Project, da lettura integrale delle due trascrizioni e degli artefatti. Inventario in 6 famiglie, i tre archi (A contributo graphify #919→#934→PR #942, B costruzione metodo, C valutazione skill+kit), stato attuale, fili aperti (ondata 2 `--edge-weight-mode`), incoerenze e indice "dov'è X" riga per riga.
- **keyword/entità:** issue #919/#934 · PR #942 · super-hub · cohesion 0.05 · ondata 2 · contributo-oss · arco A/B/C

### Mappa id - lista di (neighborid, edgedata)
- **source_id:** 791bd7f4-b0c4-48be-b1cd-ebaa74d4dbae  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Titolo fuorviante: è la trascrizione della chat "risoluzione issue Graphify con briefing tecnico" (share 2957f1e2, via proxy Jina). Stesso contenuto della fonte 79bb6837 ma versione lunga ~862 KB: lezione issue/PR, fondamenti GitHub, e training sul workflow PR a 10 step fino al pre-prompt skill (Punto 6).
- **keyword/entità:** briefing Graphify · workflow PR · fork/branch/commit · issue #934 · prompt-madre Punto 6 · neo1777

### Mappa id - lista di (neighborid, edgedata)
- **source_id:** 947d7660-c182-4f2e-9f67-a30b5a55c2cb  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Duplicato (~862 KB, stesso share 2957f1e2) della trascrizione precedente: la chat di briefing/risoluzione issue Graphify estratta via Jina. Contenuto sovrapponibile alla fonte 791bd7f4.
- **keyword/entità:** briefing Graphify · issue/PR · workflow GitHub · duplicato · neo1777

### Mappatura Ontologica e Archeologia del Progetto OSS1777
- **source_id:** 77c06f03-ee0d-4adf-93a2-4e427bfe5092  ·  **tipo:** text
- **sostanza:** Categorizza i file del corpus per ruolo funzionale (Motore=prompt, Diario di bordo=chat, Prodotto=liste/report, Bussola=mappe) e ricostruisce la catena causale in quattro archi (A contributo, B infrastruttura/metaprompt, C mappatura v2/v3, D analisi metodologica v5.1). Segnala anomalie e duplicati.
- **keyword/entità:** ontologia file · arco causale · Motore/Diario/Prodotto/Bussola · metaprompt · MAPPA v3

### catalogo-comandi-bash.md
- **source_id:** 8e172777-2c6c-44a8-882d-17fcc8d15a47  ·  **tipo:** text
- **sostanza:** Raccolta di comandi bash collaudati (Step 3 del prompt v5.1) per il corpus di 8 file: preambolo portabile, ricerca termini, mappa di frequenza, termini orfani, validazione query/chunk, cronologia da timestamp, aggiornamento liste. Include esiti del collaudo reale (graphify 162, PR 70, 119 voci orfane su 325).
- **keyword/entità:** bash/grep/awk · portabilità · LC_ALL UTF-8 · termini orfani · frequenza · JSONL embedding

### lista-embedding-vettoriale.md
- **source_id:** a8f9b324-d041-4358-9543-15b500ea25aa  ·  **tipo:** text
- **sostanza:** Chunk semantici densi (8–40 parole) per database vettoriale/RAG, derivati dalla lista raw. Espone il problema tecnico al centro del corpus (super-hub, cohesion 0.05, bug rounding, le 3 opzioni di #919, fase A ondata 2) e i principi di metodo (verify before modify, release-ready, fonte di verità).
- **keyword/entità:** chunk RAG · super-hub gravitazionale · Leiden/graspologic · exclude_hubs_percentile · edge-weight-mode · verify before modify

### lista-google-search.md
- **source_id:** 87020d28-2f7e-4160-ba46-3f4ef739b63d  ·  **tipo:** text
- **sostanza:** Query brevi (2–6 parole) per motori di ricerca derivate dalla raw, raggruppate per area: graspologic/clustering (cuore fase A), graphify, workflow open source, concetti di analisi grafi, stack marzio1777, metodo. Rimossi identificatori interni al codice.
- **keyword/entità:** graspologic leiden · networkx louvain · GitHub issue best practices · betweenness centrality · Vite bundle · query web

### lista-raw.md
- **source_id:** 0ecf8d1c-c497-4d77-82d5-fcafe7f28a94  ·  **tipo:** text
- **sostanza:** Vocabolario integrale verbatim estratto via grep dagli 8 file del corpus, in 9 categorie (A graphify, B clustering/cluster.py, C bug/rounding, D workflow GitHub, E arco #919→ondata 2, F metodo/skill, G principi, H marzio1777, I persone/repo). Accenti reali preservati; è la somma delle due liste derivate.
- **keyword/entità:** cluster.py · _partition() · cohesion_score() · Leiden/Louvain · #919/#934/#942 · Saif Shamsi · neo1777 · marzio1777

### prompt-definitivo-v4.md
- **source_id:** c6b140ca-65ae-498b-aca5-307260981efd  ·  **tipo:** text
- **sostanza:** Quarta versione del prompt multi-step per analizzare file allegati ed estrarre tre liste (raw, google, embedding). Introduce i due principi portanti: raw come somma di due liste a destinatari diversi, ed estrazione ricorsiva ("senno di poi") con sotto-step di rilettura stepN.0. Incorpora i fix N1–N10.
- **keyword/entità:** prompt multi-step · lista raw/google/embedding · ricorsività · stepN.0 · fix N1-N10 · ricognizione

### prompt-definitivo-v5.1.md
- **source_id:** 0f32df87-d201-49dd-aefc-f6a6f1b975d3  ·  **tipo:** text
- **sostanza:** Evoluzione v5 del prompt: aggiunge l'analisi temporale e stratigrafica del corpus (datare i file, file-dentro-file, frecce causali) e lo Step 4 — dossier ragionato in prosa con stato dei fatti, nodi aperti, decisioni, riferimenti file:punto. Step 1–3 invariati rispetto a v4.
- **keyword/entità:** cronologia/stratigrafia · dossier ragionato · inferenze graduate · semi-doppioni · Step 4 · fonte di verità

### prompt-definitivo-v5_2.md
- **source_id:** abcd8341-5fff-4442-ae40-a32716d8d1a0  ·  **tipo:** text
- **sostanza:** Versione rifinita da un audit su esecuzione reale: scioglie l'ambiguità imponendo la raw strettamente verbatim (i concetti sintetizzati nascono nella lista-embedding), e aggiunge N11–N13 (verifica eseguita non riflessa, "verificato" qualificato con numeri contati, artefatto rivisto = ri-emesso) più la calibrazione metodo/corpus in Step 1.
- **keyword/entità:** raw verbatim · N11/N12/N13 · verifica eseguita · gate orfani · calibrazione corpus · audit

### report-autodiagnosi-sessione.md
- **source_id:** 7f0dd760-bc48-4da0-804d-ddfee245d8ae  ·  **tipo:** text
- **sostanza:** Auto-audit (n=1) dell'esecuzione del prompt v5.1: conformità step per step, cosa è andato bene (cronologia/stratigrafia verificate, collaudo Step 3) e registro errori graduati (A: lista-raw 119/325 voci non-verbatim dichiarata "verificata"; C/D/E sovra-claim minori). Conclude che il metodo era sovradimensionato per 8 file.
- **keyword/entità:** autodiagnosi · n=1 · overclaim verifica · lista-raw 63% conforme · mismatch metodo-corpus · anti-sycophancy

### report-inventario-step1.md
- **source_id:** 7986cd0c-e817-4956-afa7-4a9cdcea28d6  ·  **tipo:** text
- **sostanza:** Step 1 del prompt v5.1: inventario di 8 file (byte, righe, hash SHA256, encoding), cronologia da timestamp interni e suffissi Unix dei `converted-*`, stratigrafia (la "gemella blind" 300581 lanciata dentro la madre 425430, verificata con grep), lettura profonda e vocabolario di dominio quantificato.
- **keyword/entità:** inventario · SHA256 · cronologia 16-22 mag · stratigrafia gemella/madre · god-node · frequenze grep

### source: claude-share
- **source_id:** 04fb9946-8748-48cd-b59f-3152108d2426  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share f71a4cc9, ~102 KB). Neo analizza marzio1777 con graphify: 1501 nodi/2200 edges/147 comunità, God Nodes (useAuth 42, db 34, useRBAC 32), surprising connections, e la Community 0 (86 nodi, cohesion 0.05). Da qui nasce l'idea della issue.
- **keyword/entità:** graphify · marzio1777 · God Nodes · useAuth/useRBAC · cohesion 0.05 · proposeTrackToSession · betweenness

### source: claude-share
- **source_id:** 3990a292-9870-4c33-be9b-efc826644aec  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "SKILLS Project OSS1777" (share 1275fd92): chat di valutazione che decide quali skill servono al Project. Esito: una sola candidata — `contributo-oss` (issue+PR+rapporto maintainer) — con quattro non-skill motivate; poi ricerca in archivio, segnalazione PAT GitHub in chiaro, e costruzione della skill definitiva (8 principi, 3 reference, zip).
- **keyword/entità:** skill contributo-oss · valutazione skill · spiegazione-tecnica/marketing · PAT GitHub · reference #919/#934/#942 · SKILL.md

### source: claude-share
- **source_id:** 48dade6f-90fc-449e-8c69-1b7f7e434682  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share 281040b5, ~102 KB). Variante della genesi: analisi di marzio1777 con graphify, God Nodes e Community 0 a cohesion 0.05, fino al consiglio finale di passare a Claude valore cohesion da graph.json + cluster.py locale + URL raw HEAD per il diff.
- **keyword/entità:** graphify · marzio1777 · God Nodes · cohesion 0.05 · cluster.py · graph.json · diff HEAD

### source: claude-share
- **source_id:** 4ce9f631-891d-4e37-81df-19822fd9a24f  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat-genesi "Analisi grafo architetturale con graphify" (share 281040b5, ~96 KB). Stessa conversazione genesi della fonte 48dade6f (export leggermente più corto): analisi del grafo di marzio1777, diagnosi super-hub, e impostazione del materiale per la chat dedicata alla issue.
- **keyword/entità:** graphify · marzio1777 · super-hub · cohesion · cluster.py · genesi issue · duplicato

### source: claude-share
- **source_id:** 8c13b522-c2d3-4533-837a-e1d3179c7dc1  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "ARCHIVIO OSS1777 ricerca" (share ddb340a7): sessione esplorativa "gemella blind" che mappa il Project. Documenta la lettura integrale a blocchi delle due trascrizioni (genesi + 11.841 righe), la scoperta dell'Arco B nella coda, e la produzione di MAPPA_OSS1777_v3 che parte dalla v2 e la aggiorna.
- **keyword/entità:** chat esplorativa · gemella blind · lettura integrale · Arco B · MAPPA v3 · ondata 2 · 11 trascrizioni

### source: claude-share
- **source_id:** 964aba79-4d2c-46d1-8b2a-e64d650a6029  ·  **tipo:** url (claude.ai/share)
- **sostanza:** Chat "Mappatura esplorativa del Project OSS1777" (share 5979d4a9): produce MAPPA v1→v2 dopo lettura integrale, scarica cluster.py via curl da raw.githubusercontent.com (v8 HEAD, 267 righe), e affina i prompt esplorativo e skill (fix anti-saturazione, COME LEGGERE, regola "mappa a chi la usa, non a chi la produce").
- **keyword/entità:** mappatura esplorativa · MAPPA v2 · cluster.py v8 HEAD · _partition() pesi archi · PROMPT_esplorativo/skill · blind · fix doppio lancio
