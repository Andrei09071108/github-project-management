# Minimum ticket requirements

A single ticket records one support request. Use the following fields when designing intake, validation, sorting, filtering, search and export. The CSV column order is id, title, category, priority, status.

| Field | Required | Allowed values |
|---|---|---|
| id | Yes | Unique string matching T followed by four digits, e.g. T0001 |
| title | Yes | Plain text with at least one non-whitespace character |
| category | Yes | Hardware, Software or Access |
| priority | Yes | High, Medium or Low |
| status | Yes | New, Assigned or Resolved |

## Synthetic records

```json
{"id":"T0001","title":"Replace demo keyboard","category":"Hardware","priority":"High","status":"New"}
```

Expected outcome: accept. All five fields are present and their values satisfy the table.

```json
{"id":"T0002","category":"Access","priority":"Low","status":"New"}
```

Expected outcome: reject and identify title as required. Both examples describe fictional requests.
