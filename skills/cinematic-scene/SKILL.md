---
name: arcane-cinematic-scene
description: >-
  Art-direct a short moving scene in the half-painted, half-solid ink style:
  one location, motivated light, hard cuts, weighty pose-to-pose action, and
  silhouettes that separate by color. Use after a character sheet when the
  scene must stay on-model, or alone for a 14–20 second square clip. Skip for
  photoreal footage and for smooth sunlit family-film 3D.
---

# Cinematic scene

A scene in this look is a short, square, already-in-motion clip. The camera hops between clear setups. The place stays put. Light has a source. People read as painted volumes with a dark contour, moving with weight.

Build the character with the character-sheet skill first when identity matters. The scene copies costume, proportions, prop, and palette from that sheet. It does not invent a new outfit mid-shot.

## Frame

- **Default delivery, as posted.** Square, 1:1, about 14–20 seconds, 24 frames per second. The moving shot occupies the top half (about 2:1). The bottom half is a still poster plate from the character-sheet skill, held for the whole clip. Across sampled frames the plate barely changes next to the shot, aside from compression and a little wobble. It is a reference lock, not a second scene.
- **Full-bleed delivery.** Same scene grammar, the shot filling the frame, when the plate would only get in the way. Keep the square and the duration unless the ask says otherwise.

## Camera and time

Open on the action. The first second is already a hit, a grip, a sprint, or a stance under pressure. No title card and no slow arrival.

Change setup about every one to two seconds. Sampled frames a few seconds apart are different compositions, not one continuous move. The kit is small:

- over-shoulder or a macro on the prop
- low angle looking up at the lead
- close-up on the face, with the practical light in the eyes
- medium two-shot in profile
- wide down a corridor, street, or room
- overhead that shows the floor plan and who is still standing

Hard cuts. Inside a shot, one physical event: a step, a strike, a muzzle flash, a body hitting a surface. End on a wide or an overhead that restates the place, the light, and who is left. Atmosphere is still in the last frame.

## Place, light, staging

One location for the whole clip. It can have zones (lobby then corridor, alley then roof, floor of a single room) as long as the architecture does not swap cities.

Light is motivated and graphic:

- overhead practicals with dust or smoke in the shafts
- warm lanterns and a hard shadow on the floor
- low sun, long shadows, colored walls as flat blocks
- night fire as a rim, or a single pool of spotlight for the last shot
- hard daylight and haze
- two neon hues, magenta and cyan, on haze and a reflective floor
- rain with a saturated horizon and a thin rim on wet surfaces

Stage for silhouette. The lead’s colors and the other people’s colors separate at thumbnail size: dark figure against blue uniforms, a bright tracksuit against a black suit, cream cloth against navy, black against tan. Extras are simpler and share one costume color. The signature prop stays visible and stays the same prop.

The set is a painted 3D space. Walls, floors, and streets have perspective and contact shadows. Surfaces are broad color with a little texture, not photographed detail. Debris (glass, paper, casings, dust) is there to show the hit.

## Motion and materials

Pose to pose, with weight. A walk does not bounce. A strike moves the other body and, when it should, the set: glass, dust, a torn screen, scraps in the air. Cloth folds shift as hard shapes. Hair is ink clumps, not a simulation. Metal flashes once and returns to a flat core. Faces keep the painted planes and the single catchlight while the head turns.

Avoid float, smear that hides the pose, and a new costume between cuts.

## Prompt

Fill the braces with an original person and an original place. If a sheet exists, point the model at it and repeat the costume in words.

Square composite (the posted format):

```text
Square 1:1 clip, {DURATION} seconds, 24 fps. Top half is the moving shot. Bottom half is a still character poster on white: dry-brush name, accent splash, mid-thigh crop, short tagline, same costume as the shot. The poster stays still.

One location only: {LOCATION}. Light: {LIGHT}. Keep the atmosphere in frame the whole time ({ATMOSPHERE}).

Lead: {LEAD_LOOK}. Costume colors {LEAD_COLORS}. Signature prop {PROP} always visible, same design in every shot.
Other people: {OTHER_LOOK}, colored {OTHER_COLORS} so the silhouette separates from the lead immediately.

Start already in the action: {OPENING_ACTION}. Hard cuts every one to two seconds among over-shoulder, low angle, face close-up, medium two-shot, wide, and overhead. One clear physical action inside each shot. Weighty pose-to-pose motion. Impacts move bodies and the set.

End on a wide or overhead of {LOCATION}, atmosphere still visible, showing {ENDING_STATE}.

Render: cel-shaded solid forms with hand-painted textures, thick dark outlines, hard-edged shadows, flat color blocks, fine grain. Faces are painted planes with a single catchlight. Same proportions and costume in every cut.

Original scene only. No celebrity likeness, no existing film, series, or game character, no reconstructed famous shot.
```

