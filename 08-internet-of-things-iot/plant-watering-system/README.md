# Plant Watering System

**Category:** [Internet of Things (IoT)](../README.md) &nbsp;·&nbsp; **Stack:** MicroPython &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Monitors soil moisture and triggers a pump when the soil gets too dry.

## Flow Diagram

```
Soil moisture sensor -> read value -> below threshold? -> activate pump for N seconds -> re-check
```

## How to Build It

1. Connect a soil moisture sensor to an ADC pin\n2. Read and calibrate dry vs wet values\n3. Set a moisture threshold\n4. Trigger a pump/relay when below threshold\n5. Add a cooldown so it doesn't overwater\n6. Log watering events

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
