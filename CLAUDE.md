# CLAUDE.md — respace-content-portal

Savvy sync protocol. Any Claude, on any surface (Cowork or Claude Code) and in any new session, follows this so work never fragments between sessions.

## Session start (before doing anything)
1. Read `STATE.md` in this folder: current state, next steps, recent log.
2. Read standing memory: `~/Documents/Claude/memory/` (projects.md, decisions.md, people.md, preferences.md).
3. If a git repo: run `git status` and `git log --oneline -5` to see what the last session left behind.

## Session end (before you stop)
1. Append a dated entry to `STATE.md`: what changed, decisions made, the next 1 to 3 steps.
2. If a git repo: commit your work (a WIP commit is fine). Do not push unless asked.
3. If a real decision, new person, or status change happened, update the matching file in `~/Documents/Claude/memory/`.

## Canonical location
Whether this folder is the real project or a duplicate is tracked in `~/Documents/Claude/memory/projects.md`. If it is a duplicate, that file names the canonical folder. Work in the canonical one.

## Writing rules
No em dashes, ever. Absolute dates. Full rules in `~/CLAUDE.md`.
