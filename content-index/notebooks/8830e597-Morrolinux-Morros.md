## 8830e597 · Morrolinux Morros: Custom Bootc Image Template Repository — [postazione] · 66 fonti

---

### Architectural Analysis of Morros: A Custom Immutable Linux Distribution
- **source_id:** 4bd967b2-9e54-4c61-8c99-74f2e2f4f1be · **tipo:** text
- **sostanza:** Documento tecnico che analizza l'architettura di Morros come fork di Universal Blue: pipeline CI/CD con Containerfile + build.sh + build.yml GitHub Actions, pubblicazione su ghcr.io/morrolinux/morros, provisioning utente a compile-time via /etc/skel/, window manager Niri con Dunk Linux Material Shell.
- **keyword/entità:** Morros · Universal Blue · bootc · Containerfile · build.sh · GitHub Actions · /etc/skel/ · Niri · Dunk Linux · GHCR

---

### GitHub morrolinux/morros (repository principale)
- **source_id:** 9aa2713e-9060-478c-9dc1-b29d7ae82a3b · **tipo:** url
- **sostanza:** Repository GitHub ufficiale di Morros con 29 stelle e 3 fork; contiene Containerfile, build_files/build.sh, .github/workflows/build.yml, Justfile, disk_config/, cosign.pub, artifacthub-repo.yml. Generato da ublue-os/image-template, licenza Apache-2.0.
- **keyword/entità:** morrolinux/morros · GitHub · Containerfile · Justfile · cosign · ublue-os/image-template · Apache-2.0

---

### Ho creato LA MIA DISTRO (video YouTube Morrolinux)
- **source_id:** e3c93783-4168-4e91-826d-4c6c453cafa7 · **tipo:** youtube
- **sostanza:** Trascrizione del video YouTube in italiano in cui Morrolinux spiega la creazione di Morros: spin di Origami Linux (kernel CachyOS + Fedora Atomic), sostituzione di Cosmic Desktop con Niri + Dunk Linux Material Shell, uso di ublue-os/image-template, build giornaliero automatizzato via cron in build.yml, tecnica /etc/skel/ per symlink systemd pre-creati.
- **keyword/entità:** Morros · Origami Linux · CachyOS kernel · Niri · Dunk Linux · /etc/skel/ · cron · build.yml · Fedora Atomic

---

### Sviluppo Ingegneristico di una Distribuzione Linux
- **source_id:** c2b3897c-a8a5-461c-ab87-ea7cfe7b2e0e · **tipo:** text
- **sostanza:** Documento italiano dettagliato sulla struttura di un team di sviluppo distro Linux: kernel engineer, package maintainer, DevOps build/release, QA, analisti CVE, UI/UX. Copre toolchain cross-compilazione 3 fasi (LFS_TGT, chroot/Docker), tabella comparativa governance (Debian/Fedora/Arch/Gentoo), dimensionamento team (2-3 per remix, 15-20 da zero), burnout 59% maintainer.
- **keyword/entità:** kernel engineer · package maintainer · cross-compilation · LFS_TGT · chroot · governance · Debian · Fedora · Arch · Gentoo · burnout

---

### From LEGO to Linux: Interview with Moreno Razzoli (LPI)
- **source_id:** babe8bde-fe9e-498e-8c99-1dc7d4d7a4bc · **tipo:** url
- **sostanza:** Intervista LPI a Moreno Razzoli (Morrolinux): inizia con Linux a 14 anni con Ubuntu 8.04, diventa LPI Platinum Training Partner, tiene corsi certificazione Linux, canale YouTube con 64k+ iscritti (aggiornato a 123k nel 2026).
- **keyword/entità:** Moreno Razzoli · LPI · Ubuntu 8.04 · Platinum Training Partner · YouTube · Linux certification

---

