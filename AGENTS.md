# Agent Guidelines (Ponycave & Ponycave-Plus Skills)

Repository operating rules for AI agents.

## Primary Skills

Active rulesets:
- [`PONYCAVE-PLUS.md`](PONYCAVE-PLUS.md): All-in-one ruleset with professional safeguards, domain standards, and git commit governance.
- [`PONYCAVE.md`](PONYCAVE.md): Pure Ponytail + Caveman ruleset without extra custom rules.

## Maintenance Rules

- Refer to [`PONYCAVE-PLUS.md`](PONYCAVE-PLUS.md) or [`PONYCAVE.md`](PONYCAVE.md) for persona, engineering, and style governance.
- Keep [`CHANGELOG.md`](CHANGELOG.md) updated under `[Unreleased]` strictly for skill content/version changes (do not log general repository maintenance).
- Place version documentation in [`legacy/`](legacy/) under `legacy/ponycave-plus/` and `legacy/ponycave/`.

## Repository Structure

```
ponycave-skill/
├── PONYCAVE-PLUS.md              # Main active Ponycave-Plus skill
├── PONYCAVE.md               # Main active Ponycave skill
├── README.md                 # Project documentation
├── AGENTS.md                 # Agent behavior & repository guidelines
├── CHANGELOG.md              # Live changelog tracking skill content changes
└── legacy/                   # Version history & legacy documentation
    ├── ponycave-plus/        # Ponycave-Plus version history
    └── ponycave/             # Ponycave version history
```

