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

## QA Lead / QA Engineer

### Role Summary
QA professionals ensure software quality and user acceptance through comprehensive testing, validation, and quality assurance practices. They collaborate with developers and product teams to define acceptance criteria and verify that features meet quality standards.

### Responsibilities
- Define test strategies and test plans aligned with feature acceptance criteria
- Execute manual and automated testing across unit, integration, and end-to-end scenarios
- Identify and triage defects, working with developers on reproductions and fixes
- Validate compliance with Definition of Done and acceptance criteria before release
- Contribute to release readiness assessments and sign-off
- Monitor quality metrics and recommend improvements

### Goals
- Deliver high-quality features with minimal post-release defects
- Reduce cycle time for bug discovery and resolution
- Build trust in release quality through rigorous validation

### Typical Communication
- Sprint planning and daily standups
- Test case and defect reports
- Pre-release quality sign-off meetings

### Interaction with Other Roles
- **With Developers**: Collaborate on test case design, defect reproductions, and acceptance criteria validation
- **With Product Managers**: Align on acceptance criteria and quality standards before development
- **With Project Managers**: Provide input on release readiness and risk assessment
- **With Security & Compliance Officer**: Coordinate on security and compliance testing requirements
- **With DevOps/Infrastructure Engineer**: Validate deployment readiness and production smoke tests

---

## Security & Compliance Officer

### Role Summary
Security professionals protect the organization by embedding security and compliance considerations into every phase of project delivery. They collaborate with engineering and product teams to identify risks, define controls, and ensure regulatory or policy alignment.

### Responsibilities
- Review features and architecture for security vulnerabilities and compliance gaps
- Define security acceptance criteria and threat models where needed
- Coordinate security scanning, penetration testing, and compliance audits
- Provide security incident response support and post-incident guidance
- Train team members on security best practices
- Maintain and communicate security policy and standards

### Goals
- Prevent security breaches and compliance violations
- Embed security practices into development workflows
- Reduce security-related incidents and rework

### Typical Communication
- Security design reviews and threat modeling sessions
- Risk registers and security incident reports
- Compliance and audit documentation

### Interaction with Other Roles
- **With Developers**: Define secure coding standards, review designs for vulnerabilities, provide security training
- **With Product Managers**: Ensure security and compliance requirements are included in acceptance criteria
- **With Project Managers**: Escalate security risks, coordinate audits, and communicate compliance timelines
- **With QA Lead**: Coordinate on security testing and penetration test coordination
- **With DevOps/Infrastructure Engineer**: Ensure infrastructure security controls and secure deployment practices

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps professionals build and maintain the infrastructure, deployment pipelines, and operational systems that enable reliable, scalable delivery. They ensure systems are observable, maintainable, and ready for production.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, monitoring, and alerting
- Support incident response and operational troubleshooting
- Collaborate on performance, scaling, and reliability requirements
- Document runbooks and operational procedures
- Ensure backup, disaster recovery, and rollback capabilities

### Goals
- Enable fast, safe, and repeatable deployments
- Minimize downtime and operational incidents
- Support observability and rapid incident response

### Typical Communication
- Release planning and deployment coordination
- Incident response and status updates
- Infrastructure and performance reviews

### Interaction with Other Roles
- **With Developers**: Support local development environments, CI/CD feedback, and deployment guidance
- **With Project Managers**: Communicate deployment windows, infrastructure dependencies, and operational risks
- **With QA Lead**: Coordinate staging deployment and smoke test environments
- **With Release Manager**: Execute deployments and coordinate rollback procedures
- **With Security & Compliance Officer**: Implement security controls, manage credentials, and comply with audit requirements

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide strategic technical direction, drive architectural decisions, and ensure system design aligns with business goals and technical best practices. They mentor developers and facilitate technical collaboration across teams.

