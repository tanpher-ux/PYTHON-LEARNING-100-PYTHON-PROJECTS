# AWS S3 Bucket Manager (boto3)

**Category:** [Cloud Computing & Services](../README.md) &nbsp;·&nbsp; **Stack:** boto3 &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Manages files in an S3 bucket: upload, download, list, delete.

## Flow Diagram

```
Script -> boto3 client -> AWS S3 API -> bucket operations (upload/download/list/delete)
```

## How to Build It

1. Install: `pip install boto3` and configure AWS credentials\n2. Create a client: `boto3.client('s3')`\n3. Upload files with `upload_file()`\n4. List objects with `list_objects_v2()`\n5. Download with `download_file()`\n6. Add delete + bucket-policy helper functions

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Cloud Computing & Services](../README.md) · [All 100 Projects](../../README.md)
