# DAW Core / DAW Core

[EN](#english) | [FR](#francais)

![DAW Core banner](../assets/project-banners/daw-core.jpg)

## English

### Product Definition

**DAW Core** is the main music project: a browser-based **web local-first DAW**. The browser is not treated as a temporary preview surface. It is the working surface where the musician creates, saves, reloads, listens, edits, and checks whether the project remains coherent.

The product idea is intentionally concrete. A session should not disappear into a vague "state" that nobody can explain. It should become a project with enough structure to be reopened, inspected, tested, and improved.

### What The Product Must Prove

The important DAW Core scenario is small but demanding:

1. Create or open a project in the browser.
2. Add musical state: tracks, arrangement, instruments, audio decisions, and project metadata.
3. Save the project through the `.dw` direction.
4. Reopen it on the target surface.
5. Check that playback, structure, assets, snapshots, and editable state still make sense.
6. Record the result in terms another tester or collaborator can use.

That is why the repo talks so much about project continuity. The value is not a screenshot. The value is that the musical work survives a round trip.

### Android Beta Track

The Android work is attached to DAW Core because it tests the same promise on real devices and mobile-browser constraints. A useful Android beta report names the device class, browser, audio route, project scenario, observed result, and whether the session stayed recoverable.

The current public need is simple: testers who can run controlled DAW Core browser scenarios on real Android devices and report what holds, what breaks, and what needs clearer guidance.

### What A Reader Can Evaluate Here

This showcase gives enough material to understand the DAW Core direction without exposing implementation internals:

- the browser-first local project model;
- the `.dw` continuity vocabulary;
- user flows for save, reload, playback, and review;
- Android beta framing;
- QA and evidence summaries;
- release-readiness language;
- visual identity and public project assets.

For the full reading path, use [user flows](user-flows.md), [QA validation](qa-validation.md), [evidence](evidence.md), [current status](current-status.md), and [release readiness](release-readiness.md).

## Francais

### Definition Produit

**DAW Core** est le projet musical principal: un **web local-first DAW** dans le navigateur. Le navigateur n'est pas traite comme une surface de preview temporaire. C'est la surface de travail ou le musicien cree, sauvegarde, rouvre, ecoute, edite et verifie que le projet reste coherent.

L'idee produit est volontairement concrete. Une session ne doit pas disparaitre dans un "etat" vague que personne ne peut expliquer. Elle doit devenir un projet assez structure pour etre rouvert, inspecte, teste et ameliore.

### Ce Que Le Produit Doit Prouver

Le scenario DAW Core important est petit mais exigeant:

1. Creer ou ouvrir un projet dans le navigateur.
2. Ajouter un etat musical: pistes, arrangement, instruments, decisions audio et metadonnees projet.
3. Sauvegarder le projet dans la direction `.dw`.
4. Le rouvrir sur la surface cible.
5. Verifier que lecture, structure, assets, snapshots et etat editable restent coherents.
6. Documenter le resultat dans des termes utilisables par un autre testeur ou collaborateur.

C'est pour cela que le repo parle autant de continuite projet. La valeur n'est pas une capture d'ecran. La valeur est que le travail musical survive a l'aller-retour.

### Piste Beta Android

Le travail Android est rattache a DAW Core parce qu'il teste la meme promesse sur vrais appareils et sous contraintes navigateur mobile. Un retour beta Android utile nomme la classe d'appareil, le navigateur, la route audio, le scenario projet, le resultat observe et si la session reste recuperable.

Le besoin public actuel est simple: des testeurs capables de lancer des scenarios DAW Core controles sur de vrais appareils Android et de dire ce qui tient, ce qui casse et ce qui manque de guidance.

### Ce Qu'Un Lecteur Peut Evaluer Ici

Cette vitrine donne assez de matiere pour comprendre DAW Core sans exposer les internes d'implementation:

- le modele projet local dans le navigateur;
- le vocabulaire de continuite `.dw`;
- les flux utilisateur sauvegarde, reouverture, lecture et review;
- le cadrage beta Android;
- les syntheses QA et preuves;
- le langage release-readiness;
- l'identite visuelle et les assets publics du projet.

Pour le chemin complet, lire [user flows](user-flows.md), [QA validation](qa-validation.md), [evidence](evidence.md), [current status](current-status.md) et [release readiness](release-readiness.md).
