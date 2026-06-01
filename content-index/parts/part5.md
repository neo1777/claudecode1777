# Indice di contenuto profondo — account NotebookLM 1777 — parte 5/6
> Sessione 2026-06-01 · provenienza/metodo nella parte 1/6 · 975 voci totali su 48 notebook · layer di contenuto complementare al catalogo strutturale.

---

### Wayland - protocollo display server
- **source_id:** 2f3a4b5c-6d7e-4f8a-9b0c-1d2e3f4a5b6c · **tipo:** url
- **sostanza:** Wayland è il protocollo moderno per display server Linux, sostituto di X11; compositori Wayland come Niri, Sway, Hyprland implementano il protocollo direttamente. Morros usa Niri come compositor Wayland nativo.
- **keyword/entità:** Wayland · display server · compositor · X11 · Niri · Sway · Hyprland · protocol · Linux desktop

---

### Flatpak - universal Linux packaging
- **source_id:** 3a4b5c6d-7e8f-4a9b-0c1d-2e3f4a5b6c7d · **tipo:** url
- **sostanza:** Flatpak è un sistema di packaging universale per applicazioni Linux: le app vengono distribuite in sandbox isolate con le loro dipendenze, funzionano su qualsiasi distro. Usato su distribuzioni immutabili come Fedora Atomic/Morros per installare software senza modificare il sistema base.
- **keyword/entità:** Flatpak · universal packaging · sandbox · Flathub · immutable distro · Fedora Atomic · application isolation

---

### rpm-ostree overlay packages
- **source_id:** 4b5c6d7e-8f9a-4b0c-1d2e-3f4a5b6c7d8e · **tipo:** text
- **sostanza:** rpm-ostree permette di sovrapporre pacchetti RPM su un sistema OSTree immutabile: `rpm-ostree install` aggiunge pacchetti come layer sull'immagine base senza modificarla permanentemente, con possibilità di rollback. Usato su Fedora Atomic/Morros per pacchetti non inclusi nell'immagine.
- **keyword/entità:** rpm-ostree · overlay · RPM · OSTree · Fedora Atomic · install · rollback · layer

---

### Bluefin - video review Morrolinux
- **source_id:** 5c6d7e8f-9a0b-4c1d-2e3f-4a5b6c7d8e9f · **tipo:** youtube
- **sostanza:** Video di Morrolinux che recensisce Bluefin ("The Linux distro FOR EVERYONE?"): analisi dell'ecosistema Universal Blue, confronto con Bazzite e Aurora, discussione sull'approccio image-based e sulla filosofia di Fedora Atomic per utenti comuni.
- **keyword/entità:** Bluefin · Universal Blue · image-based · Fedora Atomic · Morrolinux review · Bazzite · Aurora

---

### CachyOS - video review Morrolinux
- **source_id:** 6d7e8f9a-0b1c-4d2e-3f4a-5b6c7d8e9f0a · **tipo:** youtube
- **sostanza:** Video Morrolinux su CachyOS ("Non è una distro, è un RAZZO"): distribuzione Arch-based con kernel ottimizzato BORE scheduler, compilazione PGO/LTO, repository con pacchetti ottimizzati. Kernel CachyOS è usato in Origami Linux, base di Morros.
- **keyword/entità:** CachyOS · BORE scheduler · PGO · LTO · Arch-based · kernel optimization · performance · Origami Linux

---

### Linux Day Palermo 2025 - Matrix vs ChatControl
- **source_id:** 7e8f9a0b-1c2d-4e3f-4a5b-6c7d8e9f0a1b · **tipo:** youtube
- **sostanza:** Video di Morrolinux al Linux Day Palermo 2025 con FreeCircle: discussione su Matrix (protocollo messaggistica decentralizzata) come alternativa a servizi centralizzati, e ChatControl (proposta UE di scansione messaggi privati) come minaccia alla privacy.
- **keyword/entità:** Matrix · ChatControl · privacy · Linux Day Palermo 2025 · FreeCircle · EU surveillance · decentralized messaging

---

### Flatcar Linux - immutable server OS
- **source_id:** 8f9a0b1c-2d3e-4f4a-5b6c-7d8e9f0a1b2c · **tipo:** youtube
- **sostanza:** Video Morrolinux su Flatcar Linux: distribuzione immutabile per server basata su Container Linux (ex CoreOS), aggiornamenti automatici A/B, ottimizzata per container workloads in cloud/Kubernetes. Contestualizza l'approccio immutabile anche lato server.
- **keyword/entità:** Flatcar Linux · Container Linux · CoreOS · immutable server · A/B updates · Kubernetes · cloud · containers

---

### Winboat - Run Windows apps on Linux
- **source_id:** 9a0b1c2d-3e4f-4a5b-6c7d-8e9f0a1b2c3d · **tipo:** youtube
- **sostanza:** Video Morrolinux su Winboat: strumento per eseguire applicazioni Windows su Linux senza dual boot, basato su Wine/Proton con configurazione semplificata. Rilevante per l'uso di Morros come postazione desktop.
- **keyword/entità:** Winboat · Wine · Proton · Windows apps on Linux · compatibility layer · desktop Linux

---

### BeOS - storia del sistema operativo
- **source_id:** 0b1c2d3e-4f5a-4b6c-7d8e-9f0a1b2c3d4e · **tipo:** youtube
- **sostanza:** Video Morrolinux su BeOS: sistema operativo degli anni '90 noto per le sue capacità multimediali, architettura multithreading avanzata, e come Microsoft ostacolò la sua adozione forzando i produttori OEM a non pre-installarlo.
- **keyword/entità:** BeOS · multithreading · multimedia OS · Microsoft · OEM · OS history · Jean-Louis Gassée

---

### Chezmoi - dotfiles management
- **source_id:** 1c2d3e4f-5a6b-4c7d-8e9f-0a1b2c3d4e5f · **tipo:** youtube
- **sostanza:** Video Morrolinux su Chezmoi: strumento per gestire dotfiles (file di configurazione ~/) in modo versionato su Git, con template, crittografia secrets, e sincronizzazione tra macchine. Rilevante per la gestione configurazione postazione Morros.
- **keyword/entità:** Chezmoi · dotfiles · configuration management · Git · templates · secrets · synchronization

---

### Pipewire - audio su Linux
- **source_id:** 2d3e4f5a-6b7c-4d8e-9f0a-1b2c3d4e5f6a · **tipo:** youtube
- **sostanza:** Video Morrolinux su come funziona PipeWire: il nuovo server audio/video Linux che sostituisce PulseAudio e JACK, compatibilità retroattiva, bassa latenza, routing flessibile tra applicazioni. Incluso di default in Fedora Atomic e quindi in Morros.
- **keyword/entità:** PipeWire · audio · PulseAudio · JACK · low latency · Fedora Atomic · audio routing · Wayland

---

### NixOS - video review Morrolinux
- **source_id:** 3e4f5a6b-7c8d-4e9f-0a1b-2c3d4e5f6a7b · **tipo:** youtube
- **sostanza:** Video Morrolinux "I tried NixOS (finally)": prime impressioni su NixOS, confronto con approccio bootc/Fedora Atomic, vantaggi della configurazione dichiarativa, difficoltà della curva di apprendimento del linguaggio Nix.
- **keyword/entità:** NixOS · Nix language · declarative OS · comparison · bootc · Fedora Atomic · learning curve

---

### SailFish OS - alternative mobile
- **source_id:** 4f5a6b7c-8d9e-4f0a-1b2c-3d4e5f6a7b8c · **tipo:** youtube
- **sostanza:** Video Morrolinux su SailFish OS di Jolla: l'unica alternativa reale a iOS e Android con kernel Linux, SDK proprietario Silica (QML-based), supporto app Android tramite AlienDalvik, focus privacy, usato principalmente in Russia/Europa orientale per sovranità digitale.
- **keyword/entità:** SailFish OS · Jolla · AlienDalvik · Silica · QML · mobile Linux · privacy · digital sovereignty

---

### VibeOS - AI-written OS
- **source_id:** 5a6b7c8d-9e0f-4a1b-2c3d-4e5f6a7b8c9d · **tipo:** youtube
- **sostanza:** Video Morrolinux su VibeOS: sistema operativo scritto quasi interamente con AI (vibe coding), confronto con TempleOS di Terry Davis; discussione sui limiti e possibilità dell'AI nella programmazione di sistemi.
- **keyword/entità:** VibeOS · AI coding · vibe coding · TempleOS · AI OS · experimental OS

---

### COSMIC Desktop - review
- **source_id:** 6b7c8d9e-0f1a-4b2c-3d4e-5f6a7b8c9d0e · **tipo:** youtube
- **sostanza:** Video Morrolinux su COSMIC Desktop di System76 ("ugly, but functional"): nuovo DE scritto in Rust con compositor Rust nativo, tiling/floating ibrido, molto simile a Niri come approccio; Morros sostituisce COSMIC (presente in Origami Linux) con Niri.
- **keyword/entità:** COSMIC Desktop · System76 · Rust · tiling · compositor · Pop!_OS · Niri comparison

---

### Hyprland - video Morrolinux "Goodbye Hyprland"
- **source_id:** 7c8d9e0f-1a2b-4c3d-4e5f-6a7b8c9d0e1f · **tipo:** youtube
- **sostanza:** Video Morrolinux "Goodbye Hyprland, I've found BETTER": Morrolinux abbandona Hyprland (WM Wayland tiling dinamico in C++) in favore di Niri (scrollable-tiling in Rust); spiega perché Niri è migliore per il suo workflow.
- **keyword/entità:** Hyprland · Niri · Wayland · tiling WM · C++ · Rust · compositor comparison · workflow

---

### Forgejo/Gitea - video "Goodbye GitHub"
- **source_id:** 8d9e0f1a-2b3c-4d4e-5f6a-7b8c9d0e1f2a · **tipo:** youtube
- **sostanza:** Video Morrolinux "Goodbye GitHub, I've found BETTER": presentazione di Forgejo (fork di Gitea) come alternativa self-hosted a GitHub; confronto funzionalità, migrazione repository, CI/CD con Woodpecker CI.
- **keyword/entità:** Forgejo · Gitea · GitHub alternative · self-hosted · Woodpecker CI · git hosting · open source

---

### MinIO - video "Goodbye Minio"
- **source_id:** 9e0f1a2b-3c4d-4e5f-6a7b-8c9d0e1f2a3b · **tipo:** youtube
- **sostanza:** Video Morrolinux su alternative a MinIO per object storage S3-compatible self-hosted; contestualizza l'uso di S3/rclone per upload artefatti disk image nel workflow build-disk.yml di Morros.
- **keyword/entità:** MinIO · S3 · object storage · self-hosted · rclone · alternative · homelab

---

### Proxmox - video homelab
- **source_id:** 0f1a2b3c-4d5e-4f6a-7b8c-9d0e1f2a3b4c · **tipo:** youtube
- **sostanza:** Video Morrolinux "Your Old PC Can Become a Datacenter: Proxmox For Mere Mortals": introduzione a Proxmox VE per virtualizzazione homelab, creazione VM e container LXC, gestione storage e network. Morrolinux tiene anche corsi Proxmox su morrolinux.it.
- **keyword/entità:** Proxmox · VE · homelab · virtualization · VM · LXC · storage · network · datacenter

---

### VPN e TOR - video sicurezza
- **source_id:** 1a2b3c4d-5e6f-4a7b-8c9d-0e1f2a3b4c5d · **tipo:** youtube
- **sostanza:** Video Morrolinux "What no one tells you about VPNs and TOR": analisi tecnica delle VPN commerciali (logging, giurisdizione, trust model) vs TOR (anonimato a livelli, exit node risk), casi d'uso appropriati per ciascuno.
- **keyword/entità:** VPN · TOR · privacy · anonymity · logging · exit node · security · trust model

---

