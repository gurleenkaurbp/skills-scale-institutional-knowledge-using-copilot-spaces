# OctoAcme Project Management Docs

This README provides an overview and quick links to all OctoAcme project management process documents. These artifacts standardize how we initiate, plan, execute, and continuously improve projects in the OctoAcme organization.

## Summary of Project Management Processes

### Project Lifecycle & Core Approach

OctoAcme operates on a structured, five-phase project lifecycle: initiation, planning, execution, release, and close with retrospectives. The organization prioritizes customer-first delivery through iterative, testable increments while maintaining clear ownership and data-informed decision-making. Each project is anchored by a lightweight Project One-pager that captures the problem statement, business goal, success metrics, stakeholders, timeline, risks, and resource needs. This initiation phase ensures stakeholder alignment and enables a go/no-go decision before committing to detailed planning. Once approved, teams move into planning by breaking work into prioritized, estimated backlog items with clear acceptance criteria, defining a Definition of Done, identifying dependencies, and mapping release milestones.

### Roles, Responsibilities & Communication Cadence

OctoAcme emphasizes clear role delineation with three primary personas: Project Managers (PM) coordinate delivery, manage schedules and risks, and facilitate communications; Product Managers (PdM) define outcomes, prioritize the backlog, and measure success; and Developers implement features, collaborate on design, and ensure code quality. QA/Testing validates acceptance criteria, and stakeholders provide inputs and approvals. The communication rhythm includes daily standups (15 minutes focused on progress and blockers), weekly syncs between PM and PdM, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. Risk escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

### Execution, Quality Assurance & Release Management

During execution and tracking, teams use a GitHub Projects board with columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility. Pull requests follow a disciplined workflow with small PRs (≤400 lines when possible), clear issue links and acceptance criteria in descriptions, automated CI tests and linting, and at least one approval before merging. Quality standards require unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Before release, teams conduct pre-release checks including passing CI and security scans, drafted release notes, documented rollback plans, and prepared smoke tests. Deployments follow a staged approach: deploy to staging, run smoke tests, deploy to production via automated pipeline when possible, run post-deploy verifications, and announce to stakeholders. The release notes template captures the release name, date, summary, notable changes, migration steps, and known issues.

### Continuous Improvement & Risk Management

OctoAcme embeds continuous improvement through retrospectives held after each sprint, release, or milestone. These structured sessions (45–75 minutes) capture what went well, what could improve, and prioritize 2–3 actionable items with clear owners and due dates. Risk management is systematic: teams identify risks during planning and execution, assess impact and likelihood, develop mitigation plans, and monitor status during weekly syncs using a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status). Stakeholder communication is central—teams maintain a single source of truth (project README or release doc) and provide weekly status updates covering progress, next steps, risks/blockers, and decisions needed. This combination of structured workflows, transparent communication, rigorous quality practices, and built-in retrospectives enables OctoAcme to deliver reliably while continuously learning and improving.

## Process Document Links

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme – Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme – Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme – Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme – Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
