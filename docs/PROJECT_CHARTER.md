# AOIS project charter

Date: 24 October 2026. Status: shared planning proposal for ChatGPT and Claude review. Product direction is user-authorized; individual implementations and release gates are not authorized by this document.

## Purpose and users

Build a professional academic opportunity intelligence workbench and a reusable set of research skills. A person supplies a university, a CV or background summary, optional keywords, research interests, desired routes, and constraints. AOIS expands that starting point into a systematic university investigation and returns evidence-backed researchers, routes, current opportunities, historical signals, and useful next actions.

The maintainer's private profile is the first real acceptance case. Other students and researchers must be able to use the same core with their own data and goals. Initial field content is strongest in AI, vision, remote sensing, spatial science, geometry, robotics, LLMs and agents. Additional disciplines use reviewed field packs; being configurable does not establish tested competence in every discipline.

The complete product retains the earlier architecture's discovery, enrichment, comparison, deep-dive, outreach, application and monitoring scope. Sharing skills is a second delivery form of the same research process. It does not require building a hosted multi-tenant service.

“Complete” means a professional, auditable process with explicit scope, unresolved gaps and preserved evidence. No internet search can certify that every person or opportunity has been found. Coverage-complete is a scope/as-of claim with strict gates, never a marketing guarantee.

## Inputs and private intake

| Input | Treatment |
| --- | --- |
| University name or official URL | Resolve institution identity, campuses, affiliates, aliases and scope |
| CV or background summary | Private extraction with document version/page provenance and user-confirmed facts |
| Keywords, questions and desired directions | Independent seeds; a future interest need not appear as experience in the CV |
| Degree or role goals | PhD, research Master's, RA, assistantship, internship, visiting and other research routes |
| Country, funding, language and timing preferences | Private configuration, never maintainer-specific defaults |
| Existing investigation | Load accepted institutional facts plus the correct private run, profile and query-plan versions |
| Available tools and budget | Capability-tested route, finite tranches, partial saves when limits are reached |

A CV is optional for broad institutional discovery. Private profile approval is required for personalized factual claims and eligibility conclusions. Extracted CV statements remain self-reported unless independently corroborated. Do not infer citizenship, immigration status, degree equivalence, attained language scores or publication status.

Collect only details needed for the chosen route. Default external queries use topical concepts and necessary public institution/person information, not full CV text, contact details or private identifiers. Show meaningful data-transmission choices before a workflow sends sensitive documents to a new service.

Each profile and run has an owner/namespace and version. Profiles, candidate-dependent caches, assessment records, watch definitions, drafts and application state must remain isolated. A second user or an updated CV cannot inherit the first user's private judgments, credentials or conclusions.

## Research expansion without keyword confinement

Build an inspectable query plan from two distinct inputs: demonstrated methods/background and user-directed interests. Keep original labels, evidence, uncertain extraction and aspirations separate.

Expand through:

- exact aliases, spelling variants and original-language equivalents;
- broader and narrower concepts with explicit relationships;
- related methods, sensing modalities, data types, applications and scientific problems;
- equivalent job, degree and funding terminology by country;
- alternative descriptions researchers use for the same scientific connection;
- local-language phrases and multiple sentence/query families;
- evidence-driven new terminology found during the investigation.

For example, computer vision can lead to image analysis, reconstruction, computational imaging, robotics and perception. Remote sensing can lead to EO, radar/SAR/InSAR, spectroscopy, LiDAR, photogrammetry, environmental sensing and spatial modelling. LLMs/agents can lead to retrieval, planning, tool use, evaluation, grounded multimodal systems and embodied intelligence. These are technical examples, not facts about a particular applicant.

Record each expansion's seed, relation, rationale/source, language, query, channel and investigated scope. Search AI/CV and geospatial branches independently; do not require every researcher to use all seed terms. Avoid unqualified acronym queries and rigid conjunctions. Uncertain matches enter the inventory; later comparison can distinguish stronger and weaker connections.

Bound expansion by an explicit policy and review frontier. A budget limit saves the next queries and leaves coverage partial; it never silently removes related people or changes the declared scope. User exclusions change private action views and scoped investigation choices transparently, not shared institutional facts.

## University coverage

Start with an organizational graph, not a Computer Science-only query. Screen every mapped top-level faculty/school by themes and research entry points. Traverse relevant and uncertain departments, institutes, centres, labs, groups, programmes, doctoral schools, platforms, campuses, affiliates and joint units.

Include unexpected locations such as civil/electrical engineering, geography, geomatics, agriculture/forestry, environmental/earth science, physics, mathematics/statistics, urban planning, transport, architecture, health/computational imaging and interdisciplinary AI centres when a meaningful bridge exists. New domain packs define equivalent search locations for other disciplines.

Use complementary discovery channels: official structures, central/unit directories, lab/project teams, research portals, repositories/theses, appointment/news, scholarly affiliations, funder investigators and independent institution/topic searches. A sitemap, scholarly graph or one search provider is never proof of completeness. Record pagination, filters, languages, inaccessible areas and missing years.

Every plausible professor, PI, researcher, research-active lecturer, fellow, substantive postdoc/engineer, adjunct or emeritus connection is retained with role and current/former affiliation. Supervision authority, contact suitability, research relevance and recruitment status are separate claims. No-open-position researchers are first-class findings.