### Responsibilities
- Define and evolve system architecture and technical strategy
- Conduct design reviews and provide architectural guidance
- Identify and mitigate technical risks and dependencies
- Mentor developers and promote technical excellence
- Ensure scalability, performance, and maintainability
- Facilitate knowledge sharing and technical standards documentation

### Goals
- Build scalable, maintainable systems aligned with business goals
- Reduce technical debt and architectural risks
- Elevate team technical capability and decision-making

### Typical Communication
- Technical design reviews and architecture discussions
- Technical documentation and decision records
- One-on-ones with developers and team technical mentoring

### Interaction with Other Roles
- **With Developers**: Guide implementation decisions, review complex designs, provide technical mentorship
- **With Product Managers**: Advise on technical feasibility, trade-offs, and dependencies during planning
- **With Project Managers**: Identify technical risks, dependencies, and timeline impacts
- **With QA Lead**: Define technical quality standards and test strategies for complex components

---

## Design / UX Lead

### Role Summary
Design and UX professionals advocate for the user experience and usability throughout the project lifecycle. They conduct research, create design standards, and ensure features are intuitive and meet user needs.

### Responsibilities
- Conduct user research and define personas and use cases
- Create wireframes, prototypes, and design specifications
- Establish design systems and usability standards
- Collaborate with developers on implementation fidelity
- Validate designs through user testing and iteration
- Ensure accessibility and inclusive design principles

### Goals
- Deliver intuitive, user-centered features
- Maintain design consistency and brand alignment
- Reduce post-release usability issues

### Typical Communication
- Design reviews and user testing sessions
- Design specifications and component documentation
- Feedback and iteration with developers and product teams

### Interaction with Other Roles
- **With Product Managers**: Define success metrics around usability, collaborate on feature specs
- **With Developers**: Communicate design specifications, iterate on implementation feedback
- **With Project Managers**: Advise on timeline impacts for research and testing activities
- **With QA Lead**: Define usability acceptance criteria and user experience test cases

---

## Release Manager

### Role Summary
Release Managers coordinate and execute the release process from planning through production deployment. They ensure releases are well-coordinated, communicated, and executed with minimal risk.

### Responsibilities
- Create and maintain release plans and timelines
- Coordinate across teams to ensure release readiness
- Manage release notes and stakeholder communication
- Execute or oversee deployment activities
- Monitor release quality and manage rollback procedures
- Track post-release issues and feedback

### Goals
- Execute releases on time with minimal risk and disruption
- Maintain clear communication and transparency during releases
- Reduce mean time to recovery (MTTR) for release issues

### Typical Communication
- Release planning meetings and coordination calls
- Release notes and stakeholder announcements
- Deployment status updates and post-release reports

### Interaction with Other Roles
- **With Project Managers**: Coordinate release schedules and dependencies
- **With DevOps/Infrastructure Engineer**: Execute deployment activities and manage rollbacks
- **With QA Lead**: Confirm release readiness and coordinate smoke testing
- **With Product Managers**: Manage stakeholder communication and market readiness
- **With Technical Lead**: Coordinate complex deployments and technical dependencies

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, decision authority, and resource decisions that guide project direction. They represent customer/business needs and serve as escalation and approval authority.

### Responsibilities
- Define business goals and success criteria for projects
- Provide approval authority for scope and budget decisions
- Escalate and resolve blockers outside team's control
- Communicate project status to broader organization
- Provide feedback and validate solutions meet business needs
- Champion project and allocate resources

### Goals
- Ensure projects deliver business value and ROI
- Maintain alignment between project delivery and business strategy
- Enable effective decision-making and risk management

### Typical Communication
- Stakeholder reviews and approvals
- Executive status updates and business reports
- Escalation and decision forums

### Interaction with Other Roles
- **With Project Managers**: Receive status updates, provide approvals and decision authority
- **With Product Managers**: Align on business goals, success metrics, and prioritization
- **With Technical Lead**: Understand technical trade-offs and business implications
- **With Development Team**: Provide feedback and validation of delivered value

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona interactions to understand cross-functional dependencies and communication flows.
