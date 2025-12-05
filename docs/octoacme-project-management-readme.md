# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This collection of documents summarizes how OctoAcme plans, executes, and improves cross-functional projects. Use this README as the primary landing page to understand our lifecycle, roles, communication cadence, and where to find detailed guidance for each stage of the project.

OctoAcme runs projects with a stage-based lifecycle that moves work from lightweight initiation into planning, execution, release, and retrospective. Initiation uses a Project One‑pager to capture the problem, objective, success metrics, stakeholders, and a go/no‑go recommendation. Planning converts approved initiatives into a prioritized and estimated backlog using templates for backlog items, a Definition of Done, and a Risk Register to capture impact, likelihood, owners, and mitigations. Execution is guided by a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request process that encourages small PRs, clear acceptance criteria, CI checks (tests, linting, security scanning), and approvals before merging.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, risks, timelines and stakeholder communications; Developers implement features, write tests, and participate in reviews; QA validates acceptance criteria and test strategies; stakeholders provide input and approvals. Communication is structured (daily standups, weekly delivery syncs, PM+PdM alignment, and monthly stakeholder updates) with a single source of truth maintained in the project README or release docs and templates for status and incident communications. Risk and dependency management use a Risk Register plus defined escalation paths to ensure issues are triaged and escalated consistently.

Quality and release safety are enforced through automated and manual controls: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed. Releases follow defined types (patch, minor, major) with a pre-release checklist that includes passing CI, release notes, a rollback/mitigation plan, and staging smoke tests; post-release verifications and blameless retrospectives convert learnings into tracked action items.

## Process Document Links
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use
- Start here when onboarding to a project or refreshing process knowledge.
- Keep your project README or charter updated as the single source of truth.
- Use the templates and checklists linked in each document when running initiation, planning, execution, release, and retrospectives.

## Acceptance Checklist
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

This README was added to satisfy: https://github.com/pauloemmanuel/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2
