---
name: ceap-ai-usp-engine
description: Use for CEAP AI USPs, AI impact twin, regulatory co-pilot, AI review board, cited engineering memory, risk files, autonomous fix evidence, process mining, policy-bound agents, predictive review routing, release decision intelligence, risk prediction, architecture drift, compliance gaps, test debt, migrations, incident learning, requirement contradictions, privacy data flows, DevEx friction, and contract guardianship.
---

# CEAP AI USP Engine

Use this skill when the task asks for CEAP differentiation, AI product strategy, or implementation of CEAP's AI value loops.

## Core Principle

CEAP AI features must reduce enterprise engineering risk, cycle time, uncertainty, or audit effort. Do not present generic chat, dashboards, or AI-powered claims as USPs unless they include a decision loop, required data, trust controls, and a measurable outcome.

## AI USP Portfolio

### 1. AI Impact Twin

- Target user: Enterprise architects, tech leads, release managers
- Pain solved: Teams do not know which systems, APIs, processes, and compliance artifacts a change affects before implementation.
- AI mechanism: Build a semantic impact graph from repositories, tickets, pull requests, architecture docs, logs, deployments, D365/ERP objects, and service dependencies.
- Differentiation: CEAP predicts enterprise impact before code is written.
- MVP: Analyze one repository plus ticket history, PR history, API references, and architecture notes.
- Trust controls: Source-linked findings, confidence levels, explicit unknowns, and human approval before implementation.
- Proof metric: Reduce missed review impacts and post-merge surprises by at least 30 percent.

### 2. AI Regulatory Co-Pilot

- Target user: MedTech, QA/RA, compliance, regulated enterprise teams
- Pain solved: Developers cannot reliably identify when MDR, ISO, FDA, SOP, validation, or audit artifacts are affected.
- AI mechanism: Classify tickets, diffs, modules, data flows, and requirements against regulatory control points.
- Differentiation: CEAP generates regulation-aware evidence, not generic compliance text.
- MVP: PR-level MDR/ISO impact classification with evidence checklist.
- Trust controls: Mandatory citations, reviewer sign-off, no autonomous compliance approval.
- Proof metric: Reduce compliance review preparation time by 40 percent.

### 3. AI Review Board Before Pull Request

- Target user: Senior developers, architects, security, QA, compliance
- Pain solved: Architecture and governance issues are discovered after implementation when rework is expensive.
- AI mechanism: Run role-specialized agents over the ticket and implementation plan before coding.
- Differentiation: CEAP shifts review left into the planning phase.
- MVP: Planning review by architecture, security, test, compliance, and release agents.
- Trust controls: Clear agent role boundaries, dissenting opinions, and unresolved-risk list.
- Proof metric: Reduce PR rework and review-cycle duration.

### 4. Engineering Memory With Citations

- Target user: Developers, architects, platform teams, new team members
- Pain solved: AI recommendations are hard to trust without organizational evidence.
- AI mechanism: Retrieve and cite prior PRs, incidents, reviews, ADRs, tickets, and team conventions for every material recommendation.
- Differentiation: CEAP makes AI advice traceable to internal engineering history.
- MVP: Repository memory from PRs, issues, ADRs, and review comments.
- Trust controls: Citation required for claims, recency markers, source quality ranking, and hallucination checks.
- Proof metric: Increase accepted AI recommendations and reduce repeated solution discovery.

### 5. AI Change Risk File

- Target user: QA, release managers, CTOs, product owners
- Pain solved: Change risk is fragmented across tickets, PR comments, CI checks, security scans, and release notes.
- AI mechanism: Generate a machine-readable and human-readable risk file for each change.
- Differentiation: Every change gets a durable risk artifact.
- MVP: Markdown and JSON risk file attached to a PR.
- Trust controls: Source-linked risk claims, severity rubric, approval status, and residual risk section.
- Proof metric: Faster go/no-go decisions and fewer undocumented release risks.

### 6. Autonomous Fix With Proof

- Target user: Developers, DevOps, QA, platform teams
- Pain solved: AI-generated fixes are not trusted without reproducibility and validation evidence.
- AI mechanism: Reproduce failure, isolate root cause, generate fix, run tests, and produce evidence.
- Differentiation: CEAP couples autonomous repair with proof, not just a patch.
- MVP: Failing CI test to fix proposal with test evidence.
- Trust controls: No merge without human approval, test transcript, diff rationale, rollback note.
- Proof metric: Reduce manual CI triage time by 25 percent.

