# AOIS-I01 — Tool and runtime readiness

Copy the instruction block below into Codex desktop or Claude Code desktop. Issuing it authorizes only this task, including its scoped branch/commit/push. It does not authorize later roadmap steps.

---

TASK ID: AOIS-I01

OBJECTIVE
Build the smallest portable readiness checker and synthetic test protocol that identifies whether AOIS can execute on Codex desktop, Claude Code desktop, ChatGPT web and Claude web. Produce honest observed capability reports and exact follow-ups for surfaces the current agent cannot access.

REPOSITORY
Hooman1996/academic-opportunity-intelligence-system

AUTHORITATIVE INPUTS
Read AGENTS.md, README.md, docs/architecture/implementation-plan-v2.md,
docs/ROADMAP.md, docs/manager/OPERATING_PROTOCOL.md and this task.
The original documentation-only Task 01 command is superseded.

EXPECTED BASE
The final planning revision after planning PR #1 is merged into main.
Verify actual remote/main includes Plan v2 and this task before branching.
If the owner explicitly chooses the planning branch before merge, use that
verified exact head instead and report it as a deliberate base adjustment.
Do not start from README-only main as though the plan were present.

BEGIN BY INSPECTING
Repository identity and sanitized remotes; applicable instructions; actual
branch/base/head/status; existing code/checks; installed agent/client version;
available runtime and tools. Preserve useful files and unrelated changes.
Use an isolated worktree where needed. Do not reset, clean, force-push,
auto-stash or overwrite unrelated work. Report a concise inspection summary
and then continue within this authorized scope.

PERMITTED SCOPE
One portable diagnostic component:
- scripts/aois_doctor.py, or a clear existing equivalent;
- small shared diagnostic helper only if necessary;
- meaningful offline tests under tests/readiness/;
- a minimal synthetic nonpersonal JSON/HTML probe and a temporary skill-loading
  probe fixture under tests/fixtures/readiness/;
- docs/runbooks/tool-readiness.md with identical semantic checks for all four
  surfaces and exact manual steps for web account checks;
- templates/capability-matrix.md or JSON template;
- a sanitized implementation/validation report in docs/manager/;
- .gitignore protections for private local settings, credentials, runtime
  outputs and agent worktrees while preserving useful existing rules.

Prefer the Python standard library for this diagnostic. No new provider SDK,
application framework, packaging build or database is needed. Do not scaffold
the entire future repository tree or turn the probe into a production skill.

CHECKER BEHAVIOR
Support an offline mode that performs only local checks, plus explicitly
selected safe provider checks where the execution host actually exposes them.
Document a command such as:
python scripts/aois_doctor.py --offline --private-root <outside-checkout-path>

The real report must be written beneath the chosen private root. Console
output is a sanitized summary. Do not require real CVs or personal documents.

At minimum check/report:
- runtime/platform and known actual client/version, or unknown;
- the repository/workflow revision and applicable AGENTS presence/loading
  evidence when observed by the host;
- instruction and synthetic skill resource discovery separately;
- private root outside checkout, including resolved symlink/path containment;
- synthetic save/reload, canonical JSON/content integrity, immutable revision
  naming and restore from a known good copy;
- repo read capability through the tested route;
- local/Drive storage, native search/fetch, browser fallback, OpenAlex,
  Firecrawl, Apify and scheduler capability cells;
- current free-allowance/rate visibility if actually observed, otherwise
  not-tested/unknown, never zero or unlimited.

Use explicit states: passed, failed, blocked, not-tested, not-applicable.
Include operation, surface, observed-by, time, client/version, safe evidence
reference, limitation and next action. A setting/key being present does not
prove a provider works. No SDK import or website listing alone is a pass.

SYNTHETIC WEB PROTOCOL
Create a fixed synthetic payload and expected results, including JSON and
a tiny self-contained HTML probe. Provide instructions for a fresh ChatGPT web
session and a fresh Claude web session to:
1. Load the exact pinned readiness procedure and probe.
2. Confirm the available instruction/resource/runtime/tool route.
3. Save synthetic private JSON/HTML through the selected Drive connector,
   preserving usable content rather than auto-converting to a Google Doc.
4. Reload and verify the expected canonical payload/hashes in that runtime.
5. Resume from a fresh chat, and restore an earlier immutable probe revision.
6. Record failures and actual tool/permission limitations.
7. Identify cloud scheduler availability without creating a task.

