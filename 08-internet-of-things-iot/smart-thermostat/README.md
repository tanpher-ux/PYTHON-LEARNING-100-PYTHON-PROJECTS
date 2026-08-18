# Smart Thermostat

**Category:** [Internet of Things (IoT)](../README.md) &nbsp;·&nbsp; **Stack:** MicroPython + sensor lib &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Reads temperature from a sensor and controls a heater/relay to hold a target temp.

## Flow Diagram

```
Temp sensor -> MicroPython read loop -> compare to target -> GPIO relay ON/OFF -> heater
```

## How to Build It

1. Wire a temperature sensor (e.g. DHT22) to your microcontroller\n2. Flash MicroPython onto the board\n3. Read temperature in a loop\n4. Compare to a target/setpoint with hysteresis\n5. Toggle a GPIO pin controlling a relay/heater\n6. Log readings over time

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
