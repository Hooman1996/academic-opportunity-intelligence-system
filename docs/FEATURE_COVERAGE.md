# AOIS feature and requirement coverage

Date: 24 October 2026. All runtime features below are **planned, not implemented** at the inspected baseline. The current change supplies documentation only. Task numbers refer to [the roadmap](ROADMAP.md); “v1 §” refers to [the detailed blueprint](architecture/implementation-blueprint-v1.md).

This matrix preserves earlier requirements while adding reusable candidate-driven workflows. A task's future acceptance evidence is not an achieved result.

| ID | Required behavior | Baseline / component | Tasks | Verification target |
| --- | --- | --- | --- | --- |
| F01 | Reusable users with private CV/summary, goals and keywords | v1 §§12,32; generalized private intake | 03A,04,05A,26 | Self-reported facts and aspirations distinguished; no hard-coded applicant |
| F02 | Optional CV; broad discovery works before eligibility/profile | v1 §§12,17; orchestrator | 05A,09,12 | Missing CV does not remove researchers; personalized claims remain pending |
| F03 | Related keywords, concepts, aliases and search sentences | v1 §13; explicit query ledger | 03,05B | Broader/narrower/related/method/application expansions, rationale and resumable frontier |
| F04 | Local language, spelling, transliteration, ambiguous acronyms | v1 §§13–14,21 | 03,07,05B | Original text retained; full terms/context; translations flagged |
| F05 | Broad AI/CV/agents and geospatial discovery remain independent | v1 §13; field packs | 03,05B,09 | Researcher need not use all seed topics |
| F06 | All original GeoAI/EO/SAR/InSAR/LiDAR/GIS/photogrammetry/SfM/3D/geodesy fields | v1 §13; initial technical pack | 03 | Explicit concept coverage and adjacent methods/applications |
| F07 | Robotics/SLAM/autonomy, environment/hydrology/forestry/agriculture, urban/transport/twins | v1 §13 | 03,08,09 | Unexpected relevant units recovered |
| F08 | Other disciplines and applicant levels | General-purpose extension | 03A,23–25 | Synthetic non-geospatial fixture; field norms not universalized; scope qualified |
| F09 | Institution identity, campuses, affiliates, joint centres | v1 §§9,11,16 | 04,08 | Graph relationships; rename/merge cases; confirmed university boundary |
| F10 | Screen every mapped top-level unit and uncertain branch | v1 §§16–17 | 08,11 | Theme-based decisions, source/pagination/language coverage, gap ledger |
| F11 | Multiple people channels and independent reconciliation | v1 §§17,21–22 | 09,11 | Directory/lab/portal/project/scholarly/news discrepancies investigated |
| F12 | Retain weak/no-vacancy/unknown-funded/sparse/new researchers | v1 §17 | 09,14–16 | No top-N, rank, citation, ORCID or vacancy discovery filter |
| F13 | Roles, current/former affiliations, supervision separately | v1 §§9,11,17 | 04,09,17 | Publication affiliation never substitutes for current employment/capacity |
| F14 | Discovery before ranking; raw inventory preserved | v1 §§6,19 | 09,11,12 | Scored view never deletes or truncates discoveries |
| F15 | PhD/direct/integrated/industrial/joint/network routes | v1 §15 | 03,07,10 | Family/source checks and distinct degree/employment conditions |
| F16 | Research Master's, MRes/MPhil, funded thesis/placement | v1 §15 | 03,07,10 | Independent branch, not leftover PhD search |
| F17 | RA/GRA, scientific/project/predoc/research engineering roles | v1 §15 | 03,10 | Original local titles retained and context verified |
| F18 | Teaching/research/combined assistantships | Explicit taxonomy clarification | 03,07,10 | TA/RA and tuition-remission cases preserved |
| F19 | Scholarship/fellowship/bursary/waiver/remission/fee differential | v1 §§15,20 | 03,07,10 | Fees, living support and duration separated |
| F20 | Internship/summer/visiting/exchange/host/collaboration routes | v1 §15 | 03,10 | Project-host signal not mislabeled open recruitment |
| F21 | Unfunded/part-funded and later-career intelligence retained | v1 §§15,19 | 10,26 | Preference/eligibility affects private action views, not source deletion |
| F22 | Historical PhD/RA/Master's calls, recurring cycles | v1 §18 | 10,11 | Expired/current separated; event time versus first observation |
| F23 | Grants/projects, completed projects, supervision/thesis/appointments | v1 §§9,18,20 | 09,10,21 | Factual signal and future hypothesis separate; no grant-to-vacancy leap |
| F24 | Targeted archives/disappeared recruitment pages | v1 §§18,21 | 10 | Original URL/capture/effective dates, access limits, no archive sweep |
| F25 | Degree, admission, funding and application how-to | v1 §§15,26,31 | 10,06,28 | Programme/call authority; separate processes and prerequisites |
| F26 | Cycles, rolling/recurring/reopened, dates/timezones | v1 §§10,15 | 04,10,28 | Date-only and unknown timezone not fabricated; multi-deadline cases |
| F27 | Original funding currency, gross/net, share, duration, fees/living | v1 §§15,19 | 04,10,26 | Unknowns remain unknown; no guessed remaining PI balance |
| F28 | Claim-level evidence, contradiction and source lineage | v1 §10 | 04,11 | Supporting/refuting passages, URLs/dates/read depth; mirrors not independent |
| F29 | Reversible identity; same-name/moves/multiple roles | v1 §11 | 04,05,17 | No name/email-only merge; split/undo; downstream invalidation |
| F30 | Honest mapped-scope completeness and denominators | v1 §16 | 06,08,11 | Failed branches retained; gap label qualified; count not proof |
| F31 | Durable checkpoints/revisions/cursors/resumption/restore | v1 §24 | 05,12,15 | Interrupted save, stale write, version mismatch, idempotent replay |
| F32 | Profile/run isolation and version-correct assessments | General-purpose extension | 03A,04,05,15 | Two-user/profile mismatch and changed-goal cases |
| F33 | Public-safe data and private detailed reports | v1 §§8,26,32 | 06 | Whitelisting, no CV/query-intent/contact/private-assessment leakage |
| F34 | Separate fit/opportunity/history/eligibility/funding/urgency/confidence/readiness | v1 §19 | 06,12,26 | Unknown not zero; no global probability/score |
| F35 | Selected deep dives, paper versions/corrections/read depth | v1 §§5,20 | 22 | No abstract-as-full-reading; authorship verified; no whole-corpus default |
| F36 | Personalized outreach drafts, true anchors, recipient/attachment/history | v1 §30 | 27 | Zero unsupported claims; no invented email or capacity; explicit send gate |
| F37 | Replies/follow-ups/suppression and contact deduplication | v1 §§30–31 | 27–28, later bounded extension | Private history; nonresponse not rejection; no automatic send |
| F38 | Application/deadline/document/referee/interview/outcome tracking | v1 §31 | 28 | Linked process state and receipt; external submit/contact authorization |
| F39 | Weekly known-page monitoring plus new-URL discovery | v1 §29 | 32–34 | One scheduler, successful baseline, limited scope and activation |
| F40 | Semantic events, no-change health, failure/retry/dedup/last-good state | v1 §§29,34 | 32–34 | Replay cosmetic/403/empty/new/reopened/deadline/failed-save cases |
| F41 | Cross-device Ubuntu/Windows continuity without Windows online | v1 §§25,28 | 02,05,12,15 | Fresh chats and actual storage/runtime test; Codex Cloud excluded |
| F42 | Codex/ChatGPT/Claude single-source skill distribution | v1 §28 + extension | 24–25 | Exact supported-surface matrix, generated adapters/resources, no divergent copies |
| F43 | Onboarding, own credentials/tools, update/uninstall and license/notices | Distribution extension | 24–25 | Clean-user run, no maintainer accounts, pinned releases and rights review |
| F44 | Responsible crawling, secrets, injection and data minimization | v1 §§21,32 | 01,04 onward | Domain/path caps, no access-control bypass, safe logs and synthetic fixtures |
| F45 | Budgets, pagination, source health, cost and fallback | v1 §§20–22,33–34 | 02,05,07 onward | Finite tranches; no silent coverage shrink; typed failures; current provider limits |
| F46 | Independent dated fixtures, held-out recall, no answer-list leakage | v1 §23 | 04,08–16 | Denominators/time/uncertainty; same-model rerun not independent proof |
| F47 | Demand-driven scholarly/funder enrichment | v1 §§20,35 | 17–23 | Measured incremental recall; existing integration before custom adapter |
| F48 | Conditional database/service and authority cutover | v1 §4 | 29–31 | Concurrency/transaction need; least privilege; backup/restore; no dual masters |
| F49 | Wider institution/network/career intelligence | v1 §§3,35 | 35 | Evidence-backed benefit and sustainable cost; no unsupported prediction |
| F50 | ChatGPT/Claude/user governance and concrete revision review | Updated shared protocol | Every task | Independent finding/disposition records; material blockers fixed; user final authority |

The original architecture's broader bibliographic providers, funding landscapes, responsible access, monitoring, outreach and application requirements remain represented in the detailed baseline and this matrix. Adding a named provider is conditional on active need, access and measured value; feature preservation does not require implementing every API.

The maintainer pilot and public synthetic fixtures must be separate. A public table may contain aggregate evaluation results only after privacy and redistribution review; it must not expose a real applicant's assessment.
