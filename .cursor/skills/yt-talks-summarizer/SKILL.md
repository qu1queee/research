---
name: yt-talks-summarizer
description: >-
  Manual-only. One YouTube video per run. Read captions and fill the yt-talks
  twelve-section engineering notes form. Paraphrase; never commit a transcript.
  Use when the user names yt-talks or a video/playlist URL for this topic.
---

# Engineering notes from captions (yt-talks)

Assigned only to `topics/yt-talks`. **Manual runs only.** Do not schedule, loop, or summarize a whole playlist.

## Input

The user must name **one** of:

- A video URL, or
- The playlist in TOPIC.md plus an index / title to pick **one** video.

If they only paste a playlist, ask which video. Do not pick 100 talks.

## Source

Use YouTube **captions** (and the description for title, speakers, date). You are not watching the slides. ASR will mangle names. Prefer description for proper nouns when captions disagree.

Do not transcribe on-screen slide text or long spoken passages verbatim.

## IP / redistribution (not legal advice)

Goal: **personal study notes about the talk**, not a substitute for the video.

- Do not write `.vtt`, `.srt`, or a full caption dump into the repo.
- **Paraphrase** in your own words; prefer third person (“the speaker argues…”).
- **Quotes:** at most **2** per brief, each **≤15 words**, only for a named term or cited number; otherwise paraphrase.
- Do not mirror the talk’s rhetorical order sentence-by-sentence.
- **Caps:** concept table ≤15 rows; engineering decisions ≤5 unless the user asks for more.
- Omit music/sponsor reads unless technically relevant.
- If captions mention confidential or “don’t share” material, generalize or omit.
- Do not download or store video files or thumbnails.

**Save to git:** write `topics/yt-talks/briefs/` only when the user asks to save or update a brief; otherwise output in chat only.

## Cost

One ~25 min talk ≈ 4–7k caption tokens in + a long structured brief out. Stop after one video.

## Method (follow in order)

Copy the twelve steps. Skip a section only by writing **none in captions** — never invent.

1. **Identify the talk** — problem, audience, domain, type (architecture / implementation / research / operations / product / experience report).
2. **Core thesis** — 2–5 sentences.
3. **Technical concepts** — ≤15 rows; each in the speaker’s usage, paraphrased.
4. **Reconstruct the system** — components, flows, boundaries; Mermaid when it helps.
5. **Engineering decisions** — ≤5: Decision / Why / Alternatives / Trade-off / Result.
6. **Numbers** — only if spoken; never invent.
7. **Trade-offs**
8. **Fact vs opinion** — label statements.
9. **Context** — workload, scale, hardware, versions, assumptions, constraints.
10. **Lessons** — broad vs environment-specific.
11. **Uncertainty** — caption gaps, ASR; no silent guesses.
12. **Actionable notes** — your takeaways (not a recap of the talk).

## Output

Use [form.md](../../../topics/yt-talks/form.md). Path: `topics/yt-talks/briefs/YYYY-MM-DD.md` (or `-2.md` if exists). Fill **Source (attribution)** first.

If captions cannot be fetched: brief with section 11 = blocked; minimal other sections.
