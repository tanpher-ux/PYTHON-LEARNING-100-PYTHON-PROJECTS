# Text Summarizer (Spacy)

**Category:** [Natural Language Processing (NLP)](../README.md) &nbsp;·&nbsp; **Stack:** spaCy &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Extracts the most important sentences from a document as a summary.

## Flow Diagram

```
Document -> spaCy NLP pipeline -> sentence/word scoring -> pick top-N sentences -> summary
```

## How to Build It

1. Install: `pip install spacy` then `python -m spacy download en_core_web_sm`\n2. Load the doc into spaCy's `nlp()` pipeline\n3. Score words by frequency (excluding stopwords)\n4. Score each sentence by the sum of its word scores\n5. Select the top-N highest scoring sentences\n6. Reassemble them in original order as the summary

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
