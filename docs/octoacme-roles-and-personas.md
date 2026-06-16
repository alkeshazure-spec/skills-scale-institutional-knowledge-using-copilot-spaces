# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **With Product Manager**: Receive acceptance criteria and design feedback
- **With Project Manager**: Discuss timelines, capacity, and blockers
- **With Engineering Manager**: Report on technical progress and challenges
- **With QA / Testing**: Coordinate on test coverage and acceptance validation

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Manager**: Align on release timeline and dependencies
- **With Developers**: Clarify requirements and trade-offs
- **With UX Designer**: Collaborate on user needs and design validation
- **With Data Analyst**: Define and review success metrics

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Manager**: Sync on priorities and release planning
- **With Engineering Manager**: Coordinate on capacity and resource allocation
- **With Delivery Lead**: Own the detailed execution plan
- **With Support Lead**: Coordinate post-release support and escalation plans

---

## Extended Roles

### Engineering Manager

#### Role Summary
Engineering Managers own technical delivery health, capacity planning, people development, and alignment of engineering practices. They bridge the gap between individual contributors and project leadership.

#### Responsibilities
- Manage engineering team capacity and workload balance
- Foster technical excellence and code quality standards
- Mentor and develop individual contributor skills
- Identify and communicate technical risks and blockers
- Contribute to architectural decisions and technical direction
- Support recruitment and retention efforts

#### Goals
- Maintain high team morale and retention
- Deliver consistent, predictable engineering output
- Build a culture of technical excellence and continuous learning
- Reduce technical debt and operational burden

#### Typical Communication
- 1-on-1s with team members
- Weekly sync with Project Manager and Product Manager on capacity and risks
- Technical design reviews and architecture discussions
- Escalation of blockers and people-related issues

#### Key Interactions
- **With Developers**: Provide coaching, feedback, and career development
- **With Project Manager**: Report capacity constraints and timeline feasibility
- **With Product Manager**: Advise on technical trade-offs and implementation approaches
- **With DevOps / Platform Engineer**: Collaborate on infrastructure and tooling needs

---

### Delivery Lead (Technical Program Manager)

#### Role Summary
The Delivery Lead coordinates cross-team delivery execution, owns dependency tracking, manages release scheduling, and drives day-to-day execution details. They complement the Project Manager by focusing on technical coordination and removal of engineering blockers.

#### Responsibilities
- Run daily or twice-weekly standups and track progress against milestones
- Maintain and update the risk register and dependency map
- Coordinate across teams on integration points and handoffs
- Own the release checklist and deployment readiness
- Escalate blockers and unblock the team
- Track and report on velocity and sprint health

#### Goals
- Keep projects on schedule with clear visibility into progress
- Minimize context-switching and unplanned rework
- Ensure smooth handoffs between engineering, QA, and deployment
- Enable the team to focus on delivery

#### Typical Communication
- Daily standups with engineering team
- Weekly coordination sync with cross-functional leads
- Regular updates to Project Manager on execution health
- Risk and blocker escalations

#### Key Interactions
- **With Developers and Engineering Manager**: Facilitate standups and unblock work
- **With Project Manager**: Report on delivery progress and risks
- **With QA Lead**: Coordinate testing schedule and acceptance sign-off
- **With DevOps**: Manage release scheduling and deployment coordination

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers validate user needs, produce design artifacts, and define usability acceptance criteria. They ensure that solutions are user-centered and meet accessibility and usability standards.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define usability acceptance criteria and design standards
- Participate in design reviews and provide feedback on implementation
- Ensure compliance with accessibility standards (WCAG, etc.)
- Measure and iterate on user satisfaction and design effectiveness

#### Goals
- Deliver intuitive, accessible, user-centric solutions
- Reduce support burden through better design
- Build user confidence and adoption of features
- Establish design consistency and usability standards

#### Typical Communication
- Design reviews with stakeholders and developers
- User research presentations and findings
- Design specification documents and component libraries
- Feedback on prototypes and implementations

#### Key Interactions
- **With Product Manager**: Align on user needs and success metrics
- **With Developers**: Collaborate on design feasibility and implementation details
- **With QA / Testing**: Define usability acceptance criteria
- **With Support Lead**: Incorporate user feedback from support issues

---

### DevOps / Platform Engineer

#### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, deployment infrastructure, environment reliability, and operational runbooks. They enable safe, repeatable, and observable deployments.

#### Responsibilities
- Build and maintain CI/CD pipelines for testing and deployment
- Manage staging and production environments
- Implement monitoring, logging, and alerting
- Create and maintain operational runbooks and playbooks
- Support incident response and rollback procedures
- Optimize infrastructure for reliability, performance, and cost

#### Goals
- Enable fast, safe deployments with minimal risk
- Maintain high system availability and observability
- Reduce manual, error-prone deployment steps
- Support rapid incident response and recovery

#### Typical Communication
- Design reviews for deployment and infrastructure changes
- Runbook documentation and incident response procedures
- Alerts and dashboards for operational health
- Post-deployment verification checklists

#### Key Interactions
- **With Developers**: Collaborate on deployment readiness and pipeline improvements
- **With Delivery Lead**: Coordinate release scheduling and deployment execution
- **With Security Engineer**: Implement security scanning and compliance controls
- **With Support Lead**: Support incident response and escalation

