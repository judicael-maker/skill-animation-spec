---
name: animation-spec
description: >
  Use when the Motion Designer needs to document the technical specifications of
  each animated deliverable before and after production. Used both to plan animations
  (from motion-brief) and to produce the final handoff spec for Social Media Manager.
---

# Animation spec

## Purpose
The animation spec documents exactly what was produced so Social Media Manager can deploy assets correctly without guessing formats, sizes, or loop behavior.

## Handoff format

Post as a comment when animations are complete:

```
## Animation handoff — [Project name]

All animated assets are complete. Specs below.

---

### [Asset name from manifest] (e.g., hero-video-16-9)

**File**: hero-video-16-9-v1.mp4
**Format**: MP4 H.264
**Dimensions**: 1920×1080px
**Duration**: 30s (15s cut also delivered as hero-video-16-9-short-v1.mp4)
**File size**: 42MB
**Loop**: No — fades to static end card
**Audio**: No
**Captions**: Burned in (English only)
**Color space**: sRGB

**Animation summary**:
- 0:00-0:03: Logo appears (fade in, 300ms ease-out)
- 0:03-0:12: Main product visual enters (slide from bottom, spring easing)
- 0:12-0:24: Key message reveals word by word (300ms per word, ease-in-out)
- 0:24-0:30: Static end card — logo + CTA + background

**Platform destinations**: LinkedIn, Instagram feed
**Notes**: Works best on dark backgrounds — test on light bg before LinkedIn deployment

---

[Repeat for each animated asset]

---

### Assets NOT produced (and why)
If any asset from the manifest was not animated (static only, scope change, blocked):
- [Asset name]: [reason] — [what Social Media Manager should use instead]
```

## Quality checks before handoff
- [ ] All assets loop seamlessly (if looping)
- [ ] No compression artifacts at target file size
- [ ] Text is legible at smallest deployment size
- [ ] End card is stable for at least 2 seconds (no motion)
- [ ] Captions are accurate and properly timed
- [ ] File names match the asset manifest naming convention

## Rules
- Never deliver without running the quality checklist.
- If a file exceeds the size target in the asset spec, compress further — do not deliver oversized files without a comment explaining why and asking CD for approval.
- If a Social Media Manager asks for a format not in the spec (e.g., GIF), @mention Visual Designer and CD before producing — format changes affect quality and may require reapproval.
