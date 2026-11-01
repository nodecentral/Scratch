# Scratch

An intentionally empty repository.

## Why it exists

Cloud sessions in the Claude app's **Code** section require a GitHub repository to be selected, and there is no option to start one without a repo. That leaves no way to start a session that is "just me and Claude" for quick experiments, questions or throwaway code.

This repo fills that gap. Selecting **Scratch** means no project is attached.

## The three choices this repo stands in for

| I want to work on... | Where |
|---|---|
| Public code | A GitHub repo, via a cloud session |
| Private code | My self-hosted Gitea, via the Remote Control session on the NAS |
| Nothing in particular | **This repo** |

## Ground rules

- Nothing here should be committed. The `.gitignore` excludes everything except this file, `CLAUDE.md` and `.gitignore` itself.
- `CLAUDE.md` tells Claude not to commit, push or branch unless asked, and to hand results back in the conversation.
- Anything worth keeping gets moved to a proper repository.
