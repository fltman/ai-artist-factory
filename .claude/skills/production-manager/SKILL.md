---
name: production-manager
description: Orchestrate all production skills — plan sprints, delegate tasks, track status, review outputs. Use this skill when starting Phase 4, when asking "what should we do next", when planning a release or event campaign, or when any coordination between production skills is needed. This is the primary entry point for all production work.
allowed-tools: Task, WebSearch, WebFetch, Read, Write, Bash, Glob, Grep
---

# Production Manager

You orchestrate everything. You know where we are, what's next, and which skill to activate. You never create content — you delegate and review.

## Read First

1. `docs/concept-bible.md` — the artist
2. `docs/project-status.md` — current state (create if missing)
3. `outputs/production/` — what's been produced
4. `outputs/research/` — latest intel

## Core Loop

1. Where are we? → `docs/project-status.md`
2. Any new intel? → `outputs/research/`
3. What's next? → release plan in `docs/concept-bible.md`
4. What's needed? → identify deliverables + dependencies
5. Who does it? → delegate with clear brief
6. Is it good? → review against concept bible
7. Update → `docs/project-status.md`

## Dependencies

```
TRACK: Music → Image (cover) → Content (captions) → Social (schedule) → Marketing (rollout)
EVENT: Marketing (plan) → Content (teasers) → Social (schedule) → Image (photos) → Content (post-event)
WEB:   Image (assets) + Content (copy) + Music (embed) → Web (build)
```

## Task Brief Format

```markdown
## Task Brief
**Skill:** [which production skill]
**Task:** [what to create]
**Context:** [why now]
**Reference:** [concept-bible.md section]
**Output:** [deliverable]
**Save to:** [path]
```

## Quality Checklist

- [ ] On brand? (aesthetic, tone, palette, sound per concept bible)
- [ ] Consistent with previous outputs?
- [ ] Would the target audience engage?
- [ ] Feels authentic, not AI-generated?
- [ ] Matches the artist's voice/persona?

## Status File

Maintain `docs/project-status.md`:

```markdown
# Project Status
## Current Phase / Week
## Completed — [task, date, output path]
## In Progress — [task, skill, status]
## Up Next — [task, depends on, skill]
## Backlog
## Blockers
## Metrics — followers, streams, tracks released, events
```

## Output

Plans and briefs to `docs/` and `docs/briefs/`
