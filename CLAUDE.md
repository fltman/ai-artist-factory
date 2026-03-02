# AI Artist Factory

An experiment: can AI agents create a fictional music artist that builds a real audience — without anyone knowing it's AI?

## How It Works

We don't pre-decide genre, aesthetic, or audience. Research skills analyze the market, creative skills brainstorm concepts from data, production skills execute everything.

```
Phase 1: RESEARCH    → 4 skills analyze music, social, culture, market gaps
Phase 2: CONCEPT     → brainstorm creates concepts, concept-writer builds the bible
Phase 3: DECISION    → Pick the strongest concept
Phase 4: PRODUCTION  → 7 skills execute: music, images, content, social, marketing, web
Phase 5: ITERATE     → Research keeps monitoring, manager adjusts
```

## The Tour Hack

The artist does exclusive invite-only events. No phones allowed. AI-generated event photos posted afterward. FOMO-driven engagement.

## Project Layout

- `CLAUDE.md` — You are here. Project-wide conventions.
- `.claude/skills/` — All agent skills (research, creative, production)
- `docs/concept-bible.md` — The chosen artist (generated in Phase 2)
- `docs/project-status.md` — Living status tracker (maintained by production-manager)
- `docs/briefs/` — Task briefs from manager to other skills
- `outputs/research/` — Trend reports from research skills
- `outputs/concepts/` — Artist concepts from brainstorm skill
- `outputs/production/` — All produced content (music, images, content, web)

## External Skill Dependencies

Install before production phase:
- Suno Music: `https://github.com/fltman/claude-code-suno-musicgen-skill`
- Image Gen: `https://github.com/fltman/claude-code-imagegen-skill`

## Guiding Principles

1. **Data over taste.** Research determines the concept, not personal preference.
2. **Broad over niche.** The experiment needs real engagement at scale.
3. **Authentic feel.** Must feel like a real artist, not a marketing exercise.
4. **Mystery over transparency.** Audience shouldn't know it's AI.
5. **The tour hack is core.** Invite-only events with AI-generated photos.
6. **Iterate.** Research flags changes, manager adjusts strategy.
