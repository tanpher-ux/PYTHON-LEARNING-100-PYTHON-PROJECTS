# IP Geolocation Tool

**Category:** [Network Programming](../README.md) &nbsp;·&nbsp; **Stack:** requests &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Looks up the approximate geographic location of an IP address via a public API.

## Flow Diagram

```
User input IP -> requests.get(geo API) -> JSON response -> display city/country/ISP
```

## How to Build It

1. Install: `pip install requests`\n2. Pick a free IP geolocation API\n3. Send a GET request with the target IP\n4. Parse the JSON response (country, city, ISP, lat/lon)\n5. Handle invalid IPs / API errors gracefully\n6. Optionally plot the location on a map (see Folium project)

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Network Programming](../README.md) · [All 100 Projects](../../README.md)
