# Unit Testing (Pytest)

**Category:** [Testing & Quality Assurance](../README.md) &nbsp;·&nbsp; **Stack:** Pytest &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A full test suite demonstrating fixtures, parametrization, and mocking.

## Flow Diagram

```
Test file -> pytest discovers test_*() functions -> runs assertions -> pass/fail report
```

## How to Build It

1. Install: `pip install pytest`\n2. Write functions to test in a module\n3. Create `test_*.py` files with `test_*()` functions\n4. Use `assert` statements for checks\n5. Add fixtures with `@pytest.fixture` for setup/teardown\n6. Parametrize with `@pytest.mark.parametrize`\n7. Run with `pytest -v`

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
