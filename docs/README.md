# OctoAcme Project Management Docs

This README serves as the top-level entry point and table of contents for OctoAcme's project management documentation.

## Overview

OctoAcme follows a structured, lifecycle-driven project management approach that spans five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager capturing the problem statement, SMART objectives, success metrics, and stakeholder alignment before any planning work begins. A formal decision gate ensures teams only proceed to planning when success criteria are clear, stakeholders are aligned, and team capacity is confirmed. During planning, the team breaks work into shippable increments with prioritized backlogs, T-shirt or story point estimates, a Definition of Done, a release plan, and a risk register — all maintained as living artifacts in the project repository.

OctoAcme projects are staffed with four core personas, each with distinct responsibilities. The **Project Manager (PM)** coordinates delivery, manages risks and schedules, and facilitates cross-team communication. The **Product Manager (PdM)** owns the product vision, prioritizes the backlog, and measures outcomes through data-driven decisions. **Developers** implement features, write tests, participate in design and code reviews, and help identify technical risks. **QA/Testing** validates quality against acceptance criteria. This clear ownership model is a foundational principle — every project has a named PM and Product Lead to prevent ambiguity and reduce single-person dependency risk.

Communication at OctoAcme is rhythmic and role-appropriate. The delivery team runs **daily 15-minute standups** focused on progress, blockers, and dependencies, with **weekly delivery syncs** for risk updates and a demo or review at the end of each sprint. PMs and PdMs hold a dedicated **weekly alignment meeting**, while stakeholders receive **monthly updates** with ad-hoc escalations as needed. Risk escalation follows a tiered path — from team-level triage in standup, to PM escalation to the Product Lead, up to sponsor-level escalation for business-impacting issues. A standardized weekly status template (progress, next steps, risks, asks) ensures consistent, transparent communication across all stakeholders.

Execution quality is enforced through a combination of workflow conventions and automated tooling. Pull Requests are kept small (≤400 lines when possible), must link to issues with acceptance criteria, and require CI checks — including automated tests, linting, and security scanning — before review. At least one approval is required before merging. Testing layers include unit tests, integration tests, end-to-end smoke tests, and manual QA for feature acceptance. After each sprint, release, or incident, the team runs a **timeboxed retrospective** (45–75 minutes) structured around what went well, what could improve, and 2–3 prioritized action items tracked in the project backlog. This continuous improvement loop, combined with velocity and burndown tracking, keeps teams iterative, accountable, and learning.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, roles, and lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and produce a Project One-pager |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable backlog, release plan, and milestone map |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, team rhythm, quality standards, and blocker escalation paths |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk Register format, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for all roles involved in OctoAcme projects |
