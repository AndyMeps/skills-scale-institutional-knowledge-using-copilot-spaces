# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

**Related Issue**: [#4 - Adding more personas and roles to the project management processes](https://github.com/AndyMeps/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

For a cross-reference matrix of roles and their involvement in project phases, see the [Role-Responsibility Matrix](templates/role-responsibility-matrix.md).

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

### Key Interactions
- **With Product Managers**: clarify requirements and acceptance criteria, estimate effort
- **With Project Managers**: report progress, identify blockers and risks
- **With UX Designers**: collaborate on design implementation and feasibility
- **With DevOps Engineers**: coordinate on deployment pipelines and infrastructure needs
- **With QA Automation Specialists**: design for testability, review test coverage
- **With Business Analysts**: clarify technical feasibility of requirements

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

### Key Interactions
- **With Project Managers**: coordinate on timelines, resource allocation, and scope
- **With Developers**: clarify requirements, review implementations
- **With UX Designers**: align user needs with business goals, validate prototypes
- **With Business Analysts**: collaborate on requirements elicitation and prioritization
- **With Stakeholders**: gather feedback and communicate product decisions

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

### Key Interactions
- **With Product Managers**: coordinate on priorities and resource needs
- **With Developers**: track progress, remove blockers
- **With DevOps Engineers**: coordinate deployment schedules and release planning
- **With QA**: ensure test plans align with project timelines
- **With Business Analysts**: ensure requirements are properly tracked and communicated
- **With Stakeholders**: provide regular updates and manage expectations

---

## UX Designer

### Role Summary
UX Designers own user research, prototyping, and usability testing. They advocate for accessible, user-centric design throughout project delivery and ensure that features meet both user needs and business goals.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity designs
- Perform usability testing and iterate based on feedback
- Collaborate with Product Managers to refine requirements
- Partner with Developers to ensure quality design handoff and implementation
- Advocate for accessibility and inclusive design practices
- Maintain design systems and component libraries

### Goals
- Deliver intuitive, accessible user experiences
- Validate design decisions with user research and testing
- Maintain design consistency across products
- Reduce friction in user workflows

### Typical Communication
- Design reviews and critique sessions
- User research findings and test results
- Design specs and handoff documentation
- Regular sync with Product and Development teams

### Key Interactions
- **With Product Managers**: align user needs with business goals, validate feature priorities
- **With Developers**: ensure design feasibility, provide implementation guidance, review front-end code
- **With QA/QA Automation Specialists**: validate design intent in testing, ensure UI/UX quality
- **With Business Analysts**: understand business requirements and translate them into user experiences
- **With Project Managers**: coordinate timelines for design deliverables

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain deployment pipelines, infrastructure-as-code, and system monitoring. They ensure robust, repeatable releases and enable early detection of production issues.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure-as-code and cloud resources
- Implement system monitoring, logging, and alerting
- Ensure security best practices in deployment processes
- Automate environment provisioning and configuration
- Support incident response and system reliability
- Optimize build and deployment performance

### Goals
- Achieve fast, reliable, zero-downtime deployments
- Maximize system uptime and observability
- Reduce manual operations through automation
- Enable developers to deploy confidently and independently

### Typical Communication
- Deployment status and release coordination
- Infrastructure changes and maintenance windows
- Incident reports and postmortems
- Performance and reliability metrics

### Key Interactions
- **With Developers**: support build and release processes, troubleshoot deployment issues
- **With QA/QA Automation Specialists**: automate test environments, integrate testing into CI/CD
- **With Project Managers**: coordinate deployment timelines and release schedules
- **With Product Managers**: align infrastructure capacity with product roadmap
- **With Security teams**: implement security scanning and compliance controls

---

## QA Automation Specialist

### Role Summary
QA Automation Specialists design and maintain automated test suites. They work to increase test coverage, detect issues before release, and drive continuous improvement in testing processes.

### Responsibilities
- Design and implement automated test frameworks
- Create and maintain automated test suites (unit, integration, E2E)
- Work with Developers to increase test coverage
- Integrate automated tests into CI/CD pipelines
- Identify and report defects with clear reproduction steps
- Analyze test results and metrics
- Champion testability in design and architecture
- Perform exploratory testing when needed

### Goals
- Maximize automated test coverage and reliability
- Detect defects early in the development cycle
- Reduce manual testing burden
- Improve overall product quality and stability

### Typical Communication
- Test results and quality metrics
- Defect reports and triage discussions
- Test plan reviews
- Automation framework updates

### Key Interactions
- **With Developers**: design for testability, review code changes for test impact, pair on test automation
- **With DevOps Engineers**: integrate tests into CI/CD, manage test environments
- **With Product Managers**: validate acceptance criteria, ensure requirements are testable
- **With UX Designers**: validate UI/UX implementation against designs
- **With Project Managers**: report on test progress and quality risks

---

## Business Analyst

### Role Summary
Business Analysts elicit, document, and clarify requirements from stakeholders. They translate business needs into actionable items and ensure the delivery team is aligned on priorities throughout the project lifecycle.

### Responsibilities
- Elicit requirements from stakeholders through interviews, workshops, and analysis
- Document business requirements and user stories
- Clarify and refine requirements for the development team
- Validate that delivered features meet business needs
- Identify process improvements and optimization opportunities
- Maintain traceability between requirements and implementation
- Facilitate communication between business and technical teams

### Goals
- Ensure requirements are clear, complete, and actionable
- Bridge the gap between business stakeholders and technical teams
- Maximize business value delivery
- Reduce rework caused by misunderstood requirements

### Typical Communication
- Requirements documents and user stories
- Stakeholder workshop facilitation
- Requirements clarification sessions
- Business process diagrams and workflows

### Key Interactions
- **With Product Managers**: collaborate on requirements elicitation and prioritization
- **With Developers**: clarify technical feasibility, answer requirements questions
- **With Project Managers**: ensure requirements are tracked and communicated
- **With UX Designers**: align business requirements with user experience
- **With QA**: ensure acceptance criteria are clear and testable
- **With Stakeholders**: gather needs, provide updates on requirement implementation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

