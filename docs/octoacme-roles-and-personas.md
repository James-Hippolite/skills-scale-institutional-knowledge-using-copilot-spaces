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

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and ensure that all deliverables meet acceptance criteria and quality standards before release. They collaborate with product and development teams to define testability requirements early.

### Responsibilities
- Define testing strategy and test plan aligned with release milestones
- Create acceptance criteria checklists in collaboration with Product Manager and Developers
- Execute manual QA and validate automated test coverage
- Identify and log defects with clear reproduction steps
- Participate in release readiness reviews and smoke testing
- Mentor team on testing best practices and Definition of Done

### Goals
- Deliver high-quality, reliable features that meet user expectations
- Reduce defects in production through early and thorough testing
- Enable fast, confident releases

### Interaction with Existing Roles
- **Developers**: Partner on test strategy, acceptance criteria, and test automation during sprint planning
- **Product Manager**: Align on quality expectations and acceptance criteria in requirements definition
- **Project Manager**: Report quality metrics and blockers in status updates and escalations

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Daily standup status on test coverage and blockers
- QA sign-off on features before release

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business and organizational interests. They provide strategic direction, approve major decisions, and ensure alignment between delivery and business goals.

### Responsibilities
- Approve project charter, scope, and success metrics
- Provide budget, resource, and timeline constraints
- Escalate blockers that affect business delivery
- Receive and act on project status updates
- Participate in release reviews and major milestone decisions

### Goals
- Ensure project delivers measurable business value
- Maintain alignment between delivery team and organizational priorities
- Mitigate business risk through timely escalation

### Interaction with Existing Roles
- **Product Manager**: Align on priorities, business constraints, and success metrics
- **Project Manager**: Escalate blockers, budget requests, and timeline decisions; receive status updates
- **Developers & QA/Testing Lead**: Indirectly influence via PM; may participate in release reviews

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalations and decision requests
- Release announcements and post-release impact reviews

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide architectural and design decisions, manage technical risk, and ensure solutions are scalable, maintainable, and aligned with system capabilities.

### Responsibilities
- Review and approve technical design approaches
- Identify technical risks and propose mitigations
- Collaborate on technology trade-offs and sizing estimates
- Mentor Developers on best practices and patterns
- Participate in architecture reviews and performance planning

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and rework
- Enable fast, reliable delivery through good design

### Interaction with Existing Roles
- **Developers**: Guide on technical design decisions and code quality standards; review architecture and implementation
- **Product Manager**: Advise on feasibility, effort, and technical trade-offs during planning
- **Project Manager**: Flag technical risks and dependencies; estimate effort impact on schedules

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning and estimation collaboration
- Risk registers and dependency management

---

## Designer/UX Lead

### Role Summary
Designers and UX Leads define user experience requirements, create prototypes, and validate that solutions meet usability and user needs.

### Responsibilities
- Conduct user research and create user stories and personas
- Design wireframes, prototypes, and user flows
- Define usability acceptance criteria
- Validate designs with users and stakeholders
- Ensure consistency with design system and branding

### Goals
- Deliver user-centered, intuitive solutions
- Minimize rework due to usability issues
- Maximize user adoption and satisfaction

### Interaction with Existing Roles
- **Product Manager**: Collaborate on feature definition, user needs, and acceptance criteria
- **Developers**: Share designs and usability requirements; participate in design review and implementation discussions
- **QA/Testing Lead**: Define usability test cases and acceptance criteria validation

### Typical Communication
- Product planning and requirements workshops
- Design review sessions with Developers and Stakeholders
- Usability testing and feedback incorporation

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that all work meets security standards, compliance requirements, and risk management expectations.

### Responsibilities
- Define security and compliance requirements in planning
- Review designs and code for security vulnerabilities
- Ensure security scanning is configured and passing in CI
- Manage security incident response and post-incident reviews
- Maintain risk register for security and compliance risks
- Participate in release reviews and go/no-go decisions

### Goals
- Prevent security breaches and compliance violations
- Build secure-by-design solutions
- Maintain organizational trust and regulatory standing

### Interaction with Existing Roles
- **Product Manager**: Define security and compliance requirements early in planning
- **Developers**: Review code and design for security issues; guide on secure coding practices
- **QA/Testing Lead**: Ensure security testing is part of acceptance criteria
- **Project Manager**: Escalate security risks and compliance blockers; participate in release gate reviews

### Typical Communication
- Planning sessions and acceptance criteria definition
- Security reviews and incident response
- Weekly risk register updates and escalations

---

## Scrum Master/Delivery Coach

### Role Summary
Scrum Masters and Delivery Coaches facilitate agile ceremonies, remove team blockers, and coach the team on process improvement. This role complements the Project Manager by focusing on team effectiveness and iterative delivery.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Remove impediments blocking team progress
- Coach team on agile practices and continuous improvement
- Maintain sprint board and metrics (burndown, velocity)
- Foster psychological safety and team collaboration

### Goals
- Enable team to deliver at sustainable pace
- Improve delivery velocity and predictability over time
- Build a high-performing, self-organizing team

### Interaction with Existing Roles
- **Project Manager**: Coordinate on timeline and release planning; escalate external blockers
- **Developers, QA/Testing Lead, Designers**: Remove internal blockers and facilitate ceremonies
- **Product Manager**: Ensure backlog is well-refined for efficient sprint planning

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Team coaching and process improvement discussions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Existing Roles" sections to understand cross-functional dependencies and communication patterns.
