# Project Context & Coding Guidelines

## Stack
- Database: PostgreSQL / MySQL
- Backend Scripting: Node.js (v20+ LTS)
- Version Control: Git / Conventional Commits

## Architecture & Conventions
- SQL scripts stored in `/sql` with sequential naming (e.g., `01_schema.sql`, `02_indexes.sql`).
- Benchmark queries must isolate execution plans with `EXPLAIN ANALYZE`.
- Keep queries modular, avoid raw wildcard selects (`SELECT *`) in production logic.
- Follow Conventional Commits format strictly (`feat:`, `fix:`, `docs:`, `perf:`).
