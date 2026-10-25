> Historical review packet for commit 9dab324. Its original pending statuses and task sequence are historical, not current. See [planning closure](PLANNING_CLOSURE_2026-10-25.md) for the received Claude response and final baseline. The final documentation commit is not claimed to have received independent exact-byte Claude review.

# Review packet: AOIS-PLAN-20261024

Date: 24 October 2026. Objective: share the complete product direction, amended bounded roadmap and sourced reuse research for ChatGPT/Claude review.

## Task envelope and authorization

Repository: Hooman1996/academic-opportunity-intelligence-system.
Expected base: remote main, inspected at 9367b76cde1b9c555d7004c8ec67c8f74fcd8ebe.
Expected planning branch: docs/aois-shared-plan-2026-10-24.

The user asked ChatGPT to inspect the repository, generalize the planned system to other CVs/interests, retain all earlier features, research reusable skills and push descriptions/steps to GitHub for Claude. This authorizes this documentation-only change and review branch/PR, not production implementation.

Permitted scope: README, AGENTS and documentation containing charter, roadmap, feature coverage, adapted baseline, decision, operating protocol, review packet and sourced reuse assessment.

Exclusions: production skills, scripts, schemas, ontology/config, package manifests, providers, crawlers, databases/services, CI, live university research, candidate extraction/eligibility, watches, outreach, account/visibility/permission changes, new paid subscriptions, upstream skill installation and main merge.

Commit expectation: one cohesive documentation commit based on the inspected remote tree. Verify its complete tree and parent, changed paths and branch ref after pushing. No force update. Preserve the original README's mission and core principles in the expanded README. No original repository file is deleted.

## Inspection evidence

At initial inspection:
- Public repository; default branch main.
- main SHA: 9367b76cde1b9c555d7004c8ec67c8f74fcd8ebe.
- Root tree: 9bb8b7cfc6b08f6a7bdbeebbff8add434f6fdff6.
- Only file: README.md, blob c7659f356d361e721a760f0d34ec36d350d42eed.
- Recursive tree response was not truncated.
- Branch list contained main only; open PR list was empty.
- No repository AGENTS, code, tests, workflows, skills or private files existed in that tree.
- Remote main is rechecked immediately before publication; a changed base must be re-inspected, never overwritten.

This is evidence of a documentation-only starting point, not a code/security audit or proof that a local Windows checkout has no changes. Remote connector operations do not touch that checkout.

## Delivered documents

| Path | Purpose |
| --- | --- |
| README.md | Accurate current status and the two intended deliverables |
| AGENTS.md | Concise discovery, privacy, preservation and review invariants |
| docs/PROJECT_CHARTER.md | Full product scope and user workflow |
| docs/ROADMAP.md | All original task IDs, bounded additions and review gates |
| docs/FEATURE_COVERAGE.md | 50 requirements linked to tasks and verification targets |
| docs/architecture/implementation-blueprint-v1.md | All 40 technical baseline sections in publication-safe form, with dated context and clarification header |
| docs/decisions/0001-general-purpose-and-review.md | Why reusable profiles/query planning/packaging and shared review are needed |
| docs/research/EXISTING_SKILLS_REVIEW_2026-10-24.md | Inspected upstream candidates, pinned revisions, licenses and adaptation limits |
| docs/manager/OPERATING_PROTOCOL.md | Task envelope, independent reviews, findings, decisions and owner authority |
| This packet | Scope, inspected baseline, acceptance and independent-review checklist |

The original blueprint's source-byte SHA-256 is d0b6681d5905570c1f0b277c9c589f57269f6e7df6ead2414f04cd05952ea38e. This hash identifies the input bytes; the publication-safe adaptation intentionally differs. Candidate-specific paragraphs and account inventory were removed, and all 40 numbered sections remain. Generic domain/country examples are technical scope, not private preferences.

