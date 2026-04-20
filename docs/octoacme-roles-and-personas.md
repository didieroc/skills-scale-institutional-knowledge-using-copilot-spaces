# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA/Testing validates that features meet acceptance criteria and quality standards before release. They are the final quality gate between development and production.

### Responsibilities
- Define and execute test plans against acceptance criteria
- Identify, document, and track bugs and regressions
- Validate bug fixes and confirm Definition of Done is met
- Run end-to-end and smoke tests prior to release
- Maintain test suites and report quality metrics

### Goals
- Prevent regressions and ensure release readiness
- Provide clear, actionable feedback to developers
- Shorten feedback loops between development and quality validation

### Typical Communication
- Bug reports and test result summaries
- Go/no-go signals in release checklists
- Participation in sprint reviews and retrospectives

### Interactions
Works closely with **Developers** on bug reproduction and fix validation, coordinates with **Release Engineers** on staging environment readiness, and provides quality status to **Project Managers** for go/no-go decisions.

---

## UX Designer

### Role Summary
UX Designers ensure that features are usable, accessible, and meet user needs. They bridge customer insights and engineering implementation from planning through release.

### Responsibilities
- Conduct user research and translate findings into design requirements
- Create wireframes, mockups, and prototypes for developer handoff
- Define and document UX acceptance criteria (usability, accessibility)
- Review implemented features against design intent
- Bring user feedback and usability findings into planning and retrospectives

### Goals
- Ensure product features are intuitive and accessible
- Reduce iteration cycles by aligning design and implementation early
- Advocate for the end user throughout the project lifecycle

### Typical Communication
- Design reviews with Product Managers and Developers during planning
- Annotated mockups and design specs linked in project docs
- Usability feedback in sprint demos and retrospectives

### Interactions
Partners with **Product Managers** to shape requirements and acceptance criteria, works with **Developers** during implementation to clarify design intent, and shares usability findings with **Data Analysts** to validate outcomes post-release.

---

## Data Analyst / Analytics Partner

### Role Summary
Data Analysts track key metrics, build dashboards, and provide analysis that informs planning, validates outcomes, and supports data-driven decisions throughout the project lifecycle.

### Responsibilities
- Define measurement plans and identify data requirements during planning
- Build and maintain dashboards for project health and success metrics
- Run post-release analyses to validate impact against stated goals
- Surface insights that inform prioritization and retrospectives
- Ensure data instrumentation is in place before release

### Goals
- Enable the team to make confident, evidence-based decisions
- Provide clear visibility into project impact and user behavior
- Close the loop between delivery and outcome measurement

### Typical Communication
- Metric definitions and measurement plans during planning
- Dashboard links and analysis summaries in status updates
- Post-release outcome reports shared with Product Managers and stakeholders

### Interactions
Provides insights to **Product Managers** for backlog prioritization, collaborates with **Developers** to ensure analytics instrumentation is implemented correctly, and supports **Project Managers** with burndown and velocity metrics. Works with **UX Designers** to validate usability outcomes with data.

---

## Release Engineer / DevOps

### Role Summary
Release Engineers own the deployment pipeline, release infrastructure, and operational readiness. They ensure features can be delivered safely, reliably, and repeatably to production.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment tooling
- Coordinate release schedules and deployment windows
- Validate staging deployments and run pre-release smoke tests
- Ensure rollback plans are documented and tested
- Monitor deployment health and respond to pipeline failures

### Goals
- Enable safe, low-friction releases on a predictable cadence
- Minimize production incidents caused by deployment issues
- Automate repetitive release steps to reduce manual error

### Typical Communication
- Release readiness updates in the [Release & Deployment Guide](./octoacme-release-and-deployment.md) checklist
- Pipeline status and deployment notifications
- Post-deploy verification summaries shared with PM and QA

### Interactions
Coordinates with **Developers** to resolve build and release blockers, supports **QA/Testing** with staging environment access and smoke test execution, and partners with **Project Managers** for release scheduling. Escalates production incidents to the on-call team and communicates status to **Customer Support Lead**.

---

## Customer Support Lead

### Role Summary
The Customer Support Lead acts as the voice of the customer post-release. They triage user-reported issues, manage support escalations, and ensure customers receive timely, accurate communication during and after releases.

### Responsibilities
- Monitor and triage user-reported issues and feedback post-release
- Communicate release changes and known issues to customers
- Coordinate hotfix prioritization with Product Managers and Project Managers
- Provide support-theme summaries to planning and retrospectives
- Ensure support team readiness before releases (training, FAQs, runbooks)

### Goals
- Minimize customer impact from bugs, regressions, and release changes
- Close the feedback loop between customers and the delivery team
- Enable fast, well-coordinated responses to production incidents

### Typical Communication
- Release announcements and known-issue notices to customers
- Issue summaries and escalation reports to PM and Product Manager
- Participation in post-release retrospectives with customer feedback themes

### Interactions
Provides issue summaries and customer impact assessments to **Product Managers** and **Project Managers** to inform prioritization. Receives advance release notes from **Release Engineers** to prepare support communications. Feeds recurring support themes into **retrospectives** and **planning** sessions to drive quality improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Kickoff Checklist](./octoacme-kickoff-checklist.md) for a practical guide on which roles are engaged at each phase of the project lifecycle.

