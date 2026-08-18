# GCP Cloud Storage (google-cloud)

**Category:** [Cloud Computing & Services](../README.md) &nbsp;·&nbsp; **Stack:** google-cloud-storage &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Manages files in a Google Cloud Storage bucket.

## Flow Diagram

```
Script -> google-cloud-storage client -> GCS API -> bucket operations
```

## How to Build It

1. Install: `pip install google-cloud-storage` and set up a service account key\n2. Create a `storage.Client()`\n3. Get a bucket reference: `client.bucket(name)`\n4. Upload with `blob.upload_from_filename()`\n5. List blobs and download with `blob.download_to_filename()`\n6. Add signed URL generation for temporary access

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
