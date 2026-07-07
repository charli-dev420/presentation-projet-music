# DAWWW-CORE local and cross device MAO studio

<p align="center">
  <img src="assets/project-banners/daw-core.jpg" width="900" alt="DAWWW-CORE Music Lab banner">
</p>

<p align="center">
  <strong>MAO · Web Audio · DAW navigateur · Projets .dw · Android · Plugins audio</strong>
</p>

<p align="center">
  <a href="#ce-que-je-presente-ici">Présentation</a> ·
  <a href="#dawww-core">DAWWW-CORE</a> ·
  <a href="#unicorn-sound-engine">Unicorn Sound Engine</a> ·
  <a href="#pack-public--pack-acheteur">Packs</a> ·
  <a href="#english">English</a>
</p>

---

## Ce que je présente ici

Ce dépôt me permet de présenter mes projets orientés **musique**, **MAO**, **Web Audio** et **outils créatifs**.

Je l’utilise comme point d’entrée public pour expliquer mon travail sans exposer directement les sources privées, les binaires, les accès, les preuves sensibles ou les documents réservés à une discussion acheteur.

Mon objectif est simple : permettre à quelqu’un de comprendre rapidement ce que je construis, pourquoi les projets sont séparés, ce qui est déjà concret, ce qui reste à valider et quels retours peuvent réellement m’aider.

---

## Les deux lignes principales

Je travaille principalement autour de deux lignes liées, mais séparées.

| Ligne | Rôle |
| --- | --- |
| **DAWWW-CORE** | Mon projet principal : un DAW web local-first basé sur Web Audio, le format `.dw`, l’export audio, la continuité projet et une cible Android. |
| **Unicorn Sound Engine** | Une ligne séparée autour d’instruments VST, d’effets, de manuels, d’audition, de packaging et de distribution. |

Cette séparation est importante.

**DAWWW-CORE est un DAW navigateur. Il ne charge pas de VST natifs dans le navigateur.**  
**Unicorn Sound Engine est la ligne plugin séparée.**

Les deux projets appartiennent au même univers MAO, mais ils ne doivent pas être confondus.

---

## DAWWW-CORE

**DAWWW-CORE** est le projet que je mets le plus en avant.

Je le construis comme un studio musical web local-first, avec une idée centrale :

> un projet musical doit pouvoir être créé, sauvegardé, rouvert, relu, modifié, exporté et continué.

Ce qui m’intéresse ici n’est pas seulement de produire du son. Le vrai sujet, c’est la continuité du travail musical.

DAWWW-CORE regroupe notamment :

- une direction DAW navigateur ;
- un moteur basé sur Web Audio ;
- un format projet portable `.dw` ;
- des surfaces de travail type arrangeur, séquenceur, piano roll et mixer ;
- des instruments et effets intégrés au DAW ;
- des workflows d’export ;
- une logique de sauvegarde, réouverture et récupération ;
- une cible Android via Capacitor ;
- des éléments de QA et de validation orientés preuve.

Je veux présenter DAWWW-CORE comme un projet MAO sérieux, mais sans surpromettre. Les preuves détaillées, les limites et les éléments de reprise appartiennent au pack acheteur.

---

## Unicorn Sound Engine

**Unicorn Sound Engine** est une ligne séparée autour des instruments et effets audio.

Elle me permet de présenter le travail lié aux plugins, aux presets, aux manuels, aux écoutes, aux pages produit et à la distribution.

Cette ligne peut inclure :

- instruments VST ;
- effets VST ;
- manuels ;
- presets ;
- notes d’écoute ;
- audition ;
- packaging ;
- store ;
- téléchargements ;
- notes de release.

Elle complète mon univers music-tech, mais elle ne remplace pas DAWWW-CORE.

---

## FX Line

La ligne FX regroupe les effets audio par familles de traitement :

- analyzer ;
- creative ;
- delay ;
- distortion ;
- doubler ;
- dynamics ;
- EQ / filter ;
- modulation ;
- pitch / time ;
- reverb ;
- stereo.

Mon objectif n’est pas seulement d’avoir une liste d’effets. Je veux que chaque effet puisse être compris comme un vrai petit produit audio :

```text
rôle musical → comportement DSP → interface → presets/docs → packaging → distribution
```

---

## Audition & Review

