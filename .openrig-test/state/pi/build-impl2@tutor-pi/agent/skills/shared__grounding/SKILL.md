---
name: grounding
description: Retrieve before asserting; cite the source text; never answer from model memory. Works for any textbook.
---
# Grounding discipline

- Every claim about the text must be supported by a **retrieved passage** from
  the source document(s); cite page/section.
- **Retrieve first, then write.** If retrieval does not support a claim, say
  `unverified`; never invent content or citations.
- The corpus is **pluggable**: the same discipline applies to *any* textbook.
  TAPL is only the current corpus — do not hard-code its specifics.
- Fabricated citations are the cardinal sin. If in doubt, abstain.
