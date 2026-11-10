# MATCH3 MASTER ORCHESTRATOR

One **Claude Code lead**, eight independent Match3 repositories, eight Claude specialist agents, one independent read-only Claude QA role.

This ninth repository is **documentation and Claude Code configuration only**. It contains no game source, backend, database service, Github Actions, scheduler daemon or dashboard application. Merely publishing it does **not** automatically grant GitHub permissions, run Claude or continuously monitor repos.

## Managed repositories

- [Level Factory](https://github.com/Sekiph82/Match3-Level-Factory) : `Sekiph82/Match3-Level-Factory`
- [Engine](https://github.com/Sekiph82/MATCH3_ENGINE) : `Sekiph82/MATCH3_ENGINE`
- [Visual Factory](https://github.com/Sekiph82/MATCH3-Visual-UI-Factory) : `Sekiph82/MATCH3-Visual-UI-Factory`
- [Coral Rescue](https://github.com/Sekiph82/Coral_Rescue) : `Sekiph82/Coral_Rescue`
- [Garage Legends](https://github.com/Sekiph82/Garage_Legends) : `Sekiph82/Garage_Legends`
- [Dino Islands](https://github.com/Sekiph82/Dino_Islands) : `Sekiph82/Dino_Islands`
- [Wonder Pop](https://github.com/Sekiph82/Wonder_Pop) : `Sekiph82/Wonder_Pop`
- [The Fractured Realms](https://github.com/Sekiph82/The_Fractured_Realms) : `Sekiph82/The_Fractured_Realms`

All original repositories remain separate. Their original root `TASKS.md` is the canonical task tracker; this master repo maintains only coordination instructions.

## Start with Claude Code

1. Open this repository in an authorized Claude Code session. Give Claude access to all eight source repositories and their real existing Windows worktrees; do **not** overwrite uncommitted or unpushed local work.
2. Read `CLAUDE.md`, `REPOSITORIES.yaml`, `DEPENDENCIES.yaml`, `ORCHESTRATOR_RULES.md`, and relevant `.claude/agents/` definitions.
3. Ask the lead: "Act as MATCH3 MASTER ORCHESTRATOR. Inspect all eight live GitHub repositories, canonical TASKS.md, Issues/PRs and current worktrees. Prioritize dependency-safe work, delegate tasks to Claude-only specialist agents, require separate read-only Claude QA and report all real outcomes."
4. Limit parallel workers to actual tool, compute, permission and dependency constraints. The master must not claim background execution when the Claude session is inactive.

## Directory contents

- `CLAUDE.md`: authoritative lead prompt.
- `REPOSITORIES.yaml`: exact GitHub repo and agent mapping.
- `DEPENDENCIES.yaml`: impact analysis and final release gates.
- `ORCHESTRATOR_RULES.md`: delegation, QA, cost and safety rules.
- `.claude/agents/*.md`: Claude Code subagent definitions with frontmatter.
- `agents/*.md`: project-specific runbooks.
- `orchestrator/*.md`: six text-only coordination procedures.
- `state/`, `reports/`, `dashboards/`: templates, **not** running software.

No paid GitHub Actions, cloud/device tests, API spending, release, player data access, store submissions or destructive Git operations are authorized without explicit owner approval.
