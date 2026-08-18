# Time Series Forecast

**Category:** [Machine Learning (Core)](../README.md) &nbsp;·&nbsp; **Stack:** statsmodels / Prophet &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Forecasts future values of a metric (sales, traffic) from historical data.

## Flow Diagram

```
Historical time series -> decompose trend/seasonality -> fit forecasting model -> predict future periods -> plot with confidence interval
```

## How to Build It

1. Install: `pip install statsmodels` or `pip install prophet`\n2. Load a date-indexed time series\n3. Check for trend/seasonality (decomposition plot)\n4. Fit a model (ARIMA or Prophet)\n5. Forecast N future periods\n6. Plot forecast with confidence intervals

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Machine Learning (Core)](../README.md) · [All 100 Projects](../../README.md)
