# Agent Guidelines (FCP Skills)

Repository operating rules for AI agents.

## Primary Skill

Active ruleset: [`SKILL.md`](SKILL.md) (v5.3).

## Maintenance Rules

- Refer to [`SKILL.md`](SKILL.md) for persona, engineering, and style governance.
- Keep [`CHANGELOG.md`](CHANGELOG.md) updated under `[Unreleased]` strictly for skill content/version changes (do not log general repository maintenance).
- Put standalone skill modules in [`reference/`](reference/).
- Move legacy drafts to [`archive/`](archive/).

## Repository Structure

```
fcp-skill/
├── SKILL.md                  # Main active FCP skill (v5.3)
├── README.md                 # Project documentation
├── AGENTS.md                 # Agent behavior & repository guidelines
├── CHANGELOG.md              # Live changelog tracking skill content changes
├── reference/                # Standalone reference skills
│   ├── caveman-skill.md      # Standalone Caveman skill
│   ├── ponytail-skill.md     # Standalone Ponytail skill
│   └── README.md             # Reference documentation
└── archive/                  # Historical draft versions (v2 – v5.3)
```
