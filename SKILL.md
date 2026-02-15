---
name: shaping
description: Shaping + breadboarding workflows, with durable on-disk docs.
---

# Shaping (Index)

Use these skills to shape a feature/spec collaboratively and keep the artifacts durable.

## Persistence (Critical)

Do not rely on the chat transcript as the only source of truth.

- At the start of a shaping/breadboarding session, choose a doc path in the repo and write the evolving tables there.
- Default suggestion: `docs/shaping/<feature>.md` (and optionally `docs/shaping/<feature>-implementation.md`).
- Update the doc after each major change (requirements, shapes, fit checks, breadboards, slices).

## Default behavior

If the user invoked `/shaping`, follow the full shaping methodology (as described in `shaping/shaping`) by default.

Switch to:
- `shaping/breadboarding` when you need to map a workflow into affordance tables/wiring or slice a breadboard.
- `shaping/breadboard-reflection` when you need to review/fix a breadboard.

## Skills

- Use `shaping/shaping` for the shaping methodology (requirements, shapes, fit checks, slices).
- Use `shaping/breadboarding` for affordance tables and wiring.
- Use `shaping/breadboard-reflection` to review a breadboard for design smells.
