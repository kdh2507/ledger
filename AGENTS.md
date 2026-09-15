# Ledger Agent Instructions

## Repository structure

- This repository is an Obsidian vault containing multiple independent ledgers.
- Treat each top-level content directory as its own project.
- Read and follow any nested `AGENTS.md`; its instructions refine these rules for that directory.
- Keep work scoped to the ledger named by the user. Do not reorganize other ledgers opportunistically.

## Obsidian configuration

- Stable shared vault settings under `.obsidian/` may be versioned when intentionally changed.
- Treat `.obsidian/workspace.json` and similarly named workspace-state files as local UI state. Do not include incidental changes to them in commits.
- Do not add a community plugin or plugin-generated data unless it is required by the requested workflow.

## Commits

- After completing and verifying a requested repository change, create a focused commit unless the user asks to leave it uncommitted.
- Before committing, inspect the working tree and the staged diff.
- Stage only files changed for the current task. Preserve unrelated and pre-existing user changes.
- Use a concise, imperative commit subject that describes the outcome.
- Do not amend, rebase, force-push, or rewrite existing history unless the user explicitly requests it.
- Do not push a commit unless the user explicitly requests a push.
- Report the commit hash and mention any relevant changes intentionally left uncommitted.
