# QA Validation / Validation QA

[FR](#francais) | [EN](#english)

![Music QA matrix](../assets/qa-matrix.svg)

## Francais

### Matrice publique

| Surface | Validation attendue | Statut public-safe | Impact |
| --- | --- | --- | --- |
| Desktop studio | Gate complet desktop | `passed` / development proof fort. | Base principale pour discuter produit. |
| Android speaker | Gate Android studio-grade courant | `to-recertify`; anciens runs utiles en contexte seulement. | Bloque un claim release Android fort. |
| Android Bluetooth A2DP | Gate specifique si scope vise | `to-prove` si l'offre cible A2DP. | Ne pas promettre sans preuve. |
| `.dw` | `test:dw:proof` + roundtrip runtime | `contracted`; release proof a rejouer. | Clef de confiance du produit. |
| Release desktop | Summary release scoped | `missing-public-go`; dry-run non suffisant. | Necessaire pour claim release. |
| Release Android | Summary release Android | `missing-public-go`; failed/development-proof ne suffit pas. | Necessaire pour distribution Android. |
| UWdeVST 7 synthés | QA technique automatisée + ecoute RC | `technical-ok`, human listening pending. | Ne pas presenter comme RC signee. |

### Vocabulaire de statut

| Statut | Sens |
| --- | --- |
| `passed` | Preuve positive datée et redigeable. |
| `failed` | Run negatif ou preuve insuffisante; ne peut pas soutenir un claim. |
| `dry-run` | Plan ou validation sans execution finale; utile pour cadrer, pas pour signer. |
| `development-proof` | Signal utile en developpement, insuffisant pour release. |
| `operator-retained` | Preuve operateur gardee sous conditions de non-changement. |

### Regle de publication

Une preuve QA publique doit etre redigee, datable et reliee a une surface. Les logs bruts, chemins locaux, device IDs, captures internes et JSON de sortie restent hors vitrine.

## English

Public QA should be written, dateable, and tied to a product surface. Raw logs, local paths, device identifiers, internal screenshots, and output JSON stay out of this repository.
