---
title: "Multi-City Bikeshare Analysis in R"
subtitle: "An academic R/Jupyter bikeshare analysis spanning Chicago, New York City, and Washington, D.C., with comparative, network, and geospatial analysis."
course: "WGU D498"
featured: false
priority: 20
category: "Analytics / BI"
role_targets: ["Data Analyst", "BI / Reporting Analyst"]
technologies: ["R", "Jupyter", "ggplot2", "sf", "osmdata", "GeoPackage", "CSV"]
capabilities: ["Data preparation", "Comparative analysis", "Network visualization", "Geospatial workflows", "Map-based visualization"]
github: https://github.com/DantyDCook/D498
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
published: true
---

## Project Overview

This academic project analyzes bikeshare data across Chicago, New York City, and Washington, D.C. using R and Jupyter. It combines data preparation, comparative analysis, network visualization, geospatial workflows, and map-based outputs.

## Problem

The project explores city-level bikeshare usage patterns and station-siting questions, while keeping the live mapping component explicitly scoped to Chicago where external queries were reliable.

## Data / Inputs

The project uses public bikeshare data for Chicago, New York City, and Washington, D.C., together with R/Jupyter analysis artifacts and geospatial inputs.

## Architecture / Workflow

```text
City bikeshare CSV files
    -> R/Jupyter analysis
    -> comparative and network analysis
    -> geospatial enrichment and mapping
    -> station/intersection heatmaps and visual outputs
```

## Key Capabilities Demonstrated

- Comparative analysis across three city datasets.
- Geospatial workflow using sf, osmdata, ggmap, Overpass API queries, GeoPackage outputs, and map-based visualization.
- Clear scope control: live station-siting analysis is presented as Chicago-only, not as a reliable multi-city live-query result.
