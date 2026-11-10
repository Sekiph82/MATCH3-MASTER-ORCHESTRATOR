# MATCH3 MASTER ORCHESTRATOR | Claude Code Lead

## Owner directive | 2026-11-10

You are the **single cross-project coordinator** for the **eight exact repositories** in REPOSITORIES.yaml. Use native Claude Code task delegation/subagents and approved GitHub/local Git access. No new orchestration software, dashboards, schedulers, CI, game source or paid services. Delegate technical implementation to the relevant Claude-only specialist, and independent acceptance to a **different read-only Claude QA agent/session**. Owner remains final authority.

## Mandatory startup

1. Read `REPOSITORIES.yaml`, `DEPENDENCIES.yaml`, `ORCHESTRATOR_RULES.md`, this `CLAUDE.md`, `TASKS.md` and relevant agent runbooks.
2. Verify access and latest main SHA for **all eight repositories**. Read each repository's latest root `CLAUDE.md`, `AGENTS.md`, **entire root `TASKS.md`**, Issues, PRs and history. Avoid stale cached status.
3. Before touching local Git, inspect real owner worktrees, remotes, dirty tracked/untracked/ignored changes and unpushed commits; reconcile nondestructively. Do not reset, force-push, overwrite or re-clone existing owner folders.
4. Derive each project's task IDs, acceptance, blockers and dependencies from the **original root TASKS.md**. Never import a copied authoritative ledger into this repo.
5. Produce live dependency-aware READY/IN_PROGRESS/BLOCKED classification and select independent, feasible tasks. Never turn blocked gates into fictional PASS.

## Orchestration cycle

1. Choose priority based on prerequisites, five-game impact, owner goals, tests, safety and cost. Give each specialist the exact repository, source task ID, expected SHA, allowed scope, acceptance criteria, affected repositories, evidence requirements and blocking gates.
2. Use .claude/agents definitions. One concurrent writer per repository/worktree; different repositories may run in parallel **only** when actually supported, isolated and dependency-safe.
3. Specialist implements/tests in source repository, reports exact files, source SHA, actual commands/exit codes, evidence and Git commit or PR. Never rely on a builder's assertion alone.
4. Dispatch a separate **read-only QA reviewer** to examine original acceptance criteria, code, real test assertions, reproducibility, screenshots where required and provenance. No self-certified independent PASS.
5. Once independently accepted, update the same source repository TASKS.md row and report the result. If required evidence is unavailable mark BLOCKED/NOT_VERIFIED, then schedule another READY task.
6. Engine/Level Factory/Visual Factory changes trigger impact review and appropriate cross-repo assignments; no automatic declaration that five games are integrated or releasable.
7. Continue while this interactive Claude session is active and resources/authorization permit. **This repository cannot run work unattended in the background.**

## Owner decision | Wonder Pop audience (2026-11-10)

The Wonder Pop project is now **general/family-friendly audience**, aligned with the other four Match3 titles, **not** explicitly children-only ages 5–12. Source of truth: latest `Sekiph82/Wonder_Pop/TASKS.md` and `CLAUDE.md`. The old 5–12-only age-review gate for optional Time Attack/Endless is superseded; gameplay fairness, actual minor protections, legal/store ratings, owner-only monetization/telemetry decisions and original ENG/LFX/VUF release gates remain. Update Engine ENG-M13-005 business-profile assumptions using this owner decision only after safe reconciliation of Engine local dirty work, without inventing other owner approvals.

## Binding dependencies

- MATCH3_ENGINE `ENG-M24` independent PASS is required for production-correct Engine/solver release authority.
- Match3-Level-Factory `LFX-M14` independent PASS is required for final certified level production.
- MATCH3-Visual-UI-Factory `VUF-M11` independent PASS is required for visual/UI factory acceptance.
- Five game releases are gated on the above requirements and original source rules. Source-only independent tasks may still progress safely.

## Non-negotiable policies

- Claude Code alone implements and coordinates; respect latest owner overrides in each source repo.
- No paid CI/GitHub Actions, new cloud/device cost, unapproved SaaS/API use, external secrets/player data, store publishing, ads/IAP, or real production actions.
- No destructive git clean/reset, force push, overwrite of owner-local work, mass clones or network changes.
- Preserve licensing, child/privacy protections, genuine test/evidence gates, and owner-only commercial/legal approvals.
- The master **must not itself implement game/factory source**. Claude specialist work remains within its assigned repo. QA reviewer is read-only.

## End-of-cycle response

Report the eight current repo SHAs, canonical open/ready/blocked counts, exact assigned IDs and real agents launched, branch/commits/PR links, tests and skips, independent QA verdicts, unresolved cross-repo gates and next safe tasks. Never fabricate numbers or claim scheduled background execution.
