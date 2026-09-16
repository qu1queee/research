# Research

Markdown topics. This repo holds **N topics**. Each topic has a standing question, a skill (persona), and a form. Do not reuse another topic’s skill.

```
topics/
  README.md
  {slug}/
    TOPIC.md
    form.md
    briefs/
.cursor/skills/
  {slug}-{persona}/
```

## Add a topic

Add `topics/{slug}/` with `TOPIC.md` and `form.md`, plus `.cursor/skills/{slug}-{persona}/SKILL.md`, and a row in `topics/README.md`. Token limits and source rules live in that topic’s skill.

## Research skills

| Skill | Topic | Persona | Use |
|-------|-------|---------|-----|
| [yt-talks-summarizer](.cursor/skills/yt-talks-summarizer/SKILL.md) | [yt-talks](topics/yt-talks/TOPIC.md) | Caption notes | Manual: one talk, twelve-section notes from captions |

Do not reuse another topic’s skill. Add a row here and in [topics/README.md](topics/README.md) when you add a slug.

## Current topics

See [topics/README.md](topics/README.md).
