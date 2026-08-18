# Weather API Client

**Category:** [API Integration & Services](../README.md) &nbsp;·&nbsp; **Stack:** requests &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Fetches and displays current weather and forecasts for a given city.

## Flow Diagram

```
User input city -> requests.get(weather API) -> parse JSON -> display forecast
```

## How to Build It

1. Install: `pip install requests`\n2. Sign up for a free weather API key\n3. Build the request URL with city + API key\n4. Parse temperature, conditions, humidity from JSON\n5. Handle city-not-found errors\n6. Add a simple CLI or GUI front-end

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
