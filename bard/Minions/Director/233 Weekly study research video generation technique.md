# Director: Weekly study research video generation technique for playbook

Date: 2026-10-27
Task: Weekly study: research video generation technique for Playbook
For [[Bard]].

# Playbook Study: Video Generation Technique

**Scope:** This is drawn from general knowledge of current video generation practice, not live research. Verify model-specific behavior with a short test batch before adopting any rule. The Operator 19:00 draft under review was not touched.

## 1. Wordless footage control

- **Negative prompts are weak.** "No text" in the prompt reduces but does not stop glyph-like marks on monitors, keyboards, and packaging. Treat it as a soft preference, not a guarantee.
- **Remove the surfaces that carry text.** Screens facing camera, keycaps, book spines, and printed labels are the main sources of garbled characters. Frame them out, turn them away, or keep them in deep shadow.
- **Use abstract subjects.** Silhouettes, raven feathers, crown-shaped light, glass, smoke, and macro metal produce no letterforms.
- **Keep words in the overlay layer.** Titles and captions are added after render. The footage only supplies mood and motion.

## 2. Motion pacing for 10 to 15 second vertical clips

- **Motion in the first second** holds attention in feeds, and the house rule already requires it.
- **One camera idea per clip.** A single slow push, lateral dolly, or tilt. Combined moves (dolly plus tilt plus rack focus) tend to break subject coherence in short generations.
- **Simple subject action.** Models lose consistency on complex motion after roughly 5 to 8 seconds. Keep one action, then hold.
- **Avoid whip pans.** Fast lateral moves smear and produce artifacts that read as cheap in vertical.
- **Plan a clean ending.** Ending on a held frame or a loop-friendly image makes the clip easier to cut and reuse.

## 3. Light and material for dark UI hero shots

- **One key source.** A single directional light with falloff reads as cinematic. Multiple soft fills flatten black and cause banding.
- **Pink as rim and accent, not fill.** Brand pink on edges, rim highlights, and haze keeps the palette honest and leaves black negative space.
- **Preserve dark negative space.** Leave the top and bottom safe zones dark and uncluttered so overlay copy stays legible.
- **Materials that read well in the dark:** matte black surfaces, smoked glass, polished chrome edges, brushed metal. These catch light cleanly without needing screen detail.
- **Grain and bloom in moderation.** Light grain hides generation noise. Heavy bloom washes out the hero object.

## Three Playbook notes

1. **KEEP:** Frame text-bearing surfaces out of the shot and push every word to the overlay field. **DROP:** relying on "no text" in the prompt as the only control.
2. **KEEP:** One camera move, one subject action, 10 to 12 seconds, motion starting in the first second. **DROP:** multi-move shots such as dolly plus tilt plus rack focus in a single clip.
3. **KEEP:** Single key light with pink rim, dark negative space reserved for overlay copy. **DROP:** bright UI glow hero shots that depend on legible interface detail.
