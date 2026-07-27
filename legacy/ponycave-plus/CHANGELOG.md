# Ponycave-Plus Changelog

All notable changes and version history of the Ponycave-Plus skill ruleset.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## v6.0 (2026-07-27)
- Changed Git Auto-Commit to Git Commit Governance requiring explicit user confirmation before commit execution.
- Refined YAML metadata description and triggers list to eliminate contradictions and generic word false positives.
- Scoped `no arrows (->)` restriction strictly to response prose, permitting code syntax (TS types, pointers).
- Added concise before/after style output example in Section 1.
- Mandated rigorous zero-bug static self-review on diffs for 100% correctness, security, and safety under Section 3 Execution.

## v5.2 (2026-07-27)
- Added Conventional Commits governance.
- Defined explicit boundaries scope for commit messages.

## v5.1 (2026-07-26)
- Restored explicit `ask_question` tool governance with `(Recommended)` format.
- Restored cross-platform shell commands (`;` for PowerShell and `&&` for POSIX).
- Restored anti-micro-files rule (<50 lines).

## v5.0 (2026-07-26)
- Compressed v4 ruleset by ~58% (down to 2.8 KB) for token frugality.
- Preserved YAML header, Persistence, and Professional Guardianship.

## v4.0 (2026-07-26)
- Added YAML skill header (`name: ponycave-plus`, `description`, `license`).
- Added Persistence rules ("ACTIVE EVERY RESPONSE").
- Introduced Professional Guardianship and domain risk alerts.
- Added interactive dialog tool and `# Ponycave-Plus:` debt marking.

## v3.0 (2026-07-26)
- Added cross-platform shell examples.
- Added explicit test script naming conventions (`test-<feature>.js`).

## v2.1 (2026-07-26)
- Introduced initial cross-platform shell support.
- Added initial anti-micro-files restriction.

## v2.0 (2026-07-26)
- Added scope-based architecture (Bug fix vs New feature).
- Unified output templates.

## v1.0 (2026-07-26)
- Initial release of core pillars.

