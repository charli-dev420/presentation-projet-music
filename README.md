# DAWWW-CORE Music Lab

<p align="center">
  <img src="assets/project-banners/daw-core.jpg" width="900" alt="DAWWW-CORE Music Lab banner">
</p>

<p align="center">
  <strong>Browser DAW · Web Audio · Project continuity · Unicorn Sound Engine · Music-tech product work</strong>
</p>

<p align="center">
  <a href="#dawww-core">DAWWW-CORE</a> ·
  <a href="#unicorn-sound-engine">Unicorn Sound Engine</a> ·
  <a href="#fx-line">FX Line</a> ·
  <a href="#audition--review">Audition & Review</a> ·
  <a href="#francais">Français</a>
</p>

---

## What this repository is

This repository is the public music-tech showcase for my main audio projects.

It presents two separate but connected product lines:

1. **DAWWW-CORE** — a local-first browser DAW built with Web Audio.
2. **Unicorn Sound Engine** — a separate ecosystem of VST instruments, FX, manuals, audition tools, and distribution surfaces.

They belong to the same music-tech direction, but they are not the same product.

**DAWWW-CORE is a web DAW. It does not load native VST plugins in the browser.**

Most source repositories are private. This public repo exists to explain the projects, show the product direction, organize proof material, and make the work easier to understand for testers, collaborators, recruiters, buyers, or technical partners.

---

## Project map

| Project | Role | Status |
| --- | --- | --- |
| **DAWWW-CORE** | Browser DAW, Web Audio engine, `.dw` project format, export, Android testing | Main product line |
| **Unicorn Sound Engine** | VST instruments, FX, manuals, packaging and distribution | Separate plugin ecosystem |
| **VST-site** | Store, accounts, Stripe, downloads, product pages and admin tooling | Distribution layer |
| **Audition Panel** | Listening and asset-review tool for presets, audio material and generated visuals | QA / review support |
| **FX repositories** | Individual JUCE VST3 / Standalone effects | Plugin family |
| **Presentation docs** | Public explanation, evidence, current status and product framing | Showcase layer |

---

## DAWWW-CORE

**DAWWW-CORE** is the priority project.

It is a local-first browser DAW focused on the parts of music software that must not break:

- creating a project;
- saving it;
- reopening it later;
- keeping the musical state coherent;
- exporting audio;
- moving through a real user workflow;
- testing the result with enough proof to trust it.

The core idea is simple:

> a music project should survive the round trip.

DAWWW-CORE is built around Web Audio, browser workflows, project persistence, `.dw` sessions, export paths, QA gates, and Android testing.

It is not a native VST host.

### What DAWWW-CORE shows

- browser-first DAW thinking;
- local-first project continuity;
- `.dw` portable session logic;
- desktop and Android testing paths;
- Web Audio instruments and built-in effects;
- export, recovery and QA work;
- product-readiness thinking.

---

## Unicorn Sound Engine

**Unicorn Sound Engine** is the separate plugin ecosystem.

It gathers instruments, FX, manuals, product pages, listening notes, packaging work, and distribution flows.

This line is useful for a different reason than DAWWW-CORE: it shows the product path around audio tools outside the browser DAW.

### What the line includes

- VST instruments;
- VST effects;
- manuals and user-facing documentation;
- listening review and audition material;
- store/download flow;
- packaging and version alignment;
- visual and brand assets.

---

## FX Line

The FX line is organized by treatment families:

- analysis;
- delay;
- distortion;
- dynamics;
- EQ / filter;
- modulation;
- pitch / time;
- reverb;
- stereo;
- creative effects;
- doubler.

These repositories are part of the Unicorn Sound Engine ecosystem. They are not DAWWW-CORE runtime modules.

The goal of this line is to turn individual effects into a coherent, documented and testable audio product family.

---

## Audition & Review

The audition and review tools exist because audio products need more than code.

A synth or FX line needs listening checks, notes, presets, review states, and practical feedback. The review tools help structure that work instead of keeping it scattered across folders, messages, and subjective memory.

They support:

- preset review;
- audio quality notes;
- asset validation;
- visual asset review;
- CSV/exportable feedback;
- product readiness decisions.

---

## Public reading path

Start here:

1. [`docs/dawww-core.md`](docs/dawww-core.md) — main browser DAW project.
2. [`docs/unicorn-sound-engine.md`](docs/unicorn-sound-engine.md) — plugin ecosystem and product family.
3. [`docs/fx-line.md`](docs/fx-line.md) — effects line and repo family.
4. [`docs/audition-review.md`](docs/audition-review.md) — listening and review workflow.
5. [`docs/current-status.md`](docs/current-status.md) — current state and what remains to prove.
6. [`docs/open-needs.md`](docs/open-needs.md) — useful feedback, testing and collaboration needs.

---

## What this repo is good for

This repo is meant for people who want to quickly understand:

- what DAWWW-CORE is;
- what Unicorn Sound Engine is;
- why they are separate;
- what is public and what remains private;
- what has been tested or documented;
- what kind of help, feedback or collaboration would be useful.

---

## Open needs

Useful help is concrete:

- DAWWW-CORE browser DAW review;
- Web Audio testing;
- Android beta feedback;
- `.dw` project continuity feedback;
- listening notes for synths and FX;
- VST packaging review;
- plugin documentation review;
- product positioning;
- technical partnership;
- funding, mission work or roles around creative tools and music software.

---

## Français

Ce dépôt est la vitrine publique de mes projets music-tech.

Il présente deux lignes séparées :

1. **DAWWW-CORE** — un DAW web local-first basé sur Web Audio.
2. **Unicorn Sound Engine** — un écosystème séparé d’instruments VST, FX, manuels, audition et distribution.

Les deux projets appartiennent au même univers music-tech, mais ils ne sont pas le même produit.

**DAWWW-CORE est un DAW navigateur. Il ne charge pas de VST natifs dans le navigateur.**

---

## DAWWW-CORE

DAWWW-CORE est le projet principal.

Le cœur du projet est la continuité musicale :

- créer une session ;
- la sauvegarder ;
- la rouvrir ;
- vérifier que l’état musical tient ;
- exporter ;
- tester les parcours réels ;
- garder des preuves lisibles.

L’objectif n’est pas seulement de produire du son.  
L’objectif est que le projet musical survive à l’aller-retour.

---

## Unicorn Sound Engine

Unicorn Sound Engine est une ligne séparée autour des instruments et effets VST.

Elle regroupe :

- instruments ;
- effets ;
- manuels ;
- presets ;
- audition ;
- packaging ;
- store ;
- téléchargements ;
- notes de release.

Cette ligne complète l’écosystème music-tech, mais elle ne remplace pas DAWWW-CORE et ne tourne pas dans le navigateur comme VST host.

---

## Ce que cette vitrine doit montrer

- DAWWW-CORE comme projet principal ;
- Unicorn Sound Engine comme ligne plugin séparée ;
- les FX comme famille produit ;
- l’audition comme outil de validation ;
- les preuves et documents utiles ;
- les besoins concrets pour tester, améliorer ou collaborer.
