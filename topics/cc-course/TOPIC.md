# Topic: Cloud computing course — keep classic cloud, add AI-era labs

This is **one** topic in the research repo. Other slugs get their own `TOPIC.md`, `form.md`, and skill.

**Skill:** [`cc-course-curriculum`](../../.cursor/skills/cc-course-curriculum/SKILL.md)  
**Persona:** Curriculum editor (local workshops first; dated vendor docs only when a brief names a SKU, API, or tool version)  
**Outcome form:** [form.md](form.md)  
**Inventory (read this instead of all weeks):** [inventory.md](inventory.md)

**Course repo (do not copy workshops into this research repo):** [qu1queee/cc_course](https://github.com/qu1queee/cc_course)

## Standing question

How do we keep this 15-week master’s cloud course (IaaS, IaC, Docker, Kubernetes, serverless), and where do we insert AI-era cloud skills (GPUs, inference serving, token vs instance cost, optional RAG) without throwing away Vagrant/OpenStack/Docker/K8s?

A brief answers **one** rotate question, not the whole curriculum.

## In scope

- Local workshop titles and overviews (path + line range). Not assessment materials.
- Gaps vs the course README “Topics Expectation” and the published schedule.
- Student-laptop constraints (kind, Docker, CPU fallback for GPU labs).
- One dated official doc URL only if the focus is a specific tool version or billing unit.

## Out of scope

- Rewriting `cc_course` in a research brief (findings only; edits to the course are a later, separate task).
- Peer-course crawls unless a brief names a single URL.
- Copying workshop bodies into this repo.
- Assessment materials from the private course repo (never quote, list, or path them here).
- Papers-first AI-models catalog (not this topic).

## Questions to rotate

Pick **one** per brief.

1. Which stated README topics never appear in workshops (FinOps, observability, multi-cloud, Pulumi)?
2. Which existing week can take a small AI add-on vs which needs a new week?
3. Week 11–12 (Istio vs advertised FaaS wrap-up): keep, shrink, or swap for GPU/inference?
4. What is a student-laptop-feasible GPU/inference lab (CPU fallback)?
5. FinOps: token billing vs VM-hour — one workshop, not a new course.

## Success

- Every claim cites a path under the course clone or inventory.md.
- Outcome matches [form.md](form.md).
- Next focus is a different week or rotate question.
