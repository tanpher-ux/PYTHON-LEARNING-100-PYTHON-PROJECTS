# Matrix Calculator

**Category:** [Data Science & Analysis](../README.md) &nbsp;·&nbsp; **Stack:** NumPy &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A CLI tool for matrix operations: add, multiply, transpose, inverse, determinant.

## Flow Diagram

```
User input matrices -> NumPy arrays -> operation -> formatted result
```

## How to Build It

1. Install: `pip install numpy`\n2. Parse matrix input from the user (rows/cols)\n3. Convert to `numpy.array`\n4. Implement menu options: add, multiply, transpose, `np.linalg.inv`, `np.linalg.det`\n5. Handle dimension-mismatch errors gracefully\n6. Print results in a readable grid format

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Data Science & Analysis](../README.md) · [All 100 Projects](../../README.md)
