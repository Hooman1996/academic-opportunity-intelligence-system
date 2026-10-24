# Existing skills and reuse assessment

Researched: 24 October 2026. Scope: targeted public web discovery followed by original GitHub source, revision and license inspection. This is a bounded landscape review, not proof that all existing skills were found.

Search families included supervisor/PhD discovery SKILL.md, scholarship/opportunity skills, OpenAlex/scientific research skills, and portable skill authoring. Directory/search listings were leads; primary source files determine the findings below. No upstream skill was installed, executed, copied into AOIS, or benchmarked. License inspection is not a full dependency/security audit or a guarantee of fitness.

## Recommended shortlist

| Upstream | Inspected capability | Useful AOIS destination | Decision now |
| --- | --- | --- | --- |
| [Oisinwang/find_my_supervisor](https://github.com/Oisinwang/find_my_supervisor/blob/5845fbcdd94d070156d552628f12c81ab397ac19/skills/find-my-supervisor/SKILL.md) | Student intake, institution/supervisor discovery, source-backed shortlist and quality references | Private intake, query/report rubrics, selected supervisor comparison | Evaluate selected patterns; do not adopt its geography, school-tier assumptions or 5–12 shortlist as the discovery boundary |
| [voidful/academic-skills: professor-fit-analyser](https://github.com/voidful/academic-skills/blob/71e9c42c60636602e87985f4306d134a3b63809e/professor-fit-analyser/SKILL.md) | Field-aware researcher dossier, paper taxonomy, evidence/inference distinctions, applicant-level advice | Selected deep dives and later outreach preparation | Adapt cautiously after broad discovery; not a university-wide census or proof of mentoring/funding |
| [K-Dense-AI/scientific-agent-skills: paper-lookup](https://github.com/K-Dense-AI/scientific-agent-skills/blob/593377bb048752abb0152deab9fbb1083a6087df/skills/paper-lookup/SKILL.md) | Bounded scholarly API retrieval, provenance, pagination and quiet-error handling | Selected scholarly enrichment and identifier checks | Strong candidate for a small audited subset; no need to install the full collection |
| [K-Dense citation-management and literature-review](https://github.com/K-Dense-AI/scientific-agent-skills/blob/593377bb048752abb0152deab9fbb1083a6087df/skills/citation-management/SKILL.md) | Citation metadata checks and reproducible literature-search/screening records | Paper anchors, DOI validation, read-depth and coverage reporting | Later selective adaptation; verify provider rules and optional dependency costs |
| [Scottthe3rd/academic-researcher-skill](https://github.com/Scottthe3rd/academic-researcher-skill/blob/d17e1db8d660c6849ce4569cb53acb3e475a698a/academic-researcher-skill/academic-researcher/SKILL.md) | Persistent reading/decision ledgers, institutional requirement research, integrity and adversarial review procedures | Research-audit and deep-dive references | Reuse ideas selectively; its manuscript/doctoral-production scope is much broader than AOIS needs |
| [Anthropic skill-creator](https://github.com/anthropics/skills/blob/dbd4588f9e1033efb41dad4bef2f7947c8993d44/skills/skill-creator/SKILL.md) | Skill authoring, baseline comparisons, triggering evaluation and iterative review | Distribution/skill quality evaluation | Authoring/evaluation reference; not an academic opportunity finder |

## Source-specific findings and changes required

### Find My Supervisor

The inspected skill is directly relevant to student-to-supervisor screening, with explicit student intake, official/bibliographic evidence and report-quality references. Its declared initial coverage is CS/AI and mathematics in selected Mainland China and Hong Kong institutions. It produces a ranked shortlist plus uncertain/excluded groups and keeps communication under student control.

AOIS should keep broad researcher enumeration separate from that shortlist, replace location/school-tier assumptions with configurable packs, support all original opportunity families and history, and add institution-wide coverage, claim-level records, checkpoints and profile isolation. Sensitive eligibility attributes should be collected only when needed.

Inspect its referenced workflow, schemas, rubrics and helper scripts in a future bounded adoption task. Reading the entry skill and README does not audit those dependencies or establish its reported outcomes.

### Professor Fit Analyzer

The entry skill supports researcher-level dossiers across disciplines and applicant levels, separates factual evidence from inference, and warns against equating citations with mentoring quality. Useful patterns include research-taxonomy structure, read-depth honesty and field-sensitive interpretation.

Some sections still request judgments about resources, probable students, workload or mentoring from public research patterns. AOIS must preserve these as carefully bounded hypotheses or omit them when evidence is inadequate; none proves supervision authority, lab culture, current capacity or an opening. Use a small justified paper set and the user's chosen language. Trigger outreach drafting only after its separate gate, not automatically as a side effect of discovery.

This inspection covered selected portions of the long skill source and its license. It did not validate every referenced template or claim.

### Scientific Agent Skills

The current canonical repository resolves as Scientific Agent Skills; search results also used the older Claude Scientific Skills name. Verify current upstream paths instead of relying on mirrors.

Paper Lookup records endpoints/parameters/provenance and warns about successful HTTP responses that contain semantic errors, partial text or ignored filters. This is useful for AOIS adapters, not proof of current employment or vacancy status. Citation Management supplies metadata validation patterns. Literature Review supplies search/screening traceability; it does not establish complete university coverage.

The inspected collection also has [research-grants](https://github.com/K-Dense-AI/scientific-agent-skills/blob/593377bb048752abb0152deab9fbb1083a6087df/skills/research-grants/SKILL.md), but its purpose is investigator-authored grant proposal preparation. It is not a replacement for student scholarship, assistantship or award-to-vacancy discovery. Defer it.

Check optional credentials, external model/diagram services, shell/curl dependencies, retention, and current provider limits before reuse. No OpenRouter, Parallel or additional paid-provider dependency is approved. Do not copy old anonymous-access or quota assumptions into AOIS.

### Academic Researcher

The skill organizes scholarly work through persistent ledgers, integrity checks and an extensive command catalog. Selected institutional-requirement and reading/evidence patterns may help AOIS. Most manuscript production, teaching, simulated committee and doctorate-management features are outside this project's core. Its entry skill references many supporting documents that were not audited here.

Prefer a small grounded AOIS audit over wholesale import. Do not equate repeated model review with independent evidence or carry unrelated approval ceremonies into routine authorized research.

### Authoring and portable format

Anthropic's Skill Creator provides useful examples of comparing skill-assisted runs against a baseline and checking trigger behavior. The open [Agent Skills specification](https://agentskills.io/specification) defines a skill directory, SKILL.md metadata, progressive loading and supporting resources. Use these as interoperability and quality references, with AOIS-specific evidence/privacy tests.

Neither valid metadata nor a compatibility claim in another repository establishes successful operation on a user's client. Scripts, dependencies, permissions, private storage and distribution must be tested separately.

## Revision and license register

These are inspected snapshots, not floating dependencies or already-approved imports.

| Upstream | Pinned commit | Inspected license file |
| --- | --- | --- |
| Oisinwang/find_my_supervisor | 5845fbcdd94d070156d552628f12c81ab397ac19 | [MIT](https://github.com/Oisinwang/find_my_supervisor/blob/5845fbcdd94d070156d552628f12c81ab397ac19/LICENSE) |
| voidful/academic-skills | 71e9c42c60636602e87985f4306d134a3b63809e | [MIT](https://github.com/voidful/academic-skills/blob/71e9c42c60636602e87985f4306d134a3b63809e/LICENSE) |
| K-Dense-AI/scientific-agent-skills | 593377bb048752abb0152deab9fbb1083a6087df | [MIT](https://github.com/K-Dense-AI/scientific-agent-skills/blob/593377bb048752abb0152deab9fbb1083a6087df/LICENSE.md) |
| Scottthe3rd/academic-researcher-skill | d17e1db8d660c6849ce4569cb53acb3e475a698a | [MIT](https://github.com/Scottthe3rd/academic-researcher-skill/blob/d17e1db8d660c6849ce4569cb53acb3e475a698a/LICENSE) |
| anthropics/skills | dbd4588f9e1033efb41dad4bef2f7947c8993d44 | [Apache-2.0 for Skill Creator](https://github.com/anthropics/skills/blob/dbd4588f9e1033efb41dad4bef2f7947c8993d44/skills/skill-creator/LICENSE.txt) |

Anthropic's repository contains mixed licensing: its README distinguishes open-source examples from source-available document skills. Only the inspected Skill Creator license is recorded as Apache-2.0 here; do not assume its PDF/DOCX/PPTX/XLSX skills are permissively reusable.

AOIS currently has no owner-selected distribution license. Before copying code/instructions or publishing skill artifacts, record exact imported files, revision/hash, license/notice obligations, modifications, dependencies, network destinations and maintenance owner. Preserve required copyright/license notices. This review contains original summaries and links, not vendored upstream implementation.

## AOIS-specific gaps to protect

None of the inspected entry workflows establishes the entire required combination: all-top-level institutional mapping; broad plausible-person retention; independent current and historical opportunity branches; Master's/RA/TA/fee-relief routes; claim evidence and reversible identity; durable cross-device runs; candidate isolation; safe exports; independently audited completeness; and reliable weekly discovery plus semantic change checks.

That is a finding about this bounded sample, not a claim that no comparable system exists. AOIS's benefit must be demonstrated through shared fixtures and measured recall/error/cost, not asserted from feature lists.

## Bounded adoption process

1. Choose one upstream capability that fills an observed gap.
2. Inspect the exact SKILL.md, referenced resources, scripts, dependency licenses, outbound destinations and write behavior.
3. Compare with the current AOIS implementation and an unaided baseline.
4. Adapt behind AOIS contracts: no hidden ranking cutoff, keys in chats, automatic outreach, fabricated openings or full-CV disclosure.
5. Test both benefit and regressions: no-vacancy researcher, hidden department, historical call, same-name author, partial pagination and private-profile leak.
6. Record retain/adapt/reject with evidence, notices and a maintenance strategy. Pin the accepted revision; do not auto-update unreviewed instructions.
7. Have both managers review before admitting it to the released package.

Recommended order: intake/query rubric ideas during 03A/05A/05B; selected scholarly checks only when Tasks 17–21 show a gap; researcher dossier patterns in Task 22; authoring/evaluation patterns in Tasks 24–25. No new integration is installed by this plan.

## Official client references checked for planning

- [OpenAI: Build skills](https://learn.chatgpt.com/docs/build-skills) — repository-local Codex skill discovery and distinction from distributed plugin skills.
- [OpenAI: Package your plugin](https://developers.openai.com/plugins/build/plugins) — portable manifest/resources and surface-dependent distribution.
- [Claude Code: Extend Claude with skills](https://code.claude.com/docs/en/skills) — local project/personal skill locations and plugin scope; local files are not automatically available in cloud contexts.
- [Agent Skills specification](https://agentskills.io/specification) — portable authoring structure and metadata.

These documents support design choices, not account-specific compatibility. Actual release clients and versions remain untested. Keep a single canonical source and generate the necessary tested adapters; do not require users to maintain duplicate catalogs.
