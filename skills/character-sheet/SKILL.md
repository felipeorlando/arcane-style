---
name: arcane-character-sheet
description: >-
  Art-direct a still character bible or poster plate in a half-painted,
  half-solid ink style: brush title, action hero, front/side/back turnaround,
  detail callouts, color chips, and a short tagline. Use for original
  characters, model sheets, and the still plate that sits under a scene.
  Skip for photoreal portraits, smooth family-film 3D, and shot design
  (use the cinematic-scene skill for motion).
---

# Character sheet

Build an original character as a print-ready sheet on a white field. The picture should read in one glance: who they are, what they do, and which few colors they own.

The render is half illustration and half solid form. Skin and hair are painted in a few tones with a drawn eye. The body, cloth, and props have volume, perspective, and a hard shadow edge. A thick dark contour holds the silhouette together.

## Choose a layout

Use the **bible** for a character who will be drawn again or animated. Use the **poster** for a single campaign frame, a pair, or a lineup. Both share type, splash, palette, and render. Only the poster drops the turnaround and the callouts.

### Bible (default)

Wide white canvas, three columns, generous margins.

1. **Left, the hero.** The name sits top left in a large dry-brush display, in the accent color, with rough edges and slight wear. Under it, one line of small tracked capitals: `ROLE / PLACE`. The figure is large, cropped around mid-thigh, caught mid-action, with the signature prop in hand. Behind the figure only, a watercolor and ink splash in the accent fades out to white. No box and no border. When the place matters, lay a loose gouache plate of that place under the splash (a street, a court, a kitchen glow) and let it bleed into the white.
2. **Center, the turnaround.** A tiny tracked label, `TURNAROUND`, with a short rule. Three full-body views stand on one ground line: front, side, back. Neutral face, same costume, same proportions, feet planted. Pure white behind them. Props stay in the hands only when they are part of the body read; otherwise put the prop in its own row underneath, isolated on white, with a small-caps label (`THE BIKE`, `ROPE`, `BALLS`).
3. **Right, the details.** A tiny tracked label, `DETAILS`. Four tight callouts, as a 2×2 or a vertical stack: the face, the eye or the hair, one garment construction (collar, knot, cuff, sole), and the prop or the shoe. Optional one-line captions in small caps. Under them, four or five flat chips labeled `COLOR PALETTE`.
4. **Tagline.** Two to six words, in the accent, either dry-brush or small caps between thin rules. Place it in the remaining white, usually under the turnaround or at the bottom right. One tagline only.

### Poster

Same white field, same brush name, same splash, same chips when there is room. The figure is a dramatic crop from mid-thigh up. No turnaround and no callout grid.

- **Solo.** Figure centered. Name top left. A short stacked creed on the left (three fragments). A worn display word and a one-line tagline along the bottom.
- **Split.** Two halves. Each side gets its own name, role line, figure, and splash color. The center is a large brush word (`VS` for a clash, or the shared title for a partnership) plus a small place line. Chips and one tagline sit at the bottom center.
- **Lineup.** Several figures shoulder to shoulder, one of them a half-step forward. Brush title across the top, a small `PLACE / TIME / GROUP` line under it, tagline along the bottom. Shared splash behind the group.

## Render

- **Line.** Dark contour, thick enough to read at thumbnail size. On a bible the weight can vary, heavier on the silhouette, lighter inside the face. On a poster the contour is heavier and more even.
- **Face.** Two or three skin tones. One hard shadow shape under the brow, nose, and jaw. A glossy iris with a single catchlight. Hair as ink clumps and a few flyaway strokes. Expression is specific and held, not a generic smile.
- **Body and cloth.** Chunky, readable masses. Flat local color. Folds are hard-edged shadow shapes, plus an occasional white slash for a highlight. Anatomy is athletic and clear, with hands that can grip a prop.
- **Materials.** Metal and wet surfaces get a simple specular and a dark core. Leather is a broad highlight on a flat base. Fabric stays matte. Props are slightly more dimensional than the cloth, and still outlined.
- **Splash.** Watercolor blooms, dry-brush streaks, and ink spatters. Color is densest behind the torso and dies before the edge of the canvas. The white field stays white.
- **Type.** One brush display, one small-caps role line, tiny section labels, one short tagline. No paragraphs. No fake logos.
- **Palette.** Four or five colors. Usually a near-black, an off-white, one accent, one warm neutral, and one color taken from the place (sky, lantern gold, night blue). The accent is the brush name, the splash, and the tagline.

## Prompt

Fill the braces. Leave brand names, actors, and existing characters out of the braces.