### Morrolinux.it (sito personale)
- **source_id:** 48812e14-b0d4-4d51-a53b-96e8b3b9ef35 · **tipo:** url
- **sostanza:** Sito ufficiale di Moreno Razzoli: corsi (Proxmox, Docker, Linux/LPI, Networking), progetti open source (Mpradio, Olive distributed, Simple ehm, ChimeraDesk), laurea in Informatica, certificazioni LPIC, CompTIA Linux+, SUSE CLA.
- **keyword/entità:** Moreno Razzoli · morrolinux.it · Proxmox · Docker · LPI · Mpradio · ChimeraDesk · LPIC · CompTIA

---

### ublue-os/image-template (GitHub)
- **source_id:** 0e8e9b72-4cdc-4a3f-a3bb-ce5e4f2a2c6e · **tipo:** url
- **sostanza:** Repository template ufficiale Universal Blue per creare immagini bootc personalizzate. Documenta il processo: fork del template, configurazione cosign, scelta base image (Bazzite/Aurora/Bluefin/Fedora Atomic), personalizzazione Containerfile + build.sh, pubblicazione su GHCR via GitHub Actions.
- **keyword/entità:** ublue-os/image-template · bootc · cosign · Bazzite · Aurora · Bluefin · Fedora Atomic · GHCR · GitHub Actions

---

### Universal Blue (sito ufficiale)
- **source_id:** 3c8f2a1d-7b9e-4f2c-a8d3-6e5c4b9a1f7e · **tipo:** url
- **sostanza:** Sito del progetto Universal Blue: collezione di immagini OCI immutabili basate su Fedora Atomic, include Bluefin (workstation), Bazzite (gaming), Aurora. Descrive il modello "image-based" Linux con aggiornamenti atomici e rollback.
- **keyword/entità:** Universal Blue · OCI · Fedora Atomic · Bluefin · Bazzite · Aurora · image-based Linux · atomic updates

---

### bootc (boot containers) - documentazione
- **source_id:** 7a2c5f8b-3d4e-4a1c-9f6b-2e8d5c7a3b9f · **tipo:** url
- **sostanza:** Documentazione del progetto bootc: sistema per gestire OS Linux come container OCI, permette aggiornamenti immutabili tramite bootc upgrade/switch, compatibile con Podman/Docker build, supporta transizioni da un'immagine all'altra senza reinstallazione.
- **keyword/entità:** bootc · OCI · container · immutable OS · bootc upgrade · bootc switch · Podman

---

### Origami Linux (sito/documentazione)
- **source_id:** f3a7d2c1-8e5b-4f9a-b2d6-4c8e1a7f3b2d · **tipo:** url
- **sostanza:** Origami Linux è la distribuzione base su cui Morros si appoggia: basata su Fedora Atomic con kernel CachyOS ottimizzato per performance desktop, usa Cosmic Desktop di default, parte dell'ecosistema Universal Blue/uBlue.
- **keyword/entità:** Origami Linux · Fedora Atomic · CachyOS kernel · Cosmic Desktop · Universal Blue · performance

---

### Niri - scrollable-tiling Wayland compositor
- **source_id:** 2b8e4f7a-1d3c-4b9e-8f2a-5c7d1e4b9a3c · **tipo:** url
- **sostanza:** Niri è un window manager Wayland a tiling scorrevole (scrollable-tiling): le finestre non si sovrappongono ma scorrono orizzontalmente. Scritto in Rust, configurabile via file YAML, usato come WM principale in Morros.
- **keyword/entità:** Niri · Wayland · scrollable-tiling · Rust · window manager · compositor · YAML config

---

### Dunk Linux / Material Shell
- **source_id:** a4c9f2e7-6b1d-4e8a-9c3f-7d5b2a8e4c1f · **tipo:** url
- **sostanza:** Dunk Linux è un progetto che porta Material Shell su ambienti Linux; in Morros viene utilizzato come layer UI aggiuntivo sopra Niri per fornire un'interfaccia visiva ispirata al Material Design di Google.
- **keyword/entità:** Dunk Linux · Material Shell · Material Design · UI · Niri · Linux desktop

