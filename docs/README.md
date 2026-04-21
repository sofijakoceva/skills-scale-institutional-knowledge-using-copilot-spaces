# OctoAcme Project Management Docs

This file serves as a centralized entry point and overview for all OctoAcme project management process documentation. Use the index below to navigate to individual process guides.

## Summary

OctoAcme follows a structured, iterative project lifecycle built on five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, stakeholder list, and initial risk inventory. A formal decision gate — requiring clear success metrics, stakeholder alignment, and confirmed team availability — must be passed before any work moves into planning. This customer-first approach ensures that only well-validated, prioritized work enters the delivery pipeline.

Three core personas drive project delivery at OctoAcme. **Project Managers (PMs)** own delivery coordination, schedules, risk tracking, and cross-team communication. **Product Managers (PdMs)** define the product vision, own the backlog, and measure outcomes against data-driven success metrics. **Developers** implement features, maintain test coverage, and actively participate in planning and design reviews. Together, these roles operate around a shared set of artifacts — including the Project Charter, Risk Register, Sprint Backlog, and Definition of Done — that keep teams aligned throughout the lifecycle. A QA function validates acceptance criteria and quality standards before any release is approved.

Communication at OctoAcme is structured and predictable. Teams run **twice-weekly standups** to surface blockers and dependencies, **weekly delivery syncs** between PM and PdM to assess progress and flag risks, and **monthly stakeholder updates** to maintain executive and cross-functional alignment. Risk management is continuous: risks are captured in a living Risk Register (tracking impact, likelihood, owner, and mitigation plan) and reviewed at every weekly sync. A tiered escalation path — from team-level triage → PM → Product Lead → Sponsor — ensures that issues are resolved at the right level without unnecessary noise, with a separate track for security incidents.

Quality assurance and continuous improvement are embedded throughout the entire process. During execution, OctoAcme enforces small pull requests (≤400 lines), mandatory CI checks (automated tests, linting, and security scanning), and at least one peer review before merging. Releases are gated behind passing CI, acceptance criteria sign-off, documented rollback plans, and staging smoke tests. After each sprint, release, or incident, the team holds a timeboxed **retrospective** to capture what went well, identify improvements, and commit to 2–3 prioritized action items with clear owners and due dates. These actions feed back into the project backlog, creating a measurable culture of iterative, data-informed continuous improvement.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
