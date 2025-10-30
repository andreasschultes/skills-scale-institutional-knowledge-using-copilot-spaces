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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile practices and ceremonies, remove impediments, and coach teams on continuous improvement. They ensure the team follows agreed-upon processes and foster self-organization.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Remove blockers and impediments to team progress
- Coach the team on agile principles and self-organization
- Shield the team from external distractions and scope changes
- Track team metrics (velocity, cycle time) and identify improvement areas
- Collaborate with Project Managers on delivery coordination

### Goals
- Maximize team productivity and flow
- Foster continuous improvement and learning
- Ensure adherence to Definition of Done and team agreements
- Maintain healthy team dynamics and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- Weekly sync with Project Manager on blockers and risks
- Retrospective facilitation and action item tracking
- Team metrics and improvement updates

### Interactions with Other Roles
- **Project Managers**: Coordinates on timelines, dependencies, and escalations; shares team velocity and capacity insights
- **Developers**: Removes blockers, facilitates collaboration, and ensures clear understanding of work
- **Product Managers**: Helps refine backlog items and clarifies priorities during planning

---

## UX Designer

### Role Summary
UX Designers research user needs, create wireframes and prototypes, and validate designs through user testing. They ensure products are intuitive, accessible, and aligned with user expectations.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and information architecture
- Collaborate with Product Managers on requirements and priorities
- Work with Developers to ensure design feasibility and implementation fidelity
- Maintain design systems and accessibility standards

### Goals
- Deliver user-centered, accessible designs
- Reduce usability issues and support costs
- Ensure consistency across product experiences
- Validate designs with real users before development

### Typical Communication
- Design reviews with stakeholders and developers
- User research findings and usability test reports
- Weekly syncs with Product Managers and Project Managers
- Handoff documentation and design specs for developers

### Interactions with Other Roles
- **Product Managers**: Collaborates on feature definitions and user needs; validates solutions through research
- **Developers**: Provides design specifications and supports implementation; reviews built features for design fidelity
- **Customer Support Liaison**: Gathers user feedback and pain points to inform design decisions

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, analyze processes, and ensure deliverables align with business objectives and stakeholder expectations.

### Responsibilities
- Elicit and document business requirements and acceptance criteria
- Analyze current processes and identify improvement opportunities
- Create process flows, data models, and requirement specifications
- Validate solutions against business needs and success criteria
- Facilitate stakeholder workshops and requirement reviews
- Support User Acceptance Testing (UAT) planning and execution

### Goals
- Ensure solutions meet business needs and deliver value
- Reduce rework by clarifying requirements early
- Bridge communication between business stakeholders and technical teams
- Identify and document business rules and constraints

### Typical Communication
- Requirement workshops and stakeholder interviews
- Requirement documents and user stories
- UAT plans and test scenarios
- Weekly alignment with Product Managers and Project Managers

### Interactions with Other Roles
- **Product Managers**: Collaborates on defining requirements and prioritizing features based on business value
- **Developers**: Clarifies requirements, answers questions, and validates implementations
- **Project Managers**: Provides input on scope, dependencies, and requirement changes
- **Customer Support Liaison**: Gathers operational feedback and translates it into requirements

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process, ensuring smooth deployments and minimizing risk. They manage release schedules, orchestrate cross-team coordination, and ensure proper communication.

### Responsibilities
- Plan and schedule releases across teams and environments
- Coordinate release activities and dependencies
- Ensure all pre-release requirements are met (testing, documentation, approvals)
- Manage deployment execution and monitor post-release health
- Maintain release documentation and runbooks
- Facilitate go/no-go decisions and rollback procedures

### Goals
- Deliver reliable, on-time releases
- Minimize deployment-related incidents and downtime
- Ensure clear communication and coordination across teams
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings and coordination calls
- Release status updates and deployment notifications
- Go/no-go decision meetings with stakeholders
- Post-release reports and retrospectives

### Interactions with Other Roles
- **Project Managers**: Aligns on release schedules and coordinates cross-project dependencies
- **Developers**: Coordinates code freeze, branch management, and deployment readiness
- **Security Lead**: Ensures security scans and approvals are complete before release
- **Customer Support Liaison**: Coordinates release communications and prepares support teams

---

## Customer Support Liaison

### Role Summary
Customer Support Liaisons represent the customer perspective throughout the project lifecycle. They gather feedback, identify pain points, and ensure support teams are prepared for new releases.

### Responsibilities
- Collect and communicate customer feedback and feature requests
- Participate in planning to represent customer needs and support impact
- Review features for supportability and documentation needs
- Prepare support teams for upcoming releases (training, FAQs, runbooks)
- Escalate critical customer issues to product and engineering teams
- Track support metrics and identify areas for product improvement

### Goals
- Ensure customer needs are represented in product decisions
- Reduce support burden through better UX and documentation
- Prepare support teams for successful customer assistance
- Close the feedback loop between customers and product teams

### Typical Communication
- Weekly syncs with Product Managers on customer feedback
- Release readiness meetings with Release Managers
- Support documentation and training materials
- Customer issue escalations and trend reports

### Interactions with Other Roles
- **Product Managers**: Shares customer insights and feedback; influences prioritization
- **UX Designer**: Provides user feedback and identifies usability issues
- **Release Manager**: Reviews release notes and prepares support team for changes
- **Business Analyst**: Contributes to requirement definition based on customer needs

---

## Security Lead

### Role Summary
Security Leads ensure security is integrated throughout the development lifecycle. They conduct security reviews, manage vulnerabilities, and ensure compliance with security standards and regulations.

### Responsibilities
- Conduct security design reviews and threat modeling
- Define security requirements and acceptance criteria
- Review code and architecture for security vulnerabilities
- Manage security scanning tools and vulnerability remediation
- Ensure compliance with security policies and regulations
- Provide security training and guidance to teams

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with security standards and regulations
- Foster a security-aware culture across teams
- Minimize time to detect and remediate security issues

### Typical Communication
- Security review meetings during design and planning
- Vulnerability reports and remediation tracking
- Security risk assessments and compliance updates
- Training sessions and security advisories

### Interactions with Other Roles
- **Developers**: Reviews code for security issues; provides secure coding guidance
- **Release Manager**: Ensures security scans are complete and vulnerabilities are addressed before release
- **Project Managers**: Communicates security risks and coordinates remediation efforts
- **Business Analyst**: Defines security requirements and compliance constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded role set reflects modern project management practices and cross-functional collaboration patterns.

---

## Cross-Role Interactions Summary

The roles defined in this document work together throughout the project lifecycle:

**During Initiation:**
- Business Analyst gathers requirements with Product Manager
- Security Lead reviews initial security and compliance needs
- UX Designer conducts early user research

**During Planning:**
- Scrum Master facilitates sprint planning and estimates
- Release Manager establishes release timeline and dependencies
- Customer Support Liaison provides input on supportability

**During Execution:**
- Developers build features guided by UX Designer specifications
- Scrum Master removes blockers and tracks team velocity
- Security Lead conducts ongoing security reviews

**During Release:**
- Release Manager coordinates deployment activities
- Customer Support Liaison prepares support teams
- Security Lead ensures security scans are complete

**During Retrospective:**
- Scrum Master facilitates learning and improvement
- All roles contribute feedback for continuous improvement

These interactions ensure clear handoffs, shared accountability, and effective collaboration across the entire project lifecycle.

---

_Reference: This enhancement addresses gaps identified in [Issue #4](https://github.com/andreasschultes/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)_

