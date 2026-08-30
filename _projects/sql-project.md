---
title: "PostgreSQL Data Transformation & Reporting Workflow"
subtitle: "A staged PostgreSQL workflow using functions, procedures, triggers, and recommendation/reporting queries."
course: "WGU D191"
featured: true
priority: 2
category: "SQL / Data Engineering"
role_targets: ["SQL Analyst", "Data Analyst", "Analytics Engineer"]
technologies: ["PostgreSQL", "SQL", "PL/pgSQL", "CTEs", "Triggers", "Stored Procedures"]
capabilities: ["Relational transformation", "Staging workflow", "Reporting query design", "Recommendation logic", "Database automation"]
status: "Academic project / local evidence"
evidence_note: "Evidence reviewed from preserved WGU coursework materials."
metrics:
  - label: "local SQL artifacts reviewed"
    value: "42"
  - label: "staging procedure imports source tables"
    value: "11"
published: true
---

## Project Overview

This project demonstrates PostgreSQL transformation and reporting work through staged SQL files, PL/pgSQL functions, stored procedures, triggers, and recommendation queries. The current portfolio version treats this as an academic database workflow, not a production system.

## Problem

The workflow organizes rental, customer, film, inventory, store, and category data into tables and reportable outputs. It supports questions such as customer viewing history, genre ranking, rental ranking, and recommendation candidates.

## Data / Inputs

The source context is the DVD rental-style database used in the D191 coursework. Preserved coursework artifacts include SQL files from the D191 SQLCode folder and staged workflow files from the vdm1 folder.

## Architecture / Workflow

```text
Source database tables
    -> Stage 1 table import procedure
    -> Stage 2 cleanup and enrichment functions
    -> Stage 3 reporting and change tracking functions
    -> Recommendation and ranking queries
    -> Reporting tables / review outputs
```

## Technical Implementation

The SQL artifacts include table creation scripts, stage procedures, cleanup functions, triggers, and CTE-heavy recommendation logic. One reviewed procedure imports 11 source tables into staging, and a reviewed recommendation query uses dense ranking, joins, exclusion logic, unions, and ordered candidate selection.

## Results

The verified metric available in this pass is structural: 42 local SQL artifacts were reviewed across the D191 SQL folders. Result-row counts and production performance metrics were not published because the missing discovery files did not provide vetted output measures.

## Key Capabilities Demonstrated

- PostgreSQL workflow decomposition with staged procedures and functions.
- SQL reporting logic with CTEs, joins, ranking, filtering, and unioned candidate sets.
- Careful academic-to-professional framing that avoids implying enterprise deployment.

## Academic Context

Completed for WGU D191. This page should receive a later CareerOps evidence pass if the project is promoted into canonical resume claims.