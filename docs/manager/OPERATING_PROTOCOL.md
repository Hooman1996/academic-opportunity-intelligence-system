# AOIS manager, implementer and review protocol

Finalized 25 October 2026 under Implementation Plan v2. The owner authorizes tasks; ChatGPT and Claude manage/review; Codex or Claude Code can execute the assigned bounded task in a supported local environment. All four desktop/web research surfaces are product requirements.

## Authority and cycle

GitHub is the shared technical/review record, not the findings database. Private files and cloud bundles own investigation state. Chat memory and an agent's local notes are not an approval record or canonical data store.

1. Inspect actual repository, applicable AGENTS, exact branch/base, status and current task.
2. Manager prepares one bounded task; user issues/authorizes it.
3. Assigned implementer preserves unrelated changes, implements and performs meaningful checks.
4. Push a task branch and return exact base/head, changed behavior/files, commands/results, skips/limits, deviations and worktree status.
5. ChatGPT and Claude independently inspect the exact revision and relevant diff/artifacts. Self-checks are not independent review.
6. Record findings/dispositions and verification of fixes. Material blockers stop the next component.
7. User resolves material disagreements and controls merge/publication/consequential actions.
8. Issue the next component only after its gate closes.

No automatic main merge, force-push, deployment, watch activation, message sending or application submission. Review at a changed HEAD does not retroactively validate an older revision.

## Task envelope and ownership

Every issued task includes ID, objective, repository, expected base branch/revision, dependencies, permitted scope, exclusions, expected components, tests/checks, privacy/security, acceptance, task branch, commit/push expectations, final report and stop condition.

Codex/Claude Code may make routine implementation choices; major architecture/private authority/completion/provider/spend/hosting/action changes return to the managers. Use one implementation owner per task and separate Git worktrees for concurrent code changes.

Use one writable owner/authority per university. The other agent can review frozen records. Local locking, revision checks and atomic saves belong in shared code. A lock timeout alone cannot permit takeover. Cross-store handoff freezes the old writer, verifies a revisioned destination bundle and records the new owner/epoch. Cloud watches write unique private run proposals; they do not overwrite active local records.

## Review records

Findings contain ID, reviewer, reviewed SHA, severity, exact path/section/behavior, evidence/reproduction, consequence and minimal correction. Dispositions: accepted, accepted-with-change, rejected-with-evidence, deferred-with-trigger, or needs-owner-decision. Fixes identify commit and actual retest.

Verdicts: APPROVED, APPROVED WITH MINOR FOLLOW-UP, CHANGES REQUIRED, BLOCKED. Keep each reviewer's outcome distinct. Minor follow-up has an owner/task/trigger; material privacy, correctness, authority or unsupported-capability failures are not minor. No silence-based approval or invented external review.

## Owner constraints

- AGENTS.md is the sole repository-level instruction file; no CLAUDE.md or CLAUDE.local.md. Validate installed Claude support.
- No embeddings/vector/semantic similarity features. Use field vocabulary and evidence-grounded reasoning.
- The first usable output includes polished self-contained HTML and CSV from structured JSON.
- CV/investigation content may be sent to the OpenAI/Claude models doing the work; training-opt-out and context-minimization prerequisites are removed. Credentials and unrelated external disclosure remain out of scope.
- Private CV/profile/person/opportunity/dossier/cache/assessment/application/outreach data never enter Git. Local roots and/or private Drive hold them.
- Web research and computers-off weekly automation are requirements. Particular Codex Cloud environments are optional evaluated routes, not prerequisites.
- Incremental spend is $0. Only verified free allowances and existing authorized subscriptions may be used; no auto-top-up or paid API inference.

## Capability and research handoffs

Readiness records identify surface, client/version, timestamp, workflow/config versions, operation, state (passed/failed/blocked/not-tested/not-applicable), evidence, limitation and next action. SDK imports, listings or documentation alone cannot mark authenticated operation passed.

Research handoffs privately identify institution/run/profile/query IDs and versions, base/proposed revision, authority/owner, work queue/cursors, coverage/gaps/conflicts, validation, costs/health and artifact hashes. Public review summaries use synthetic/sanitized development evidence.

Desktop apps use configured private filesystem roots. Web sessions use a verified private cloud transport and cannot assume access to offline local files. Generated packages/resources preserve the same procedure versions on every surface. A blocked client mode is not hidden behind another client's successful run.

## Planning closure

Claude's supplied 25 October response accepts the reconciled C-01–C-19 decisions and says planning can close. The owner asked for finalization with desktop/web portability. ChatGPT has consolidated those decisions into Plan v2 and the I-series roadmap. This closes architecture planning; it does not claim Claude independently reviewed this final documentation SHA.

The next component is AOIS-I01 tool/runtime readiness. Read [the closure record](PLANNING_CLOSURE_2026-10-25.md), [Plan v2](../architecture/implementation-plan-v2.md), [the roadmap](../ROADMAP.md) and [the task prompt](../tasks/AOIS-I01-tool-readiness.md). Capability tests and each future implementation retain review gates.
