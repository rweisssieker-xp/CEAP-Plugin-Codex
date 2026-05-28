---
name: ceap-agent-operations
description: Use for CEAP multi-agent workflows, agent role assignment, release management, incident response, observability, autonomous engineering, VS Code or Teams agent workflows, and human-in-the-loop operations.
---

# CEAP Agent Operations

Use this skill when coordinating multiple specialized agents or designing controlled autonomous engineering operations.

## Workflow

1. Select agent roles.
   - Choose only the roles required for the work: planning, coding, review, security, testing, refactoring, compliance, architecture, documentation, DevOps, observability, incident response, release, dependency management, or data analysis.
   - Define each agent's input, output, authority, tools, and stopping condition.

2. Design the orchestration.
   - Decide whether tasks should run sequentially, in parallel, or adaptively.
   - Add persistent workflow state, handoff artifacts, health checks, retry policy, and escalation paths.
   - Keep human approval gates for code writes, risky commands, production actions, regulated decisions, and autonomous maintenance.

3. Add explainability and observability.
   - Record agent decisions, risk reasoning, architecture rationale, telemetry, performance metrics, hallucination checks, and audit exports.
   - Provide workflow analytics and root-cause analytics where incident or release risk exists.

4. Operate channels.
   - For VS Code workflows, include side-panel control, ticket analysis, explain-code, generate-tests, PR preparation, inline security warnings, architecture insights, diff/risk preview, agent status, workflow debugging, and architecture previews.
   - For Teams workflows, include adaptive cards, approval workflows, PR approvals, notifications, incident alerts, release status, build/deployment warnings, security alerting, compliance reviews, meeting summaries, task extraction, dashboards, and escalation management.

5. Control autonomous work.
   - Scope dependency updates, security patches, API migrations, test repair, release readiness, build repair, configuration correction, rollback recommendations, performance optimization, legacy modernization, and hardening suggestions.
   - Require policy checks and human approval before irreversible or production-impacting steps.

## Feature Coverage

- Planning, coding, reviewer, security, test, refactoring, compliance, architecture, documentation, DevOps, observability, incident response, release, dependency, and data-analysis agents
- Coordinated workflows, persistent orchestration, role-based assignment, adaptive prioritization, dynamic delegation, specialized pipelines, parallel execution, shared memory, capability profiles, and health monitoring
- Explainability layer, agent telemetry, workflow analytics, hallucination tracking, audit export, run history, decision rationale, KPI dashboards, multi-agent telemetry, and governance analytics
- Controlled autonomous maintenance, dependency updates, security patching, incident response, rollback recommendation, hardening, stability analysis, technical-debt reduction, and workflow optimization

## Output Shape

Return:

- Agent roster
- Workflow state model
- Handoff artifacts
- Approval gates
- Observability signals
- Autonomous boundaries
