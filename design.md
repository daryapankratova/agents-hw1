# Design: Data Model and Calculations (design.md)

## Data Model

Каждая задача представлена объектом:

```json
{
  "id": "unique-string-or-number",
  "title": "string (trimmed, non-empty)",
  "hours": "number (0.5–24, step 0.5)",
  "done": "boolean"
}
