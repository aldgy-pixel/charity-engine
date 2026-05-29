# charity-engine

Mirror of the Charity Engine memory files (`project_charity_engine.md`, `charity_engine_ledger.md`) so that scheduled remote Claude Code agents can read + write them.

**Local symlinks** in `~/.claude/projects/-Users-alex/memory/` point at the files in this repo. When the remote agent pushes a new council verdict or ledger entry, `git pull` here syncs the local Claude Code memory automatically.

## Files

- `project_charity_engine.md` — terminal goal, decision framework, hard rules, focus pins
- `charity_engine_ledger.md` — live capital + hours + revenue + charity-earmark ledger
- `councils-index.md` — index of weekly council verdicts saved here by the scheduled agent
- `council-YYYY-MM-DD-charity-engine.md` — individual council verdicts (created by the agent)

## Terminal goal

$10,000 to animal welfare + people in need by **2027-10-04**.
