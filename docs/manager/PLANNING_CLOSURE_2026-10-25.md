# AOIS planning closure — 25 October 2026

## Verdict and authority

PLANNING CLOSED — IMPLEMENTATION BASELINE APPROVED.

The owner asked to finalize planning while requiring execution from Codex/Claude desktop apps and the web UI. Claude's supplied 25 October response explicitly accepts the manager's corrected review decisions and says planning can close. ChatGPT accepts that response with the storage/portability clarifications consolidated in Implementation Plan v2.

Claude's response is evidence of agreement on the design, not independent review of this final documentation commit's exact bytes. No implementation, account setup, cloud deployment, scheduled task, notification or main merge is reported as completed.

The review input's SHA-256 is c14f4f331019f26bee635c980d14726134172a1c47cfc28589018b81c5758a3d. The raw attachment is not published; only public-safe design decisions are recorded. The earlier 9dab324 planning commit remains traceable through Git history and the archive.

## Final C-01–C-19 dispositions

| ID | Final disposition | Treatment in current baseline |
| --- | --- | --- |
| C-01 | Accepted protection; no existing CV leak | External private local/Drive storage, no candidate records in Git |
| C-02 | Accepted default policy; no blanket legal determination | All real person-level findings/dossiers remain private |
| C-03 | Accepted with current client clarification and owner override | AGENTS only; direct Claude support must be tested; generated skill discovery; no CLAUDE.md |
| C-04 | Resolved by renewed four-surface requirement | Local and cloud modes both required, with actual save/restore/handoff checks |
| C-05 | Accepted with recall safeguards | Early OpenAlex access; institution/topic, text, institutional and history passes; no topic/year inventory cutoff |
| C-06 | Accepted named-source refinement | Explicit CRIS/portal detection; generic portals were already in scope |
| C-07 | Accepted vocabulary enhancement; owner excludes embeddings | Field packs plus external label/topic proposals and auditable queries; no similarity feature at any phase |
| C-08 | Mandatory estimator rejected; optional experiment only | Channel overlap/yield plus independent audits, no numeric guarantee |
| C-09 | Accepted | Dated route-specific availability statements; student lists are activity, not capacity |
| C-10 | Accepted source refinement; outdated service removed | Thesis/supervision sources remain; DART-Europe closed |
| C-11 | Accepted with delegation/access verification | Official-linked issuer systems and JSON-LD supporting content; no assumed public API |
| C-12 | Accepted concurrency need; unsafe takeover rejected | One writer, atomic saves/revision checks; no timeout-only takeover |
| C-13 | Owner strengthened requirement | HTML plus CSV in first usable output; XLSX later |
| C-14 | Accepted with finite subscription/provider controls | Per-provider free budgets/usage plus host/time/context limits; $0 new spend |
| C-15 | Early prototype accepted; mega-task/review waiver rejected | Bounded I-series components, early partial end-to-end result, both reviewers retained |
| C-16 | Accepted explicit source policy | Permitted/manual routes; no Scholar/LinkedIn scraping dependency |
| C-17 | Accepted lightweight early view | Sourced intake/deadline view in first dossier; full application/calendar tools later |
| C-18 | Accepted; owner names optional | Independently curated held-out sets and no production answer leakage |
| C-19 | Accepted narrowly | Credential/private-path controls and configuration review; no indiscriminate email ban |

Claude accepted the OpenAlex key clarification, DART-Europe correction, PyMuPDF license caution, nonmandatory estimator, corrected locking and finite budgets. The default stack remains native tools + OpenAlex + Firecrawl, with audited Apify fallback and no new paid account.

## Owner requirements now normative

1. No CLAUDE.md or CLAUDE.local.md; AGENTS.md is the sole repository-level instruction file.
2. Field vocabularies; no embeddings/vector similarity/semantic-search feature at any stage.
3. JSON master and polished self-contained HTML/CSV in the first usable prototype.
4. Owner permits CV/research model context in OpenAI/Claude; no training-opt-out/context-minimization prerequisite. Secret handling and no public publication remain.
5. Codex desktop, Claude Code desktop, ChatGPT web and Claude web are all required targets.
6. Private local roots and/or private Drive; one writable authority and explicit verified handoff.
7. Computers-off scheduled cloud investigations remain a gated later feature.
8. Messenger/email notifications later, default disabled and explicitly activated per destination.
9. Early tool-readiness step and repeatable doctor across surfaces; no unsupported capability claims.
10. Reusable skills for other applicants and the maintainer's private pilot remain equally part of the scope.

## Remaining issues are implementation evidence, not planning blockers

Verify exact installed client/settings, free allowances, tools, Drive file/bundle operations, package activation and cloud scheduling in AOIS-I01 and later readiness gates. A desktop cannot claim to have tested another account. A failed capability identifies the next narrow implementation choice; it does not authorize an unplanned database/service.

Cloud watch runs and interactive writers are separated by unique run/proposal areas and ownership. There is no ungoverned Drive/local sync. A local-only scheduler cannot satisfy the computers-off requirement.

## Document and review gate

README, AGENTS, charter, roadmap, feature matrix, Plan v2, Decision 0002 and operating protocol are current. Historical v1 material and the original review packet are labeled non-authoritative history.

The earlier unissued task sequence is mapped to new bounded IDs. The first ready task is [AOIS-I01](../tasks/AOIS-I01-tool-readiness.md). Task authorization occurs when the owner issues that prompt; it does not authorize later tasks.

Future implementation returns exact branch/base/head, tests, privacy/scope review and actual capability evidence for ChatGPT/Claude review. The main branch is not merged automatically by this closure record.

## Documentation checks supporting the platform design

Official documentation inspected on 25 October 2026 describes web workflows and connected storage, but does not establish this owner's account permissions or operational readiness:

- [OpenAI Build skills](https://learn.chatgpt.com/docs/build-skills): local skill discovery and packaged web distribution are different routes.
- [ChatGPT Scheduled tasks](https://learn.chatgpt.com/docs/automations): web tasks use available context/tools and do not retain a local folder/worktree.
- [Claude Google Workspace connectors](https://support.claude.com/en/articles/10166901-use-google-workspace-connectors): file upload and generated-file saves to Drive are documented, with code execution/permissions requirements and limitations.
- [Claude Cowork across web/desktop/mobile](https://support.claude.com/en/articles/15520349-use-claude-cowork-on-web-desktop-and-mobile): cloud execution/scheduling and local Code workflows must be distinguished.

The final documentation checks found 16 Markdown files, 46 valid relative links, 35 structurally consistent tables, all 40 archived blueprint sections, F01–F58 and 31 ordered I-series task slots. No forbidden instruction file, unexpanded authoring marker, flagged private-source string or credential-like pattern was found. Whitespace/staged scope and remote content are checked before delivery. These are documentation checks, not runtime/capability tests.
