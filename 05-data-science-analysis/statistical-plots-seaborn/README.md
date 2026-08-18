# Statistical Plots (Seaborn)

**Category:** [Data Science & Analysis](../README.md) &nbsp;·&nbsp; **Stack:** Seaborn &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A set of statistical visualizations: distributions, correlations, box plots.

## Flow Diagram

```
DataFrame -> seaborn plotting functions -> statistical chart (with matplotlib backend) -> save/show
```

## How to Build It

1. Install: `pip install seaborn pandas`\n2. Load a sample or your own dataset\n3. Plot distributions with `sns.histplot` / `sns.kdeplot`\n4. Plot relationships with `sns.scatterplot` / `sns.pairplot`\n5. Visualize correlation with `sns.heatmap(df.corr())`\n6. Compare groups with `sns.boxplot`

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
