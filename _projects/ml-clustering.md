---
title: "Identify Customer Segments"
subtitle: "An academic unsupervised-segmentation project using demographic data, PCA, K-Means, representation analysis, and a refactored Python package."
course: "WGU D499 Project 2"
featured: true
priority: 4
category: "Machine Learning / Analytics"
role_targets: ["Data Analyst", "Analytics Engineer", "AI / ML Adjacent"]
technologies: ["Python", "Pandas", "scikit-learn", "PCA", "KMeans", "Matplotlib", "Seaborn"]
capabilities: ["Dimensionality reduction", "Clustering", "Feature preprocessing", "Customer segmentation", "Data visualization"]
github: https://github.com/DantyDCook/WGU_D499_P2_DCook
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "PCA components retained"
    value: "144"
  - label: "variance explained"
    value: "90.08%"
  - label: "selected K-Means clusters"
    value: "8"
published: true
---

## Project Overview

This academic project uses demographic data, PCA, K-Means, representation analysis, centroid interpretation, and a refactored Python package to explore customer segments relative to a broader population.

## Problem

The goal was to identify segments that are overrepresented or underrepresented in the customer base and examine the characteristics that distinguish those groups.

## Data / Inputs

The project uses WGU/Udacity coursework data and keeps the results explicitly academic rather than presenting customer segments as production business findings.

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

The workflow applied PCA and retained 144 components explaining 90.08% of variance. It selected K-Means k=8 with inertia elbow analysis and programmatic KneeLocator knee detection, then refactored the segmentation workflow into a documented installable Python package with nine modules.

## Results

No silhouette score or other cluster-separation metric was computed, and the final K-Means fit is unseeded. The page therefore does not claim cluster quality, production readiness, or business impact.

## Key Capabilities Demonstrated

- Unsupervised segmentation workflow design.
- PCA, K-Means selection, and high-dimensional feature management.
- Refactoring analytical work into a reusable Python package while keeping cluster interpretation cautious.
