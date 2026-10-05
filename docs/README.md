# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured project lifecycle with clear roles, processes, and artifacts to ensure customer-first delivery, iterative progress, and data-informed decisions. This documentation centralizes guidance for all phases of project execution, from initiation through retrospective, enabling teams to collaborate effectively and scale institutional knowledge.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

### 1. [Project Initiation](octoacme-project-initiation.md)
Validate business need, identify stakeholders, and decide go/no-go for planning.
- **Key deliverable**: Project One-pager with problem, goal, and success metrics
- **Template**: Use the initiation template for structured onboarding

### 2. [Project Planning](octoacme-project-planning.md)
Break work into shippable increments, identify dependencies, and align timelines.
- **Key deliverable**: Prioritized backlog with acceptance criteria and Definition of Done
- **Scope**: T-shirt sizing or story points, risk register, release plan

### 3. [Execution & Tracking](octoacme-execution-and-tracking.md)
Manage day-to-day execution, track progress, and maintain team rhythm.
- **Key activities**: Daily standups, weekly delivery sync, quality assurance
- **Tools**: Project board, PR workflow, CI/CD pipelines

### 4. [Release & Deployment](octoacme-release-and-deployment.md)
Standardize releases to production with reduced risk and improved observability.
- **Key activities**: Pre-release checklist, deployment, rollback planning
- **Types**: Patch, Minor, Major releases

### 5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements.
- **Timing**: After each sprint, release, or important milestone
- **Outcome**: Prioritized action items with owners and timelines

## Cross-cutting Resources

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Manage risks and dependencies throughout the project lifecycle.
- Risk Register template and lifecycle
- Stakeholder communication templates
- Escalation paths

### [Project Management Overview](octoacme-project-management-overview.md)
High-level introduction to OctoAcme approach, core roles, and key artifacts.

### [Roles & Personas](octoacme-roles-and-personas.md)
Detailed descriptions of Project Manager, Product Manager, Developer, and QA roles.

## Project Management Processes Summary

OctoAcme operates through a structured lifecycle that begins with initiation, moves into planning, then execution, release, and closeout. The core intent is to align work around customer value, measurable outcomes, and iterative delivery. Each project is expected to have a clear charter or one-pager, a defined team, milestone timeline, and risk list, and to progress through a defined board workflow such as Backlog → Ready → In Progress → In Review → QA → Done. This keeps work visible, prioritized, and grounded in shared criteria for progress and completion.

The process documents emphasize a clear set of roles and responsibilities. Product leads define the problem, vision, and success measures; project managers coordinate delivery, schedule, communication, dependencies, and risk; developers build and test solutions; QA validates acceptance criteria and release readiness; and stakeholders provide input, priorities, and approvals. The documentation also reinforces a culture of clear ownership, evidence-based decisions, and psychological safety, so teams can collaborate effectively and learn quickly while staying aligned on outcomes.

Communication is treated as a critical operational discipline. OctoAcme uses weekly syncs between PM and product leadership, twice-weekly or agreed standups for delivery teams, milestone-based stakeholder updates, and escalation paths for blockers. The team is expected to maintain a single source of truth for status, such as a project README or release document, and to document progress, next steps, risks, dependencies, and decisions in shared artifacts. Risk and issue management are tied directly to this communication rhythm, with escalation moving from the team to project management to product leadership and, when needed, executive sponsors.

Quality assurance is built into the workflow rather than treated as a separate phase. New work is expected to include clear acceptance criteria and definition of done, while delivery practices emphasize small PRs, code review, CI validation, unit and integration tests, and smoke testing for high-risk workflows. Security scanning and manual QA are also required for critical work, and releases must meet pre-release checks, include rollback plans, and undergo post-deployment verification. After releases or milestones, teams conduct retrospectives to capture lessons learned, define action items, and convert improvements into ongoing process refinement.

## Issue Templates

To standardize process documentation requests, use the following template:
- [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Submit updates or new content to process docs

## Quick Links

- [Project Management Overview](octoacme-project-management-overview.md) — Start here for a quick intro
- [Risk & Communication Guide](octoacme-risks-and-communication.md) — Escalation paths and stakeholder communication
- [Roles & Personas](octoacme-roles-and-personas.md) — Understand team responsibilities
