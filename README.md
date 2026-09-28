# 🎸 AI Music Prompt Builder — Bandmate Edition

> **A simple, no-API music prompt studio for turning a song reference or fresh idea into a structured prompt for AI music tools.**

[![Live App](https://img.shields.io/badge/▶%20OPEN%20LIVE%20APP-Vercel-000000?style=for-the-badge&logo=vercel)](https://ai-music-prompt-builder-bandmate.vercel.app/)
![Single File](https://img.shields.io/badge/Single--File-HTML-f97316?style=for-the-badge&logo=html5&logoColor=white)
![No API Key](https://img.shields.io/badge/API%20Key-Not%20Required-22c55e?style=for-the-badge)
![Bandmate Edition](https://img.shields.io/badge/Edition-Bandmate-8b5cf6?style=for-the-badge)

Built for Rob and the old band crew, around seven **Separate Piece** reference tracks and the history of **A Separate Peace**. This started as a small personal prompt tool and evolved into a fun way for bandmates to experiment with new musical ideas using modern AI music generators.

---

## ⚡ Quick Start — About 60 Seconds

If you just want to make something and don't care how the machinery works:

1. **Open the live app:** https://ai-music-prompt-builder-bandmate.vercel.app/
2. Choose **Our Band**, **Favorite Song**, or **Start Fresh**.
3. If using a band reference, pick a song and choose what you want to emphasize:
   - Full Band
   - Bass
   - Guitar
   - Drums
   - Vocals
   - Keys
4. Adjust as much or as little as you want.
5. Hit **Generate Prompt**.
6. Start with the **Suno** output.
7. Copy the prompt, open Suno, paste it into **Custom** mode, and generate a few versions.
8. Want a different interpretation? Try the **Gemini / Lyria** version next.

You do **not** need to understand prompt engineering to use this. The whole point is to let the app handle most of that nonsense for you. 🤘

---

## 🥇 Recommended Starting Point: Suno

For this project, **Suno is the easiest place to start**.

The app creates a Suno-specific prompt from your choices so you can go from:

**reference song → musical direction → generated prompt → new AI track**

A simple workflow:

1. Build your idea in the app.
2. Switch to the **Suno** output.
3. Copy the generated prompt.
4. Open Suno.
5. Use **Custom** mode.
6. Paste the prompt into the appropriate style / description area.
7. Add your own lyrics if you want vocals, or use **Instrumental only**.
8. Generate multiple versions and see what sticks.

The first generation does not need to be "the song." Treat it like another musician throwing ideas into the room.

---

## 🥈 Alternative: Gemini / Lyria

The **Gemini / Lyria** output is useful when you want another interpretation of the same musical direction.

Try the same basic idea in both Suno and Gemini / Lyria. Different models can emphasize different parts of the prompt, arrangement, mood, or instrumentation.

The app also includes a reference-analysis workflow that can help break a song down into transferable musical characteristics before you generate something original.

---

## 🎧 Using a Reference Song

You have two main options.

### Use one of the included band tracks

Pick one of the seven **Separate Piece** reference tracks, then choose an instrument or full-band focus.

The app uses that selection as a creative anchor and helps describe things like:

- groove
- dynamics
- instrumentation
- guitar / bass / drum roles
- vocal character
- arrangement
- atmosphere
- production direction
- overall energy

A Spotify preview is available for the included tracks when you're online.

### Use another song you love

Paste a Spotify, YouTube, or other reference URL into the reference-song workflow.

The app can generate a structured **reverse-engineering prompt** that you can copy into Gemini, ChatGPT, or another capable AI tool.

The goal is **not** to copy the song.

The workflow asks the AI to identify transferable characteristics such as tempo, mood, structure, instrumentation, groove, production, and dynamics so you can use those ideas in an **original composition**.

---

## 🥁 Instrumental Only

Turn on **Instrumental only** when you do not want lead vocals, lyrics, or a sung melody.

The generated prompt will adjust accordingly instead of making you manually remove vocal instructions afterward like some kind of unpaid studio intern.

---

## 🎛️ What You Can Shape

The builder can help define:

- Primary genre and subgenre
- Mood and emotion
- Energy profile
- Vocal style and character
- Tempo / BPM
- Time feel
- Groove
- Drum direction
- Bass role
- Guitar direction
- Main instruments
- Texture and atmosphere
- Song structure
- Biggest payoff / climax
- Hook focus
- Production style
- Spatial / mix character
- Things to avoid
- Optional prompt enhancers

Everything remains editable.

---

## 🤖 Generator Outputs

The app currently provides platform-oriented output for:

- **Suno** — recommended starting point
- **Gemini / Lyria** — excellent second interpretation
- **Universal** — useful as a flexible general-purpose prompt
- **Grok** — alternate prompt formatting

It also includes launch links for other music tools such as Udio and Eleven Music.

The app copies your prompt and opens the destination service. You still paste the prompt yourself because third-party sites do not provide a dependable cross-site prefill mechanism for this little static app.

---

## 💾 Saving Your Work

The app is local-first.

You can:

- **Save to Browser**
- **Load Saved**
- **Export Project JSON**
- **Import Project JSON**

Browser saves stay on that device/browser.

Use JSON export if you want to:

- keep a backup
- move an idea between devices
- send a project to another bandmate
- pick up where you left off later

---

## 🔐 No API Keys Required

This edition intentionally does **not** require:

- an OpenAI API key
- a Gemini API key
- a Spotify API key
- a backend server
- an account database
- an installation process

The prompt builder itself is static HTML and JavaScript.

Internet access is only needed for things such as Spotify previews and whichever AI music service you decide to open.

---

## 💻 Run It Locally

If you clone or download the repository, simply open:

```
index.html
```

in a modern browser.

There is:

- no npm install
- no build process
- no framework setup
- no server required

For the easiest experience, use the hosted Vercel version.

---

## 🌐 Live Version

**https://ai-music-prompt-builder-bandmate.vercel.app/**

The GitHub repository is the source project, and the live app is hosted on Vercel.

---

## 🎵 A Note for the Band

This is not meant to replace writing together, playing instruments, arguing about arrangements, changing the bridge sixteen times, or any of the other traditions musicians have perfected over thousands of years.

It's just another creative tool.

Use it to:

- spark an idea
- explore a different arrangement
- build a backing-track concept
- experiment with a forgotten song
- try a new genre
- hear what a weird idea might sound like
- get everybody talking about music again

If it creates something cool, keep going.

---

## Credits

**Bandmate Edition concept and prompt mechanics by Rob Abramov**

Built for collaborative songwriting, production study, experimentation, and reconnecting old bandmates with some very new tools.

⚡ Human Built. AI Assisted. Pure Heavy Metal & Rock & Roll! ⚡
