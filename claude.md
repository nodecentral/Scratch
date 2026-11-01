# Scratch: instructions for Claude

## What this repository is

This repository is intentionally empty. It exists only because the Claude app requires a GitHub repository to be selected before a cloud Code session can start. There is no "no repository" option.

Selecting this repo means: **"just Claude and me, no project attached."** Treat the session as a sandbox, not as work on this repository.

## Rules for working here

1. **Do not commit, push, create branches or open pull requests** unless I explicitly ask you to in this session. If the session tooling would push automatically, tell me before it happens.
2. **Do not edit `CLAUDE.md`, `README.md` or `.gitignore`** unless I ask.
3. **Treat the working directory as disposable.** Create whatever files you need to answer the question, test an idea or run code, but assume they will be thrown away when the session ends.
4. **Give me the result, not the repo.** When we produce something worth keeping (a script, a snippet, an answer), show it to me in the conversation so I can copy it, and say plainly that nothing has been saved anywhere.
5. **If the work outgrows a sandbox,** for example it needs a proper project, history or collaboration, say so and suggest moving it to its own repository: GitHub for public work, or my self-hosted Gitea for private work. Do not turn Scratch into that project.

## Why the .gitignore ignores everything

The `.gitignore` excludes every file except these three, so stray files can't be committed by accident. If I genuinely want to keep a file here, I will ask, and you can add it with `git add -f <file>`.
