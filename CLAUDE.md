<!-- phoenix-command:git-workflow-rule -->
## Git workflow (Phoenix Command)

This worktree is checked out on its own feature branch. Commit and push your work to **this branch only** (`git push origin <branch>`) — never push directly to `main`, `development`, or any other target/default branch, and never merge or fast-forward this branch's work into the target branch yourself.

When work is ready, tell the user — they will review and merge it (or open a pull request) themselves via the Phoenix Command dashboard's Commit / Pull Request / Merge buttons. Do not merge into the target branch on your own initiative.
