# Code Linter

**Category:** [Educational Tools](../README.md) &nbsp;·&nbsp; **Stack:** ast &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Analyzes Python source for style issues and common mistakes.

## Flow Diagram

```
Source code -> ast.parse() -> AST -> walk tree checking rules -> report line/col + issue
```

## How to Build It

1. Parse source with `ast.parse(code)`\n2. Write an `ast.NodeVisitor` subclass\n3. Add checks (e.g. unused imports, bare except, long lines)\n4. Report issues with file, line, and message\n5. Add a simple severity/rule ID system\n6. Run it across your own codebase for real findings

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
