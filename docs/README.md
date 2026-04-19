# OctoAcme Project Management Docs

Welcome to the documentation hub for OctoAcme's project management practices. This README provides an overview of how projects are managed at OctoAcme, plus links to all detailed process documents.

## Overview of Project Management Processes

OctoAcme runs projects through a lightweight, repeatable lifecycle that emphasizes clear outcomes, ownership, and iterative delivery. The lifecycle follows five key phases:

- **Initiation** — Validate the business need and success metrics using a Project One-pager, identify stakeholders, outline a high-level timeline and milestones, and capture early risks and resource needs.
- **Planning** — Hold a kickoff, break work into shippable increments, build a prioritized backlog with acceptance criteria, estimate scope, define a Definition of Done, and map dependencies and a release timeline.
- **Execution & Tracking** — Deliver work iteratively using a project board (Backlog → Ready → In Progress → In Review → QA → Done), with regular standups, weekly delivery syncs, and milestone demos.
- **Release & Deployment** — Follow a standard release checklist: verify acceptance criteria, pass CI/security checks, prepare release notes and rollback plans, deploy to staging, smoke-test, then promote to production and verify health.
- **Retrospective & Continuous Improvement** — After milestones or incidents, capture learnings and feed a small set of owned action items back into the backlog.

Execution is supported by a consistent delivery workflow. OctoAcme favors small pull requests linked to issues and acceptance criteria, with required review approvals before merge. Status reporting uses a simple weekly format covering progress, next steps, risks/blockers, and asks/decisions. This cadence keeps all team members and stakeholders aligned throughout delivery.

Roles and responsibilities are explicitly defined to ensure shared accountability. **Project Managers** coordinate delivery, timelines, risks, and communications. **Product Managers** define outcomes, prioritize the backlog, and measure success. **Developers** design, build, and test features while helping identify technical risks. **QA/Testing** validates quality and acceptance criteria, and **Stakeholders** provide inputs and approvals. Risk management is handled through a maintained **Risk Register** reviewed during weekly syncs and escalated via a clear path—from team triage to PM/product leadership and, if necessary, sponsor-level escalation.

Quality assurance is built into every phase rather than treated as a final gate. Teams apply layered testing—unit, integration, and end-to-end smoke tests where appropriate—and run CI checks covering tests, linting, and security scanning. Manual QA is performed when needed for feature acceptance. After every major milestone or release, OctoAcme holds a retrospective to surface learnings and continuously improve both the product and the process.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
