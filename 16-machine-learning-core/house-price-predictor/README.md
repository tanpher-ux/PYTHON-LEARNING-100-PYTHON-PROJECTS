# House Price Predictor

**Category:** [Machine Learning (Core)](../README.md) &nbsp;·&nbsp; **Stack:** scikit-learn &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A regression model predicting house prices from features like size and location.

## Flow Diagram

```
Housing dataset -> feature engineering -> train/test split -> Regression model.fit() -> predict() -> evaluate (RMSE/R2)
```

## How to Build It

1. Install: `pip install scikit-learn pandas`\n2. Load a housing dataset (e.g. Kaggle or built-in)\n3. Handle missing values and encode categorical features\n4. Split into train/test sets\n5. Train a `LinearRegression` or `RandomForestRegressor`\n6. Evaluate with RMSE/R² and inspect feature importance

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
