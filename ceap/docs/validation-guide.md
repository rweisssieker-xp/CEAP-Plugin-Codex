# CEAP Validation Guide

## Plugin Validation

Run the plugin validator from the plugin-creator skill:

```powershell
python 'C:\Users\reinerw\.codex\skills\.system\plugin-creator\scripts\validate_plugin.py' 'D:\temp\CEAP-Plugin-Codex\ceap'
```

Expected result:

```text
Plugin validation passed: D:\temp\CEAP-Plugin-Codex\ceap
```

## Documentation Validation

Check that the documentation covers:

- Product purpose
- User workflows
- Skill reference
- Architecture
- Governance and security
- AI USPs
- Integration and data model
- MVP roadmap
- Validation process

## USP Validation

Every CEAP AI USP should include:

- Target user
- Pain solved
- AI mechanism
- Required data
- MVP path
- Trust controls
- Proof metric

Reject claims that are:

- Generic AI marketing
- Unmeasurable
- Not tied to a painful workflow
- Dependent on unavailable data
- Missing trust controls
- Too broad for an MVP

## MVP Readiness Checklist

- The workflow has a clear target user.
- Required inputs are available.
- Output artifacts are reviewable.
- Human approval gates are explicit.
- Risk and compliance assumptions are documented.
- Success metrics are measurable.
- Validation can be repeated.

## Release Readiness Checklist

- Plugin manifest validates.
- Skills have clear trigger descriptions.
- Documentation is in US English.
- No placeholder text remains.
- Governance limitations are explicit.
- MVP sequencing is documented.
- Risk-heavy workflows require human approval.
