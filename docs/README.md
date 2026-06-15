# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This README provides a concise overview of how OctoAcme runs projects and links to detailed process guides for each phase of the project lifecycle.

## Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first prioritization**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Projects progress through five distinct phases—Initiation, Planning, Execution, Release, and Close & Retrospective—each with defined artifacts and decision gates to ensure alignment and transparency.

### Core Roles & Responsibilities

Three primary personas drive project success:

- **Developers** design, build, test, and deliver software components. They collaborate on implementation, maintain quality through code reviews and testing, and help identify technical risks.
- **Product Managers** define the product vision, prioritize the backlog, and measure outcomes through success metrics and user research.
- **Project Managers** coordinate delivery activities, manage risks and dependencies, and ensure stakeholder alignment and transparent communication.

### Key Execution Practices

OctoAcme emphasizes **iterative delivery** through sprint-based planning using a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done). Work is prioritized with clear acceptance criteria and a Definition of Done, keeping pull requests small (≤400 lines) and requiring automated CI/CD checks and approvals before merging.

**Quality assurance** is embedded throughout execution: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance when needed.

**Risk management** is proactive, not reactive. Teams maintain a Risk Register and escalate blockers through three levels (team triage → PM/Product Lead → Sponsor). Communication happens via twice-weekly standups, weekly PM/Product Manager syncs, and monthly stakeholder updates.

**Continuous improvement** is institutionalized through structured retrospectives held after each sprint, release, or milestone. Teams capture learnings, generate 2–3 prioritized action items with clear owners, and measure the impact of improvements.

## Process Documents

The following documents provide detailed guidance for each phase of the project lifecycle:

### Planning & Preparation
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery

### Delivery & Operations
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized approach to releases to reduce risk and improve observability

### Learning & Improvement
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into actionable improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles and responsibilities in OctoAcme projects

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick introduction.
2. **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective.
3. **Looking for specific guidance?** Use the document index above to jump to the relevant phase or topic.
4. **Integrating with Copilot?** Add these docs to `.copilot/` in your project repository to ground Copilot Spaces with your project's processes.

## Keeping This Documentation Current

As OctoAcme's processes evolve, please:
- Update these docs to reflect new practices and learnings
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose additions or updates
- Keep the links and summaries in this README synchronized with the actual documents

---

*Last updated: June 15, 2026*
