# OctoAcme Project Management Docs

This folder contains OctoAcme’s project management playbook — a concise, opinionated set of practices, templates, and checklists teams use to plan, execute, and deliver features reliably. The approach is iterative and customer-focused: projects move through a lightweight lifecycle (Initiation → Planning → Execution & Tracking → Release → Retrospective) and rely on small, testable increments and measurable success criteria.

Workflows emphasize short feedback loops and clear handoffs. Planning produces a prioritized backlog with acceptance criteria and a Definition of Done. Execution is driven from a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request workflow (small PRs, linked issues, CI checks, and required approvals). Regular cadences — daily standups, weekly delivery syncs, and sprint/milestone demos — keep work visible and reduce surprises.

Roles and responsibilities are explicit so accountability is clear: Product Managers own problems and success metrics, Project Managers coordinate schedules, risks, and communication, Developers build and test, QA validates acceptance criteria, and Stakeholders provide input and approvals. Role descriptions and typical responsibilities are documented in the Roles & Personas doc to help teams onboard and align quickly.

Quality assurance and release gates are embedded in CI/CD and release practices. Tests (unit, integration, and smoke), security scans, and manual QA (when needed) must pass before production deploys. Releases follow documented pre-release checks, rollback plans, and post-deploy verifications. Risks are tracked in a simple Risk Register and escalated via defined paths; retrospectives convert learnings into actionable backlog items to drive continuous improvement.

Process documents (open any file to read the full guidance):
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

How to propose updates
- Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to propose additions or updates.
- When submitting changes, link to the relevant issue, include acceptance criteria, and follow the review checklist.
