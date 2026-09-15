# Inventory: cc_course (titles and paths only)

**Course repo:** [qu1queee/cc_course](https://github.com/qu1queee/cc_course) (cite paths relative to that repo).  
**Constraint:** keep classic cloud; add AI-era labs later (briefs, not this file).  
**Not a brief.** Later chats should read this instead of all `weeks/*/workshop.md`.

## Course frame (README)

- Audience: grad / master’s; 15 weeks, 60 hours; Friday theory + workshop.
- Stated expectations: K8s, serverless, observability, FinOps, multi-cloud/hybrid, IaC (Terraform, Pulumi), platform engineering.
- Schedule table (weeks 01–12 + holidays): `README.md`

## Workshops

| Week | Title (H1 / workshop subtitle) | Path | vs README expectations |
|------|--------------------------------|------|------------------------|
| 01 | Object Storage with MinIO / Cloud Storage Concepts in Practice | `weeks/01/workshop.md` | Classic storage; schedule said “Introduction & Cloud Fundamentals” |
| 02 | REST APIs & Virtualization / From the Hypervisor to the HTTP Request | `weeks/02/workshop.md` | Classic IaaS / HTTP — keep |
| 03 | Reproducible Infrastructure with Vagrant | `weeks/03/workshop.md` | Classic IaaS — keep |
| 03 | OpenStack with DevStack / A Real Cloud on Your Laptop | `weeks/03/workshop_openstack.md` | Classic IaaS — keep |
| 04 | Infrastructure as Code & Configuration Management / First Ansible Playbooks | `weeks/04/workshop.md` | IaC — keep |
| 05 | Cloud Networking & Infrastructure as Code / First Terraform Configuration | `weeks/05/workshop.md` | IaC / networking — keep; schedule also listed Terraform on Labour Day |
| 06 | Collaborative CI/CD Engineering / GitHub Actions pipeline | `weeks/06/workshop.md` | DevOps — keep |
| 07 | Container Image Engineering / Production-Grade Container Images | `weeks/07/workshop.md` | Containers — keep |
| 08 | Kubernetes Part 1 / Orchestrating Your First Service | `weeks/08/workshop.md` | Orchestration — keep |
| 09 | Kubernetes Part 2 / Production Hardening | `weeks/09/workshop.md` | Orchestration — keep |
| 10 | PaaS, CaaS & 12-Factor Apps / CaaS with Shipwright | `weeks/10/workshop.md` | Platform — keep |
| 11 | Service Mesh in Practice / Zero-Trust Networking with Istio | `weeks/11/workshop.md` | Not in README “Topics Expectation” |
| 12 | (see `weeks/12/workshop.md`) | `weeks/12/workshop.md` | Schedule advertised FaaS + serverless wrap-up; workshop does not match that label |

Teacher notes exist for several weeks as `weeks/NN/workshop_teacher.md` (not inventoried line-by-line).

Do not inventory or cite assessment materials from the private course repo.

## Obvious holes for later briefs (not researched here)

- README expectations missing from workshops: FinOps, observability, multi-cloud, Pulumi.
- AI-era content: none in titles.
- Week 11–12 vs advertised FaaS / wrap-up.
