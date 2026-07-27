# Ponycave & Ponycave-Plus Skills

The only token-saving agent rules you may need.

*A fusion of [Caveman](https://github.com/JuliusBrussee/caveman) (ultra-terse communication) and [Ponytail](https://github.com/DietrichGebert/ponytail) (minimalist engineering & YAGNI).*

## Core Philosophy

- **Simplicity & Minimalism**: Prioritizes concise communication and minimal code footprint. Unnecessary abstractions, speculative features, and verbose explanations are eliminated by default.
- **No Command Bloat**: Rejects artificial tiering and redundant command variants (e.g., `lite`, `full`, `max`). The rulesets maintain a clean, unified, and easy-to-maintain structure without unnecessary complexity.

## Active Skills

| Skill | File | Description |
| :--- | :--- | :--- |
| **Ponycave** | [`PONYCAVE.md`](PONYCAVE.md) | **Recommended for most users.** Pure ruleset: combines Ponytail + Caveman rules without custom safeguards or extra additions. |
| **Ponycave-Plus** | [`PONYCAVE-PLUS.md`](PONYCAVE-PLUS.md) | **Personal reference ruleset.** All-in-one ruleset: Ponytail + Caveman + domain safeguards, risk alerts, interactive decision scrutiny, and git commit governance. |

> [!NOTE]
> **Which Version Should You Use?**
> - **Ponycave** ([`PONYCAVE.md`](PONYCAVE.md)) is the **standard version** and likely the best fit for most people. It provides pure Ponytail (minimalist engineering & YAGNI) and Caveman (ultra-terse communication) with zero extra overhead.
> - **Ponycave-Plus** ([`PONYCAVE-PLUS.md`](PONYCAVE-PLUS.md)) is my **personal reference ruleset**. It is tailored for beginners or users without domain expertise who want the AI agent to act as a proactive, senior professional—auto-applying domain standards, flagging hidden technical/regulatory risks before code execution, scrutinizing risky decisions interactively, and managing git commit governance with explicit user confirmation.

## Usage

Copy either [`PONYCAVE.md`](PONYCAVE.md) or [`PONYCAVE-PLUS.md`](PONYCAVE-PLUS.md) into your agent skills directory or system prompt context.

## Skill Size Comparison

Comparison of file sizes and line counts across active skills and foundational reference modules:

| Metric / Attribute | **Ponytail + Caveman** | **Ponycave-Plus** | **Ponycave** |
| :--- | :--- | :--- | :--- |
| **File Size** | ~12.1 KB (12,059 B) | ~3.9 KB (3,936 B) **(67% savings)** | ~2.1 KB (2,061 B) **(83% savings)** |
| **Line Count** | 198 lines | 79 lines (60% reduction) | 54 lines (73% reduction) |
| **Scope & Focus** | Combined original reference modules | **All-in-one**: Ponytail + Caveman + safeguards + git commit governance | **Most compact**: Pure Ponytail + Caveman rules |

## Legacy & Version Documentation

Version documentation is organized in `legacy/`:
- `legacy/ponycave-plus/`: Historical drafts and version documentation for Ponycave-Plus
- `legacy/ponycave/`: Version documentation for Ponycave

## References & Credits

Foundational reference sources:

| Skill | Original Source / Credit | Description |
| :--- | :--- | :--- |
| **Caveman** | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | Reference source for ultra-terse communication mode & token reduction. |
| **Ponytail** | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | Reference source for minimalist engineering rules & YAGNI decision ladder. |
