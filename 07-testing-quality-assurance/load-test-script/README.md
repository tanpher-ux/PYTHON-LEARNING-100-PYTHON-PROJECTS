# Load Test Script

**Category:** [Testing & Quality Assurance](../README.md) &nbsp;·&nbsp; **Stack:** Locust &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Simulates many concurrent users hitting an API to measure performance under load.

## Flow Diagram

```
Locust spawns N virtual users -> each runs task() repeatedly against target host -> aggregated stats/dashboard
```

## How to Build It

1. Install: `pip install locust`\n2. Define a `HttpUser` class with `@task` methods\n3. Set `wait_time` between simulated requests\n4. Run with `locust -f locustfile.py`\n5. Open the web UI to set user count and spawn rate\n6. Analyze response time / failure rate charts

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Testing & Quality Assurance](../README.md) · [All 100 Projects](../../README.md)
