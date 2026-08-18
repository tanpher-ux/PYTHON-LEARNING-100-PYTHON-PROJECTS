# System Monitor Utility

**Category:** [Desktop Applications (GUI)](../README.md) &nbsp;·&nbsp; **Stack:** psutil + Tkinter/PySide &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Displays live CPU, memory, disk, and network usage.

## Flow Diagram

```
psutil polls system stats -> update GUI widgets/charts on a timer -> live-updating dashboard
```

## How to Build It

1. Install: `pip install psutil`\n2. Read CPU/memory/disk stats with `psutil`\n3. Update GUI labels/progress bars on a timer (`after()` in Tkinter)\n4. Add a simple live-updating chart (rolling window)\n5. Add per-process listing sorted by CPU/memory\n6. Add alerts when usage crosses a threshold

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Desktop Applications (GUI)](../README.md) · [All 100 Projects](../../README.md)
