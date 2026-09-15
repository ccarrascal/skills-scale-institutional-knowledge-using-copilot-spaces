# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process documentation. These guides help teams plan, execute, and deliver projects consistently and effectively.

## Quick Start

New to OctoAcme project management? Start here: [Project Management Overview](./octoacme-project-management-overview.md)

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leadership
- **Data-informed decisions**: Measure impact and iterate
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Process Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The initiation phase validates business need through a lightweight One-pager that captures the problem statement, objectives, success metrics, stakeholders, and initial risks. Once stakeholders and leadership align on priority and success criteria, the project moves into planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a prioritized backlog is created. Execution follows an iterative delivery model with small pull requests (≤400 lines when possible), automated CI/CD testing and linting, and mandatory code review approval before merging. Throughout all phases, OctoAcme maintains a Risk Register and escalation framework—team-level triaging in daily standups, PM escalation to Product Leads, and sponsor-level escalation for business-impacting issues.

OctoAcme defines clear ownership across four core personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and measure outcomes; **Developers** implement features and maintain quality; and **QA/Testing** validates acceptance criteria. Weekly syncs between PM and Product Manager, twice-weekly (or agreed-upon) team standups, and monthly stakeholder updates form the communication backbone. This clarity of ownership and regular cadence reduces ambiguity and keeps all stakeholders informed.

Quality is embedded throughout execution: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI all happen before release. Manual QA validates feature acceptance when needed, and a Definition of Done ensures consistent quality standards. The release process is deliberately standardized—patch, minor, and major releases each follow pre-release requirements including passing CI, drafted release notes, and a documented rollback plan. Post-deployment verification and stakeholder announcements complete the handoff, with incident playbooks and blameless retrospectives ready if issues arise. This emphasis on automated quality gates, clear acceptance criteria, and documented rollback procedures minimizes production risk and enables confident, iterative delivery.

After each sprint, release, or milestone, OctoAcme runs retrospectives to capture what went well, what could improve, and to generate 2–3 prioritized action items with clear owners and due dates. These improvements feed back into the project backlog and are reviewed in weekly PM syncs, creating a feedback loop that systematically raises team capability. Combined with measurement of success metrics (velocity, burndown, error rates, latency, usage) and a culture that emphasizes psychological safety and blameless postmortems, OctoAcme builds institutional knowledge over time. This approach—anchored in shared process documents, regular communication, and documented learning—enables new team members to onboard quickly and the organization to avoid repeating mistakes, turning scattered tacit knowledge into searchable, versioned, and continuously refined artifacts.

## Documentation by Project Phase

### Planning Phase

- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Validate business need and align stakeholders on go/no-go decisions
- [**Project Planning**](./octoacme-project-planning.md) — Break work into actionable increments with clear acceptance criteria and timelines
- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Understand team roles, responsibilities, goals, and communication patterns

### Execution Phase

- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery, quality assurance, and sprint rhythm
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identify, assess, and monitor risks; escalate and communicate to stakeholders

### Release Phase

- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardize release processes, rollback procedures, and incident response

### Learning Phase

- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, and continuously improve processes

## How to Use These Docs

- **Keep project charters and plans updated** in your project repository
- **Reference specific sections** during planning, execution, reviews, and retrospectives
- **Use templates and checklists** provided in each guide to standardize work
- **Add to Copilot Spaces** by including these docs in `.copilot/` for context-aware guidance
- **For questions or improvements**, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template

## Project Lifecycle at a Glance

```
Initiation → Planning → Execution → Release → Close & Retrospective
    ↓          ↓           ↓          ↓               ↓
  One-pager  Backlog     Standups   Deploy        Learnings
  Alignment  Sprint Plan  PR Review  Announce      Action Items
  Risks      DoD         Quality    Rollback       Metrics
```

## Communication Cadence

- **Daily**: Team standups (15 min) focused on progress, blockers, and dependencies
- **Twice-weekly**: Delivery team syncs (or as agreed)
- **Weekly**: PM + Product Manager alignment
- **Monthly**: Stakeholder updates
- **Per milestone**: Demo/review and retrospective
- **Ad-hoc**: Risk escalation and incident response

## Key Artifacts

Each project maintains:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Project Board** — Backlog, Ready, In Progress, In Review, QA, Done
- **Acceptance Criteria & Definition of Done** — What done looks like
- **Release Notes** — Changes, migrations, known issues
- **Retrospective Notes** — Learnings and action items

## Getting Started with a New Project

1. **Initiate**: Complete the [Project One-pager template](./octoacme-project-initiation.md#project-one-pager-template)
2. **Plan**: Run a kickoff meeting and build your backlog using the [Backlog Item template](./octoacme-project-planning.md#backlog-item-template)
3. **Execute**: Use the project board and follow the PR workflow; hold regular standups
4. **Track**: Monitor risks, dependencies, and success metrics weekly
5. **Release**: Follow the [Deployment Checklist](./octoacme-release-and-deployment.md#deployment-checklist)
6. **Retrospect**: Run a retrospective and prioritize action items for the next cycle

---

**Questions?** Refer to the relevant phase documentation or open an issue with the process docs template.
