# OctoAcme Project Management Docs

OctoAcme uses a lightweight, repeatable delivery lifecycle focused on customer value, clear ownership, and iterative execution. Projects move through **Initiation → Planning → Execution → Release → Close/Retrospective**, with a small set of source-of-truth artifacts such as the project one-pager, prioritized backlog, Definition of Done, risk register, and retrospective action items.

Day-to-day delivery is tracked through a practical workflow and team rhythm. Work typically flows on the project board from **Backlog → Ready → In Progress → In Review → QA → Done**, while pull requests stay small and reviewable, link to issues and acceptance criteria, and require approvals before merge. Teams keep momentum with daily standups, weekly delivery syncs, and sprint or milestone demos/reviews.

Roles are explicit to reduce ambiguity and improve accountability. The **Project Manager (PM)** coordinates schedules, risks, dependencies, and stakeholder communication; the **Product Manager (PdM/Product Lead)** defines outcomes and prioritization; **Developers** build and maintain solutions; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide input and approvals at key checkpoints. Communication follows a regular cadence with weekly or milestone-based updates, a clear escalation path (**Team-level triage → PM → Product Lead → Sponsor**), and continuous risk/dependency tracking in the risk register.

Quality is treated as a continuous practice across execution and release, not a final gate. OctoAcme expects **unit tests** for new logic, **integration tests** where applicable, and **smoke tests** for critical flows before release, supported by CI checks for linting and security scanning. The process emphasizes small PRs (often targeting <=400 lines when possible), passing CI before review, and required approvals as part of consistent release readiness.

## Key process documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