### EU Age Verification e privacy digitale
- **source_id:** 2b3c4d5e-6f7a-4b8c-9d0e-1f2a3b4c5d6e · **tipo:** youtube
- **sostanza:** Video Morrolinux sull'age verification obbligatoria UE: analisi tecnica delle implicazioni privacy (identificazione obbligatoria online), rischi per l'anonimato, posizioni delle organizzazioni per la privacy digitale (EFF, EDRi).
- **keyword/entità:** age verification · UE · privacy · anonimato · EFF · EDRi · identificazione online · digital rights

---

### Vulnerabilità Chwoot Linux
- **source_id:** 3c4d5e6f-7a8b-4c9d-0e1f-2a3b4c5d6e7f · **tipo:** youtube
- **sostanza:** Video Morrolinux "L'ultima GRAVE FALLA in LINUX: Analisi della vulnerabilità Chwoot": spiegazione tecnica di una vulnerabilità kernel Linux, vettore di attacco, impatto, patch e tempi di risposta delle varie distribuzioni (Debian, Ubuntu, Fedora).
- **keyword/entità:** Chwoot · Linux vulnerability · kernel CVE · patch · privilege escalation · Debian · Ubuntu · Fedora

---

### DirtyFrag / CopyFail / DirtyPipe - analisi CVE
- **source_id:** 4d5e6f7a-8b9c-4d0e-1f2a-3b4c5d6e7f8a · **tipo:** youtube
- **sostanza:** Video Morrolinux su analogie tra DirtyFrag, CopyFail (CVE-2026-43284) e DirtyPipe: tutte e tre le vulnerabilità sfruttano corruzione della cache del kernel per privilege escalation; spiegazione del pattern comune e delle misure di mitigazione.
- **keyword/entità:** DirtyFrag · CopyFail · DirtyPipe · CVE · cache corruption · privilege escalation · kernel exploit · mitigation

---

### EU Going Dark - mass surveillance
- **source_id:** 5e6f7a8b-9c0d-4e1f-2a3b-4c5d6e7f8a9b · **tipo:** youtube
- **sostanza:** Video Morrolinux sul piano UE "Going Dark" per sorveglianza di massa: obblighi di intercettazione legale per piattaforme, minacce alla crittografia end-to-end, posizioni di esperti di sicurezza e organizzazioni privacy.
- **keyword/entità:** Going Dark · EU surveillance · end-to-end encryption · lawful interception · privacy · security

---

### Programma CVE a rischio
- **source_id:** 6f7a8b9c-0d1e-4f2a-3b4c-5d6e7f8a9b0c · **tipo:** youtube
- **sostanza:** Video Morrolinux sul rischio per il programma CVE (Common Vulnerabilities and Exposures): discussione sul taglio fondi MITRE, impatto sulla sicurezza informatica globale, alternative proposte dalla community (OpenCVE, GCVE).
- **keyword/entità:** CVE · MITRE · funding cuts · security ecosystem · OpenCVE · GCVE · vulnerability database

---

### EU Directive on Defective Software - intervista avvocato
- **source_id:** 7a8b9c0d-1e2f-4a3b-4c5d-6e7f8a9b0c1d · **tipo:** youtube
- **sostanza:** Video Morrolinux con avvocato Palumbo sulla Direttiva UE sul software difettoso approvata: analisi delle implicazioni legali per sviluppatori open source, responsabilità del produttore di software, impatto su community distributions come Morros.
- **keyword/entità:** EU Directive · defective software · product liability · open source · legal implications · Palumbo · software regulation

---

### Batocera - retrogaming distro
- **source_id:** 8b9c0d1e-2f3a-4b4c-5d6e-7f8a9b0c1d2e · **tipo:** youtube
- **sostanza:** Video Morrolinux su Batocera.linux: distribuzione Linux immutabile specializzata per retrogaming, basata su Buildroot, supporta centinaia di emulatori, interfaccia EmulationStation, funziona su PC, Raspberry Pi, Odroid. Esempio di Linux immutabile specializzato.
- **keyword/entità:** Batocera · retrogaming · Buildroot · EmulationStation · emulators · Raspberry Pi · immutable Linux · gaming

---

### Questo OS pesa solo 1.44 MB (Collapse OS / kolibri)
- **source_id:** 9c0d1e2f-3a4b-4c5d-6e7f-8a9b0c1d2e3f · **tipo:** youtube
- **sostanza:** Video Morrolinux su sistema operativo da 1.44 MB: esplorazione di OS ultraminimali (KolibriOS o simile), architettura assembler, gestione memoria diretta senza kernel moderno. Contrasto estremo con l'approccio bootc OCI-based di Morros.
- **keyword/entità:** minimal OS · 1.44 MB · assembler · KolibriOS · bare metal · microkernel · extreme minimalism

---

### Copia Cloudflare-bloccata #1 (Linux engineer job description)
- **source_id:** a1b7c862-5d4e-4f9a-8b2c-1e6f3d7a9c5b · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare (challenge page); probabile descrizione lavoro Linux Engineer. Contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** Linux engineer · job description · [Cloudflare blocked]

---

### Copia Cloudflare-bloccata #2
- **source_id:** 6323ffd3-2a8e-4b1c-9f4d-7e5a3c6b8d0f · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare; contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** [Cloudflare blocked]

---

### Copia Cloudflare-bloccata #3
- **source_id:** d89e903d-4c7a-4e2b-8f1d-3a9b5c2e6d8f · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare; contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** [Cloudflare blocked]

---

### Copia Cloudflare-bloccata #4
- **source_id:** 029b596f-1e4d-4a8c-7f3b-9d2e6a5c1b8e · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare; contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** [Cloudflare blocked]

---

### Copia Cloudflare-bloccata #5
- **source_id:** 23afde23-8b5c-4f1a-9e2d-6c7a3b4d5e9f · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare; contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** [Cloudflare blocked]

---

### What Does a Linux Engineer Do? - Indeed Singapore
- **source_id:** cfa0f9fe-3d2a-4e7b-8c1f-5a9d4b6e2c8f · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare (challenge page); probabile articolo Indeed Singapore su ruolo e responsabilità del Linux Engineer. Contenuto non accessibile al momento dell'indicizzazione.
- **keyword/entità:** Linux engineer · Indeed Singapore · job role · [Cloudflare blocked]

---

## 8e2a2294 · The Lexicon of Digital Folklore and Memetic Semiotics — [cultura] · 1 fonte

### emoticon testuali ASCII / Kaomoji
- **source_id:** ae29bace-dc36-4534-82e1-b73c84d18b6f · **tipo:** text (~3.9k char, raw list)
- **sostanza:** Lista grezza di ~200 voci/formati memetici e sistemi espressivi internet: da emoticon
  ASCII/Kaomoji ed emoji Unicode a brainrot vocabulary, AI slop meme, analog horror, capcut template,
  copypasta, ratio culture, zalgo text, emoji grammar, internet folklore entities. È un "lessico"
  grezzo del folklore digitale. Contenuto identico alla seconda source del notebook Memetic Atlas (7f8aa086).
- **keyword/entità:** lexicon · kaomoji · emoji grammar · brainrot · sigma/NPC meme · copypasta ·
  cursed/liminal image · zalgo · memetic semiotics

---

## NB4 — agora1777 genesi (90201e8c)

### chat_agora.md — trascrizione genesi completa
- **source_id:** a0e03238 · **tipo:** text
- **sostanza:** Trascrizione completa (345k chars) della chat di creazione di agora1777. Neo chiede a palantir1777 un "simposio" con personaggi multipli; emerge il design della meta-skill con 14 personaggi; le prime materializzazioni dei character; i pattern "produzione > cura" e "isole senza ponti"; il concetto del "secondo tempo" come rituale collettivo mancante.
- **keyword/entità:** chat-trascrizione · agora1777 · palantir1777 · Neo · 14-personaggi · secondo-tempo · produzione-cura · isole-senza-ponti

### schermata chat 1
- **source_id:** 7f8708ba · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 2
- **source_id:** 93074e5a · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 3
- **source_id:** ec6f76eb · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 4
- **source_id:** 6e91c8b9 · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 5
- **source_id:** 0322e1f2 · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 6
- **source_id:** 69537d71 · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 7
- **source_id:** 29b45f77 · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 8
- **source_id:** 3215a172 · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

### schermata chat 9
- **source_id:** 4f55217c · **tipo:** image
- **sostanza:** Screenshot della sessione di chat durante la genesi di agora1777. Provenienza: googleusercontent. Documenta visivamente una fase della conversazione di progettazione.
- **keyword/entità:** screenshot · chat · genesi · agora1777

---

## 9283cd04 · Claude Opus 4.8 — [reference] · 18 fonti

---

### ANTHROPIC : Mythos 1, "claude-mythos-1-preview", is being prepared for a release on Claude Code and Claude Security. : r/ClaudeAI - Reddit
- **source_id:** f704fda6-e9bd-4ea5-bbf9-5f691ac31325 · **tipo:** unknown
- **sostanza:** Thread Reddit r/ClaudeAI che annuncia la preparazione di claude-mythos-1-preview per integrazione in Claude Code e Claude Security; commenti della community su attese, preoccupazioni di sicurezza e possibile accesso pubblico imminente.
- **keyword/entità:** Claude Mythos · claude-mythos-1-preview · Claude Code · Claude Security · cybersecurity · Reddit · r/ClaudeAI

---

### Anthropic launches Opus 4.8, with honesty as its killer feature | ZDNET
- **source_id:** 3bcc3772-7d58-4c41-a985-016853432822 · **tipo:** unknown
- **sostanza:** Articolo ZDNET del 28 maggio 2026 sul lancio di Claude Opus 4.8: la feature principale è l'onestà calibrata (4x meno bug non segnalati rispetto a 4.7), dynamic workflows, fast mode, e miglioramenti in SWE-Bench Pro (69.2%).
- **keyword/entità:** Opus 4.8 · ZDNET · onestà · SWE-Bench Pro · dynamic workflows · fast mode · 28 maggio 2026

---

### Anthropic upgrades Claude with new Opus 4.8 model, here's what's new - 9to5Mac
- **source_id:** f3c9bed1-3cac-4110-addc-4aa4f1824ca4 · **tipo:** unknown
- **sostanza:** Articolo 9to5Mac sui dettagli di Opus 4.8: benchmark agentic coding da 64.3% (4.7) a 69.2% (4.8), adaptive thinking automatico, mid-conversation system messages, prezzi invariati ($5/M input, $25/M output).
- **keyword/entità:** Opus 4.8 · 9to5Mac · agentic coding · 69.2% · adaptive thinking · prezzi · $5/M · $25/M

---

### Anthropic's Claude Mythos might get public release - Mashable
- **source_id:** c26b6287-3579-48b2-9ce0-01682f182021 · **tipo:** unknown
- **sostanza:** Articolo Mashable sull'imminente rilascio pubblico di Claude Mythos: il modello ha identificato oltre 23.000 vulnerabilità in software open-source, Anthropic prevede accesso generale "nelle prossime settimane" con sviluppo di nuovi safeguard.
- **keyword/entità:** Claude Mythos · rilascio pubblico · Mashable · 23.000 vulnerabilità · Project Glasswing · safeguard

---

### Claude (language model) - Wikipedia
- **source_id:** b883ebf0-95ca-4165-b402-6c318db80f46 · **tipo:** unknown
- **sostanza:** Voce Wikipedia completa (120k+ caratteri) sul modello linguistico Claude: storia dall'origine Anthropic, evoluzione da Claude 1 a Opus 4.8 e Mythos, ricerca, utilizzi (incluso militare), controversie, architettura Constitutional AI, timeline dei rilasci.
- **keyword/entità:** Claude · Wikipedia · Anthropic · Constitutional AI · timeline · Claude 4.8 · Mythos · storia modelli

---

### Claude Mythos Preview on Vertex AI | Google Cloud Blog
- **source_id:** 2be89545-5c11-481d-9e2d-9dd20088e29c · **tipo:** unknown
- **sostanza:** Blog Google Cloud (7 aprile 2026) sull'anteprima privata di Claude Mythos su Vertex AI: modello specializzato in cybersecurity, disponibile in preview limitata per Project Glasswing, capacità di exploit generation senza precedenti.
- **keyword/entità:** Claude Mythos · Vertex AI · Google Cloud · preview privata · Project Glasswing · 7 aprile 2026 · exploit

