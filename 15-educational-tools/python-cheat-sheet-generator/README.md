# Python Cheat Sheet Gen

**Category:** [Educational Tools](../README.md) &nbsp;·&nbsp; **Stack:** Jinja2 &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Generates a printable PDF/HTML cheat sheet from a structured topics file.

## Flow Diagram

```
topics.yaml/json -> Jinja2 template -> rendered HTML -> (optional) HTML-to-PDF -> cheat sheet
```

## How to Build It

1. Install: `pip install jinja2`\n2. Define topics/snippets in a YAML or JSON file\n3. Build a Jinja2 HTML template with sections per topic\n4. Render the template with your data\n5. Optionally convert HTML to PDF (e.g. with `weasyprint`)\n6. Style it with simple CSS for print

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
