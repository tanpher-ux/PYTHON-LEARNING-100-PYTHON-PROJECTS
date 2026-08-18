# Property-based Testing

**Category:** [Testing & Quality Assurance](../README.md) &nbsp;·&nbsp; **Stack:** Hypothesis &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

Tests that generate hundreds of random inputs to find edge cases automatically.

## Flow Diagram

```
Hypothesis generates many random inputs -> runs your property function -> shrinks failing case to minimal example
```

## How to Build It

1. Install: `pip install hypothesis`\n2. Pick a function with clear invariants (e.g. `sorted()` output is ordered)\n3. Write a test using `@given(st.lists(st.integers()))`\n4. Assert the property holds for all generated inputs\n5. Let Hypothesis find and shrink failing examples\n6. Add `@example()` for known edge cases

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Testing & Quality Assurance](../README.md) · [All 100 Projects](../../README.md)