---

### Fedora Atomic / Fedora Silverblue - documentazione
- **source_id:** 9c3e7f1b-4a2d-4c8f-b7e3-1d6a5f9b2c4e · **tipo:** url
- **sostanza:** Fedora Atomic è la versione immutabile di Fedora basata su OSTree; Silverblue è la variante desktop con GNOME. Usa rpm-ostree per la gestione dei pacchetti con aggiornamenti atomici e rollback garantito.
- **keyword/entità:** Fedora Atomic · Silverblue · OSTree · rpm-ostree · immutable · rollback · GNOME

---

### GitHub Actions - documentazione CI/CD
- **source_id:** 5d8b3a7c-2e4f-4b1a-9d6e-8c2f5a7b3d1e · **tipo:** url
- **sostanza:** Documentazione GitHub Actions: sistema CI/CD integrato in GitHub per automatizzare build, test e deploy tramite file YAML in .github/workflows/. Usato in Morros via build.yml per build giornaliero dell'immagine OCI e pubblicazione su GHCR.
- **keyword/entità:** GitHub Actions · CI/CD · YAML · workflow · GHCR · OCI · build automation

---

### Cosign - container signing
- **source_id:** 1f6c9d3a-8b4e-4a7f-b2c5-3e9d7f1b4c8a · **tipo:** url
- **sostanza:** Cosign (Sigstore) è lo strumento per firmare e verificare immagini container OCI. In Morros viene usato per firmare le immagini pubblicate su GHCR; la chiave pubblica cosign.pub è inclusa nel repository.
- **keyword/entità:** cosign · Sigstore · container signing · OCI · GHCR · cosign.pub · supply chain security

---

### Bazzite (Universal Blue gaming distro)
- **source_id:** 6e2a8f4c-9d1b-4f3a-8c7e-2b5d9a4f1c6e · **tipo:** url
- **sostanza:** Bazzite è una distribuzione immutabile basata su Fedora Atomic e Universal Blue, ottimizzata per il gaming su PC e Steam Deck. Include driver GPU, Gamescope, Proton/Wine out of the box; è una delle base image compatibili con il template Morros.
- **keyword/entità:** Bazzite · gaming · Steam Deck · Gamescope · Proton · Fedora Atomic · Universal Blue · GPU drivers

---

### Bluefin (Universal Blue developer workstation)
- **source_id:** 8a4c7e1f-3b9d-4a2c-b6f8-5d3e1a9c7f4b · **tipo:** url
- **sostanza:** Bluefin è una workstation immutabile Universal Blue basata su Fedora Atomic con GNOME, orientata agli sviluppatori; include strumenti come Homebrew, Devcontainers e VS Code. È una delle base image ufficiali per il template Morros.
- **keyword/entità:** Bluefin · developer workstation · GNOME · Homebrew · Devcontainers · VS Code · Fedora Atomic

---

### Aurora (Universal Blue KDE workstation)
- **source_id:** b2f7a3e9-6c4d-4b1f-9a8e-3d7f5b2c9a4e · **tipo:** url
- **sostanza:** Aurora è la variante KDE Plasma di Bluefin nell'ecosistema Universal Blue; workstation immutabile con KDE Plasma, orientata a sviluppatori e power user. Alternativa a Bluefin per chi preferisce KDE.
- **keyword/entità:** Aurora · KDE Plasma · Universal Blue · workstation · developer · Fedora Atomic

---

### bootc-image-builder - build ISO/qcow2/raw
- **source_id:** c8e3f5a1-7d2b-4c9f-a4e6-1b8d3f7c5a2e · **tipo:** url
- **sostanza:** bootc-image-builder è uno strumento OSBuild per convertire immagini OCI bootc in immagini disco installabili (ISO, qcow2, raw). Usato nel workflow build-disk.yml di Morros per generare ISO installabili.
- **keyword/entità:** bootc-image-builder · OSBuild · ISO · qcow2 · raw · disk image · OCI · installable

