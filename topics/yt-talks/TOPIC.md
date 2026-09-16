# Topic: YouTube talks — manual engineering notes from captions

This is **one** topic. Other slugs get their own skill.

**Skill:** [`yt-talks-summarizer`](../../.cursor/skills/yt-talks-summarizer/SKILL.md)  
**Persona:** Caption notes (twelve-section form; paraphrase; no transcript in git)  
**Outcome form:** [form.md](form.md)

## How to run (manual)

In chat, name **one video URL**, or the playlist below plus which talk (index or title). The skill fills [form.md](form.md) from captions. It does not run on a schedule and does not summarize the whole playlist.

Default playlist (edit if needed):

`https://www.youtube.com/playlist?list=PLj6h78yzYM2MLSW4tUDO2gs2pR5UpiD0C`

## Standing question

What did this talk teach, as structured engineering notes (thesis, system, decisions, numbers, trade-offs, lessons)?

## In scope

- Captions + description for one public video.
- Twelve sections in form.md; empty = **none in captions**, not invention.
- Briefs saved to `briefs/` only when you ask to save or update a file.

## Out of scope

- Overnight / playlist-wide runs.
- Transcripts, slide dumps, video/thumbnail files in the repo.
- Republishing notes as course material, blog posts, or training data without a separate decision.
- Legal opinions on fair use.

## IP hygiene (summary)

Paraphrase, attribute (URL + accessed date), cap quotes (see skill). Notes are for **personal study / curriculum research**, not a replacement for watching.

## Success

- One video per run; attribution block complete.
- Numbers only if spoken; uncertainty labeled.
