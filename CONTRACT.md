# Contract — zistgah/qaem

`qaem` (قائم — *that which stands*) is **Geometry of Persisting (Beyond Life)**, Volume III of the Geometry Trilogy, published as a poster collection on the **zistgah/kitab** template. This overlay only ADDS constraints to the master Zistgah CONTRACT at <https://github.com/zistgah/governance>; it never relaxes it.

## Derivation

* **Derived from kitab.** Plumbing — `js/`, `readers/`, `assets/theme/` — is kitab's and is **not modified here**. Only data changes: `config/`, `content/`, `assets/figures/`, `metadata/`, and these overlays. A build that edits plumbing fails this contract.
* **One documented exception:** `index.html` may carry book-specific `<head>` metadata (title, description, canonical, Open Graph / Twitter card, `theme-color`) and a `<noscript>` fallback. Everything below `<body>` — the header, `#reader-root`, the module script tag — stays kitab's. The runtime title is set from `config/book.config.json` by kitab's engine; the static head exists for crawlers, share cards, and JS-less visitors. Any edit beyond the head and the `<noscript>` block fails this contract.

## Composition

* **One poster = one chapter. Twenty-three chapters**, `ch-01`–`ch-23`, named by poster title, grouped for navigation into five parts. **Twenty-four posters in total, including the cover.**
* **The cover is the cover asset, not a chapter.** `assets/figures/cover.png` has no entry in `structure.chapters` and no file in `content/`.
* **Name pairing is an invariant.** For every chapter, the poster filename stem and the content filename stem are identical: `assets/figures/<slug>.png` ↔ `content/<slug>.json`, and the figure `src` inside that JSON resolves to its own poster. A chapter whose stems disagree, or a poster referenced by two chapters, fails this contract.
* **Titles are matched to the poster, not to the upload order.** A chapter title is what the sheet itself says. Where a mapping is asserted, it is verified against the rendered poster before it is written.

## Provenance and licensing

* **Affiliation is AyeAI only** — never "Independent Researcher". ORCID 0009-0002-0684-8320 travels with every minted record.
* **ISBN 978-81-985112-2-6** (Volume III). This is not zindagi's ISBN; the two are distinct works and their identifiers do not travel between repos.
* **Posters and chapter text CC-BY-SA-4.0** (`config/book.config.json → meta.license`). Plumbing GPL-3.0-or-later. Metadata CC0-1.0.
* **Canonical DOI metadata lives in `metadata/misty.json`.** Zenodo, DataCite and CFF forms are produced by misty, never hand-written. `meta.doi` in the book config stays `null` until a real DOI is minted, and is then written back from the mint receipt — never typed in by hand.

## Serving and governance

* **Homepage serves from repo root** — `index.html` at the Pages root, kitab convention. The homepage loads directly; it is not reached through a `docs/` landing page.
* **Framing.** The framework is presented as an integrative research proposal, not established consensus. Every chapter carries that callout; removing it fails this contract.
* Issues route by `needs:*` capability labels per master **C36** (`needs:code`, `needs:proof`, `needs:ontology`, `needs:visual`, `needs:testing`, `needs:legal`, `needs:human`). The deprecated `ai:*` labels are not used here.
* Litigation-simulation hook (C34) is kitab's default stub → `zistgah/vakil`; learning links → `zistgah/varzish`. Both kept as kitab defaults.
* Nothing is pushed or minted without Abhishek's typed gate.

Reconstruct faithfully. Critique with evidence, not tone. Maintain contract and context.

© 1982–2026 Abhishek Choudhary. All rights reserved.
