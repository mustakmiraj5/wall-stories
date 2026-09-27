---
name: commit
description: Generate a commit message from the current git changes and commit them. Use when the user says "commit", "commit this", "commit my changes", "write a commit message", or invokes /commit.
---

# Commit

1. Gather context in one go:
   ```sh
   git status --short && git diff --cached --stat && git diff --stat && git log --oneline -10
   ```

2. Decide what goes in:
   - Something already staged → commit only that. Don't stage more.
   - Nothing staged → stage tracked changes and relevant untracked files by path (`git add <paths>`), not `git add -A`.
   - Never stage secrets or junk: `.env*`, keys, credentials, build output, `node_modules`, OS files. If one shows up, skip it and tell the user.
   - Nothing to commit → say so and stop.

3. Read the actual diff (`git diff --cached`) before writing. The message describes what changed and why, not a file list.

4. Write the message:
   - Match the style of `git log` if it has a clear convention (e.g. Conventional Commits); otherwise use a plain imperative subject.
   - Subject ≤ 72 chars, imperative ("Add", "Fix"), no trailing period.
   - Body only when the why isn't obvious from the subject: a blank line, then short wrapped lines.
   - Unrelated changes mixed together → suggest splitting before committing.
   - Add any commit attribution trailer that the session's instructions require.

5. Commit with a heredoc so formatting survives:
   ```sh
   git commit -F - <<'EOF'
   <subject>

   <body>
   EOF
   ```

6. Show `git log --oneline -1` and stop.

## Never
- Push, amend, rebase, or use `--no-verify` unless the user asks.
- Commit when a pre-commit hook fails. Fix the cause, restage, and make a new commit.
