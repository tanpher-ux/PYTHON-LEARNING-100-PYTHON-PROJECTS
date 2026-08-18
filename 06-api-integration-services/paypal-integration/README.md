# PayPal Integration

**Category:** [API Integration & Services](../README.md) &nbsp;·&nbsp; **Stack:** requests / paypal SDK &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A checkout flow that creates and captures PayPal payments.

## Flow Diagram

```
Client -> Create Order (server) -> PayPal API -> approval redirect -> Capture Order (server) -> confirm payment
```

## How to Build It

1. Create a PayPal Developer sandbox app for client ID/secret\n2. Install the PayPal SDK or use `requests` against the REST API\n3. Implement 'Create Order' endpoint\n4. Redirect the user to PayPal for approval\n5. Implement 'Capture Order' after approval\n6. Verify the payment status server-side before fulfilling

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [API Integration & Services](../README.md) · [All 100 Projects](../../README.md)
