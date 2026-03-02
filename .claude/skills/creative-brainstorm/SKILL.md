---
name: creative-brainstorm
description: Synthesize research reports into 3-5 concrete, ranked artist concepts for the AI artist factory. Use this skill after all research skills have produced their reports (Phase 2), when you need to generate artist concepts from data, or when the manager requests new concept ideas. Every idea must be grounded in research data, not personal taste.
allowed-tools: WebSearch, WebFetch, Read, Write, Bash
---

# Brainstorm — Artist Concept Generator

Take all research from `outputs/research/` and synthesize it into 3-5 concrete artist concepts. Every idea must be GROUNDED in data. No "wouldn't it be cool if" — only "the data says this would work because."

## Process

1. Read ALL reports in `outputs/research/`
2. Extract top 5 insights from each
3. Map intersections where multiple trends converge
4. Develop a full concept for each promising intersection
5. Stress-test: AI-feasible? Broad enough? Authentic-feeling?
6. Rank with clear rationale

## What Makes a Strong Concept

Must score high on ALL: audience breadth, cultural resonance, AI feasibility (Suno + image gen), authenticity, shareability, mystery potential, visual identity, tour hack compatibility, content engine sustainability, differentiation.

## Concept Format

For each concept:

```markdown
## Concept [N]: [Artist Name]

### Elevator Pitch
[2 sentences max]

### Data Case
[Why research says this works. Cite specific findings.]

### Artist Profile
- Name: [+ reasoning]
- Genre: [primary + sub]
- Origin: [where "from" + why it matters]
- Persona: [archetype]
- Aesthetic: [visual world]
- Sound in 3 words:

### Target Audience
- Primary: [demo, interests, platforms]
- Secondary: [adjacent audiences]
- Size estimate:

### Why This Works
- Music trend fit:
- Social strategy:
- Cultural hook:
- Market position:

### Why This Could Fail
[Honest risks]

### AI Feasibility
- Music (Suno): [1-10]
- Visuals (image gen): [1-10]
- Text content: [1-10]
- Biggest exposure risk:

### Sample Content
- First track concept:
- First Instagram post:
- Origin story seed:

### Tour Hack Fit
[How invite-only events work for this artist]

### Gap Score
| Dimension | Score | Notes |
|-----------|-------|-------|
| Demand | | |
| Supply | | |
| AI Fit | | |
| Virality | | |
| Breadth | | |
| Feasibility | | |
| Longevity | | |
```

## Final Ranking

End with clear 1st/2nd/3rd choice with rationale. Make a decisive recommendation — don't hedge.

## Rules

1. No genre snobbery. Pop is valid if the data supports it.
2. Global thinking. Don't default to US/EU only.
3. Platform-native. Born for platforms, not adapted to them.
4. Name matters. Memorable, searchable, fits the aesthetic.

## Output

Save to `outputs/concepts/brainstorm-[date].md`
