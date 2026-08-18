# Crypto Portfolio Tracker

**Category:** [Financial Python (Fintech)](../README.md) &nbsp;·&nbsp; **Stack:** requests (exchange API) &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Tracks holdings across multiple cryptocurrencies and their current value.

## Flow Diagram

```
Holdings list -> fetch live prices from exchange API -> compute value/P&L -> display summary
```

## How to Build It

1. Install: `pip install requests`\n2. Maintain a list of your holdings (coin, quantity, cost basis)\n3. Fetch live prices from a public exchange/API\n4. Compute current value and profit/loss per holding\n5. Display a summary table (with Pandas)\n6. Refresh periodically and track history

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Financial Python (Fintech)](../README.md) · [All 100 Projects](../../README.md)
