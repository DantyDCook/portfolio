---
title: "Income Classification Model Evaluation"
subtitle: "A supervised-learning project using census features to evaluate predictive models for donor-targeting analysis."
course: "WGU D499 Project 1"
featured: true
priority: 5
category: "Machine Learning / Analytics"
role_targets: ["Data Analyst", "AI / ML Adjacent", "Analytics Engineer"]
technologies: ["Python", "Pandas", "NumPy", "scikit-learn", "Matplotlib", "Jupyter"]
capabilities: ["Classification", "Model evaluation", "Feature preprocessing", "Notebook analysis", "Performance comparison"]
github: https://github.com/dantydcook/D499_Project_1_Supervised/tree/main/cd0025-supervised-learning-master/starter
status: "Academic project / GitHub and local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "census rows reviewed"
    value: "45,222"
  - label: "input features documented in README"
    value: "13"
published: true
---

## Project Overview

This project evaluates supervised learning models against a modified census income dataset for a donor-targeting scenario. The previous page incorrectly described clustering; this version corrects the project identity and keeps the claims aligned to the available README and dataset evidence.

## Problem

The project asks which supervised model can best identify people likely to have income above a target threshold, using census demographic and employment features.

## Data / Inputs

The local `census.csv` file contains 45,222 rows. The README documents 13 input features such as age, workclass, education, occupation, hours per week, and native country, plus the income target variable.

## Architecture / Workflow

```text
Census dataset
    -> feature and target review
    -> preprocessing
    -> supervised model training
    -> metric comparison
    -> selected model explanation
```

## Technical Implementation

The project uses Python, NumPy, Pandas, matplotlib, scikit-learn, and Jupyter notebooks. The portfolio does not publish model performance values in this pass because the missing discovery files were not available to verify the final selected metrics.

## Results

Verified portfolio metrics are limited to dataset size and documented feature count. A later evidence pass should extract final model accuracy/F-score and selected-model rationale directly from the completed notebook before adding them here.

## Key Capabilities Demonstrated

- Supervised-learning framing and target-variable analysis.
- Model evaluation discipline without overstating unverified performance.
- Correction of a prior portfolio content mismatch.