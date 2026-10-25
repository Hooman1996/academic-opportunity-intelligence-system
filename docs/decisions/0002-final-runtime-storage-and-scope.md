# Decision 0002 — finalized runtime, private authority and scope

Date: 25 October 2026. Status: finalized design baseline. Supersedes conflicting parts of Decision 0001, Blueprint v1, the 24 October roadmap and initial manager task prompt.

## Basis and review status

The owner asked to finalize planning and reaffirmed running from Codex/Claude desktop apps and the web UI. Claude's supplied response agrees with the manager's corrected C-01–C-19 decisions and says planning can close. It also conveys owner decisions: no CLAUDE.md, no embeddings, HTML/CSV in the first prototype, authorized model context, local/Drive private data, four required surfaces, computers-off scheduling, later messenger notifications and an early readiness/doctor task.

This commit transcribes that agreed design and resolves handoff/scheduler ambiguity. Claude's supplied agreement is not represented as independent review of this new commit's exact bytes. Future implementation retains both reviewers and owner authority. No main merge or runtime action is implied.

## Decisions

1. Support Codex desktop, Claude Code desktop, ChatGPT web and Claude web. Treat each client/account capability as tested evidence, not shared assumptions.
2. Keep only AGENTS.md as repository-level agent instructions. Do not add CLAUDE.md or CLAUDE.local.md. Require compatible direct-loading Claude settings/version.
3. Author skills once; generate client-specific packages/resources. Manual pinned workflow loading is a temporary declared mode, not proof of installed activation.
4. Exclude embeddings and vector/semantic similarity features from all phases. Field vocabularies and LLM evidence interpretation provide expansion.
5. Private CVs, profiles, researcher/opportunity findings, caches, dossiers and application/outreach state never enter Git. Use external private local roots and/or private Drive.
6. The owner authorizes research/CV context in the OpenAI/Claude models doing the work. No training-opt-out or model-context-minimization prerequisite. Secrets and unrelated external disclosure remain prohibited.
7. Use one writable authority per institution with revisioned checkpoint handoff. No blind local/Drive two-way sync or timeout-only takeover. Cloud watches write their own append-only run areas and read cloud baselines without mutating an active local investigation.
8. Produce self-contained attractive HTML and CSV from JSON in the first usable output; XLSX later. Use safe escaping, links, formula protection and offline assets.
9. Retain cloud scheduled investigations with computers off and future explicitly activated messenger/email notifications. Select one scheduler only after actual-account readiness and monitoring gates.
10. Web execution is allowed. Repository-backed Codex Cloud is optional if needed and separately evaluated, not a blanket prohibition or mandatory dependency.
11. First implementation is AOIS-I01 tool/runtime readiness; later code remains bounded. Keep the early end-to-end prototype, independent pilots, held-out audits and all earlier opportunity/history/research features.
12. Reuse existing accounts/free allowances. No new paid account, paid API inference route, auto-top-up or hosted infrastructure is approved.

## Consequences, tests and revisit conditions

The portability target is stronger than a local-only MVP: require fresh-session restore and an equivalent bounded run across all four surfaces before claiming the full product works everywhere. A desktop can implement/test the doctor and complete its own cells while web cells remain not-tested.

Drive writes, exact supported file types, byte/canonical-record fidelity, provider access and scheduler tool availability must be tested. If a required operation is unavailable, mark the affected mode blocked and propose the smallest compatible route; never pretend file search is write access or silently build a service.

Review a narrow service/transactional store only if actual concurrency or connector limits require it. Any new cost or changed private authority gets a bounded decision with rollback. Account/permission changes remain user-controlled.

The [current plan](../architecture/implementation-plan-v2.md), [roadmap](../ROADMAP.md), [feature matrix](../FEATURE_COVERAGE.md) and [closure record](../manager/PLANNING_CLOSURE_2026-10-25.md) hold the complete normative treatment.
