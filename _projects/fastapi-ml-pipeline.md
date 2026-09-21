---
title: "Deploying a Scalable ML Pipeline with FastAPI"
subtitle: "An academic ML deployment project with FastAPI model serving, Docker and DVC artifact handling, CI, and config-driven scikit-learn model selection."
course: "WGU D501"
featured: false
priority: 21
category: "Machine Learning / Data Engineering"
role_targets: ["Data Analyst", "Analytics Engineer", "Junior Data Engineer"]
technologies: ["Python", "FastAPI", "scikit-learn", "Docker", "DVC", "GitHub Actions", "pytest"]
capabilities: ["Model serving", "Config-driven model selection", "Containerization", "Local artifact versioning", "CI validation"]
status: "Academic project / local and dev-container evidence"
evidence_note: "Canonical CareerOps evidence; no production deployment, users, cloud storage, MLflow, or Weights & Biases ownership is claimed."
metrics:
  - label: "captured CI result"
    value: "7 passed · 2 skipped"
published: true
---

## Project Overview

This academic project implements a FastAPI REST API serving scikit-learn model predictions. The work is presented as local or dev-container model serving—not as a deployed production API or user-facing application.

## Architecture / Workflow

```text
Training and feature-preparation code
    -> config-driven model factory
    -> versioned local data and model artifacts
    -> FastAPI GET and POST inference endpoints
    -> Docker development environment and CI checks
```

## Technical Implementation

The API includes a welcome endpoint and a POST inference endpoint supporting runtime model selection. The project containerizes the application with Docker on Ubuntu 22.04 with Conda, uses DVC against a local-filesystem remote, and establishes GitHub Actions checks for flake8 and pytest on pushes and pull requests.

## Claim Boundary

Serving evidence is limited to local or dev-container use. The DVC remote is local filesystem rather than cloud storage. MLflow and Weights & Biases ownership are not claimed, and only confirmed trained artifacts are represented.

## Key Capabilities Demonstrated

- FastAPI model serving with bounded local/development scope.
- Config-driven scikit-learn estimator selection without code changes.
- Docker, local DVC artifact handling, linting, and unit-test automation.
