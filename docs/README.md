# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation hub. These guides standardize how we run projects, coordinate delivery, and measure success so new teammates and stakeholders can quickly find the right processes and artifacts.

OctoAcme follows an iterative, customer-first approach with clear ownership for each initiative: a named Project Manager (PM) and Product Manager (PdM) supported by developers, QA, and stakeholders. The process lifecycle moves through initiation, planning, execution, release, and retrospective. At initiation we capture a one‑pager to align goals and stakeholders; planning breaks approved work into a prioritized backlog with acceptance criteria and a Definition of Done; execution uses a project board and small, testable PRs; and retrospectives turn learnings into tracked action items.

Workflows and day-to-day practices emphasize predictability and low cognitive load. Use the project board columns (Backlog, Ready, In Progress, In Review, QA, Done) to show work state. Pull requests should be small and link back to issue acceptance criteria, run CI (tests, linting, security scans) before review, and require at least one approval prior to merge. Communication cadence includes daily standups for progress and blockers, weekly delivery syncs for progress and risk review, and regular PM+PdM alignment meetings. Templates and escalation paths (team → PM → Product Lead → Sponsor; security incidents follow the security runbook) ensure consistent messaging and rapid resolution of blockers.

Quality is enforced through tests and CI: developers add unit and integration tests, critical flows receive end-to-end smoke tests, and automated security scanning runs in CI. Releases follow a checklist (staging smoke tests, rollback plan, post-deploy verifications) and include an incident playbook for fast mitigation. Continuous improvement is driven by regular retrospectives with prioritized, tracked action items and dashboards (velocity, burndown, operational signals) to monitor progress and health.

## Process documents
- [Project Management Overview](octoacme-project-management-overview.md) — Roles, principles, and lifecycle
- [Project Initiation](octoacme-project-initiation.md) — One-pager, stakeholder alignment, and decision gates
- [Project Planning](octoacme-project-planning.md) — Backlog, estimates, Definition of Done
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, board workflow, PR guidance
- [Release & Deployment](octoacme-release-and-deployment.md) — Release types, deployment checklist, rollback playbook
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register and stakeholder templates
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking
- [Roles & Personas](octoacme-roles-and-personas.md) — Role definitions and responsibilities

## Quick start by role
- Project Managers: Start with the Overview, then Project Planning and Risk Management.
- Product Managers: Begin with Project Initiation and Planning for goals and acceptance criteria.
- Developers: Read Execution & Tracking for workflow, PR expectations, and QA guidance.
- QA/Testing: Consult Execution & Tracking and Release & Deployment for test plans and pre-release checks.

## How to request doc updates
Use the process update issue template at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to propose additions or edits to these documents.
