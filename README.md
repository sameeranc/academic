# Sameera Viswakula — Academic Website

Personal academic website for Sameera Viswakula, Senior Lecturer, Department of Statistics, University of Colombo. Built with [Quarto](https://quarto.org/) and published via GitHub Pages from the `docs/` folder.

Live site: https://sameeranc.github.io/academic/

## Structure

- `index.qmd` — About, experience, teaching, honors/awards, grants, and publications
- `projects.qmd` — Research project areas
- `workshops.qmd` — Workshops conducted
- `software.qmd` — Released software, R Shiny apps, and copyrights
- `_quarto.yml` — Site configuration (navbar, theme, footer)
- `img/` — Site images

## Updating the site

1. Edit the relevant `.qmd` file(s).
2. In RStudio: Build tab → Render Website (this regenerates the `docs/` folder).
3. Commit and push all changed files, including `docs/`, to GitHub.

This repo was initially generated from a Quarto template available here: https://github.com/jtr13/website-template.
