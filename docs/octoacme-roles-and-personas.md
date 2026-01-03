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

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for creating intuitive, accessible, and visually appealing user experiences. They conduct user research, create wireframes and prototypes, and collaborate with developers to ensure design implementation matches intended user flows.

### Responsibilities
- Conduct user research and usability testing
- Design wireframes, mockups, and interactive prototypes
- Create and maintain design systems and component libraries
- Collaborate with product managers to understand user needs
- Work with developers to ensure accurate design implementation
- Validate designs through user feedback and analytics

### Goals
- Deliver user-centered designs that meet accessibility standards
- Improve user satisfaction and reduce friction in user journeys
- Maintain design consistency across all product touchpoints
- Create scalable design patterns that accelerate future development

### Typical Communication
- Design review sessions with product and engineering teams
- User research findings and recommendations
- Design specs and handoff documentation for developers
- Usability testing reports and iteration plans

### Interaction Points with Other Roles
- **Product Managers**: Collaborate on product requirements, user stories, and success metrics
- **Developers**: Provide design specifications, review implementations, clarify design intent
- **QA Engineers**: Define expected user experiences and visual regression test cases
- **Customer Success**: Gather user feedback and pain points to inform design decisions
- **Project Managers**: Provide design effort estimates and milestone commitments

---

## Quality Assurance (QA) Engineer

### Role Summary
QA Engineers ensure product quality through systematic testing, validation, and defect prevention. They design test strategies, execute manual and automated tests, and work closely with developers to identify and resolve issues before release.

### Responsibilities
- Develop comprehensive test plans and test cases
- Execute manual and automated testing (functional, regression, integration, performance)
- Identify, document, and track defects to resolution
- Validate acceptance criteria and user stories
- Maintain and expand automated test suites
- Perform exploratory testing to uncover edge cases
- Participate in requirement reviews to ensure testability

### Goals
- Deliver high-quality, bug-free software to production
- Maximize test coverage and automation efficiency
- Reduce escaped defects and production incidents
- Enable fast, confident releases through comprehensive testing

### Typical Communication
- Daily test status updates and defect reports
- Test plan reviews with product and engineering teams
- Bug triage sessions and severity assessments
- Release readiness reports and go/no-go recommendations

### Interaction Points with Other Roles
- **Developers**: Collaborate on defect resolution, test case reviews, and testability
- **Product Managers**: Validate acceptance criteria and prioritize testing focus areas
- **DevOps Engineers**: Integrate automated tests into CI/CD pipelines
- **UX/UI Designers**: Validate design implementations and user experience flows
- **Project Managers**: Report test progress, risks, and release readiness status

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and automation that enable rapid, reliable software delivery. They manage CI/CD pipelines, monitoring systems, and production environments while ensuring security, scalability, and observability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure and containerized environments
- Implement monitoring, logging, and alerting systems
- Ensure system reliability, performance, and scalability
- Automate operational tasks and infrastructure provisioning
- Manage secrets, credentials, and security configurations
- Participate in incident response and post-incident reviews

### Goals
- Achieve high deployment frequency with low failure rates
- Minimize mean time to recovery (MTTR) for incidents
- Automate repetitive operational tasks
- Maintain high system availability and performance

### Typical Communication
- Infrastructure status updates and capacity planning
- Incident response coordination and post-mortems
- Deployment schedules and change management notifications
- Infrastructure design reviews and technical documentation

### Interaction Points with Other Roles
- **Developers**: Provide deployment tools, troubleshoot build issues, optimize application performance
- **QA Engineers**: Integrate automated tests into pipelines, manage test environments
- **Security Lead**: Implement security controls, manage vulnerability scanning and remediation
- **Project Managers**: Communicate deployment schedules, infrastructure risks, and dependencies
- **Product Managers**: Provide observability data to inform product decisions

---

## Customer Success/Support Lead

### Role Summary
Customer Success/Support Leads serve as the voice of the customer, ensuring users achieve their desired outcomes while using OctoAcme products. They handle escalations, gather customer feedback, and collaborate with product and engineering teams to improve user experience.

### Responsibilities
- Manage customer escalations and critical support tickets
- Collect and synthesize customer feedback for product improvements
- Create and maintain customer-facing documentation and knowledge bases
- Conduct customer onboarding and training sessions
- Track customer health metrics and identify at-risk accounts
- Advocate for customer needs in product planning discussions
- Coordinate with engineering on issue reproduction and resolution

### Goals
- Maximize customer satisfaction and retention rates
- Reduce time-to-resolution for customer issues
- Proactively identify and address customer pain points
- Enable customer self-service through documentation and training

### Typical Communication
- Daily customer issue updates and escalation reports
- Weekly customer health reviews and churn risk analysis
- Feature requests and bug reports from customers
- Customer success stories and case studies

### Interaction Points with Other Roles
- **Product Managers**: Share customer insights, prioritize feature requests and pain points
- **Developers**: Report bugs, coordinate on issue reproduction and fixes
- **QA Engineers**: Validate fixes from customer perspective, provide real-world test scenarios
- **UX/UI Designers**: Share user feedback on design and usability issues
- **Project Managers**: Communicate customer commitments and deadlines

---

## Security Lead

### Role Summary
Security Leads establish and enforce security standards, practices, and controls across the software development lifecycle. They conduct security reviews, threat modeling, vulnerability assessments, and ensure compliance with security policies and regulations.

### Responsibilities
- Define security standards and best practices for the organization
- Conduct security reviews of designs, code, and infrastructure
- Perform threat modeling and risk assessments for new features
- Manage vulnerability scanning and coordinate remediation efforts
- Lead security incident response and investigations
- Ensure compliance with security regulations and standards
- Provide security training and guidance to development teams
- Review and approve third-party dependencies and integrations

### Goals
- Minimize security vulnerabilities and attack surface
- Ensure compliance with security standards and regulations
- Enable secure-by-default development practices
- Reduce time-to-detect and time-to-respond for security incidents

### Typical Communication
- Security review findings and remediation recommendations
- Vulnerability reports and patching schedules
- Security incident updates and post-incident reports
- Security training sessions and awareness communications

### Interaction Points with Other Roles
- **Developers**: Review code for security issues, provide secure coding guidance
- **DevOps Engineers**: Implement security controls in infrastructure and pipelines
- **Product Managers**: Assess security implications of new features, prioritize security work
- **QA Engineers**: Define security test cases and penetration testing scenarios
- **Project Managers**: Communicate security risks, compliance requirements, and timelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction points clarify cross-functional collaboration patterns for onboarding and day-to-day work.

