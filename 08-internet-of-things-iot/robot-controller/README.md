# Robot Controller

**Category:** [Internet of Things (IoT)](../README.md) &nbsp;·&nbsp; **Stack:** MicroPython / RPi.GPIO &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Drives a wheeled robot's motors based on commands (manual or sensor-based).

## Flow Diagram

```
Command (keyboard/app/sensor) -> Controller logic -> GPIO PWM signals -> motor driver -> wheels move
```

## How to Build It

1. Wire motors to a motor driver board (e.g. L298N)\n2. Write functions: `forward()`, `back()`, `turn_left()`, `turn_right()`, `stop()`\n3. Use PWM for speed control\n4. Add an input method (keyboard, remote command, or ultrasonic sensor)\n5. Add obstacle-avoidance logic if using a sensor\n6. Test incrementally with low speeds first

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Internet of Things (IoT)](../README.md) · [All 100 Projects](../../README.md)
