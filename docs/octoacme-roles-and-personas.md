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

## Project Sponsor / Executive Sponsor

### Role Summary
Project Sponsors provide strategic direction, authorize major commitments, and remove organizational blockers. They represent the accountable business sponsor for the initiative.

### Responsibilities
- Confirm the project mandate, funding, capacity, and priority
- Approve major scope, timeline, and risk trade-offs
- Resolve escalated dependencies and support decision gates
- Confirm whether sponsor-level risks are accepted or require mitigation

### How this role interacts
- Partners with Product Managers on outcomes and priority
- Partners with Project Managers on milestones, resources, risks, and escalation
- Consults Developers and Technical Leads on feasibility and delivery risk
- Reviews QA/Testing readiness and stakeholder feedback at decision gates

### Accountability boundary
The Sponsor owns organizational authorization and escalated trade-offs, not the product backlog or day-to-day delivery decisions.

---

## Business Analyst / Requirements Lead

### Role Summary
Business Analysts translate business needs and workflows into clear, testable requirements. They connect stakeholder context to an actionable backlog.

### Responsibilities
- Elicit and document business needs, workflows, and constraints
- Refine backlog items, acceptance criteria, and traceability
- Identify gaps, assumptions, dependencies, and process impacts
- Validate that delivered behavior addresses the agreed requirement

### How this role interacts
- Works with Product Managers on problem statements, scope, and priorities
- Works with Project Managers on requirements dependencies, decisions, and readiness
- Clarifies requirements with Developers and supports QA/Testing with acceptance criteria
- Facilitates stakeholder review without changing priorities or accepting scope alone

### Accountability boundary
The Requirements Lead owns requirement clarity and traceability; the Product Manager owns product priority and the Stakeholder or Product Manager approves material requirement changes.

---

## UX/UI Designer / User Researcher

### Role Summary
UX/UI Designers and User Researchers represent user needs and validate that proposed solutions are understandable, accessible, and usable.

### Responsibilities
- Research user needs, workflows, and usability risks
- Create and maintain user flows, designs, and interaction guidance
- Validate designs with users and incorporate actionable findings
- Define usability and accessibility considerations for delivery and testing

### How this role interacts
- Partners with Product Managers on user outcomes and research priorities
- Coordinates with Project Managers on design milestones and review activities
- Collaborates with Developers on feasible implementation and with QA/Testing on usable, testable behavior
- Uses stakeholder feedback as input while keeping user evidence visible

### Accountability boundary
The role owns design rationale and user research evidence; the Product Manager owns product decisions when user, business, and delivery constraints conflict.

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects set technical direction and help the team make consistent, sustainable implementation decisions.

### Responsibilities
- Define architecture, interfaces, and non-functional requirements
- Review technical options, estimates, and implementation risks
- Maintain technical decisions and mitigation plans
- Ensure solutions meet reliability, security, performance, and maintainability goals

### How this role interacts
- Advises Product Managers and Project Managers on feasibility, sequencing, and technical trade-offs
- Guides Developers through design and code reviews
- Coordinates with QA/Testing on quality attributes and test strategy
- Engages stakeholders when technical constraints change scope, timing, or risk

### Accountability boundary
The Technical Lead owns technical direction and technical risk recommendations; the Product Manager and Sponsor decide business trade-offs when those recommendations affect scope or priority.

---

## DevOps/SRE / Release Manager

### Role Summary
DevOps/SRE and Release Managers make delivery repeatable and keep environments, deployment, observability, and rollback readiness coordinated.

### Responsibilities
- Maintain deployment pipelines, environments, and operational readiness
- Coordinate release windows, release notes, and rollback plans
- Confirm monitoring, alerting, and post-deployment verification
- Coordinate incident response and capture operational follow-up work

### How this role interacts
- Works with Developers on automation, reliability, and observability
- Works with Project Managers on release milestones, dependencies, and status
- Works with Product Managers on release scope and stakeholder communications
- Coordinates with QA/Testing on staging smoke tests and with stakeholders on release or incident updates

### Accountability boundary
The Release Manager owns release coordination and readiness evidence; the Product Manager or Sponsor approves business timing and risk acceptance, while Developers and SREs own implementation and operational actions.

---

## Security / Privacy Representative

