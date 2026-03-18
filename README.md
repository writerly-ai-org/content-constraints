# Content Constraints

**Purpose:** Defines min/max/optimal length or count constraints for product and collection fields used across EKOM systems (shopify, enterprise, etc.).

## Structure

Top-level keys: `product`, `collection`. Each field object contains:

- `min` — number
- `max` — number
- `optimal` — number or `null`
- `unit` — string (e.g., "characters", "words", "items")

**Future Dev**: Expand this to add `target_min` and `target_max` and `structural` data.