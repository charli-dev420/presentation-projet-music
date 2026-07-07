# Current Status

This page summarizes the music-tech showcase at a public, non-source-code level.

---

## DAWWW-CORE

**Status:** main product line.

DAWWW-CORE is the priority. It is a local-first browser DAW based on Web Audio, `.dw` project continuity, export workflows, QA proof and Android testing.

Current public framing:

- browser DAW, not native VST host;
- local-first project model;
- `.dw` session continuity;
- export and recovery workflows;
- desktop and Android validation paths;
- Web Audio instruments and built-in effects.

What remains important:

- keep release claims aligned with real proof;
- avoid mixing DAWWW-CORE with the VST plugin line;
- keep documentation short, honest and product-facing;
- show real user workflows rather than long internal QA text.

---

## Unicorn Sound Engine

**Status:** separate plugin ecosystem.

Unicorn Sound Engine groups instruments, effects, manuals, audition material, packaging and distribution flows.

Current public framing:

- separate from DAWWW-CORE;
- native plugin ecosystem;
- VST instruments and FX;
- manuals, store/downloads and review material;
- audio product family, not browser runtime for DAWWW-CORE.

What remains important:

- improve per-plugin documentation;
- align names, prices, versions and packaging;
- add listening examples and product screenshots;
- document which builds are ready, pending or experimental.

---

## VST-site

**Status:** distribution layer.

The distribution site is part of the Unicorn Sound Engine path: product pages, accounts, downloads, Stripe, admin surfaces and manuals.

It should be presented as store/distribution infrastructure, not as the audio engine itself.

---

## Audition & Review

**Status:** support layer.

The review tooling supports listening notes, preset decisions, visual asset review and exportable feedback.

This is useful as proof that product quality is reviewed, not only implemented.

---

## Public showcase priority

1. Make the main README readable in under two minutes.
2. Keep DAWWW-CORE and Unicorn Sound Engine clearly separated.
3. Replace long generic documents with short product pages.
4. Keep old private/source details out of the public vitrine.
5. Add proof only when it is understandable to an external reader.

---

## Français

DAWWW-CORE reste le projet principal : DAW web local-first, Web Audio, format `.dw`, export, QA et Android.

Unicorn Sound Engine est une ligne séparée autour des instruments et effets VST, des manuels, de l’audition, du store et des téléchargements.

La priorité de cette vitrine est la clarté : montrer les projets, leur rôle, leur séparation, leur état actuel et les besoins utiles sans transformer le repo en dossier interne trop long.
