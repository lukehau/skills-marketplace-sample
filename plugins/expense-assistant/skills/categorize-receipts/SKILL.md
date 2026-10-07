---
name: categorize-receipts
description: >-
  Read receipts and assign the correct spend category to each. Use when the
  user wants receipts sorted, coded, or classified for an expense claim — e.g.
  "categorize these receipts" or "what expense category is this dinner?".
---

# Categorize receipts

Read each receipt and assign a clean, policy-aligned spend category.

## Read each receipt
- Extract merchant, date, amount, and line items.
- Note the payment method and whether tax is itemized separately.

## Classify
- Map the merchant and items to a standard category: meals, lodging, ground
  transport, airfare, supplies, or client entertainment.
- Split mixed receipts (for example, groceries plus fuel) into separate lines.
- Detect likely duplicate photos of the same transaction and group them.

## Report
- Return a table of receipts with the assigned category and a confidence note.
- Call out anything ambiguous so the user can confirm the category.
