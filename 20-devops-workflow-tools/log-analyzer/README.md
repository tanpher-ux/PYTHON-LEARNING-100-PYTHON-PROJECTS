# Log Analyzer

**Category:** [DevOps & Workflow Tools](../README.md) &nbsp;·&nbsp; **Stack:** re + pandas &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Parses server/app logs to surface error rates, patterns, and anomalies.

## Flow Diagram

```
Log files -> regex parse each line into fields -> DataFrame -> aggregate (errors/min, top patterns) -> report
```

## How to Build It

1. Define a regex matching your log line format\n2. Parse each line into structured fields (timestamp, level, message)\n3. Load parsed rows into a Pandas DataFrame\n4. Aggregate error counts over time windows\n5. Surface the most frequent error messages\n6. Flag time windows with anomalous spikes

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [DevOps & Workflow Tools](../README.md) · [All 100 Projects](../../README.md)
