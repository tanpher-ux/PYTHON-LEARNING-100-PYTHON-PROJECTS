# Space Shooter

**Category:** [Game Development (Pygame)](../README.md) &nbsp;·&nbsp; **Stack:** Pygame &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A top-down arcade shooter with enemies, bullets, and score tracking.

## Flow Diagram

```
Game loop: input (move/shoot) -> update bullets/enemies -> collision detection -> update score -> draw -> tick
```

## How to Build It

1. Install: `pip install pygame`\n2. Create player, bullet, and enemy sprite classes\n3. Handle shooting on keypress, spawning bullet sprites\n4. Spawn enemies at intervals from the top of the screen\n5. Detect bullet-enemy and player-enemy collisions\n6. Track and display score, add a game-over state

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
