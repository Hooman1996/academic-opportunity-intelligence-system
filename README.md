# Academic Opportunity Intelligence System (AOIS)

AOIS is a planned, evidence-backed academic research system and reusable agent skill set. Given a university, a private CV or background summary, research interests, and goals, it will discover relevant researchers, supervisors, laboratories, degree routes, funding, research jobs, and current and historical opportunities across the institution.

It expands beyond literal keywords into related methods, topics, applications, local terminology, and unexpected departments. Relevant researchers remain in the inventory even when no vacancy is advertised. Discovery comes before ranking; coverage records establish how thoroughly an institution was investigated.

**Current status: planning and documentation.** Repository inspection on 24 October 2026 found one README at `9367b76cde1b9c555d7004c8ec67c8f74fcd8ebe`. This planning change adds shared specifications for review. No AOIS production skills, collectors, schemas, services, tests, or weekly watches have been implemented. Goals below describe intended behavior, not released capabilities.

## Two deliverables, one research core

- **A complete personal workbench:** detailed university dossiers, broad researcher inventories, current routes, historical recruitment and project intelligence, private candidate comparisons, selected paper deep dives, application planning, and eventually reliable weekly discovery and change checks.
- **Reusable skills for other applicants:** configurable CV-and-interest workflows, field and country packs, reproducible evidence and coverage records, and versioned packages for supported Codex, ChatGPT, and Claude surfaces. Each person uses their own private profile, storage, permissions, and accounts.

The maintainer's private workflow is the first real pilot. Generalization is evaluated with additional synthetic profiles and other disciplines; personal facts never become public defaults or fixtures.

## Protected principles

1. Researcher discovery, vacancy discovery, and ranking are separate.
2. Retain plausible researchers, uncertain identities, weak matches, and people without advertised funding.
3. Screen every top-level unit; traverse relevant and uncertain departments, institutes, centres, labs, groups, programmes, joint units, and affiliates.
4. Preserve old calls, grants, projects, supervision, and thesis history. Grants are signals; expired calls are history.
5. Cover PhD, direct/integrated and industrial routes; research Master's and funded thesis work; RA/GRA and scientific/project roles; teaching/research assistantships; scholarships, fellowships, fee waivers/remission; internships and visiting routes.
6. Evidence supports claims. Unknown is not negative. A researcher count never proves completeness.
7. Candidate information, search intent, rankings, correspondence, and applications remain private. Secrets never enter Git, chats, artifacts, or logs.

The initial technical field pack includes AI, computer vision, remote sensing, GeoAI, GIS, photogrammetry, geometry, robotics, LLMs, agents, and related methods and applications. The core must support additional fields without applying computing norms to every discipline.

## Start with the shared plan

| Document | Purpose |
| --- | --- |
| [Project charter](docs/PROJECT_CHARTER.md) | Users, full product scope, workflow, privacy, outputs, and success conditions |
| [Implementation roadmap](docs/ROADMAP.md) | Ordered steps, dependencies, acceptance gates, and changes to the earlier plan |
| [Feature coverage](docs/FEATURE_COVERAGE.md) | Trace every planned feature to its component, task, and verification |
| [Blueprint v1](docs/architecture/implementation-blueprint-v1.md) | Complete publication-safe technical baseline from 7 October 2026 |
| [General-purpose design decision](docs/decisions/0001-general-purpose-and-review.md) | Profile isolation, field neutrality, portable skills, and shared review authority |
| [Operating protocol](docs/manager/OPERATING_PROTOCOL.md) | ChatGPT/Claude review, task boundaries, and exact-revision handoffs |
| [Existing skills research](docs/research/EXISTING_SKILLS_REVIEW_2026-10-24.md) | Inspected upstream skills, licenses, reuse opportunities, and gaps |
| [Current planning review](docs/manager/PLANNING_REVIEW_2026-10-24.md) | Inspection evidence, review status, checks, and next action |

## Development and release boundaries

GitHub is the shared technical and review record. Codex Desktop on Windows implements one authorized component at a time. ChatGPT and Claude review exact revisions and record findings and dispositions. The user settles unresolved material disagreements and authorizes consequential actions.

Normal ChatGPT Work research on Ubuntu must run and resume while Windows is offline. Cross-client packaging and Claude compatibility are targets requiring tests on actual supported surfaces. Codex Cloud is out of scope.

Start with portable files and a single writer. Add databases or a narrow remote service only after measured need and review. Weekly checks require durable baselines, semantic comparison, failure reporting, budgets, and explicit activation. Outreach remains reviewed preparation until the user authorizes a concrete send or submission.

No installation command is provided yet because there is no AOIS skill release. Public availability of this repository does not itself grant a reuse license; the owner must select the AOIS license and review third-party notices before redistribution.
