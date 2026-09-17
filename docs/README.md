# OctoAcme Project Management Docs

This folder is the single source of truth for OctoAcme's project management processes. Use it as the starting point when joining a project, planning a release, or looking for guidance on any phase of the delivery lifecycle.

---

## Process Overview

OctoAcme's project management lifecycle is built around five phases: **Initiate → Plan → Execute → Release → Reflect**. Every project starts with a lightweight one-pager that defines the business problem, success metrics, key stakeholders, timeline, and scope, which feeds a go/no-go decision. Once approved, teams break work into a prioritized backlog, map milestones, identify dependencies, and document a Definition of Done. Delivery is iterative and measurable, with each stage producing durable artifacts — project charter, backlog, risk register, and release plan — that keep stakeholders aligned.

Execution is driven by small, well-scoped pull requests, CI/CD gates, and daily standups. Releases follow a formal checklist that covers smoke tests, security scanning, rollback planning, and a post-deploy verification step. Every sprint or incident closes with a retrospective to capture what worked, what didn't, and what process changes the team commits to next.

---

## Key Workflow Phases

| Phase | Purpose |
|---|---|
| **Initiation** | Define problem, goals, scope, stakeholders, and get go/no-go sign-off |
| **Planning** | Build backlog, set milestones, map dependencies, define DoD |
| **Execution & Tracking** | Iterative delivery, daily standups, PR reviews, CI gates, blocker resolution |
| **Release & Deployment** | Release checklist, smoke tests, security scan, rollback plan, post-deploy check |
| **Risk & Communication** | Risk register, escalation paths, stakeholder updates, single source of truth |
| **Retrospective & Improvement** | Sprint/incident retros, action items, process commits |

---

## Roles & Personas

| Role | Responsibilities |
|---|---|
| **Developer** | Build, test, document, and maintain reliable solutions |
| **Product Manager** | Define outcomes, own backlog priorities, validate business value |
| **Project Manager** | Coordinate timing, risks, communications, and documentation |
| **QA / Testing** | Validate acceptance criteria, quality, and regression coverage |
| **Stakeholder** | Provide input, funding, approvals, and business context |

---

## Communication Cadence

- **Daily standup** — surface blockers and keep the team aligned
- **Weekly delivery review** — track progress against milestones
- **Monthly stakeholder update** — highlight status, risks, and decisions needed
- **Milestone demo** — demonstrate working software at key checkpoints
- **Escalation path** — Team Triage → PM → Product Lead → Sponsor (security incidents follow a dedicated runbook)

---

## Quality Assurance & Delivery Practices

- Pull requests must link to an issue and include acceptance criteria
- CI must pass (tests + linting) before a review is requested
- New logic requires unit tests; integration tests for cross-service flows; smoke tests for critical paths
- Security scanning runs before every release
- Manual QA sign-off required for feature acceptance
- Formal release checklist and documented rollback plan for every deployment
- Retrospective held after each sprint or incident to drive continuous improvement

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Guiding principles, lifecycle summary, and governance model |
| [Project Initiation](./octoacme-project-initiation.md) | One-pager template, stakeholder identification, go/no-go process |
| [Project Planning](./octoacme-project-planning.md) | Backlog setup, milestone mapping, dependency tracking, Definition of Done |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Sprint cadence, PR standards, CI gates, blocker management |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release checklist, smoke tests, rollback planning, post-deploy verification |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, stakeholder communication strategy |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Role definitions, responsibilities, and collaboration expectations |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retro formats, action item tracking, process improvement commits |
