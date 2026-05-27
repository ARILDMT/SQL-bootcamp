# SQL Bootcamp

Educational SQL bootcamp repository with solutions for the first two modules.

## Structure

```text
.
├── SQL00/   # Basic SELECT queries, filtering, CASE, subqueries
└── SQL01/   # Set operations, JOINs, IN, EXISTS
```

Each module contains:

- `README.md` with the module overview and exercise descriptions
- `materials/model.sql` with the PostgreSQL schema and seed data
- `src/exXX/*.sql` with exercise solutions

## Setup

Create a PostgreSQL database and load the module schema:

```bash
createdb pizza_db
psql -d pizza_db -f SQL00/materials/model.sql
```

Run an exercise:

```bash
psql -d pizza_db -f SQL00/src/ex00/day00_ex00.sql
```

For `SQL01`, use the files under `SQL01/` in the same way.