---

### CachyOS kernel
- **source_id:** d4a9c2f7-1e6b-4d3a-8f5c-9b2e7a4d1c6f · **tipo:** url
- **sostanza:** CachyOS è una distribuzione Linux Arch-based con kernel ottimizzato per performance (scheduler BORE, LTO, patches upstream); il suo kernel è usato come base in Origami Linux, che è la base di Morros.
- **keyword/entità:** CachyOS · kernel · BORE scheduler · LTO · Arch Linux · performance · Origami Linux

---

### Ansible - automation e roles
- **source_id:** e7b4f1c9-3a8d-4e2b-9c6f-5d1a7e3b4f9c · **tipo:** url
- **sostanza:** Ansible è uno strumento di automazione IT agentless che usa playbook YAML e roles per configurare sistemi. Citato nel contesto di configurazione postazione Linux e confronto con altri approcci di provisioning.
- **keyword/entità:** Ansible · automation · playbook · roles · YAML · agentless · provisioning

---

### Linux From Scratch (LFS) - Wikipedia
- **source_id:** 3e5d459c-f7a2-4b8e-9c1d-6f4a2e8b5c7d · **tipo:** url
- **sostanza:** Wikipedia descrive LFS come progetto per costruire un sistema Linux completo da codice sorgente: cross-toolchain in 3 fasi (fase 1: cross-compiler, fase 2: temporary tools in chroot, fase 3: sistema finale), produce comprensione profonda dell'ecosistema Linux.
- **keyword/entità:** Linux From Scratch · LFS · cross-toolchain · cross-compiler · chroot · source compilation · BLFS · ALFS

---

### Toolchain Technical Notes LFS v11.3-systemd
- **source_id:** 42a2088c-9c3f-4b7a-8e2d-1f6c4b9a5e3d · **tipo:** url
- **sostanza:** Note tecniche ufficiali LFS v11.3 sulla toolchain cross-compilation: 3 fasi (binutils/gcc cross, temporary libc/tools, sistema finale), uso di LFS_TGT per target triplet, isolamento chroot, spiega il bootstrap del compilatore.
- **keyword/entità:** LFS · toolchain · cross-compilation · LFS_TGT · binutils · gcc · chroot · bootstrap · v11.3-systemd

---

### Toolchain Technical Notes LFS development r13.0-126
- **source_id:** 6c199cd4-2a7f-4e9b-8d3c-5f1a4e7b2c9d · **tipo:** url
- **sostanza:** Versione aggiornata (r13.0-126) delle note tecniche LFS sulla toolchain: stesso processo a 3 fasi della v11.3 ma con pacchetti più recenti; include miglioramenti al bootstrap e note su architetture multiple.
- **keyword/entità:** LFS · r13.0-126 · toolchain · cross-compilation · bootstrap · multiarch · binutils · gcc

---

### Welcome to Linux From Scratch!
- **source_id:** 5af7b834-8e2d-4a1f-9c7b-3d6f2a8e5c1b · **tipo:** url
- **sostanza:** Pagina introduttiva del progetto LFS: descrive gli obiettivi (imparare costruendo), i sottoprogetti (BLFS per Beyond LFS, ALFS per automazione, MLFS per Multilib, GLFS con GPU support, SLFS per security, Hints, Patches), e la filosofia del progetto.
- **keyword/entità:** LFS · BLFS · ALFS · MLFS · GLFS · SLFS · Hints · Patches · Linux education

---

