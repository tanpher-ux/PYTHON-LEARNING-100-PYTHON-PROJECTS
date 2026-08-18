# Serverless Deployer

**Category:** [Cloud Computing & Services](../README.md) &nbsp;·&nbsp; **Stack:** boto3 / AWS SAM CLI wrapper &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A script that packages and deploys a Python function to AWS Lambda.

## Flow Diagram

```
Local function code -> zip package -> upload to Lambda -> configure trigger -> deployed & invokable
```

## How to Build It

1. Write your handler function following the Lambda signature\n2. Package code + dependencies into a `.zip`\n3. Use `boto3` to create/update the Lambda function\n4. Attach an IAM role with the right permissions\n5. Configure a trigger (API Gateway, S3 event, schedule)\n6. Add a rollback step on deploy failure

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
