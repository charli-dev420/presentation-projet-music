# DAWWW-CORE Project Overview

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

DAWWW-CORE is a local-first browser DAW focused on music project continuity.

The project is built around Web Audio, portable `.dw` sessions, audio export, recovery workflows and an Android direction through Capacitor.

Its main idea is simple: a music project should not disappear into a temporary browser session. It should be possible to create it, save it, reopen it, recover its musical state, export it and continue working.

---

## Core purpose

DAWWW-CORE addresses a practical music-production problem: keeping a session usable over time.

A DAW is not only judged by the sound it can produce while open. It also needs to preserve the work behind that sound:

```text
create → save → reopen → recover → export → continue
```

That workflow is the central product thread of DAWWW-CORE.

---

## Product surface

DAWWW-CORE brings together several music-production surfaces:

- arranger;
- sequencer;
- piano roll;
- mixer;
- instruments;
- sampler;
- effects;
- automation;
- modulation;
- project save and reload;
- audio export;
- Android target through Capacitor.

The `.dw` format is an important part of the project. It gives DAWWW-CORE a portable project container and makes the local-first direction easier to understand, test and hand over.

---

## Product direction

DAWWW-CORE is not presented as a cloud-first platform, native VST host or marketplace.

Its public direction is narrower and clearer:

- browser-first music production;
- local-first project handling;
- portable `.dw` project continuity;
- Web Audio instruments and effects;
- export and recovery workflows;
- desktop web usage;
- Android direction through Capacitor.

This makes the project easier to evaluate: the main question is whether the musical session survives the full workflow, not how many unrelated features can be listed.

---

## Relationship with Unicorn Sound Engine

DAWWW-CORE and Unicorn Sound Engine belong to the same music-tech portfolio, but they are separate product lines.

| Product | Role |
| --- | --- |
| **DAWWW-CORE** | Browser DAW / local-first music workspace. |
| **Unicorn Sound Engine** | Separate VST instrument and effect ecosystem. |

DAWWW-CORE does not load native VST plugins in the browser.

Unicorn Sound Engine covers the separate plugin path: VST instruments, effects, manuals, audition material, packaging and distribution.

---

## Public scope

This public repository is an overview and presentation layer. It is not meant to expose private source code, unreleased binaries, credentials, private proof artifacts or handover material.

Detailed evidence can be reviewed separately through a controlled buyer proof pack when a deeper technical discussion is needed.

---

## Useful review areas

Useful review can focus on concrete product behavior:

- `.dw` project creation and reopen workflow;
- save, recovery and export behavior;
- Web Audio playback and rendering behavior;
- Android readiness boundaries;
- instrument and effect listening checks;
- documentation clarity;
- release-readiness gaps.

---

## Summary

DAWWW-CORE is best understood as a browser-based MAO project with a strong local-first direction.

Its value is not only the presence of DAW features. Its value is the way those features are organized around project continuity, portability, export and recoverability.

<p align="right"><a href="#dawww-core-project-overview">↑ Back to top</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

DAWWW-CORE est un DAW navigateur local-first centré sur la continuité des projets musicaux.

Le projet s’appuie sur Web Audio, les sessions portables `.dw`, l’export audio, la récupération de session et une direction Android via Capacitor.

L’idée principale est simple : un projet musical ne doit pas disparaître dans une session temporaire du navigateur. Il doit pouvoir être créé, sauvegardé, rouvert, récupéré, exporté et continué.

---

## Rôle principal

DAWWW-CORE répond à un problème concret de MAO : garder une session utilisable dans le temps.

Un DAW ne se juge pas seulement au son qu’il produit quand il est ouvert. Il doit aussi préserver le travail derrière ce son :

```text
créer → sauvegarder → rouvrir → récupérer → exporter → continuer
```

Ce workflow est le fil conducteur du projet.

---

## Surface produit

DAWWW-CORE réunit plusieurs surfaces MAO :

- arrangeur ;
- séquenceur ;
- piano roll ;
- mixer ;
- instruments ;
- sampler ;
- effets ;
- automation ;
- modulation ;
- sauvegarde et réouverture projet ;
- export audio ;
- cible Android via Capacitor.

Le format `.dw` est une partie importante du projet. Il donne à DAWWW-CORE un conteneur projet portable et rend la direction local-first plus facile à comprendre, tester et transmettre.

---

## Direction produit

DAWWW-CORE n’est pas présenté comme une plateforme cloud-first, un host VST natif ou une marketplace.

Sa direction publique est plus claire et plus ciblée :

- production musicale dans le navigateur ;
- gestion projet local-first ;
- continuité projet portable `.dw` ;
- instruments et effets Web Audio ;
- export et récupération ;
- usage web desktop ;
- direction Android via Capacitor.

Cela rend le projet plus facile à évaluer : la question principale est de savoir si la session musicale survit au workflow complet, pas combien de fonctionnalités sans lien peuvent être listées.

---

## Relation avec Unicorn Sound Engine

DAWWW-CORE et Unicorn Sound Engine appartiennent au même portfolio music-tech, mais ce sont deux lignes produit séparées.

| Produit | Rôle |
| --- | --- |
| **DAWWW-CORE** | DAW navigateur / workspace musical local-first. |
| **Unicorn Sound Engine** | Écosystème séparé d’instruments et effets VST. |

DAWWW-CORE ne charge pas de VST natifs dans le navigateur.

Unicorn Sound Engine couvre le chemin plugin séparé : instruments VST, effets, manuels, audition, packaging et distribution.

---

## Périmètre public

Ce dépôt public sert de couche de présentation. Il n’est pas destiné à exposer les sources privées, les binaires non publiés, les credentials, les artefacts de preuve privés ou la matière de handover.

Les preuves détaillées peuvent être revues séparément dans un buyer proof pack contrôlé lorsqu’une discussion technique plus profonde est nécessaire.

---

## Zones de revue utiles

Une revue utile peut se concentrer sur des comportements concrets :

- création et réouverture des projets `.dw` ;
- sauvegarde, récupération et export ;
- lecture et rendu Web Audio ;
- limites de readiness Android ;
- écoute des instruments et effets ;
- clarté de la documentation ;
- lacunes de release-readiness.

---

## Résumé

DAWWW-CORE se comprend d’abord comme un projet MAO navigateur avec une direction local-first forte.

Sa valeur ne vient pas seulement de la présence de fonctions DAW. Sa valeur vient de l’organisation de ces fonctions autour de la continuité projet, de la portabilité, de l’export et de la récupération.

<p align="right"><a href="#dawww-core-project-overview">↑ Retour en haut</a> · <a href="#english">English</a></p>