J’ai aussi besoin d’outils de revue, parce qu’un projet audio ne se valide pas uniquement avec du code.

Pour les synthés, les FX, les presets ou les assets visuels, il faut pouvoir noter, écouter, comparer, accepter, refuser ou demander une correction.

Cette partie sert à structurer :

- les écoutes ;
- les presets ;
- les verdicts ;
- les notes de qualité ;
- les assets visuels ;
- les exports de feedback ;
- les décisions de release.

C’est une couche importante pour passer d’un projet “qui existe” à un projet plus lisible, plus testable et plus crédible.

---

## Pack public / Pack acheteur

J’ai séparé les documents en deux niveaux.

### Pack public

Le pack public sert à présenter les projets proprement.

Il peut contenir :

- un deck court ;
- un one-pager ;
- quelques visuels ;
- une explication produit ;
- un appendice technique léger ;
- des liens vers les pages publiques.

Son rôle est de donner une première compréhension sans exposer ce qui doit rester privé.

### Pack acheteur

Le pack acheteur sert à une discussion plus sérieuse ou à une due diligence.

Il peut contenir :

- la politique de claims ;
- le scope réel ;
- les preuves `.dw` ;
- les preuves Android ;
- les éléments runtime audio ;
- la QA ;
- les dépendances et licences ;
- les limites connues ;
- les notes de sécurité ;
- les sujets billing / store / handover ;
- les éléments de reprise ou de transfert.

Ce pack n’est pas destiné à être publié tel quel dans ce dépôt.

---

## Documentation

Le dépôt public doit rester court et lisible.

Chemin de lecture recommandé :

| Page | Rôle |
| --- | --- |
| [`docs/dawww-core.md`](docs/dawww-core.md) | Présenter le projet principal |
| [`docs/unicorn-sound-engine.md`](docs/unicorn-sound-engine.md) | Présenter la ligne plugin séparée |
| [`docs/fx-line.md`](docs/fx-line.md) | Présenter la famille FX |
| [`docs/audition-review.md`](docs/audition-review.md) | Présenter la logique d’écoute et de revue |
| [`docs/current-status.md`](docs/current-status.md) | Résumer l’état actuel public |
| [`docs/open-needs.md`](docs/open-needs.md) | Lister les retours et collaborations utiles |

Les pages de synthèse publique des preuves et de positionnement commercial peuvent être ajoutées ensuite, à partir du pack public, sans reprendre les détails sensibles du pack acheteur.

---

## Ce que je veux montrer

Avec ce dépôt, je veux montrer :

- que DAWWW-CORE est le projet MAO principal ;
- que Unicorn Sound Engine est une ligne plugin séparée ;
- que les projets sont reliés mais techniquement distincts ;
- que la continuité projet `.dw` est un sujet central ;
- que la QA, l’export, l’audition et la documentation font partie du travail ;
- que les sources privées peuvent rester privées sans rendre le projet opaque.

---

## Besoins utiles

Les retours les plus utiles sont concrets :

- tester DAWWW-CORE comme DAW web ;
- vérifier les parcours sauvegarde / réouverture / export ;
- tester la continuité `.dw` ;
- donner un retour sur l’expérience Android ;
- écouter les synthés et FX ;
- relire les manuels ;
- tester les flows de téléchargement ;
- aider à prioriser les effets ;
- améliorer le positionnement produit ;
- discuter partenariat, mission, financement ou reprise.

---

## English

This repository helps me present my music and music-production oriented projects in a clean public way.

My main project is **DAWWW-CORE**, a local-first browser DAW built around Web Audio, portable `.dw` sessions, export workflows, project continuity, QA and an Android target.

Alongside it, I also work on **Unicorn Sound Engine**, a separate plugin ecosystem around VST instruments, effects, manuals, audition material, packaging and distribution.

The distinction matters:

**DAWWW-CORE is a browser DAW. It does not load native VST plugins in the browser.**  
**Unicorn Sound Engine is the separate plugin line.**

This repository is not meant to expose private source code, binaries, credentials, sensitive proof material or buyer-only documents. It is meant to make the projects understandable from the outside.

The public pack gives a first readable overview. The buyer proof pack is reserved for controlled due diligence and contains the deeper proof, limits, scope, QA, handover and transfer material.
