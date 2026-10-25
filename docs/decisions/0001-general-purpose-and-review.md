> Historical decision proposal from 24 October 2026. Superseded by [Decision 0002](0002-final-runtime-storage-and-scope.md) and [Plan v2](../architecture/implementation-plan-v2.md), including private findings, four required surfaces and final owner instructions. Original wording below is retained for traceability, not authorization.

# Decision 0001: reusable candidate-driven AOIS and shared review

Date: 24 October 2026. Status: proposed design refinement; user requested direction, ChatGPT author review complete, Claude review pending. No implementation or public release is approved by this record.

## Context

The approved 7 October blueprint emphasized a single candidate's cross-device investigations. The user now explicitly requires the same thorough system to serve other applicants through reusable Codex/ChatGPT/Claude skills, with the maintainer's private workflow as the first pilot. The public repository is the common point for ChatGPT and Claude to review and plan.

Inspection found only README.md at main commit 9367b76cde1b9c555d7004c8ec67c8f74fcd8ebe. No production implementation needs migration. The earlier Task 01 command was issued but is not established as completed by this repository state.

## Decisions proposed

1. Keep discovery, vacancy search, ranking, history, evidence, coverage, resumption and action gates from Blueprint v1.
2. Separate a field-neutral research core, versioned domain/country packs, private candidate profiles and generated client packages.
3. Model each candidate's background, interests and constraints privately, with ownership/versioning and isolated assessment/run state. Shared institutional facts contain no candidate annotations.
4. Add an explicit auditable CV/interest-to-concept/query contract before core configs and a private intake/query workflow before personalized pilots. Candidate-independent discovery remains possible without a CV.
5. Preserve the initial AI/CV/geospatial/LLM/agents pack at full depth, and evaluate other synthetic profiles before claiming broader discipline support. No maintainer facts or country exclusions become defaults.
6. Target portable Agent Skills instructions/resources with thin generated adapters for Codex, ChatGPT and Claude. Client paths, permissions, private distribution and runtime must be tested. Do not require Windows hooks, symlinks or a local MCP for ordinary web research.
7. Use one private installation per user initially; general-purpose use does not require SaaS, concurrent users, a database or extra paid tools. A hosted multi-user service requires its own architecture/access-control gate.
8. Keep GitHub as the shared technical/review authority. ChatGPT and Claude both review substantive changes against exact revisions; the user owns authorization and resolves unresolved material disputes.
9. Put planning changes on a review branch/PR. Leave main unmerged until review; do not pretend that either model has approved another's changes.
10. Evaluate upstream skills as bounded candidates, with pinned revision, exact license, dependencies, security/data-transmission review and AOIS regressions. This planning change vendors or installs nothing.

## Consequences and minimal roadmap changes

Add 03A for generic intake/query contracts before Task 03, 05A for private intake after storage, and 05B for auditable query planning before integrated pilots. Task 26 becomes advanced profile/readiness maintenance; it no longer delays the first verified profile until after MVP. Strengthen Task 04 with ownership and privacy semantics, Tasks 14–16 with candidate-isolation/expansion tests, and Tasks 24–25 with Claude packaging and licensing gates.

Preserve original task IDs and conditional components. No other feature is removed. These are separately authorized tasks after review, not a batch implementation instruction. See the [roadmap](../ROADMAP.md).

Tradeoffs: a slightly larger early contract surface and more privacy/portability tests, in exchange for avoiding a single-person design that must later be rewritten. Limit the added work through synthetic contracts and independent installs, rather than a hosted account system.

## Authority and privacy

Public Git holds approved definitions and deliberately accepted publication-safe institutional exports. Private active runs are versioned proposals against a baseline. Private profiles, raw CVs, searches revealing intent, hypotheses tied to a candidate, rankings, applications and correspondence stay in one designated private store, selected through capability tests. Freeze accepted drafts instead of keeping two mutable masters.

The new plan does not authorize sharing the maintainer's CV with Claude through public Git or any other repository. The owner supplies private documents to an authorized private review context when necessary.

## Approval, revisit and rollback

Claude review must record finding IDs, evidence, proposed changes and disposition. ChatGPT responds against the same revision; material disagreements return to the user. Merge/publication decisions remain explicit. Revisit if client capabilities, privacy constraints, licensing, concurrency or actual pilot cost/recall requires a material change.

Rollback is the documentation diff on the planning branch. No runtime, account, schema, data or service has been changed. The original task sequence remains recoverable in the publication-safe baseline.
