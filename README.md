# Exercise 2: Visualizing Models

Part of the workshop **Data Visualization With AI**. Prompts are on the workshop page.

## Install packages

Run this once in the R console, from the project folder:

```r
source("setup.R")
```

It installs any of this project's packages that are missing: tidyverse, rmarkdown, here, scales, mgcv, broom.

## Open the project

- **RStudio:** open the `.Rproj` file.
- **Positron or VS Code:** open this folder.
- **Claude Code or Codex:** start the tool from a terminal in this folder.

You need R and Quarto (bundled with RStudio and Positron). `setup.R` installs the packages.

## What's here

| Notebook | Use |
|---|---|
| `notebooks/01_association.qmd` | Scatterplots and smoothers |
| `notebooks/02_model-plots.qmd` | Model predictions, interactions, and diagnostics |

The check that matters: plot the model over the data. If the line doesn't follow the points, the model is wrong, however good the table looks.

## About the folders

This project was created from a [Framework](https://framework.pub) blueprint, so it has the layout of a real analysis project: data in `inputs/raw/` (codebooks in `inputs/raw/codebooks/`), your notebooks in `notebooks/`, and results in `outputs/`. `docs/reference/` holds worked reference notebooks from Erik's data visualization course; compare them with what your assistant produces. You don't need the framework R package.
