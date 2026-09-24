# AI Music Prompt Builder — Bandmate Edition

An offline-first, single-file prompt studio for Rob and the A Separate Peace crew. It turns a reference song or a fresh idea into a clear, editable music-production brief for Suno, Gemini / Lyria, Udio, Eleven Music, or another generator.

## What it does

- Starts from seven A Separate Peace reference tracks with a no-API Spotify preview.
- Builds structured prompts from genre, mood, vocals, rhythm, instruments, arrangement, production, and mix direction.
- Supports an explicit **Instrumental only** mode with no lead vocals, lyrics, or sung melody.
- Presents readable prompt sections with editable output fields, short variants, platform variants, and copy actions.
- Copies a platform-ready prompt and opens the selected service in a new tab. The destination site still requires the user to paste because third-party text boxes do not expose a stable, supported cross-site prefill API.
- Generates a structured reverse-engineering prompt for a Spotify, YouTube, or other reference URL. No external API key is stored or required.
- Saves locally, exports portable project JSON, imports it later, and keeps onboarding from repeating automatically.

## Reference-song workflow

1. Select an included track, or paste another song URL.
2. Choose the musical focus: Full Band, Bass, Guitar, Drums, Vocals, or Keys.
3. Copy the reverse-engineering prompt, then paste it into Gemini, ChatGPT, or another tool that can inspect the reference.
4. Bring the resulting characteristics back into the editable builder and generate an original prompt. The workflow intentionally asks for transferable traits rather than lyrics, melodies, or a recreation of a protected recording.

## Run locally

Open `AI_Music_Prompt_Builder_FINAL.html` in a modern browser. It has no build step and no runtime dependency. HTTPS hosting is recommended for the most reliable clipboard behavior; manual select-and-copy remains available when a browser blocks clipboard access.

## Privacy and scope

This edition is intentionally static and API-free. Browser saves stay on the current device unless a project JSON file is exported. Reference URLs are placed into prompts for the user to send to their chosen AI service; this file does not transmit them itself.

## Deployment

The project is portable by design and can be hosted as a static Vercel deployment or served from GitHub Pages. The final HTML is the deployable artifact.

## Credits

Bandmate Edition concept and prompt mechanics by Rob Abramov. Built for collaborative songwriting, production study, and drummer-focused musical exploration.