### 7. AI Process Mining For Engineering Work

- Target user: Engineering managers, platform teams, developer productivity teams
- Pain solved: Repetitive engineering work is invisible and therefore not automated.
- AI mechanism: Detect recurring workflows from tickets, PRs, builds, logs, debug patterns, IDE events, and tool transitions.
- Differentiation: CEAP discovers automation opportunities from real engineering behavior.
- MVP: Pattern mining from tickets and PRs without screen/OCR data.
- Trust controls: Privacy boundaries, opt-in sources, aggregation, retention limits, and no individual performance scoring by default.
- Proof metric: Number of high-confidence automation candidates implemented per month.

### 8. Policy-Bound AI Agents

- Target user: Enterprise security, platform engineering, compliance
- Pain solved: Autonomous agents are risky when data access, tools, and actions are not constrained.
- AI mechanism: Give every agent a policy contract defining allowed data, tools, actions, approvals, logging, and stop conditions.
- Differentiation: CEAP turns agent autonomy into governable enterprise automation.
- MVP: Agent policy manifest plus runtime preflight checks before tool use.
- Trust controls: Deny-by-default permissions, audit logs, approval gates, tenant isolation, and policy violation reporting.
- Proof metric: Zero unauthorized tool/data actions in agent runs.

### 9. Predictive Review Routing

- Target user: Developers, team leads, code owners
- Pain solved: Pull requests wait for the wrong reviewers or miss required domain experts.
- AI mechanism: Infer reviewers from semantic code ownership, historical reviews, affected domains, risk level, and compliance relevance.
- Differentiation: CEAP routes reviews by impact and expertise, not only static ownership files.
- MVP: Reviewer recommendation from git history, PR diff, and ownership metadata.
- Trust controls: Explain why each reviewer is suggested, expose alternatives, avoid sensitive profiling.
- Proof metric: Reduce review latency by 20 to 30 percent.

### 10. AI Release Negotiator

- Target user: Release managers, product owners, engineering leads
- Pain solved: Release decisions are fragmented, political, and weakly documented.
- AI mechanism: Convert tickets, PRs, CI, tests, incidents, compliance gates, and customer impact into release options.
- Differentiation: CEAP produces decision-ready release scenarios: ship, delay, partial release, canary, rollback-ready.
- MVP: Release readiness brief from PRs, CI status, test results, open risks, and rollback state.
- Trust controls: Evidence-backed recommendations, explicit uncertainty, human final decision, and audit trail.
- Proof metric: Faster release decisions with fewer untracked exceptions.

## Default Output

When applying these USPs, return:

- Selected USP or USP bundle
- Target user and painful job
- Required data and integrations
- AI mechanism
- MVP implementation path
- Trust and governance controls
- Proof metric
- Open risks and assumptions

## Prioritization

Build first:

1. PR Evidence Pack Agent combining AI Change Risk File, Regulatory Co-Pilot, Engineering Memory With Citations, and Predictive Review Routing.
2. Policy-Bound AI Agents to make all later autonomy governable.
3. AI Impact Twin for high-value enterprise differentiation.

## Advanced AI USP Portfolio

Use these USPs when CEAP needs deeper differentiation beyond the first ten AI value loops.

### 11. AI Engineering Risk Market

- Target user: CTOs, VPs of Engineering, release managers
- Pain solved: Engineering risk is assessed subjectively and inconsistently.
- AI mechanism: Learn from historical PRs, incidents, rollbacks, test failures, security findings, ownership patterns, and release outcomes to predict which change patterns create later problems.
- Differentiation: CEAP scores risk from organization-specific evidence, not generic heuristics.
- MVP: PR risk prediction with low, medium, high severity and cited drivers.
- Trust controls: Explainable risk factors, calibration reports, no automated blocking without policy approval.
- Proof metric: Reduce unplanned post-release incidents.

### 12. AI Architecture Drift Detector

- Target user: Enterprise architects, tech leads, platform teams
- Pain solved: Systems drift away from target architecture before anyone notices.
- AI mechanism: Compare code, dependencies, APIs, data flows, ADRs, and architecture principles against the intended architecture model.
- Differentiation: CEAP detects architecture drift continuously, not only during manual review.
- MVP: Drift report per PR or sprint.
- Trust controls: Cite violated ADRs or principles, classify severity, allow architect override.
- Proof metric: Reduce architecture violations found late in review.

### 13. AI Compliance Gap Simulator

