---
name: ceap-quality-governance
description: Use for CEAP quality engineering, automated test generation, security checks, compliance validation, policy gates, auditability, and regulated enterprise or MedTech engineering review.
---

# CEAP Quality Governance

Use this skill when a request needs quality, security, compliance, or regulated-delivery controls.

## Workflow

1. Classify the change risk.
   - Determine whether the change touches security, privacy, regulated workflows, data integrity, APIs, infrastructure, dependencies, or release gates.
   - Identify MDR, ISO, FDA, SOP, tenant-isolation, RBAC, audit, or enterprise-governance implications when relevant.

2. Build a validation matrix.
   - Select unit, integration, regression, API, smoke, snapshot, load, mutation, compliance, and security tests according to risk.
   - Include mock or synthetic test data requirements.
   - Add canary, rollback, runtime, and performance-regression checks for production-facing changes.

3. Run security and compliance review.
   - Check secrets, dependency risk, license risk, supply-chain exposure, container security, policy enforcement, prompt isolation, and runtime permissions.
   - Validate PII redaction, least privilege, tenant isolation, sandbox execution, and audit-trail requirements.
   - Treat automated findings as evidence to triage, not as a substitute for reasoning.

4. Document audit evidence.
   - Record decisions, controls, tests, residual risks, and approval gates.
   - Preserve traceability from requirement to implementation to validation result.
   - Produce clear review notes for teams, PRs, and regulated approval workflows.

## Feature Coverage

- Unit, integration, regression, smoke, snapshot, load, mutation, and compliance test generation
- Static analysis, dependency validation, container checks, supply-chain security, license analysis, and runtime validation
- AI-assisted bug reproduction, test-impact analysis, intelligent failure correlation, and test repair
- RBAC, Entra ID, least privilege, sandboxing, secret isolation, policy engine, approval gates, tenant isolation, and zero-trust controls
- MDR, ISO, FDA, SOP, audit export, revision-safe logs, governance dashboards, and compliance reporting

## Output Shape

Return a concise governance report:

- Risk classification
- Required checks
- Evidence collected
- Findings by severity
- Approval gates
- Residual risk
