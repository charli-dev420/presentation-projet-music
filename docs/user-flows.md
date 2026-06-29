# User Flows / Flux utilisateur

[EN](#english) | [FR](#francais)

## English

### Flow 1 - Create And Preserve A DAW Core Project

1. The user creates a local DAW Core project.
2. They add musical material: tracks, instruments, effects, arrangement decisions, and project state.
3. They save the project using the portable `.dw` contract.
4. They reload the project on the supported surface being evaluated.
5. They check whether the musical state, assets, snapshots, and expected behavior remain coherent.
6. They produce feedback as a product observation, not just as a crash report.

This is the flagship workflow because it turns DAW Core into a continuity product: the project is the object being protected.

### Flow 2 - Review A `.dw` Portable Project

1. Start from a known project scenario.
2. Confirm the expected project content: musical state, required sampler assets, instrument/effect snapshots, and metadata.
3. Save or export the `.dw`.
4. Import or reload it on the target surface.
5. Review checksums, embedded assets, snapshots, and musical continuity.
6. Record whether the issue is functional, sonic, UX-related, packaging-related, or device-specific.

For partners, this flow is the best way to ask for a focused demo: define the scenario, target surface, expected proof, and shareability rules in advance.

### Flow 3 - Android Beta Evaluation

1. Pick the Android device class and audio route being evaluated.
2. Choose a small DAW Core scenario: open project, save project, reload project, route audio, or validate a known workflow.
3. Run the scenario through the current Android gate or guided beta checklist.
4. Capture a public-safe summary: device class, scenario, result, reproducibility, and blocker level.
5. Keep raw logs, device identifiers, builds, and local paths private.

The Android story should be treated as a beta track with recertification. That is a strength for review work: the next proof step is explicit instead of vague.

### Flow 4 - Discover Unicor SoundEngine

1. Start with DAW Core to understand why the ecosystem exists.
2. Choose a musical need: instrument, sound layer, effect treatment, or distribution review.
3. Read the relevant suite page: [synth suite](synth-suite.md) or [VST distribution](vst-distribution.md).
4. Evaluate the role of the plugin family around the workstation.
5. Provide feedback on musical usefulness, UX clarity, compatibility, documentation, or distribution readiness.

### Flow 5 - Evaluate As Buyer, Partner, Or Recruiter

1. Read the [one-pager](one-pager.md) and [project map](project-map.md).
2. Review [evidence](evidence.md), [proof pack](proof-pack.md), and [release readiness](release-readiness.md).
3. Decide which surface matters most: DAW Core desktop, Android beta, synth suite, FX suite, VST distribution, or QA process.
4. Ask for a private demo with a clear success criterion.
5. Separate public material from NDA material before requesting artifacts.

### Useful Feedback Format

| Field | Example |
| --- | --- |
| Surface | DAW Core desktop, Android beta, synth suite, VST site. |
| Scenario | Save/reload `.dw`, route audio, review synth UX, inspect manual link. |
| Expected result | Project state survives reload; UI remains understandable; asset loads. |
| Observed result | What happened, in practical musical terms. |
| Reproducibility | Once, frequent, always, device-specific, project-specific. |
| Impact | Cosmetic, workflow friction, sonic issue, release blocker. |

## Francais

### Flux 1 - Créer et préserver un projet DAW Core

1. L'utilisateur crée un projet DAW Core local.
2. Il ajoute du matériel musical: pistes, instruments, effets, arrangement et état projet.
3. Il sauvegarde avec le contrat portable `.dw`.
4. Il recharge le projet sur la surface supportée en évaluation.
5. Il vérifie que l'état musical, les assets, les snapshots et le comportement attendu restent cohérents.
6. Il formule un retour produit, pas seulement un rapport de crash.

Ce flux est le plus important parce qu'il présente DAW Core comme un produit de continuité: l'objet à protéger est le projet.

### Flux 2 - Reviewer un projet portable `.dw`

1. Partir d'un scénario projet connu.
2. Confirmer le contenu attendu: état musical, assets sampler requis, snapshots instruments/effets et métadonnées.
3. Sauvegarder ou exporter le `.dw`.
4. Importer ou recharger sur la surface cible.
5. Vérifier checksums, assets embarqués, snapshots et continuité musicale.
6. Classer le retour: fonctionnel, sonore, UX, packaging ou device-specific.

Pour un partenaire, c'est le meilleur format de démo ciblée: scénario, surface, preuve attendue et règles de partage sont définis avant le test.

### Flux 3 - Evaluation beta Android

1. Choisir la classe d'appareil Android et la route audio à évaluer.
2. Choisir un petit scénario DAW Core: ouvrir, sauvegarder, recharger, router l'audio ou valider un workflow connu.
3. Passer le scénario dans le gate Android courant ou la checklist beta guidée.
4. Produire une synthèse public-safe: classe device, scénario, résultat, reproductibilité et niveau de blocage.
5. Garder logs bruts, identifiants device, builds et chemins locaux privés.

Android doit être lu comme une piste beta avec recertification. C'est utile pour la review: la prochaine preuve attendue est explicite.

### Flux 4 - Découvrir Unicor SoundEngine

1. Commencer par DAW Core pour comprendre pourquoi l'écosystème existe.
2. Choisir un besoin musical: instrument, couche sonore, traitement FX ou review distribution.
3. Lire la page correspondante: [suite synthés](synth-suite.md) ou [distribution VST](vst-distribution.md).
4. Evaluer le rôle de la famille plugin autour de la workstation.
5. Remonter un retour sur utilité musicale, clarté UX, compatibilité, documentation ou readiness distribution.

### Flux 5 - Evaluer comme acheteur, partenaire ou recruteur

1. Lire le [one-pager](one-pager.md) et la [carte projet](project-map.md).
2. Lire [evidence](evidence.md), [proof pack](proof-pack.md) et [release readiness](release-readiness.md).
3. Choisir la surface prioritaire: DAW Core desktop, beta Android, synthés, FX, distribution VST ou process QA.
4. Demander une démo privée avec critère de succès clair.
5. Séparer matériel public et matériel NDA avant de demander des artefacts.

### Format de retour utile

| Champ | Exemple |
| --- | --- |
| Surface | DAW Core desktop, beta Android, suite synthés, VST site. |
| Scénario | Save/reload `.dw`, routing audio, review UX synthé, lien manuel. |
| Résultat attendu | L'état projet survit au reload; l'UI reste lisible; l'asset charge. |
| Résultat observé | Ce qui s'est produit, en termes musicaux pratiques. |
| Reproductibilité | Une fois, fréquent, toujours, spécifique device, spécifique projet. |
| Impact | Cosmétique, friction workflow, souci sonore, bloqueur release. |
