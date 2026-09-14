# OctoAcme Project Management Documentation

## Overview

OctoAcme uses an iterative, customer-first approach to project management that emphasizes clear ownership, data-informed decisions, and psychological safety. This documentation guides teams through all phases of project delivery: from initiation through retrospectives and continuous improvement.

OctoAcme follows a structured lifecycle spanning five key phases: **Initiation** (validating business need and stakeholder alignment through a lightweight One-pager), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (building, testing, and reviewing with daily standups and weekly syncs), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Close & Retrospective** (capturing learnings and driving continuous improvement). This approach ensures that every project starts with a clear problem statement and measurable success metrics, moves through structured planning with dependency management, and concludes with intentional reflection to improve future execution.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documentation

### Project Lifecycle

| Phase | Document | Purpose |
|-------|----------|---------|
| Overview | [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme methodology, roles, and artifacts |
| Initiation | [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work |
| Planning | [Project Planning](octoacme-project-planning.md) | Creating actionable plans and backlog |
| Execution | [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution and progress tracking |
| Risk & Communication | [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification and stakeholder communication |
| Release | [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release processes |
| Close & Learn | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Learning and improvements |

### Roles & Support

- [Roles & Personas](octoacme-roles-and-personas.md) — Role descriptions for Developers, Product Managers, and Project Managers

## Quick Reference

### Communication Cadence

- **Daily standups** (15 min) — Focus on progress, blockers, dependencies
- **Weekly PM + PdM sync** — Alignment on priorities and risks
- **Twice-weekly delivery team standups** — Or as agreed by team
- **Monthly stakeholder updates** — High-level progress and status
- **Sprint retrospectives** — After each iteration or milestone

### Core Roles

| Role | Responsibility |
|------|-----------------|
| **Project Manager** | Coordinates delivery, manages schedules, risks, and communications |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success |
| **Developers** | Implement features, collaborate on design and testability |
| **QA/Testing** | Validates quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

### Quality & Execution Standards

- Use GitHub Projects board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Keep Pull Requests small (≤ 400 lines when possible)
- Require at least one approval before merging
- Run automated tests, linting, and security scanning in CI
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release

### Risk Management & Escalation

**Three-Level Escalation Model:**
1. **Team-level**: Triage in daily standup
2. **PM escalation**: To Product Lead and dependent teams
3. **Sponsor-level**: For business-impacting issues

**Risk Register Tracking:**
- ID, Description, Impact, Likelihood, Owner, Mitigation Plan, Status
- Reviewed weekly during syncs

## Issue Templates

Process documentation updates are managed via issue templates:

- [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Request new content or updates to process documentation

## Getting Started

**For new team members:**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your role and responsibilities
3. Bookmark this README as your central reference point

**For project kickoff:**
1. Follow [Project Initiation](octoacme-project-initiation.md) to validate the project
2. Use [Project Planning](octoacme-project-planning.md) to create your backlog and timeline
3. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance

**For stakeholder communication:**
- Use templates in [Risk Management & Communication](octoacme-risks-and-communication.md)
- Track progress against success metrics from your Project One-pager

**For release:**
- Follow [Release & Deployment](octoacme-release-and-deployment.md) checklist
- Prepare rollback and incident response plans

**For continuous improvement:**
- Run retrospectives per [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Capture learnings and feed improvements back into these docs

---

*Last updated: 2026-09-14*
