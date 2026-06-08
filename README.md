# Paper template — Working Papers in Critical Search

Starting point for a paper in [*Working Papers in Critical Search*](https://working-papers-in-critical-search.github.io/home/). Click **Use this template** to create your own repo, then write in `index.qmd`.

## Quick start

1. Click **Use this template → Create a new repository**, owner = your own GitHub account, name = `paper-your-short-title`.
2. Clone the new repo locally.
3. Edit `index.qmd` (your paper) and `references.bib` (your bibliography). Structure the paper however makes sense for the work — no required format.
4. Preview with `quarto preview`. The site renders to `_site/` on `quarto render`.
5. When the work is ready for editorial review, email an editor with the repo URL. Editors handle the handoff into the journal organisation, GitHub Pages setup, release tagging, and DOI minting. See the full [submission guide](https://working-papers-in-critical-search.github.io/home/submit.html).

## What's in here

```
├── index.qmd                   # Your paper (edit this)
├── references.bib              # Bibliography
├── data/                       # Small data files (< 10MB) — larger goes on Zenodo / Hugging Face
├── figures/                    # Images, plots
├── _quarto.yml                 # Quarto site config (leave alone unless you know why)
├── _custom.scss / _tokens.scss # Shared journal chrome — leave alone
├── _paper.scss                 # Paper-page typography and layout — leave alone
├── _includes/                  # Topbar, footer, fonts — leave alone
├── .github/workflows/          # Auto-deploy on push to `main`
└── README.md                   # This file (replace with your abstract before submission)
```

The styling is set up so the rendered paper sits inside the journal's branded chrome (topbar / footer / typography). You don't need to touch any of the SCSS or include files; just edit `index.qmd`.

## What we're looking for

Work at the intersection of history, computation, and critical approaches to political economy, empire, and environment. Method and interpretation should be inseparable: make your evidentiary chain explicit. We publish in four formats — draft papers, dataset papers, method notes, and short pieces. Full scope and "what falls outside" on the [submission page](https://working-papers-in-critical-search.github.io/home/submit.html).

## Compute and data

We welcome work at any scale — laptop, single GPU, cluster with weeks of runtime. Be clear about what you used so readers can calibrate. The point is transparency about the analytical chain from source to claim, not one-click reproducibility.

For data: small files (`< 10 MB`) live in `data/`; larger goes on Zenodo, Hugging Face, or another DOI repository, with a link from the paper.

## Preview locally

```bash
quarto preview   # local server with live reload
quarto render    # build static site to _site/
```

You'll need [Quarto](https://quarto.org/docs/get-started/) installed.

## License

Content: CC-BY 4.0. Code: MIT unless you specify otherwise.

## Questions

[Open an issue on the main site repo](https://github.com/Working-Papers-in-Critical-Search/home/issues) or email the editors: <jim.clifford@usask.ca> / <jo.guldi@emory.edu>.
