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

### Interaction with Other Roles
- Work closely with **QA/Testing Specialists** to define testability requirements and resolve defects
- Collaborate with **Technical Architects** on design reviews and technical guidance
- Receive acceptance criteria and prioritization from **Product Managers**
- Coordinate with **Project Managers** on schedule and dependency management
- Support **Scrum Masters** in maintaining team velocity and removing blockers

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

### Interaction with Other Roles
- Align with **Stakeholders & Sponsors** on business goals and priorities
- Define acceptance criteria with **Developers** and **QA/Testing Specialists**
- Consult **Technical Architects** on technical feasibility and scalability implications
- Receive project updates and risk reports from **Project Managers**
- Participate in retrospectives facilitated by **Scrum Masters**

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

### Interaction with Other Roles
- Report project status and risks to **Stakeholders & Sponsors**
- Coordinate with **Developers**, **QA/Testing Specialists**, and **Technical Architects** on scheduling and dependencies
- Work with **Scrum Masters** on process adherence and team health metrics
- Ensure compliance and security requirements from **Security & Compliance Leads** are incorporated into the plan
- Collaborate with **Product Managers** on scope and prioritization trade-offs

---

## QA/Testing Specialists

### Role Summary
QA and Testing Specialists ensure product quality through systematic testing, validation of acceptance criteria, and identification of defects before release. They collaborate with developers and product teams to define testability requirements and execute test plans.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Execute manual and automated testing for features and regressions
- Identify, document, and triage defects with reproduction steps
- Validate that quality standards and Definition of Done (DoD) are met before release
- Advise on test automation strategy and CI integration
- Participate in acceptance testing and User Acceptance Testing (UAT) coordination

### Goals
- Deliver high-quality, reliable features to production
- Reduce production defects and customer impact
- Enable faster, more confident releases
- Maintain test coverage and reduce testing cycle time

### Typical Communication
- Test plans and acceptance criteria review with Developers and Product Managers
- Defect logs and quality metrics
- Daily standups and sprint reviews
- Release readiness reports

### Interaction with Other Roles
- Partner with **Developers** to define testability requirements and resolve defects
- Collaborate with **Product Managers** to validate acceptance criteria and user expectations
- Report quality metrics to **Project Managers** for risk assessment
- Coordinate with **Security & Compliance Leads** on security testing requirements
- Support **Scrum Masters** in maintaining sprint quality standards
- Work with **Technical Architects** on testing strategy for complex components

---

## Stakeholders & Sponsors

### Role Summary
Stakeholders and Sponsors represent business interests, provide approvals, and ensure alignment with organizational goals. They may be executives, department heads, or customer representatives who have decision authority and vested interest in project outcomes.

### Responsibilities
- Provide business context and success metrics
- Review and approve project charter and milestones
- Make prioritization and trade-off decisions
- Receive regular status updates and escalations
- Support resource allocation and risk mitigation
- Validate that delivered outcomes meet business objectives

### Goals
- Ensure project delivers business value
- Maintain alignment with organizational strategy
- Enable timely decision-making and escalation
- Minimize business risk and maximize return on investment

### Typical Communication
- Monthly stakeholder updates and reviews
- Escalation notifications for risks and blockers
- Approval of project charter and major milestones
- Business impact assessments

### Interaction with Other Roles
- Provide strategic direction to **Product Managers** and **Project Managers**
- Approve scope and timeline decisions presented by **Project Managers**
- Receive regular updates on delivery progress and risks
- Make business trade-off decisions involving **Developers**, **Technical Architects**, and **Product Managers**
- Escalate critical issues or decisions when needed

---

## Security & Compliance Leads

### Role Summary
Security and Compliance Leads ensure that projects meet security standards, compliance requirements, and risk management policies. They collaborate with development and release teams to integrate security best practices and conduct reviews.

### Responsibilities
- Review security requirements and design implications
- Define security and compliance acceptance criteria
- Conduct or coordinate security testing and reviews
- Participate in release approval and incident response
- Track security debt and compliance issues
- Advise on data protection, encryption, and access control requirements

### Goals
- Reduce security vulnerabilities and compliance risk
- Integrate security early in the development lifecycle (shift-left security)
- Enable secure, compliant releases to production
- Build security awareness across the team

### Typical Communication
- Security requirements in acceptance criteria
- Code review and design review participation
- Release approval gates and incident escalation
- Security metrics and risk reports

### Interaction with Other Roles
- Define security requirements with **Product Managers** and **Technical Architects**
- Collaborate with **Developers** on secure coding practices and remediation
- Work with **QA/Testing Specialists** to validate security testing coverage
- Participate in release reviews with **Project Managers**
- Advise **Stakeholders & Sponsors** on security and compliance risk
- Support incident response led by **Project Managers**

---

## Technical Architects

### Role Summary
Technical Architects provide strategic technical guidance, design reviews, and ensure solutions align with system architecture, scalability, and maintainability goals. They mentor developers and identify technical risks.

### Responsibilities
- Review and guide technical design and architecture decisions
- Identify scalability, performance, and maintainability concerns
- Mentor and support developers on technical best practices
- Advise on technology choices and technical debt trade-offs
- Participate in design reviews and code reviews for critical components
- Identify and mitigate technical risks

### Goals
- Ensure technical solutions are scalable, maintainable, and aligned with strategic architecture
- Reduce rework and technical debt
- Build team capability in architecture and design patterns
- Enable sustainable, high-quality delivery

### Typical Communication
- Design review participation and guidance
- Code review comments on architecture-critical changes
- Technical planning and estimation support
- Architecture documentation and decision records

### Interaction with Other Roles
- Guide **Developers** on technical design and best practices
- Advise **Product Managers** and **Stakeholders & Sponsors** on technical feasibility and trade-offs
- Collaborate with **QA/Testing Specialists** on testing strategy for complex components
- Support **Project Managers** in identifying and mitigating technical risks
- Partner with **Security & Compliance Leads** on secure architecture design
- Mentor team growth and support **Scrum Masters** in technical coaching

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove impediments, and help teams adopt agile practices. They focus on team dynamics, process improvement, and coaching rather than technical delivery.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments
- Coach team on agile principles and practices
- Maintain project board and process health metrics
- Drive continuous improvement through retrospective action items
- Support psychological safety and team dynamics
- Escalate impediments that require management attention

### Goals
- Maximize team velocity and delivery rhythm
- Foster continuous improvement and learning culture
- Ensure consistent process adherence and team health
- Enable self-organizing, high-performing teams

### Typical Communication
- Sprint ceremonies and retrospective facilitation
- Action item tracking and process metrics
- Coaching and team support conversations
- Process improvement recommendations

### Interaction with Other Roles
- Support **Developers**, **QA/Testing Specialists**, and other team members in removing blockers
- Facilitate collaboration between **Product Managers** and the delivery team
- Escalate team-level impediments to **Project Managers**
- Coach all team members on agile practices and team dynamics
- Support **Technical Architects** in mentoring and knowledge sharing
- Work with **Project Managers** on timeline and capacity planning
- Report team health metrics to leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interaction with Other Roles" sections to understand cross-functional dependencies and communication patterns.
