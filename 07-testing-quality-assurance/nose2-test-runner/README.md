# Nose2 Test Runner

**Category:** [Testing & Quality Assurance](../README.md) &nbsp;·&nbsp; **Stack:** nose2 &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A test suite run with the nose2 runner, including test discovery and plugins.

## Flow Diagram

```
Test modules -> nose2 discovers TestCase classes -> runs -> report
```

## How to Build It

1. Install: `pip install nose2`\n2. Write tests as `unittest.TestCase` subclasses\n3. Organize tests in a `tests/` package\n4. Run all tests with `nose2`\n5. Add a `unittest.cfg` for configuration\n6. Explore coverage plugin: `nose2 --with-coverage`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Testing & Quality Assurance](../README.md) · [All 100 Projects](../../README.md)
