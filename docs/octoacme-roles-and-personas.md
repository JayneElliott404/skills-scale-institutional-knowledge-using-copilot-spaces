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
The QA/Testing Lead owns quality assurance strategy, test planning, and acceptance validation. They ensure features meet acceptance criteria and quality standards before release, working closely with Developers to define testable requirements and with Product Managers to confirm acceptance criteria are complete.

### Responsibilities
- Create and maintain test plans for each sprint and release
- Coordinate manual and automated testing efforts
- Validate acceptance criteria alongside Product Managers and Developers
- Identify regressions and ensure defects are tracked and resolved
- Coordinate smoke tests and sign-off before production releases

### Goals
- Ensure high-quality, stable releases with minimal post-release defects
- Maintain strong test coverage and automation standards
- Provide quality metrics that inform release decisions

### Typical Communication
- Sprint planning and definition-of-done workshops with Developers and Project Managers
- Pre-release coordination with Project Managers and Product Managers
- Quality metrics reviews with the broader team
- Defect triage sessions with Developers

---

## Technical Lead/Architect

### Role Summary
The Technical Lead/Architect defines technical strategy, architecture decisions, and design patterns for the project. They ensure technical feasibility and scalability of planned work and serve as a mentor and escalation point for Developers on complex engineering challenges.

### Responsibilities
- Review and approve technical designs and architecture proposals
- Assess technical feasibility and risks of planned features
- Mentor Developers and guide implementation approaches
- Coordinate with dependent teams on technical integration points
- Produce and maintain architecture decision records (ADRs)

### Goals
- Maintain technical quality, consistency, and long-term maintainability
- Reduce technical debt and prevent architectural drift
- Enable scalable, reliable architecture that supports business goals

### Typical Communication
- Design reviews with Developers and Product Managers
- Technical spike planning with Project Managers and Developers
- Dependency coordination with external or partner teams
- Architecture decision records shared with the full project team

---

## Product Lead

### Role Summary
The Product Lead provides strategic product guidance and holds final decision authority for prioritization and trade-offs across multiple product initiatives or Product Managers (PdMs). They represent the customer voice at the executive level and ensure the product roadmap aligns with broader business strategy.

### Responsibilities
- Make final prioritization decisions when trade-offs arise between initiatives
- Represent customer needs and product strategy at the executive level
- Coordinate cross-initiative dependencies with Project Managers and Product Managers
- Review metrics and business impact to guide roadmap decisions

### Goals
- Align the product roadmap with overall business strategy
- Maximize customer value at the portfolio level
- Ensure Product Managers have clear direction and authority within their scope

### Typical Communication
- Weekly syncs with Product Managers to review priorities and blockers
- Executive updates and stakeholder alignment meetings
- Roadmap reviews with Project Managers and engineering leadership
- Escalation discussions when cross-initiative conflicts arise

---

## Sponsor/Executive Stakeholder

### Role Summary
The Sponsor or Executive Stakeholder provides business authorization, resource allocation, and escalation authority for the project. They represent organizational priorities and investment decisions, and are engaged at key milestones or when significant risks or blockers require executive action.

### Responsibilities
- Approve the project charter, scope, and resource commitments
- Escalate or resolve organizational risks and blockers that cannot be handled at the team level
- Make final trade-off decisions when scope, schedule, or budget require executive judgment
- Communicate project status and outcomes to leadership and the broader organization

### Goals
- Ensure the project delivers outcomes aligned with business objectives
- Remove organizational blockers that impede delivery
- Minimize delivery risk through proactive governance

### Typical Communication
- Monthly stakeholder updates from Project Managers and Product Lead
- Milestone gate reviews to assess readiness to proceed
- Escalation meetings when critical risks or issues arise
- Executive briefings on business impact and return on investment

---

## Security/Compliance Officer

### Role Summary
The Security/Compliance Officer ensures that security and compliance requirements are identified, addressed, and validated throughout the project lifecycle. They work with Developers, Technical Leads, and Product Managers to embed security into design and delivery rather than treating it as an afterthought.

### Responsibilities
- Review backlog items to identify and document security and compliance requirements
- Conduct security assessments and threat modeling during design phases
- Validate that security controls and testing meet organizational standards
- Coordinate incident response when security issues are discovered
- Ensure audit and compliance evidence is captured for regulated features

### Goals
- Minimize security and compliance risk across the project
- Maintain the organization's security posture and meet regulatory obligations
- Enable teams to build securely without slowing delivery unnecessarily

### Typical Communication
- Security requirements definition sessions with Product Managers and Technical Leads
- Design reviews with Technical Lead/Architect and Developers
- Pre-release security validation with QA/Testing Lead and Project Managers
- Incident response coordination across all relevant team members

---

## How these personas are used in OctoAcme processes
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The three core personas (Developer, Product Manager, Project Manager) drive day-to-day sprint and delivery activities.
- The QA/Testing Lead and Technical Lead/Architect are closely integrated into sprint ceremonies and design reviews.
- The Product Lead and Sponsor/Executive Stakeholder operate at a higher cadence, engaging at roadmap reviews and milestone gates.
- The Security/Compliance Officer engages at key points in the delivery lifecycle—requirements, design, and pre-release—to ensure security and compliance are embedded in the process.

