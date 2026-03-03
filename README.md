# Jets — Was könnte man stattdessen kaufen?

An interactive ISOTYPE visualization comparing Austrian military spending to social spending equivalents. Inspired by [Otto Neurath's ISOTYPE system](https://en.wikipedia.org/wiki/Isotype_(picture_language)), built with [Quarto](https://quarto.org/), [D3.js](https://d3js.org/), and [Observable JS](https://quarto.org/docs/interactive/ojs/).

**Live:** https://schmoigl.github.io/jets/

## What it does

Select a military expense (e.g. a fighter jet at €90M) and a social spending category (e.g. teacher salaries at €0.3M/year). The visualization shows how many units of the social good could be funded with the same budget — using pictographic glyphs in the ISOTYPE tradition.

## Getting Started

```bash
git clone https://github.com/schmoigl/jets.git
cd jets
quarto preview
```

## Deploy

```bash
./deploy.sh
```

Publishes to GitHub Pages via `quarto publish gh-pages`.

## Technologies

- **[Quarto](https://quarto.org/)** — Publishing system with [Observable JS](https://quarto.org/docs/interactive/ojs/) integration
- **[D3.js](https://d3js.org/)** — Data visualization
- **[Isotype Font](https://fonts.cdnfonts.com/isotype.font)** — 234+ pictographic glyphs
- **[League Spartan Font](https://fonts.google.com/specimen/League+Spartan)** — Headings

## Data

**The spending figures in `data/data_long.csv` are not real data.** They are rough illustrative estimates used to demonstrate the visualization concept and do not represent official statistics or verified sources.

## Resources

- [ISOTYPE — Wikipedia](https://en.wikipedia.org/wiki/Isotype_(picture_language))
- [Quarto with Observable](https://quarto.org/docs/interactive/ojs/)
- [D3 Gallery](https://observablehq.com/@d3/gallery)

---

**Maintained by:** [@schmoigl](https://github.com/schmoigl) | **Organization:** [WIFO](https://www.wifo.ac.at/)
