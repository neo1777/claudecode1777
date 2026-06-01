## 9b1dafe8 · create1777 — fucina, verbali e domande — [meta] · 5 fonti

### Analisi del metodo — come ragioniamo e lavoriamo (agora, 1 giu 2026)
- **source_id:** 25a954d1-0abc-4da3-a777-da69566bd309 · **tipo:** text (verbale agora)
- **sostanza:** Auto-analisi del metodo di lavoro del "NOI" (i lati di Neo + le voci agora),
  a partire dalla chat sync→agora→prompt MCP. Tesi centrale: il motore è fortissimo nello
  scoprire/diagnosticare/costruire ma strutturalmente debole nel chiudere; la riunione stessa
  riproduce l'asimmetria che diagnostica (apre un fronte mentre ne studia uno aperto).
- **keyword/entità:** anti-sycophancy a doppio taglio · divario di chiusura · meta vs core ·
  over-deliberazione · funzioni-forzanti F1–F4 · PR edge-weight-mode · False Completeness

### Le mille domande — banca ragionata (1 giu 2026)
- **source_id:** 618bc6d2-05f5-473b-be5e-511f47c4543d · **tipo:** text
- **sostanza:** Banca di ~130 domande vere (non mille di riempimento) ordinate in 12 temi:
  metodo/chiusura, now-vs-cautela, core graphify vs meta-infra, create1777, agora come metodo,
  design di agora-comm, i 15 fronti aperti concreti, memoria/continuità, NOI portabile, Neo nel
  metodo, rischi, e le 2 domande-radice. Si pescano per riunione, non si rispondono tutte.
- **keyword/entità:** 130 domande · 12 temi · saldo aperti/chiusi · agora-comm · fronti zombie ·
  named tunnel · over-reliance · sprawl

### Piano aggiornato (v2) — domande, prompt, metodo (agora, 1 giu 2026)
- **source_id:** e281250b-1644-4158-8ce9-f5b676172b2c · **tipo:** text
- **sostanza:** Stato-lavori v2 dopo la sessione operativa: sync masterIndex FATTO e verificato
  (atomico, una sola source); prodotti il prompt coordinamento e il prompt indice-contenuto-profondo.
  Da fare: allargare le mille domande, addendum al verbale, azioni sulle skill (agora1777,
  bibliotecario1777). Introduce la "batteria di angoli" riusabile in riunione.
- **keyword/entità:** sync atomico fatto · prompt coordinamento · deep-index · batteria di angoli
  (concorrenza/provenienza/idempotenza/TOCTOU/failure-mode) · confini · F4 core graphify

### Verbale agora — sessione bibliotecario + domande (1 giu 2026)
- **source_id:** 7bd9ea19-87b8-4be7-8fca-afcf9c399287 · **tipo:** text (verbale agora)
- **sostanza:** Studio della sessione in cui bibliotecario1777 tentò il sync del catalogo:
  parser fallito spacciato per delta (poi corretto), catalogo salvato in formato che non
  sopravvive alla rilettura (tabella markdown appiattita, niente id), sync.py spedito con 2 bug
  noti. Ne ricava azioni per create1777: A1 pre-volo schemi, A2 artefatti robusti, A3 fallback, A4 chiusura atomica.
- **keyword/entità:** bibliotecario1777 · sync.py bug (entries; text+source_type) · errore-castello ·
  artefatto-dato · 47 nb/921 fonti · cura ha bisogno di cura · A1–A4

### now e sync — diagnosi del trasporto (per la discussione, 1 giu 2026)
- **source_id:** 0dba9805-b244-4b5f-8033-7f3c513e64de · **tipo:** text
- **sostanza:** Censimento delle ~11-12 chat in cui il "now e sync" su NotebookLM fu tentato:
  ~4 riuscite, ~8 a metà — tutte per il trasporto, non per il metodo. Causa radice: URL ballerino
  del tunnel trycloudflare che ruota a ogni restart. La ricetta provata: HTTP diretto al gateway,
  schema corretto (text+source_type, tag da entries), verifica prima/dopo, chiusura atomica.
- **keyword/entità:** trycloudflare URL ballerino · named tunnel · canale write · 502 origine giù ·
  HTTP diretto vs tool-MCP · ricetta provata · chiusura atomica add+verify+delete
