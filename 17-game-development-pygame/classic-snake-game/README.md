# Classic Snake Game

**Category:** [Game Development (Pygame)](../README.md) &nbsp;·&nbsp; **Stack:** Pygame &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

The classic snake game: eat food, grow longer, avoid the walls and yourself.

## Flow Diagram

```
Game loop: handle input -> update snake position -> check collisions -> draw frame -> tick clock -> repeat
```

## How to Build It

1. Install: `pip install pygame`\n2. Set up the window and a game loop with `pygame.time.Clock`\n3. Represent the snake as a list of grid positions\n4. Handle arrow-key input to change direction\n5. Move the snake each tick and check self/wall collisions\n6. Spawn food and grow the snake when eaten

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
