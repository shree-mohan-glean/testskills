---
name: commit-helper
description: >-
  Generates concise git commit messages from staged changes. Use when the user asks
  for help writing a commit message, summarizing a diff, or drafting commit text.
---

# Commit Helper

## Instructions

When asked to help with a commit message:

1. Run `git diff --staged` (or `git diff` if nothing is staged) to inspect changes.
2. Draft a 1–2 sentence message focused on **why**, not what.
3. Use imperative mood (e.g. "Add feature" not "Added feature").
4. Keep the subject line under 72 characters.

## Format

```
Short subject line (imperative, under 72 chars)

Optional body explaining motivation or context.
```

## Example

Changes: added a new SKILL.md to a skills repo

```
Add commit-helper skill for message drafting.

Covers diff inspection and imperative-style subject lines.
```
