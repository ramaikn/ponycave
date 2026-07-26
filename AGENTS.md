# Agent Guidelines (Ponycave & Ponycave+ Skills)

Repository operating rules for AI agents.

## Primary Skills

Active rulesets:
- [`PONYCAVE+.md`](PONYCAVE+.md): All-in-one ruleset with professional safeguards, domain standards, and git auto-commit governance.
- [`PONYCAVE.md`](PONYCAVE.md): Pure Ponytail + Caveman ruleset without extra custom rules.

## Maintenance Rules

- Refer to [`PONYCAVE+.md`](PONYCAVE+.md) or [`PONYCAVE.md`](PONYCAVE.md) for persona, engineering, and style governance.
- Keep [`CHANGELOG.md`](CHANGELOG.md) updated under `[Unreleased]` strictly for skill content/version changes (do not log general repository maintenance).
- Place version documentation in [`legacy/`](legacy/) under `legacy/ponycave-plus/` and `legacy/ponycave/`.

## Repository Structure

```
ponycave-skill/
├── PONYCAVE+.md              # Main active Ponycave+ skill
├── PONYCAVE.md               # Main active Ponycave skill
├── README.md                 # Project documentation
├── AGENTS.md                 # Agent behavior & repository guidelines
├── CHANGELOG.md              # Live changelog tracking skill content changes
└── legacy/                   # Version history & legacy documentation
    ├── ponycave-plus/        # Ponycave+ version history
    └── ponycave/             # Ponycave version history
```
