# Price Scraper

**Category:** [Automation & Scripting](../README.md) &nbsp;·&nbsp; **Stack:** requests + BeautifulSoup + schedule &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Runs on a schedule to track prices and alert on drops.

## Flow Diagram

```
Scheduled trigger -> scrape price -> compare to last known -> if dropped, send alert (email/notification)
```

## How to Build It

1. Reuse the scraping approach from Product Price Scraper\n2. Store historical prices with timestamps\n3. On each run, compare current price to stored minimum\n4. If price drops below a threshold, trigger an alert (email/desktop notification)\n5. Schedule the script with `schedule` or OS cron\n6. Log every run for auditing

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
