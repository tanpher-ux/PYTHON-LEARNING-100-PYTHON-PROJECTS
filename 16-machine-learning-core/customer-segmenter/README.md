# Customer Segmenter

**Category:** [Machine Learning (Core)](../README.md) &nbsp;·&nbsp; **Stack:** scikit-learn &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Groups customers into segments using clustering on behavioral features.

## Flow Diagram

```
Customer feature data -> scale features -> K-Means clustering -> assign cluster labels -> profile each segment
```

## How to Build It

1. Install: `pip install scikit-learn pandas`\n2. Select behavioral features (recency, frequency, spend)\n3. Scale features with `StandardScaler`\n4. Use the elbow method to choose K for `KMeans`\n5. Fit and assign cluster labels to each customer\n6. Profile each cluster (mean values) to name segments

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
