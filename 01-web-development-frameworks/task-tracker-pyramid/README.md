# Task Tracker (Pyramid)

**Category:** [Web Development Frameworks](../README.md) &nbsp;·&nbsp; **Stack:** Pyramid &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A CRUD task-tracking web app built with the Pyramid framework.

## Flow Diagram

```
Browser\n-> Pyramid Router\n-> View Callable\n-> SQLAlchemy Model\n-> DB -> Chameleon/Jinja2 Template
```

## How to Build It

1. Install: `pip install pyramid pyramid_jinja2 sqlalchemy`\n2. Scaffold a project with `pcreate`\n3. Define a `Task` model with SQLAlchemy\n4. Add routes for list/create/complete/delete task\n5. Wire views to templates\n6. Run with `pserve development.ini --reload`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Web Development Frameworks](../README.md) · [All 100 Projects](../../README.md)
