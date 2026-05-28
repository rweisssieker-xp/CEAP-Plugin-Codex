# CEAP Plugin Codex Repository

This repository is the CEAP Codex plugin root.

CEAP is an Enterprise AI Agentic Engineering Platform plugin for Codex. It supports governed ticket-to-code workflows, AI impact analysis, regulated evidence packs, policy-bound agents, enterprise engineering memory, AI USP strategy, and release decision support.

## Repository Layout

- [`.codex-plugin/plugin.json`](.codex-plugin/plugin.json): Plugin manifest.
- [`skills/`](skills/): Codex skills included in the plugin.
- [`docs/`](docs/): Complete US-English plugin documentation.
- [`ceap/`](ceap/): Legacy nested copy kept for compatibility with earlier repository revisions.
- [`CEAP-prd_codex_engineering_agent_plugin.md`](CEAP-prd_codex_engineering_agent_plugin.md): Original product description used to build the plugin.

## Start Here

- [Documentation Index](docs/index.md)
- [AI USP Backlog](docs/ai-ki-usps.md)
- [MVP Roadmap](docs/mvp-roadmap.md)
- [Validation Guide](docs/validation-guide.md)

## Included Plugin Skills

- `ceap-engineering-orchestrator`
- `ceap-quality-governance`
- `ceap-enterprise-context`
- `ceap-agent-operations`
- `ceap-ai-usp-engine`

## Validation

Run the local plugin validator:

```powershell
python 'C:\Users\reinerw\.codex\skills\.system\plugin-creator\scripts\validate_plugin.py' 'D:\temp\CEAP-Plugin-Codex'
```

Expected result:

```text
Plugin validation passed: D:\temp\CEAP-Plugin-Codex
```

## Distribution Status

The plugin is valid as a local Codex plugin directory. For Codex UI marketplace-style installation, add a personal or team marketplace entry that points to this repository root.
