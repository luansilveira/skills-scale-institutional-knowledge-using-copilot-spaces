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
QA/Testing Leads own the quality assurance strategy and ensure that features and releases meet acceptance criteria before production deployment.

### Responsibilities
- Define and maintain test plans aligned to acceptance criteria
- Validate completed work against the Definition of Done
- Coordinate smoke tests, regression testing, and release verification
- Track quality metrics, defects, and test coverage trends
- Partner with Developers and Product Managers to triage issues and define risk thresholds

### Goals
- Catch defects before release and reduce production risk
- Support predictable, high-confidence delivery
- Maintain strong automation and coverage across critical workflows

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Daily standup blockers and defect triage
- Pre-release quality gates and smoke testing sign-off
- Release readiness updates with PMs and stakeholders

### Interacts with existing roles
- Works closely with Developers to validate implementation quality and resolve defects
- Aligns with Product Managers on acceptance criteria, feature readiness, and release criteria
- Supports Project Managers by surfacing risks, blockers, and readiness status
- Coordinates with DevOps/Release Engineers to confirm deployment and rollback readiness

---

## Product Lead

### Role Summary
Product Leads provide strategic product direction and decision-making authority on scope, trade-offs, and business alignment. They help connect customer needs and platform priorities to the delivery team's work.

### Responsibilities
- Approve roadmap direction, milestones, and prioritization decisions
- Define and refine product goals, success metrics, and goals for each initiative
- Resolve priority conflicts and trade-offs across workstreams
- Review project charters and ensure alignment with business outcomes
- Escalate cross-functional decisions when stakeholder alignment is needed

### Goals
- Maximize customer value and business impact
- Reduce ambiguity in prioritization and scope decisions
- Keep delivery aligned with strategic objectives

### Typical Communication
- Weekly alignment with Product Managers and Project Managers
- Milestone reviews and steering committee updates
- Escalations for scope, priority, and dependency decisions
- Stakeholder briefings and roadmap reviews

### Interacts with existing roles
- Works with Product Managers to shape priorities and success metrics
- Provides executive-level direction to Project Managers during planning and execution
- Partners with Engineering Leads on feasibility, sequencing, and resourcing trade-offs
- Informs Sponsors and stakeholders on progress, business value, and risk impacts

---

## Engineering Lead

### Role Summary
Engineering Leads guide technical strategy, maintain engineering quality, and help the team navigate architecture, delivery, and technical risk.

### Responsibilities
- Review technical designs, architecture decisions, and implementation trade-offs
- Identify dependencies, performance risks, and integration challenges early
- Set engineering standards, review practices, and technical quality expectations
- Mentor Developers and support healthy technical decision-making
- Partner with Project Managers on delivery sequencing and resourcing concerns

### Goals
- Deliver maintainable, scalable, and reliable solutions
- Reduce technical risk and delivery friction
- Build consistent engineering practices across projects

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning for risk assessment and dependency management
- Code review standards and engineering quality checkpoints
- Post-release retrospectives and technical improvement reviews

### Interacts with existing roles
- Guides Developers on implementation strategy and technical risk mitigation
- Advises Product Leads and Product Managers on feasibility and sequencing trade-offs
- Supports Project Managers in identifying blockers, dependencies, and delivery constraints
- Coordinates with Security/Compliance Officers to ensure technical safeguards are incorporated

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers manage deployment pipelines, release coordination, and operational readiness so work can move safely from development to production.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Coordinate release windows, cutover activities, and rollback readiness
- Monitor production health and post-deployment verification
- Maintain runbooks, observability, and deployment documentation
- Partner with QA/Testing Leads and Project Managers to confirm release confidence

### Goals
- Deliver safe, repeatable, and observable releases
- Minimize deployment failures and recovery time
- Improve engineering reliability and operational visibility

### Typical Communication
- Release planning and deployment readiness reviews
- Pre-release checklists and smoke test coordination
- Post-deploy verification and incident communication
- Operational updates with PMs, engineering, and stakeholders

### Interacts with existing roles
- Works with Developers to ensure deployments are automated and safe
- Collaborates with QA/Testing Leads on smoke tests and release gates
- Supports Project Managers in timing releases and communicating operational risk
- Coordinates with Security/Compliance Officers when deployment checks and controls are required

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet required security controls, policy expectations, and risk requirements before release and during operations.

### Responsibilities
- Review project requirements for security, privacy, and compliance impacts
- Validate security scanning, controls, and remediation activities in CI/CD
- Assess risks related to data handling, access, and critical dependencies
- Support incident response and post-incident review processes
- Provide guidance on secure design, remediation priorities, and governance expectations

### Goals
- Reduce risk of security and compliance issues in delivery
- Ensure work is aligned with organizational policies and standards
- Support secure, trusted release decisions

### Typical Communication
- Project initiation and risk assessment reviews
- Security findings and remediation discussions
- Pre-release reviews and compliance checkpoints
- Incident response and post-incident learning sessions

### Interacts with existing roles
- Reviews work with Developers and Engineering Leads to ensure secure implementation
- Partners with Product Leads and Product Managers to align risk and business decisions
- Supports Project Managers in tracking security risks and dependencies
- Works with Sponsors on escalations involving governance or high-impact risk

---

## Sponsor

### Role Summary
Sponsors are executive or strategic stakeholders responsible for setting direction, funding, and escalation support for key initiatives.

### Responsibilities
- Approve project initiation, priority, and milestone gates
- Resolve escalations that exceed team-level authority
- Allocate resources and budget support for strategic initiatives
- Confirm alignment between project work and business strategy
- Provide visibility and support for major milestones and high-impact changes

### Goals
- Ensure projects deliver measurable strategic value
- Remove barriers to execution and resolve cross-team issues
- Maintain confidence in the program's outcomes and direction

### Typical Communication
- Project kickoff and milestone approvals
- Escalation meetings for delivery or business decisions
- Executive updates on progress, risks, and benefits
- Sponsor reviews tied to timing, investment, and strategic fit

### Interacts with existing roles
- Holds Product Leads and Project Managers accountable for strategic alignment and milestone outcomes
- Receives updates from Product Leads and Project Managers to support decision-making
- Works with Security/Compliance Officers when risk or governance escalations arise
- Provides sponsorship for issues that require cross-functional prioritization or resource commitment

---

## Stakeholders

### Role Summary
Stakeholders are people or groups affected by the project outcome or invested in its success. They provide input, feedback, and decisions that guide project goals and adoption.

### Responsibilities
- Share business needs, requirements, and expected outcomes
- Review milestones, plans, and key decisions that affect their domain
- Provide perspective on customer needs, operational impact, and adoption readiness
- Support alignment when trade-offs or strategic changes are needed

### Goals
- Ensure the delivered work matches real-world needs and business expectations
- Keep project outcomes relevant, usable, and valuable
- Improve confidence in delivery decisions through clear feedback

### Typical Communication
- Weekly or milestone-based updates
- Requirements reviews and stakeholder feedback sessions
- Decisions on scope, launch readiness, and operational support
- Cross-functional reviews during planning and release readiness

### Interacts with existing roles
- Provide direction and feedback to Product Managers and Product Leads
- Contribute to project planning and acceptance criteria with Project Managers and QA/Testing Leads
- Inform release readiness and rollout planning with DevOps/Release Engineers and sponsors
- Are represented in project communication and status updates by the PM and PMO-like coordination functions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The project team can reference these roles when clarifying ownership, dependencies, and communication during planning, execution, and release activities.
