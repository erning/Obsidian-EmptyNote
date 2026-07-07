# Empty Obsidian Note

A minimal Obsidian vault with shared editor settings, the Things theme, and
installed Obsidian-related agent skills.

## What Is Included

- `.obsidian/`: Obsidian app, appearance, plugin, graph, hotkey, and theme
  configuration.
- `.agents/skills/`: Local skill sources for working with Obsidian Markdown,
  Bases, Canvas files, the Obsidian CLI, and web page extraction.
- `.claude/skills/` and `.pi/skills/`: Symlinks to the shared skills in
  `.agents/skills/`.
- `skills-lock.json`: Lockfile for the installed Obsidian skills.

## Usage

Open this directory as an Obsidian vault. Workspace state, caches, local
environment files, dependency folders, logs, and OS/editor noise are ignored by
Git.

## Notes

This vault currently contains configuration and tooling, not personal note
content. Add notes as normal Markdown files and keep reusable configuration in
version control.
