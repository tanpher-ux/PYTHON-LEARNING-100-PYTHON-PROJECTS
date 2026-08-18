# Azure Blob Storage

**Category:** [Cloud Computing & Services](../README.md) &nbsp;·&nbsp; **Stack:** azure-storage-blob &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Manages files in an Azure Blob Storage container.

## Flow Diagram

```
Script -> BlobServiceClient -> Azure Storage API -> container operations
```

## How to Build It

1. Install: `pip install azure-storage-blob`\n2. Create a `BlobServiceClient` from a connection string\n3. Get/create a container client\n4. Upload with `upload_blob()`\n5. List blobs with `list_blobs()`\n6. Download and delete blobs

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
