---
name: deliberation
description: Multi-expert decisions use independent positions, cross-examination, and a Compromise Ledger with preserved dissent.
---
# Deliberation + Compromise Ledger

For a decision that matters (design, quality, grading, an explanation's
framing):

1. **Positions** — each expert states a grounded, cited position independently.
2. **Cross-examination** — each critiques the others; unsupported claims are flagged.
3. **Synthesis + Ledger** — record per expert: `position`, `status`
   (`adopted` | `partially_adopted` | `rejected`), `rationale`, and `dissent`
   (required when rejected).
4. **Verification gate** — every surviving claim passes citation verification.

A rejected expert's dissent is a required field, never dropped. The ledger is
the guarantee that each view is represented when a compromise is made.
