# Property Listing Scraper

**Category:** [Web Scraping & Data Mining](../README.md) &nbsp;·&nbsp; **Stack:** Scrapy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A Scrapy spider that crawls real-estate listing pages and extracts structured data.

## Flow Diagram

```
Scrapy Engine -> Scheduler -> Downloader -> Spider (parse) -> Item Pipeline -> Output (CSV/DB)
```

## How to Build It

1. Install: `pip install scrapy`\n2. Run `scrapy startproject listings`\n3. Define an `Item` with fields: price, address, beds, baths\n4. Write a Spider with `parse()` using CSS/XPath selectors\n5. Handle pagination with `response.follow()`\n6. Export with `scrapy crawl listings -o output.json`

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
