# OctoAcme Project Management Docs

This folder contains OctoAcme's lightweight, repeatable project management playbook. The goal is to make delivery predictable and transparent: validate outcomes early, plan in shippable increments, execute with clear ownership and team cadence, release safely with verification, and continuously improve through retrospectives.

OctoAcme projects generally follow this lifecycle: **Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement**. Core artifacts include a **Project One-pager/Charter** (problem statement, goals, success metrics), a **prioritized backlog with acceptance criteria**, a **Definition of Done**, a **risk register**, and **release notes**. Work is tracked on a project board (e.g., GitHub Projects) and delivered via a pull request workflow that favors small PRs, linked issues, and CI validation before merge.

Roles are intentionally explicit. The **Project Manager (PM)** coordinates delivery mechanics — timeline, risks, dependencies, status reporting, and meeting facilitation. The **Product Manager / Product Lead (PdM)** owns outcomes, prioritization, and measuring success. **Developers** design, build, and test the solution while surfacing technical risks early. **QA/Testing** validates against acceptance criteria and quality standards. **Stakeholders** provide input, alignment, and approvals as needed. Communication emphasizes a predictable cadence: daily standups, weekly delivery syncs, sprint or milestone demos, and regular stakeholder updates following a consistent status format (progress, next steps, risks/blockers, and decisions needed).

Quality assurance is built into every phase. Teams run automated tests and linting in CI, include security scanning, and apply unit, integration, and end-to-end smoke tests appropriate to the change. Releases require acceptance criteria completion, passing CI/scans, release notes, and a rollback/mitigation plan, followed by staging validation and post-deploy verification. Risks are captured in a living risk register (impact/likelihood/owner/mitigation/status) and escalated through a defined path when business impact requires it. After sprints, releases, milestones, or incidents, a blameless retrospective captures learnings and turns them into owned backlog items — closing the improvement loop.

## Docs index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
