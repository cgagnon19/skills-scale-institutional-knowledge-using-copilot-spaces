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

## QA / Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They work closely with Developers and Product Managers to ensure features meet acceptance criteria and maintain quality standards.

### Responsibilities
- Create and maintain test plans aligned with feature acceptance criteria
- Define QA approach, testing phases, and quality gates for releases
- Coordinate testing activities across the team and external testers
- Validate acceptance criteria before features move to Done
- Identify and report quality issues with clear reproduction steps
- Establish and maintain testing standards and best practices

### Goals
- Ensure product quality and reduce post-release defects
- Establish consistent, repeatable testing processes
- Provide confidence in release readiness through comprehensive test coverage

### Typical Communication
- Test planning meetings during sprint planning
- Sprint reviews to validate acceptance criteria
- Release gate decisions and pre-deployment smoke test sign-offs
- Quality metrics and defect trend reports in weekly syncs

### Interactions with Other Roles
- **With Developers**: Review acceptance criteria, collaborate on test-driven development, provide feedback on testability
- **With Product Managers**: Clarify acceptance criteria, discuss quality trade-offs, validate feature completion
- **With Project Managers**: Report on test coverage and readiness, escalate quality blockers
- **With Technical Leads**: Coordinate testing strategy for complex features, identify technical risks that impact quality

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical vision, design guidance, and architecture oversight. They mentor the development team, identify technical risks, and ensure solutions are scalable and maintainable.

### Responsibilities
- Provide technical direction and architectural guidance on complex features
- Review technical designs and propose optimizations
- Identify and mitigate technical risks during planning and execution
- Mentor Developers on technical standards and best practices
- Make or facilitate key technology decisions and trade-offs
- Ensure scalability, performance, and maintainability of solutions

### Goals
- Maintain technical excellence and reduce technical debt
- Accelerate delivery by removing technical blockers
- Build and mentor a strong engineering culture

### Typical Communication
- Design reviews and architecture discussions during planning
- Technical mentoring and code review sessions
- Risk assessment and mitigation planning in weekly syncs
- Escalation of technical debt and long-term sustainability concerns

### Interactions with Other Roles
- **With Developers**: Guide implementation, review complex code, mentor on technical decisions
- **With Project Managers**: Identify technical risks and dependencies, provide estimates for technical work
- **With QA/Testing Leads**: Discuss testability and quality implications of design choices
- **With Product Managers**: Advise on technical feasibility, performance implications of features

---

## Scrum Master / Delivery Facilitator

### Role Summary
Scrum Masters remove blockers, facilitate team processes and ceremonies, and protect the team's focus. They enable the team to deliver consistently by maintaining process health and addressing impediments.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and track impediments blocking team progress
- Protect the team from scope creep and external distractions
- Maintain visibility into sprint progress via project boards and dashboards
- Coach the team on process improvements and best practices
- Escalate blockers to Project Manager or Project Lead when team-level resolution isn't possible

### Goals
- Maximize team velocity and consistency
- Reduce process friction and waste
- Maintain team health and psychological safety

### Typical Communication
- Daily standups (brief, focused on blockers and dependencies)
- Sprint planning and capacity planning sessions
- Process improvement retrospectives
- Weekly blocker reports to Project Manager

### Interactions with Other Roles
- **With Project Managers**: Escalate impediments, report on team metrics and health
- **With Developers**: Facilitate daily coordination, remove process bottlenecks
- **With All Roles**: Ensure ceremonies run smoothly and on schedule

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical delivery. They gather and clarify requirements, create user stories, and ensure alignment between stakeholder needs and team understanding.

### Responsibilities
- Gather and document business requirements from stakeholders
- Create clear, testable user stories with acceptance criteria
- Refine and clarify requirements during backlog refinement
- Serve as liaison between business stakeholders and delivery team
- Validate that delivered features meet original business intent
- Identify scope creep and propose trade-offs

### Goals
- Ensure requirement clarity and traceability from business need to delivery
- Reduce scope creep and rework due to unclear requirements
- Improve stakeholder satisfaction and feature adoption

### Typical Communication
- Requirement gathering sessions with stakeholders
- Backlog refinement and user story creation with team
- Clarification sessions with Developers and QA on acceptance criteria
- Stakeholder check-ins and feedback loops

### Interactions with Other Roles
- **With Product Managers**: Collaborate on user stories and acceptance criteria, align with product vision
- **With Developers**: Clarify requirements, discuss technical feasibility, address implementation questions
- **With QA/Testing Leads**: Ensure acceptance criteria are testable and complete
- **With Project Managers**: Provide visibility into requirements clarity and scope changes

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, strategic oversight, and governance for projects. They approve major decisions, remove organizational blockers, and ensure projects align with business objectives.

### Responsibilities
- Define and communicate project strategic value and business objectives
- Approve scope changes and major decisions with business impact
- Remove organizational blockers and manage dependencies outside the team
- Provide governance and ensure compliance with organizational standards
- Escalate business risks and make prioritization decisions across projects
- Celebrate milestones and ensure project visibility across the organization

### Goals
- Ensure project aligns with strategic business objectives
- Minimize organizational dependencies and governance delays
- Maximize business value and ROI from project delivery

### Typical Communication
- Milestone reviews and demo sessions
- Monthly executive status reports
- Exception-based escalations for critical blockers or scope changes
- Decision gates (go/no-go) at key project phases

### Interactions with Other Roles
- **With Project Managers**: Review status, approve scope changes, escalate organizational blockers
- **With Product Managers**: Align on business strategy and success metrics
- **With All Roles**: Provide context on business priorities and organizational dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when designing workflows, communication plans, and documentation to ensure all critical roles are represented and understood.
