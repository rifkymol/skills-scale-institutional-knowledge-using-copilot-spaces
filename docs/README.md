# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, iterative project management lifecycle designed to centralize institutional knowledge and ensure repeatable success. The process is divided into five distinct phases: Initiation, Planning, Execution, Release, and Closing. Each project is grounded by a **Project One-pager** that defines the problem and success metrics, which then evolves into an actionable backlog during the planning phase. Work is managed through a project board (typically GitHub Projects) using a transparent workflow that moves tasks from a prioritized backlog through development, review, and QA.

The framework relies on three core personas with clearly defined accountabilities. **Project Managers (PM)** coordinate schedules, risk mitigation, and stakeholder communication, while **Product Managers (PdM)** own the product vision and backlog prioritization. **Developers** are responsible for high-quality implementation, estimation, and technical design. This collaborative structure is supported by a rigorous communication cadence, including daily standups focused on blockers, weekly delivery syncs to flag risks, and monthly stakeholder updates to maintain alignment across the organization.

Quality and consistency are maintained through standardized workflows and strict **Definition of Done (DoD)** criteria. OctoAcme emphasizes small, testable increments, requiring Pull Requests to be under 400 lines when possible, accompanied by automated CI testing, linting, and at least one peer approval. Quality assurance is multi-layered, involving unit and integration tests, security scanning, and manual smoke tests for critical flows before any release. A robust risk management strategy is also central to execution, featuring a live **Risk Register** and tiered escalation paths (Team → PM → Product Lead → Sponsor) to address blockers before they impact business outcomes.

Finally, OctoAcme fosters a culture of continuous improvement by integrating **Retrospectives** at the end of every sprint or milestone. These sessions are used to identify process gaps and generate actionable improvement items that are fed back into the project backlog. By utilizing **GitHub Issue Templates** to propose updates to these living process documents, the team ensures that tacit knowledge is consistently captured, refined, and made accessible to all members, thereby reducing single-person dependency and accelerating onboarding.

---

## Process Documents Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management approach and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps and templates for kicking off a new project |
| [Project Planning](octoacme-project-planning.md) | Planning processes, backlog management, and sprint setup |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Workflow, Definition of Done, and progress tracking during delivery |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadence |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment process, and QA gates |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and process for capturing improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions and accountabilities for PMs, PdMs, and Developers |
