# AOIS Implementation Plan v2 — finalized baseline

Finalized: 25 October 2026. Planning status: APPROVED by the ChatGPT manager after reconciling Claude's supplied agreement and the owner's requirements. Production implementation: not started. The final documentation commit is a consolidation of the agreed design; it is not represented as independently reviewed by Claude at that exact SHA.

This plan, the current charter, roadmap, feature matrix, AGENTS.md and operating protocol supersede conflicting earlier plans. All 40 Blueprint v1 sections are retained in docs/archive for traceability. Planning closure does not authorize every future task.

## 1. Product and non-negotiable scope

Build the complete private academic intelligence workbench and reusable skills for other applicants. Inputs are a university, private CV/background, keywords/interests, target routes and preferences. The maintainer's private case is the first real pilot, not a production persona. Other users bring their own stores, credentials and goals.

Discovery and ranking are separate; researcher discovery and vacancy discovery are separate. Retain plausible and uncertain researchers, including weak fit, no opening, unknown funding, sparse publications, unexpected units, junior/emeritus/affiliate roles and supervision authority that remains unknown.

Map the institution as a graph. Screen all mapped top-level units; traverse relevant/uncertain departments, institutes, centres, groups, labs, programmes, doctoral schools, campuses, affiliates and joint units. Reconcile official structures, CRIS portals, directories, project teams, theses/news, scholarly affiliations and external/local-language searches. No single provider, researcher count or sitemap proves completeness.

Keep current calls, programmes/cycles, grants/projects, historical recruitment, supervision/theses and future hypotheses distinct. Cover PhD/direct/integrated/industrial/collaborative/joint/network routes; research Master's/MRes/MPhil and funded thesis work; RA/GRA/scientific/project/research-engineering roles; TA/RA/combined graduate assistantships; scholarships/fellowships/bursaries/fee waivers/remission; internships, visiting, exchange, host and appropriate research-career routes. Retain unfunded/partial routes and later-career intelligence with eligibility clearly qualified.

## 2. Four required execution surfaces

| Surface | Instructions/procedures | Expected persistence | Readiness evidence |
| --- | --- | --- | --- |
| Codex desktop | AGENTS.md and canonical .agents/skills when implemented | Configured private local root; optional Drive handoff | Installed client/version, instruction discovery, runtime, tools and private save/restore |
| Claude Code desktop | Direct AGENTS.md support; generated .claude/skills | Same local bundle format; optional Drive handoff | Installed version/settings, actual instruction/skill load and same checks |
| ChatGPT web, including Work | Pinned procedures/resources or supported private plugin package | Private Google Drive bundles; session scratch is temporary | Actual resource load, available tools, create/reload/hash/restore and fresh-chat resume |
| Claude web | Account-enabled procedures/skills and code execution where supported | Private Google Drive bundles; session scratch is temporary | Account/client capability, tools, save/reload/restore and fresh-chat resume |

AGENTS.md is the only repository-level agent instruction file. No CLAUDE.md or CLAUDE.local.md. If the installed Claude version/settings do not load AGENTS directly, report the compatibility issue and upgrade/configure the supported client; do not add an instruction workaround contrary to the owner rule.

Keep one skill source in .agents/skills. Generate supported Claude and web distributions with hashes and bundled shared resources; generated copies are not edited independently. No symlink or Windows-only hook dependency. Record the exact version/resource manifest for every investigation. A pinned manually loaded procedure bundle is an honest initial execution mode, not proof of automatic skill activation.

A web UI cannot assume access to an offline local folder. Interactive web execution and cloud scheduled execution require accessible private cloud state. A desktop relay requires its host online and cannot satisfy the computers-off gate.

ChatGPT Work web is not the same as a repository-backed Codex Cloud environment. Specific Codex Cloud environments are optional candidates only if a measured capability need justifies them; no environment, paid API account or hosted service is required or provisioned by this plan. Web research itself is an explicit product requirement.

Full product readiness requires a small equivalent investigation and cross-session restore on all four surfaces. Local development may advance while another surface remains not-tested, but the product cannot claim four-surface completion until those tests pass.

## 3. Private storage, authority and handoff

