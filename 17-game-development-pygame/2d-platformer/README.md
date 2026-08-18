# 2D Platformer

**Category:** [Game Development (Pygame)](../README.md) &nbsp;·&nbsp; **Stack:** Pygame &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A side-scrolling platformer with gravity, jumping, and platform collisions.

## Flow Diagram

```
Game loop: input -> apply gravity/velocity -> resolve collisions with platforms -> draw sprites -> tick
```

## How to Build It

1. Install: `pip install pygame`\n2. Build a `Player` sprite with position and velocity\n3. Apply gravity every frame\n4. Handle jump input (only when grounded)\n5. Detect and resolve collisions with platform rectangles\n6. Add a scrolling camera following the player

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
