# AI Artist Factory

> Can AI build a music artist that people believe is real?

## The Experiment

Create a fully AI-generated fictional music artist. Music, visuals, social media, biography, "live events" — all produced by AI. The concept isn't pre-decided; research skills analyze the market and creative skills brainstorm the optimal concept from data.

### The Tour Hack
Exclusive invite-only events. No phones allowed. AI-generated "event photos" posted afterward. Nobody can prove the events happened. Nobody can prove they didn't.

## Setup

```bash
# Install external dependencies
claude skill install https://github.com/fltman/claude-code-suno-musicgen-skill
claude skill install https://github.com/fltman/claude-code-imagegen-skill

cd ai-artist-factory
claude
```

## Quick Start

```
> Use the research-music-trends skill to research what's working
> Use the research-social-trends skill to analyze platforms
> Use the research-cultural-trends skill to read the moment
> Use the research-market-gaps skill to find whitespace
> Use the creative-brainstorm skill to generate artist concepts
> [Pick a concept]
> Use the creative-concept-writer skill to build the concept bible
> Use the production-manager skill to plan Sprint 1
```

## Skills (in `.claude/skills/`)

### Research (Phase 1)
| Skill | Purpose |
|-------|---------|
| `research-music-trends` | Genres, virality, platforms, AI feasibility |
| `research-social-trends` | Algorithms, formats, aesthetics, growth |
| `research-cultural-trends` | Zeitgeist, emotions, movements, narratives |
| `research-market-gaps` | Underserved audiences, whitespace, intersections |

### Creative (Phase 2)
| Skill | Purpose |
|-------|---------|
| `creative-brainstorm` | Synthesize research → 3-5 ranked concepts |
| `creative-concept-writer` | Chosen concept → production-ready bible |

### Production (Phase 4)
| Skill | Purpose |
|-------|---------|
| `production-manager` | Orchestrate, plan, delegate, review |
| `production-music` | Suno packages (style + lyrics) |
| `production-image` | All visual assets |
| `production-content` | All text content |
| `production-social` | Content calendars & scheduling |
| `production-marketing` | Strategy, growth, PR |
| `production-web` | Website & platform profiles |