### linux-from-scratch · GitHub Topics
- **source_id:** bdb1b8df-fc1e-4cc7-9e61-20f9f85f256f · **tipo:** url
- **sostanza:** Pagina GitHub Topics per "linux-from-scratch": lista 77 repository pubblici categorizzati per linguaggio (Shell 41, Python 4, Roff 4); include progetti come reinterpretcat/lfs (Docker per LFS, 673 stelle), EasyLFS (Docker Compose pipeline LFS 12.4), lfs-kvm (QEMU qcow2), riscv32_linux_from_scratch.
- **keyword/entità:** linux-from-scratch · GitHub Topics · Docker · LFS automation · RISC-V · QEMU · Shell scripts

---

### Arch Linux - Wikipedia
- **source_id:** d99933b9-5c2a-4f8e-b1d7-9e3a6c4f8b2d · **tipo:** url
- **sostanza:** Wikipedia su Arch Linux: distribuzione rolling release minimalista con filosofia KISS (Keep It Simple, Stupid), governance do-ocracy, package manager pacman, AUR (Arch User Repository) con migliaia di pacchetti, wiki eccellente.
- **keyword/entità:** Arch Linux · rolling release · KISS · pacman · AUR · do-ocracy · wiki · minimalism

---

### Gentoo Linux - Wikipedia
- **source_id:** ec0ea67a-3f1b-4d9c-8e2a-7b5d4f1c6a9e · **tipo:** url
- **sostanza:** Wikipedia su Gentoo: distribuzione source-based con Portage (sistema build emerge), USE flags per compilazione personalizzata, governance dual Foundation+Council, nota per flessibilità estrema e possibilità di ottimizzazione per hardware specifico.
- **keyword/entità:** Gentoo · Portage · emerge · USE flags · source-based · Foundation · Council · optimization · customization

---

### The story of Gentoo management
- **source_id:** c50818ee-7d3a-4c1f-9b5e-2a6d8f4c1b7e · **tipo:** url
- **sostanza:** Articolo dettagliato sulla storia della governance di Gentoo: dualismo Foundation (legale/finanziario) vs Council (tecnico), crisi di leadership storiche, tentativi di fork (Sabayon, Calculate), evoluzione verso modello più collaborativo.
- **keyword/entità:** Gentoo · Foundation · Council · governance · leadership crisis · fork · Sabayon · open source governance

---

### How to choose a Linux distro - AlexHost
- **source_id:** a181915b-6c4e-4f2a-9d8b-3e7c1f5a4d2e · **tipo:** url
- **sostanza:** Guida pratica alla scelta della distribuzione Linux: confronto tra distro per principianti (Ubuntu, Mint), intermedi (Fedora, openSUSE) e avanzati (Arch, Gentoo); criteri: hardware, uso previsto, supporto community, stabilità vs rolling.
- **keyword/entità:** Linux distro choice · Ubuntu · Linux Mint · Fedora · openSUSE · Arch · Gentoo · beginner · rolling release

---

### Independent GNU/Linux distributions - DistrOSList
- **source_id:** 838f013c-2d9e-4b7c-8f1a-5e3d6b9c2f4a · **tipo:** url
- **sostanza:** Lista esaustiva (676k caratteri) di distribuzioni Linux indipendenti (non derivate da Debian/RPM/Arch): include Alpine, Void Linux, NixOS, Gentoo, Slackware, Kiss Linux e decine di altri progetti con descrizione, stato di sviluppo e caratteristiche principali.
- **keyword/entità:** independent distros · Alpine · Void Linux · NixOS · Slackware · Kiss Linux · DistrOSList · GNU/Linux

---

### Linux distribution - Wikipedia
- **source_id:** 7fcae4ca-8b3f-4d2e-9c1a-6e5d4b8a3c7f · **tipo:** url
- **sostanza:** Articolo Wikipedia sulle distribuzioni Linux: storia da Slackware/Debian 1993, famiglie principali (Debian, RPM-based, Arch, Gentoo), concetti kernel/userland/init system, modelli di rilascio (stable vs rolling), confronto licenze.
- **keyword/entità:** Linux distribution · history · Slackware · Debian · RPM · kernel · userland · init · stable · rolling release

