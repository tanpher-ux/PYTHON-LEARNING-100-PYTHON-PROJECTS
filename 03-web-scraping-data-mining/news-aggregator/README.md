# News Aggregator

**Category:** [Web Scraping & Data Mining](../README.md) &nbsp;·&nbsp; **Stack:** feedparser + requests &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Pulls headlines from multiple RSS feeds into one unified, de-duplicated feed.

## Flow Diagram

```
RSS Feed A -\\nRSS Feed B -> feedparser -> normalize -> de-dupe -> unified feed\nRSS Feed C -/
```

## How to Build It

1. Install: `pip install feedparser`\n2. Maintain a list of RSS feed URLs\n3. Parse each with `feedparser.parse(url)`\n4. Normalize entries into a common structure (title, link, date, source)\n5. De-duplicate near-identical headlines\n6. Sort by date and display/export the combined feed

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Web Scraping & Data Mining](../README.md) · [All 100 Projects](../../README.md)