GitHub holds code, instructions, skill source, field/country/source definitions, schemas, synthetic fixtures/tests, evaluation definitions, public-safe development reports and release artifacts. It holds no real CV/profile, person-level researcher inventory, applicant's opportunities, dossier, evidence cache, private assessment, correspondence or application state. Do not publish raw reviewer attachments that may contain credentials or personal details.

Private local example categories: profiles/<profile-id>, institutions/<internal-id>, runs/<run-id>, watch/<watch-id>, exports and backups. The private root is outside the checkout and configured per machine; actual paths/account/file IDs stay in private client configuration. Use stable internal IDs; ROR is an optional evidenced mapping, not a required folder identity.

Private Google Drive is the first cloud-store candidate for web runs and unattended watches. Test folder/file access and exact usable bundle fidelity; a connector's search ability or ability to edit Google Docs does not prove JSON/HTML/checkpoint upload and reload. Do not auto-convert canonical files into Google document formats.

A bundle includes profile/run/institution IDs, schema/data/workflow/field/country/policy versions, base revision, owner/session and authority epoch, work queue/cursors, claim/evidence records, budgets/health and artifact hashes. It contains no credentials. JSON is the structured master; HTML/CSV/XLSX are reproducible views. Restricted snapshots remain private with retention/rights metadata.

For each institution, record one active writable authority: local or Drive. Other locations hold frozen copies/proposals, never competing mutable masters. Initial transport uses explicit checkpoint export/import and ownership handoff:

1. Current owner completes an atomic checkpoint and records revision/hash and completed/remaining work.
2. Persist and verify the transfer bundle in the destination store.
3. Record the destination owner/surface and a new authority epoch; freeze the source writer before destination writes.
4. Destination verifies hash, versions, baseline and ownership; it refuses stale proposals instead of overwriting.
5. Return handoffs follow the same procedure. Reuse a verified accepted baseline and refresh stale claims.

Local mutual exclusion uses a tested deterministic lock primitive, atomic replacement and expected-revision checks. Timeout alone never authorizes takeover. Verify the original writer has stopped or use a storage-enforced fencing protocol before recovery. Do not rely on advisory instructions as proof against concurrent writers.

Drive/file transport may lack transactional compare-and-swap. Use a tested serialized owner protocol and unique immutable revision bundles; do not claim distributed locking it does not enforce. If overlapping writers become necessary, stop and review a narrow service/transactional store.

Cloud watch runs use unique append-only run IDs beneath their watch/run area, reading a frozen institution baseline. They do not mutate a local investigation, take over its ownership, or maintain a conflicting copy of its current revision. Comparison baselines live in the approved cloud watch state. Accepted watch findings are imported through a revision-checked proposal/handoff.

Local backups are versioned, encrypted where supported and stored off the source disk. Drive copies are not a substitute for a restore test. Test corrupted/interrupted save and restoration from the last successful revision. No live synchronized SQLite or blind local/Drive two-way folder sync.

## 4. CV use, field vocabulary and privacy

The owner permits CV and investigation content to be sent to the OpenAI and Claude models performing the work. Do not require training opt-outs, a local LLM or minimizing model context before a run. This permission does not authorize secrets in context, public publication, sending raw documents to unrelated services, professor outreach or application submission.

Private intake keeps document/version/page provenance, self-reported versus corroborated facts, original strings, dates, publication/language status and missingness. Interests can be aspirational and need not appear in the CV. Individualized eligibility, funding sufficiency and claims about experience require approved facts; broad discovery can run without a CV.

Use field packs with exact aliases, broader/narrower/related concepts, methods, modalities, applications, research locations, original-language labels and query families. OpenAlex topics, Wikidata labels, ESCO and other reviewed vocabularies can help author proposals. Routine run-local query expansions retain their rationale without a human approval ceremony; canonical vocabulary changes go through review.

No embedding pipeline, vector database, vector/semantic similarity scoring, embedding-based identity/researcher matching or semantic-search feature is planned at any stage. LLM interpretation of inspected evidence and ordinary text/topic/identifier search remain available. A provider's opaque internal ranking is not an AOIS embedding implementation.

The initial technical pack retains AI/ML/deep learning, CV/image analysis, LLMs/RAG/agents/tool use/evaluation, GeoAI/GIScience/GIS/geoinformatics/geomatics/spatial data science, EO/remote sensing/SAR/InSAR/multi- and hyperspectral/thermal imagery, LiDAR/point clouds, photogrammetry/SfM/3D geometry/reconstruction, geodesy/GNSS/surveying/mapping, robotics/SLAM/autonomy, environmental/climate/hydrology/forestry/agriculture, urban/transport/mobility/smart cities/digital twins and meaningful adjacent work. AI/CV/agents and spatial/EO are independent discovery branches, not mandatory keyword conjunctions.