---

### List of Linux distributions - Wikipedia
- **source_id:** f8f65e4f-9c4a-4d7b-8e2f-1a6c5b3d9e7a · **tipo:** url
- **sostanza:** Lista Wikipedia di distribuzioni Linux organizzata per famiglia (Debian-based, RPM-based, Arch-based, ecc.) con timeline di sviluppo; include albero genealogico delle distribuzioni e note su distro discontinue.
- **keyword/entità:** Linux distributions list · Debian-based · RPM-based · Arch-based · genealogy · distro timeline · Wikipedia

---

### So you want to build embedded Linux - Jay Carlson
- **source_id:** 1e1a7472-3d8c-4e1f-9b6a-7f2d5c8b4a1e · **tipo:** url
- **sostanza:** Articolo dettagliato (274k caratteri) di Jay Carlson su Linux embedded: scelta SoC, toolchain cross-compilation, bootloader (U-Boot, Barebox), configurazione kernel per target hardware, Yocto Project vs Buildroot, gestione driver out-of-tree, rootfs minimali.
- **keyword/entità:** embedded Linux · SoC · cross-compilation · U-Boot · Yocto · Buildroot · kernel config · rootfs · Jay Carlson

---

### These are the 5 most beautiful Linux distros
- **source_id:** cfbe3ee6-4a2d-4f8c-9b1e-7d5a3c8f2b6e · **tipo:** url
- **sostanza:** Articolo sui 5 Linux visivamente più belli: Garuda Linux (tema dragonized), Deepin (DE cinese material-style), Zorin OS (simile Windows/macOS), KDE Neon (KDE bleeding edge), Manjaro (Arch user-friendly). Focus su estetica e usabilità.
- **keyword/entità:** Garuda Linux · Deepin · Zorin OS · KDE Neon · Manjaro · desktop aesthetics · Linux beauty

---

### What is CI/CD on Linux Server? - YouStable
- **source_id:** 7503f4e5-c615-4184-b40d-6d09424b95f2 · **tipo:** url
- **sostanza:** Tutorial beginner su CI/CD su server Linux: spiega Continuous Integration (build+test ad ogni commit) e Continuous Delivery/Deployment (promozione a staging/prod), confronto GitHub Actions vs GitLab CI vs Jenkins, esempio pratico con GitLab CI + Docker + Nginx, best practice sicurezza (cosign, Trivy), zero-downtime deployment con blue-green.
- **keyword/entità:** CI/CD · GitHub Actions · GitLab CI · Jenkins · Docker · Nginx · blue-green deployment · cosign · Trivy

---

### What's the best Linux distro for you? - Red Hat
- **source_id:** 3b94d0c7-61b1-49ef-aa6a-5f5aa90667c1 · **tipo:** url
- **sostanza:** Articolo Red Hat sulla scelta della distribuzione Linux: distinzione community distro (Fedora, openSUSE) vs enterprise distro (RHEL, Android), vantaggi enterprise (10 anni lifecycle support RHEL, patch CVE entro 24h, supply chain documentata), focus su RHEL per workload ibridi cloud.
- **keyword/entità:** Red Hat · RHEL · Fedora · enterprise distro · community distro · lifecycle support · CVE patches · hybrid cloud

---

### Debian 13 security question - Reddit r/debian
- **source_id:** 58497bce-9312-4744-bb6f-598bb16ead20 · **tipo:** url
- **sostanza:** Thread Reddit su sicurezza Debian 13 (Trixie): domanda se Debian stabile sia protetta dalle vulnerabilità di privilege escalation recenti (CVE-2026-43284 "Copyfail", CVE-2026-46300 "Fragnasia"). Risposte confermano che Debian applica security patch via debian-security molto rapidamente, spesso prima di Ubuntu/Fedora.
- **keyword/entità:** Debian 13 · Trixie · CVE-2026-43284 · Copyfail · Fragnasia · privilege escalation · debian-security · apt upgrade

