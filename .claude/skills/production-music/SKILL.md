---
name: production-music
description: Generate Suno-ready song packages (300-character style description + tagged lyrics) for the AI artist. Use this skill when creating new tracks, when the manager delegates music production, or when anyone asks to generate music for the artist. Requires the Suno music skill to be installed. Always read docs/concept-bible.md first for sound profile.
allowed-tools: Read, Write, Bash
---

# Music Production

Create Suno-ready song packages. Read `docs/concept-bible.md` → "Genre & Sound" + "For the Music Agent" sections first.

## Output Per Track

### 1. Style Description (exactly 300 characters)
One paragraph: genre, subgenre, mood, tempo, instruments, vocal style, atmosphere.

### 2. Tagged Lyrics
Structure: `[Intro]`, `[Verse]`, `[Pre-Chorus]`, `[Chorus]`, `[Bridge]`, `[Outro]`, `[Instrumental Break]`, `[Drop]`
Vocals: `[Male Vocal]`, `[Female Vocal]`, `[Whispered]`, `[Spoken Word]`, `[Harmony]`, `[Ad-lib]`

## Rules

- ALL creative decisions from concept bible. Don't improvise genre/style.
- Track titles follow concept bible naming convention.
- Lyrics match voice, themes, language rules from concept bible.
- Every track must feel like the SAME artist.

## Output

Save to `outputs/production/music/[trackname]-suno-package.md`
