# Synth Suite / Suite synthés

[FR](#francais) | [EN](#english)

## Francais

La suite UWdeVST regroupe 7 synthés: Piano, Guitar, Bass, Perc, Drum, Orch et Rare / Instr.

| Synthé | Etat public-safe | Preuve synthesee | Limite |
| --- | --- | --- | --- |
| Piano | OK technique | Tests production Release, QA presets, QA CPU, suites pitch/release. | Ecoute finale a faire. |
| Guitar | OK technique | Tests production Release, 90/90 QA presets, chord candidates PASS. | Ecoute finale a faire. |
| Bass | OK technique | Tests production Release, 90/90 QA presets, pitch 63/63. | Ecoute finale a faire. |
| Perc | OK technique | Tests production Release, 54/54 QA presets, release 13/13. | Ecoute finale a faire. |
| Drum | OK technique | Tests production Release, 2070/2070 QA presets, matrix 90/90. | Ecoute humaine RC restante. |
| Orch | OK technique | Tests production Release, 200/200 QA presets. | Mini-score/ecoute manuelle attendus. |
| Rare / Instr | OK technique | Tests production Release, 42/42 QA presets, strict chord candidates PASS. | Ecoute humaine RC restante. |

### Architecture commune

Les synthés partagent une logique utilisateur: selection d'instrument, macros, LFO selon instrument, onglets FX, presets usine, sorties audio et documentation utilisateur.

### Garde-fou

Cette page ne publie pas les CSV QA, presets, binaires, installateurs, fichiers audio, code JUCE/C++ ou captures internes. Elle donne une synthese decisionnelle.

## English

The UWdeVST suite groups seven synths with automated technical QA signals. Release-candidate completion still depends on human listening review for selected families, so this showcase must not claim a fully signed RC.
