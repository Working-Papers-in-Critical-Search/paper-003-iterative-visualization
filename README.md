# What Became Possible: Iterative Visualization with an LLM as a Research Method in Computational History

**Jessica Jack** · University of Saskatchewan

Paper 003 in [*Working Papers in Critical Search*](https://working-papers-in-critical-search.github.io/home/).

Read it: <https://working-papers-in-critical-search.github.io/paper-003-iterative-visualization/>

## Abstract

Agentic coding assistants have changed what is tractable for historians without a
technical background. This paper documents an iterative, LLM-supported
visualization method developed over the first months of an MA thesis on
Saskatchewan's urban settler network and Indigenous dispossession, 1880–1921.
Working in plain-English prompts with Claude Code, the author brought three
otherwise incompatible datasets — a census-derived knowledge graph, a historical
railway GIS layer, and reserve surrender records — into conversation without
writing code by hand. The argument is that the value of the method lay not in the
answers it produced but in the questions it made askable: the analytical work
migrated from programming to history. Several of the resulting interactive
visualizations are embedded live in the paper; the experiments that failed are
shown as static figures, because recognizing them as failures was itself a
research outcome.

## What's in here

```
├── index.qmd                   # The paper
├── embeds/                     # Live, scoped interactive visualizations embedded in the paper
├── data/                       # Knowledge-graph CSV + the JSON that drives the visualizations
├── code/                       # Python data-preparation and network-building scripts
├── figures/                    # Static screenshots (reserve-surrender overlay + the failed experiments)
├── _quarto.yml                 # Quarto site config
├── _custom.scss / _tokens.scss # Shared journal chrome
├── _paper.scss                 # Paper-page typography and layout
├── _includes/                  # Topbar, footer, fonts, paper-id banner, shared viz assets
└── .github/workflows/          # Auto-deploy on push to `main`
```

The interactive maps are also published as standalone full-screen pages at
[jjax07.github.io/Sask_Railway_Visualizations](https://jjax07.github.io/Sask_Railway_Visualizations/),
and their source lives in the
[Sask_Railway_Visualizations repository](https://github.com/jjax07/Sask_Railway_Visualizations).

## Preview locally

```bash
quarto preview   # local server with live reload
quarto render    # build static site to _site/
```

## License

Content: CC-BY 4.0. Code: MIT unless otherwise specified.

## Questions

[Open an issue on the main site repo](https://github.com/Working-Papers-in-Critical-Search/home/issues)
or email the editors: <jim.clifford@usask.ca> / <jo.guldi@emory.edu>.
