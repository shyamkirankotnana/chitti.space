# "The Next Step": storyboard (Phase A, awaiting approval)

Made with the `directing-stickman-videos` skill (https://github.com/kaomei/stickman-video-director), A · Model Engine.

| Setting | Choice |
|---|---|
| Topic | "Life will always have uncertainty: you only need the next step" (theme from the shared screenshot; narration is original wording, not the book's text) |
| Format | 9:16 vertical, about 48 s |
| Style | A4 · Cozy Storytelling: white-filled round head and torso, dark stick limbs, full-colour 2D cartoon scenery |
| Picture | Google Flow, Omni 1.1 Flash, 6 clips × 8 s (12 credits each) |
| Voice | ElevenLabs: one continuous narration track, recorded first so the picture is cut to it |
| Clip audio | Natural ambience only (wind, river, footsteps); no generated speech or music |
| Captions | Bold single-line captions burned in afterwards, from the actual narration timing |
| Music | Soft piano/ambient bed under the voice, from a track you supply or a royalty-free library |

## Character (repeated word for word in every prompt)

> One minimalist 2D cartoon protagonist with a white filled circular head, two small dark oval eyes, simple eyebrow strokes and a short curved mouth. The torso is a slim closed tapered shape with solid white fill inside its dark outline. Both arms and both legs are dark single-line strokes with constant medium weight; hands are small dark rounded shapes and feet are short dark rounded strokes. No hair or clothing accessories. Keep the same head-to-body proportions, white head and torso fill, and outline weight in every shot. Exactly two arms and two legs exist; a moving limb replaces its previous pose rather than leaving another limb behind. Expressions change only the simple facial marks, never the head shape or character design.

The only prop is a **blank folded paper map**, plain cream colour with no markings. It's in the hand in clips 1–3, gets folded into a pocket in clip 4, and isn't seen after that.

## Narration (about 120 words, about 48 s)

1. **Hook (0–6 s):** "What if you're stuck… because you're waiting for a map that doesn't exist?"
2. **The assumption (6–14 s):** "We think we need the whole plan before we move. Every step. Every outcome. Guaranteed."
3. **The secret (14–24 s):** "But nobody gets that map. Not even the people who look certain. They just stopped waiting for it."
4. **The truth (24–38 s):** "You'll never know exactly how it all turns out. And that's fine. You don't need to see the whole road. Just the next step."
5. **The close (38–48 s):** "Take it, and the next one appears. So what's the one step you've been putting off? Tell me below."

## Shot list (9:16, built for vertical depth)

| # | Time | Setting | Action and camera | Narration |
|---|---|---|---|---|
| 1 | 0–8 s | Night trailhead, thick blue fog, path climbing up the frame into nothing | Protagonist unfolds the blank map, turns it over (blank on both sides too), looks up the misty path, shoulders drop. Slow push-in from low behind. | Hook |
| 2 | 8–16 s | Cozy bedroom at night, warm desk lamp | Protagonist pins blank map pages to the wall, adds icon-only cards (arrows, question marks, a clock icon) until the wall is full, then steps back and rubs their head. Camera tilts up the crowded wall. | Assumption |
| 3 | 16–24 s | Snowy mountain foot at dawn, peak hidden in cloud | Protagonist finds fresh footprints going up into the cloud, kneels, touches one, then looks up the trail. Camera tilts up from the footprints into the clouds. | Secret |
| 4 | 24–32 s | Misty river at sunrise, flat stepping stones fading into fog | Protagonist folds the map into a pocket and steps onto the first stone; as the foot lands, the next stone softly glows into view. Low camera behind, rising slightly. | Truth, part 1 |
| 5 | 32–40 s | Same river, continuous take from clip 4 | Two more steps, each landing lighting the next stone; fog ahead still thick, posture now relaxed. Camera follows from behind. | Truth, part 2 |
| 6 | 40–48 s | Far bank, sun breaking through the fog onto a meadow trail | Protagonist steps onto the bank, turns to look back at the glowing stones, smiles, faces forward and takes one confident step toward the sunrise. Camera pulls back wide, sun at top of frame. | Close |

The settings change at each section of the script. Clip 4 runs straight into clip 5 as one continuous shot (Flow's `chain_previous`). The other joins are deliberate cuts that keep the protagonist moving in the same screen direction.

## Cost and rollout

1. **Narration (ElevenLabs):** about 650 characters, quoted before generating.
2. **Test (Flow):** clips 1 and 4 at the lowest resolution: 2 × 12 = 24 credits.
3. **Full film (Flow):** the remaining 4 clips at 720p (48 credits), plus clips 1 and 4 again at 720p if needed (24 credits). Proposed cap with one repair round: **120 credits**.
4. **Assembly:** cut to the narration, captions, ambience and music bed, loudness -14 LUFS, 1080×1920 master.
