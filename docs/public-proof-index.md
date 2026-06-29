# Public Proof Index / Index des preuves publiques

[FR](#francais) | [EN](#english)

## Francais

| ID | Surface | Date source | Statut | Preuve publique | Ce que cela ne prouve pas |
| --- | --- | --- | --- | --- | --- |
| MUS-P01 | DAW Core desktop | 2026-06-23 | `passed` | Complete-gate visible: 25/25, `findings=0`, virtual keyboard passed. | Ne signe pas a lui seul une release scoped. |
| MUS-P02 | DAW Core Android | 2026-06-23+ | `to-recertify` | La QA Android active exige `cert:android:studio-grade` et un `summary.json`. | Anciennes preuves ne valent pas GO release. |
| MUS-P03 | `.dw` v3 | 2026-06-19/23 | `contracted` | Checksum, assets sampler embarques, snapshots instruments/effets, reload desktop/Android, re-export apres import. | Ne remplace pas le roundtrip release cross-device courant. |
| MUS-P04 | VST-site assets | 2026-06-29 | `referenced` | 94 assets publics, 94 referencés runtime, 0 public asset non reference; 23 assets `screen-synth`. | Ne prouve pas paiement, storage, admin ou distribution binaire. |
| MUS-P05 | VST manuals | 2026-06-29 | `clean-public` | 7 PDF propres lies par `manualUrl`: Bass, Drum, Guitar, Orch, Perc, Piano, RareInstr. | Les PDF ne sont pas recopies ici; ils restent dans le site produit. |
| MUS-P06 | UWdeVST 7 synthés | 2026-06-19 | `technical-ok` | 7 synthés OK technique automatise, QA presets/CPU et suites avancees documentees. | La RC reste bloquee par ecoute humaine pour Drum/Bass/Orch/Rare tant que `PENDING_HUMAN_REVIEW`. |
| MUS-P07 | Play billing/publish | 2026-05-21 retenu | `operator-retained` | Preuve operateur retenue sous conditions. | A rejouer si catalogue, RevenueCat, entitlement, billing bridge, version ou publication changent. |

## English

This index lists public-safe proof summaries only. Every claim has a surface, date, status, public proof, and explicit limitation. Raw logs, binaries, private screenshots, builds, installers, audio files, QA JSON, CSV files, local paths, and secrets are excluded.
