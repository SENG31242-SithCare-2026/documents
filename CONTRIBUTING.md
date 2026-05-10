# Contributing Guidelines

This document outlines the team's branching strategy and commit conventions for the SithCare project documentation.

## Branch Strategy
We adhere to the following branch structure:

* **`main`**: This is a protected branch that represents the latest approved version. It only accepts merges via Pull Request with at least 1 approval.
* **`draft/<document>`**: Use this prefix for an active working branch when drafting a document in progress (e.g., `draft/srs-chapter2`).
* **`fix/<issue-number>`**: Use this prefix for corrective changes addressing review feedback (e.g., `fix/42`).

## Commit Message Convention
All commits must follow the adapted Conventional Commits specification:

`<type>(<scope>): <short imperative summary>` 
`[Optional body: explain WHY this change was made, not WHAT]`
`[Optional footer: references to issues]` 

### Allowed Types
* **`docs`**: Adding or updating a document (SRS, SDS, diagrams, meeting notes).
* **`feat`**: Adding a new section, use case, or design element.
* **`fix`**: Correcting an error or incorporating review feedback.
* **`refactor`**: Restructuring a document without changing its content.
* **`chore`**: Repository housekeeping (updating `.gitignore`, `README`, etc.).
* **`style`**: Formatting changes only (font, heading levels, figure captions).

## Pull Request Process
1. Create a draft PR as soon as a branch is created to signal work-in-progress.
2. When the document or task is ready for review, mark the PR as "Ready for Review" and assign a reviewer from the team.
3. The PR description must strictly follow the standard template, which includes sections for `## Summary`, `## Changes Made`, `## Related Issues`, and a `## Review Checklist`.
