# Native workflows

Open the Project menu and choose Workflows. Inspect current settings before editing. For a five-column process controlled by the author, check whether Sync with issue status is active. Where available, turn it off for this Project and leave Auto-close issue off. This allows closing through an accepted PR while avoiding an accidental close from a card move. Record the actual settings.

Set Item added to Backlog, Item closed to Done and Pull request merged to Done. Enable one Auto-add to project workflow for this repository filtered by is:issue is:open. Create a new matching issue after enabling it; earlier matching items may need manual addition. Add the demonstration PR as a separate project item to observe its own merged transition.

Observe the new issue's admission and initial Status. Record the issue and PR statuses immediately before merge. Merge a tested PR targeting main with a valid closing keyword. Inspect the linked issue's closure, its final Status and the PR item's final Status separately. Capture timestamps or timeline links. If the expected transition fails, retain the evidence and record the actual settings before any manual repair. A manual correction cannot establish that a workflow ran.

Sources: [native workflows](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-built-in-automations) and [automatic admission](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/adding-items-automatically).
