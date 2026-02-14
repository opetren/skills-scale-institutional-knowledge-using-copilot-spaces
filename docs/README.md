# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection of process documents guides how OctoAcme runs cross-functional projects that deliver product features, services, and integrations.

## Overview

OctoAcme follows a structured yet flexible project management approach built on customer-first principles, iterative delivery, and clear ownership. Every project progresses through a well-defined lifecycle from **initiation** to **planning**, **execution and tracking**, **release and deployment**, and finally **retrospective and continuous improvement**. Each phase has specific deliverables, checkpoints, and quality gates to ensure alignment across teams and stakeholders.

At the heart of OctoAcme's process are clearly defined **roles and personas**. The Project Manager (PM) coordinates delivery, schedules, risks, and communications. The Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success. Developers implement features collaboratively with design and testability in mind, while QA validates quality and acceptance criteria. Stakeholders provide essential inputs and approvals throughout the lifecycle. This role clarity enables teams to move quickly while maintaining accountability.

**Communication strategies** ensure transparency and rapid issue resolution. Weekly syncs between PM and PdM keep leadership aligned, while twice-weekly standups help delivery teams coordinate daily work and surface blockers. Monthly stakeholder updates provide visibility into progress and risks. The team uses a three-level escalation process—from team-level triage to PM escalation to sponsor-level intervention for business-critical issues. Key artifacts like the Project One-pager, risk register, and Definition of Done serve as shared sources of truth.

**Quality assurance practices** are integrated throughout delivery. Teams use GitHub Projects to track work across standard columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests remain small (ideally ≤400 lines), include issue links and acceptance criteria, and require automated tests and linting before review. At least one approval is required before merging. Unit tests, integration tests, and end-to-end smoke tests validate functionality, while security scanning in CI helps identify vulnerabilities early. Pre-release checklists ensure all acceptance criteria are met, CI passes, release notes are drafted, and rollback plans are documented before any production deployment.

## Process Documents

The following documents provide detailed guidance for each phase of the OctoAcme project lifecycle:

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's project approach, core roles, key artifacts, and communication cadence.

- **[OctoAcme Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize new work, including the Project One-pager template, stakeholder alignment, and the decision gate to move into planning.

- **[OctoAcme Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan, create a prioritized backlog with acceptance criteria, define the Definition of Done, and manage dependencies and risks.

- **[OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance including team rhythm, project board workflows, pull request conventions, quality and testing practices, and blocker escalation levels.

- **[OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, assess, mitigate, and monitor risks using the risk register, plus stakeholder communication templates and escalation paths.

- **[OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release process including pre-release requirements, deployment checklist, rollback procedures, and release notes template.

- **[OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives after sprints, releases, or incidents to capture learnings and convert them into actionable improvements.

- **[OctoAcme Roles and Personas](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles (Developers, Product Managers, Project Managers) including responsibilities, goals, and communication patterns.

---

**Need help?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick introduction, then dive into the specific process doc that matches your current project phase.
