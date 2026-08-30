---
title: "UFO Sightings & CDC Birth Rate Data Wrangling"
subtitle: "A Python/Pandas workflow joining cleaned UFO sighting records with CDC natality data for exploratory analysis."
course: "WGU D497"
featured: true
priority: 3
category: "Data Wrangling / Analytics"
role_targets: ["Data Analyst", "BI / Reporting Analyst", "Analytics Engineer"]
technologies: ["Python", "Pandas", "Jupyter", "Matplotlib", "Seaborn", "CSV"]
capabilities: ["Data cleaning", "Dataset joining", "Exploratory analysis", "Visualization", "Reproducible notebooks"]
github: https://github.com/dantydcook/WGU-C687-JYM1
image: /assets/images/projects/ufo-cdc-correlation.png
image_alt: "Scatter plot visual output from the UFO sightings and CDC birth rate project."
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "cleaned UFO sighting rows"
    value: "128,175"
  - label: "cleaned CDC birth-rate rows"
    value: "187,620"
  - label: "generated result plots reviewed"
    value: "6"
published: true
---

## Project Overview

This project cleans and analyzes UFO sighting records alongside CDC birth-rate data. It is strongest as evidence of data acquisition, cleaning, structured notebooks, joining, and visualization rather than as evidence of a confirmed causal relationship.

## Problem

The analytical question was whether sighting patterns and birth-rate records show meaningful temporal or regional relationships. The portfolio wording keeps the result cautious: exploratory patterns were reviewed, but no statistically significant national relationship is claimed here.

## Data / Inputs

Local cleaned data includes 128,175 UFO sighting rows and 187,620 CDC birth-rate rows. The project also includes FIPS lookup data, notebooks for extraction/cleaning/loading/transformation, and generated visual outputs.

## Architecture / Workflow

```text
UFO, CDC, and FIPS source data
    -> extraction notebooks
    -> cleaning notebooks
    -> lookup and transformation notebooks
    -> merged analytical combinations
    -> correlation and time-series plots
```

## Technical Implementation

The local project contains helper modules, setup scripts, cleaned data directories, notebook stages, and result artifacts. The workflow separates extraction, cleaning, loading, transformation, and analysis rather than putting the full project into a single one-off notebook.

## Results

The current page publishes verified dataset and artifact counts from local files. Statistical conclusions should remain cautious until the missing discovery evidence or a CareerOps review confirms exact language for correlation results.

## Key Capabilities Demonstrated

- Cleaning and joining multi-source public datasets.
- Creating reproducible notebook stages and local helper modules.
- Producing exploratory plots that communicate trends and limitations.

## Repository

The current portfolio links this project to the GitHub repository listed in the prior site content. A future pass should reconcile the GitHub repository name against the missing discovery files.