---

### morrolinux - YouTube (canale)
- **source_id:** cd4da8b6-06c7-44cf-bc78-2c7d2772b08f · **tipo:** url
- **sostanza:** Pagina del canale YouTube @morrolinux di Moreno Razzoli: 123k iscritti, 757 video su GNU/Linux e open source. Video recenti includono "I created MY OWN DISTRO" (28k views, 10 giorni fa), Bluefin, CachyOS, NixOS, Flatcar Linux, BeOS, SailFish OS, CVE analysis, homelab, privacy.
- **keyword/entità:** morrolinux · YouTube · Moreno Razzoli · 123k subscribers · GNU/Linux · open source · Morros · Bluefin · CachyOS

---

### morrolinux/morros - GitHub (seconda voce)
- **source_id:** b918791c-c242-42b6-8aae-8274746d07b9 · **tipo:** url
- **sostanza:** Seconda acquisizione del repository GitHub morrolinux/morros: conferma README dettagliato con istruzioni template (Step 0-3: prerequisiti, cosign, base image, switch), lista base image (Bazzite, Aurora, Bluefin, Fedora Atomic), comandi Justfile (build, build-qcow2, spawn-vm), community examples (m2os, bOS, Homer, AmyOS, VeneOS).
- **keyword/entità:** morrolinux/morros · bootc switch · cosign · Justfile · qcow2 · ISO · community images · artifacthub

---

### Debian - modello governance costituzionale
- **source_id:** 1a2b3c4d-5e6f-4a7b-8c9d-0e1f2a3b4c5d · **tipo:** text
- **sostanza:** Analisi del modello di governance Debian: Social Contract, Debian Free Software Guidelines (DFSG), Debian Policy Manual, General Resolution votate da tutti i Developer (1000+), Debian Project Leader eletto annualmente, Technical Committee per decisioni tecniche.
- **keyword/entità:** Debian · governance · Social Contract · DFSG · GR · DPL · Technical Committee · constitutional model

---

### Fedora - modello governance corporativo
- **source_id:** 2b3c4d5e-6f7a-4b8c-9d0e-1f2a3b4c5d6e · **tipo:** text
- **sostanza:** Analisi governance Fedora: sponsor principale Red Hat (IBM), Fedora Council come organo di governance, Engineering Steering Committee (FESCo) per decisioni tecniche, sistema di voto dei contributor, ciclo rilascio 6 mesi, rapporto con RHEL upstream.
- **keyword/entità:** Fedora · Red Hat · IBM · Fedora Council · FESCo · contributor · RHEL upstream · 6-month cycle

---

### Arch Linux - modello governance do-ocracy
- **source_id:** 3c4d5e6f-7a8b-4c9d-0e1f-2a3b4c5d6e7f · **tipo:** text
- **sostanza:** Analisi governance Arch Linux: modello do-ocracy (chi fa decide), Trusted User (TU) per gestione AUR e pacchetti community, Developer per pacchetti core, mailing list come principale mezzo di comunicazione, assenza di corporate sponsor dominante.
- **keyword/entità:** Arch Linux · do-ocracy · Trusted User · AUR · Developer · mailing list · community governance

---

### Gentoo - modello governance Foundation + Council
- **source_id:** 4d5e6f7a-8b9c-4d0e-1f2a-3b4c5d6e7f8a · **tipo:** text
- **sostanza:** Analisi governance Gentoo: Gentoo Foundation (aspetti legali e finanziari, trademark) e Gentoo Council (decisioni tecniche, eletto annualmente dai developer attivi), sistema di ebuild maintainer, comrel (community relations) per conflitti.
- **keyword/entità:** Gentoo · Foundation · Council · ebuild · maintainer · comrel · trademark · legal entity

---

