# Financial Statement Parser

**Category:** [Financial Python (Fintech)](../README.md) &nbsp;·&nbsp; **Stack:** pdfplumber / pandas &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Extracts structured financial data (line items, totals) from PDF statements.

## Flow Diagram

```
PDF statement -> pdfplumber extract text/tables -> parse line items -> structured DataFrame -> export CSV
```

## How to Build It

1. Install: `pip install pdfplumber pandas`\n2. Open the PDF and extract text/tables per page\n3. Use regex or table extraction to find line items and amounts\n4. Normalize into a structured DataFrame\n5. Validate totals (e.g. sum of line items = stated total)\n6. Export the structured result to CSV/JSON

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Financial Python (Fintech)](../README.md) · [All 100 Projects](../../README.md)
