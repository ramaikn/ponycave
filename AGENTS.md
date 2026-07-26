# Agent Guidelines (FCP & Ponycave Skills)

Repository operating rules for AI agents.

## Primary Skills

Active rulesets:
- [`FCP.md`](FCP.md) (v5.3): All-in-one ruleset with professional safeguards and git auto-commit governance.
- [`PONYCAVE.md`](PONYCAVE.md) (v1.0): Pure Ponytail + Caveman ruleset without extra custom rules.

## Maintenance Rules

- Refer to [`FCP.md`](FCP.md) or [`PONYCAVE.md`](PONYCAVE.md) for persona, engineering, and style governance.
- Keep [`CHANGELOG.md`](CHANGELOG.md) updated under `[Unreleased]` strictly for skill content/version changes (do not log general repository maintenance).
- Place version documentation in [`legacy/`](legacy/) under `legacy/fcp/` and `legacy/ponycave/`.

## Repository Structure

```
fcp-skill/
├── FCP.md                    # Main active FCP skill (v5.3)
├── PONYCAVE.md               # Main active Ponycave skill (v1.0)
├── README.md                 # Project documentation
├── AGENTS.md                 # Agent behavior & repository guidelines
├── CHANGELOG.md              # Live changelog tracking skill content changes
└── legacy/                   # Version history & legacy documentation
    ├── fcp/                  # FCP version history (v2.0 – v5.3)
    └── ponycave/             # Ponycave version history (v1.0)
```
