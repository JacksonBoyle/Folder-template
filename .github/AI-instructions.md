# Repo Instructions

This repo contains a multi-language utility suite (`HotKey-CMD`) featuring AutoHotkey (AHK) automation scripts, PowerShell deployment tools, and Python backend scripts designed to streamline workflow tasks.

## Repository Priorities

1. Maintain accurate and up-to-date architecture documentation.
2. Keep metadata accurate and up to date.
3. Explain dependencies explicitly between tools and components.
4. Update the README whenever functionality changes.
5. Favor maintainability, readability, and documentation over clever or overly complex code.
6. Minimize duplicate logic and promote modular, reusable scripts.
7. Consider the needs of end-users (who may not be software developers).

## Repository Structure

- `source/` — Contains primary source code and scripts.
- `docs/` — Contains user and technical documentation.
- `metadata/` — Contains machine-readable project information.
- `tests/` — Contains automated test assets and validation scripts.
- `examples/` — Contains sample files and usage examples.
- `releases/` — Contains packaged, distributable artifacts.

## Documentation Requirements

When functionality changes, ensure the following are updated:

- `README.md`
- `CHANGELOG.md`
- `ARCHITECTURE.md` (if system behavior or design patterns change)
- `DATAFLOW.md` (if inputs, outputs, or file dependencies change)
- Document any new dependencies clearly.
- Document breaking changes explicitly.

## Architecture Expectations

Document the following core elements clearly:
- Inputs
- Outputs
- Dataflow mechanics
- External system interactions
- File and path dependencies
- User interactions and triggers

*Preference: Use clear workflow descriptions and diagrams where applicable.*

## AI Guidance

Before proposing major changes or edits:

- Review existing architecture documentation.
- Preserve backwards compatibility whenever practical.
- Explain tradeoffs clearly in your response.
- Suggest documentation updates when appropriate.
- Consider how changes affect maintainability, deployment ease, and future users.
