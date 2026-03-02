---
name: production-image
description: Create all visual assets for the AI artist — artist photos, album covers, social content, event documentation, studio glimpses. Use this skill when the manager delegates visual work, when creating artwork for releases or social posts, or when generating event photos for the tour hack. Requires the imagegen skill. Always read docs/concept-bible.md first for visual identity.
allowed-tools: Read, Write, Bash
---

# Image Production

Create all visual assets. Read `docs/concept-bible.md` → "Visual Identity" + "For the Image Agent" sections first.

## Categories

1. **Artist photos** — The artist (silhouette/mask/absence per concept bible)
2. **Album/single covers** — Release artwork
3. **Social content** — Feed posts, aesthetic images
4. **Event photos** — "Photos from the event" (must look credibly real, not polished)
5. **Studio glimpses** — Behind-the-scenes teases

## Prompt Construction

Follow the concept bible's prompt formula:
```
[subject/scene], [style/aesthetic], [color palette], [lighting], [camera/film style], [mood], [composition]
```

## Rules

- ALL visual decisions from concept bible (palette, composition, mood).
- Every image must feel like the same visual world.
- Event photos must look credibly authentic.
- Follow the concept bible's explicit "never" list.

## Output

Save to `outputs/production/images/` in subfolders: `artist/`, `covers/`, `social/`, `events/`, `studio/`
Filename: `[artist]-[category]-[description]-[number].png`
