# COMP454-3 — Data Warehouses and Data Mining

Course repository for lecture material, practical labs, datasets, SQL exercises and Databricks notebooks used in COMP454-3.

## Course flow

1. Databricks and the Lakehouse
2. Dimensional Modelling and OLAP
3. ETL / ELT in Databricks
4. Lakeflow Pipelines
5. OLAP, ROLLUP, CUBE and dashboards
6. Data Mining

## Repository structure

```text
lectures/   Lecture slide decks
labs/       Student lab manuals
 datasets/  SmartRetail source data
sql/        SQL scripts used in labs
notebooks/  Databricks / PySpark notebooks
```

## Current lecture material

| Lecture | Topic |
|---|---|
| Lecture 1 | Introduction, Lakehouse, Databricks and course architecture |
| Lecture 2 | Dimensional Modelling and OLAP |
| Lecture 3 | ETL / ELT in Databricks |

## Current labs

| Lab | Topic |
|---|---|
| Lab 0 | Databricks setup and environment |
| Lab 1 | SQL for Data Warehousing and ETL |
| Lab 2 | Building the SmartRetail dimensional warehouse |
| Lab 3 | SCD and incremental ETL |
| Lab 4 | Lakeflow Pipelines *(planned)* |
| Lab 5 | OLAP, ROLLUP, CUBE and dashboards *(planned)* |

## SmartRetail

SmartRetail is the common dataset used across the course so that students work through one coherent pipeline rather than disconnected weekly examples.

```text
Raw files
   ↓
Bronze
   ↓
Silver
   ↓
Gold dimensional warehouse
   ↓
OLAP / CUBE
   ↓
Data Mining
```

## Notes for students

- Use Databricks Free Edition unless instructed otherwise.
- Follow the lab manual for the required catalog, schema and object names.
- Do not assume that informational PK/FK constraints are enforced; validate uniqueness and orphan keys with SQL.
- Keep your own SQL and notebook work under the relevant lab folder in your personal copy/fork of this repository.

## Instructor note

Solutions should be maintained separately from the student-facing repository.
