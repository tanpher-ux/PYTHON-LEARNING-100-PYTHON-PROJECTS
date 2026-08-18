# Note Taking App

**Category:** [Mobile App Development (Kivy)](../README.md) &nbsp;·&nbsp; **Stack:** Kivy &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A mobile note-taking app with create/edit/delete and local storage.

## Flow Diagram

```
Kivy UI (screens) -> App logic -> local storage (JSON/SQLite) -> persists notes
```

## How to Build It

1. Install: `pip install kivy`\n2. Design the UI in a `.kv` file (list screen + editor screen)\n3. Use `ScreenManager` to switch between screens\n4. Store notes as JSON or in SQLite\n5. Wire buttons to add/edit/delete note functions\n6. Package for Android with Buildozer

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
