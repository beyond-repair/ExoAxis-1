# RESEARCH lock — ExoAxis-1 (Sweep-085)

**Classification:** RESEARCH  
**Sweep:** 085  
**Tree SHA at audit:** `65d9878f6c5400c7adb70f62c83b78b5609fa6a4`  
**Evidence date:** 2026-09-06

## What exists (verified)

| Artifact | State |
|----------|-------|
| README.md | VERIFIED present (conceptual architecture + claim-capped scope) |
| LICENSE (CC-BY-4.0) | VERIFIED present |
| Source code / models / data | ABSENT |
| Tests | ABSENT |
| `.github/workflows` | ABSENT (Actions `total_count=0`) |
| Releases / tags | ABSENT (`[]`) |
| Branches | `main` only |

## What must not be claimed

| Capability | State |
|------------|-------|
| Conceptual conjugate architecture (A/B/C domains) | VERIFIED as prose only |
| Network-pharmacology implementation | PLANNED / UNVERIFIED (no code) |
| Clinical efficacy, safety, dosing | FORBIDDEN |
| Synthesis, CMC, enabling chemical recipes | FORBIDDEN |
| Regulatory completeness | FORBIDDEN |
| Product / ACTIVE lifecycle | FALSIFIED (docs-only tree) |

## Justification

Live tree contains two blobs. No executable surface. Census metadata already marks cluster HEALTH / METADATA_ONLY. Independent of agent runtimes and game prototypes.

Not SUPERSEDED: no replacement implementation exists in the portfolio.
Not ARCHIVED: open-science rationale retained.
Not ACTIVE: no CI, tests, or demonstrated software.

## Operator notes

Do not add synthesis instructions, dose tables, or manufacturing content.
Do not invent a code tree to satisfy completeness optics.

## Sweep-257 recheck (2026-10-06)

Pre-sweep head `72957022135437a6782c126f62f5fc7b46508c9f` still had README, RESEARCH.md, and LICENSE only. No `src`. No dose or synthesis file. Sweep-085 lock retained.

This sweep adds `.github/workflows/ci.yml` as a presence check only. A green docs-ci run is not a pharmacology implementation, not a clinical result, and not claim elevation. Classification remains RESEARCH. Claim remains ≤ 1.
