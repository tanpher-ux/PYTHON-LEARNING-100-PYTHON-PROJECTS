# Text Rewriter

**Category:** [Natural Language Processing (NLP)](../README.md) &nbsp;·&nbsp; **Stack:** transformers (paraphrase model) &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Rewrites input text into an alternate phrasing while preserving meaning.

## Flow Diagram

```
Input text -> tokenizer -> paraphrase model -> decode -> rewritten text
```

## How to Build It

1. Install: `pip install transformers torch`\n2. Load a pretrained paraphrasing model from Hugging Face\n3. Tokenize the input sentence\n4. Generate paraphrase(s) with `model.generate()`\n5. Decode the output tokens back to text\n6. Offer multiple rewrite variants to choose from

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Natural Language Processing (NLP)](../README.md) · [All 100 Projects](../../README.md)
