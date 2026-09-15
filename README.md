# Research

Markdown topics. This repo holds **N topics**; `cc-course` is one of them. Each topic has a standing question, a skill (persona), and a form. Do not reuse another topic’s skill.

```
topics/
  README.md                 index of all topics
  {slug}/
    TOPIC.md
    form.md
    briefs/                 filled forms
    inventory.md            optional cache (cc-course has one)
.cursor/skills/
  {slug}-{persona}/
```

## Add a topic

Add `topics/{slug}/` with `TOPIC.md` and `form.md`, plus `.cursor/skills/{slug}-{persona}/SKILL.md`, and a row in `topics/README.md`. Token limits and source rules live in that topic’s skill, not as a repo-wide course rule.

## Current topics

See [topics/README.md](topics/README.md).
