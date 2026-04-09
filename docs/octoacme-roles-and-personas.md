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

## DevOps Engineer

### Role Summary
DevOps Engineers automate infrastructure and delivery pipelines, manage deployments, and ensure system reliability. They bridge the gap between development and operations to enable fast, safe, and repeatable releases.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate infrastructure provisioning and configuration management
- Monitor system health, performance, and availability
- Manage deployment processes and rollback strategies
- Collaborate on release readiness and environment stability

### Goals
- Enable frequent, low-risk deployments
- Reduce manual toil through automation
- Maintain high availability and observability across environments

### Typical Communication
- Sprint planning and release coordination with Developers and Project Managers
- On-call runbooks and incident postmortems
- Infrastructure documentation and deployment guides

### Interaction with Existing Roles
- **Developers**: Partners on delivery automation, pipeline configuration, and environment parity
- **Product Managers**: Consults on operational requirements for features (e.g., scaling, monitoring)
- **Project Managers**: Provides deployment status updates and flags operational risks

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers own the quality of the user experience. They conduct user research, create wireframes and prototypes, and collaborate with product and engineering teams to ensure solutions are usable, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research, usability testing, and synthesis
- Develop wireframes, prototypes, and interaction specifications
- Define and maintain design standards and accessibility requirements
- Collaborate on acceptance criteria and feature definitions
- Validate designs with users and iterate based on feedback

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Ground product decisions in user evidence and data
- Reduce rework by aligning design and engineering early

### Typical Communication
- Design reviews and critique sessions
- Usability test reports and research readouts
- Annotations and design specs shared with developers

### Interaction with Existing Roles
- **Product Managers**: Collaborates during discovery and feature design to align on user needs and success metrics
- **Developers**: Works alongside engineering during implementation to clarify design intent and review delivered UI
- **Project Managers**: Communicates design milestones and flags risks related to user experience scope

---

## Security Champion

### Role Summary
Security Champions advocate for secure coding practices and proactive risk management throughout the software development lifecycle. They embed security thinking into the team's day-to-day workflows and serve as the primary liaison for security concerns.

### Responsibilities
- Promote and coach secure coding standards and best practices
- Facilitate threat modeling and security design reviews
- Review code and architecture for common vulnerabilities
- Coordinate with compliance and security teams on requirements
- Track and help remediate security findings and incidents

### Goals
- Shift security left by catching issues early in the development cycle
- Reduce the team's exposure to known vulnerability patterns
- Build security awareness and accountability across the team

### Typical Communication
- Security review sessions and threat model workshops
- Vulnerability reports and remediation tracking
- Escalations to Project Managers and senior leadership when risk thresholds are exceeded

### Interaction with Existing Roles
- **Developers**: Engaged during code reviews and design discussions to identify and remediate security risks
- **Product Managers**: Advises on security implications of product decisions and compliance requirements
- **Project Managers**: Reports security risks, helps prioritize remediation work, and advises on incident response

---

## Data Steward

### Role Summary
Data Stewards manage data quality, governance, and compliance across the organization. They define standards for how data is collected, stored, used, and protected, and ensure that features and processes meet regulatory and privacy requirements.

### Responsibilities
- Define and enforce data quality standards and governance policies
- Manage data classification, retention, and privacy requirements
- Review feature designs for compliance with data regulations (e.g., GDPR, CCPA)
- Maintain a data catalog and document data lineage
- Collaborate on data-related requirements and acceptance criteria

### Goals
- Ensure data is accurate, consistent, and trustworthy
- Reduce compliance risk through proactive governance
- Enable teams to use data confidently and responsibly

### Typical Communication
- Data governance reviews and compliance assessments
- Privacy impact assessments and audit reports
- Requirements documentation for data handling in features

### Interaction with Existing Roles
- **Developers**: Provides data requirements and reviews implementation for compliance alignment
- **Product Managers**: Consults on data strategy, privacy considerations, and regulatory constraints
- **Project Managers**: Flags data governance risks and ensures compliance milestones are tracked in project plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

