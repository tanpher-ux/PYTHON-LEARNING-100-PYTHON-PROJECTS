# Portfolio Optimizer

**Category:** [Financial Python (Fintech)](../README.md) &nbsp;·&nbsp; **Stack:** NumPy / SciPy / PyPortfolioOpt &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Computes an optimal asset allocation using modern portfolio theory.

## Flow Diagram

```
Historical returns -> expected returns + covariance matrix -> optimizer (maximize Sharpe / min variance) -> optimal weights
```

## How to Build It

1. Install: `pip install numpy scipy pypfopt pandas`\n2. Gather historical price data for candidate assets\n3. Compute expected returns and the covariance matrix\n4. Use `scipy.optimize` or PyPortfolioOpt to solve for optimal weights\n5. Maximize Sharpe ratio or minimize variance for a target return\n6. Plot the efficient frontier

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