Queries sent to search/retrieval providers are short task-appropriate phrases or identifiers. Record seed, relation, source/rationale, language, query family, results and remaining frontier. Budget exhaustion checkpoints the frontier and leaves coverage partial.

## 5. Evidence, identity, time and comparison contracts

Use stable institution/unit/person/role/output/project/grant/programme/opportunity/cycle/source/observation/claim/evidence/history/coverage/run/identity-decision concepts with explicit relationships. Every MVP concept needs a serialization and validation mapping, whether embedded or stored separately.

Claims have typed subject/predicate/value, supporting/refuting evidence, verification/confidence, effective time, observation/verification dates and contradictions. Important facts need inspected passages, original/resolved URLs, source authority, language/fidelity/read depth and workflow/extractor versions. Snippets are leads. Actionable calls, deadlines, rules and support need original issuer/delegated official evidence.

Add stated-availability claim types: accepting/not accepting specified student/role routes, join-us wording and recruitment conditions. Preserve the exact statement, date, route scope and uncertainty. Student/team lists are activity evidence, not proof of remaining supervision capacity or money.

Identity resolution is non-destructive and reversible. Provider IDs/author clusters are mappings requiring evidence; names/email alone do not justify merges. Separate current/former/multiple affiliations. A conflicting ORCID or move is reviewed; it never rewrites old grants/publications.

Preserve event, publication, capture, retrieval and first-observed time. Programmes and annual cycles differ. Rolling/recurring are attributes; reopened is a change event. Keep date-only values and unknown timezones. Funding records preserve amount/currency/period/gross-net/fee basis/duration/benefits/recipient share and unknown components.

Research compatibility, current opportunity evidence, historical potential, eligibility, funding adequacy, urgency, confidence, preferences and readiness remain separate private views. Missing evidence is unknown, not zero. No global admission probability, prestige/citation exclusion, private-personality prediction or grant-to-opening inference.

## 6. Discovery and source strategy

Map official sources and CRIS/portal families explicitly: Pure, Converis, Esploro, VIVO, NVA, relevant repositories/DiVA and institutional research portals. Use only documented/permitted access; source branding does not establish an open API. ROR and sitemaps seed identity/entry points, not complete department or page denominators.

Include scholarly institution-and-topic/text discovery in the MVP, with OpenAlex access tested before it becomes a dependency. Use topic-filter, text-query, institutional and historical passes; a recent-year window is a priority pass, never the edge of the inventory. Extract authors linked to the target institution in the specific work, retain ambiguous leads and verify current roles officially. Supplement sparsely publishing/new people through directories, appointments, teams and ORCID where useful. Do not treat OpenAlex or ORCID as a staff census.

Official degree/HR/lab/project/funder sources and delegated systems such as Jobbnorge, Varbi/ReachMee and institution-linked ATS belong in opportunity checks. Verify delegation, actual call text, attachments, dates and lifecycle; JSON-LD is supporting source content, not sufficient proof of current openness. Aggregators supply leads and corroboration. Targeted archives and thesis/supervision records preserve history.

DART-Europe is closed and is not a live integration. Current NVA/access/funder details are tested for the actual country. Community API clients, Wayback client defaults and example endpoints do not establish provider contracts.

Default stack: available native search/fetch; existing OpenAlex key/account; Firecrawl within verified free allowance; Apify only as an audited bounded fallback. ROR/Crossref/ORCID/DBLP and country sources are added as justified read routes. Semantic Scholar is optional enrichment and never an MVP key dependency. No additional paid account or automatic credit purchase.

Measure per-provider free balances/reset times, requests/credits, host usage/limits, pages, retries and wall time. Hard incremental spend is $0. Included subscriptions/credits remain finite resources. Unknown cost bounds stop the relevant metered action; use a safe alternative or report a gap. Controls and queues are shared across runs.

## 7. First usable output and quality gates

