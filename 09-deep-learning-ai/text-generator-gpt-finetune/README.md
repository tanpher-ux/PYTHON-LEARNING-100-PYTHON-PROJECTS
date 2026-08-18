# Text Generator (GPT fine-tuning)

**Category:** [Deep Learning & AI](../README.md) &nbsp;·&nbsp; **Stack:** transformers (Hugging Face) &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Fine-tunes a small language model on custom text to generate stylistically similar output.

## Flow Diagram

```
Custom text corpus -> tokenize -> fine-tune pretrained model -> generate() -> styled text output
```

## How to Build It

1. Install: `pip install transformers datasets torch`\n2. Prepare a text dataset (plain `.txt` or `datasets` format)\n3. Load a small pretrained model + tokenizer\n4. Fine-tune with the `Trainer` API on your text\n5. Generate text with `model.generate()`\n6. Experiment with temperature/top-k sampling

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
