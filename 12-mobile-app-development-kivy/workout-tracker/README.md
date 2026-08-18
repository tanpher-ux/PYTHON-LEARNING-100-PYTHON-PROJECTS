# Workout Tracker

**Category:** [Mobile App Development (Kivy)](../README.md) &nbsp;·&nbsp; **Stack:** Kivy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Logs workouts (exercise, sets, reps, weight) and shows simple progress.

## Flow Diagram

```
Kivy UI (log entry form) -> save to local DB -> query history -> simple progress chart
```

## How to Build It

1. Install: `pip install kivy`\n2. Build a form to log an exercise entry\n3. Store entries in SQLite (via `sqlite3`)\n4. Build a history screen listing past workouts\n5. Add a basic progress chart (e.g. with `kivy_garden.graph`)\n6. Add filters by exercise/date

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Mobile App Development (Kivy)](../README.md) · [All 100 Projects](../../README.md)
