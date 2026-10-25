# AOIS feature and requirement coverage

Finalized 25 October 2026. Runtime features remain **planned, not implemented**. Current task IDs refer to [the I-series roadmap](ROADMAP.md); architecture references refer to [Implementation Plan v2](architecture/implementation-plan-v2.md). Historical baseline/source mappings remain in Git history.

This matrix preserves F01–F50 and adds the owner's finalized requirements F51–F58. Acceptance targets are not achieved results. Real investigation outputs are private local/Drive records, never public Git exports.

| ID | Required behavior | Baseline / component | Tasks | Verification target |
| --- | --- | --- | --- | --- |
| F01 | Reusable users with private CV/summary, goals and keywords | v2 §4 | I03,I05,I21 | Self-reported facts and aspirations distinguished; no hard-coded applicant |
| F02 | Optional CV; broad discovery works before eligibility/profile | v2 §4 | I05,I13,I16 | Missing CV does not remove researchers; personalized claims remain pending |
| F03 | Related keywords, concepts, aliases and search sentences | v2 §4 | I04,I07 | Broader/narrower/related/method/application expansions, rationale and resumable frontier |
| F04 | Local language, spelling, transliteration, ambiguous acronyms | v2 §4 | I04,I06,I07 | Original text retained; full terms/context; translations flagged |
| F05 | Broad AI/CV/agents and geospatial discovery remain independent | v2 §4 | I04,I07,I13 | Researcher need not use all seed topics |
| F06 | All original GeoAI/EO/SAR/InSAR/LiDAR/GIS/photogrammetry/SfM/3D/geodesy fields | v2 §4 | I04 | Explicit concept coverage and adjacent methods/applications |
| F07 | Robotics/SLAM/autonomy, environment/hydrology/forestry/agriculture, urban/transport/twins | v2 §4 | I04,I12,I13 | Unexpected relevant units recovered |
| F08 | Other disciplines and applicant levels | v2 §4 | I04,I18,I19.n,I30 | Synthetic non-geospatial fixture; field norms not universalized; scope qualified |
| F09 | Institution identity, campuses, affiliates, joint centres | v2 §1 | I03,I12 | Graph relationships; rename/merge cases; confirmed university boundary |
| F10 | Screen every mapped top-level unit and uncertain branch | v2 §1 | I12,I15 | Theme-based decisions, source/pagination/language coverage, gap ledger |
| F11 | Multiple people channels and independent reconciliation | v2 §6 | I13,I15 | Directory/lab/portal/project/scholarly/news discrepancies investigated |
| F12 | Retain weak/no-vacancy/unknown-funded/sparse/new researchers | v2 §1 | I13,I17–I18 | No top-N, rank, citation, ORCID or vacancy discovery filter |
| F13 | Roles, current/former affiliations, supervision separately | v2 §5 | I03,I13,I19.n | Publication affiliation never substitutes for current employment/capacity |
| F14 | Discovery before ranking; raw inventory preserved | v2 §1 | I13,I15,I16 | Scored view never deletes or truncates discoveries |
| F15 | PhD/direct/integrated/industrial/joint/network routes | v2 §1 | I04,I06,I14 | Family/source checks and distinct degree/employment conditions |
| F16 | Research Master's, MRes/MPhil, funded thesis/placement | v2 §1 | I04,I06,I14 | Independent branch, not leftover PhD search |
| F17 | RA/GRA, scientific/project/predoc/research engineering roles | v2 §1 | I04,I14 | Original local titles retained and context verified |
| F18 | Teaching/research/combined assistantships | v2 §1 | I04,I06,I14 | TA/RA and tuition-remission cases preserved |
| F19 | Scholarship/fellowship/bursary/waiver/remission/fee differential | v2 §1 | I04,I06,I14 | Fees, living support and duration separated |
| F20 | Internship/summer/visiting/exchange/host/collaboration routes | v2 §1 | I04,I14 | Project-host signal not mislabeled open recruitment |
| F21 | Unfunded/part-funded and later-career intelligence retained | v2 §1 | I14,I21 | Preference/eligibility affects private action views, not source deletion |
| F22 | Historical PhD/RA/Master's calls, recurring cycles | v2 §5 | I14,I15 | Expired/current separated; event time versus first observation |
| F23 | Grants/projects, completed projects, supervision/thesis/appointments | v2 §5 | I13,I14,I19.n | Factual signal and future hypothesis separate; no grant-to-vacancy leap |
| F24 | Targeted archives/disappeared recruitment pages | v2 §6 | I14 | Original URL/capture/effective dates, access limits, no archive sweep |
| F25 | Degree, admission, funding and application how-to | v2 §5 | I14,I08,I23 | Programme/call authority; separate processes and prerequisites |
| F26 | Cycles, rolling/recurring/reopened, dates/timezones | v2 §5 | I03,I14,I23 | Date-only and unknown timezone not fabricated; multi-deadline cases |
| F27 | Original funding currency, gross/net, share, duration, fees/living | v2 §5 | I03,I14,I21 | Unknowns remain unknown; no guessed remaining PI balance |
| F28 | Claim-level evidence, contradiction and source lineage | v2 §5 | I03,I15 | Supporting/refuting passages, URLs/dates/read depth; mirrors not independent |
| F29 | Reversible identity; same-name/moves/multiple roles | v2 §5 | I03,I02,I19.n | No name/email-only merge; split/undo; downstream invalidation |
| F30 | Honest mapped-scope completeness and denominators | v2 §7 | I08,I12,I15 | Failed branches retained; gap label qualified; count not proof |
| F31 | Durable checkpoints/revisions/cursors/resumption/restore | v2 §3 | I02,I10,I16,I18 | Interrupted save, stale write, version mismatch, idempotent replay |
| F32 | Profile/run isolation and version-correct assessments | v2 §3 | I03,I02,I18 | Two-user/profile mismatch and changed-goal cases |
| F33 | Private JSON master plus generated HTML/CSV dossier | v2 §7 | I08,I10 | No real findings in Git; views share source revision and safe escaping/formulas |
| F34 | Separate fit/opportunity/history/eligibility/funding/urgency/confidence/readiness | v2 §5 | I08,I16,I21 | Unknown not zero; no global probability/score |
| F35 | Selected deep dives, paper versions/corrections/read depth | v2 §8 | I20 | No abstract-as-full-reading; authorship verified; no whole-corpus default |
| F36 | Personalized outreach drafts, true anchors, recipient/attachment/history | v2 §8 | I22 | Zero unsupported claims; no invented email or capacity; explicit send gate |
| F37 | Replies/follow-ups/suppression and contact deduplication | v2 §8 | I22,I23 | Private history; nonresponse not rejection; no automatic send |
| F38 | Application/deadline/document/referee/interview/outcome tracking | v2 §8 | I23 | Linked process state and receipt; external submit/contact authorization |
| F39 | Weekly known-page monitoring plus new-URL discovery | v2 §8 | I26–I28 | One scheduler, successful baseline, limited scope and activation |
| F40 | Meaningful change events, no-change health, retry/dedup/last-good state | v2 §8 | I26–I28 | Replay cosmetic/403/empty/new/reopened/deadline/failed-save cases |
| F41 | Four desktop/web surfaces with fresh-session continuity | v2 §2 | I01,I10–I11,I18 | Actual per-surface resource/tools/Drive save/restore; computers-off web execution |
| F42 | Codex/ChatGPT/Claude single-source skill distribution | v2 §2 | I11,I30 | Exact supported-surface matrix, generated adapters/resources, no divergent copies |
| F43 | Onboarding, own credentials/tools, update/uninstall and license/notices | v2 §9 | I11,I30 | Clean-user run, no maintainer accounts, pinned releases and rights review |
| F44 | Responsible access, secrets, injection and authorized model context | v2 §4 | I01,I03 onward | Source bounds, no bypass, no secrets/Git findings; no training-opt-out/context-minimization prerequisite |
| F45 | Budgets, pagination, source health, cost and fallback | v2 §6 | I01,I02,I06 onward | Finite tranches; no silent coverage shrink; typed failures; current provider limits |
| F46 | Independent dated fixtures, held-out recall, no answer-list leakage | v2 §7 | I03,I12–I18 | Denominators/time/uncertainty; same-model rerun not independent proof |
| F47 | Demand-driven scholarly/funder enrichment | v2 §6 | I13,I19.n | Measured incremental recall; existing integration before custom adapter |
| F48 | Conditional database/service and authority cutover | v2 §3 | I24–I25.n | Concurrency/transaction need; least privilege; backup/restore; no dual masters |
| F49 | Wider institution/network/career intelligence | v2 §9 | I31.n | Evidence-backed benefit and sustainable cost; no unsupported prediction |
| F50 | ChatGPT/Claude/user governance and concrete revision review | v2 §9 | Every task | Independent finding/disposition records; material blockers fixed; user final authority |

