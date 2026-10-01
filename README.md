# Sanskar Bachani's website

My website for Mini-Project 1 in Foundations of Data Science in R.

[View the website](https://sbachani28.github.io/portfolio/)

## Files

- `index.qmd`: My bio and links to both plots.
- `basketball.qmd`: Boxplots of player ages by team in men's basketball at the 2016 Olympics.
- `movies.qmd`: A scatterplot of film budgets and worldwide box office revenue.
- `_quarto.yml`: Website settings and menu.
- `styles.css`: A file for style changes.
- `.nojekyll`: Tells GitHub Pages to skip Jekyll.
- `docs/`: HTML files for GitHub Pages.

Sanskar Bachani supplied the homepage photo.

## Run locally

Install R, Quarto, and the tidyverse package. Then run these commands from the project folder:

```sh
quarto render
touch docs/.nojekyll
quarto preview
```

The site needs an internet connection to load the TidyTuesday data. GitHub Pages serves the `docs` folder on the `main` branch.

Website setup follows [Sam Csik's Quarto tutorial](https://ucsb-meds.github.io/creating-quarto-websites/).

The layout uses the tutorial’s YAML settings. The assignment calls for the Data Viz menu and hidden messages and warnings. Each plot page shows its R code.
