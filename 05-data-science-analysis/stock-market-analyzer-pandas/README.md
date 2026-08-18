# Stock Market Analyzer (Pandas)

**Category:** [Data Science & Analysis](../README.md) &nbsp;·&nbsp; **Stack:** Pandas &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Analyzes historical stock data — moving averages, returns, volatility.

## Flow Diagram

```
CSV/API data -> pandas DataFrame -> compute indicators -> summary stats/plots
```

## How to Build It

1. Install: `pip install pandas yfinance`\n2. Load historical price data into a DataFrame\n3. Compute daily returns: `df['close'].pct_change()`\n4. Compute moving averages (`rolling(window).mean()`)\n5. Compute volatility (`rolling().std()`)\n6. Visualize with Matplotlib

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Data Science & Analysis](../README.md) · [All 100 Projects](../../README.md)
