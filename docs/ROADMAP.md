# AOIS finalized implementation roadmap

Finalized 25 October 2026. Architectural planning is closed under [Implementation Plan v2](architecture/implementation-plan-v2.md) and [Decision 0002](decisions/0002-final-runtime-storage-and-scope.md). Future tasks are not authorized merely by appearing here.

Repository baseline before this consolidation: planning branch docs/aois-shared-plan-2026-10-24 at 9dab324bd5911368e156a8e60262b950918a94e5; main at 9367b76cde1b9c555d7004c8ec67c8f74fcd8ebe. No production AOIS implementation was present. The dated original roadmap remains in [the archive](archive/roadmap-2026-10-24.md).

## Task IDs and execution rule

The old documentation-only Task 01 proposal and the unissued 01–35/03A/05A/05B sequence are superseded. Use the distinct I-series IDs below for actual implementation; the legacy column preserves traceability and prevents issuing an obsolete prompt.

Each I-series task is one reviewable component with its own user authorization, exact base, scope/exclusions, files, meaningful checks, privacy rules, acceptance, branch/commit and result report. Rows that identify optional adapters/packs are templates for one separately numbered child task, never an instruction to implement them all.

The current planning work is documentation only. Start with AOIS-I01, whose [complete task prompt](tasks/AOIS-I01-tool-readiness.md) is ready to paste into either local coding agent after the owner merges the planning PR or explicitly selects its exact head as the task base.

## Ordered implementation steps

| ID | Bounded objective and output | Dependencies | Acceptance gate | Legacy coverage |
| --- | --- | --- | --- | --- |
| AOIS-I01 | Tool/runtime readiness: portable doctor, synthetic probe, four-surface matrix/checklist, public sanitized template and private observed report | Final plan | Local offline checks and tests; actual client/AGENTS discovery; repo/runtime/private-store/provider/scheduler cells with evidence; no fabricated cross-account passes | 01–02,18 access test,24 capability |
| AOIS-I02 | Local foundation: configured external private root, revisioned manifest, atomic save, single-owner locking and restore | I01 local path | Outside-checkout enforcement, interrupted save, stale revision, no timeout-only takeover, off-disk restore; no live CV | 05 foundation |
| AOIS-I03 | Minimal research/run/evidence/identity/availability record contracts and validators | I02 | All MVP concepts mapped; broken references, unknowns, dates/cycles, same-name identities and real-data export boundaries tested | 04,17 baseline |
| AOIS-I04 | Core field vocabulary/query contract and initial technical pack | I03 | All original AI/CV/geospatial/LLM/agent interests; broader/narrower/related/method/application/local-language expansion; no embeddings or hard-coded candidate | 03A,03 |
| AOIS-I05 | Private CV/background intake workflow with factual approval/versioning | I03–I04 | Page/document provenance, self-reported versus corroborated, aspirations, language/publication status; private context permitted; no Git findings | 05A,26 initial |
| AOIS-I06 | Minimal source/country registry and first pilot country pack | I04, needed I01 route checks | CRIS/official directory/delegated HR/degree/funding/history sources, source lineage, pagination/language/access gaps, current free access; one country only | 07 |
| AOIS-I07 | Auditable vocabulary-driven query planner | I04–I06 | Independent topic branches, text/topic/institution/history passes, short queries, rationale, frontier and budget resume; no ranking cutoff | 05B |
| AOIS-I08 | First report generator: JSON to polished self-contained HTML and CSV | I03 | Summary, sortable/filterable tables, current/history/deadline/coverage/gaps/evidence; offline assets, safe HTML/URLs, CSV formulas, multilingual/keyboard/responsive checks | 06,13 human views,17 deadline view |
| AOIS-I09 | Early end-to-end prototype on one small institution using pinned manual procedures and available tools | I02–I08, selected source readiness | Actual bounded map/people/opportunity/history pass; HTML/CSV/coverage/checkpoint; honest partial scope; no code redesign hidden in research run | New early prototype |
| AOIS-I10 | Private Drive bundle transport and explicit local/web handoff | I01 Drive tests,I02–I03; may parallel I04–I09 if needed for web prototype | Canonical-record fidelity/hashes, unique revisions, owner/epoch transfer, stale refusal, frozen source and fresh-chat restore with local computer off | 05 cloud,25/28 portability |
| AOIS-I11 | Canonical skill resource loader and generated local/web packaging mechanism | I01 skill tests,I04,I10 | AGENTS only; .agents source to generated .claude/web package; resource/hash/version equality, manual mode identified; all four surfaces load the same synthetic procedure | 24–25 mechanism |
| AOIS-I12 | Institution-map production skill | I06–I07,I09 findings,I11 | All-top-level screening, hidden/joint/affiliated/renamed units, CRIS detection, themes before outside-scope judgment, pagination/language gaps | 08 |
| AOIS-I13 | Broad researcher-discovery production skill | I12, scholarly readiness | No-vacancy/weak/sparse/new/moved people retained; multi-channel institution/text/topic/history discovery; identity discrepancies; no date/topic filter defines universe | 09,18–19 minimal scholarly route |
| AOIS-I14 | Opportunity and historical-intelligence production skill | I06,I13 | Independent Master's/RA/TA/fee-relief/PhD/short-term/host branches; cycles, attachments, stated availability, archives; grants not calls | 10 |
| AOIS-I15 | Research-audit production skill and independent reference fixtures | I08,I12–I14 | Denominators, hidden/unfinished units, freshness, false-open/identity/claim failures, second pass; expected researcher lists isolated from production | 11,16 fixture baseline |
| AOIS-I16 | Investigation orchestrator over approved procedures | I05,I07–I08,I10–I15 | Correct versions/owner/profile, map/discover/routes/history/audit, budget interruption, restore, private HTML/CSV; no nested-skill API assumption | 12 |
| AOIS-I17 | Pilot A and profile-generalization check | I16, selected pack | Independent institutional/person/history audit and measured usage; real private case plus synthetic alternate; no ranking-selected inventory | 13–14 |
| AOIS-I18 | Pilot B, held-out audit and four-surface investigation release | I17 fixes, needed second pack | Two layouts/languages, dated held-out recall, all four equivalent bounded runs and fresh-session restore; no false-open/known false merge; no completeness claim from partial pilots | 15–16 |
| AOIS-I19.n | One justified scholarly/identity/funder adapter or field/country pack | I18, measured gap | Current access/license/cost, pagination/retry/error tests and incremental verified recall; one adapter/pack per task | 17–21,23 |
| AOIS-I20 | Selected researcher deep-dive skill | I18 | Verified authorship/version/corrections/read depth and truthful candidate connection; no full-career corpus default or capacity inference | 22 |
| AOIS-I21 | Advanced private profile/assessment/readiness maintenance | I18,I05 | New CV/goals supersede without cross-profile leak; evidence-backed separate fit/opportunity/eligibility/funding views | 26 later |
| AOIS-I22 | Outreach-prepare skill and private draft | I20–I21 | Verified recipient/contact, inspected anchors, attachment/history check, zero unsupported facts; no sending/unrequested Gmail draft | 27 |
| AOIS-I23 | Minimal linked application-process tracker and optional XLSX view | I21, selected verified route | Admissions/employment/funding dependencies, document versions, actual receipts, private state; no submission or legal certification | 28 |
| AOIS-I24 | Optional shared-service/storage decision | I18, measured connector/concurrency need | Scope, authority cutover, access/cost, rollback/export/restore; no automatic database/MCP | 29 |
| AOIS-I25.n | One smallest approved service/database component only if required | I24, explicit authorization | Atomic/revision/ownership/access tests, export/restore; narrow tools, no arbitrary SQL/crawl/send | 30–31 |
| AOIS-I26 | Meaningful-change comparator and private event state | I18,I10 | New/reopened/deadline/funding/identity changes; cosmetic/reorder/no-change/403/empty/failure/dedup replays; last-good baseline preserved; no similarity metric | 32 |
| AOIS-I27 | Three reviewed cloud watch dry runs and scheduler selection | I26, cloud scheduler/tool readiness | Cloud state/resources accessible with both computers off, one scheduler, budgets/health/retry/overlap/failed-save tests | 33 |
| AOIS-I28 | One explicitly authorized weekly cloud watch | I27, target/cadence authorization | Known-page plus discovery checks, private Drive run results, healthy no-change report, first-run review before expansion | 34 |
| AOIS-I29.n | One explicitly enabled messenger/email notification route | I28, chosen destination/content authorization | Deterministic event deduplication, failure/retry/replay checks, no duplicate or unintended recipient; default disabled | New alerts extension |
| AOIS-I30 | Tested portable public skill release and onboarding | I18, owner-selected license; later features separately versioned | All claimed surfaces install/load/upgrade/uninstall; private store setup, hashes/resources/notices and synthetic clean-user tests; no implicit access to maintainer data | 24–25 release |
| AOIS-I31.n | One justified wider institution/network/career intelligence component | Core evaluated release, measured benefit | Coverage/value/cost evidence, no unvalidated admission prediction | 35 |

