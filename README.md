# Academic Opportunity Intelligence System (AOIS)

AOIS is a planned academic intelligence system and reusable skill set. Given a university, a CV/background, interests and goals, it will systematically discover researchers, supervisors, labs, programmes, current opportunities, funding routes and historical signals across the institution.

**Planning baseline v2 is finalized on 25 October 2026. Implementation starts with AOIS-I01: tool and runtime readiness.** The repository currently contains planning documentation; no production AOIS skills, collectors, dossier generator or watches are implemented. Claude's supplied response accepts the review corrections and planning closure; this updated commit is the resulting consolidation, not a claim that Claude independently inspected its exact bytes.

## Run from desktop or the web

| Required surface | Planned execution and private persistence |
| --- | --- |
| Codex desktop on Windows or Ubuntu where supported | Local tools and a configured private root outside the Git checkout; cloud checkpoint handoff when wanted |
| Claude Code desktop on Windows or Ubuntu where supported | Same approved instructions, procedures, private record format and ownership rules |
| ChatGPT web, including Work | Approved workflow resources plus available tools; private Drive bundles for cross-session continuity |
| Claude web | Account-enabled workflow package/resources, code execution and connectors; private Drive bundles |

Every surface must pass its own readiness checks. A web session does not automatically access an offline computer's folder. A pinned manual workflow bundle can start research before automatic skill installation is available; it is reported as manual mode. Full four-surface readiness is a release gate.

## What the complete system will do

- Expand interests through field vocabularies: related/broader/narrower topics, methods, modalities, applications, original-language labels and varied query phrases. No embeddings, vector similarity or semantic-search feature.
- Screen all top-level units and investigate relevant/uncertain departments, centres, institutes, labs, projects, programmes, campuses and affiliates.
- Keep every plausible researcher, including weak matches and people without an advertised position or known funding. Discovery, vacancy search and ranking remain separate.
- Search doctoral/direct/integrated/industrial/collaborative routes; research Master's and funded thesis work; RA/GRA/scientific/project roles; teaching/research assistantships; scholarships/fellowships/fee waivers; internships, visiting and host routes.
- Preserve expired calls, grants, projects, recurring cycles, supervision and thesis history. Grants are signals, not vacancies.
- Produce a polished self-contained HTML dossier and CSV from structured JSON, with searchable/sortable/filterable tables, coverage/gaps and clickable evidence. XLSX follows later.
- Support selected paper deep dives, private comparisons, outreach preparation and application planning.
- Eventually run weekly discovery and meaningful-change checks in an account-supported cloud scheduler with computers off, write private results, and deliver explicitly enabled messenger/email alerts.

Researcher counts never prove completeness. Evidence, honest unknowns, reversible identity decisions, checkpoints, budgets and independent audit remain core requirements.

## Public system; private investigations

GitHub holds code, instructions, skills, field/country packs, schemas, tests with synthetic fixtures, documentation and release artifacts. CVs, profiles, person-level findings, opportunities found for an applicant, dossiers, evidence caches, rankings, correspondence and applications stay in local private storage and/or private Google Drive. They are never committed to this repository.

The owner permits sending CV/investigation content to the Claude and OpenAI models performing the work. Training opt-outs and model-context minimization are not AOIS prerequisites. Secrets still never enter Git, chat, model context or artifacts. Search APIs receive appropriate short derived queries.

The maintainer's private case is the first real pilot. Other applicants use their own profiles, goals, stores, credentials and optional field packs; no personal fact or country exclusion becomes a product default.

## Current documents

| Document | Purpose |
| --- | --- |
| [Implementation Plan v2](docs/architecture/implementation-plan-v2.md) | Current architecture, private authority, four surfaces and release gates |
| [Roadmap](docs/ROADMAP.md) | Ordered bounded implementation tasks and legacy-ID crosswalk |
| [Project charter](docs/PROJECT_CHARTER.md) | Complete scope and workflow |
| [Feature coverage](docs/FEATURE_COVERAGE.md) | F01–F50 plus finalized owner requirements |
| [Final decision](docs/decisions/0002-final-runtime-storage-and-scope.md) | Resolved review/owner decisions and superseded proposals |
| [Planning closure](docs/manager/PLANNING_CLOSURE_2026-10-25.md) | C-01–C-19 dispositions, evidence and closure status |
| [Operating protocol](docs/manager/OPERATING_PROTOCOL.md) | Owner authorization and ChatGPT/Claude exact-revision review |
| [First implementation task](docs/tasks/AOIS-I01-tool-readiness.md) | Complete copy/paste task envelope for the local implementer |
| [Existing skills review](docs/research/EXISTING_SKILLS_REVIEW_2026-10-24.md) | Pinned upstream sources/licenses and adaptation limits |
| [Historical blueprint](docs/archive/implementation-blueprint-v1.md) | All 40 earlier sections retained as non-authoritative history |

AGENTS.md is the only repository-level agent instruction file. Do not add CLAUDE.md or CLAUDE.local.md. Canonical skill source will be .agents/skills; generated Claude and web packages must preserve version equality.

Use native search/fetch, the existing OpenAlex account/key and Firecrawl first; Apify is an audited bounded fallback. Incremental spending is $0 and only verified free allowances may be consumed. Extra tools, paid services, API billing and hosting require separate approval.

A web UI is an execution surface. A particular repository-backed Codex Cloud environment is an optional route to evaluate only if needed, not a requirement or a blanket prohibition on web research. No such environment is provisioned by this plan.

No AOIS skill release or installation command exists yet. Owner-selected licensing and upstream notices are required before redistribution. Future notifications, messages and submissions are individually scoped and authorized.