Full-bleed, when the plate is not wanted: drop the two sentences about the poster, and say the shot fills the square frame.

## Exclusions

Leave out photoreal skin, smooth plastic family-film shading, a montage that jumps cities, a slow title sequence, and any existing person or scene.

A 16:9 sunlit piece with soft fur, volumetric sun, and no ink contour is a different look. So is a photoreal widescreen shot. Do not pull those into this prompt.

## What this is based on

Clips were checked by extracting frames several seconds apart from the video files. They were not played as a continuous screening, and the audio was not heard. Captions on the posts describe a continuous score and hard impacts; that audio was not verified. The prompt above is a fresh template. The frames kept for the square clips are listed in [references/INDEX.md](../../references/INDEX.md).

Every square clip below is 720×720 in the file that was sampled, with the scene on top and the poster plate underneath. Durations are from the files.

| Date | Duration | What the frames showed | Post |
| --- | --- | --- | --- |
| 30 Sep 2026 | 18.5s | Opens inside a vehicle on a shattered windshield. Then a smoky lobby, two foreground figures framing a walker. Face close-up with a red practical in the glasses. One-point corridor in fluorescent haze. Low hero at the end. Dust in the light. Black lead against blue uniforms. | [post](https://x.com/TechieBySA/status/2105307477197594872) |
| 30 Sep 2026 | 15.0s | Weapon macro, overhead of a wooden floor under round lanterns, close clash, overhead again with scraps in the air. Warm tungsten, hard floor shadows. Bright yellow figure against a black suit. | [post](https://x.com/TechieBySA/status/2105256768595193986) |
| 29 Sep 2026 | 15.0s | Close grapple in a narrow alley of flat pink, yellow, and blue walls, golden dust. Later a high wide of a rooftop in low sun, long shadows, lead alone in the middle of the roof. | [post](https://x.com/TechieBySA/status/2104944740114239758) |
| 29 Sep 2026 | 20.1s | Night exterior, fire as a rim. Black figures against tan figures. Ends overhead: a pool of spotlight, the group together, the tan figures arranged around them. | [post](https://x.com/TechieBySA/status/2104896360722076082) |
| 28 Sep 2026 | 14.2s | Warm wood interior, paper screens, dust in the sun. Profile two-shot in stance, then a close grapple from behind. Cream cloth against navy. | [post](https://x.com/TechieBySA/status/2104623023365992855) |
| 28 Sep 2026 | 17.3s | Hard daylight street, haze, cars as blocks of color. Close profile with a muzzle flash, then a runner between open car doors, then a high wide of the intersection still full of smoke. | [post](https://x.com/TechieBySA/status/2104581946240070062) |
| 14 Sep 2026 | 14.6s | Interior haze in magenta and cyan, reflective floor, crowd as dark shapes. Lead in a dark suit, prop in hand. Later a wider view of the same colored room. | [post](https://x.com/TechieBySA/status/2099502862799638678) |
| 5 Sep 2026 | 15.0s | Rain on a wet roof, thin rim light, saturated red horizon. Low tangle of black figures, then a wide profile of two figures with the city behind them. | [post](https://x.com/TechieBySA/status/2096196085198839832) |
| 1 Sep 2026 | 14.2s | Bright high-key street, palms, a saturated yellow vehicle. An aerial kick on a rail, then a looser two-shot with a grin. Same ink render, lighter mood. | [post](https://x.com/TechieBySA/status/2094793092297605595) |

**Neighboring clips from 29 Sep 2026, not this grammar.** A 15.1s 1280×720 piece ([post](https://x.com/TechieBySA/status/2104864790938292464)) is smooth stylized 3D: lion-dance costume, golden-hour sun in the lens, fur and cloth with soft shading, no ink contour, no poster plate. The still board beside it is the same sunlit painterly 3D in eight panels ([image post](https://x.com/TechieBySA/status/2104864787117056145)). A 30.5s widescreen clip in that thread ([post](https://x.com/TechieBySA/status/2104864794297733293)) is photoreal: overcast landscape, then a stone gate, natural skin. A fisheye tool demo the same day was ignored.

Pixel check on the square clips: the lower half’s frame-to-frame difference was small beside the upper half (on the order of 10–25 versus 60–130 in a coarse sample). That matches a held poster, not a second animated scene.
