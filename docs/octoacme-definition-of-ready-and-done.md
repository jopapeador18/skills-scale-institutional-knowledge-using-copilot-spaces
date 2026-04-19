# OctoAcme — Definition of Ready and Definition of Done

## Purpose
Provide clear, agreed-upon criteria that determine when a backlog item is ready to be worked on (Definition of Ready) and when completed work can be considered done (Definition of Done). Using these checklists consistently reduces ambiguity during sprint planning, PR review, and QA sign-off.

---

## Definition of Ready (DoR)

A backlog item is **Ready** when all of the following are true:

- [ ] The item has a clear, concise title
- [ ] A user story or problem statement is written (e.g., "As a [persona], I want [goal] so that [outcome]")
- [ ] Acceptance criteria are documented and agreed upon by PM and the team
- [ ] Dependencies and blockers have been identified and are either resolved or have a mitigation plan
- [ ] The item is estimated (T-shirt size or story points)
- [ ] Design assets or specs are available if UX work is required
- [ ] Linked issues, parent epics, or related documents are referenced

> **When to apply:** Use the DoR checklist during backlog refinement and sprint planning before pulling an item into the sprint. See [Project Planning](octoacme-project-planning.md) for full planning guidance.

---

## Definition of Done (DoD)

A work item is **Done** when all of the following are true:

- [ ] Code is implemented and meets the acceptance criteria
- [ ] Unit tests written and passing
- [ ] Integration/end-to-end tests updated or added where applicable
- [ ] CI pipeline passes (tests, lint, security scans)
- [ ] Code reviewed and approved (minimum one approval per team policy)
- [ ] Documentation updated (inline docs, README, or process docs as needed)
- [ ] QA sign-off obtained (manual or automated, per feature risk level)
- [ ] Feature flag or rollback plan documented if applicable
- [ ] PR linked to the relevant issue and acceptance criteria confirmed
- [ ] Item moved to **Done** on the project board

> **When to apply:** Use the DoD checklist before merging a PR and before marking an item Done on the board. See [Execution & Tracking](octoacme-execution-and-tracking.md) for workflow guidance.

---

## Roles and Responsibilities

| Role | DoR | DoD |
|---|---|---|
| Product Manager (PdM) | Author acceptance criteria and confirm DoR | Confirm acceptance criteria met |
| Project Manager (PM) | Confirm dependencies resolved | Confirm status and docs updated |
| Developer | Estimate and flag blockers | Implement, test, and request review |
| Scrum Master | Facilitate DoR review in planning | Facilitate DoD review in sprint review |
| QA/Testing | Clarify test scope in DoR | Provide QA sign-off |
| UX Designer | Provide design specs before item is Ready | Confirm design intent implemented |

---

## Tips for Use
- Review the DoR checklist during backlog refinement sessions, before items enter sprint planning.
- Review the DoD checklist as part of the PR review process and the sprint review ceremony.
- Adapt these checklists per project if necessary, but maintain the core criteria for consistency.
- Incomplete DoR items should be returned to the backlog and not pulled into the sprint.
