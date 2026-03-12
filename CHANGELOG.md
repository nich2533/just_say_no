# Changelog

## 2.0.0 — 2026-03-12

### Breaking Changes

- **Claude Code: Migrated from commands to skills.** Files moved from `.claude/commands/<name>.md` to `.claude/skills/<name>/SKILL.md`. If you previously installed the commands, delete your old `.claude/commands/` directory and copy the new `.claude/skills/` directory in its place.

### Changed

- Claude Code frontmatter updated from `description` + `argument-hint` to `name` + `description` to match the skills format.
- Updated README to reflect the new structure.

### Unchanged

- Codex CLI skills (`.agents/skills/`) — no changes needed, already in the correct format.
- All 13 substances, their doses, and behavior — identical content.

## 1.0.0 — 2026-03-10

Initial release. 13 altered state commands for Claude Code and Codex CLI.
