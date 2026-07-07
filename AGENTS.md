# Agent Instructions

This repository is an Obsidian vault. Treat Markdown files as Obsidian Flavored
Markdown and keep vault configuration changes scoped and intentional.

## Repository Layout

- `.obsidian/` stores shared Obsidian settings and the Things theme.
- `.agents/skills/` stores the actual skill files.
- `.claude/skills/` and `.pi/skills/` are symlink views into `.agents/skills/`.
- `skills-lock.json` records the installed Obsidian skill set.

## Working Rules

- Preserve symlinks under `.claude/skills/` and `.pi/skills/`.
- Do not commit Obsidian workspace state, caches, `.env` files, dependency
  folders, logs, or OS/editor files.
- Prefer standard Markdown unless Obsidian features such as wikilinks,
  callouts, embeds, properties, Canvas files, or Bases are specifically useful.
- Use wikilinks for vault-internal note links and Markdown links for external
  URLs.
- Keep generated docs short, practical, and readable in Obsidian.

## Git

- Use Conventional Commits.
- Commit messages must be in English and ASCII.
- Stage only files relevant to the requested change.
