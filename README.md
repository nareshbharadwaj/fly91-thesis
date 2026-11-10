# FLY91 thesis

A data-driven artefact about FLY91, India's regional turboprop airline, and the
digital-commerce opportunity behind its "Digital Entrepreneur" role.

| Path | What it is |
| --- | --- |
| `research/dossier.md` | Sourced research: every figure links to its source and carries a confidence grade (A–D) |
| `research/derived_numbers.py` | Reproduces every calculated (grade D) figure: `python3 research/derived_numbers.py` |
| `site/` | The artefact, published by GitHub Pages (not built yet) |
| `.github/workflows/pages.yml` | Publishes `site/` to Pages on every push to `main` that changes it |

## One-time Pages setup

In the repository, open **Settings → Pages** and set **Source** to **GitHub Actions**.
The site then appears at `https://nareshbharadwaj.github.io/fly91-thesis/` once
`site/index.html` exists.

Only `site/` is published. Note that if this repository is public, the research
notes are visible on GitHub too; they contain only public, sourced material.
