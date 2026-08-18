# Text Quality Checker

**Category:** [Natural Language Processing (NLP)](../README.md) &nbsp;·&nbsp; **Stack:** language_tool_python &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Flags grammar, spelling, and style issues in a piece of text.

## Flow Diagram

```
Text -> LanguageTool engine -> list of issues (position + suggestion) -> report/highlight
```

## How to Build It

1. Install: `pip install language_tool_python`\n2. Initialize `LanguageTool('en-US')`\n3. Run `tool.check(text)` to get a list of matches\n4. For each match, show the message + suggested replacement\n5. Build a simple report or auto-correct mode\n6. Try it on your own writing samples

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