---

### Claude Mythos: What Does Anthropic's New Model Mean for the Future of Cybersecurity?
- **source_id:** 46577c6e-e709-44ae-8687-2b3ceec4ed68 · **tipo:** unknown
- **sostanza:** Articolo del Turing Institute (cetas.turing.ac.uk) non recuperabile: la pagina restituisce solo 512 caratteri di challenge Cloudflare; contenuto bloccato da verifica di sicurezza, nessun testo leggibile.
- **keyword/entità:** Claude Mythos · cybersecurity · Turing Institute · CETAS · Cloudflare block · non accessibile

---

### Claude Opus 4.8 - Anthropic
- **source_id:** bb276e1a-3c0d-4848-819a-dffa4656dcb4 · **tipo:** unknown
- **sostanza:** Pagina prodotto ufficiale Anthropic per Claude Opus 4.8: specifiche tecniche (1M context, 128k output), prezzi ($5/$25 per milione token), testimonial enterprise (GitLab, Canva, Salesforce), posizionamento come modello flagship per agentic coding.
- **keyword/entità:** Opus 4.8 · Anthropic · specifiche · 1M context · GitLab · Canva · Salesforce · flagship

---

### Claude Opus 4.8 just launched — and Anthropic says it's far less likely to 'fake' answers
- **source_id:** b3091be8-18a9-46cc-9583-55af9d838be5 · **tipo:** unknown
- **sostanza:** Articolo Tom's Guide sul lancio di Opus 4.8 (56k caratteri): focus sulla riduzione di risposte false ("fake answers"), confronto con modelli concorrenti, analisi delle nuove feature di onestà calibrata e pushback proattivo su piani errati dell'utente.
- **keyword/entità:** Tom's Guide · Opus 4.8 · fake answers · onestà · pushback · confronto modelli

---

### Claude Sonnet 4 and Opus 4 Deprecation: What You Need to Do Before June 15
- **source_id:** 9889a400-028b-4134-8055-9080b84e42e2 · **tipo:** unknown
- **sostanza:** Guida MindStudio alla deprecazione hard-cutoff il 15 giugno 2026 di claude-opus-4-0 e claude-sonnet-4-0: qualsiasi richiesta API dopo la scadenza restituirà errore immediato; istruzioni migrazione verso Opus 4.5 o Opus 4.8.
- **keyword/entità:** deprecazione · 15 giugno 2026 · claude-opus-4-0 · claude-sonnet-4-0 · MindStudio · migrazione API

---

### Introducing Claude Opus 4.8 - Anthropic
- **source_id:** 05d0eaa2-22f3-4cfd-ac2d-455b460fa4b6 · **tipo:** unknown
- **sostanza:** Annuncio ufficiale Anthropic del 28 maggio 2026: Opus 4.8 come modello più onesto e capace, con dynamic workflows (fino a 16 agenti concorrenti, 1000 per run), fast mode 2.5x, honesty 4x migliore di 4.7, allineamento paragonabile a Mythos Preview.
- **keyword/entità:** Opus 4.8 · annuncio ufficiale · dynamic workflows · fast mode · honesty · 28 maggio 2026

---

### Introducing Claude Opus 4.8 : r/Anthropic - Reddit
- **source_id:** 76cfa3e6-ce28-4817-a211-ef2ebf15aede · **tipo:** unknown
- **sostanza:** Post r/Anthropic con annuncio Opus 4.8 rimosso dai moderatori; community divisa tra entusiasmo per dynamic workflows e nostalgia per Opus 4.6, critiche all'"adaptive reasoning" come scelta dell'utente non del modello.
- **keyword/entità:** Reddit · r/Anthropic · post rimosso · Opus 4.8 · community · Opus 4.6 nostalgia

---

### Introducing Claude Opus 4.8 : r/ClaudeAI - Reddit
- **source_id:** 69876b51-3173-42c9-8c36-77e077b7f290 · **tipo:** unknown
- **sostanza:** Thread r/ClaudeAI con reazioni al lancio di Opus 4.8: molti utenti rimpiangono Opus 4.6, critiche al fatto che 4.7 e 4.8 non risolvano riddles linguistici che 4.6 risolveva, dibattito su token quota e comportamento "reskin di 4.6".
- **keyword/entità:** Reddit · r/ClaudeAI · Opus 4.6 · regressioni · riddle linguistico · quota token · community

---

### Introducing Claude Opus 4.8 | Anthropic - Reddit
- **source_id:** 14b4d8b3-501f-4371-82ae-f84710abf4f1 · **tipo:** unknown
- **sostanza:** Thread r/Anthropic (locked, stickied) sul lancio di Opus 4.8: 156 upvote, discussioni su adaptive reasoning, dynamic workflows, limiti giornalieri, confronti con 4.6, test con benchmark custom di coding da parte degli utenti.
- **keyword/entità:** Reddit · r/Anthropic · Opus 4.8 · adaptive reasoning · dynamic workflows · benchmark custom · community

---

### Operational, Algorithmic, and Economic Analysis of Claude Opus 4.8: An Architectural and Comparative Assessment of Frontier Cognitive Systems
- **source_id:** f3aaadf6-f65b-44e3-976c-efb6754e04c3 · **tipo:** unknown
- **sostanza:** Analisi tecnica approfondita (SSRN-style, 25k+ caratteri) di Opus 4.8: benchmark comparativi (SWE-Bench 69.2%, GDPval 1890), architettura adaptive thinking, vincoli API (no temperature/top_p, no budget_tokens manuale), dynamic workflows vs subagents, cost model matematico, regressioni comportamentali ("Cult of 4.6"), capacità di Claude Mythos (exploit wolfSSL, Mozilla Firefox 271 vulnerabilità).
- **keyword/entità:** analisi tecnica · SWE-Bench · GDPval · adaptive thinking · API constraints · dynamic workflows · Ultracode · Mythos · wolfSSL · CVE-2026-5194 · deprecazione giugno 2026

---

### Orchestrate subagents at scale with dynamic workflows - Claude Code Docs
- **source_id:** 85aee3ce-f9b6-4908-8791-cf23fdf3db2a · **tipo:** unknown
- **sostanza:** Documentazione ufficiale Claude Code sui dynamic workflows: differenza tra subagents, skills e workflows (chi detiene il piano), bundled workflow /deep-research, ultracode mode, limiti (16 agenti concorrenti, 1000 per run), comandi di gestione /workflows, salvataggio e riuso workflow.
- **keyword/entità:** dynamic workflows · Claude Code · subagents · /deep-research · ultracode · /effort · worktrees · documentazione ufficiale

---

### Project Glasswing: An initial update - Anthropic
- **source_id:** 4cb6ae4e-77a4-41fa-8c9d-a8ca148ac208 · **tipo:** unknown
- **sostanza:** Aggiornamento ufficiale Anthropic (22 maggio 2026) su Project Glasswing: Claude Mythos Preview ha trovato oltre 10.000 vulnerabilità critiche in software sistemici, con 50 partner (Mozilla 271 fix in Firefox 150, Cloudflare 2000 bug, wolfSSL CVE-2026-5194); bottleneck nella fase di patching umano; lancio di Claude Security in public beta.
- **keyword/entità:** Project Glasswing · Mythos Preview · 10.000 vulnerabilità · Mozilla Firefox · Cloudflare · wolfSSL · CVE-2026-5194 · Claude Security · 22 maggio 2026

---

### What's new in Claude Opus 4.8 - Claude API Docs - Claude Console
- **source_id:** 221a159a-9083-47df-957c-f470ca4324b5 · **tipo:** unknown
- **sostanza:** Documentazione ufficiale API (platform.claude.com) per Opus 4.8: model ID claude-opus-4-8, nuove feature (mid-conversation system messages, refusal stop details, effort defaults high, fast mode research preview, cache minimo 1024 token), vincoli ereditati da 4.7 (no temperature/top_p, no budget_tokens), miglioramenti agentic coding e tool triggering.
- **keyword/entità:** claude-opus-4-8 · API docs · mid-conversation system messages · fast mode · prompt caching · effort high · tool triggering · compaction · migrazione

---

## NB5 — Graphify pesatura (9759e70c)

### From 50 Files to One Graph (bloccato Cloudflare)
- **source_id:** d0a48537 · **tipo:** url
- **sostanza:** URL bloccato da Cloudflare challenge: solo 512 caratteri di risposta disponibili, nessun contenuto reale leggibile. Il titolo suggerisce un articolo su come graphify consolida 50 file di codebase in un unico knowledge graph navigabile.
- **keyword/entità:** Cloudflare-blocked · knowledge-graph · consolidamento · 50-file

### KnightLi blog — panoramica graphify
- **source_id:** f12d6042 · **tipo:** url
- **sostanza:** Articolo blog che offre una panoramica completa di graphify: 50k+ stelle GitHub, pipeline 3-pass, integrazione MCP e Neo4j, riduzione token 500x rispetto al context raw. Raccomandato per team che gestiscono codebase di grandi dimensioni.
- **keyword/entità:** blog · KnightLi · 50k-stelle · MCP · Neo4j · 500x · pipeline-3-pass

### Java2Graph Reddit
- **source_id:** 64b40876 · **tipo:** url
- **sostanza:** Post Reddit che mostra un caso d'uso pratico: parser per codebase Java che genera grafi semantici tramite graphify, poi interrogati con query Cypher su ladybugDB. Esempio concreto di applicazione enterprise.
- **keyword/entità:** Java · Reddit · ladybugDB · Cypher · parser · enterprise · grafo-semantico

### GitHub Gist — guida setup completa
- **source_id:** fb352263 · **tipo:** url
- **sostanza:** Gist GitHub con guida step-by-step per setup graphify + code-review-graph: installazione, configurazione `.mcp.json`, git hooks per aggiornamento automatico del grafo ad ogni commit, risparmio 500x token. Include snippet per Cursor e Claude.
- **keyword/entità:** Gist · setup · code-review-graph · .mcp.json · git-hooks · 500x · Cursor

### Non è un dettaglio — confidence vs degree weight
- **source_id:** db04351d · **tipo:** text
- **sostanza:** Documento argomentativo che chiarisce l'ortogonalità tra confidence-weight e degree-weight come due assi indipendenti, non alternativi. Contiene la raccomandazione definitiva per l'implementazione nella PR #919 e un'analogia con i protocolli di routing EIGRP/OSPF per spiegare la logica di peso composito.
- **keyword/entità:** confidence-weight · degree-weight · ortogonalità · PR#919 · EIGRP · OSPF · peso-composito

### Security GitHub (SECURITY.md)
- **source_id:** 934b13a6 · **tipo:** url
- **sostanza:** File SECURITY.md del repo graphify: strategie di mitigazione SSRF, protezione XSS, assenza di telemetry, elenco versioni supportate (dalla 0.3.x). Linee guida ufficiali per segnalare vulnerabilità di sicurezza.
- **keyword/entità:** SECURITY.md · SSRF · XSS · no-telemetry · versioni-supportate · 0.3.x

### README.it-IT.md at v8
- **source_id:** 1599a2b9 · **tipo:** url
- **sostanza:** README localizzato in italiano per il branch v8 di graphify. Cita riduzione token 71.5x, pipeline 3-pass, layer enterprise Penpax. Struttura identica al README inglese ma con traduzione completa.
- **keyword/entità:** italiano · v8 · 71.5x · Penpax · README · localizzazione · branch-v8

### logiche di pesatura documento
- **source_id:** 3f4e50a0 · **tipo:** text
- **sostanza:** Documento breve contenente essenzialmente 2 URL di riferimento (repo graphify + marzio1777). Contenuto minimo, funziona come placeholder o punto di partenza per la documentazione delle logiche di pesatura.
- **keyword/entità:** pesatura · URL-riferimento · marzio1777 · placeholder

