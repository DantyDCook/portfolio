---
title: "PostgreSQL Customer Rental Analytics & Recommendation Pipeline"
subtitle: "A five-stage academic PostgreSQL workflow using PL/pgSQL procedures, trigger-driven updates, materialized reporting views, and rule-based recommendation ranking."
course: "WGU D191"
featured: true
priority: 2
category: "SQL / Data Engineering"
role_targets: ["SQL Analyst", "Data Analyst", "Analytics Engineer"]
technologies: ["PostgreSQL", "SQL", "PL/pgSQL", "CTEs", "Window Functions", "Triggers", "Stored Procedures", "Materialized Views"]
capabilities: ["Five-stage ETL", "Relational transformation", "Materialized reporting", "Rule-based recommendation logic", "Incremental database updates"]
status: "Academic project / local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
published: true
---

## Project Overview

This academic project implements a five-stage PostgreSQL ETL pipeline across public, staging, and marketing schemas. It uses PL/pgSQL procedures, trigger-driven updates, materialized reporting views, and rule-based recommendation ranking. It is not presented as a production system, customer-data platform, or machine-learning recommender.

## Problem

The workflow organizes DVD-rental sample data into analytical and reportable outputs, including category and film popularity, customer viewing history, and recommendation candidates.

## Data / Inputs

The source context is the DVD rental-style database used in the D191 coursework. Preserved coursework artifacts include SQL files from the D191 SQLCode folder and staged workflow files from the vdm1 folder.

## Architecture / Workflow

```text
Public source tables
    -> staging import and enrichment
    -> marketing transformations
    -> trigger-driven popularity updates
    -> materialized reporting views
    -> rule-based recommendation ranking
```

## Technical Implementation

The implementation uses PL/pgSQL procedures to orchestrate the five stages, trigger functions to incrementally update popularity and recommendation tables on rental events, and SQL window functions with array-based exclusion logic to avoid previously watched films.

## Results

The project demonstrates a bounded academic implementation. It does not claim production deployment, real customer impact, benchmark performance, or machine-learning recommendation behavior.

## Key Capabilities Demonstrated

- Five-stage PostgreSQL ETL orchestration with procedures and functions.
- Trigger-driven incremental updates and materialized reporting views.
- Rule-based recommendation ranking with CTEs, joins, window functions, and array-based exclusions.

## Academic Context

Completed for WGU D191. Its public wording is based on canonical CareerOps evidence and remains explicitly academic in scope.
