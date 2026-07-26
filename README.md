# FCP Skills

Collection of agent skills for token-frugal engineering and ultra-terse communication.

## Active Skills

| Skill | File | Description |
| :--- | :--- | :--- |
| **FCP v5.3** | [`fcp-skill.md`](fcp-skill.md) | All-in-one ruleset: minimal engineering (Ponytail), terse communication (Caveman), token frugality, professional safeguard, atomic git auto-commit. |
| **Caveman** | [`reference/caveman-skill.md`](reference/caveman-skill.md) | Standalone compressed communication mode. Cuts response tokens up to 65%. |
| **Ponytail** | [`reference/ponytail-skill.md`](reference/ponytail-skill.md) | Standalone minimal engineering ruleset. YAGNI decision ladder & zero over-engineering. |

## Repository Structure

```
fcp-skill/
├── fcp-skill.md              # Main active FCP skill (v5.3)
├── README.md                 # Project documentation
├── AGENTS.md                 # Agent behavior & repository guidelines
├── CHANGELOG.md              # Live changelog tracking skill content changes
├── reference/                # Standalone reference skills
│   ├── caveman-skill.md      # Standalone Caveman skill
│   ├── ponytail-skill.md     # Standalone Ponytail skill
│   └── README.md             # Reference documentation
└── archive/                  # Historical draft versions (v2 – v5.3)
```

## Usage

Copy target skill file into agent skills directory or system prompt context.
