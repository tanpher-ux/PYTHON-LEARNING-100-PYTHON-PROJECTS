# Sentiment Analyzer (NLTK)

**Category:** [Natural Language Processing (NLP)](../README.md) &nbsp;·&nbsp; **Stack:** NLTK &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Classifies text as positive, negative, or neutral.

## Flow Diagram

```
Raw text -> tokenize/clean -> NLTK VADER/classifier -> sentiment score/label
```

## How to Build It

1. Install: `pip install nltk` then `nltk.download('vader_lexicon')`\n2. Clean input text (lowercase, strip punctuation)\n3. Use `SentimentIntensityAnalyzer().polarity_scores(text)`\n4. Map compound score to positive/neutral/negative\n5. Test on a batch of sample sentences/reviews\n6. Wrap it in a simple function/CLI

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
