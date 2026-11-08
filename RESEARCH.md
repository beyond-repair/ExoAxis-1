# RESEARCH lock — ExoAxis-1 (Sweep-085 / Sweep-700 recheck)

**Classification:** RESEARCH  
**Sweep:** 085 (initial) / 700 (recheck)  
**Tree SHA at audit:** `6cef3bc031d0345e262d00a97703ce2488511537`  
**Evidence date:** 2026-11-08

## What exists (verified)

| Artifact | State |
|----------|-------|
| README.md | VERIFIED present (conceptual architecture + claim-capped scope) |
| LICENSE (CC-BY-4.0) | VERIFIED present |
| RESEARCH.md | VERIFIED present |
| `.github/workflows/ci.yml` | VERIFIED present (docs-only presence check; not pharmacology validation) |
| Source code / models / data | ABSENT |
| Tests (pharmacology) | ABSENT |
| Releases / tags | ABSENT (`[]`) |
| Dependabot open alerts | 0 |
| Branches | `main` only |

## What must not be claimed

| Capability | State |
|------------|-------|
| Conceptual conjugate architecture (A/B/C domains) | VERIFIED as prose only |
| Network-pharmacology implementation | PLANNED / UNVERIFIED (no code) |
| Clinical efficacy, safety, dosing | FORBIDDEN |
| Synthesis, CMC, enabling chemical recipes | FORBIDDEN |
| Regulatory completeness | FORBIDDEN |
| Product / ACTIVE lifecycle | FALSIFIED (docs-only tree + presence CI) |
| CI green as experimental validation | FORBIDDEN (docs-ci is presence only) |

## Justification

Live tree contains README, RESEARCH.md, LICENSE, and a minimal docs-ci workflow that asserts docs-only structure. No executable pharmacology surface. Independent of agent runtimes and game prototypes.

Not SUPERSEDED: no replacement implementation exists in the portfolio.
Not ARCHIVED: open-science rationale retained.
Not ACTIVE: no pharmacology tests, no demonstrated software implementation. Docs-ci does not elevate claim.

## Operator notes

Do not add synthesis instructions, dose tables, or manufacturing content.
Do not invent a code tree to satisfy completeness optics.
Presence CI is not claim elevation.

## Prior Sweep-257 recheck preserved

Pre-sweep head `72957022135437a6782c126f62f5fc7b46508c9f` still had README, RESEARCH.md, and LICENSE only. No `src`. No dose or synthesis file. Sweep-085 lock retained. Later addition of docs-ci is presence-only.
