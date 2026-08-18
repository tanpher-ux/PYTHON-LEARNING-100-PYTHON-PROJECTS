# Social Post Miner

**Category:** [Web Scraping & Data Mining](../README.md) &nbsp;·&nbsp; **Stack:** tweepy / snscrape &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Collects public posts matching a keyword or hashtag for analysis.

## Flow Diagram

```
API/Scraper -> fetch posts by keyword -> clean text -> store in DataFrame -> analyze
```

## How to Build It

1. Install a scraping/API library (e.g. `snscrape`)\n2. Define search parameters (keyword, date range)\n3. Iterate through results and extract text/date/author\n4. Store into a Pandas DataFrame\n5. Clean text (remove URLs, emojis) for analysis\n6. Export to CSV for further NLP work

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