```text
Print-ready character bible, wide white canvas, three columns, generous margins.

LEFT: Large dry-brush name "{NAME}" in {ACCENT}, top left, slightly worn. Under it, small tracked capitals: {ROLE} / {PLACE}. One large figure cropped around mid-thigh, mid-action: {ACTION}, signature prop {PROP} in hand. Behind the figure only, a {ACCENT} watercolor-and-ink splash that fades to white, no frame. Optional loose gouache plate of {PLACE} bleeding into the white.

CENTER: Small tracked label TURNAROUND with a short rule. Three full-body views on one ground line — front, side, back — neutral face, identical costume, pure white background. Under them, {PROP} isolated on white with a small-caps label, if it is not already in the hands.

RIGHT: Small tracked label DETAILS. Four tight callouts: face, eye or hair, one garment detail, the prop or the shoe. Four or five flat chips labeled COLOR PALETTE: {PALETTE}.

Tagline, two to six words, in {ACCENT}: {TAGLINE}.

Render: painted face with solid volume, two or three skin tones, hard-edged shadow, single catchlight, hair as ink clumps. Thick dark contour. Flat color blocks on cloth, simple specular on metal. Hand-painted texture, fine grain, chunky readable forms. White field stays white.

Original person only. No celebrity likeness, no existing film, series, or game character, no brand logos.
```

Poster solo, when the turnaround is not wanted:

```text
Print-ready poster on a clean white field. One original figure centered, cropped around mid-thigh, {ACTION}, prop {PROP}. Large dry-brush name "{NAME}" top left in {ACCENT}. Small tracked capitals under it: {ROLE} / {PLACE}. Three short stacked fragments on the left. A worn display word and a one-line tagline along the bottom. {ACCENT} watercolor-and-ink splash behind the torso, fading to white. Palette chips if there is room: {PALETTE}. Thick dark contour, flat color blocks, hard-edged shadows, painted face with a single catchlight, hand-painted texture, fine grain. Original person only. No celebrity likeness, no existing character, no logos.
```

## Exclusions

Leave out photoreal pores, smooth plastic family-film shading, chibi proportions, thin fashion-sketch line, busy infographic boxes, and any name or face that already belongs to someone.

## What this is based on

Stills were looked at directly. Dates are the post dates. The prompt blocks above are a fresh template, not a copy of any caption.

**Supplied bibles (names were not found in the post searches).** Six wide sheets, same skeleton: brush name, `ROLE / PLACE`, action hero over a painted place and a colored splash, `TURNAROUND` front/side/back on white, a 2×2 `DETAILS` block (face, eye, hair or garment, prop), an isolated object on some of them (bike, rope, balls, sash, necklace), four or five chips, short tagline. Subjects were a BMX rider, a jump-rope athlete, a bar athlete, a capoeira dancer, a breakdancer, and a street juggler. These are the softer, more gouache end of the look: painted skin, pressure in the line, architecture suggested in watercolor. The breakdancer chips are brush swatches; the others are flat blocks. Use the layout. Do not reuse the people.

**Supplied poster contact.** A 3×3 of poster plates in the white-field splash family (solo and split). One cell is blurred. Used as layout evidence only.

**Public bibles, same three columns.**

- 22 Sep 2026, kitchen lead with a pan and a knife: [post](https://x.com/TechieBySA/status/2102356370188026095). Hero left, three neutral views, four detail crops, four chips, brush tagline bottom right. Splash is red and black. Turnaround props stay in the hands.
- 7 Sep 2026, barista mid-pour: [post](https://x.com/TechieBySA/status/2096967425132556778). Brown-gold splash, tagline under the hero, chips centered, details are face, apron knot, cuff, shoe.
- 7 Sep 2026, driver with earphones: [post](https://x.com/TechieBySA/status/2096919376792256967). Red splash, seated hero, standing turnaround, labeled detail stack, chips bottom right.
- 6 Sep 2026, chef with a knife pointed out: [post](https://x.com/TechieBySA/status/2096556627927220697). Red-gold splash, three standing views, vertical labeled details, centered tagline.

**Public posters, same render, no turnaround.** 28–30 Sep 2026: solo plates on [30 Sep](https://x.com/TechieBySA/status/2105307488744571211) and [29 Sep](https://x.com/TechieBySA/status/2104944751766065348), split plates on [30 Sep](https://x.com/TechieBySA/status/2105256780565492165), [28 Sep](https://x.com/TechieBySA/status/2104623035009347974), and [28 Sep](https://x.com/TechieBySA/status/2104581957145207293), lineup on [29 Sep](https://x.com/TechieBySA/status/2104896373321507030). Heavier even contour, harder cel shading, figure cropped mid-thigh, splash or a graphic motif behind the torso.

**Prompt and picture can diverge.** On 2 Sep 2026 the text asked for a turnaround with close-ups. The images on those posts are posters: a duo plate ([post](https://x.com/TechieBySA/status/2095158505187459367)) and a four-figure lineup with a place plate ([post](https://x.com/TechieBySA/status/2095111018087072099)). Trust the layout you ask for, and check the picture.

The bible is the stable sheet for a new character. The poster is the campaign frame, and it is also the plate held under the square clips described in the cinematic-scene skill.
