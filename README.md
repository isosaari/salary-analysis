# Regressioanalyysi keskituntipalkasta

Regression analysis of hourly wages using data from 1976.

This repository contains a Quarto document that analyzes the relationship between education, work experience, and hourly wages.

## Setup

1. Push this repository to GitHub
2. Go to your repository Settings → Pages
3. Under "Source", select "Deploy from a branch" and choose the `gh-pages` branch
4. The analysis will be automatically rendered to HTML and published to GitHub Pages whenever changes are pushed to the main branch

To view the rendered analysis, visit the GitHub Pages URL for this repository (typically `https://[username].github.io/[repository-name]/`).

## Local Development

To render the document locally:

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Install R and required packages:
   ```r
   install.packages(c("wooldridge", "car"))
   ```
3. Render the document:
   ```bash
   quarto render Regressioanalyysi.qmd
   ```

