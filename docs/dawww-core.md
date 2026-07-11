# DAWWW-CORE

<p align="center">
  <a href="#english">🇬🇧 English</a> · <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

DAWWW-CORE is the main browser DAW presented in this repository.

It is built around Web Audio, portable `.dw` projects, audio export, recovery workflows and an Android target through Capacitor.

## Core workflow

```text
create → save → reopen → edit → export → continue
```

This loop defines the product more clearly than a long feature list. The important question is whether the musical project remains usable after the session is closed and reopened.

## Main surfaces

| Surface | Role |
| --- | --- |
| **Arranger** | Organize sections, clips and timeline structure. |
| **Sequencer** | Build rhythmic and musical patterns. |
| **Piano roll** | Edit notes and phrases. |
| **Mixer** | Balance tracks and audio layers. |
| **Instruments / sampler** | Create and manipulate sound in the browser. |
| **Effects** | Process audio through built-in Web Audio tools. |
| **Automation / modulation** | Control parameter changes over time. |
| **Project handling** | Save, reopen and recover work through `.dw`. |
| **Export** | Render audio output. |

## `.dw` project format

The `.dw` format is the portable project container used by DAWWW-CORE. It supports the local-first direction by keeping the musical session outside a temporary browser state.

The public demonstration should show at least one complete round trip:

```text
create project → save .dw → close → reopen → verify state → export
```

## Platform scope

- **Desktop web** is the main public DAW experience.
- **Android through Capacitor** is an active test target.

Android should be described through dated device validation rather than a universal compatibility claim.

## Product boundary

DAWWW-CORE is not a native VST host. Its instruments and effects belong to the browser / Web Audio path. Native plugin products are presented under UnicorSoundEngine.

## Most useful evidence

- one complete workspace screenshot;
- one `.dw` save / reopen example;
- one export result;
- one dated Android test snapshot;
- one short audio example created or exported through the DAW.

---

<h2 id="francais">🇫🇷 Français</h2>

DAWWW-CORE est le DAW navigateur principal présenté dans ce dépôt.

Il repose sur Web Audio, les projets portables `.dw`, l’export audio, les mécanismes de récupération et une cible Android via Capacitor.

## Workflow central

```text
créer → sauvegarder → rouvrir → modifier → exporter → continuer
```

Cette boucle définit mieux le produit qu’une longue liste de fonctions. La question importante est de savoir si le projet musical reste utilisable après fermeture et réouverture de la session.

## Surfaces principales

| Surface | Rôle |
| --- | --- |
| **Arrangeur** | Organiser les sections, clips et la structure temporelle. |
| **Séquenceur** | Construire des patterns rythmiques et musicaux. |
| **Piano roll** | Modifier les notes et phrases. |
| **Mixer** | Équilibrer les pistes et couches audio. |
| **Instruments / sampler** | Créer et manipuler le son dans le navigateur. |
| **Effets** | Traiter l’audio avec les outils Web Audio intégrés. |
| **Automation / modulation** | Contrôler les paramètres dans le temps. |
| **Gestion projet** | Sauvegarder, rouvrir et récupérer le travail via `.dw`. |
| **Export** | Produire une sortie audio. |

## Format projet `.dw`

Le format `.dw` est le conteneur projet portable de DAWWW-CORE. Il soutient l’approche local-first en conservant la session musicale hors d’un simple état temporaire du navigateur.

La démonstration publique doit montrer au moins un aller-retour complet :

```text
créer un projet → sauvegarder .dw → fermer → rouvrir → vérifier l’état → exporter
```

## Périmètre plateforme

- **Web desktop** constitue l’expérience DAW publique principale.
- **Android via Capacitor** est une cible de test active.

Android doit être présenté à travers des validations datées sur appareils, pas comme une compatibilité universelle.

## Limite produit

DAWWW-CORE n’est pas un hôte VST natif. Ses instruments et effets appartiennent au chemin navigateur / Web Audio. Les produits plugins natifs sont présentés dans UnicorSoundEngine.

## Preuves les plus utiles

- une capture complète du workspace ;
- un exemple sauvegarde / réouverture `.dw` ;
- un résultat d’export ;
- une validation Android datée ;
- un court exemple audio créé ou exporté avec le DAW.
