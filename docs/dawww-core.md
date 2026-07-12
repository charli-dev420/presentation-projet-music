# DAWWW-CORE

<p align="center">
  <a href="#english">🇬🇧 English</a> · <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

DAWWW-CORE is a music-production studio that runs in the browser.

It is designed for creating a track from the first idea to the final export without requiring a traditional desktop installation.

## Main tools

| Tool | What it is used for |
| --- | --- |
| **Arranger** | Build the structure of a song on a timeline |
| **Sequencer** | Create patterns and rhythmic parts |
| **Piano roll** | Write and edit notes |
| **Mixer** | Balance tracks and shape the final sound |
| **Instruments** | Play and program sounds directly in the studio |
| **Sampler** | Use and transform sample-based material |
| **Effects** | Add color, space, movement and control |
| **Automation** | Change settings over time |
| **Export** | Render the full mix or individual stems |

## Portable projects

DAWWW-CORE uses the `.dw` format to keep a project together.

A `.dw` project is made to preserve the musical session so it can be saved, reopened and continued later. This includes the project structure, musical data, settings and referenced material needed by the session.

```text
create → save → reopen → edit → export → continue
```

## Local-first by design

The project is built around work stored on the user’s device rather than making an online connection the center of every session.

This approach keeps the music project close to the person creating it and makes offline or low-connectivity use possible where the browser and device support it.

## Desktop and Android

The desktop browser version is the main DAWWW-CORE experience.

An Android version is also maintained through Capacitor. It adapts the same studio direction to compatible phones and tablets.

## Built-in sound tools

The instruments and effects inside DAWWW-CORE are made for the browser through Web Audio.

DAWWW-CORE does not load native VST plugins. Native instruments and effects belong to the separate [UnicorSoundEngine](unicorsoundengine.md) collection.

---

<h2 id="francais">🇫🇷 Français</h2>

DAWWW-CORE est un studio de production musicale qui fonctionne dans le navigateur.

Il est conçu pour créer un morceau depuis la première idée jusqu’à l’export final, sans nécessiter l’installation d’un logiciel desktop traditionnel.

## Outils principaux

| Outil | Utilisation |
| --- | --- |
| **Arrangeur** | Construire la structure d’un morceau sur une timeline |
| **Séquenceur** | Créer des patterns et des parties rythmiques |
| **Piano roll** | Écrire et modifier les notes |
| **Mixer** | Équilibrer les pistes et travailler le son final |
| **Instruments** | Jouer et programmer des sons directement dans le studio |
| **Sampler** | Utiliser et transformer des contenus basés sur des samples |
| **Effets** | Ajouter de la couleur, de l’espace, du mouvement et du contrôle |
| **Automation** | Faire évoluer les réglages dans le temps |
| **Export** | Produire le mix complet ou des stems séparés |

## Projets portables

DAWWW-CORE utilise le format `.dw` pour garder un projet réuni.

Un projet `.dw` est conçu pour préserver la session musicale afin de la sauvegarder, de la rouvrir et de la poursuivre plus tard. Il peut contenir la structure du projet, les données musicales, les réglages et la matière référencée nécessaire à la session.

```text
créer → sauvegarder → rouvrir → modifier → exporter → continuer
```

## Une approche local-first

Le projet est construit autour d’un travail conservé sur l’appareil de l’utilisateur, plutôt que de placer une connexion en ligne au centre de chaque session.

Cette approche garde le projet musical proche de la personne qui le crée et permet un usage hors ligne ou avec une connexion limitée lorsque le navigateur et l’appareil le permettent.

## Desktop et Android

La version navigateur desktop constitue l’expérience principale de DAWWW-CORE.

Une version Android est également maintenue via Capacitor. Elle adapte la même direction de studio aux téléphones et tablettes compatibles.

## Outils sonores intégrés

Les instruments et effets présents dans DAWWW-CORE sont conçus pour le navigateur avec Web Audio.

DAWWW-CORE ne charge pas de plugins VST natifs. Les instruments et effets natifs appartiennent à la collection séparée [UnicorSoundEngine](unicorsoundengine.md).
