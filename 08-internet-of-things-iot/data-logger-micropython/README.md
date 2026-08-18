# Data Logger (MicroPython)

**Category:** [Internet of Things (IoT)](../README.md) &nbsp;·&nbsp; **Stack:** MicroPython &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Logs sensor readings to onboard storage or over Wi-Fi at fixed intervals.

## Flow Diagram

```
Sensor read -> timestamp -> append to file/send over WiFi -> repeat on timer
```

## How to Build It

1. Flash MicroPython to your board\n2. Read a sensor value on a timer/loop\n3. Append `timestamp,value` to a local CSV file\n4. Optionally push data over Wi-Fi to a server\n5. Rotate/limit log file size\n6. Add a way to download the log

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
