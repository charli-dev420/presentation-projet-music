# Synth Suite / Suite synthés

[EN](#english) | [FR](#francais)

## English

### Suite Positioning

The UWdeVST synths are presented as one **Unicor SoundEngine** instrument suite, separate from DAW Core. The point is not to pitch seven unrelated plugins or to imply that they are DAW Core features. The point is to show a coherent set of musical instruments with shared UX, documentation, QA discipline, and distribution potential.

### Instrument Map

| Instrument | Musical role | Public QA signal | Product next step |
| --- | --- | --- | --- |
| Piano | Core harmonic and melodic writing. | Production Release tests, preset QA, CPU QA, pitch/release suites. | Listening pass and first-session manual review. |
| Guitar | Chords, plucked color, arrangement sketching. | Production Release tests, 90/90 preset QA, chord candidates PASS. | Listening pass focused on playability and articulation expectations. |
| Bass | Low-end writing, groove, foundation for DAW Core projects. | Production Release tests, 90/90 preset QA, pitch 63/63. | Listening pass focused on mix usefulness and preset naming. |
| Perc | Percussive layers and rhythmic accents. | Production Release tests, 54/54 preset QA, release 13/13. | Listening pass focused on transient consistency and user labels. |
| Drum | Drum kit/rhythm base for project sketches. | Production Release tests, 2070/2070 preset QA, matrix 90/90. | Human RC listening pass and kit-level review. |
| Orch | Orchestral color and layered arrangement support. | Production Release tests, 200/200 preset QA. | Mini-score review and musical balance check. |
| Rare / Instr | Less common tones and character instruments. | Production Release tests, 42/42 preset QA, strict chord candidates PASS. | Human listening pass focused on identity and usefulness. |

### Shared User Model

The suite should feel familiar from one instrument to the next:

- instrument selection and visible musical role;
- macro controls that give quick sound shaping;
- instrument-specific modulation where useful;
- FX tabs for practical tone shaping;
- factory preset structure and documentation;
- output behavior that can be reviewed inside DAW Core or VST workflows.

### Why This Matters For DAW Core

DAW Core needs musical material that makes workflows worth testing. The synth suite gives the workstation real content: instruments for project continuity, sound design, UX review, preset handling, VST distribution, and listening-based QA.

### Public Boundary

This page publishes a decision-level summary. It does not publish JUCE/C++ source, plugin binaries, installers, private presets, QA CSV files, internal audio outputs, local paths, or private captures.

### Best Next Review

For a partner or buyer, the best next review is a focused listening and UX pass on the instruments most relevant to the target demo. That review should produce clear outcomes: ready for demo, needs sound design, needs UX copy, needs QA replay, or needs packaging work.

## Francais

### Positionnement de suite

Les synthés UWdeVST sont présentés comme une suite instrumentale **Unicor SoundEngine**, séparée de DAW Core. Le but n'est pas de pitcher sept plugins sans lien ni de laisser croire qu'ils sont des fonctions DAW Core. Le but est de montrer un ensemble cohérent d'instruments avec UX partagée, documentation, discipline QA et potentiel distribution.

### Carte instruments

| Instrument | Rôle musical | Signal QA public | Prochaine étape produit |
| --- | --- | --- | --- |
| Piano | Ecriture harmonique et mélodique centrale. | Tests production Release, QA presets, QA CPU, suites pitch/release. | Ecoute et review manuel première session. |
| Guitar | Accords, couleur pincée, sketch arrangement. | Tests production Release, 90/90 QA presets, chord candidates PASS. | Ecoute centrée jouabilité et articulation attendue. |
| Bass | Grave, groove, fondation pour projets DAW Core. | Tests production Release, 90/90 QA presets, pitch 63/63. | Ecoute centrée utilité mix et nommage presets. |
| Perc | Couches percussives et accents rythmiques. | Tests production Release, 54/54 QA presets, release 13/13. | Ecoute centrée cohérence transitoires et labels utilisateur. |
| Drum | Base kit/rhythm pour sketches projet. | Tests production Release, 2070/2070 QA presets, matrix 90/90. | Ecoute humaine RC et review niveau kit. |
| Orch | Couleur orchestrale et support arrangement en couches. | Tests production Release, 200/200 QA presets. | Mini-score review et équilibre musical. |
| Rare / Instr | Timbres moins communs et instruments de caractère. | Tests production Release, 42/42 QA presets, strict chord candidates PASS. | Ecoute humaine centrée identité et utilité. |

### Modèle utilisateur partagé

La suite doit rester familière d'un instrument à l'autre:

- sélection d'instrument et rôle musical visible;
- macros pour modeler rapidement le son;
- modulation spécifique à l'instrument quand utile;
- onglets FX pour le tone shaping pratique;
- structure presets usine et documentation;
- comportement de sortie reviewable dans DAW Core ou workflows VST.

### Pourquoi c'est important pour DAW Core

DAW Core a besoin de matière musicale pour rendre les workflows utiles à tester. La suite synthés donne du contenu réel à la workstation: instruments pour continuité projet, sound design, review UX, gestion presets, distribution VST et QA par écoute.

### Limite publique

Cette page publie une synthèse décisionnelle. Elle ne publie pas code JUCE/C++, binaires plugin, installateurs, presets privés, CSV QA, sorties audio internes, chemins locaux ou captures privées.

### Meilleure prochaine review

Pour un partenaire ou acheteur, la meilleure review suivante est une passe écoute et UX ciblée sur les instruments les plus pertinents pour la démo visée. La sortie doit être claire: prêt pour démo, besoin sound design, besoin copie UX, besoin replay QA ou besoin packaging.
