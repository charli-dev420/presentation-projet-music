# DAWWW-CORE

<p align="center">
  <a href="#english">🇬🇧 English</a> · <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

DAWWW-CORE is a local-first music studio that runs in the browser.

It is built for creating ideas, arranging tracks, editing notes, mixing audio and keeping projects portable from one session to the next.

## Main workspace

DAWWW-CORE brings together:

| Tool | What it is for |
| --- | --- |
| **Arranger** | Organising sections, clips and the musical timeline |
| **Sequencer** | Building patterns and rhythmic ideas |
| **Piano roll** | Editing notes and phrases |
| **Mixer** | Balancing tracks and audio layers |
| **Instruments** | Creating sound directly in the browser |
| **Sampler** | Working with sample-based material |
| **Effects** | Shaping sound with built-in processing |
| **Automation and modulation** | Moving parameters over time |
| **Export** | Producing audio and stems |

## Portable `.dw` projects

The `.dw` format is the project container used by DAWWW-CORE.

It can hold the structure and musical information needed to continue a session later:

```text
create → save → reopen → edit → export → continue
```

This keeps the project separate from the temporary state of a single browser tab.

## Local-first direction

DAWWW-CORE is designed so that music projects can remain on the user’s device instead of depending entirely on a cloud service.

The focus is on practical continuity: opening the studio, working, saving the project and returning to it later.

## Platforms

The main version targets desktop browsers.

An Android version is also maintained through Capacitor, bringing the same project direction to mobile devices.

## Built-in audio path

The instruments and effects inside DAWWW-CORE use the browser and Web Audio.

Native VST plugins belong to the separate [UnicorSoundEngine](unicorsoundengine.md) line and are not loaded inside the browser studio.

---

<h2 id="francais">🇫🇷 Français</h2>

DAWWW-CORE est un studio musical local-first qui fonctionne dans le navigateur.

Il est conçu pour créer des idées, arranger des pistes, modifier des notes, mixer l’audio et garder les projets portables d’une session à l’autre.

## Workspace principal

DAWWW-CORE réunit :

| Outil | Utilité |
| --- | --- |
| **Arrangeur** | Organiser les sections, les clips et la timeline musicale |
| **Séquenceur** | Construire des patterns et des idées rythmiques |
| **Piano roll** | Modifier les notes et les phrases musicales |
| **Mixer** | Équilibrer les pistes et les couches audio |
| **Instruments** | Créer du son directement dans le navigateur |
| **Sampler** | Travailler avec des contenus basés sur des samples |
| **Effets** | Façonner le son avec des traitements intégrés |
| **Automation et modulation** | Faire évoluer les paramètres dans le temps |
| **Export** | Produire de l’audio et des stems |

## Projets portables `.dw`

Le format `.dw` est le conteneur projet utilisé par DAWWW-CORE.

Il peut conserver la structure et les informations musicales nécessaires pour reprendre une session plus tard :

```text
créer → sauvegarder → rouvrir → modifier → exporter → continuer
```

Le projet ne dépend donc pas uniquement de l’état temporaire d’un onglet de navigateur.

## Direction local-first

DAWWW-CORE est conçu pour que les projets musicaux puissent rester sur l’appareil de l’utilisateur au lieu de dépendre entièrement d’un service cloud.

L’objectif est simple : ouvrir le studio, travailler, sauvegarder le projet et le reprendre plus tard.

## Plateformes

La version principale cible les navigateurs desktop.

Une version Android est également maintenue via Capacitor afin d’étendre la même logique de projet aux appareils mobiles.

## Chemin audio intégré

Les instruments et effets présents dans DAWWW-CORE utilisent le navigateur et Web Audio.

Les plugins VST natifs appartiennent à la ligne séparée [UnicorSoundEngine](unicorsoundengine.md) et ne sont pas chargés dans le studio navigateur.
