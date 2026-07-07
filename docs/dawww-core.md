# DAWWW-CORE

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

DAWWW-CORE is the main DAW product line presented in this repository.

It is a local-first browser music workspace built around Web Audio, portable `.dw` projects, audio export, recovery workflows and an Android direction through Capacitor.

---

## Core workflow

The project is centered on a practical DAW workflow:

```text
create → save → reopen → recover → export → continue
```

This workflow is more important than a long feature list. It defines what DAWWW-CORE must preserve: the musical state, the project structure and the ability to continue working after closing and reopening a session.

---

## Main surfaces

DAWWW-CORE groups several music-production surfaces in one browser-based workspace:

| Surface | Role |
| --- | --- |
| **Arranger** | Organize musical sections and timeline structure. |
| **Sequencer** | Build patterns, rhythms and structured musical events. |
| **Piano roll** | Edit notes and musical phrases. |
| **Mixer** | Balance tracks and audio layers. |
| **Instruments** | Produce sound inside the browser DAW. |
| **Sampler** | Work with sample-based material. |
| **Effects** | Shape sound through built-in Web Audio processing. |
| **Automation / modulation** | Control parameter changes over time. |
| **Export** | Render or prepare audio output. |
| **Project handling** | Save, reopen and recover work through the local-first direction. |

---

## Project format

The `.dw` format is central to DAWWW-CORE.

It gives the project a portable container and makes the local-first story concrete. The format helps frame the project as something that can be saved, moved, reopened and reviewed outside a temporary browser state.

---

## Platform scope

DAWWW-CORE is presented publicly around two platform directions:

- **desktop web** for the main browser DAW experience;
- **Android through Capacitor** as a mobile target and validation path.

Production-level Android claims require fresh validation and should not be treated as universal device certification from the public README alone.

---

## What DAWWW-CORE is not

DAWWW-CORE is not a native VST host.

It does not load native VST plugins in the browser. Instruments and effects inside DAWWW-CORE belong to the browser/Web Audio path.

The separate VST and plugin work belongs to Unicorn Sound Engine.

---

## Useful review focus

A useful review of DAWWW-CORE should focus on concrete behavior:

- project creation;
- `.dw` save and reopen;
- recovery behavior;
- Web Audio playback and export;
- timeline and editing workflow;
- Android readiness boundaries;
- documentation clarity;
- release-readiness gaps.

<p align="right"><a href="#dawww-core">↑ Back to top</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

DAWWW-CORE est la ligne DAW principale présentée dans ce dépôt.

C’est un workspace musical navigateur local-first basé sur Web Audio, les projets portables `.dw`, l’export audio, la récupération de session et une direction Android via Capacitor.

---

## Workflow central

Le projet est centré sur un workflow DAW concret :

```text
créer → sauvegarder → rouvrir → récupérer → exporter → continuer
```

Ce workflow est plus important qu’une longue liste de fonctionnalités. Il définit ce que DAWWW-CORE doit préserver : l’état musical, la structure du projet et la possibilité de continuer à travailler après fermeture et réouverture d’une session.

---

## Surfaces principales

DAWWW-CORE regroupe plusieurs surfaces MAO dans un workspace navigateur :

| Surface | Rôle |
| --- | --- |
| **Arrangeur** | Organiser les sections musicales et la structure temporelle. |
| **Séquenceur** | Construire des patterns, rythmes et événements musicaux. |
| **Piano roll** | Éditer les notes et phrases musicales. |
| **Mixer** | Équilibrer les pistes et couches audio. |
| **Instruments** | Produire du son dans le DAW navigateur. |
| **Sampler** | Travailler avec des sources sample-based. |
| **Effets** | Façonner le son via des traitements Web Audio intégrés. |
| **Automation / modulation** | Contrôler les changements de paramètres dans le temps. |
| **Export** | Rendre ou préparer une sortie audio. |
| **Gestion projet** | Sauvegarder, rouvrir et récupérer le travail dans la logique local-first. |

---

## Format projet

Le format `.dw` est central dans DAWWW-CORE.

Il donne au projet un conteneur portable et rend l’approche local-first concrète. Le format permet de présenter le projet comme un travail qui peut être sauvegardé, déplacé, rouvert et revu hors d’un simple état temporaire du navigateur.

---

## Périmètre plateforme

DAWWW-CORE est présenté publiquement autour de deux directions plateforme :

- **web desktop** pour l’expérience principale de DAW navigateur ;
- **Android via Capacitor** comme cible mobile et piste de validation.

Les claims Android production demandent une validation fraîche et ne doivent pas être lus comme une certification universelle sur tous les appareils depuis le README public seul.

---

## Ce que DAWWW-CORE n’est pas

DAWWW-CORE n’est pas un host VST natif.

Il ne charge pas de VST natifs dans le navigateur. Les instruments et effets dans DAWWW-CORE appartiennent au chemin navigateur/Web Audio.

Le travail VST et plugin séparé appartient à Unicorn Sound Engine.

---

## Axes de revue utiles

Une revue utile de DAWWW-CORE doit se concentrer sur des comportements concrets :

- création projet ;
- sauvegarde et réouverture `.dw` ;
- récupération ;
- lecture et export Web Audio ;
- workflow timeline et édition ;
- limites de readiness Android ;
- clarté de documentation ;
- lacunes de release-readiness.

<p align="right"><a href="#dawww-core">↑ Retour en haut</a> · <a href="#english">English</a></p>
