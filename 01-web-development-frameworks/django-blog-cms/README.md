# Django Blog CMS

**Category:** [Web Development Frameworks](../README.md) &nbsp;·&nbsp; **Stack:** Django &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A full blog engine with posts, categories, comments and an admin panel.

## Flow Diagram

```
Browser\n-> Django URLs\n-> Views\n-> Models (ORM)\n-> SQLite/Postgres DB\n-> Templates -> Browser
```

## How to Build It

1. Install Django: `pip install django`\n2. Start project: `django-admin startproject blogcms`\n3. Create a `posts` app: `python manage.py startapp posts`\n4. Define a `Post` model (title, body, author, created_at)\n5. Run `makemigrations` + `migrate`\n6. Register `Post` in `admin.py` to get a free admin UI\n7. Build list/detail views and templates\n8. Add a comment model with a ForeignKey to Post

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