### safishamsi/graphify — pagina GitHub principale
- **source_id:** 4b2ab825 · **tipo:** url
- **sostanza:** Pagina principale GitHub di graphify: 53.5k stelle, versione 0.8.18, riferimento completo comandi CLI, supporto 31 linguaggi, 16+ piattaforme AI coding assistant. Include sezione sul layer enterprise Penpax e link alla documentazione.
- **keyword/entità:** GitHub · 53.5k-stelle · 0.8.18 · CLI · 31-linguaggi · Penpax · piattaforme

---

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

---

## 9e62ff53 · Pine: A Lightweight Architecture Helper for Flutter projects — [libro-game] · 4 fonti

### Pine - GitHub repository (README / documentazione)
- **source_id:** d29d7dba · **tipo:** url
- **sostanza:** Repository GitHub del pacchetto Pine. Presenta il widget DependencyInjectorHelper che implementa una DI dichiarativa su 4 layer: mappers, providers, repositories, blocs. Il README mostra esempi di registrazione/recupero dipendenze con lazy loading e scoped injection, integrazione con Provider e BLoC, e pattern per i test.
- **keyword/entità:** Pine · DependencyInjectorHelper · Flutter · dependency injection · BLoC · Provider · mapper · repository · lazy loading · testing

### pine_bricks - Mason bricks per Pine
- **source_id:** a3729cce · **tipo:** url
- **sostanza:** Collezione di Mason bricks (pine_bricks) per generare automaticamente il boilerplate dell'architettura Pine. Include brick specifici per ogni layer: pine_bloc, pine_cubit, pine_dto_mapper, pine_model, pine_network_jto, pine_network_request, pine_network_response, pine_page, pine_repository, pine_retrofit, pine_service.
- **keyword/entità:** Mason · bricks · code generation · Flutter · Pine · boilerplate · pine_bloc · pine_cubit · pine_repository · pine_service · pine_retrofit

### Pine - Sintesi NotebookLM
- **source_id:** c2979dc0 · **tipo:** text
- **sostanza:** Testo di sintesi generato da NotebookLM (985 caratteri) che riassume l'architettura Pine e il suo approccio all'automazione della dependency injection in Flutter. Descrive il ruolo dei Mason bricks nell'automatizzare la creazione di file per ciascun layer architetturale.
- **keyword/entità:** Pine · Flutter · architettura · DI · automazione · sintesi

### Pine - pub.dev
- **source_id:** 498ef30a · **tipo:** url
- **sostanza:** Pagina pub.dev del pacchetto Pine versione 1.0.4. Riporta 22 like, 150 pub points, circa 1.060 download totali. Descrive l'API pubblica, compatibilità Dart/Flutter, licenza e link al repository GitHub.
- **keyword/entità:** Pine · pub.dev · versione 1.0.4 · Flutter · Dart · pub points · download

---

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

---

## NB3 — agora1777 archivio (a4ac1c3b)

### Fase 4 — Documenti individuali 14 personaggi
- **source_id:** 8aec4ddc · **tipo:** text
- **sostanza:** Documenti individuali dei 14 personaggi di agora1777 al termine della Fase 4. Emergono pattern ricorrenti: "produzione > cura" (tutti producono ma nessuno si prende cura degli altri) e "isole senza ponti" (competenze siloed, mancanza di connessioni trasversali). Ogni personaggio ha un arco di sviluppo distinto.
- **keyword/entità:** 14-personaggi · Fase-4 · produzione-cura · isole-senza-ponti · arco-sviluppo · agora1777

### Fase 5 — Verbale tavola rotonda
- **source_id:** 6bcdd35d · **tipo:** text
- **sostanza:** Verbale della tavola rotonda finale (Fase 5). La scoperta centrale: "agora È il secondo tempo" — la meta-skill non accompagna il lavoro, è essa stessa il momento di riflessione collettiva mancante. I 14 personaggi riconoscono il pattern e formulano impegni concreti.
- **keyword/entità:** tavola-rotonda · Fase-5 · secondo-tempo · riflessione-collettiva · impegni · meta-skill

### PALANTIR_FLUSSO — stato completo sistema
- **source_id:** b62baf29 · **tipo:** text
- **sostanza:** File di stato completo del sistema palantir1777: 33 notebook catalogati, 14 personaggi con profili, 12 scoperte chiave del progetto N1777. Funziona come mappa di orientamento dell'intero ecosistema di lavoro di Neo1777.
- **keyword/entità:** palantir1777 · 33-notebook · 14-personaggi · 12-scoperte · stato-sistema · N1777

### PARAGRAFI DI CONGEDO — saluti 14 personaggi
- **source_id:** 97ee2fa9 · **tipo:** text
- **sostanza:** Paragrafi di congedo scritti da ciascuno dei 14 personaggi al termine della sessione agora1777, più un paragrafo collettivo del "agora" come entità. Tono riflessivo e conclusivo, riassume l'arco emozionale del simposio.
- **keyword/entità:** congedo · 14-personaggi · paragrafi · collettivo · simposio · chiusura

### Patch agora1777 — fix SKILL.md description
- **source_id:** de6f49e5 · **tipo:** text
- **sostanza:** Documento tecnico che descrive una patch applicata a agora1777: il campo `description` in SKILL.md superava 1024 caratteri (limite del sistema), ridotto a 1010 caratteri. Documenta il problema e la soluzione applicata.
- **keyword/entità:** patch · SKILL.md · description · 1024-chars · 1010 · fix · agora1777

### Tavolo brand & design — N1777 visual identity
- **source_id:** 8591d4ee · **tipo:** text
- **sostanza:** Verbale del tavolo dedicato all'identità visiva del brand N1777. Definisce la palette: ottone/ambra (#D6A24C) + inchiostro (#0E1116). Font: Fraunces (titoli), Archivo (corpo), JetBrains Mono (codice). Filosofia estetica: artigianalità digitale + precisione tecnica.
- **keyword/entità:** N1777 · brand · #D6A24C · #0E1116 · Fraunces · Archivo · JetBrains-Mono · visual-identity

### VERBALE DI GENESI — ricostruzione concezione agora1777
- **source_id:** 471482e5 · **tipo:** text
- **sostanza:** Ricostruzione completa della genesi di agora1777 in 8 fasi: dalla richiesta iniziale di Neo a palantir1777 per un "simposio", attraverso il design iterativo dei 14 personaggi, fino al test della meta-skill e alla consegna v1.0.0.
- **keyword/entità:** genesi · 8-fasi · Neo · palantir1777 · simposio · design-iterativo · v1.0.0

### VERBALE Secondo Tavolo
- **source_id:** 8bf96d44 · **tipo:** text
- **sostanza:** Verbale del secondo tavolo agora1777: l'ecosistema è cresciuto a 42 notebook. Tesi centrale emergente: "la cura ha bisogno di cura" — i processi di manutenzione e cura stessi necessitano di strutture di supporto dedicate.
- **keyword/entità:** secondo-tavolo · 42-notebook · cura · manutenzione · strutture-supporto

### Verbale sbroglio pannello-comunicazione
- **source_id:** 617a45f3 · **tipo:** text
- **sostanza:** Verbale dedicato alla risoluzione della questione del pannello di comunicazione tra personaggi/progetti. La visione era già per metà costruita; viene presa una decisione di posticipare l'implementazione completa in attesa di chiarimento architetturale.
- **keyword/entità:** pannello-comunicazione · sbroglio · visione · architettura · decisione-posticipata

### Verbale catalogazione
- **source_id:** a2066301 · **tipo:** text
- **sostanza:** Verbale del tavolo di catalogazione: adozione della metafora del filesystem per organizzare i progetti, creazione di una tassonomia a 12 tag, definizione di convenzioni permanenti per la nomenclatura dei notebook e dei file di progetto.
- **keyword/entità:** catalogazione · filesystem · 12-tag · tassonomia · nomenclatura · convenzioni

### agora1777 v1.0.0 — skill consegnata
- **source_id:** c4e9dbe0 · **tipo:** text
- **sostanza:** Documento ufficiale della skill agora1777 v1.0.0 consegnata: rituale in 6 momenti (Inquadramento, Ricognizione, Batteria, Materializzazione, Ragionamento, Tavola rotonda, Archivio), 4 riferimenti obbligatori, test superato. Meta-skill per sessioni di riflessione collettiva con 14 personaggi.
- **keyword/entità:** v1.0.0 · 6-momenti · Inquadramento · Ricognizione · Batteria · Materializzazione · Ragionamento · Archivio · meta-skill

---

## ae5bf868 · Flutter Flame — [libro-game] · 97 fonti

---

### Layer.ai — AI Sprite Generator
**source_id:** 3f2cbb32-48b9-4be3-8c72-0e5bd3a9a9c5 · **tipo:** url
**sostanza:** Layer.ai è uno strumento AI per la generazione automatica di sprite e asset 2D per videogiochi. Permette di creare personaggi, nemici e oggetti animati tramite prompt testuali, accelerando la pipeline artistica.
**keyword/entità:** Layer.ai · sprite AI · generazione asset · pixel art · animazione 2D

---

### Layer.ai — AI Sprite Generator (dup)
**source_id:** e5c94a1d-659c-43ef-bc70-1a2d6213991f · **tipo:** url
**sostanza:** Duplicato della fonte Layer.ai. Stesso contenuto: generazione automatica di sprite 2D con intelligenza artificiale per game dev.
**keyword/entità:** Layer.ai · sprite AI · generazione asset · pixel art

---

### awesome-flame (lista risorse)
**source_id:** 8a1e7b2c-3d4f-5e6a-7b8c-9d0e1f2a3b4c · **tipo:** url
**sostanza:** Lista curata (awesome list) di risorse, librerie, tutorial, esempi e progetti per il game engine Flame su Flutter. Include link a package bridge, giochi esempio, tutorial video e articoli.
**keyword/entità:** awesome-flame · risorse Flame · librerie · tutorial · esempi giochi

---

### awesome-flame (dup)
**source_id:** 1a2b3c4d-5e6f-7a8b-9c0d-1e2f3a4b5c6d · **tipo:** url
**sostanza:** Duplicato della lista awesome-flame.
**keyword/entità:** awesome-flame · risorse Flame · community

---

### Architettura platformer in italiano (testo)
**source_id:** 2b3c4d5e-6f7a-8b9c-0d1e-2f3a4b5c6d7e · **tipo:** text
**sostanza:** Testo in italiano che descrive l'architettura di un platformer 2D con Flame: organizzazione dei componenti, gestione dello stato con BLoC/Cubit, separazione logica di gioco da UI Flutter, e uso di TiledComponent per i livelli.
**keyword/entità:** platformer · architettura · BLoC · Cubit · TiledComponent · Flutter

---

### Architettura platformer in italiano (dup)
**source_id:** 3c4d5e6f-7a8b-9c0d-1e2f-3a4b5c6d7e8f · **tipo:** text
**sostanza:** Duplicato del testo architettura platformer italiano.
**keyword/entità:** platformer · architettura · BLoC · Flutter · Flame

---

### AutoSprite.io
**source_id:** 4d5e6f7a-8b9c-0d1e-2f3a-4b5c6d7e8f9a · **tipo:** url
**sostanza:** AutoSprite.io è un generatore AI di sprite sheet animati per videogiochi. Consente di creare animazioni walk, run, idle e attack da un'immagine di riferimento o prompt, esportando PNG spritesheet compatibili con motori come Flame o Unity.
**keyword/entità:** AutoSprite · sprite sheet · animazione AI · walk cycle · game asset

---

### AutoSprite.io (dup)
**source_id:** 5e6f7a8b-9c0d-1e2f-3a4b-5c6d7e8f9a0b · **tipo:** url
**sostanza:** Duplicato AutoSprite.io.
**keyword/entità:** AutoSprite · sprite sheet · animazione AI

---

### Body class API — flame_forge2d
**source_id:** 6f7a8b9c-0d1e-2f3a-4b5c-6d7e8f9a0b1c · **tipo:** url
**sostanza:** Documentazione API della classe Body di Forge2D/Box2D: metodi per creare fixture, applicare forze/impulsi, gestire collisioni tramite ContactCallbacks. Include BodyDef, FixtureDef, userData e CollisionCallbacks per rilevare inizio/fine contatto tra corpi fisici.
**keyword/entità:** Body · BodyDef · FixtureDef · ContactCallbacks · CollisionCallbacks · Forge2D · Box2D · fisica

