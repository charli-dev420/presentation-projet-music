# VST Distribution / Distribution VST

[EN](#english) | [FR](#francais)

## English

### Role In The Ecosystem

The VST distribution surface is part of **Unicor SoundEngine**. It is separate from **DAW Core**. Its job is to make the synth and FX line presentable, navigable, documented, and distributable without implying that the VSTs are functionally tied to the browser DAW.

### Public-Safe Distribution Signals

| Surface | Public signal | Why it matters |
| --- | --- | --- |
| Public assets | 94 public assets inventoried, 94 referenced at runtime, 0 public asset left unused in the referenced inventory. | The catalog surface has been reviewed as a real presentation layer. |
| Synth showcase images | 23 public `screen-synth` assets; seven showcase images copied into this repo. | Reviewers can see product-facing visuals without private logs or internal folders. |
| Manuals | Seven clean manual links by runtime metadata: Bass, Drum, Guitar, Orch, Perc, Piano, RareInstr. | The synth suite has user-facing documentation paths. |
| Catalog positioning | Synths and FX are grouped under Unicor SoundEngine. | The plugin/sound line is readable without being confused with DAW Core. |
| Public repo boundary | Backend, storage, payment, admin, binaries, and release artifacts are not published here. | Public review stays safe while still being useful. |

### Showcase Gallery

The public presentation images live in [`assets/vst-showcase`](../assets/vst-showcase/README.md). They are meant for orientation and product review, not as raw QA proof.

### What A Distributor Or Buyer Should Review Next

1. Catalog clarity: can a user understand the instrument family and what to download?
2. Manual quality: does each synth have enough guidance for a first session?
3. Installer and support story: what happens after interest becomes installation?
4. Version and asset discipline: do visible names, manuals, and release objects stay aligned?
5. Privacy and compliance: what can be public, what stays private, and what needs NDA review?

### Useful Demo Request

Ask for a scoped walkthrough of one synth product page, its manual reference, its installer path under private review, and the expected support story. That is more useful than asking for every internal distribution detail at once.

## Francais

### Rôle dans l'écosystème

La surface de distribution VST fait partie de **Unicor SoundEngine**. Elle est séparée de **DAW Core**. Son rôle est de rendre la ligne synthés et FX présentable, navigable, documentée et distribuable sans laisser entendre que les VST sont fonctionnellement liés au DAW navigateur.

### Signaux distribution public-safe

| Surface | Signal public | Pourquoi c'est utile |
| --- | --- | --- |
| Assets publics | 94 assets publics inventoriés, 94 référencés runtime, 0 asset public inutilisé dans l'inventaire référencé. | La surface catalogue a été relue comme vraie couche présentation. |
| Images vitrine synthés | 23 assets publics `screen-synth`; sept images showcase copiées dans ce repo. | Les reviewers voient des visuels produit sans logs privés ni dossiers internes. |
| Manuels | Sept liens manuels propres par métadonnée runtime: Bass, Drum, Guitar, Orch, Perc, Piano, RareInstr. | La suite synthés possède des chemins documentation utilisateur. |
| Positionnement catalogue | Synthés et FX sont groupés sous Unicor SoundEngine. | La ligne plugin/son reste lisible sans être confondue avec DAW Core. |
| Limite repo public | Backend, storage, paiement, admin, binaires et artefacts release ne sont pas publiés ici. | La review publique reste sûre tout en restant utile. |

### Galerie showcase

Les images de présentation publiques sont dans [`assets/vst-showcase`](../assets/vst-showcase/README.md). Elles servent l'orientation et la review produit, pas la preuve QA brute.

### Ce qu'un distributeur ou acheteur doit reviewer ensuite

1. Clarté catalogue: l'utilisateur comprend-il la famille d'instruments et quoi télécharger?
2. Qualité manuel: chaque synthé donne-t-il assez de guidance pour une première session?
3. Histoire installer/support: que se passe-t-il après l'intérêt utilisateur?
4. Discipline version/assets: noms visibles, manuels et objets release restent-ils alignés?
5. Privacy et compliance: qu'est-ce qui peut être public, privé ou sous NDA?

### Demande de démo utile

Demander un walkthrough cadré d'une page produit synthé, sa référence manuel, son chemin installer sous review privée, et l'histoire support attendue. C'est plus utile que demander tous les détails distribution internes d'un coup.
