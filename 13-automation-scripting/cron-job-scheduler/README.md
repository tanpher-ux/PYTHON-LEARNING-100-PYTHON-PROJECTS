# Cron Job Scheduler

**Category:** [Automation & Scripting](../README.md) &nbsp;·&nbsp; **Stack:** schedule / APScheduler &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Runs Python functions on a recurring schedule without OS-level cron.

## Flow Diagram

```
schedule library -> checks time each loop tick -> due job? -> run function -> sleep -> repeat
```

## How to Build It

1. Install: `pip install schedule`\n2. Define the task functions you want to run\n3. Register them: `schedule.every().day.at("09:00").do(job)`\n4. Run a loop calling `schedule.run_pending()` + `time.sleep(1)`\n5. Add logging for each run\n6. For production, consider APScheduler or real cron

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Automation & Scripting](../README.md) · [All 100 Projects](../../README.md)
