# Director: Weekly study video generation technique distilled to playbook keep and

Date: 2026-10-30
Task: Weekly study: video generation technique, distilled to Playbook keep and drop notes
For [[Bard]].

# Video Generation Playbook: Weekly Study

**Scope note:** I had no live browsing this run, so these notes come from my training knowledge of the vendors' published prompting guides. Before the Playbook locks, someone should confirm each source's current version and link.

## KEEP

- **Motion in the first second.** Short-form vendors and creator guides consistently favor an action in the opening beat. *Source: Runway Help Center prompting guides; TikTok Creative Center trend reports (vertical short-form retention patterns).*
- **One idea per clip.** Veo and Sora prompting docs both recommend a single subject, single action, single camera move. *Source: Google Veo prompt guide (Vertex AI docs); OpenAI Sora prompting guidance.*
- **Name the camera move explicitly.** "Slow push-in," "static locked shot," "slow orbit." Generic words like "cinematic" do little. *Source: Runway and Luma prompting guides.*
- **Describe light by source.** "Pink rim light from camera left, black background" outperforms "moody lighting." *Source: Google Veo and Kling prompt guides.*
- **Start from a locked still (image-to-video).** It gives tighter control over the look than text alone. *Source: Runway Gen-3/Gen-4 image-to-video documentation.*
- **Reuse identical subject wording across shots** so the look stays consistent. *Source: OpenAI Sora prompting guidance (character consistency notes).*

## DROP

- **Any text, letters, numbers, or logos in footage.** Video models cannot spell. Put all words in the overlay field. *Source: consistent failure mode across model release notes and community testing; our own house law.*
- **Stacked camera moves** ("dolly, pan, and tilt while zooming"). They cause drift and warping. *Source: Veo and Runway prompt guides, which warn against it.*
- **Keyword salad** ("8K, ultra detailed, masterpiece, hyperreal"). Modern models ignore most of it and the prompt gets noisy. *Source: Veo and Sora prompting guides.*
- **Fake profit imagery** (cash piles, falling charts, "money" B-roll). It conflicts with our honesty standard. *Source: BlackCrown brand standards.*
- **Long single generations with no cut.** Plan 15 seconds as short beats so a weak moment can be cut rather than rerolled. *Source: cost and pacing reasoning; clip length is now 15s per owner ruling 10-29.*

## OPEN QUESTIONS

- Current per-second cost on Bloom versus the Furnace GPU path for 15-second clips.
- Whether first-frame control on the Furnace model is as tight as Runway's image-to-video.