The I09 prototype intentionally precedes complete production skills and can use reviewed manual procedures. It is not a full-coverage release. I10–I11 are early portable plumbing, not something postponed until after claiming the whole system works everywhere.

## Readiness and release gates

- I01 produces the common checker and actual local evidence. Other account cells may remain not-tested with exact follow-up instructions; a local implementer cannot certify a web session it did not observe.
- A web mode is usable only after its resource/tool/private-save checks pass. If no safe Drive write route works, mark that mode blocked and review the smallest compatible transport; do not silently build a service.
- Full investigation release requires two independent pilots and four-surface run/restore evidence. Expected answer lists are held out, never production hints.
- Full distribution additionally requires owner-selected licensing, pinned upstream notices, generated resources, onboarding and actual supported-client tests.
- Cloud weekly operation requires cloud-readable baselines, one scheduler, free limits, three reviewed dry runs and explicit watch activation. Local schedulers are not evidence of computers-off operation.
- Messenger/email notifications and outreach are separate action authorizations; neither follows automatically from a watch or a draft.
- Both managers review substantive components at exact SHAs. The early prototype does not waive reviews. The user owns authorization and resolves material conflicts.

## First implementation task

Use [AOIS-I01-tool-readiness.md](tasks/AOIS-I01-tool-readiness.md). The owner can merge planning PR #1 and use current main, or explicitly base the task on the final planning head. Do not start from the old README-only main while pretending it contains the final plan. No production work has been completed by this planning revision.