The upstream report records inspected files and limits. No upstream implementation was imported and no existing skill was evaluated in execution. No candidate CV was copied into this change.

## Acceptance checklist

- User's complete feature intent retained and mapped, including historical and non-PhD routes.
- CV/interests are configurable inputs; expanded queries are auditable; discovery precedes ranking.
- Other users' profiles, storage, credentials, query intent and state stay separate.
- Maintainer remains the private first pilot; no personal facts become public defaults.
- Early intake/query additions are explained and bounded; original task IDs are preserved.
- Codex, ChatGPT and Claude are target surfaces requiring actual compatibility tests.
- Weekly discovery/change checks remain a full product requirement behind existing operational gates.
- Source provenance, identity safety, recovery, evaluation, budgets, safe export, outreach and application boundaries remain intact.
- No functionality, achieved performance, compatibility, independent approval or provider access is fabricated.
- No production component, candidate data or credential is introduced.
- Both reviewers have one exact-revision review protocol; user retains authorization.
- Documentation-only checks are recorded honestly; no meaningless prose unit tests or unnecessary CI is added.

## Checks and evidence

The final delivery report/PR records actual documentation checks: repository diff/scope, all relative links, path/anchor validity where used, Markdown table/fence consistency, whitespace, full blueprint section preservation, coverage rows, original task-ID preservation, candidate/secret-pattern scan, upstream revision/license links, and post-push exact-tree/branch verification.

Pre-publication results: 10 Markdown files, 30 valid relative links, 31 structurally consistent tables, all 40 numbered blueprint sections, F01–F50 in order, and all original 01–35 task IDs plus 03A/05A/05B. No broken relative links, odd code fences, unexpanded authoring markers, flagged private-source strings, credential-like patterns or whitespace errors were found. The 28 external links were recorded; upstream source/license and official reference retrieval were performed selectively, not a blanket live link check. The staged diff and remote publication identity are checked again at delivery.

Checks used a temporary local Git comparison snapshot whose tracked README matched the inspected remote blob. That local snapshot commit is not the upstream base and is never pushed. Publication uses the actual remote parent SHA/tree through the GitHub connector, preserving repository identity and history.

There is no AOIS runtime to test. No upstream skill execution, live university pilot, restore test, account-specific compatibility test, monitoring dry run or eligibility analysis is claimed. Those remain the roadmap's acceptance targets.

## Review status and questions for Claude

ChatGPT: author self-checks and planning recommendation; this is not independent approval.
Claude: PENDING.
Owner merge/publication decision: PENDING.
Production Task 01: NOT ESTABLISHED AS COMPLETE.

Claude should inspect the exact planning branch head and full diff, then answer:

1. Does the extension preserve the original contracts and all feature families?
2. Are early intake/query components necessary, bounded and sequenced without ranking-before-discovery?
3. Could profiles, caches, queries, exports or resumes leak candidate information or carry another person's assumptions?
4. Are query expansion and field packs broad enough while keeping uncertainty and bounded cost?
5. Are semantic claims, historical/current status, supervision and identity handled conservatively?
6. Do the task dependencies/gates avoid skipped capabilities, circular work or oversized coding tasks?
7. Are cross-client paths and packaging explicitly testable rather than presumed?
8. Are upstream findings faithful to the pinned source/license, with no wholesale import or unexpected dependency?
9. Are weekly monitoring, deep dives, outreach and application features preserved without premature activation?
10. Is any material correction needed before Task 01 reconciliation?

Return finding ID, severity, exact path/section, evidence, consequence and minimal correction. Distinguish BLOCKING, NON-BLOCKING and OPTIONAL IMPROVEMENT. Give an overall APPROVED / APPROVED WITH MINOR FOLLOW-UP / CHANGES REQUIRED / BLOCKED verdict against the reviewed SHA.

Do not assume the author can approve on Claude's behalf or that roadmap publication authorizes implementation. Reconcile findings in this planning branch before starting the next component.