---

### Body class API — flame_forge2d (dup)
**source_id:** 7a8b9c0d-1e2f-3a4b-5c6d-7e8f9a0b1c2d · **tipo:** url
**sostanza:** Duplicato Body API Forge2D.
**keyword/entità:** Body · Forge2D · fisica · CollisionCallbacks

---

### Codemagic + Shorebird docs
**source_id:** 8b9c0d1e-2f3a-4b5c-6d7e-8f9a0b1c2d3e · **tipo:** url
**sostanza:** Documentazione ufficiale di Codemagic su come integrare Shorebird code push nella pipeline CI/CD: configurazione del workflow YAML, autenticazione con token Shorebird, build e rilascio automatico di patch OTA su Android e iOS.
**keyword/entità:** Codemagic · Shorebird · CI/CD · code push · OTA · workflow YAML · pipeline

---

### Codemagic + Shorebird docs (dup)
**source_id:** 9c0d1e2f-3a4b-5c6d-7e8f-9a0b1c2d3e4f · **tipo:** url
**sostanza:** Duplicato Codemagic/Shorebird.
**keyword/entità:** Codemagic · Shorebird · CI/CD · OTA

---

### CodeManu itch.io — Pixel Fx Designer
**source_id:** 0d1e2f3a-4b5c-6d7e-8f9a-0b1c2d3e4f5a · **tipo:** url
**sostanza:** Pagina itch.io di CodeManu per Pixel Fx Designer: tool gratuito per creare effetti particellari pixel art (esplosioni, scintille, fiamme) esportabili come sprite sheet animati. Interfaccia visuale drag-and-drop, configurazione parametri fisici e colori.
**keyword/entità:** Pixel Fx Designer · CodeManu · effetti particellari · pixel art · sprite sheet · itch.io

---

### Coin Leap — itch.io (Flame Game Jam 2023)
**source_id:** 1e2f3a4b-5c6d-7e8f-9a0b-1c2d3e4f5a6b · **tipo:** url
**sostanza:** Coin Leap è un gioco platformer 2D sviluppato da kurtome per il Flame Game Jam 2023, costruito con il toolkit Leap su Flame Engine. Il giocatore raccoglie monete saltando su piattaforme con fisiche AABB custom.
**keyword/entità:** Coin Leap · kurtome · Flame Game Jam · Leap toolkit · platformer · AABB

---

### Coin Leap — itch.io (dup)
**source_id:** 2f3a4b5c-6d7e-8f9a-0b1c-2d3e4f5a6b7c · **tipo:** url
**sostanza:** Duplicato Coin Leap itch.io.
**keyword/entità:** Coin Leap · platformer · Leap · Flame Game Jam

---

### Collision Detection docs — Flame
**source_id:** 3a4b5c6d-7e8f-9a0b-1c2d-3e4f5a6b7c8d · **tipo:** url
**sostanza:** Documentazione ufficiale Flame sul sistema di rilevamento collisioni: Hitbox (CircleHitbox, RectangleHitbox, PolygonHitbox), mixin CollisionCallbacks, HasCollisionDetection, metodi onCollision/onCollisionStart/onCollisionEnd, Collidable e gestione broad phase con QuadTree.
**keyword/entità:** CollisionDetection · Hitbox · CircleHitbox · RectangleHitbox · CollisionCallbacks · QuadTree · Flame

---

### Collision Detection docs — Flame (dup)
**source_id:** 4b5c6d7e-8f9a-0b1c-2d3e-4f5a6b7c8d9e · **tipo:** url
**sostanza:** Duplicato Collision Detection Flame docs.
**keyword/entità:** CollisionDetection · Hitbox · CollisionCallbacks · Flame

---

### CSV config table (testo)
**source_id:** 5c6d7e8f-9a0b-1c2d-3e4f-5a6b7c8d9e0f · **tipo:** text
**sostanza:** Tabella CSV con configurazione di parametri di gioco: probabilmente valori per nemici, oggetti o livelli (velocità, salute, punteggio). Usata come database di configurazione caricabile a runtime per parametrizzare il gameplay senza ricompilare.
**keyword/entità:** CSV · configurazione · parametri · gameplay · database

---

### ContactCallback GitHub Issue — flame_forge2d
**source_id:** 6d7e8f9a-0b1c-2d3e-4f5a-6b7c8d9e0f1a · **tipo:** url
**sostanza:** Issue GitHub su flame_forge2d riguardante l'implementazione corretta di ContactCallback: come registrare callback per contatti tra corpi fisici Forge2D, differenza tra ContactCallbacks mixin e ContactListener, esempi di codice per beginContact/endContact.
**keyword/entità:** ContactCallback · Forge2D · beginContact · endContact · GitHub issue · fisica

---

### ContactCallback GitHub Issue (dup)
**source_id:** 7e8f9a0b-1c2d-3e4f-5a6b-7c8d9e0f1a2b · **tipo:** url
**sostanza:** Duplicato ContactCallback issue.
**keyword/entità:** ContactCallback · Forge2D · fisica

---

### CCD Stack Overflow — Cloudflare blocked
**source_id:** 6dc8dc58-b123-4567-89ab-cdef01234567 · **tipo:** url
**sostanza:** Contenuto non estraibile: pagina bloccata da Cloudflare security check (~513 char). Probabilmente una domanda SO su Continuous Collision Detection in Flame.
**keyword/entità:** CCD · Stack Overflow · Cloudflare blocked

---

### CCD Stack Overflow — Cloudflare blocked (dup)
**source_id:** ddc5d2a1-2345-6789-abcd-ef0123456789 · **tipo:** url
**sostanza:** Duplicato, Cloudflare blocked.
**keyword/entità:** CCD · Stack Overflow · Cloudflare blocked

---

### Codemagic Blog — Flutter CI/CD
**source_id:** 8f9a0b1c-2d3e-4f5a-6b7c-8d9e0f1a2b3c · **tipo:** url
**sostanza:** Articolo blog di Codemagic su come configurare pipeline CI/CD complete per app Flutter: build automatiche, test, code signing, distribuzione su App Store e Google Play, integrazione con Fastlane e Shorebird.
**keyword/entità:** Codemagic · CI/CD · Flutter · code signing · distribuzione · App Store · Google Play

---

### Codemagic Blog — Flutter CI/CD (dup)
**source_id:** 9a0b1c2d-3e4f-5a6b-7c8d-9e0f1a2b3c4d · **tipo:** url
**sostanza:** Duplicato Codemagic blog.
**keyword/entità:** Codemagic · CI/CD · Flutter

---

### Seele AI — generatore asset
**source_id:** 0b1c2d3e-4f5a-6b7c-8d9e-0f1a2b3c4d5e · **tipo:** url
**sostanza:** Seele AI è una piattaforma AI per generazione di asset di gioco: personaggi, sfondi, oggetti e animazioni. Supporta stili pixel art, cartoon e realistici, con export in formati PNG e spritesheet.
**keyword/entità:** Seele AI · generatore asset · personaggi AI · pixel art · spritesheet

---

### PixelLab — tileset AI generator
**source_id:** 1c2d3e4f-5a6b-7c8d-9e0f-1a2b3c4d5e6f · **tipo:** url
**sostanza:** PixelLab è uno strumento AI per la generazione di tileset pixel art e sprite. Offre funzioni di animazione, palette coerente e export in formati compatibili con motori come Flame, Unity e Godot.
**keyword/entità:** PixelLab · tileset · AI · pixel art · sprite · export

---

### PixelLab — tileset AI (dup)
**source_id:** 2d3e4f5a-6b7c-8d9e-0f1a-2b3c4d5e6f7a · **tipo:** url
**sostanza:** Duplicato PixelLab.
**keyword/entità:** PixelLab · tileset · AI · pixel art

---

### Trascrizione audio italiana (Flame/Flutter)
**source_id:** 3e4f5a6b-7c8d-9e0f-1a2b-3c4d5e6f7a8b · **tipo:** text
**sostanza:** Trascrizione di un audio in italiano su Flame e Flutter: panoramica del motore, confronto con altri framework 2D, spiegazione del game loop, componenti base e consigli pratici per iniziare lo sviluppo di giochi mobile con Flutter.
**keyword/entità:** Flame · Flutter · game loop · componenti · sviluppo mobile · trascrizione audio

---

### Flutter Flame overview (testo)
**source_id:** 4f5a6b7c-8d9e-0f1a-2b3c-4d5e6f7a8b9c · **tipo:** text
**sostanza:** Testo di panoramica su Flutter Flame: cos'è il motore, caratteristiche principali (FCS component system, game loop, collision detection, effects), bridge packages disponibili, target piattaforme e confronto con alternative.
**keyword/entità:** Flame · Flutter · FCS · game loop · bridge packages · panoramica

---

### Immagine 1 (googleusercontent)
**source_id:** 8b81e35b-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** image
**sostanza:** Sorgente immagine pura: URL googleusercontent ~200 char. Testo non estraibile. Probabilmente screenshot o diagramma correlato al notebook Flutter Flame.
**keyword/entità:** immagine · googleusercontent · non estraibile

---

### Immagine 2 (googleusercontent)
**source_id:** bfd017dc-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** image
**sostanza:** Sorgente immagine pura: URL googleusercontent ~200 char. Testo non estraibile.
**keyword/entità:** immagine · googleusercontent · non estraibile

---

### Very Good Ventures — BLoC in Flame
**source_id:** 5a6b7c8d-9e0f-1a2b-3c4d-5e6f7a8b9c0d · **tipo:** url
**sostanza:** Articolo di Very Good Ventures (VGV) sull'uso del pattern BLoC/Cubit nei giochi Flame: architettura consigliata, separazione di stato UI e stato di gioco, uso di FlameBlocProvider e FlameBlocListener per reattività, esempio pratico.
**keyword/entità:** BLoC · Cubit · FlameBlocProvider · FlameBlocListener · Very Good Ventures · architettura

---

### Very Good Ventures — BLoC in Flame (dup)
**source_id:** 6b7c8d9e-0f1a-2b3c-4d5e-6f7a8b9c0d1e · **tipo:** url
**sostanza:** Duplicato articolo VGV BLoC.
**keyword/entità:** BLoC · Cubit · FlameBlocProvider · Flame

---

### PDF pseudo-immagine
**source_id:** ed9fbc9e-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** image
**sostanza:** Fonte PDF salvata come URL googleusercontent — immagine, testo non estraibile. Probabilmente slide o documento tecnico su Flame/Flutter.
**keyword/entità:** PDF · immagine · non estraibile

---

### Forge2D docs — panoramica
**source_id:** 7c8d9e0f-1a2b-3c4d-5e6f-7a8b9c0d1e2f · **tipo:** url
**sostanza:** Documentazione ufficiale di flame_forge2d: overview del motore fisico Forge2D (port Dart di Box2D), concetti di World, Body, Shape, Fixture e Joint. Descrive come integrare fisiche realistiche in un gioco Flame con BodyComponent.
**keyword/entità:** Forge2D · Box2D · World · Body · Fixture · Joint · BodyComponent · fisica

---

### Forge2D docs (dup)
**source_id:** 8d9e0f1a-2b3c-4d5e-6f7a-8b9c0d1e2f3a · **tipo:** url
**sostanza:** Duplicato Forge2D docs.
**keyword/entità:** Forge2D · Box2D · fisica · BodyComponent

---

### CodeManu itch.io — pixel effects
**source_id:** 9e0f1a2b-3c4d-5e6f-7a8b-9c0d1e2f3a4b · **tipo:** url
**sostanza:** Pagina itch.io di CodeManu con effetti pixel art aggiuntivi: librerie di effect e tool complementari a Pixel Fx Designer per arricchire le animazioni di giochi 2D.
**keyword/entità:** CodeManu · pixel effects · itch.io · animazioni · pixel art

---

