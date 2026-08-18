# Chess AI

**Category:** [Game Development (Pygame)](../README.md) &nbsp;·&nbsp; **Stack:** python-chess &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A chess game with a simple AI opponent using minimax with alpha-beta pruning.

## Flow Diagram

```
Board state -> generate legal moves -> minimax + alpha-beta search to depth N -> evaluate leaf boards -> pick best move
```

## How to Build It

1. Install: `pip install python-chess pygame`\n2. Use `python-chess` for move generation and rules\n3. Write a board evaluation function (material + position)\n4. Implement minimax with alpha-beta pruning\n5. Limit search depth for reasonable move time\n6. Render the board and pieces with Pygame

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
