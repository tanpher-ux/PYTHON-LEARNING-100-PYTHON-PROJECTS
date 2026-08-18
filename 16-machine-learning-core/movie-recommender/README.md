# Movie Recommender

**Category:** [Machine Learning (Core)](../README.md) &nbsp;·&nbsp; **Stack:** scikit-learn / Surprise &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Recommends movies to users based on ratings similarity (collaborative filtering).

## Flow Diagram

```
Ratings matrix (users x movies) -> similarity computation -> for target user, rank unseen movies by predicted rating
```

## How to Build It

1. Install: `pip install scikit-surprise pandas`\n2. Load a ratings dataset (userId, movieId, rating)\n3. Build a user-item ratings matrix\n4. Train a collaborative-filtering model (e.g. SVD)\n5. Predict ratings for unseen movies per user\n6. Recommend the top-N highest predicted movies

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