Temporary synthetic skill-loading tests are permitted only in the chosen
user-owned test area/account. Do not install third-party skills, publish a
plugin, add production .agents/.claude catalogs, or overwrite existing skills.

The local implementing agent cannot perform tests in a different web account
by assertion. It must produce the repeatable handoff/checklist, mark those
cells not-tested, and give precise user steps. There is no requirement to
invent cross-account access to make the report green. Local implementation
can be reviewed while remaining web probes are carried out in their surfaces.

SAFE OPTIONAL CONNECTIVITY
Use existing authenticated tools/config only. Native search/fetch and provider
checks must be finite, nonpersonal, read-only and explicitly selected.
OpenAlex: at most three safe requests, using the existing key through approved
secret handling if available; no key output or secret-bearing logged URL.
Firecrawl: at most one known public page, only with verified included/free
allowance and a bounded cost; otherwise leave it not-tested.
Apify: inspect connection/capability metadata if safe; no Actor execution.
Do not probe unneeded APIs, perform university research or create accounts.
Unknown billing bounds stop a metered probe. Incremental spend remains $0.
No API keys, OAuth tokens or .env values in chat, logs, reports or test fixtures.

OWNER REQUIREMENTS
- AGENTS.md only; do not create CLAUDE.md or CLAUDE.local.md.
- Verify installed Claude direct-AGENTS support; report unsupported settings
  or versions rather than adding the prohibited workaround.
- No embeddings/vector similarity/semantic-search implementation.
- Private CV/research findings stay outside Git.
- The owner allows task content in Claude/OpenAI models; do not impose
  training opt-out or context-minimization prerequisites.
- All four execution surfaces remain required product targets.
- Local/Drive handoff is explicit; no uncontrolled sync or false distributed
  locking guarantee.
- Cloud weekly runs and messenger alerts remain later gated work.

EXCLUSIONS
No production research skills, source collectors, ontology/config packs,
business schemas/validators, query planner, CV parser/profile extraction,
dossier/report generator, private research data, lock/lease engine, database,
MCP service, API wrapper platform, CI service, full plugin packaging, schedule,
watch, messenger/email action, outreach or application submission.
Do not create .mcp.json or .codex/config.toml, enable arbitrary servers, modify
account permissions/visibility, buy credits or publish credentials.
The small diagnostic probe is not production storage, a production skill or
the first real investigation.

REQUIRED TESTS/CHECKS
Run offline tests covering:
- valid external private root;
- rejected in-repository/nested/symlink-contained private paths;
- missing runtime/tool/credential represented honestly;
- known synthetic JSON/HTML save, reload, corruption and restore;
- report states and sanitized exceptions/logs, including fake credential
  values that must not appear in output;
- offline mode makes no network calls;
- no unobserved surface or provider is marked passed;
- no report with real host/account paths is written to tracked output.

Use portable temporary directories and meaningful assertions. Mock provider
errors; no real account dependency in default tests. Run on the current host;
document untested OS/client combinations. Run git diff --check, scope review,
secret/private-output scan and applicable existing lightweight checks.
Record exact commands/results, failures/skips and limitations.

ACCEPTANCE
A repeatable readiness component and four-surface protocol exist. Offline
tests pass. Actual local results are private and honest. Public artifacts
contain only synthetic/sanitized development evidence. Each untested mode
has actionable follow-up; no fabricated pass or production component appears.
No forbidden instruction file or secret/private data is introduced.
The task is reviewable at exact base/head with checks and preserved work.

BRANCH
aois/i01-tool-readiness
Inspect any existing branch before reuse; choose a clear unused suffix if
necessary and never overwrite unrelated work.

COMMITS AND PUSH
One or more cohesive task-owned commits, e.g.
feat: add AOIS tool and runtime readiness checks
Stage exact task files, verify the staged diff, and push the task branch to
the verified repository remote. No force-push, main merge, deployment or PR
auto-merge. If push is blocked, retain local commits and report the actual
nonsecret blocker.

FINAL REPORT
- Task ID, outcome and implementing agent.
- Actual base branch/SHA, task branch/head SHA and pushed branch or PR URL.
- Inspection summary and unrelated changes preserved.
- Changed files/behavior and scoped deviations.
- Exact check/test commands and results.
- Sanitized local readiness summary; private report location shown only to
  the user in the private session, not in Git.
- Four-surface matrix with real observed states and not-tested cells.
- Remaining account-specific steps and limitations.
- Privacy/scope review, worktree status and manager review PENDING.

Stop after AOIS-I01. Do not begin AOIS-I02 or activate an actual watch.
