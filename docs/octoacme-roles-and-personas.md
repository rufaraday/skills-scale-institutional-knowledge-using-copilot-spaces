# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Key Interactions
- **With Product Managers**: Clarify acceptance criteria and ask for prioritization decisions
- **With Project Managers**: Provide estimates, flag blockers, participate in risk planning
- **With Platform/DevOps Engineers**: Troubleshoot infrastructure issues, coordinate deployment concerns
- **With Release Engineers**: Provide build artifacts and deployment runbooks
- **With UX Researchers**: Review design prototypes, implement accessibility requirements

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Key Interactions
- **With Project Managers**: Align on scope, timelines, and trade-offs; collaborate on risk management
- **With Developers**: Define and refine acceptance criteria; provide context for feature decisions
- **With UX Researchers**: Commission research, use findings to inform prioritization
- **With Support Lead**: Receive customer feedback to inform backlog prioritization
- **With Technical Program Managers**: Translate product priorities into coordinated technical milestones

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Key Interactions
- **With Product Managers**: Align on scope, timelines, and dependencies
- **With Developers**: Track progress, identify blockers, facilitate unblocking
- **With Technical Program Managers**: Coordinate cross-team dependencies and escalations
- **With Release Engineers**: Schedule releases, coordinate deployment timing
- **With Support Lead**: Incorporate customer issues into project risk management

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers coordinate complex, multi-team technical initiatives that span engineering disciplines and cross-functional dependencies. They ensure technical projects are well-scoped, feasible, and aligned with business goals.

### Responsibilities
- Coordinate complex technical projects involving multiple teams or systems
- Manage technical dependencies and integration points
- Run engineering-focused program cadence (technical design reviews, dependency tracking)
- Identify and mitigate technical risks early
- Create and maintain technical roadmaps and architecture decisions
- Facilitate alignment on technical trade-offs between teams

### Goals
- Ensure technical feasibility before committing to delivery timelines
- Minimize rework due to missed technical dependencies
- Accelerate time-to-market by coordinating technical effort efficiently
- Maintain architectural consistency across teams

### Typical Communication
- Technical design review facilitation
- Cross-team dependency tracking and escalation
- Technical roadmap and architecture decision docs
- Engineering-focused program reviews

### Key Interactions
- **With Project Managers**: Own technical dependencies; provide technical feasibility input to PM timelines
- **With Product Managers**: Translate product priorities into coordinated technical milestones; surface technical constraints
- **With Developers**: Facilitate design reviews, coordinate work across teams, surface blockers
- **With Platform/DevOps Engineers**: Coordinate infrastructure readiness, define platform constraints
- **With Release Engineers**: Coordinate staged deployments and rollback strategies for complex releases

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own user research, design exploration, and ensuring that features meet both user needs and acceptance criteria. They bridge customer insights and technical implementation.

### Responsibilities
- Conduct user research, usability testing, and user interviews
- Create prototypes, wireframes, and design specifications
- Ensure designs meet accessibility standards and acceptance criteria
- Participate in design reviews and iterative refinement
- Validate solutions with users before and after implementation
- Document design decisions and rationale

### Goals
- Deliver user-centered solutions that reduce support burden
- Validate product assumptions early to avoid rework
- Ensure consistent, accessible, and usable design across features
- Maximize customer satisfaction and product adoption

### Typical Communication
- Research findings and user personas
- Design prototypes and specifications in design tools
- Design review meetings and feedback loops
- Accessibility audit reports

### Key Interactions
- **With Product Managers**: Conduct research to inform prioritization; validate solutions through testing
- **With Developers**: Clarify design intent, review implementation against specs, conduct usability testing on builds
- **With Project Managers**: Provide design timeline estimates, flag design-related dependencies
- **With Support Lead**: Incorporate customer feedback and common issues into design improvements
- **With QA/Testing**: Define acceptance criteria for design quality and accessibility

---

## Platform / DevOps Engineer

