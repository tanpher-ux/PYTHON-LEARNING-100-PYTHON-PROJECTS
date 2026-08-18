# Image Classifier (TensorFlow)

**Category:** [Deep Learning & AI](../README.md) &nbsp;·&nbsp; **Stack:** TensorFlow/Keras &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Trains a CNN to classify images into categories.

## Flow Diagram

```
Image dataset -> preprocessing -> CNN layers -> training loop -> evaluate -> predict on new images
```

## How to Build It

1. Install: `pip install tensorflow`\n2. Load a dataset (e.g. CIFAR-10 or your own folder of images)\n3. Preprocess: resize, normalize pixel values\n4. Build a CNN with `Conv2D`, `MaxPooling2D`, `Dense` layers\n5. Compile with an optimizer + loss function, then `fit()`\n6. Evaluate on a test set and visualize predictions

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Deep Learning & AI](../README.md) · [All 100 Projects](../../README.md)
