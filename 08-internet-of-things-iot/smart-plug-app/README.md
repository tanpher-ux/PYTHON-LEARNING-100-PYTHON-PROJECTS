# Smart Plug App

**Category:** [Internet of Things (IoT)](../README.md) &nbsp;·&nbsp; **Stack:** MicroPython + Flask &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A tiny web app to remotely toggle a relay-controlled power outlet.

## Flow Diagram

```
Phone/PC browser -> HTTP request -> microcontroller web server -> toggles relay GPIO -> plug ON/OFF
```

## How to Build It

1. Connect a relay module controlling the plug\n2. Run a tiny web server on the microcontroller (or use a Raspberry Pi + Flask)\n3. Expose `/on` and `/off` routes\n4. Toggle the relay pin from the route handler\n5. Build a minimal HTML page with two buttons\n6. Add a status endpoint to check current state

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