### Role Summary
Security and Privacy Representatives identify threats, data-handling obligations, and compliance needs early enough to influence the design.

### Responsibilities
- Review data flows, access controls, threat models, and privacy impacts
- Define security and privacy requirements and review evidence
- Coordinate security testing and track remediation or exceptions
- Escalate risks that require formal risk acceptance

### How this role interacts
- Advises Product Managers on trust, privacy, and compliance impacts
- Works with Technical Leads and Developers on controls and mitigations
- Works with QA/Testing on security test coverage and release evidence
- Works with Project Managers on risk registers and with Sponsors or stakeholders on accepted exceptions

### Accountability boundary
The role owns security and privacy advice and approval criteria; it does not silently accept residual risk. A designated Sponsor or accountable business owner must approve documented exceptions.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads define how project outcomes are measured and how trustworthy product data will be collected and interpreted.

### Responsibilities
- Define success metrics, instrumentation, and reporting requirements
- Establish data quality, privacy, and ownership expectations
- Validate dashboards or analysis used for release and outcome decisions
- Report post-release results and recommend follow-up improvements

### How this role interacts
- Partners with Product Managers on measurable outcomes and with Project Managers on milestone reporting
- Works with Developers on instrumentation and data contracts
- Works with QA/Testing on analytics validation and edge cases
- Shares findings with stakeholders without replacing the Product Manager's prioritization authority

### Accountability boundary
The Analytics Lead owns measurement definitions and data quality evidence; the Product Manager owns outcome interpretation and prioritization decisions.

---

## Customer Support / Operations Representative

### Role Summary
Customer Support and Operations Representatives bring frontline and operational knowledge into delivery and prepare the organization to support the change.

### Responsibilities
- Identify support, training, workflow, and operational readiness needs
- Review customer-facing behavior, communications, and known issues
- Prepare support guidance and escalation paths before release
- Feed incidents, recurring requests, and post-release learnings into the backlog

### How this role interacts
- Works with Product Managers on customer impact and follow-up priorities
- Works with Project Managers on readiness tasks, communications, and dependencies
- Coordinates with Developers and QA/Testing on reproducible issues and acceptance scenarios
- Partners with Release Managers on rollout communications and with stakeholders on operational impact

### Accountability boundary
The role owns support and operational readiness input; the Product Manager owns product priority, and the Project Manager coordinates completion of readiness actions.

---

## Combining roles on smaller projects

Not every project needs a separate person for each role. One person may cover multiple roles, or a role may be consulted only at a relevant decision point. The project plan must still name the accountable person for each decision and deliverable, record any conflicts between combined roles, and identify who provides independent review for quality, security, or risk acceptance when needed.

---

## Lifecycle participation overview

| Lifecycle activity | Primary accountability | Typical contributors and interactions |
| --- | --- | --- |
| Initiation | Sponsor, Product Manager, and Project Manager | Business Analyst defines the need; Analytics Lead proposes success measures; Technical Lead, Security/Privacy, UX, and stakeholders identify feasibility, user, and risk considerations. |
| Planning | Product Manager and Project Manager | Requirements Lead refines the backlog; UX defines design work; Technical Lead defines technical approach; Developers estimate; QA/Testing defines coverage; Security/Privacy, Data, and Operations add readiness tasks. |
| Execution and tracking | Project Manager for coordination; Developers for implementation | Product Manager manages priority; Technical Lead guides decisions; Requirements, UX, QA/Testing, Security/Privacy, and Analytics validate their areas; stakeholders review agreed checkpoints. |
| Risk management and communication | Project Manager for the register and escalation path | Sponsor decides escalated trade-offs; Technical Lead, Security/Privacy, Operations, and stakeholders provide risk evidence and mitigations; Product Manager communicates product impact. |
| Release and deployment | Release Manager for release readiness and coordination | Developers and DevOps/SRE deploy and observe; QA/Testing verifies; Security/Privacy confirms required evidence; Product Manager approves product messaging; Support/Operations prepares customers and stakeholders. |
| Retrospective and continuous improvement | Project Manager facilitates; the accountable owner is assigned per action | Product, engineering, QA/Testing, UX, Security/Privacy, Analytics, Support/Operations, and stakeholders contribute evidence and leave with named, actionable improvements. |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