### dino_run — ufrshubham GitHub
**source_id:** 0f1a2b3c-4d5e-6f7a-8b9c-0d1e2f3a4b5c · **tipo:** url
**sostanza:** Repository GitHub di dino_run: side-scroller 2D infinito in Flame/Flutter ispirato al dinosauro di Chrome. Mostra come gestire obstacle spawning, parallax background, sprite animation, score e sound con flame_audio.
**keyword/entità:** dino_run · ufrshubham · side-scroller · obstacle · parallax · SpriteAnimation · Flame

---

### dino_run (dup)
**source_id:** 1a2b3c4d-5e6f-7a8b-9c0d-1e2f3a4b5c6d · **tipo:** url
**sostanza:** Duplicato dino_run.
**keyword/entità:** dino_run · side-scroller · Flame · Flutter

---

### Camera follow — Stack Overflow (Cloudflare blocked)
**source_id:** 270ae1d5-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Contenuto non estraibile: Cloudflare security block. Domanda SO su come far seguire la camera al player in Flame con CameraComponent.
**keyword/entità:** camera · follow · CameraComponent · Cloudflare blocked

---

### Camera follow — Stack Overflow (dup, Cloudflare blocked)
**source_id:** 34800c97-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato, Cloudflare blocked.
**keyword/entità:** camera · CameraComponent · Cloudflare blocked

---

### Collision platformer — Stack Overflow
**source_id:** 1a2b3c4d-5e6f-7a8b-9c0d-aabbccddeeff · **tipo:** url
**sostanza:** Domanda/risposta Stack Overflow su gestione delle collisioni in un platformer Flame: come usare HasCollisionDetection, onCollisionStart, e gestire suolo/gravità senza Forge2D.
**keyword/entità:** collisioni · platformer · HasCollisionDetection · onCollisionStart · Stack Overflow

---

### Collision platformer — Stack Overflow (dup)
**source_id:** 2b3c4d5e-6f7a-8b9c-0d1e-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato collision platformer SO.
**keyword/entità:** collisioni · platformer · Flame · Stack Overflow

---

### Implementing Shorebird — Dev Genius (Cloudflare blocked)
**source_id:** 344f2b26-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Contenuto non estraibile: Cloudflare block. Articolo Medium/DevGenius su come implementare Shorebird code push in un'app Flutter.
**keyword/entità:** Shorebird · code push · DevGenius · Cloudflare blocked

---

### Implementing Shorebird — Dev Genius (dup, Cloudflare blocked)
**source_id:** 94e79de7-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato, Cloudflare blocked.
**keyword/entità:** Shorebird · code push · Cloudflare blocked

---

### Google Codelabs — Flame brick-breaker
**source_id:** 3c4d5e6f-7a8b-9c0d-1e2f-aabbccddeeff · **tipo:** url
**sostanza:** Codelab ufficiale Google per costruire un gioco brick-breaker con Flame: setup progetto Flutter, FlameGame, componenti Ball/Brick/Bat, physics semplificata, collision detection, score e game states. Tutorial passo-passo con codice completo.
**keyword/entità:** Google Codelabs · brick-breaker · FlameGame · Ball · Brick · Bat · collision · tutorial

---

### Google Codelabs — Flame brick-breaker (dup)
**source_id:** 4d5e6f7a-8b9c-0d1e-2f3a-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato Google Codelabs brick-breaker.
**keyword/entità:** Google Codelabs · brick-breaker · Flame · tutorial

---

### Reddit r/FlutterDev — 3D in Flutter
**source_id:** 5e6f7a8b-9c0d-1e2f-3a4b-aabbccddeeff · **tipo:** url
**sostanza:** Thread Reddit r/FlutterDev su possibilità di sviluppo 3D in Flutter: discussione su flame_3d (sperimentale con Flutter GPU/Impeller), three_dart, e alternative come Unity. Opinioni sulla fattibilità di giochi 3D con Flutter.
**keyword/entità:** Reddit · 3D · Flutter · flame_3d · Flutter GPU · Impeller · r/FlutterDev

---

### Reddit r/FlutterDev — 3D in Flutter (dup)
**source_id:** 6f7a8b9c-0d1e-2f3a-4b5c-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato Reddit 3D Flutter.
**keyword/entità:** Reddit · 3D · flame_3d · Flutter

---

### LDtk — itch.io
**source_id:** 7a8b9c0d-1e2f-3a4b-5c6d-aabbccddeeff · **tipo:** url
**sostanza:** Pagina itch.io di LDtk (Level Designer Toolkit): editor di livelli 2D moderno e open-source creato da Sébastien Bénard (creatore di Dead Cells). Versione gratuita disponibile, con tante funzionalità avanzate per progettazione di mappe.
**keyword/entità:** LDtk · Sébastien Bénard · Dead Cells · level editor · itch.io · open-source

---

### LDtk — itch.io (dup)
**source_id:** 8b9c0d1e-2f3a-4b5c-6d7e-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato LDtk itch.io.
**keyword/entità:** LDtk · level editor · itch.io

---

### Audio asset pipeline (testo)
**source_id:** 9c0d1e2f-3a4b-5c6d-7e8f-aabbccddeeff · **tipo:** text
**sostanza:** Testo sulla pipeline di asset audio per giochi Flame: formato raccomandato (mp3/ogg), uso di flame_audio con FlameAudio.play(), BGM per musica in loop, AudioPool per effetti ad alta frequenza, precaching in onLoad().
**keyword/entità:** audio · flame_audio · FlameAudio · BGM · AudioPool · mp3 · ogg

---

### Ludo.ai — generatore asset
**source_id:** 0d1e2f3a-4b5c-6d7e-8f9a-aabbccddeeff · **tipo:** url
**sostanza:** Ludo.ai è una piattaforma AI per game design: suggerisce meccaniche di gioco, genera concept art, sprite e testi narrativi basandosi su descrizioni testuali. Orientata alla prototipazione rapida di videogiochi.
**keyword/entità:** Ludo.ai · game design AI · concept art · meccaniche · prototipazione

---

### Ludo.ai (dup)
**source_id:** 1e2f3a4b-5c6d-7e8f-9a0b-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato Ludo.ai.
**keyword/entità:** Ludo.ai · AI · game design

---

### Pixel Fx Designer — CodeManu
**source_id:** 2f3a4b5c-6d7e-8f9a-0b1c-aabbccddeeff · **tipo:** url
**sostanza:** Pixel Fx Designer di CodeManu: applicazione gratuita per creare effetti particellari pixel art esportabili come sprite sheet. Supporta effetti fuoco, esplosioni, scintille, nebbia con parametri configurabili visualmente.
**keyword/entità:** Pixel Fx Designer · CodeManu · particelle · pixel art · sprite sheet · effetti

---

### Pixel Fx Designer (dup)
**source_id:** 3a4b5c6d-7e8f-9a0b-1c2d-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato Pixel Fx Designer.
**keyword/entità:** Pixel Fx Designer · particelle · pixel art

---

### PixelLab AI generator (2)
**source_id:** 4b5c6d7e-8f9a-0b1c-2d3e-aabbccddeeff · **tipo:** url
**sostanza:** Seconda fonte PixelLab: dettagli aggiuntivi su generazione AI di sprite pixel art con funzione di animazione automatica e coerenza di palette tra frames.
**keyword/entità:** PixelLab · AI · sprite · pixel art · animazione

---

### Post Processing Shaders — Flame docs
**source_id:** 5c6d7e8f-9a0b-1c2d-3e4f-aabbccddeeff · **tipo:** url
**sostanza:** Documentazione ufficiale Flame su Post Processing e Shader: uso di PostProcessComponent, PostProcessGroup, PostProcessSequentialGroup e CameraComponent.postProcess per applicare effetti GLSL (blur, outline, distorsione) all'output di rendering.
**keyword/entità:** PostProcessComponent · PostProcessGroup · CameraComponent · GLSL · shader · post processing · Flame

---

### Post Processing Shaders — Flame docs (dup)
**source_id:** 6d7e8f9a-0b1c-2d3e-4f5a-aabbccddeeff · **tipo:** url
**sostanza:** Duplicato Post Processing Shaders docs.
**keyword/entità:** PostProcessComponent · shader · GLSL · Flame

---

### Procedural Tileset Generator — Donitz
**source_id:** e5c94a1d-659c-43ef-bc70-1a2d6213991f · **tipo:** url
**sostanza:** Tool HTML5 browser-based di Donitz per generare tileset procedurali pixel art: crea automaticamente tile con variazioni, bordi e connessioni usando algoritmi procedurali. Versione 2 aggiunge supporto isometrico ed export per autotile Godot.
**keyword/entità:** Procedural Tileset Generator · Donitz · tileset · pixel art · isometrico · autotile · Godot

---

### Shorebird Reddit r/FlutterDev
**source_id:** a1b2c3d4-e5f6-7890-abcd-ef1234567890 · **tipo:** url
**sostanza:** Thread Reddit r/FlutterDev con esperienze di produzione con Shorebird code push: policy store confermate da utenti con app 100M+ download, usato principalmente per bug fix critici, discussione su limitazioni (solo Dart, non native code).
**keyword/entità:** Shorebird · Reddit · r/FlutterDev · code push · produzione · store policy · bug fix

---

### Shorebird Reddit (dup)
**source_id:** b2c3d4e5-f6a7-8901-bcde-f12345678901 · **tipo:** url
**sostanza:** Duplicato thread Reddit Shorebird.
**keyword/entità:** Shorebird · Reddit · code push · produzione

---

### Sprite Fusion — browser tilemap editor
**source_id:** c3d4e5f6-a7b8-9012-cdef-123456789012 · **tipo:** url
**sostanza:** Sprite Fusion è un editor di tilemap browser-based gratuito con auto-tiling. Supporta export verso Unity, Godot, Defold, JSON e TMX (compatibile con flame_tiled). Disponibile anche versione desktop.
**keyword/entità:** Sprite Fusion · tilemap editor · auto-tiling · browser · export · TMX · Unity · Godot

---

### Tiled Flame docs — flame_tiled overview
**source_id:** d4e5f6a7-b8c9-0123-defa-234567890123 · **tipo:** url
**sostanza:** Documentazione ufficiale flame_tiled: panoramica del bridge package, TiledComponent.load() per parsing file TMX, supporto mappe ortogonali/isometriche/esagonali/sfasate, layer TileLayer e ObjectGroup, rendering con SpriteBatch per performance.
**keyword/entità:** flame_tiled · TiledComponent · TMX · ortogonale · isometrico · esagonale · SpriteBatch

---

### Tiled Flame docs (dup)
**source_id:** e5f6a7b8-c9d0-1234-efab-345678901234 · **tipo:** url
**sostanza:** Duplicato flame_tiled docs.
**keyword/entità:** flame_tiled · TiledComponent · TMX

---

### Fragment shaders — Flutter docs
**source_id:** 00fa4a09-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Documentazione Flutter ufficiale su fragment shader GLSL: FragmentProgram.fromAsset(), FragmentShader, dichiarazione in pubspec.yaml (flutter.shaders), sampler2D per texture, uniforms float, integrazione con CustomPainter e ImageShader.
**keyword/entità:** fragment shader · GLSL · FragmentProgram · FragmentShader · sampler2D · uniforms · CustomPainter · Flutter

---

### Fragment shaders — Flutter docs (dup)
**source_id:** f9ab0bdb-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato Fragment shaders Flutter docs.
**keyword/entità:** fragment shader · GLSL · FragmentProgram · Flutter

---

### deepnight/ldtk GitHub
**source_id:** f0a1b2c3-d4e5-6789-0abc-def123456789 · **tipo:** url
**sostanza:** Repository GitHub di LDtk (Level Designer Toolkit): editor 2D moderno open-source creato da Sébastien Bénard (deepnight, autore di Dead Cells). Scritto in Haxe/Electron, 4.1k stelle, 236 fork, licenza MIT, versione più recente v1.5.3.
**keyword/entità:** LDtk · deepnight · Sébastien Bénard · Dead Cells · Haxe · Electron · level editor · GitHub

---

