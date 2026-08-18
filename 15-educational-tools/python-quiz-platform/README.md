# Python Quiz Platform

**Category:** [Educational Tools](../README.md) &nbsp;·&nbsp; **Stack:** Flask + SQLite &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A web quiz app with multiple-choice questions, scoring, and a leaderboard.

## Flow Diagram

```
Flask routes -> serve question -> receive answer -> check + store score in SQLite -> show leaderboard
```

## How to Build It

1. Design a `Question` model (text, choices, correct answer)\n2. Build routes to serve a question and accept an answer\n3. Track score per session/user\n4. Store results in SQLite\n5. Build a leaderboard view sorted by score\n6. Add categories/difficulty levels

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Educational Tools](../README.md) · [All 100 Projects](../../README.md)