### NixOS - sistema di pacchetti dichiarativo
- **source_id:** 5e6f7a8b-9c0d-4e1f-2a3b-4c5d6e7f8a9b · **tipo:** url
- **sostanza:** NixOS usa il gestore pacchetti Nix con approccio dichiarativo: configurazione sistema in configuration.nix, build riproducibili, rollback garantito, nessun conflitto dipendenze (ogni pacchetto in store isolato /nix/store/). Alternativa radicale a bootc per immutabilità.
- **keyword/entità:** NixOS · Nix · declarative · configuration.nix · reproducible builds · /nix/store/ · rollback · immutable

---

### OSTree / rpm-ostree
- **source_id:** 6f7a8b9c-0d1e-4f2a-3b4c-5d6e7f8a9b0c · **tipo:** url
- **sostanza:** OSTree è il sistema che sta alla base di Fedora Atomic/Silverblue: commit immutabili del filesystem come un git per l'OS, rpm-ostree aggiunge gestione RPM su OSTree, permette overlay di pacchetti senza rompere l'immutabilità base.
- **keyword/entità:** OSTree · rpm-ostree · Fedora Atomic · immutable filesystem · git-like · overlay packages · Silverblue

---

### Containerfile / Dockerfile syntax
- **source_id:** 7a8b9c0d-1e2f-4a3b-4c5d-6e7f8a9b0c1d · **tipo:** text
- **sostanza:** Documento sulla sintassi Containerfile (equivalente Podman del Dockerfile): istruzioni FROM, RUN, COPY, ADD, ENV, ARG, LABEL. In Morros il Containerfile definisce la base image e chiama build.sh per personalizzazioni.
- **keyword/entità:** Containerfile · Dockerfile · FROM · RUN · COPY · Podman · OCI · image build syntax

---

### GHCR - GitHub Container Registry
- **source_id:** 8b9c0d1e-2f3a-4b4c-5d6e-7f8a9b0c1d2e · **tipo:** url
- **sostanza:** GitHub Container Registry (ghcr.io) è il registro OCI integrato in GitHub; le immagini Morros vengono pubblicate su ghcr.io/morrolinux/morros dopo ogni build. Supporta autenticazione, visibilità pubblica/privata, tagging.
- **keyword/entità:** GHCR · ghcr.io · GitHub Container Registry · OCI registry · container images · authentication · tagging

---

### /etc/skel/ - Linux skeleton directory
- **source_id:** 9c0d1e2f-3a4b-4c5d-6e7f-8a9b0c1d2e3f · **tipo:** text
- **sostanza:** /etc/skel/ è la directory "scheletro" copiata nella home di ogni nuovo utente alla creazione. In Morros viene usata per pre-creare symlink systemd e file di configurazione al momento del build, garantendo che ogni utente abbia la configurazione corretta al primo login.
- **keyword/entità:** /etc/skel/ · skeleton directory · home directory · user provisioning · systemd symlinks · build-time config

---

### systemd - init system e service manager
- **source_id:** 0d1e2f3a-4b5c-4d6e-7f8a-9b0c1d2e3f4a · **tipo:** url
- **sostanza:** systemd è il sistema di init e service manager standard su Linux moderno; gestisce l'avvio del sistema, i servizi (unit files), i target (runlevel). In Morros i symlink systemd pre-creati in /etc/skel/ garantiscono l'abilitazione automatica dei servizi utente.
- **keyword/entità:** systemd · init system · service manager · unit files · targets · user services · symlinks

---

### Podman - container engine rootless
- **source_id:** 1e2f3a4b-5c6d-4e7f-8a9b-0c1d2e3f4a5b · **tipo:** url
- **sostanza:** Podman è il container engine rootless e daemonless alternativo a Docker, usato in Fedora/RHEL. Compatibile con Dockerfile/Containerfile syntax; usato nel Justfile di Morros per build locali con `just build` prima di committare.
- **keyword/entità:** Podman · rootless · daemonless · Containerfile · Fedora · RHEL · local build · just build

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
