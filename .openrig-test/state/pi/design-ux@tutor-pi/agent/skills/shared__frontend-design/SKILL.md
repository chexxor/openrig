---
name: frontend-design
description: Web UX/UI for the tutor app - chat-first, accessible, math-correct, and corpus-agnostic.
---
# Frontend / UX design

The product is a **chat-first web app** (FastAPI + a small JS UI). Design for
a learner, not a demo.

- **Chat-first:** the conversation is the primary surface; setup/hints/scenes
  support it, never compete with it.
- **Accessibility:** keyboard reachable, readable contrast, real labels, and
  no meaning carried by color alone. Respect reduced-motion.
- **Math & content:** notation must render correctly (MathJax); never show raw
  delimiters. Long input must wrap/grow; long output must scroll.
- **Corpus-agnostic:** no copy, branding, or layout that assumes one textbook.
- **Honest states:** loading, empty, error, and "unverified" must be visible —
  never a silent blank.
- Verify with a real browser pass, not by eyeballing CSS.
