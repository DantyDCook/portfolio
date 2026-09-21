---
title: "Finding Donors for CharityML"
subtitle: "An academic supervised-classification project comparing classifiers and tuning HistGradientBoosting on a Census-derived dataset."
course: "WGU D499 Project 1"
featured: true
priority: 5
category: "Machine Learning / Analytics"
role_targets: ["Data Analyst", "AI / ML Adjacent", "Analytics Engineer"]
technologies: ["Python", "Pandas", "NumPy", "scikit-learn", "GridSearchCV", "Jupyter"]
capabilities: ["Classification", "Cross-validation", "Model evaluation", "Feature preprocessing", "Performance-versus-simplicity trade-offs"]
github: https://github.com/DantyDCook/D499_Project_1_Supervised/tree/main/cd0025-supervised-learning-master/starter
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "tuned HistGradientBoosting accuracy"
    value: "87.1%"
  - label: "F-beta (0.5)"
    value: "0.752"
published: true
---

## Project Overview

This academic supervised-classification project evaluates candidate classifiers against a Census-derived dataset for a donor-targeting scenario. It compares models, tunes HistGradientBoosting with GridSearchCV, and evaluates accuracy and F-beta trade-offs.

## Problem

The project asks which supervised model can best identify people likely to have income above a target threshold, using census demographic and employment features.

## Data / Inputs

The executed Census-derived artifact contains 45,222 rows. The project uses demographic and employment features to predict whether income exceeds the target threshold.

## Architecture / Workflow

```text
Census dataset
    -> feature and target review
    -> preprocessing
    -> classifier comparison
    -> GridSearchCV tuning
    -> accuracy and F-beta evaluation
```

## Technical Implementation

The project trains and evaluates Logistic Regression, Random Forest, Gradient Boosting, and HistGradientBoosting classifiers. The HistGradientBoosting tuning used five-fold cross-validation, 32 candidates, and 160 fits.

## Results

The tuned HistGradientBoosting model achieved 87.1% accuracy and F-beta(0.5) of 0.752. A reduced five-feature model was also evaluated as a performance-versus-simplicity trade-off. These are academic-project evaluation results, not production outcomes or business impact.

## Key Capabilities Demonstrated

- Supervised classification and target-variable analysis.
- Cross-validated model tuning and bounded performance evaluation.
- Transparent performance-versus-simplicity trade-off analysis.
