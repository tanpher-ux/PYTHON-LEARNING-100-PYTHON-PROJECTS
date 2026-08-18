# DB Migration Tool (Alembic)

**Category:** [Database Interactions](../README.md) &nbsp;·&nbsp; **Stack:** Alembic + SQLAlchemy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Version-controlled schema migrations for a SQLAlchemy-backed database.

## Flow Diagram

```
Model change -> `alembic revision --autogenerate` -> migration script -> `alembic upgrade head` -> DB schema updated
```

## How to Build It

1. Install: `pip install alembic sqlalchemy`\n2. Run `alembic init migrations`\n3. Point `env.py` at your SQLAlchemy models' metadata\n4. Generate a migration: `alembic revision --autogenerate -m "add table"`\n5. Apply it: `alembic upgrade head`\n6. Practice a rollback: `alembic downgrade -1`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Database Interactions](../README.md) · [All 100 Projects](../../README.md)
