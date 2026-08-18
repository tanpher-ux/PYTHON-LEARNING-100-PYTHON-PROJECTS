# Simple Mobile Game

**Category:** [Mobile App Development (Kivy)](../README.md) &nbsp;·&nbsp; **Stack:** Kivy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A basic touch-controlled arcade game (e.g. dodge falling objects).

## Flow Diagram

```
Kivy Clock.schedule_interval (game loop) -> update positions -> check collisions -> render widgets -> touch input controls player
```

## How to Build It

1. Install: `pip install kivy`\n2. Set up a game loop using `Clock.schedule_interval`\n3. Draw the player and obstacles as widgets/canvas instructions\n4. Handle touch input to move the player\n5. Detect collisions between player and obstacles\n6. Track and display score, add a game-over screen

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
