# Neural Network (from scratch)

**Category:** [Deep Learning & AI](../README.md) &nbsp;·&nbsp; **Stack:** NumPy &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Builds a feedforward neural network with backpropagation using only NumPy.

## Flow Diagram

```
Input -> weighted layers + activation (forward pass) -> loss -> backprop gradients -> update weights
```

## How to Build It

1. Install: `pip install numpy`\n2. Implement a `Layer` class with weights, biases, and an activation function\n3. Implement forward propagation through all layers\n4. Implement a loss function (e.g. MSE or cross-entropy)\n5. Implement backpropagation to compute gradients\n6. Update weights with gradient descent\n7. Test on a simple dataset like XOR

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
