# CEAP User Guide

## Purpose

Use CEAP when a Codex task requires enterprise-grade engineering reasoning, not just code generation. CEAP is best suited for changes that need impact analysis, risk assessment, compliance evidence, multi-agent planning, or release decision support.

## Common Workflows

### Ticket-To-Code Planning

Use `ceap-engineering-orchestrator` when a ticket, bug, feature, or incident needs to become an implementation plan.

Expected output:

- Engineering objective
- Context findings
- Affected modules and files
- Implementation plan
- Test and validation plan
- Risks and assumptions
- PR-ready summary

### PR Evidence Pack

Use `ceap-ai-usp-engine` with `ceap-quality-governance` when a change needs review evidence.

Expected output:

- Ticket summary
- Impact analysis
- Risk file
- Compliance flags
- Cited historical context
- Test recommendations
- Reviewer recommendations
- Release note

### Enterprise Context Analysis

Use `ceap-enterprise-context` when the task depends on repositories, tickets, docs, incidents, logs, Teams, SharePoint, ERP, D365, or CI/CD context.

Expected output:

- Context sources used
- Verified facts
- Inferred relationships
- Impact map
- Missing context
- Reusable memory entries

### Multi-Agent Operations

Use `ceap-agent-operations` when coordinating specialized agents for planning, coding, security, QA, compliance, architecture, documentation, incident response, or release management.

Expected output:

- Agent roster
- Workflow state model
- Handoff artifacts
- Approval gates
- Observability signals
- Autonomous boundaries

## Recommended Prompts

- "Create a PR evidence pack for this ticket and repository."
- "Run an AI impact twin analysis before implementation."
- "Classify this change for MDR/ISO compliance impact."
- "Create a policy-bound multi-agent workflow for this incident."
- "Generate a release readiness brief from these PRs and CI results."

## Human Review Requirements

CEAP can recommend, draft, classify, and validate. It must not silently approve regulated, security-sensitive, production-impacting, or irreversible actions. Human approval is required for:

- Production deployments
- Compliance sign-off
- Security exception approval
- Data access expansion
- Autonomous merge or release
- Policy changes
- Tenant boundary changes

## Output Quality Standard

Every CEAP workflow should include:

- Clear objective
- Evidence sources
- Explicit assumptions
- Risk level
- Validation plan
- Human approval gates
- Measurable success signal
