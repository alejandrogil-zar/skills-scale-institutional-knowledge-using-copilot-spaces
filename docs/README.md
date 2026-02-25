# OctoAcme Project Management Docs

Welcome to the central documentation hub for OctoAcme project management. Here you'll find a summary of our core methodology, roles, communications, and all current process resources.

## Project Management Process Overview

OctoAcme employs a structured, customer-first approach organized across five distinct phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The **Initiation** phase validates business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and initial timeline. Once approved, the **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This structured handoff ensures that teams move into **Execution** with clear ownership and measurable goals, using GitHub Projects for visualization and maintaining small pull requests (≤400 lines) with automated CI/CD testing before requiring at least one approval. The **Release** phase standardizes deployment processes with pre-release checklists, smoke tests, and documented rollback plans, while the final **Close & Retrospective** phase captures learnings and converts them into actionable improvements tracked through the project backlog.

OctoAcme defines clear roles and responsibilities to maintain accountability and reduce silos. **Product Managers** own the vision, prioritization, and success metrics; **Project Managers** coordinate schedules, risks, and communications; **Developers** implement features with quality and testability in mind; and **QA/Testing** validates acceptance criteria. Each project has named PM and Product Lead owners, and the organization emphasizes psychological safety and data-informed decision-making. Communication happens through a consistent cadence: daily standups (15 minutes) focusing on progress and blockers, weekly delivery syncs between PM and Product Lead, twice-weekly team standups, and monthly stakeholder updates. This multi-layered communication approach ensures alignment across engineering, product, and stakeholder groups.

Quality assurance is embedded throughout the delivery cycle, with unit tests, integration tests, and end-to-end smoke tests required before release, along with security scanning in CI and manual QA for feature acceptance when needed. Risk management is formalized through a Risk Register that tracks identification, assessment, mitigation, and monitoring of blockers. Escalation follows a structured path: team-level triage in daily standups (Level 1), PM escalation to Product Lead and dependent teams (Level 2), and sponsor-level escalation for business-impacting issues (Level 3). Teams also maintain a culture of continuous improvement by reviewing action items from retrospectives in weekly syncs and measuring the impact of process changes, reinforcing OctoAcme's commitment to iterative delivery and organizational learning.

## Docs Index

Refer to these documents for detailed guidance and templates on managing OctoAcme projects end to end:

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
