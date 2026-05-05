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

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for a project or product area. They define testing standards, coordinate test activities across the team, and act as the final gatekeeper for release readiness from a quality perspective.

### Responsibilities
- Define and maintain the test strategy, test plans, and acceptance criteria standards
- Coordinate manual and automated testing efforts across sprints
- Identify, track, and communicate defects through to resolution
- Establish and monitor quality metrics (e.g., defect rate, test coverage, escape rate)
- Review and approve release readiness from a quality standpoint
- Champion shift-left testing practices in collaboration with Developers

### Goals
- Prevent defects from reaching production
- Increase test automation coverage over time
- Ensure acceptance criteria are verifiable and consistently met

### Typical Communication
- Participates in sprint planning to clarify acceptance criteria
- Shares daily testing status in standups
- Produces QA sign-off summaries before each release
- Raises quality risks in the project risk register

### Interactions with Existing Roles
- **Developers**: pairs during development to write testable code and review test coverage
- **Project Manager**: reports on quality status and surfaces risks that may affect timelines
- **Product Manager**: aligns on acceptance criteria and helps validate that features meet user expectations
- **DevOps Engineer**: collaborates to integrate automated tests into CI/CD pipelines

---

## UX Designer

### Role Summary
The UX Designer ensures that features and products are usable, accessible, and aligned with user needs. They translate user research and business requirements into interaction designs and prototypes that guide development.

### Responsibilities
- Conduct user research, usability testing, and synthesis of findings
- Produce wireframes, prototypes, and design specifications
- Define and maintain UX guidelines, component patterns, and accessibility standards
- Collaborate with Product and Engineering to validate feasibility of designs
- Participate in design and sprint reviews to ensure implementation fidelity

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability issues discovered post-launch
- Maintain consistency across product surfaces through shared design patterns

### Typical Communication
- Attends sprint planning and backlog refinement to surface UX requirements early
- Shares design documents and prototypes for review with Product Manager and Developers
- Participates in demos and user testing sessions
- Contributes findings and recommendations to retrospectives

### Interactions with Existing Roles
- **Product Manager**: collaborates closely to translate user insights into prioritized requirements
- **Developers**: provides detailed design specs and answers implementation questions
- **QA Lead**: assists in defining usability and accessibility acceptance criteria
- **Customer Success Manager**: incorporates customer feedback into future design iterations

---

## DevOps Engineer

### Role Summary
The DevOps Engineer owns the continuous integration, delivery, and deployment infrastructure. They bridge development and operations by building reliable, automated pipelines and maintaining stable environments throughout the project lifecycle.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage environment configuration, infrastructure-as-code, and secrets management
- Monitor system health, performance, and availability; respond to incidents
- Enforce security scanning and compliance checks in the pipeline
- Establish and document deployment runbooks and rollback procedures
- Optimize build times and environment parity (dev/staging/production)

### Goals
- Enable fast, safe, and repeatable deployments
- Minimize environment-related toil and deployment risk
- Improve observability and reduce mean time to recovery (MTTR)

### Typical Communication
- Shares pipeline and environment status in standups or delivery syncs
- Documents runbooks and infrastructure changes in the repository
- Participates in release planning to flag deployment dependencies
- Contributes to incident postmortems and retrospectives

### Interactions with Existing Roles
- **Developers**: provides deployment guidance, reviews infrastructure-impacting code changes, and supports local environment setup
- **QA Lead**: integrates automated test suites into CI/CD and manages environment provisioning for testing
- **Project Manager**: coordinates deployment windows and communicates environment risks
- **Product Manager**: supports release readiness by ensuring environments and pipelines are ready for launch

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team. They gather, analyze, and document requirements, ensuring that what is built solves the right problem and delivers measurable business value.

### Responsibilities
- Elicit and document business requirements through workshops, interviews, and process analysis
- Translate business needs into actionable user stories, use cases, and acceptance criteria
- Maintain traceability between business goals and implemented features
- Identify process gaps and recommend improvements
- Support UAT (User Acceptance Testing) by coordinating with stakeholders and QA

### Goals
- Ensure delivered solutions align with stated business needs
- Reduce ambiguity in requirements to minimize rework
- Build shared understanding between business and technical teams

### Typical Communication
- Facilitates requirements workshops and presents findings to the team
- Documents requirements in the backlog with clear acceptance criteria
- Provides regular requirement clarification during sprint planning and backlog refinement
- Coordinates UAT sign-off with stakeholders