The first usable prototype produces structured JSON, self-contained HTML and CSV together. HTML has a concise summary first, polished readable typography/layout, responsive and keyboard-usable navigation, sortable/filterable researcher and opportunity tables, current versus historical sections, funding/deadline views, coverage/gap/source-health panels and clickable claim evidence.

Bundle CSS and required JavaScript locally in the file; no CDN, analytics, remote fonts, tracker or automatic external fetch. Escape untrusted values, validate link schemes, handle long/multilingual content and prevent CSV formula injection. Counts/labels in every view come from the same master revision. XLSX is a later generated view, never another master.

Coverage labels remain coverage-complete, coverage-complete with unresolved gaps, and partial, for a declared institution/scope/as-of date. The gap label always adds “procedure completed; source coverage remains incomplete.” Queued mandatory work, truncated pagination or unfinished mapping is partial. Failures stay in denominators. Separate accounted-for branches from successful inspections and show map confidence.

Use channel overlap, incremental yield and independent audits as diagnostics. Capture–recapture may be an optional separately reviewed experiment, never a completeness guarantee or release gate.

Develop a small end-to-end prototype early using pinned manual procedures where production skills are not yet ready. It can be honestly partial. Then harden contracts/modules from observed failures and run two audited institutional pilots, held-out known-researcher/history fixtures and different synthetic profiles. Owner-supplied names are optional; expected answer lists never enter production prompts.

Full release needs traceable fresh actionable calls, no known false merges, all mandatory branches accounted for, profile isolation, restore/handoff, reproducible HTML/CSV, and equivalent bounded runs across all four surfaces. A partial prototype does not establish complete university coverage.

## 8. Weekly cloud runs, applications and notifications

Computers-off automation is a later requirement, not an assumption that desktop scheduling is sufficient. Choose one account-supported cloud scheduler after readiness and monitoring tests. Both ChatGPT scheduled tools and Claude cloud scheduling are candidates; record actual account/tool/auth/storage support, usage and state retention. Do not duplicate ingestion schedules across vendors.

A watch reads cloud-accessible instructions, target definitions and successful baselines, performs known-page and new-URL discovery, compares meaningful academic fields/text, deduplicates by stable entity/cycle/change keys and writes private run/health/event bundles. This uses no embeddings or similarity metric. Failed retrieval cannot replace the last successful baseline or imply a filled call/person departure.

Before activation: bounded target/cadence/free budget/destination; durable cloud save/reload/restore with local machines off; replay cosmetic/reordered/new/reopened/deadline/403/empty/duplicate/interrupted-save cases; three reviewed dry runs; explicit watch authorization.

Later notifications may use Telegram, Slack, WhatsApp or email through a separately approved route. Default is disabled. Require concrete recipient/channel, content scope, explicit activation, event deduplication, retries and no duplicate alert on replay. Do not enable all messengers or contact professors by implication.

Selected deep dives verify authorship/version/corrections/read depth and credible candidate intersections. Outreach preparation produces factual private drafts, verified contacts, attachment versions and history checks; sending/draft creation/follow-up remains explicitly authorized. Applications track linked admissions/employment/funding/supervisor-consent processes, requirements, documents, interviews, receipts and outcomes. A simple sourced deadline/intake view arrives with the early dossier. No legal/immigration/equivalence certainty is invented.

## 9. Implementation and closure

Use one bounded task at a time with exact base, scope, files, exclusions, checks, privacy, acceptance, branch/commits and final evidence. Either local coding agent can implement; the managers review exact revisions independently and the user resolves material disputes. Do not create a merged mega-task or remove review gates for the early prototype.

The previous standalone governance Task 01 proposal is superseded by the finalized documentation and revised I-series roadmap. AOIS-I01 is the first new implementation task: portable doctor diagnostics, synthetic probes, safe local configuration and a four-surface capability matrix. It builds no production investigation skill, collector, schema suite, scheduler or service.

Readiness unknowns are implementation checks, not a reason to reopen completed planning. Report each cell as passed, failed, blocked, not-tested or not-applicable with evidence/date/client version. A local agent cannot certify another web account remotely. Build the shared test protocol first; run it on the other surfaces through explicit user-executed handoffs.

Before public distribution: owner-selected AOIS license, exact upstream notices/dependency review, one source with generated resources, clean install/upgrade/uninstall and trigger/version checks on every claimed surface. The existing-source survey is an evaluation queue, not permission to install or copy everything.
