---
name: ceap-engineering-orchestrator
description: Use for CEAP ticket-to-code, implementation planning, code impact analysis, repository analysis, refactoring, PR preparation, release notes, and architecture justification workflows.
---

# CEAP Engineering Orchestrator

Use this skill when a development request needs enterprise-grade ticket-to-code orchestration.

## Workflow

1. Normalize the input into an engineering objective.
   - Identify the ticket, defect, feature, incident, or modernization request.
   - Capture acceptance criteria, constraints, affected users, and expected delivery artifact.
   - Flag missing business, regulatory, or operational context instead of guessing.

2. Build the technical context model.
   - Inspect repository structure, ownership boundaries, modules, API surfaces, integrations, and dependency graph.
   - Use semantic search, exact search, git history, existing docs, tests, logs, and related PR patterns.
   - Identify affected files, services, data flows, critical paths, and likely breaking-change vectors.

3. Produce an implementation plan.
   - Split work into coding, refactoring, tests, documentation, release, and review steps.
   - Include architecture rationale, risk assumptions, and rollback considerations.
   - Prefer the codebase's existing patterns over new abstractions.

4. Execute or prepare the change.
   - Generate code, refactor only where it reduces real risk or complexity, and update documentation when behavior changes.
   - Generate focused unit, integration, regression, API, smoke, or snapshot tests according to blast radius.
   - Prepare PR material with summary, risk analysis, validation evidence, and changelog notes.

5. Validate before completion.
   - Run relevant build, test, static analysis, dependency, and runtime checks.
   - If validation cannot run, state the exact blocker and residual risk.
   - Summarize changed behavior, changed files, tests, and release notes.

## Feature Coverage

- Ticket-to-code orchestration and semantic ticket analysis
- Automatic context aggregation and affected module identification
- Agentic implementation planning, code generation, refactoring, and PR preparation
- Diff, risk, architecture, dependency, API, data-flow, and breaking-change analysis
- Legacy code analysis, technical debt detection, explain-code workflows, and documentation generation
- Semantic code navigation, branch analysis, commit summaries, changelogs, and release notes

## Output Shape

For planning tasks, return:

- Objective
- Context findings
- Affected modules and files
- Implementation plan
- Test and validation plan
- Risks, assumptions, and approval gates

For completed implementation tasks, return:

- What changed
- Validation performed
- Risks or unresolved blockers
- PR-ready summary