### Interactions with Existing Roles
- **Product Manager**: collaborates on problem framing, prioritization, and validation of business value
- **Project Manager**: aligns on scope, dependencies, and change requests that affect the project plan
- **Developers**: provides detailed requirements and answers clarifying questions during implementation
- **QA Lead**: defines and reviews acceptance criteria; supports UAT execution
- **UX Designer**: shares process and user research to inform design decisions

---

## Customer Success Manager

### Role Summary
The Customer Success Manager (CSM) acts as the voice of the customer after launch. They ensure customers realize value from delivered features, relay adoption feedback to the team, and coordinate escalations when customer issues arise.

### Responsibilities
- Monitor customer onboarding, adoption, and satisfaction metrics
- Collect and synthesize customer feedback and escalate product issues
- Work with Product and Project Managers on continuous improvement based on customer outcomes
- Facilitate customer communications around new releases, changes, and known issues
- Coordinate with Support and Operations for issue triage and resolution

### Goals
- Drive customer adoption and satisfaction post-launch
- Ensure product improvements are informed by real customer outcomes
- Reduce churn by proactively addressing customer pain points

### Typical Communication
- Shares customer feedback summaries with Product Manager and Developers after each release
- Participates in retrospectives to surface customer-reported issues
- Sends customer-facing release notes and announcements in coordination with the PM
- Escalates high-priority customer issues to the Project Manager for triage

### Interactions with Existing Roles
- **Product Manager**: provides customer feedback loop data to inform roadmap and prioritization
- **Project Manager**: escalates customer-impacting risks and coordinates release communications
- **Developers**: reports reproducible customer issues that require engineering investigation
- **UX Designer**: shares usability pain points observed in customer interactions

---

## Engineering Manager

### Role Summary
The Engineering Manager (EM) is responsible for the health, growth, and performance of the engineering team. They remove organizational blockers, support career development, and partner with the Project Manager and Product Manager to align team capacity with delivery goals.

### Responsibilities
- Manage the engineering team's workload, priorities, and capacity
- Coach and support engineers on technical and professional growth
- Partner with PM and PdM on resourcing, team structure, and dependency management
- Remove organizational and process blockers that impede delivery
- Drive engineering excellence initiatives (e.g., tech debt reduction, on-call health)

### Goals
- Maintain a high-performing, engaged engineering team
- Ensure team capacity aligns with project commitments
- Balance feature delivery with long-term technical investment

### Typical Communication
- Regular 1:1s with direct reports and skip-level check-ins
- Participates in planning and roadmap discussions to represent team capacity
- Coordinates with Project Manager on resourcing changes or escalations
- Shares team health updates with leadership

### Interactions with Existing Roles
- **Project Manager**: aligns on team availability, risks related to resourcing, and escalation paths
- **Product Manager**: partners on roadmap feasibility and priority trade-offs
- **Tech Lead**: delegates technical direction and collaborates on engineering standards
- **Developers**: provides growth coaching, removes blockers, and advocates for the team

---

## Tech Lead

### Role Summary
The Tech Lead provides technical leadership for a project or squad. They set the technical direction, make architecture decisions, guide developers through complex implementations, and ensure the codebase remains maintainable and aligned with broader engineering standards.

### Responsibilities
- Define and communicate technical approach, architecture, and standards for the project
- Lead technical design reviews and code reviews
- Identify and escalate technical risks, dependencies, and trade-offs
- Mentor and support developers in solving complex technical problems
- Collaborate with DevOps on CI/CD, infrastructure, and deployment strategies

### Goals
- Deliver a well-architected, maintainable, and scalable solution
- Reduce technical risk and unplanned rework
- Foster technical growth within the team

### Typical Communication
- Leads technical design discussions and documents decisions in ADRs or design docs
- Active participant in sprint planning, reviews, and retrospectives
- Provides technical status updates to the Project Manager and Engineering Manager
- Reviews and approves significant PRs and architectural changes

### Interactions with Existing Roles
- **Developers**: mentors, reviews code, and resolves technical blockers
- **DevOps Engineer**: collaborates on deployment strategy, pipeline design, and infrastructure decisions
- **Project Manager**: flags technical risks and provides effort estimates for planning
- **Product Manager**: translates technical trade-offs into business-relevant language
- **Engineering Manager**: shares team technical health and development needs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When designing cross-functional scenarios, refer to the [Cross-Functional Roles Reference](octoacme-cross-functional-roles-reference.md) for RACI and handoff guidance.

