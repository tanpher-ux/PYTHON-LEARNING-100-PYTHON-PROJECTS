# K8s Helm deployer

**Category:** [DevOps & Workflow Tools](../README.md) &nbsp;·&nbsp; **Stack:** subprocess + PyYAML &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A Python wrapper that templates and deploys Helm charts to Kubernetes.

## Flow Diagram

```
values.yaml (per env) -> Python script renders/validates -> `helm upgrade --install` via subprocess -> deployed to cluster
```

## How to Build It

1. Install `helm` and `kubectl`; install `pip install pyyaml`\n2. Maintain per-environment `values.yaml` files\n3. Write a script that picks the right values file for the target env\n4. Run `helm upgrade --install` via `subprocess.run()`\n5. Check rollout status with `kubectl rollout status`\n6. Add a rollback command using `helm rollback`

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
