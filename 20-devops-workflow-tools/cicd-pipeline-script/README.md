# CI/CD Pipeline Script

**Category:** [DevOps & Workflow Tools](../README.md) &nbsp;·&nbsp; **Stack:** PyYAML + subprocess &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A script that runs a build/test/deploy pipeline defined in a YAML config.

## Flow Diagram

```
pipeline.yaml -> parse stages -> run each stage as subprocess -> stop on failure -> report result
```

## How to Build It

1. Install: `pip install pyyaml`\n2. Define pipeline stages in a YAML file (lint, test, build, deploy)\n3. Parse the YAML into an ordered list of steps\n4. Run each step with `subprocess.run()`, capturing output\n5. Stop the pipeline on the first failing step\n6. Print a clear pass/fail summary at the end

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [DevOps & Workflow Tools](../README.md) · [All 100 Projects](../../README.md)
