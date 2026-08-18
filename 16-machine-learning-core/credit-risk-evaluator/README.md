# Credit Risk Evaluator

**Category:** [Machine Learning (Core)](../README.md) &nbsp;·&nbsp; **Stack:** scikit-learn &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Classifies loan applicants as low/high default risk based on financial features.

## Flow Diagram

```
Applicant data -> preprocessing/encoding -> classification model.fit() -> predict_proba() -> risk score/decision
```

## How to Build It

1. Install: `pip install scikit-learn pandas`\n2. Load a credit/loan dataset\n3. Handle class imbalance (e.g. with `class_weight`)\n4. Train a classifier (Logistic Regression / Gradient Boosting)\n5. Evaluate with precision/recall/ROC-AUC (accuracy alone is misleading here)\n6. Inspect feature importance for explainability

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