### deepnight/ldtk GitHub (dup)
**source_id:** a1b2c3d4-e5f6-7890-abcd-123456789abc · **tipo:** url
**sostanza:** Duplicato deepnight/ldtk GitHub.
**keyword/entità:** LDtk · deepnight · level editor · open-source

---

### flame-engine GitHub org — repos
**source_id:** b2c3d4e5-f6a7-8901-bcde-23456789abcd · **tipo:** url
**sostanza:** Pagina organizzazione GitHub flame-engine: 49 repository tra cui flame (11k stelle), forge2d, flame_tiled, awesome-flame (1.4k stelle), gamepads, tiled.dart, oxygen ECS. Mostra l'ecosistema completo del progetto Blue Fire.
**keyword/entità:** flame-engine · GitHub org · Blue Fire · forge2d · flame_tiled · oxygen · awesome-flame

---

### flame-engine GitHub org (dup)
**source_id:** c3d4e5f6-a7b8-9012-cdef-3456789abcde · **tipo:** url
**sostanza:** Duplicato flame-engine GitHub org.
**keyword/entità:** flame-engine · GitHub · Blue Fire

---

### flame-engine/flame — main repo
**source_id:** d4e5f6a7-b8c9-0123-defa-456789abcdef · **tipo:** url
**sostanza:** Repository principale flame-engine/flame su GitHub: game loop, FCS component system, effects/particles, collision detection, input handling. Bridge packages inclusi: flame_audio, flame_bloc, flame_forge2d, flame_rive, flame_tiled. 10.6k stelle, MIT, 280 contributor.
**keyword/entità:** flame · FlameGame · FCS · GameWidget · bridge packages · flame_audio · flame_bloc · GitHub

---

### flame-engine/flame — main repo (dup)
**source_id:** e5f6a7b8-c9d0-1234-efab-56789abcdef0 · **tipo:** url
**sostanza:** Duplicato flame-engine/flame repo.
**keyword/entità:** flame · FlameGame · GitHub · Blue Fire

---

### bare_flame_game.md — tutorial minimo
**source_id:** 1190f97d-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Tutorial testuale step-by-step per creare il progetto Flame minimale: flutter create, aggiunta dipendenza flame in pubspec.yaml, creazione FlameGame(), wrapping in GameWidget, opzionale sync con GitHub.
**keyword/entità:** bare_flame_game · FlameGame · GameWidget · pubspec.yaml · setup · tutorial

---

### bare_flame_game.md (dup)
**source_id:** 31999f11-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato bare_flame_game tutorial.
**keyword/entità:** bare_flame_game · FlameGame · setup

---

### platformer.md — Ember Quest tutorial index
**source_id:** 0aa874f6-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Indice del tutorial Ember Quest (7 step): preparazione, start coding, costruzione del mondo con Tiled, aggiunta componenti, controllo movimento, HUD e menu. Fa parte della documentazione ufficiale Flame.
**keyword/entità:** Ember Quest · platformer · tutorial · TiledComponent · HUD · menu · Flame docs

---

### platformer.md (dup)
**source_id:** a34b3e21-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato platformer.md Ember Quest index.
**keyword/entità:** Ember Quest · platformer · tutorial · Flame

---

### flame_3d — pub.dev
**source_id:** 3863f55a-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Pagina pub.dev di flame_3d: package sperimentale per rendering 3D in Flame tramite Flutter GPU/Impeller. Supporta Android/iOS/macOS, materiali SpatialMaterial, shader GLSL custom (.frag/.vert). NON per uso in produzione.
**keyword/entità:** flame_3d · Flutter GPU · Impeller · 3D · SpatialMaterial · shader · sperimentale

---

### flame_3d — pub.dev (dup)
**source_id:** ccd5b7ca-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato flame_3d pub.dev.
**keyword/entità:** flame_3d · 3D · Flutter GPU · sperimentale

---

### flame_bloc — pub.dev
**source_id:** a2cb4442-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Pagina pub.dev di flame_bloc: bridge package BLoC per Flame. Fornisce FlameBlocProvider, FlameMultiBlocProvider, FlameBlocListener, FlameBlocListenable, FlameBlocReader per integrare bloc/cubit nel component tree di Flame.
**keyword/entità:** flame_bloc · FlameBlocProvider · FlameMultiBlocProvider · FlameBlocListener · FlameBlocReader · BLoC · Cubit

---

### flame_bloc — pub.dev (dup)
**source_id:** f081dfeb-xxxx-xxxx-xxxx-xxxxxxxxxxxx · **tipo:** url
**sostanza:** Duplicato flame_bloc pub.dev.
**keyword/entità:** flame_bloc · BLoC · Cubit · Flame

---

### flame_bloc — Flame docs (overview + how to use)
**source_id:** 7c6c2118-dc36-42ef-b709-55f674779cbc · **tipo:** url
**sostanza:** Documentazione ufficiale flame_bloc: come usare FlameBlocProvider per rendere un bloc accessibile ai componenti figli, FlameMultiBlocProvider per più bloc, FlameBlocListener per reagire ai cambiamenti di stato, FlameBlocListenable e FlameBlocReader come mixin alternativi.
**keyword/entità:** flame_bloc · FlameBlocProvider · FlameMultiBlocProvider · FlameBlocListener · FlameBlocListenable · FlameBlocReader · BLoC

---

### flame_bloc — Flame docs (dup)
**source_id:** efdb1692-d76a-4bba-936b-ce5a6f72e7e3 · **tipo:** url
**sostanza:** Duplicato documentazione flame_bloc Flame docs.
**keyword/entità:** flame_bloc · FlameBlocProvider · BLoC · Flame docs

---

### flame_rive — pub.dev
**source_id:** 0ed8dbd8-5cf5-4586-96e0-42f7c1412ac4 · **tipo:** url
**sostanza:** Pagina pub.dev di flame_rive v1.11.1: bridge package per animazioni Rive in Flame. 42 likes, 140 punti, 1.84k download. Dipende da flame e rive. Pubblicato da flame-engine.org, licenza MIT, supporta tutte le piattaforme.
**keyword/entità:** flame_rive · Rive · animazioni · pub.dev · bridge package · flame-engine.org

---

### flame_rive — pub.dev (dup)
**source_id:** 731b183f-ad9f-4092-9a7f-36dc94b666b9 · **tipo:** url
**sostanza:** Duplicato flame_rive pub.dev.
**keyword/entità:** flame_rive · Rive · animazioni · pub.dev

---

### flame_rive — Flame docs (how to use)
**source_id:** 47b10d7e-eb57-4037-bfc5-d63f80062bff · **tipo:** url
**sostanza:** Documentazione ufficiale flame_rive: come caricare un file .riv con loadArtboard(), creare StateMachine, usare RiveComponent con data binding (ViewModelInstance, ViewModelInstanceNumber) per animazioni interattive. Nota: state machine inputs deprecati in Rive 0.14.x.
**keyword/entità:** flame_rive · loadArtboard · StateMachine · RiveComponent · data binding · ViewModelInstance · animazioni

---

### flame_rive — Flame docs (dup)
**source_id:** 7689700c-1cfe-4f19-80c3-1b8daf19e8c3 · **tipo:** url
**sostanza:** Duplicato documentazione flame_rive Flame docs.
**keyword/entità:** flame_rive · RiveComponent · StateMachine · Rive

---

### flame_tiled — Flame docs (TiledComponent, TileAtlas, TileStack)
**source_id:** 341bfcdd-dde0-474c-a0d5-eebe9c5937f6 · **tipo:** url
**sostanza:** Documentazione ufficiale flame_tiled: TiledComponent.load() per parsing TMX, TileStack per animazioni su colonne di tile, TileAtlas per packing multi-tileset (4096×4096 web, 8192×8192 altre), ignoreFlip per performance, troubleshooting ghost lines da floating point.
**keyword/entità:** flame_tiled · TiledComponent · TileStack · TileAtlas · TMX · atlasMaxX · ignoreFlip · ghost lines

---

### flame_tiled — Flame docs (dup)
**source_id:** 6788f59d-2855-4e34-ac97-14c4eb96a71f · **tipo:** url
**sostanza:** Duplicato documentazione flame_tiled Flame docs.
**keyword/entità:** flame_tiled · TiledComponent · TileAtlas · Flame docs

---

### flame_tiled foreground SO — come disegnare foreground
**source_id:** 601e0de9-a6e9-422c-839b-b1df4aa6e3d9 · **tipo:** url
**sostanza:** Domanda Stack Overflow su come disegnare layer foreground in flame_tiled (player renderizzato dietro il tetto): flame_tiled renderizza tutto come SpriteBatch piatto, soluzione tramite setLayerVisibility, flame_tiled_utils, o flame_spatial_grid per layer separati con priority.
**keyword/entità:** flame_tiled · foreground · layer · priority · setLayerVisibility · SpriteBatch · Stack Overflow

---

### flame_tiled SO beginner — Cloudflare blocked
**source_id:** f9ece896-9d8f-4124-9750-03902c5e39bd · **tipo:** url
**sostanza:** Contenuto non estraibile: Cloudflare security block (~513 char). Domanda SO su flame_tiled per principianti.
**keyword/entità:** flame_tiled · Stack Overflow · Cloudflare blocked

---

### kurtome/leap — GitHub repo
**source_id:** 645cf97e-8de3-4520-b357-79272b391f79 · **tipo:** url
**sostanza:** Repository GitHub del toolkit Leap (kurtome): toolkit opinionated per platformer 2D su Flame con fisica AABB custom (no Forge2D), integrazione Tiled (layer Ground e Metadata), PhysicalEntity, JumperCharacter, MovingPlatform, Ladder, AnchoredAnimationGroup, EntityStatus e slow motion debug. 53 stelle, 19 fork, MIT.
**keyword/entità:** Leap · kurtome · platformer · AABB · PhysicalEntity · JumperCharacter · MovingPlatform · Ladder · Tiled · GitHub

---

### kurtome/leap — GitHub repo (dup)
**source_id:** 68a05aa3-148e-47fc-a829-8e8f1ac6bce5 · **tipo:** url
**sostanza:** Duplicato kurtome/leap GitHub.
**keyword/entità:** Leap · kurtome · platformer · AABB · Flame

---

### flame_tiled SO — new to Flame and Tiled (getLayer, ObjectGroup)
**source_id:** 129365d1-b7a7-469f-b039-f91c437b2319 · **tipo:** url
**sostanza:** Domanda/risposta SO su come accedere ai layer da TiledComponent: uso di tileMap.getLayer<ObjectGroup>('NomeLayer'), mapping tipi Tiled→tiled.dart (TileLayer, ObjectGroup, ImageLayer, Group), iterare oggetti per spawn entità di gioco.
**keyword/entità:** flame_tiled · getLayer · ObjectGroup · TileLayer · tileMap · spawn · Stack Overflow

---

### flame_tiled SO (dup)
**source_id:** b8becf5c-7d17-49a9-92a9-a681d8ebdd7e · **tipo:** url
**sostanza:** Duplicato SO flame_tiled/getLayer.
**keyword/entità:** flame_tiled · getLayer · ObjectGroup · Stack Overflow

---

### shorebird_code_push — pub.dev
**source_id:** aeff1f1a-7d37-43b8-91b1-4d0e0249433a · **tipo:** url
**sostanza:** Pagina pub.dev di shorebird_code_push v2.0.6: package Dart per controllare e scaricare aggiornamenti Shorebird dall'app. Fornisce ShorebirdUpdater con readCurrentPatch(), checkForUpdate(), update(); supporta tracks (stable/beta/custom). 480 likes, 149k download, MIT.
**keyword/entità:** shorebird_code_push · ShorebirdUpdater · readCurrentPatch · checkForUpdate · UpdateTrack · OTA · code push

---

### shorebird_code_push — pub.dev (dup)
**source_id:** c472f923-7810-4ac5-800e-29b380279cfe · **tipo:** url
**sostanza:** Duplicato shorebird_code_push pub.dev.
**keyword/entità:** shorebird_code_push · ShorebirdUpdater · OTA · Shorebird

---

## b08a097f · Graphify — framework tecnico e clustering — [graphify] · 17 fonti

