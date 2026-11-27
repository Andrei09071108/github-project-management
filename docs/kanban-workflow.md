# Kanban policy

| Status | Purpose | Enter when | Leave when |
|---|---|---|---|
| Backlog | Untriaged or deferred proposal | A need is recorded | Scope, checks and prerequisites are understood |
| Todo | Selected and ready | Priority and milestone set; prerequisites accepted | Owner starts the agreed work |
| In Progress | Work underway | A concrete deliverable is being prepared | Link the artefact and request review |
| In Review | Delivery under review | Artefact and acceptance checklist are available | All checks pass and the change is integrated; return to In Progress on failure |
| Done | Accepted delivery | Verify checks, integration and issue closure | Reopen on substantiated regression and re-triage |

Keep an impeded item in its actual state. Apply blocked, record the dependency and the action needed, and remove the label when verified. A column move alone is insufficient evidence of delivery. In this single-author exercise, check criteria against the actual diff before merging. If a premature closure moved an item to Done, reopen it and reconcile its Status.
