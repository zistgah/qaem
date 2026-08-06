# Context — zistgah/qaem

## What this is

**Geometry of Persisting (Beyond Life)** — Volume III of the Geometry Trilogy — published as a twenty-three-chapter poster collection on the **kitab** template. One poster per chapter; each poster is a self-describing "talking artifact" figure with a pop-out explanation, browser read-aloud (TTS), and BYOK Ask-AI. Three interchangeable readers (paginated, scroll, liquid) render the same content.

The repo name is قائم — *that which stands* — the persisting member of the habitat set alongside `tabdili` (becoming), `zindagi` (living) and `tarbiyat` (formation).

## Where it sits in the trilogy

| Volume | Boundary problem | Question |
|---|---|---|
| I — Geometry of Becoming | Existence | Under what conditions can an intent-bearing semantic structure emerge? |
| II — Geometry of Living | Stability | How are intent-bearing systems maintained under continuous perturbation? |
| **III — Geometry of Persisting** | **Invariance** | **What remains invariant across substrate change, context loss, deep time, and realization?** |

## Built on kitab (data replaced, plumbing untouched)

* **Data (this repo authored):** `config/book.config.json` (title, author, licence, chapter manifest, theme tokens), `content/<slug>.json` (the twenty-three chapters), `assets/figures/` (twenty-three posters + `cover.png`), `metadata/misty.json`, and these overlays.
* **Plumbing (kitab's, unchanged):** `js/{app,core,features}.js`, `readers/{paginated,scroll,liquid}.js`, `assets/theme/`, and the body of `index.html` — see <https://github.com/zistgah/kitab>. The one permitted edit is book-specific `<head>` metadata and a `<noscript>` fallback in `index.html`; see CONTRACT.md.

## Chapter mapping

Flat: 1 poster = 1 chapter, twenty-three chapters, named by poster title. Content files are named by slug, not by number, and each poster carries the same stem as its JSON. The wraparound jacket is `cover.png` — the cover asset, not a chapter — so the poster count is twenty-four including it.

**Part I — Foundations of Persistence**
1. Axiomatic Foundation of Intent Dynamics
2. Geometry Beyond Living
3. Volume III — Geometry of Persisting (Beyond Life)
4. Geometry of Persisting — Volume III Chapter Map
5. Geometry of Persisting — Beyond Life (Jacket & Contents)

**Part II — The Civilizational Architecture**
6. The Triad of Civilization: Matter · Energy · Intent
7. Cosmopolis · Humanesque · From Matter to Intent
8. Kaivalyik AGI
9. GramSheel Ecosystem
10. Geometry of Persisting — Persistent Civilizational Architecture

**Part III — Institutions, Economy & Rights**
11. The Three Equities
12. Political Science, The State, and Governance
13. Macro-Economics & Sociology
14. Geometry of Information Rights
15. Geometry of Living — Inheritance Laws as Cross-Generational Thermodynamic Conservation Protocols

**Part IV — Memory, Body & Identity**
16. History, Anthropology & Philology
17. Anti-Aging & Age Reversal
18. Canonical Identity Ontology
19. Humanity Beyond the Individual

**Part V — The Sacred & the Frontiers**
20. Jung, Archetypes & The Collective Unconscious
21. Soul · Heaven · Hell · Karma · Mysticism · The Absolute
22. Geometry of the Sacred
23. Humanity at the Frontiers of the Manifold

Two chapters carry titles from neighbouring volumes as printed on the sheets themselves — ch-15 and ch-02 — and are kept verbatim rather than renamed to fit this volume. Chapter 18 states on its own face that its dependency order is canonical and must not be reordered, flattened, or reconstructed; that ordering is preserved as delivered.

## Provenance

Author Abhishek Choudhary; affiliation AyeAI only; ORCID 0009-0002-0684-8320; ISBN 978-81-985112-2-6; posters CC-BY-SA-4.0, plumbing GPL-3.0-or-later, metadata CC0-1.0. `meta.doi` is `null` until minted. Framework presented as an integrative research proposal, not established consensus.

## Contributions

GitHub issue templates route work with `needs:*` capability labels (`needs:code`, `needs:proof`, `needs:ontology`, `needs:visual`, `needs:testing`, `needs:legal`, `needs:human`) per master C36 — the human routes at dispatch. Learning links → `zistgah/varzish`; litigation hook → `zistgah/vakil`.
