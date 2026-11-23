---
title: Business Definitions
owner: Khush Gill
last_reviewed: 2026-11-23
related:
  - data-model-guidance.md
  - glossary.md
---

# Business Definitions

## Hierarchies

### Product dimension
Product Type > Product Family > Product Line > Product Name

### Store dimension
Store Region > Store State > Store City > Store Name

## Retail Reporting

### Store comparisons
- When comparing stores, use same-store analysis only.
- **Same store:** a store that has been open for at least 12 months,
  based on the `Store Open Date` field.
- **Reference date:** the 12-month test is measured from **January 1, 2027**.
  A store qualifies as same-store if its `Store Open Date` is on or before
  January 1, 2026 (at least 12 months before the reference date).

## Table Guidance

- Use the **Big Buys Data Model** in the Context Hub workspace.
- https://staging.sigmacomputing.io/context-hub/data-model/Big-Buys-Data-Model-3R6ZoVIfMTCk5p0qB2dkJh
