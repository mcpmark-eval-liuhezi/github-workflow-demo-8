# Workflow Audit

This page documents how branches, pull requests, issues, and close-out fit together in a tidy, end-to-end GitHub workflow.

## Branches

- Feature work happens on its own branch (`feature/audit-notes`) so the default branch stays clean.
- Work is commit-by-commit, each with a clear, imperative message.

## Pull Requests

- A PR (`feature/audit-notes` → `main`) is the single reviewable unit of change.
- The write-up we committed is tracked through the PR diff so reviewers can verify exactly what landed.

## Issues

- A **checklist** issue (`Demo: workflow checklist`) captures the workflow checklist.
- Smaller follow-up items are attached as sub-issues under the checklist so the work decomposes cleanly.
- Closing the checklist as completed marks the checklist item as done; open sub-issues are tracked separately.

## Close-Out

- After the PR is merged or left open for review, the checklist issue is closed as completed.
- The demo artifacts remain visible: the committed write-up, the open PR, and the open follow-up issue.

## Owner

| Field | Value |
| --- | --- |
| Login | HeziLiu |
| Display name | Hezi Liu |
| Bio | treat me like a tree |
| Location | Beijing/Guiyang |
| Company | BUPT/GZU |
