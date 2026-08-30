---
title: "Customer Segmentation with PCA & KMeans"
subtitle: "Unsupervised learning workflow comparing customer demographic clusters with a broader population dataset."
course: "WGU D499 Project 2"
featured: true
priority: 4
category: "Machine Learning / Analytics"
role_targets: ["Data Analyst", "Analytics Engineer", "AI / ML Adjacent"]
technologies: ["Python", "Pandas", "scikit-learn", "PCA", "KMeans", "Matplotlib", "Seaborn"]
capabilities: ["Dimensionality reduction", "Clustering", "Feature preprocessing", "Customer segmentation", "Data visualization"]
github: https://github.com/dantydcook/WGU_D499_P2_DCook
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "population records"
    value: "891,221"
  - label: "customer records"
    value: "191,652"
  - label: "documented features"
    value: "85"
published: true
---

## Project Overview

This project applies PCA and KMeans clustering to compare customer demographic segments with a broader German population dataset. The project is presented as academic unsupervised-learning evidence using anonymized/synthetic coursework data.

## Problem

The goal was to identify segments that are overrepresented or underrepresented in the customer base and describe the characteristics that distinguish those groups.

## Data / Inputs

Local raw files include 891,221 population records, 191,652 customer records, and an 85-row feature summary. The project README notes that the dataset and prompt came through WGU/Udacity coursework.

## Architecture / Workflow

```text
Population and customer demographic data
    -> missing-data review and preprocessing
    -> feature scaling and transformation
    -> PCA dimensionality reduction
    -> KMeans clustering
    -> customer-vs-population segment comparison
```

## Technical Implementation

The repository uses a cookiecutter-style data science structure with modules for dataset handling, transformations, imputation/scaling, PCA, clustering, plotting, and model training/prediction helpers. That structure makes it stronger than a notebook-only project for analytics engineering and reproducibility signals.

## Results

This pass publishes only verified data-size and feature-count metrics. Segment names, business interpretations, and performance-style claims should be reviewed against the notebook outputs before being promoted into resume bullets.

## Key Capabilities Demonstrated

- Unsupervised learning workflow design.
- Preprocessing and feature management for high-dimensional demographic data.
- Translating clustering outputs into cautious business-segmentation language.