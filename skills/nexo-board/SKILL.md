---
name: nexo-board
description: Nexo Apps' user-facing alias for the super-board application factory. Use when the user says "nexo-board", "/nexo-board", or asks to onboard, lint, inspect, run, or stop the Nexo Apps application factory.
---

# nexo-board — Nexo Apps application factory

This is the public Nexo Apps name for the inherited `super-board` orchestrator.
The implementation remains shared during the migration so existing projects and
installed packs keep working.

Map the command directly to the inherited orchestrator:

```text
/nexo-board onboard  → /super-board onboard
/nexo-board lint     → /super-board lint
/nexo-board status   → /super-board status
/nexo-board run      → /super-board run
/nexo-board stop     → /super-board stop
```

Before acting, read `skills/super-board/SKILL.md` and the matching reference
under `skills/super-board/references/`. Preserve the inherited state paths and
scripts until the migration is complete. Report the user-facing command as
`/nexo-board`; do not ask the user to know the compatibility name.
