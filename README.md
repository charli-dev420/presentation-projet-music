# DAWWW-CORE local and cross device MAO studio

<p align="center">
  <img src="assets/project-banners/daw-core.jpg" width="900" alt="DAWWW-CORE banner">
</p>

<p align="center">
  <strong>Browser DAW · Web Audio · Portable .dw projects · Android target · Separate VST ecosystem</strong>
</p>

<p align="center">
  <a href="#english">🇬🇧 English</a> · <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

This repository presents my music-tech work through two separate product lines:

- **DAWWW-CORE** — a local-first browser DAW built around Web Audio and portable `.dw` projects.
- **UnicorSoundEngine** — a separate native plugin ecosystem for instruments, effects, presets and product documentation.

DAWWW-CORE does not load native VST plugins in the browser.

## At a glance

| Line | Public status | Main focus |
| --- | --- | --- |
| **DAWWW-CORE desktop** | Implemented · stabilisation and release preparation | Browser DAW, editing, playback, save / reopen, export |
| **`.dw` project format** | Implemented | Portable local-first project continuity |
| **Android target** | Active test target | Capacitor integration and device validation |
| **UnicorSoundEngine** | Separate product line | Native instruments, FX, presets, manuals and distribution |
| **Audition and review tools** | Supporting workflow | Listening checks, preset review and release decisions |

<p align="center">
  <img src="assets/diagrams/music-portfolio-map.svg" width="900" alt="Music portfolio map separating DAWWW-CORE and UnicorSoundEngine">
</p>

## DAWWW-CORE

DAWWW-CORE is organized around a practical project loop:

<p align="center">
  <img src="assets/diagrams/dawww-core-workflow.svg" width="900" alt="DAWWW-CORE project workflow from creation to continuation">
</p>

The browser workspace brings together arranger, sequencer, piano roll, mixer, instruments, sampler, built-in effects, automation, export and recovery workflows.

The `.dw` format is central because it makes the project portable and turns save, reopen and recovery into a visible product capability rather than a hidden implementation detail.

[DAWWW-CORE details](docs/dawww-core.md) · [Portfolio overview](docs/project-overview.md) · [Public proof](docs/proof-summary.md)

## UnicorSoundEngine

UnicorSoundEngine is the separate native plugin line. It covers seven instrument families, a dedicated FX line, presets, listening review, manuals, packaging and product distribution.

The plugin line is presented separately so that the browser DAW and the native audio products remain easy to understand.

[UnicorSoundEngine](docs/unicorsoundengine.md) · [FX line](docs/fx-line.md) · [Audition and review](docs/audition-review.md)

## What can be reviewed now

A useful first review can focus on:

- the separation between the browser DAW and the native plugin line;
- the `.dw` save / reopen / recovery story;
- browser playback, editing and export;
- Android test boundaries;
- instrument, effect and preset listening quality;
- product and documentation clarity.

[Three-minute review](docs/quick-review.md) · [Current status](docs/current-status.md) · [FAQ](docs/faq.md)

<details>
<summary><strong>Extended documentation</strong></summary>

- [Public presentation pack](docs/public-pack.md)
- [Visual index](docs/visual-index.md)
- [Public roadmap](docs/public-roadmap.md)
- [Open review needs](docs/open-needs.md)
- [Repository notice](NOTICE.md)
- [Contact](CONTACT.md)

</details>

## Contact

- DAWWW-CORE: [contact@dawww-core-local.com](mailto:contact@dawww-core-local.com)
- General / UnicorSoundEngine: [unicornwhodev@gmail.com](mailto:unicornwhodev@gmail.com)

---

<h2 id="francais">🇫🇷 Français</h2>

Ce dépôt présente mes projets music-tech à travers deux lignes produit séparées :

- **DAWWW-CORE** — un DAW navigateur local-first basé sur Web Audio et les projets portables `.dw`.
- **UnicorSoundEngine** — un écosystème séparé de plugins natifs pour instruments, effets, presets et documentation produit.

DAWWW-CORE ne charge pas de VST natifs dans le navigateur.

## Vue rapide

| Ligne | État public | Axe principal |
| --- | --- | --- |
| **DAWWW-CORE desktop** | Implémenté · stabilisation et préparation release | DAW navigateur, édition, lecture, sauvegarde / réouverture, export |
| **Format `.dw`** | Implémenté | Continuité projet portable et local-first |
| **Cible Android** | Cible de test active | Intégration Capacitor et validation sur appareils |
| **UnicorSoundEngine** | Ligne produit séparée | Instruments natifs, FX, presets, manuels et distribution |
| **Outils d’audition et de revue** | Workflow de support | Écoute, revue de presets et décisions de release |

<p align="center">
  <img src="assets/diagrams/music-portfolio-map.svg" width="900" alt="Carte du portfolio séparant DAWWW-CORE et UnicorSoundEngine">
</p>

## DAWWW-CORE

DAWWW-CORE est organisé autour d’une boucle projet concrète :

<p align="center">
  <img src="assets/diagrams/dawww-core-workflow.svg" width="900" alt="Workflow DAWWW-CORE de la création à la reprise du projet">
</p>

Le workspace navigateur réunit arrangeur, séquenceur, piano roll, mixer, instruments, sampler, effets intégrés, automation, export et récupération.

Le format `.dw` est central, car il rend le projet portable et transforme la sauvegarde, la réouverture et la récupération en capacités produit visibles.

[Détails DAWWW-CORE](docs/dawww-core.md) · [Vue du portfolio](docs/project-overview.md) · [Preuves publiques](docs/proof-summary.md)

## UnicorSoundEngine

UnicorSoundEngine est la ligne séparée de plugins natifs. Elle couvre sept familles d’instruments, une ligne FX dédiée, les presets, la revue d’écoute, les manuels, le packaging et la distribution.

La séparation garde le DAW navigateur et les produits audio natifs faciles à comprendre.

[UnicorSoundEngine](docs/unicorsoundengine.md) · [Ligne FX](docs/fx-line.md) · [Audition et revue](docs/audition-review.md)

## Ce qui peut être revu maintenant

Une première revue utile peut porter sur :

- la séparation entre le DAW navigateur et la ligne de plugins natifs ;
- le parcours sauvegarde / réouverture / récupération `.dw` ;
- la lecture, l’édition et l’export dans le navigateur ;
- les limites de test Android ;
- la qualité d’écoute des instruments, effets et presets ;
- la clarté produit et documentaire.

[Revue en trois minutes](docs/quick-review.md) · [État actuel](docs/current-status.md) · [FAQ](docs/faq.md)

<details>
<summary><strong>Documentation étendue</strong></summary>

- [Pack de présentation public](docs/public-pack.md)
- [Index visuel](docs/visual-index.md)
- [Roadmap publique](docs/public-roadmap.md)
- [Besoins de revue](docs/open-needs.md)
- [Notice du dépôt](NOTICE.md)
- [Contact](CONTACT.md)

</details>

## Contact

- DAWWW-CORE : [contact@dawww-core-local.com](mailto:contact@dawww-core-local.com)
- Général / UnicorSoundEngine : [unicornwhodev@gmail.com](mailto:unicornwhodev@gmail.com)