---

### Security Liaison / Security Engineer

#### Role Summary
Security Engineers run security reviews, perform threat modeling, and coordinate fixes for security findings. They ensure that solutions meet security and compliance requirements and that risks are mitigated appropriately.

#### Responsibilities
- Conduct security code reviews and threat modeling
- Identify and prioritize security vulnerabilities
- Define security acceptance criteria and requirements
- Coordinate remediation of security findings
- Ensure compliance with security policies and standards
- Provide security guidance and training to the team

#### Goals
- Deliver secure, compliant solutions
- Minimize security vulnerabilities and breach risk
- Build security awareness and best practices across the team
- Meet regulatory and compliance requirements

#### Typical Communication
- Security reviews and threat modeling sessions
- Vulnerability reports and remediation plans
- Security policies and standards documentation
- Pre-release security sign-off

#### Key Interactions
- **With Developers**: Review code and provide security guidance
- **With Product Manager**: Advise on security trade-offs and requirements
- **With DevOps**: Implement security scanning and compliance controls
- **With Project Manager**: Coordinate on security issue remediation timelines

---

### Data Analyst / Measurement Lead

#### Role Summary
Data Analysts define instrumentation strategies, track success metrics, build dashboards, and provide data-driven insights. They enable evidence-based decision-making and measure the impact of delivered features.

#### Responsibilities
- Define success metrics and KPIs for projects and features
- Design instrumentation and data collection strategies
- Build dashboards and reports for key signals
- Analyze feature usage and impact
- Identify trends and anomalies in production data
- Inform retrospectives and continuous improvement efforts

#### Goals
- Enable data-driven decision-making
- Measure and quantify the impact of delivered features
- Identify optimization opportunities based on usage patterns
- Build a culture of measurement and continuous improvement

#### Typical Communication
- Metric definition and instrumentation planning documents
- Dashboards and analytics reports
- Data-driven presentations and insights
- Post-release impact analysis

#### Key Interactions
- **With Product Manager**: Define success metrics and evaluate feature impact
- **With Developers**: Collaborate on instrumentation implementation
- **With QA / Testing**: Design test scenarios and data validation
- **With Support Lead**: Incorporate user feedback and support trends

---

### Support / Customer Success Lead

#### Role Summary
Support and Customer Success Leads own triage of customer issues, escalation to the delivery team, and feedback loops to Product. They are the voice of the customer and ensure that delivery is informed by real customer needs and pain points.

#### Responsibilities
- Triage and prioritize customer issues and support requests
- Escalate critical issues to the delivery team
- Gather and communicate customer feedback to Product
- Coordinate post-release support readiness and training
- Monitor customer satisfaction and health metrics
- Identify patterns in customer issues and suggest improvements

#### Goals
- Maximize customer satisfaction and retention
- Enable fast resolution of customer issues
- Bring customer voice into product planning
- Reduce support burden through better design and documentation

#### Typical Communication
- Customer issue reports and escalations
- Customer feedback and feature requests
- Support readiness plans and training materials
- Post-release support coordination

#### Key Interactions
- **With Product Manager**: Report customer feedback and support trends
- **With Project Manager**: Coordinate on post-release support readiness
- **With Developers**: Collaborate on issue reproduction and resolution
- **With Support Team**: Manage escalation and response procedures

---

### Subject Matter Expert (SME) / Domain Owner

#### Role Summary
SMEs and Domain Owners provide domain-specific guidance, compliance input, and acceptance of domain-related requirements. They ensure that solutions are correct, compliant, and aligned with domain best practices.

#### Responsibilities
- Provide domain expertise and guidance during planning and design
- Define domain-specific acceptance criteria and requirements
- Review and approve domain-related implementation details
- Ensure compliance with domain standards and regulations
- Train the team on domain-specific knowledge and practices
- Support acceptance testing and validation

#### Goals
- Ensure domain correctness and compliance
- Reduce domain-related rework and issues in production
- Build domain expertise across the team
- Meet regulatory and compliance requirements

#### Typical Communication
- Domain requirement documentation and standards
- Design and implementation reviews
- Domain-specific acceptance criteria and test cases
- Training and knowledge-sharing sessions

#### Key Interactions
- **With Product Manager**: Define domain requirements and constraints
- **With Developers**: Review implementation and provide guidance
- **With QA / Testing**: Define domain-specific acceptance criteria
- **With Project Manager**: Advise on domain-related risks and dependencies

---

## How These Personas Are Used

- **Project Charter**: Include relevant personas in the Project One-pager to clarify ownership and accountability.
- **Planning & Kickoff**: Use persona definitions to frame roles and responsibilities during project initiation.
- **Execution & Standups**: Reference personas to clarify handoffs, dependencies, and communication channels.
- **Retrospectives**: Use persona insights to identify gaps in collaboration or escalation.
- **Copilot Spaces Guidance**: Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and assistance.

## Notes on Scaling

- Not all projects will require all roles. Small projects may combine roles (e.g., Product Manager + Delivery Lead).
- For cross-functional initiatives, ensure clear ownership and escalation paths across personas.
- Use the **Key Interactions** section to clarify handoffs and communication channels between roles.
