# CEAP Plugin Codex Repository

This repository contains the CEAP Codex plugin under [`ceap/`](ceap/).

CEAP is an Enterprise AI Agentic Engineering Platform plugin for Codex. It supports governed ticket-to-code workflows, AI impact analysis, regulated evidence packs, policy-bound agents, enterprise engineering memory, AI USP strategy, and release decision support.

## Repository Layout

- [`ceap/`](ceap/): Installable Codex plugin directory.
- [`ceap/.codex-plugin/plugin.json`](ceap/.codex-plugin/plugin.json): Plugin manifest.
- [`ceap/skills/`](ceap/skills/): Codex skills included in the plugin.
- [`ceap/docs/`](ceap/docs/): Complete US-English plugin documentation.
- [`CEAP-prd_codex_engineering_agent_plugin.md`](CEAP-prd_codex_engineering_agent_plugin.md): Original product description used to build the plugin.

## Start Here

- [Plugin README](ceap/README.md)
- [Documentation Index](docs/index.md)
- [Plugin Documentation Index](ceap/docs/index.md)
- [AI USP Backlog](ceap/docs/ai-ki-usps.md)
- [MVP Roadmap](ceap/docs/mvp-roadmap.md)
- [Validation Guide](ceap/docs/validation-guide.md)

## Included Plugin Skills

- `ceap-engineering-orchestrator`
- `ceap-quality-governance`
- `ceap-enterprise-context`
- `ceap-agent-operations`
- `ceap-ai-usp-engine`

## Validation

Run the local plugin validator:

```powershell
python 'C:\Users\reinerw\.codex\skills\.system\plugin-creator\scripts\validate_plugin.py' 'D:\temp\CEAP-Plugin-Codex\ceap'
```

Expected result:

```text
Plugin validation passed: D:\temp\CEAP-Plugin-Codex\ceap
```

## Distribution Status

The plugin is valid as a local Codex plugin directory. For Codex UI marketplace-style installation, add a personal or team marketplace entry that points to the `ceap/` plugin directory.
