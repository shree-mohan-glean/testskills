---
name: commit-helper
description: >-
  Generates concise git commit messages from staged changes, optionally using
  conventional commit prefixes. Use when the user asks for help writing a commit
  message, summarizing a diff, or drafting commit text.
---

# Commit Helper

## Instructions

When asked to help with a commit message:

1. Run `git diff --staged` (or `git diff` if nothing is staged) to inspect changes.
2. Pick a conventional prefix when it fits: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`.
3. Draft a 1–2 sentence message focused on **why**, not what.
4. Use imperative mood (e.g. "Add feature" not "Added feature").
5. Keep the subject line under 72 characters.

## Format

```
<type>: short subject line (imperative, under 72 chars)

Optional body explaining motivation or context.
```

## Example

Changes: added a new SKILL.md to a skills repo

```
docs: add commit-helper skill for message drafting

Covers diff inspection, conventional prefixes, and imperative-style subject lines.
```

## Changelog

- v2: Added conventional commit prefix guidance and changelog
