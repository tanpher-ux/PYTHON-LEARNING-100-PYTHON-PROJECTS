# Twitter Post Automator (Tweepy)

**Category:** [API Integration & Services](../README.md) &nbsp;·&nbsp; **Stack:** Tweepy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Schedules and posts content to X/Twitter automatically via the API.

## Flow Diagram

```
Scheduled trigger -> Tweepy client -> Twitter API v2 -> Tweet posted
```

## How to Build It

1. Install: `pip install tweepy`\n2. Get API keys from the X Developer Portal\n3. Authenticate with `tweepy.Client()`\n4. Post with `client.create_tweet(text=...)`\n5. Queue scheduled posts (e.g. with `schedule` or a cron job)\n6. Log successes/failures

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [API Integration & Services](../README.md) · [All 100 Projects](../../README.md)
