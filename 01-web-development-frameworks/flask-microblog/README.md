# Flask Microblog

**Category:** [Web Development Frameworks](../README.md) &nbsp;·&nbsp; **Stack:** Flask &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A lightweight blogging app using Flask, Jinja2 templates and SQLite.

## Flow Diagram

```
Browser\n-> Flask route\n-> function view\n-> SQLite query\n-> Jinja2 template -> Browser
```

## How to Build It

1. Install Flask: `pip install flask`\n2. Create `app.py` with a `Flask(__name__)` instance\n3. Define routes: `/`, `/post/<id>`, `/new`\n4. Use `sqlite3` or `Flask-SQLAlchemy` for storage\n5. Create Jinja2 templates in `/templates`\n6. Add a simple form to create new posts\n7. Run with `flask run`

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