| F51 | AGENTS only; no CLAUDE.md or CLAUDE.local.md | v2 §2 | I01,I11 | Direct Claude support observed; generated skill discovery is separate |
| F52 | Field vocabularies and no embeddings/similarity feature at any phase | v2 §4 | I04,I07 and all later | No vector/semantic-search/matching dependency or later reintroduction |
| F53 | Polished self-contained HTML and CSV in first usable prototype | v2 §7 | I08–I09 | Summary, sortable/filterable tables, coverage/gaps/evidence, offline assets, safe text/links/formulas |
| F54 | Owner-authorized OpenAI/Claude CV and investigation context | v2 §4 | I05 and all research | No training-opt-out/context-minimization prerequisite; credentials remain outside context |
| F55 | Cloud weekly checks with both local machines off | v2 §8 | I01,I27–I28 | Cloud instructions/baselines/storage/tools and one scheduler actually tested |
| F56 | Later explicitly enabled messenger/email opportunity alerts | v2 §8 | I29.n | Concrete destination, event keys, replay/retry dedup; default disabled |
| F57 | Early repeatable doctor and four-surface capability matrix | v2 §9 | I01 | Evidence/version/time per cell; no unobserved pass; private actual results |
| F58 | One writable authority, explicit local/Drive handoff, append-only watch runs | v2 §3 | I02,I10,I26 | Frozen source, verified destination, epoch/revision checks; no timeout-only takeover or blind sync |

The original architecture's broader bibliographic providers, funding landscapes, responsible access, monitoring, outreach and application requirements remain represented in Plan v2 and this matrix. Adding a named provider is conditional on active need, access and measured value; feature preservation does not require implementing every API.

The maintainer pilot and public synthetic fixtures must be separate. A public table may contain aggregate evaluation results only after privacy and redistribution review; it must not expose a real applicant's assessment.
