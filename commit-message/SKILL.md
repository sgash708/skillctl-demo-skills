---
name: commit-message
description: Write a Conventional Commits message from the staged diff
---

# commit-message

Read `git diff --staged` and propose a Conventional Commits message: a short
imperative subject line (`feat:`, `fix:`, `docs:`, ...) and, only when needed, a body
that explains why the change was made.
