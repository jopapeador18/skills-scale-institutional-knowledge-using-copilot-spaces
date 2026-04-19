# OctoAcme Project Management Docs

Welcome to the documentation hub for OctoAcme's project management practices. This README provides an overview of how projects are managed at OctoAcme, plus links to all detailed process documents.

## Overview of Project Management Processes

OctoAcme runs projects through a lightweight, repeatable lifecycle that emphasizes clear outcomes, ownership, and iterative delivery. Work begins with **Initiation**, where teams validate the business need and success metrics using a **Project One-pager**, identify stakeholders, outline a high-level timeline and milestones, and capture early risks and resource needs. Once a go/no-go decision is made, the project moves into **Planning**, where the team holds a kickoff, breaks work into shippable increments, builds a prioritized backlog with acceptance criteria, estimates scope, defines a **Definition of Done**, and maps dependencies and a release timeline.

Execution is managed with a consistent team rhythm and delivery workflow. OctoAcme uses a project board (e.g., GitHub Projects) to track work through stages like **Backlog → Ready → In Progress → In Review → QA → Done**, supported by a pull request process that favors small PRs, links work to issues and acceptance criteria, and requires review approvals before merge. The team maintains regular ceremonies—short daily standups, weekly delivery syncs, and milestone/sprint demos—to surface blockers, confirm progress, and keep stakeholders aligned. Status reporting follows a simple weekly update format covering progress, next steps, risks/blockers, and asks/decisions.

Roles are explicitly defined to ensure shared accountability: **Project Managers** coordinate delivery, timelines, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** design, build, and test features while helping identify technical risks; and **QA/Testing** validates quality and acceptance criteria, with stakeholders providing inputs and approvals as needed. Risk management is handled through a maintained **Risk Register** (tracking impact, likelihood, owner, mitigation, and status), reviewed during weekly syncs, and escalated via a clear path from team triage to PM/product leadership and, if necessary, sponsor-level escalation—including a dedicated path for security incidents.

Quality assurance and release practices are built into the workflow rather than treated as a final step. During execution, teams apply layered testing (unit, integration, and end-to-end smoke tests where appropriate), run CI checks (tests, linting, and security scanning), and perform manual QA when needed for feature acceptance. Releases follow a standard checklist: ensure acceptance criteria are met, CI/security checks pass, release notes and rollback plans are prepared, deploy to staging with smoke tests, deploy to production via an automated pipeline when possible, verify post-deploy health, and communicate outcomes. After milestones, releases, or incidents, OctoAcme runs retrospectives to capture learnings and track a small number of owned action items back into the backlog to continuously improve the process.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
