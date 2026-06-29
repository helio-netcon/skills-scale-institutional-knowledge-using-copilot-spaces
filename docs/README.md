# OctoAcme Project Management Docs

**Welcome to the OctoAcme project management process documentation.** This folder contains comprehensive guides for running projects using the OctoAcme methodology.

## OctoAcme Approach

OctoAcme is built on the principles of:
- **Customer-first delivery**: Prioritize customer value and usability
- **Iterative execution**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-driven decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

Every OctoAcme project follows this lifecycle:

1. **Initiation** → Validate business need, align stakeholders, create one-pager
2. **Planning** → Break work into shippable increments, define timeline
3. **Execution** → Build, test, review; manage daily progress and risks
4. **Release** → Deploy to production with verification and rollback plans
5. **Close & Retrospective** → Capture learnings and improvements

## OctoAcme Process Overview

### Lifecycle & Workflows

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The initiation phase begins with a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics before approval to proceed. Once approved, the planning phase breaks work into shippable increments, creates a prioritized backlog with acceptance criteria, estimates scope, and defines dependencies. During execution, the team follows a rhythm of daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review flagged risks, and regular demos. Work flows through a GitHub Projects board with stages—Backlog, Ready, In Progress, In Review, QA, Done—while pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. This structured approach ensures iterative delivery of validated, testable increments.

### Roles, Responsibilities & Communication

OctoAcme operates with clear ownership across three primary personas: **Project Managers** coordinate delivery schedules, risks, and communications; **Product Managers** define outcomes, prioritize backlogs, and measure success; and **Developers** implement features, write tests, and participate in planning. Each project has a named PM and Product Lead to ensure accountability. Communication is structured through a cadence of weekly syncs between PM and PdM, twice-weekly delivery standups, and monthly stakeholder updates. Risks and blockers are escalated through a three-level process—team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues—ensuring problems are surfaced and resolved quickly without getting stuck.

### Quality Assurance & Risk Management

Quality is embedded throughout the OctoAcme process via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI pipelines. A Definition of Done is established during planning and enforced before items move to release. Risk management is formalized through a Risk Register that captures ID, description, impact, likelihood, owner, and mitigation plans—reviewed weekly during syncs to keep risks active and addressed. The team maintains dashboards for key signals (errors, latency, usage) and tracks velocity and burndown to monitor progress against committed outcomes. When releases occur, they're preceded by comprehensive pre-release checklists, smoke test validation, rollback planning, and post-deploy verification to minimize production risk.

### Continuous Improvement & Learning

OctoAcme closes each sprint, release, or milestone with a retrospective—a 45–75 minute session where the team reflects on what went well, what could improve, and identifies 2–3 prioritized action items with clear owners and due dates. These action items are added to the project backlog and reviewed in weekly PM syncs to ensure accountability and impact measurement. The organization emphasizes psychological safety, blameless incident retrospectives, and data-informed decision-making. By treating retrospectives as a core ritual and connecting learnings back to the project backlog, OctoAcme builds a culture of iterative improvement where processes evolve and mature based on lived experience and team feedback.

## Core Roles

- **Project Manager**: Coordinates delivery, schedules, risks, communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Documentation Index

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme approach, roles, and artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, create lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turn approved initiatives into actionable plans and prioritized backlogs |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, quality standards, team rhythm, and progress tracking |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk management, stakeholder communication, escalation paths |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, track improvements, continuous improvement culture |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of typical roles and responsibilities |

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md).

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md).

**In execution phase?** See [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risks & Communication](./octoacme-risks-and-communication.md).

**Preparing a release?** Review [Release & Deployment](./octoacme-release-and-deployment.md).

**Project complete?** Run a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md).

## Contributing to OctoAcme Docs

To propose updates or add new content to the OctoAcme documentation, use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
