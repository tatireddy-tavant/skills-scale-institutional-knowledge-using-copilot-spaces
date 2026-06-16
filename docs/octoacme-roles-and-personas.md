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

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads provide technical direction and establish quality standards for the project. They collaborate with developers on architecture decisions, mentor team members, and ensure the technical solution aligns with long-term maintainability goals.

### Responsibilities
- Define technical architecture and design patterns
- Set code quality standards and review practices
- Make trade-off decisions on tech debt vs. new features
- Mentor and onboard new engineers on the project
- Identify and escalate technical risks
- Coordinate with QA on testing strategy

### Goals
- Deliver scalable, maintainable technical solutions
- Build engineering capability within the team
- Balance velocity with code quality
- Reduce technical debt accumulation

### Interactions
- **With Developers:** Provides design guidance, reviews architecture proposals, approves major technical decisions
- **With Product Manager:** Discusses trade-offs, estimates feasibility, advises on scope impact
- **With QA/Testing:** Defines testability requirements, coordinates testing strategy
- **With Project Manager:** Escalates technical blockers and risks

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and mentoring
- Technical risk assessments
- Pre-sprint tech planning sessions

---

## Delivery Lead / Scrum Master

### Role Summary
Delivery Leads ensure the team executes efficiently within their sprint or iteration cadence. They facilitate ceremonies, remove impediments, track progress, and help the team maintain sustainable delivery pace.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help resolve team blockers and impediments
- Track sprint velocity and burndown
- Ensure sprint commitment is realistic and met
- Coordinate dependencies and escalate cross-team blockers
- Maintain team morale and psychological safety

### Goals
- Maximize team throughput and consistency
- Reduce cycle time and unplanned disruptions
- Build a healthy, sustainable delivery rhythm
- Improve team collaboration and transparency

### Interactions
- **With Project Manager:** Partners on release planning, escalates blockers, reports on delivery metrics
- **With Developers:** Removes impediments, facilitates ceremonies, tracks individual capacity
- **With Product Manager:** Ensures backlog readiness, discusses priorities with team
- **With other teams:** Coordinates sprint-level dependencies

### Typical Communication
- Daily standup facilitation
- Sprint retrospectives and action tracking
- Burndown and velocity reporting
- Blocker resolution and escalation

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers ensure solutions are user-centered, accessible, and delightful. They validate design decisions through research, create design artifacts, and work with developers to implement designs that meet usability and accessibility standards.

### Responsibilities
- Conduct user research to understand needs and pain points
- Create wireframes, prototypes, and design specifications
- Validate design decisions through usability testing
- Ensure accessibility standards (WCAG) are met
- Collaborate with developers on design implementation
- Define and validate UX acceptance criteria

### Goals
- Deliver intuitive, accessible user experiences
- Reduce design-related rework and scope creep
- Ground product decisions in user insights
- Ensure compliance with accessibility standards

### Interactions
- **With Product Manager:** Shares user research, validates problem statements, refines acceptance criteria
- **With Developers:** Hands off design specifications, reviews implementation for fidelity, advises on technical trade-offs
- **With QA/Testing:** Coordinates usability testing, validates acceptance criteria
- **With Engineering Lead:** Discusses technical feasibility of design proposals

### Typical Communication
- User research findings and insights
- Design specs and prototypes
- Design reviews and feedback
- Usability testing coordination and results

---

## Data & Measurement Lead

### Role Summary
Data & Measurement Leads define success metrics, instrument products for observability, and drive data-informed decision-making. They ensure the team can measure impact and learn from production data.

### Responsibilities
- Define and validate success metrics aligned with business goals
- Design telemetry and instrumentation strategy
- Set up dashboards and monitoring for key signals
- Analyze experiment results and usage patterns
- Advise on data-driven prioritization decisions
- Ensure compliance with data privacy and security standards

### Goals
- Enable data-driven product decisions
- Provide early signal on feature impact and risks
- Reduce guesswork in prioritization
- Build a culture of measurement and continuous improvement

### Interactions
- **With Product Manager:** Defines metrics, analyzes experiment results, advises on priorities
- **With Developers:** Reviews instrumentation code, validates telemetry implementation
- **With Project Manager:** Reports on key success metrics and project health signals
- **With Release/DevOps Engineer:** Coordinates deployment monitoring and incident tracking

### Typical Communication
- Metric definitions and success dashboards
- Experiment analysis and insights
- Data-driven recommendations
- Monitoring and alert configuration

---

## Release / DevOps Engineer

### Role Summary
Release and DevOps Engineers own the deployment pipeline, environment management, and runbooks for releasing software safely and reliably. They ensure teams can deploy confidently with minimal manual effort and quick rollback capability.

### Responsibilities
- Build and maintain release pipelines and CI/CD automation
- Manage staging and production environments
- Document and execute deployment runbooks
- Define and practice rollback procedures
- Monitor releases for early signals of problems
- Coordinate with teams on deployment scheduling and verification

### Goals
- Enable fast, low-risk deployments
- Minimize manual, error-prone release steps
- Reduce mean time to detection (MTTD) and mean time to recovery (MTTR)
- Support frequent, small incremental releases

### Interactions
- **With Developers:** Reviews deployment-readiness, coordinates code deployment, communicates deployment windows
- **With QA/Testing:** Coordinates staging verification before production deployment
- **With Project Manager:** Schedules releases, communicates deployment status
- **With Data & Measurement Lead:** Monitors post-deployment metrics and health signals

### Typical Communication
- Deployment runbooks and procedures
- Release notes and deployment checklists
- Rollback and incident response coordination
- Deployment status updates and metrics

---

## Compliance / Security Owner

### Role Summary
Compliance and Security Owners ensure projects meet regulatory, legal, and security requirements. They review designs and implementations early, approve releases when controls are needed, and advise on risk mitigation.

### Responsibilities
- Identify compliance and security requirements early in the project
- Review designs and implementations for security/compliance risks
- Approve releases where security or regulatory controls are needed
- Advise on data privacy, encryption, and access controls
- Coordinate with external audits and certifications
- Escalate security incidents and risks

### Goals
- Ensure products are secure and compliant by design
- Reduce security and compliance rework late in the project
- Maintain customer trust and regulatory standing
- Build security awareness across the team

### Interactions
- **With Product Manager:** Reviews requirements early, advises on feature impacts
- **With Engineering Lead:** Designs security architecture, reviews technical implementations
- **With Developers:** Provides security guidance, conducts code/design reviews for sensitive areas
- **With Release/DevOps Engineer:** Approves production deployments when controls are required
- **With Project Manager:** Escalates compliance risks and timelines

### Typical Communication
- Security/compliance requirement assessments
- Design and code review comments
- Risk assessments and mitigation plans
- Release approval decisions
- Incident response and post-mortems

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interactions sections to understand handoffs and dependencies across the team.
