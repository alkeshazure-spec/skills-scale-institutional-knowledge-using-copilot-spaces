# OctoAcme Project Management Processes

Welcome to OctoAcme's program and project management documentation. This folder contains guidance for running projects with clear ownership, iterative delivery, and data-driven decisions.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety. The organization defines distinct roles—Project Managers (PM) coordinate schedules and communications, Product Managers define outcomes and prioritize work, Developers implement features collaboratively, and QA teams validate quality—each with explicit responsibilities and communication touchpoints.

Execution and delivery are managed through a well-defined team rhythm and artifact structure. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain transparency, conduct daily standups focused on progress and blockers, and hold weekly delivery syncs to assess risk and dependencies. Pull requests follow lean conventions—preferably under 400 lines, linked to issues with acceptance criteria, and requiring at least one approval before merge. Quality is baked in through unit testing, integration testing, smoke tests before release, and security scanning in CI.

Communication and transparency are central to OctoAcme's approach, ensuring all stakeholders remain informed and aligned. The organization maintains a consistent cadence: weekly PM and Product Manager syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates, with ad-hoc escalations as needed. A single source of truth—the project repository—holds the Project Charter, roadmap, backlog, risk register, and retrospective notes, making history and decisions searchable and repeatable. This commitment to documented processes, clear roles, and regular feedback loops helps OctoAcme accelerate onboarding, reduce single-person dependencies, and ensure consistent, reliable project delivery.

## Core Elements

**Roles:** Project Manager (PM), Product Manager (PdM), Developers, QA, Stakeholders

**Rhythm:** Daily standups, weekly delivery syncs, sprint demos and reviews

**Artifacts:** Project one-pager, roadmap and release plan, prioritized backlog, acceptance criteria and Definition of Done, risk register, retrospective notes

**Workflows:** Prioritized backlog, small PRs (≤400 lines), CI testing and linting, project board tracking, automated deployments

## Process Documents

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence.

- [**Project Initiation Guide**](octoacme-project-initiation.md) — Initial steps to validate business need, align stakeholders, and create a lightweight plan including the Project One-pager template.

- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan: backlog creation, estimation, dependencies, and release planning.

- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day execution guidance: team rhythm, PR workflow, quality practices, metrics, and blocker escalation.

- [**Risks & Communication**](octoacme-risks-and-communication.md) — Risk management lifecycle, stakeholder communication templates, and escalation paths.

- [**Release & Deployment**](octoacme-release-and-deployment.md) — Standardized release process: types, pre-release requirements, deployment checklist, and rollback procedures.

- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Structure and running retrospectives to capture learnings and drive actionable improvements.

- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed role definitions for Developers, Product Managers, and Project Managers with responsibilities and typical communication patterns.

## How to Use These Docs

1. **For new projects:** Start with [Project Initiation Guide](octoacme-project-initiation.md) to define the problem, goals, and stakeholders.

2. **For ongoing execution:** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily standup guidance, PR workflow, and quality practices.

3. **For releases:** Follow the [Release & Deployment](octoacme-release-and-deployment.md) guide to standardize how features reach production.

4. **To propose updates:** Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. Link back to the specific document and include clear acceptance criteria.

5. **To understand roles:** Reference [Roles & Personas](octoacme-roles-and-personas.md) for explicit responsibilities and communication patterns for your team.

## Key Principles

- **Customer-first:** Prioritize customer value and usability in every decision.
- **Iterative delivery:** Ship small, testable increments and gather feedback early.
- **Clear ownership:** Each project has named PM and Product Manager with explicit responsibilities.
- **Data-informed:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives.

---

For questions or suggestions about these processes, open an issue using the process doc update template or reach out to your Product Lead or Project Manager.