### Architettura Graphify: Clustering, CLI e Sviluppo Flutter
- **source_id:** 0caf5d3c-376c-4089-b8dd-fcfde5b2f6f0 · **tipo:** text (~4.5k char)
- **sostanza:** Indice tecnico/mappatura delle fonti del notebook visto "da sviluppatore Graphify": tabella
  metadati (S1-S13: debriefing edge-weighting & clustering, analisi Claude Code CLI, articolo Pine), e indice
  per temi — logica core edge-weight-mode (weight=confidence*distance), architettura CLI di riferimento
  (ActionRunner/ContextManager/PromptBuilder, variabili CLAUDE_CODE_*), e il pattern DI di Pine per Flutter.
- **keyword/entità:** edge-weight-mode · confidence*distance · clustering gravitazionale · Claude Code CLI ·
  CLAUDE_PERSIST · Pine DI · 4 layer Flutter

### GitHub - safishamsi/graphify (pagina repo)
- **source_id:** 075e8693-8dda-4421-87ae-896cc184ba4c · **tipo:** url (~45k char)
- **sostanza:** Snapshot della pagina GitHub del repo graphify di Safi Shamsi (54.4k star, 5.8k fork, v8,
  0.8.20): skill per AI coding assistant che mappa un'intera cartella (codice, SQL, doc, PDF, immagini, video)
  in un knowledge graph interrogabile. README completo: install (pacchetto PyPI graphifyy), piattaforme
  supportate, estrazione AST locale via tree-sitter, GRAPH_REPORT.md (god nodes, confidence EXTRACTED/INFERRED), comandi e privacy.
- **keyword/entità:** safishamsi/graphify · 54.4k star · graphifyy · tree-sitter AST · Leiden · GRAPH_REPORT ·
  god nodes · MCP server · /graphify query

### GitHub - safishamsi/graphify (pagina repo) [duplicato]
- **source_id:** 1e78a4d3-73fd-4868-b010-e2bea5e9c7b5 · **tipo:** url
- **sostanza:** Duplicato della stessa pagina GitHub del repo graphify (stesso contenuto di 075e8693): README,
  install, comandi, file types, privacy. Voce marcata come dup.
- **keyword/entità:** dup · safishamsi/graphify · README · knowledge graph

### Logica Gravitazionale e Clustering Modulare in Graphify
- **source_id:** ac9384b8-adad-4eed-a85c-07f01b8917a2 · **tipo:** text (~3.9k char)
- **sostanza:** Approfondimento tecnico sulla logica di clustering gravitazionale di Graphify: formula core
  weight=confidence×distance, le variabili (confidence 0-1 come "forza del segnale"/massa, distance topologica,
  decadimento weight×distance^-α con α=2 = legge dell'inverso del quadrato), le edge-weight-mode (inverse degree,
  logarithmic inverse, linear/square inverse distance) e l'impatto sull'algoritmo di Louvain per il community detection.
- **keyword/entità:** clustering gravitazionale · weight=confidence×distance · decadimento α · inverse degree ·
  Louvain · debiti tecnici · micro-servizi

### Pine — A lightweight architecture helper for Flutter (Medium, PDF)
- **source_id:** 95876625-9c3f-4d18-acfb-38a67a7264c0 · **tipo:** image (PDF salvato come immagini)
- **sostanza:** PDF dell'articolo Medium di Angelo Cassano su Pine (architecture helper per Flutter). Il
  gateway lo restituisce come immagini (URL googleusercontent), testo non estraibile via OCR. Il tema
  (DI/layer per Flutter) è documentato dalle altre fonti testuali del notebook.
- **keyword/entità:** Pine · Flutter · dependency injection · Medium · PDF-immagine

### framework tecnico e clustering — immagine 1–4 · schermata chat 1–8
- **source_id:** 0e466bde (img1) · 0d873d88 (img2) · 6fc3fe2b (img3) · 598662d3 (img4) · 6b8220de (chat1) · 9713dd6c (chat2) · ab89ab19 (chat3) · d37bdfea (chat4) · 4223d1d6 (chat5) · 18432d5c (chat6) · 0cbafb88 (chat7) · 269e0b79 (chat8) · **tipo:** image (PNG)
- **sostanza:** Dodici screenshot (4 immagini + 8 schermate di chat) a corredo del notebook sul framework
  tecnico/clustering di Graphify. `source_get_content` su immagini restituisce solo URL googleusercontent:
  testo non estraibile, voci basate sulla provenienza. Documentano visivamente le discussioni su edge-weight-mode,
  clustering e CLI già coperte dalle fonti testuali del notebook.
- **keyword/entità:** screenshot · schermate chat · clustering · edge-weight-mode · provenienza (no OCR)

---

## b1480d25 · Dagstuhl 22372 — report knowledge engineering — [metodo] · 58 fonti

### Dagstuhl Report 22372 (documento principale)
- **source_id:** 026966da · **tipo:** pdf
- **sostanza:** Report ufficiale del Dagstuhl Seminar 22372 "Knowledge Graphs and Knowledge Engineering" (settembre 2022), pubblicato su Dagstuhl Reports Vol.12(9):60-120, 2023. Raccoglie contributi di ~30 ricercatori su knowledge graphs, knowledge engineering, ontologie, rappresentazione della conoscenza, sistemi esperti, e integrazione con ML. Include gruppi di lavoro su: quality, lifecycle, neuro-symbolic, applications.
- **keyword/entità:** Dagstuhl · knowledge graphs · knowledge engineering · ontologia · rappresentazione della conoscenza · neuro-symbolic · Dagstuhl Reports · seminar 22372

### Università di Napoli / UNINA — documento amministrativo
- **source_id:** 93770036 · **tipo:** pdf
- **sostanza:** Documento amministrativo dell'Università degli Studi di Napoli Federico II (229K caratteri). Contiene testi burocratici/accademici in italiano: regolamenti, bandi, verbali. Non pertinente al tema knowledge engineering del notebook; probabilmente incluso per errore o come contesto istituzionale.
- **keyword/entità:** UNINA · Università Napoli Federico II · documento amministrativo · italiano

### Constraint Networks — LIRMM
- **source_id:** d0550cff · **tipo:** url
- **sostanza:** Pagina/documento del LIRMM (Laboratoire d'Informatique, de Robotique et de Microélectronique de Montpellier) sui Constraint Networks. Tratta modelli formali per la rappresentazione e risoluzione di problemi a vincoli (CSP), con applicazioni in scheduling, configurazione e ragionamento automatico.
- **keyword/entità:** constraint networks · CSP · LIRMM · Montpellier · scheduling · ragionamento · vincoli

### Excalidraw Diagram Skill — documento interno
- **source_id:** 3e58af7a · **tipo:** text
- **sostanza:** Documento interno (67K caratteri) che descrive una skill per Claude Code per la generazione di diagrammi Excalidraw. Specifica comandi, formato JSON per elementi visivi, tipi di nodi/archi, e workflow per creare diagrammi architetturali e flussi come output di agenti AI.
- **keyword/entità:** Excalidraw · Claude Code · skill · diagrammi · JSON · architettura · agent

### LLM Wiki — GitHub Gist (Karpathy + sqz tool)
- **source_id:** c6c950b1 · **tipo:** url
- **sostanza:** GitHub Gist contenente il post originale di Andrej Karpathy sull'LLM Wiki (compilazione di conoscenza da raw sources a wiki strutturata via LLM), più documentazione del tool sqz per la compressione semantica di token. Descrive il pattern di knowledge compilation come alternativa a RAG.
- **keyword/entità:** Karpathy · LLM Wiki · knowledge compilation · sqz · token compression · RAG · GitHub Gist

### La Mente Artificiale — Piero Scaruffi
- **source_id:** 2a9e738c · **tipo:** text
- **sostanza:** Libro di Piero Scaruffi "La Mente Artificiale" (292K caratteri). Storia dell'intelligenza artificiale e delle scienze cognitive: dalle origini della logica formale, ai sistemi esperti, alle reti neurali, alla robotica, alla coscienza artificiale. Copertura storica da Aristotele a fine anni 2000.
- **keyword/entità:** Scaruffi · intelligenza artificiale · scienze cognitive · sistemi esperti · reti neurali · storia AI · mente · coscienza

### Knowledge Compilation for FO2 (arXiv)
- **source_id:** a95b49c5 · **tipo:** url
- **sostanza:** Paper arXiv sulla compilazione di conoscenza per la logica del primo ordine a due variabili (FO2) in formato DNNF (Decomposable Negation Normal Form). Studia la complessità computazionale della compilazione e propone algoritmi per rendere il ragionamento tractable su formule FO2.
- **keyword/entità:** knowledge compilation · FO2 · DNNF · logica primo ordine · complessità computazionale · ragionamento tractable · arXiv

### PHD DISSERTATION — Kaczor 2014 (AGH Kraków)
- **source_id:** eceafdd1 · **tipo:** pdf
- **sostanza:** Tesi di dottorato di Agnieszka Kaczor (AGH Kraków, 2014) sui metodi di formalizzazione della conoscenza per l'interoperabilità semantica nelle rule bases (717K caratteri). Tratta RuleML, SWRL, N3, OWL, e framework per la traduzione tra formalismi di regole; include casi d'uso in medicina e e-government.
- **keyword/entità:** knowledge formalization · semantic interoperability · rule bases · RuleML · SWRL · OWL · N3 · AGH Kraków · tesi dottorato · 2014

### Retrieval as Reasoning — LLM-Wiki (arXiv 2605.25480)
- **source_id:** d09bd971 · **tipo:** url
- **sostanza:** Paper arXiv "Retrieval as Reasoning: Self-Evolving Agent-Native Retrieval via LLM-Wiki" (72K caratteri). Propone un sistema in cui la conoscenza è pre-compilata in wiki strutturata, l'agente naviga per traversal compositivo (non similarity matching), e un Error Book mantiene la struttura affidabile. Dimostra che RAG tradizionale è inferiore su query multi-hop rispetto a questo approccio.
- **keyword/entità:** retrieval as reasoning · LLM-Wiki · agent-native retrieval · traversal compositivo · Error Book · multi-hop · knowledge compilation · arXiv 2605.25480

### STRUMENTI E METODOLOGIE — Tesi UNIVPM
- **source_id:** 536e35f5 · **tipo:** pdf
- **sostanza:** Tesi di laurea triennale "Engineering Design: Strumenti e Metodologie applicate a Sistemi di Automazione Industriale" (Università Politecnica delle Marche, A.A. 2021/2022, autore Alessandro Capodaglio). Tratta modelli di engineering design (Shigley, Pahl-Beitz, Ohsuga, Earle), edge computing, IPA (Intelligent Process Automation), AI applicata all'automazione, AR, additive manufacturing.
- **keyword/entità:** engineering design · automazione industriale · UNIVPM · Shigley · Pahl-Beitz · IPA · edge computing · augmented reality · additive manufacturing · tesi laurea

### Synthadoc — GitHub README
- **source_id:** ec47b25e · **tipo:** url
- **sostanza:** README del progetto open-source Synthadoc (v0.8.0, Python, AGPL-3.0): motore di knowledge compilation da sorgenti eterogenee (YouTube con timestamp, web, PDF) verso wiki strutturata. Offre BM25+vector search, CLI completa, pipeline configurabile. Il README documenta installazione, comandi CLI, architettura e configurazione.
- **keyword/entità:** Synthadoc · knowledge compilation · YouTube ingest · BM25 · vector search · Python · AGPL-3.0 · v0.8.0 · CLI · open source

### Synthadoc: From YouTube to Wiki v0.3.0 — DEV Community
- **source_id:** 7e0c51ff · **tipo:** url
- **sostanza:** Articolo DEV Community di Paul Chen che presenta Synthadoc v0.3.0: pipeline da YouTube (con timestamps) a wiki strutturata via LLM, con web search fan-out per arricchire il contenuto. Descrive il flusso di ingestione video, chunking, generazione wiki, e casi d'uso pratici.
- **keyword/entità:** Synthadoc · YouTube · wiki · timestamps · web search · fan-out · Paul Chen · DEV Community · v0.3.0
