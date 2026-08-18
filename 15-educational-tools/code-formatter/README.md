# Code Formatter

**Category:** [Educational Tools](../README.md) &nbsp;·&nbsp; **Stack:** tokenize / ast &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A tool that reformats Python code to a consistent style.

## Flow Diagram

```
Source code -> tokenize/parse (AST) -> apply formatting rules -> reconstruct formatted source
```

## How to Build It

1. Use Python's `tokenize` or `ast` module to parse source code\n2. Define formatting rules (indentation, spacing, quote style)\n3. Walk the token stream / AST and rebuild formatted output\n4. Handle edge cases: comments, multi-line strings\n5. Compare against `black`'s output for validation\n6. Wrap it as a CLI: `format.py myfile.py`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Educational Tools](../README.md) · [All 100 Projects](../../README.md)