### Role Summary
Platform and DevOps Engineers maintain the infrastructure, CI/CD pipelines, and operational foundations that enable teams to build and deploy reliably. They own platform reliability, security hardening, and observability.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines
- Manage cloud infrastructure, containerization, and deployment automation
- Implement security hardening and compliance controls
- Establish observability (logging, metrics, alerting) and runbook documentation
- Respond to platform-level incidents and remediate root causes
- Coordinate infrastructure changes and capacity planning
- Support Developers and Release Engineers with deployment concerns

### Goals
- Enable fast, reliable deployments with minimal manual overhead
- Minimize platform-related incidents and deployment failures
- Maintain security posture and compliance requirements
- Reduce time-to-resolution for production issues

### Typical Communication
- CI/CD pipeline status and change logs
- Infrastructure incident reports and postmortems
- Runbook and architecture documentation
- Security audit reports and compliance checklists

### Key Interactions
- **With Developers**: Support deployment issues, provide infrastructure constraints and guidance
- **With Release Engineers**: Ensure deployment pipelines are secure and efficient, coordinate staging/production deploys
- **With Project Managers**: Surface platform dependencies and constraints that affect timelines
- **With Technical Program Managers**: Coordinate infrastructure readiness for complex multi-team projects
- **With QA/Testing**: Support staging environment setup and smoke test infrastructure

---

## Release Engineer

### Role Summary
Release Engineers own the end-to-end release process: validating release readiness, coordinating staged deployments, running smoke tests, and maintaining rollback procedures. They are the custodian of deployment safety and post-release verification.

### Responsibilities
- Validate release checklists and acceptance criteria completion
- Coordinate staging and production deployments
- Run pre- and post-deployment smoke tests
- Maintain release notes and documentation
- Define and execute rollback procedures when needed
- Track deployment status and troubleshoot deployment failures
- Maintain release calendar and communicate deployment windows

### Goals
- Ensure zero or minimal production incidents from deployments
- Reduce deployment risk through rigorous testing and validation
- Enable rapid rollback when issues occur
- Provide clear visibility into release status and readiness

### Typical Communication
- Release readiness checklists and sign-offs
- Deployment schedules and window notifications
- Release notes and change summaries
- Post-deployment incident reports and rollback decisions

### Key Interactions
- **With Developers**: Validate that all acceptance criteria are met, collect deployment artifacts and runbooks
- **With Project Managers**: Coordinate release timing and dependencies, report release readiness status
- **With Platform/DevOps Engineers**: Coordinate CI/CD pipeline execution, troubleshoot deployment issues
- **With QA/Testing**: Coordinate smoke test execution and validation in staging/production
- **With Support Lead**: Notify of deployments, coordinate customer-facing announcements, handle post-deployment issue triage

---

## Support Lead / Customer Success Liaison

### Role Summary
Support Leads and Customer Success Liaisons serve as the voice of the customer within the project team. They triage customer-reported issues, surface high-impact problems, and help the team prioritize fixes based on customer impact.

### Responsibilities
- Triage and categorize customer-reported issues and bugs
- Surface high-impact customer problems to the product and engineering teams
- Maintain knowledge base articles and customer documentation
- Provide context on customer workflows and use cases
- Help prioritize hotfixes and escalations based on customer impact
- Coordinate customer communications for incidents and deployments
- Track customer satisfaction metrics and feedback trends

### Goals
- Reduce customer-facing issues by surfacing problems early
- Improve time-to-resolution for critical customer issues
- Increase customer satisfaction through proactive communication
- Inform product decisions with real customer use cases and pain points

### Typical Communication
- Customer issue summaries and impact assessments
- Customer feedback and feature requests
- Knowledge base articles and FAQ updates
- Incident notifications and status updates to customers

### Key Interactions
- **With Product Managers**: Provide customer feedback to inform prioritization and roadmap decisions
- **With Developers**: Provide context on customer-reported bugs, help reproduce issues
- **With Project Managers**: Escalate high-impact customer issues that need timeline prioritization
- **With QA/Testing**: Coordinate testing of fixes for customer-reported issues
- **With Release Engineers**: Notify of deployments, help communicate fixes to affected customers
- **With Platform/DevOps Engineers**: Provide customer context for platform-level incidents, coordinate incident communication

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Key Interactions" section to understand how roles coordinate and reduce handoff delays.
- When onboarding new team members, assign them a primary persona and explain how they interact with the broader team.
