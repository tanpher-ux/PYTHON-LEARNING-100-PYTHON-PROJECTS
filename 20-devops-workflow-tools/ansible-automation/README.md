# Ansible Automation

**Category:** [DevOps & Workflow Tools](../README.md) &nbsp;·&nbsp; **Stack:** ansible (Python-based) &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A set of Ansible playbooks to configure servers consistently.

## Flow Diagram

```
playbook.yml -> Ansible engine -> SSH to inventory hosts -> apply tasks idempotently -> report changed/ok/failed
```

## How to Build It

1. Install: `pip install ansible`\n2. Define an `inventory` file listing target hosts\n3. Write a playbook YAML with tasks (install packages, copy configs)\n4. Use modules like `apt`, `copy`, `service`\n5. Run with `ansible-playbook -i inventory playbook.yml`\n6. Add handlers for restart-on-change behavior

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
