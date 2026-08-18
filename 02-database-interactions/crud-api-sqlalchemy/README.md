# CRUD API with SQLAlchemy

**Category:** [Database Interactions](../README.md) &nbsp;·&nbsp; **Stack:** SQLAlchemy + FastAPI &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A REST API exposing full Create/Read/Update/Delete operations backed by SQLAlchemy ORM.

## Flow Diagram

```
Client -> REST endpoint -> SQLAlchemy Session -> DB table
```

## How to Build It

1. Install: `pip install sqlalchemy fastapi uvicorn`\n2. Define a declarative model class\n3. Create an `engine` and `SessionLocal`\n4. Write POST/GET/PUT/DELETE endpoints\n5. Use Pydantic schemas for request/response validation\n6. Add pagination to the list endpoint

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
