# Assessing Urban Transportation Vulnerability: A Case Study of Hat Yai, Thailand

This repository contains all project materials (code, notebooks, datasets, and figures) submitted to Canvas for **MUSA 5500 Geospatial Data Science in Python**.

## Project website (URL)
https://sihan-yu429.github.io/MUSA5500_Project/

## Overview
This project evaluates transportation vulnerability to flooding in **Hat Yai, Thailand**, using the **Nov 23, 2025** flood event as a case study. The workflow includes:
- Flood exposure analysis (roads and population)
- Network vulnerability analysis (betweenness centrality; post-flood stress shift)
- Scenario analysis using DEM-based static inundation (+1 m / +3 m / +5 m)
- Interactive visualization outputs for interpretation

## Repository contents
**Folders**
- `data/` — datasets and intermediate files used in the analysis
- `docs/` — rendered website files for GitHub Pages
- `cache/` — cached outputs (generated during builds)
- `.ipynb_checkpoints/` — Jupyter autosave checkpoints (generated)

**Key notebooks (main workflow)**
- `index.ipynb` — project landing / website entry notebook
- `0_Me.ipynb` — author / project intro page
- `1_background.ipynb` — background and study context
- `2_exposure.ipynb` — flood exposure analysis (roads + population)
- `Vulnerability.ipynb` — network vulnerability analysis (centrality + stress shift)
- `4_interactive.ipynb` — interactive maps / web visualizations
- `5_Conclusion.ipynb` — discussion and conclusion

**Other files**
- `_quarto.yml` — Quarto site configuration
- `styles.scss` — website styling
- `.gitignore` — ignores generated or unnecessary files

## How to run (basic)
Open the notebooks and run them in order from `index.ipynb` (or run `1_background.ipynb` → `5_Conclusion.ipynb`).

## Website build (Quarto)
This project website is built with Quarto using `_quarto.yml`, and the rendered site is published from the `docs/` folder via GitHub Pages.

## Author
Sihan Yu
