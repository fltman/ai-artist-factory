---
name: creative-concept-writer
description: Turn a chosen artist concept into a complete, production-ready concept bible at docs/concept-bible.md. Use this skill after the brainstorm skill has produced concepts and one has been selected (Phase 2 completion), or when the manager needs an updated concept bible. The bible must be detailed enough that any production skill can create on-brand content without additional guidance.
allowed-tools: WebSearch, WebFetch, Read, Write, Bash
---

# Concept Writer — Build the Bible

Turn the chosen concept from `outputs/concepts/brainstorm-[date].md` into a production-ready concept bible. This becomes the single source of truth for ALL production skills.

## Read First

1. The chosen concept in `outputs/concepts/`
2. All research in `outputs/research/` for supporting data
3. `CLAUDE.md` for project context

## Bible Structure

Write to `docs/concept-bible.md`:

1. **The Experiment** — Brief explanation of the AI artist project
2. **The Artist** — Identity, genre & sound (detailed: instruments, tempo, vocal approach, BPM, what it feels like, anti-references), visual identity (hex codes, fonts, composition, motifs, never-list), backstory
3. **The Tour Hack** — Event concept, invite mechanics, locations, AI photo documentation, campaign template
4. **Content Strategy** — Platforms table, content types with examples, voice & tone rules, engagement rules
5. **Production Guides** — Specific briefs for each production skill:
   - Music: sound brief, Suno template, lyric guidelines, naming conventions
   - Image: visual brief, prompt formula with examples, category guidelines
   - Content: voice guide with 10+ examples, vocabulary, platform adaptations
   - Social: schedule, platform strategies, hashtags, event templates
   - Marketing: target outlets/playlists, release cycle, growth phases, KPIs
   - Web: site design spec, CSS variables, platform profiles, EPK
6. **Release Plan** — Month 1-3 week-by-week, month 4-6 monthly, month 7-12 quarterly
7. **Success Metrics** — How we measure if it's working
8. **Ethics & Endgame** — Reveal strategy options

## Writing Rules

- **Be specific.** "Moody" is useless. "Driving alone at 2am through rain, streetlights on wet asphalt" is useful.
- **Include examples.** Every guideline needs at least one concrete example.
- **Anti-examples matter.** What NOT to do is as important as what to do.
- **Hex codes, not color names.** "#E8652E" not "warm orange."
- **Named references.** "Like Billie Eilish's Instagram" not "dark and moody."
- **Self-contained.** A skill should never need to ask "what does this mean?"

## Output

Save to `docs/concept-bible.md`
