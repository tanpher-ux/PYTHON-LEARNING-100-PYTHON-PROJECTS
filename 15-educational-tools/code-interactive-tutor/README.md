# Code Interactive Tutor

**Category:** [Educational Tools](../README.md) &nbsp;·&nbsp; **Stack:** exec() sandbox + Flask &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A guided, browser-based tutorial that runs learner-submitted code and checks output.

## Flow Diagram

```
Learner submits code -> server runs it in a sandboxed subprocess -> capture stdout -> compare to expected -> feedback
```

## How to Build It

1. Design a lesson format: instructions + starter code + expected output\n2. Build a Flask endpoint that receives submitted code\n3. Run it safely in a restricted subprocess (never raw `exec` on untrusted input)\n4. Capture stdout/stderr and compare to the expected result\n5. Return pass/fail + hints\n6. Track learner progress across lessons

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
