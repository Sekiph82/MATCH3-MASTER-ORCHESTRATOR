# Cross-Repository Coordination Rules

1. **One master lead.** Master Claude alone prioritizes and dispatches cross-repository AI tasks; the owner can override.
2. **Separate repositories.** Keep code, assets, tests, history and original root TASKS.md in each original repository. This ninth repository has no game source and no duplicate task ledger.
3. **Claim tasks first.** Record repo, source TASKS ID, source SHA, assigned specialist, blocked gates and activity in the active session. **Maximum one writing agent per repo/worktree.** Concurrent workers in independent repos are allowed only where genuinely safe and available.
4. **Original evidence wins.** Do not mark PASS without the real source task's acceptance and a separate read-only Claude reviewer. Stale tests, synthetic/replayed mocks, incomplete native tests or developer claims alone are not proof.
5. **Cross-repo impact.** If Engine or either Factory changes a shared contract, create follow-up assignments for affected games/factories and demand real integration tests. Respect ENG-M24, LFX-M14, VUF-M11 gates.
6. **Real QA.** Reviewer is a different Claude agent/session and read-only. Inspect original assertions, code, SHA, actual commands/logs, negative cases, reproducibility and required screenshots. Use BLOCKED/NOT_VERIFIED when evidence is missing.
7. **Costs and safety.** No paid GitHub Actions/CI, new cloud/device spending, secrets, destructive Git operations, player data, stores, live ads/IAP, unapproved release or privacy-impacting changes without owner permission.
8. **Recovery.** On interruption re-read live GitHub and local dirty state; never silently repeat a published operation or overwrite owner changes.
9. **No phantom automation.** The documentation does not launch sessions, run indefinitely, create background services, or automatically give repo permissions. Launch only as many agents as real session/tool/resources allow.
10. **Reports.** Provide canonical task IDs, current repo SHA, actual assigned agents, commits/PRs, real test results, reviewer verdicts, blocks and next READY tasks.

## Assignment envelope

- Exact repository, branch, source SHA and original TASKS.md ID
- Owner-approved scope, expected deliverables, acceptance tests and exclusions
- Dependency and release gates; local dirty/unpushed worktree protections
- One exclusive specialist writer and separate read-only reviewer
- Actual test commands, evidence location, exact commit/PR
- PASS/FAIL/BLOCKED/NOT_VERIFIED and downstream impact

A central GitHub Project board can be configured separately in GitHub; no such board is created automatically by these Markdown files.
