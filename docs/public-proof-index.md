# Public Proof Index / Index des preuves publiques

[EN](#english) | [FR](#francais)

## English

This index lists public-safe proof summaries. Each row names a surface, source date, status, public proof signal, and next validation note.

| ID | Surface | Source date | Status | Public proof signal | Next validation note |
| --- | --- | --- | --- | --- | --- |
| MUS-P01 | DAW Core desktop | 2026-06-23 | `passed` | Visible complete-gate signal: 25/25, `findings=0`, virtual keyboard passed. | Attach a current release-scope summary before signing a release claim. |
| MUS-P02 | DAW Core Android | 2026-06-23+ | `to-recertify` | Active Android QA expects `cert:android:studio-grade` style proof and a summary. | Current device/workflow proof should be replayed for the target beta or release decision. |
| MUS-P03 | `.dw` continuity | 2026-06-19/23 | `contracted` | Checksums, embedded sampler assets, instrument/effect snapshots, desktop/Android reload, re-export after import. | Roundtrip proof should be scoped to the current target surface. |
| MUS-P04 | VST-site assets | 2026-06-29 | `referenced` | 94 public assets, 94 referenced at runtime, 0 public asset unreferenced in the inventory; 23 `screen-synth` assets. | Private storage, payment, admin, and binary distribution stay under separate review. |
| MUS-P05 | VST manuals | 2026-06-29 | `clean-public` | Seven clean PDFs linked by `manualUrl`: Bass, Drum, Guitar, Orch, Perc, Piano, RareInstr. | Manuals are referenced rather than copied here to keep this repo light. |
| MUS-P06 | UWdeVST seven synths | 2026-06-19 | `technical-ok` | Seven synths have automated technical QA, preset/CPU checks, and advanced suites documented. | Listening sign-off should be completed for release-selected families. |
| MUS-P07 | Play billing/publish | 2026-05-21 retained | `operator-retained` | Operator proof retained under no-change conditions. | Replay if catalog, entitlement, billing bridge, version, or publication surface changes. |

### Boundary

Raw logs, binaries, private screenshots, builds, installers, audio files, QA JSON, CSV files, local paths, and secrets are excluded.

## Francais

Cet index liste des synthèses de preuves public-safe. Chaque ligne nomme une surface, une date source, un statut, un signal public et une note de validation suivante.

| ID | Surface | Date source | Statut | Signal public | Note validation suivante |
| --- | --- | --- | --- | --- | --- |
| MUS-P01 | DAW Core desktop | 2026-06-23 | `passed` | Signal complete-gate visible: 25/25, `findings=0`, virtual keyboard passed. | Joindre un summary release-scope courant avant de signer un claim release. |
| MUS-P02 | DAW Core Android | 2026-06-23+ | `to-recertify` | La QA Android active attend une preuve type `cert:android:studio-grade` et un summary. | Rejouer une preuve device/workflow courante pour la décision beta ou release cible. |
| MUS-P03 | Continuité `.dw` | 2026-06-19/23 | `contracted` | Checksums, assets sampler embarqués, snapshots instruments/effets, reload desktop/Android, re-export après import. | La preuve roundtrip doit être cadrée sur la surface cible courante. |
| MUS-P04 | Assets VST-site | 2026-06-29 | `referenced` | 94 assets publics, 94 référencés runtime, 0 asset public non référencé dans l'inventaire; 23 assets `screen-synth`. | Storage privé, paiement, admin et distribution binaire restent en review séparée. |
| MUS-P05 | Manuels VST | 2026-06-29 | `clean-public` | Sept PDFs propres liés par `manualUrl`: Bass, Drum, Guitar, Orch, Perc, Piano, RareInstr. | Les manuels sont référencés plutôt que copiés ici pour garder ce repo léger. |
| MUS-P06 | Sept synthés UWdeVST | 2026-06-19 | `technical-ok` | Sept synthés ont QA technique automatisée, checks presets/CPU et suites avancées documentées. | Le sign-off écoute doit être complété pour les familles choisies release. |
| MUS-P07 | Play billing/publish | 2026-05-21 retenu | `operator-retained` | Preuve opérateur retenue sous conditions de non-changement. | Rejouer si catalogue, entitlement, billing bridge, version ou publication changent. |

### Limite

Logs bruts, binaires, captures privées, builds, installateurs, fichiers audio, JSON QA, CSV, chemins locaux et secrets sont exclus.
