# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This README provides an overview of the project management processes used at OctoAcme and links to all in-depth process documents. Use this as your entry point for project planning, execution, continuous improvement, and understanding team roles and responsibilities.

## OctoAcme Project Management Overview

OctoAcme follows a structured, iterative project lifecycle designed around customer value delivery and clear ownership. The methodology spans five core phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (building and testing in regular cadence), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings for continuous improvement).

Central to this approach is the **Project One-pager**—a lightweight artifact that consolidates the problem statement, success metrics, stakeholders, and timeline—which serves as the decision gate before committing resources to planning. This ensures that only well-validated initiatives move forward, reducing wasted effort and misalignment.

### Execution Rhythm & Workflows

Execution operates on a predictable rhythm anchored by daily standups (15 minutes, focused on progress and blockers), weekly delivery syncs (showcasing progress and flagged risks), and end-of-sprint demos. Work flows through a GitHub Projects board with columns: Backlog, Ready, In Progress, In Review, QA, and Done.

Pull requests are kept small (≤400 lines when possible) with clear issue links and acceptance criteria, and all changes pass automated CI tests, linting, and security scanning before review. Quality is enforced through:
- Unit tests for new logic
- Integration and end-to-end smoke tests for critical flows
- Manual QA when needed
- Continuous risk monitoring and escalation through three levels (team triage → PM to Product Lead → sponsor-level escalation)

### Roles & Accountability

Three core roles define accountability and decision-making:

- **Product Manager:** Owns the vision, prioritizes the backlog, and measures outcomes
- **Project Manager:** Coordinates delivery, manages schedules and risks, and ensures transparent communication
- **Developers:** Implement features, write tests, and collaborate on design and risk mitigation

Communication is structured around weekly PM-to-PdM syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates. A single source of truth (the project README or release document) ensures alignment across engineering, sales, support, and other stakeholder groups.

### Release & Continuous Improvement

Before any production deployment, the team verifies that all acceptance criteria are met, CI and security scans pass, release notes are drafted, and a rollback plan is documented. Releases are categorized as patches (hotfixes), minor (incremental features), or major (breaking changes), and include post-deploy verification and stakeholder announcement.

After each sprint, release, or incident, teams conduct a 45–75 minute retrospective to discuss what went well, what could improve, and to capture 2–3 prioritized action items. These improvements feed back into the backlog or process docs, reinforcing a culture of incremental learning and measurable impact.

---

## Process Documents Index

Use this index to navigate to the specific process guidance you need:

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, lifecycle, and communication cadence
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles and responsibilities in OctoAcme projects

### Project Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate business need, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into shippable increments, identifying dependencies, and defining Definition of Done
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality standards, and progress reporting
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release process, deployment checklist, and rollback procedures

### Ongoing & Cross-Phase
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register usage, escalation paths, and stakeholder communication strategies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives and convert learnings into actionable improvements

---

## Quick Start

**New to OctoAcme project management?**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the big picture
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to identify your role
3. Follow the appropriate phase guide based on where your project is in its lifecycle

**Launching a new project?**
1. Read [Project Initiation Guide](octoacme-project-initiation.md)
2. Create a Project One-pager and get stakeholder alignment
3. Move to [Project Planning](octoacme-project-planning.md) once approved

**Managing an active project?**
1. Use [Execution & Tracking](octoacme-execution-and-tracking.md) for daily guidance
2. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for risk and stakeholder updates
3. Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) at sprint/milestone boundaries

---

## Contributing to These Docs

These documents are living artifacts. When you identify gaps, improvements, or need to add new processes:

1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Include the rationale for your update and suggested content
3. Request review from stakeholders and team leads
4. Incorporate feedback and merge your changes

Your continuous input helps keep OctoAcme processes aligned with how the team actually works and what new team members need to know.
