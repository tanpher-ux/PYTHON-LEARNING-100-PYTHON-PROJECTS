# Enterprise ERP

**Category:** [Desktop Applications (GUI)](../README.md) &nbsp;·&nbsp; **Stack:** Tkinter/PySide + SQLAlchemy &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A simplified ERP covering inventory, orders, and basic reporting.

## Flow Diagram

```
GUI forms -> business logic layer -> SQLAlchemy ORM -> relational DB (inventory/orders/customers)
```

## How to Build It

1. Design the data model: Product, Customer, Order, OrderItem\n2. Set up SQLAlchemy models and a local database\n3. Build GUI screens (list/detail/form) for each entity\n4. Wire CRUD actions to the ORM\n5. Add an orders workflow (create order -> reduce stock)\n6. Add a simple reporting screen (totals, low stock)

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Desktop Applications (GUI)](../README.md) · [All 100 Projects](../../README.md)