## Opportunity and historical coverage

Cover independent routes and their combinations:

- Salaried, supervisor-led, structured, direct/fast-track, integrated, industrial, collaborative, joint/cotutelle and network doctoral routes.
- Research/thesis Master's, MRes/MPhil, funded thesis or placement, bridge routes and research programmes with partial or no living support.
- RA/GRA, scientific/project assistant, junior/predoc researcher, research engineering/software and appropriate related research roles.
- Teaching assistantships, research assistantships, combined graduate assistantships and tuition remission.
- Scholarships, fellowships, bursaries, full/partial fee waivers, differential-fee support, salary/stipend and mobility/travel/relocation support.
- Internships, summer research, visiting, exchange, traineeship and project/host routes.
- Relevant research-career development and later-career intelligence without assuming candidate eligibility.

Record programmes, recruitment cycles and application processes separately. Preserve admissions, employment, funding, nomination and supervisor-consent dependencies and distinct deadlines. Retain original currencies, duration, fee basis, salary/stipend terms and unknown components; “funded” does not imply affordable.

Historical checks cover expired PhD/RA/Master's calls, grants, project starts/completions, recurring cycles, supervision, theses, appointments and partnerships. Preserve event dates, source/capture dates and first observation. Keep factual events separate from future-opportunity hypotheses. A grant is not a vacancy; history is not present recruitment.

## Evidence, comparison and outputs

Use claim-level passages, URLs, retrieval/publication/event dates, provenance, extraction/read depth, language/fidelity and supporting/refuting evidence. Search snippets are leads. Actionable status, deadlines, eligibility and funding require inspected original issuer or delegated official evidence.

Resolve people with stable internal IDs and evidenced external mappings. Names alone do not establish identity; bibliographic affiliation does not prove current employment. Merges require recorded, reversible decisions, and consequential conflicts block external use.

Discover first; compare afterwards. Keep research compatibility, present opportunity evidence, historical potential, eligibility, funding adequacy, urgency, evidence confidence, preferences and action readiness distinct. No combined admission probability or prestige-based filtering.

The final output set is:

1. A detailed university dossier with scope, organizational map, inventory, current routes, historical signals and cited application guidance.
2. Structured reusable institutional records and claim/evidence relationships.
3. A coverage audit with denominators, successful versus blocked checks, missing branches, mapping confidence and as-of dates.
4. Private candidate-specific comparisons, uncertainties and next actions.
5. A durable private checkpoint with versions, hashes, owner, work queue, cursors, budgets and exact resume context.
6. Public-safe exports when deliberately accepted, plus private human-readable/downloadable views as appropriate.

Public publication is a separate choice. Discovery facts that are public on the web do not automatically authorize bulk redistribution or publishing private search intent.

## Later work retained in full scope

Selected researcher deep dives inspect a small justified paper/project set with authorship, version, corrections and read depth. Outreach uses true candidate evidence, verified recipients and concrete scientific anchors; prepare drafts and attachment checklists first. Gmail draft creation, sending, follow-ups and application submissions require their specific user authorization.

Application planning tracks linked admissions/employment/funding processes, document versions, references, deadlines, interviews, replies and outcomes. Calendar and spreadsheet views are projections, not competing databases. No fabricated legal, immigration, tax or credential-equivalence certainty.

Weekly checks include both known-page comparison and new-URL discovery for calls, deadlines, funding conditions, researchers, labs, grants and relevant history. Persist last successful baselines, semantic before/after evidence, deduplication, source health, costs and no-change run status. Failed extraction cannot replace a successful baseline. One scheduler; reviewed dry runs and explicit activation before live watches.

## Distribution, operation and success

Use a field-neutral core, reviewed domain/country packs and one canonical skill source. Start with file-based single-writer runs and manual pinned workflow bundles. Later build versioned packages, onboarding and client adapters for tested Codex, ChatGPT and Claude surfaces. Expose capabilities and limitations per surface; no universal compatibility claim from SKILL.md alone.

No AOIS hosted service is necessary for independent users. Each installation brings its own approved tools, private storage and credentials. Review authentication/tenant isolation before any future shared hosted operations. Add PostgreSQL, remote MCP or workers only for measured needs and approved cost/access/recovery plans.

The initial reusable workflow adds aois-candidate-intake and aois-query-plan to the original five investigation procedures: aois-institution-map, aois-researcher-discovery, aois-opportunity-intelligence, aois-research-audit and aois-university-investigation. Later procedures remain aois-researcher-deep-dive, aois-outreach-prepare, aois-application-tracker and aois-university-watch. These are planned responsibilities, not installed skills. The orchestrator follows approved procedures/resources; it does not assume an automatic nested-skill API.

Success requires independently audited university coverage, no unsupported actionable openings, safe identities, interruption/resumption/restore, private-data isolation, broad recovery under changed interests, and improvements measured against credible held-out references. Add synthetic profiles beyond the initial technical domain before broad distribution claims. Record recall, errors, source health, costs, time and uncertainty; never invent achieved performance.

See [feature coverage](FEATURE_COVERAGE.md), [roadmap](ROADMAP.md), [detailed baseline](architecture/implementation-blueprint-v1.md), and [review protocol](manager/OPERATING_PROTOCOL.md).
