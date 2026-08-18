# Sudoku Solver

**Category:** [Game Development (Pygame)](../README.md) &nbsp;·&nbsp; **Stack:** Pygame + backtracking &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A visual Sudoku solver that shows the backtracking algorithm working in real time.

## Flow Diagram

```
Puzzle grid -> backtracking algorithm tries values -> visualize each attempt -> backtrack on conflict -> solved grid
```

## How to Build It

1. Install: `pip install pygame`\n2. Represent the board as a 9x9 grid\n3. Implement a backtracking solver: try 1-9, recurse, undo on failure\n4. Draw the grid and redraw on each attempt for visualization\n5. Add a way to input your own puzzle\n6. Highlight conflicts and the solving path

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Game Development (Pygame)](../README.md) · [All 100 Projects](../../README.md)
