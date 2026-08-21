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
QA/Testing Leads validate software quality, manage test strategies, and ensure all features meet acceptance criteria before release. They partner with developers and product managers to define quality standards and catch defects early.

### Responsibilities
- Develop and execute comprehensive test plans
- Design and maintain test automation frameworks
- Triage and prioritize defects for developer resolution
- Validate acceptance criteria completion before merge
- Identify quality risks and recommend testing approaches
- Coordinate manual QA efforts when automated testing is insufficient

### Goals
- Ensure high-quality releases with minimal post-deployment issues
- Reduce defect escape rates through comprehensive testing
- Enable team confidence in deployment readiness

### Typical Communication
- Test plan reviews with developers and product managers
- Defect reports and triage during daily standups
- QA sign-off on pull requests and release candidates
- Weekly quality metrics reports

### How they interact with existing roles
- **With Developers**: Collaborate on test strategy, report issues with clear repro steps, coordinate hotfixes for critical defects
- **With Product Managers**: Clarify acceptance criteria, validate feature completeness, communicate quality trade-offs
- **With Project Managers**: Flag quality risks that impact timeline, provide test coverage metrics for release readiness

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide the technical direction of projects, make architectural decisions, and mentor developers. They balance innovation with pragmatism to ensure scalable, maintainable solutions.

### Responsibilities
- Drive technical design and architecture decisions
- Review pull requests for architectural alignment and best practices
- Lead technical spike investigations on complex problems
- Identify and mitigate technical risks
- Mentor developers and foster code quality standards
- Collaborate on technology choices and dependency management

### Goals
- Build scalable, maintainable, and performant systems
- Reduce technical debt while enabling delivery velocity
- Develop team technical capabilities through mentoring

### Typical Communication
- Technical design documents and architecture reviews
- Code review feedback on complex PRs
- Technical guidance in planning and retrospective meetings
- One-on-one mentoring with developers

### How they interact with existing roles
- **With Developers**: Provide architectural guidance, unblock technical decisions, review complex implementations
- **With Project Managers**: Escalate technical risks and dependencies, estimate technical complexity for planning
- **With Product Managers**: Advise on feasibility and trade-offs of feature proposals, suggest technical approaches

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, secure resources, and remove organizational barriers. They ensure projects deliver business value and align with strategic priorities.

### Responsibilities
- Define business objectives and success criteria
- Approve budget, resources, and project milestones
- Remove organizational and cross-team blockers
- Make high-level business decisions and trade-offs
- Monitor project health and escalate business-critical risks
- Communicate project value to broader organization

### Goals
- Ensure projects deliver measurable business impact
- Align team efforts with organizational strategy
- Maximize ROI on project investments

### Typical Communication
- Monthly stakeholder updates and reviews
- Milestone approval meetings
- Escalations for business-impacting decisions
- Executive summary reports

### How they interact with existing roles
- **With Project Managers**: Receive status updates, approve major decisions, address high-level blockers
- **With Product Managers**: Align on business strategy, validate success metrics, make trade-off decisions
- **With Developers**: Occasional technical deep-dives, celebration of key milestones

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security standards, regulatory requirements, and organizational policies. They embed security practices throughout the project lifecycle.

### Responsibilities
- Define security and compliance requirements upfront
- Conduct security reviews of designs and code
- Manage vulnerability assessments and remediation
- Ensure regulatory compliance (GDPR, HIPAA, SOC2, etc.)
- Coordinate with incident response when needed
- Provide security training and best practices guidance

### Goals
- Prevent security breaches and compliance violations
- Build security into the development process
- Maintain customer trust and regulatory standing

### Typical Communication
- Security requirements at project kickoff
- Code security reviews before release
- Vulnerability reports and remediation tracking
- Compliance sign-off on releases

### How they interact with existing roles
- **With Developers**: Review code for security vulnerabilities, provide secure coding guidance
- **With Project Managers**: Flag security-related blockers, ensure compliance checkpoints in timeline
- **With QA/Testing Leads**: Coordinate security and penetration testing as part of QA process

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach teams on agile practices. They focus on process health and continuous improvement rather than technical delivery.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help resolve team blockers and dependencies
- Coach team members on agile principles and practices
- Protect the team from scope creep and external distractions
- Maintain sprint boards and tracking artifacts
- Foster psychological safety and continuous improvement culture

### Goals
- Maximize team velocity and predictability
- Ensure consistent, sustainable pace
- Build a high-performing, collaborative team

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching with team members
- Impediment escalation to project managers
- Retrospective facilitation and action item tracking

### How they interact with existing roles
- **With Project Managers**: Escalate timeline and resource blockers, provide velocity and capacity data
- **With Developers**: Remove impediments, coach on estimation and task breakdown
- **With Product Managers**: Facilitate backlog refinement, manage scope changes during sprints
- **With All Roles**: Foster team collaboration and psychological safety

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
