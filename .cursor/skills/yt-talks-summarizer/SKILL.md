---
name: yt-talks-summarizer
description: >-
  Manual-only. One YouTube video per run. Read captions and fill the yt-talks
  twelve-section engineering notes form. Never commit a transcript. Use when
  the user names yt-talks or a video/playlist URL for this topic.
---

# Engineering notes from captions (yt-talks)

Assigned only to `topics/yt-talks`. **Manual runs only.** Do not schedule, loop, or summarize a whole playlist.

## Input

The user must name **one** of:

- A video URL, or
- The playlist in TOPIC.md plus an index / title to pick **one** video.

If they only paste a playlist, ask which video. Do not pick 100 talks.

## Source

Use YouTube **captions** (and the description for title, speakers, date). You are not watching the slides. ASR will mangle names (`Qflow` → Kubeflow). Prefer description for proper nouns when captions disagree.

## Copyright hygiene (not legal advice)

Do not write `.vtt`, `.srt`, or a full caption dump into the repo. Fill [form.md](../../../topics/yt-talks/form.md) with paraphrase and, if needed, quotes ≤25 words. This does **not** mean the notes are free of copyright risk.

## Cost

One ~25 min talk ≈ 4–7k caption tokens in + a long structured brief out. Stop after one video.

## Method (follow in order)

Copy the user’s twelve steps. Skip a section only by writing **none in captions** — never invent.

1. **Identify the talk** — problem, audience, domain, type (architecture / implementation / research / operations / product / experience report).
2. **Core thesis** — 2–5 sentences: what they teach, what they solve, main conclusion.
3. **Technical concepts** — technologies, algorithms, architectures, protocols, hardware, software, infra, terms; each in *the speaker’s* usage.
4. **Reconstruct the system** — components, data/control flow, dependencies, interfaces, scaling boundaries, failure points. Mermaid when it helps.
5. **Engineering decisions** — for each: Decision / Why / Alternatives / Trade-off / Result. Omit if none spoken.
6. **Numbers** — GPU count/type/memory, throughput, latency, batch, model size, bandwidth, storage, utilization, cost, scale. **Never invent missing numbers.**
7. **Trade-offs** — X better than Y when…; chose X because…; X fails when…; bottleneck…; downside…
8. **Fact vs opinion** — label: observed, measured, architectural choice, speaker opinion, recommendation, hypothesis.
9. **Context** — workload, scale, hardware, software version, assumptions, constraints.
10. **Lessons** — split broadly applicable vs specific to their company/system.
11. **Uncertainty** — mark caption gaps; do not silently guess; do not promote speculation to fact.
12. **Actionable notes** — remember; investigate next; docs/tech to learn; design questions to ask.

## Output

Write `topics/yt-talks/briefs/YYYY-MM-DD.md` using [form.md](../../../topics/yt-talks/form.md). If that file exists, `YYYY-MM-DD-2.md`.

If captions cannot be fetched: one short brief with section 11 = blocked, empty other sections.
