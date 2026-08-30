---
title: "Industrial Pump Anomaly Detection & Alert Triage"
subtitle: "A WGU capstone project comparing a baseline Isolation Forest against staged cascade models for maintenance-alert review."
course: "WGU Data Analytics Capstone"
featured: true
priority: 1
category: "Machine Learning / Data Engineering"
role_targets: ["Data Analyst", "Analytics Engineer", "Junior Data Engineer"]
technologies: ["Python", "Pandas", "scikit-learn", "PostgreSQL", "Kafka", "Docker", "Weights & Biases"]
capabilities: ["Anomaly detection", "Model comparison", "Artifact lineage", "Medallion-style workflow", "Dashboard-ready outputs"]
image: /assets/images/projects/pump-alert-comparison.png
image_alt: "Model comparison chart for industrial pump anomaly detection alert counts and metrics."
status: "Academic capstone / local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "test alerts after Stage 3 Improved mode"
    value: "6,594"
  - label: "baseline Isolation Forest test alerts"
    value: "31,200"
  - label: "fewer test alerts than baseline"
    value: "78.9%"
  - label: "rows in early-warning review"
    value: "220,320"
published: true
---

## Project Overview

This capstone evaluates whether a staged anomaly-detection cascade can create a more useful industrial pump maintenance alert stream than a single broad Isolation Forest baseline. The project is framed as a maintenance triage aid, not as an autonomous production failure predictor.

## Problem

The baseline anomaly model generated a very large alert stream. The practical question was whether staged filtering could reduce alert burden while preserving useful early-warning behavior for reviewers.

## Data / Inputs

The local capstone archive contains pump sensor data, generated Bronze/Silver/Gold artifacts, model comparison outputs, anomaly detection summaries, and review plots. The README documents the limitation that the dataset contains limited failure examples.

## Architecture / Workflow

```text
Raw pump sensor data
    -> Bronze ingestion and standardization
    -> Silver profiling, EDA, and data-quality review
    -> Gold preprocessing and baseline modeling
    -> Cascade model variants
    -> Model comparison and anomaly timeline review
    -> Dashboard-ready summaries and plots
```

## Technical Implementation

The project uses Python notebooks and project utilities with a Medallion-style artifact structure. It includes PostgreSQL, Kafka, Docker Compose, YAML configuration, generated ledgers, truth records, and model comparison artifacts. The modeling path compares a baseline Isolation Forest with default, tuned, and Stage 3 cascade operating modes.

## Results

In the reviewed run documented in the capstone README, Stage 3 Improved reduced test alerts from 31,200 to 6,594, or about 78.9% fewer alerts than the baseline. Stage 3 Strict had higher precision and F1 but lower recall, so the project narrative treats Stage 3 Improved as the practical review mode and Stage 3 Strict as a conservative audit mode.

## Key Capabilities Demonstrated

- Translating model metrics into an operational tradeoff: alert burden, precision, recall, and reviewer workload.
- Building a repeatable analytical artifact structure with summaries, plots, lineage records, and dashboard-ready outputs.
- Communicating model limitations clearly instead of overstating predictive certainty.

## Visual Evidence

The portfolio image is a preserved capstone model-comparison plot.

## Academic Context

Completed as a WGU Data Analytics capstone. The project is evidence of academic and portfolio implementation work, not production deployment.
