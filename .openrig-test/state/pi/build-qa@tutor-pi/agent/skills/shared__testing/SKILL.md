---
name: testing
description: One concern per change; run the test that proves it; report exactly what passed.
---
# Testing discipline

- Before claiming "done", run the test that proves it (e.g.
  `python -m <pkg>.<test>`), and report the exact command + result.
- **One concern per change.** Never mix a refactor with a behavior change.
- When adding a capability, add the test that would fail without it.
- Unrun does not mean passing: say `unverified` and why.
