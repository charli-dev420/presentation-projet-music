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

This repository presents my music and MAO projects through two separate product lines:

- **DAWWW-CORE** — a local-first browser DAW built around Web Audio and portable `.dw` projects.
- **UnicorSoundEngine** — a separate VST instrument and effects ecosystem.

DAWWW-CORE does not load native VST plugins in the browser.

## At a glance

| Line | Public status | Main focus |
| --- | --- | --- |
| **DAWWW-CORE desktop** | Implemented · stabilisation and release preparation | Browser DAW, playback, editing, save / reopen, export |
| **`.dw` project format** | Implemented | Portable local-first project continuity |
| **Android target** | Active test target | Capacitor integration and device validation |
| **UnicorSoundEngine** | Separate product line | VST instruments, FX, manuals, packaging and distribution |
| **FX and audition tools** | Supporting product tools | Listening review, presets, documentation and release decisions |

---

## DAWWW-CORE

DAWWW-CORE is built around a practical project loop:

```text
create → save → reopen → edit → export → continue
```

The project brings together arranger, sequencer, piano roll, mixer, instruments, sampler, built-in effects, automation, export and recovery workflows in a browser-based studio.

The `.dw` format is central: it gives the project a portable container and makes continuity easier to test, explain and review.

[DAWWW-CORE overview](docs/dawww-core.md) · [Project overview](docs/project-overview.md) · [Public proof summary](docs/proof-summary.md)

---

## UnicorSoundEngine

UnicorSoundEngine is the separate native plugin line. It covers:

- VST instruments and effects;
- presets and listening review;
- manuals and product documentation;
- packaging, product pages and download flows.

FX repositories and the audition panel are supporting parts of this product line rather than separate top-level products.

[UnicorSoundEngine](docs/unicorsoundengine.md) · [FX line](docs/fx-line.md) · [Audition and review](docs/audition-review.md)

---

## Review the project

A useful first review can focus on:

- `.dw` save / reopen / recovery;
- browser playback and editing;
- audio export;
- Android test boundaries;
- listening quality, presets and manuals for UnicorSoundEngine.

[Five-minute review](docs/quick-review.md) · [Current status](docs/current-status.md) · [FAQ](docs/faq.md)

<details>
<summary><strong>Extended documentation</strong></summary>

- [Public pack](docs/public-pack.md)
- [Visual index](docs/visual-index.md)
- [Public roadmap](docs/public-roadmap.md)
- [Open needs](docs/open-needs.md)
- [Repository notice](NOTICE.md)
- [Contact](CONTACT.md)

</details>

---

## Contact

- DAWWW-CORE: [contact@dawww-core-local.com](mailto:contact@dawww-core-local.com)
- General / UnicorSoundEngine: [unicornwhodev@gmail.com](mailto:unicornwhodev@gmail.com)

---

<h2 id="francais">🇫🇷 Français</h2>

Ce dépôt présente mes projets musique et MAO autour de deux lignes séparées :

- **DAWWW-CORE** — un DAW navigateur local-first basé sur Web Audio et les projets portables `.dw`.
- **UnicorSoundEngine** — un écosystème séparé d’instruments et effets VST.

DAWWW-CORE ne charge pas de VST natifs dans le navigateur.

## Vue rapide

| Ligne | État public | Axe principal |
| --- | --- | --- |
| **DAWWW-CORE desktop** | Implémenté · stabilisation et préparation release | DAW navigateur, playback, édition, sauvegarde / réouverture, export |
| **Format `.dw`** | Implémenté | Continuité projet portable et local-first |
| **Cible Android** | Cible de test active | Intégration Capacitor et validation appareils |
| **UnicorSoundEngine** | Ligne produit séparée | Instruments VST, FX, manuels, packaging et distribution |
| **FX et outils d’audition** | Outils produit de support | Écoute, presets, documentation et décisions de release |

## DAWWW-CORE

DAWWW-CORE est construit autour d’une boucle simple :

```text
créer → sauvegarder → rouvrir → modifier → exporter → continuer
```

Le projet réunit arrangeur, séquenceur, piano roll, mixer, instruments, sampler, effets intégrés, automation, export et récupération dans un studio navigateur.

[DAWWW-CORE](docs/dawww-core.md) · [Vue projet](docs/project-overview.md) · [Résumé des preuves](docs/proof-summary.md)

## UnicorSoundEngine

UnicorSoundEngine est la ligne plugin native séparée : instruments, effets, presets, écoute, manuels, packaging, pages produit et téléchargements.

[UnicorSoundEngine](docs/unicorsoundengine.md) · [Ligne FX](docs/fx-line.md) · [Audition et revue](docs/audition-review.md)

## Revoir le projet

Les retours les plus utiles concernent `.dw`, sauvegarde / réouverture, playback, export, Android, qualité d’écoute, presets et documentation.

[Revue en cinq minutes](docs/quick-review.md) · [État actuel](docs/current-status.md) · [FAQ](docs/faq.md)

<details>
<summary><strong>Documentation étendue</strong></summary>

- [Pack public](docs/public-pack.md)
- [Index visuel](docs/visual-index.md)
- [Roadmap publique](docs/public-roadmap.md)
- [Besoins ouverts](docs/open-needs.md)
- [Notice](NOTICE.md)
- [Contact](CONTACT.md)

</details>

## Contact

- DAWWW-CORE : [contact@dawww-core-local.com](mailto:contact@dawww-core-local.com)
- Général / UnicorSoundEngine : [unicornwhodev@gmail.com](mailto:unicornwhodev@gmail.com)
