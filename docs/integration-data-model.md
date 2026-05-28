# CEAP Integration And Data Model

## Integration Categories

CEAP can integrate with the following categories:

- Repositories: GitHub, GitLab, Azure DevOps Repos
- Ticket systems: Azure Boards, Jira, ServiceNow
- Documentation: SharePoint, Confluence, Markdown repositories, ADR stores
- Communication: Microsoft Teams
- CI/CD: GitHub Actions, Azure Pipelines, GitLab CI, Jenkins
- Security: SAST, dependency scanners, container scanners, SIEM tools
- Observability: Datadog, Splunk, Elastic, Prometheus, Grafana, OpenTelemetry
- Cloud and infrastructure: Azure, AWS, Google Cloud, Kubernetes, Docker, IaC repositories
- Enterprise systems: D365, ERP, SAP, API gateways, event streaming platforms

## Core Data Objects

### Ticket

- ID
- Title
- Description
- Acceptance criteria
- Priority
- Status
- Linked systems
- Regulatory tags
- Business owner

### Repository Context

- Repository name
- Branch
- Commit range
- Changed files
- Module ownership
- Dependency references
- API references
- Test locations

### Pull Request

- PR ID
- Title
- Summary
- Diff
- Review comments
- Checks
- Linked tickets
- Reviewers
- Risk file
- Evidence pack

### Risk File

- Change summary
- Impact areas
- Risk level
- Security findings
- Compliance flags
- Test evidence
- Rollback notes
- Approval status
- Residual risk

### Evidence Pack

- Ticket summary
- Impact graph summary
- Cited historical evidence
- Architecture rationale
- Test plan
- Validation results
- Reviewer routing
- Release note
- Audit summary

### Agent Policy

- Agent name
- Role
- Allowed inputs
- Allowed tools
- Allowed actions
- Required approvals
- Logging rules
- Stop conditions

## Minimum MVP Data Set

For the PR Evidence Pack Agent, the minimum useful data set is:

- Ticket text
- Repository diff
- Git history
- PR history
- Test command or CI status
- Ownership metadata
- Basic compliance taxonomy

## Data Quality Requirements

CEAP should mark findings as low confidence when:

- Source data is missing
- Linked tickets are incomplete
- Ownership metadata is stale
- Compliance rules are not configured
- Tests cannot be executed
- External system state cannot be verified
