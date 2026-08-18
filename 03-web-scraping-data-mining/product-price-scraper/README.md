# Product Price Scraper

**Category:** [Web Scraping & Data Mining](../README.md) &nbsp;·&nbsp; **Stack:** requests + BeautifulSoup &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Scrapes product prices from e-commerce pages and tracks price changes over time.

## Flow Diagram

```
requests.get(url) -> HTML\nBeautifulSoup parses HTML -> extract price\nSave to CSV/DB -> compare over time
```

## How to Build It

1. Install: `pip install requests beautifulsoup4`\n2. Fetch the page HTML with `requests.get()`\n3. Parse with `BeautifulSoup(html, 'html.parser')`\n4. Use CSS selectors to find the price element\n5. Store results with a timestamp in CSV/SQLite\n6. Schedule it to run daily and alert on price drops

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
