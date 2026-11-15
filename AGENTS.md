# Soneverse Agent Instructions

## Personal wiki

The Obsidian wiki is stored at a user-specific local path. Read
`soneverse.local.properties` in the repository root first. This file is
intentionally not versioned.

When a task concerns ideas, concepts, decisions, project knowledge, or the
second-brain workflow, inspect the configured wiki vault first. Relevant entry
points are:

- `README.md`
- `wiki/_SYSTEM.md`
- `wiki/LLM-Wiki-Workflow.md`
- `01-Projects/Soneverse/Soneverse.md`

## Wiki change rules

- Never overwrite raw sources under `sources/`.
- Document new knowledge as Markdown with sources or dates where possible.
- Check existing pages before creating new ones.
- Mark contradictions instead of silently correcting them.
- Never store passwords, API keys, or other secrets.
- Commit wiki changes separately from the code repository.
- Summarize wiki changes before committing them.

The wiki is not an automatic background store. Read or change it only when
the current task concerns the second brain or project knowledge.

## Git safety

- Never run `git add`, `git commit`, `git push`, `git pull`, merge, rebase, or
  create/update a pull request automatically.
- Never change a remote repository or publish files without an explicit,
  current user instruction for that exact action.
- After editing files, show the user the changes and leave them uncommitted.
- A request to implement or edit files does not imply permission to commit or
  push them.
