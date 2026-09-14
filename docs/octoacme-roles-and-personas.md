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

### Interactions with Other Roles
- **Technical Lead/Architect**: Receive architectural guidance and design feedback; collaborate on technical spike investigations
- **Product Managers**: Implement features to meet acceptance criteria; clarify requirements and scope
- **Project Managers**: Report progress and blockers; estimate work and participate in planning
- **QA Lead**: Collaborate on test scenarios and edge cases; ensure code meets quality standards
- **UX/Design Lead**: Implement design specifications; clarify usability requirements
- **Operations/DevOps Lead**: Ensure code meets operational requirements; support deployment processes

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

### Interactions with Other Roles
- **Developers**: Define acceptance criteria and priorities; validate solutions through user research
- **Project Managers**: Align on roadmap, milestones, and success metrics; conduct weekly syncs
- **Technical Lead/Architect**: Collaborate on technical feasibility and architectural implications
- **Stakeholders/Sponsors**: Present roadmap priorities and success metrics; manage stakeholder expectations
- **UX/Design Lead**: Partner on feature design and user research; validate usability
- **QA Lead**: Define acceptance criteria validation approach; review quality metrics

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

### Interactions with Other Roles
- **Product Managers**: Weekly alignment on roadmap, priorities, and success metrics
- **Developers**: Track progress; identify and resolve blockers; coordinate capacity planning
- **Technical Lead/Architect**: Identify technical risks; schedule design reviews and architecture discussions
- **Stakeholders/Sponsors**: Provide regular status updates; escalate business-level risks
- **QA Lead**: Track quality metrics; ensure QA is integrated in release planning
- **Operations/DevOps Lead**: Coordinate deployment planning and schedules; manage deployment windows
- **UX/Design Lead**: Integrate design timeline into project plan; coordinate design reviews

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical strategy, architectural guidance, and quality oversight. They ensure technical solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Define architectural approach and technical standards
- Conduct design reviews and provide technical guidance to developers
- Identify technical risks and propose mitigation strategies
- Lead technical spike investigations for complex problems
- Mentor junior developers and support knowledge transfer
- Collaborate with Product Manager on technical feasibility of features

### Goals
- Ensure technical excellence and long-term system maintainability
- Reduce technical debt and architectural complexity
- Enable team to ship high-quality features efficiently

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and mentoring
- Risk escalations and technical trade-off decisions

### Interactions with Other Roles
- **Developers**: Provide architectural guidance; conduct design reviews; mentor on technical decisions
- **Product Managers**: Advise on technical feasibility of features; identify technical trade-offs
- **Project Managers**: Escalate technical risks; provide estimates for complex technical work
- **QA Lead**: Define testability requirements; collaborate on test strategy for complex features
- **Operations/DevOps Lead**: Align on operational and scalability requirements; review infrastructure implications
- **Stakeholders/Sponsors**: Escalate critical technical risks with business impact

---

## Quality Assurance Lead

### Role Summary
QA Leads own the quality strategy, test planning, and acceptance criteria validation. They ensure delivered features meet quality standards and acceptance criteria before production release.

### Responsibilities
- Develop test strategy and test plan for each initiative
- Define acceptance criteria validation approach
- Execute manual testing and coordinate automated test coverage
- Identify and triage quality issues
- Partner with developers on edge cases and test scenarios
- Report quality metrics and recommend go/no-go for release

### Goals
- Maintain high quality and user confidence in product
- Reduce production defects and post-release issues
- Provide clear quality signals for release decisions

### Typical Communication
- Test plans and quality reports
- Defect triage and acceptance criteria review
- Release quality assessments

### Interactions with Other Roles
- **Developers**: Collaborate on test scenarios; review edge cases; provide feedback on code quality
- **Product Managers**: Validate acceptance criteria; review definition of done; ensure feature meets requirements
- **Project Managers**: Report quality metrics; provide go/no-go recommendation for release; manage test schedule
- **Technical Lead/Architect**: Collaborate on testability design; align on test strategy for complex features
- **Operations/DevOps Lead**: Coordinate smoke testing; validate production readiness
- **UX/Design Lead**: Validate usability and user experience; coordinate acceptance testing

---

## Stakeholder/Sponsor

### Role Summary
Sponsors are executive or business owners who champion the project and allocate resources. They provide business context, approve milestones, and represent the business perspective in project decisions.

### Responsibilities
- Approve project charter and resource allocation
- Provide business context and success metrics definition
- Escalation point for business-level risks and trade-offs
- Receive and approve milestone and release communications
- Support cross-organizational coordination

### Goals
- Ensure project delivers business value
- Align project with organizational strategy
- Provide executive sponsorship for cross-team collaboration

### Typical Communication
- Monthly stakeholder updates and status reports
- Approval of project charter and major decisions
- Escalation of business-level risks

### Interactions with Other Roles
- **Project Managers**: Receive regular status updates; approve milestones; escalate business-level blockers
- **Product Managers**: Align on roadmap priorities and success metrics; provide business context
- **Technical Lead/Architect**: Escalation point for critical technical risks with business impact
- **All team members**: Define project success criteria; allocate resources; support cross-team coordination

---

## Operations/DevOps Lead

### Role Summary
Ops/DevOps Leads manage deployment infrastructure, CI/CD pipelines, and production operations. They enable reliable, automated delivery and maintain production health.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage deployment infrastructure and environments
- Coordinate deployments and manage rollback processes
- Monitor production systems and alert on issues
- Respond to production incidents and support post-mortems
- Partner with developers on operational requirements and testing

### Goals
- Enable fast, reliable deployments to production
- Maintain high system availability and observability
- Support incident response and rapid problem resolution

### Typical Communication
- Deployment coordination and release timing
- Infrastructure and operational requirements discussions
- Production monitoring and incident reports

### Interactions with Other Roles
- **Developers**: Define operational requirements; support deployment processes; test deployment readiness
- **Project Managers**: Coordinate deployment windows; manage release schedules
- **Technical Lead/Architect**: Align on infrastructure and scalability requirements; review architectural implications
- **QA Lead**: Coordinate smoke testing; validate production readiness before go-live
- **All team members**: Support incident response; provide production visibility and alerts

---

## UX/Design Lead

### Role Summary
Design Leads define user experience requirements, conduct user research, and validate usability. They ensure delivered features are intuitive and meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user experience requirements and acceptance criteria
- Validate usability through testing and feedback
- Collaborate with developers on design implementation
- Ensure consistency across user interface and experience

### Goals
- Deliver intuitive, usable features that delight users
- Reduce support burden through good design
- Build products that meet user needs and expectations

### Typical Communication
- Design specifications and user research findings
- Usability testing results and recommendations
- Design reviews and implementation feedback

### Interactions with Other Roles
- **Product Managers**: Partner on feature design; conduct user research; validate solutions meet user needs
- **Developers**: Provide design specifications; clarify usability requirements; review implementation
- **Project Managers**: Integrate design timeline into project plan; communicate design milestones
- **Technical Lead/Architect**: Collaborate on design feasibility; ensure design aligns with technical architecture
- **QA Lead**: Coordinate usability acceptance testing; validate implementation matches design specs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand cross-functional dependencies and communication paths.