- Target user: QA/RA, compliance owners, engineering leads
- Pain solved: Teams do not know which evidence is missing until audit or release pressure starts.
- AI mechanism: Simulate an audit against tickets, tests, risk files, SOPs, validation artifacts, release notes, and approval records.
- Differentiation: CEAP identifies missing evidence, not just compliance status.
- MVP: Audit readiness gap report for one release.
- Trust controls: Human compliance owner remains accountable, all gaps cite missing or weak artifacts.
- Proof metric: Reduce audit preparation rework.

### 14. AI Test Debt Investor

- Target user: QA leads, engineering managers, tech leads
- Pain solved: Test debt is known but not economically prioritized.
- AI mechanism: Rank missing tests by expected risk reduction using code criticality, change frequency, defect history, coverage, and incident correlation.
- Differentiation: CEAP turns test generation into a risk-reduction investment decision.
- MVP: Top 10 missing tests by risk reduction.
- Trust controls: Show assumptions, avoid false precision, require human selection before generating large test suites.
- Proof metric: Increase defect detection per new test.

### 15. AI Migration Commander

- Target user: platform teams, legacy modernization teams, API owners
- Pain solved: Legacy, framework, API, cloud, or dependency migrations are difficult to sequence safely.
- AI mechanism: Break migrations into impact graph, dependency order, partial PRs, tests, rollback points, and release gates.
- Differentiation: CEAP plans migration as a controlled engineering program, not a one-shot code edit.
- MVP: Migration plan for one dependency, framework, or API version.
- Trust controls: Human approval at each migration slice, rollback criteria, compatibility tests.
- Proof metric: Reduce migration duration and regression rate.

### 16. AI Incident Memory Loop

- Target user: SREs, DevOps, engineering leads
- Pain solved: Incidents are resolved but lessons are not reliably converted into engineering prevention.
- AI mechanism: Convert incident timelines into root cause, recurring patterns, prevention PRs, tests, runbook updates, and detection rules.
- Differentiation: CEAP turns incident response into durable engineering improvement.
- MVP: Incident-to-prevention pack.
- Trust controls: Cite logs and timeline evidence, require owner approval for prevention tasks.
- Proof metric: Reduce recurring incidents.

### 17. AI Requirements Contradiction Detector

- Target user: product owners, business analysts, developers, QA
- Pain solved: Tickets, specs, acceptance criteria, SOPs, tests, and API contracts can contradict each other.
- AI mechanism: Compare requirements across tickets, docs, contracts, tests, and compliance rules to detect conflicts before implementation.
- Differentiation: CEAP prevents wrong implementation before coding starts.
- MVP: Contradiction scan for ticket plus linked docs.
- Trust controls: Present contradictions with exact source references and ask for human resolution.
- Proof metric: Reduce clarification loops and requirement-driven rework.

### 18. AI Data Flow Privacy Guardian

- Target user: security teams, DPOs, compliance, architects
- Pain solved: Sensitive data flows are hard to trace across enterprise systems.
- AI mechanism: Infer data flows from code, schemas, APIs, logs, and docs, classify PII/PHI/sensitive fields, and compare them to policy.
- Differentiation: CEAP brings privacy-by-design into the engineering workflow.
- MVP: PR-level sensitive data flow check.
- Trust controls: Strict data minimization, source citations, policy-owner review, no unnecessary data retention.
- Proof metric: Reduce late privacy findings before release.

### 19. AI DevEx Friction Radar

- Target user: platform engineering, developer productivity teams, engineering managers
- Pain solved: Developer time is lost to builds, flaky tests, unclear workflows, and repeated manual steps.
- AI mechanism: Correlate CI time, failure rates, review latency, ticket cycle time, flaky tests, and recurring manual workflow patterns.
- Differentiation: CEAP recommends concrete platform fixes, not just productivity metrics.
- MVP: Monthly friction report with top five fix recommendations.
- Trust controls: Aggregate team-level reporting by default, avoid individual performance scoring.
- Proof metric: Reduce lead time, flaky-test time, and repeated manual work.

### 20. AI Contract Guardian

- Target user: API teams, integration teams, ERP/D365 teams
- Pain solved: API, event, schema, and ERP contracts break silently across consumers.
- AI mechanism: Check code changes against OpenAPI, GraphQL, event schemas, ERP fields, consumer behavior, and historical integration failures.
- Differentiation: CEAP protects enterprise integration stability beyond unit tests.
- MVP: Contract risk report per PR.
- Trust controls: Cite contract source, identify affected consumers, require owner approval for breaking changes.
- Proof metric: Reduce integration failures after deployment.
