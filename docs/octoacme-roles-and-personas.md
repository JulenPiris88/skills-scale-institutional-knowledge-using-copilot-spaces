# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It also expands the set of personas to include cross-functional contributors and provides clear interaction points to improve clarity and handoffs.

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

## UX Designer / Product Designer

### Role Summary
Designs user experiences and interfaces that meet user needs and business goals. Helps convert product requirements into usable interfaces.

### Responsibilities
- Conduct user research and usability testing
- Produce wireframes, interaction designs, and high-fidelity mocks
- Collaborate on acceptance criteria related to UX
- Provide design assets and implementation guidance

### Typical Interactions
- Works with Product Managers to translate requirements
- Partners with Developers to ensure feasible implementations
- Supports QA and PMs during acceptance and reviews

---

## QA Engineer / Test Engineer

### Role Summary
Ensures product quality through planned testing and verification; supports automation and test strategy.

### Responsibilities
- Define and execute test plans (unit, integration, e2e where applicable)
- Build/maintain automated test suites and test data
- Validate acceptance criteria and regression checks
- Report and verify fixes and contribute to release readiness

### Typical Interactions
- Works closely with Developers on testability and bug triage
- Coordinates with Project Managers and Release Manager for release sign-off
- Feeds quality findings into retrospectives and planning

---

## Scrum Master / Agile Coach

### Role Summary
Facilitates the team’s agile process and removes impediments to flow and delivery.

### Responsibilities
- Facilitate agile ceremonies (standups, planning, retrospectives)
- Coach teams on agile practices and continuous improvement
- Help unblock work and improve team dynamics

### Typical Interactions
- Supports Developers, PMs, and PdMs to keep the team on track
- Coaches Project Managers and Product Managers on agile tooling and cadence
- Raises process impediments to leadership as needed

---

## Release Manager

### Role Summary
Coordinates and validates releases; ensures deployments are planned, communicated, and verified.

### Responsibilities
- Plan and schedule releases with stakeholders
- Validate pre-release requirements and checklists
- Coordinate deployment steps and post-release verification
- Manage rollback and mitigation plans

### Typical Interactions
- Works with Developers, QA, and PMs to confirm readiness
- Communicates release windows and status to Support and Stakeholders
- Owns release notes and post-release follow-ups

---

## Support Specialist / Customer Support

### Role Summary
Provides post-release user support, triages incidents, and funnels user feedback back into product and project decisions.

### Responsibilities
- Triage incoming tickets and incidents
- Communicate user-impact and reproducible steps to engineering
- Maintain knowledge base and support documentation
- Collaborate on incident communications and post-incident follow-up

### Typical Interactions
- Notifies PdMs and PMs of user-impacting issues
- Works with Release Manager during incidents
- Provides input for prioritization of bug fixes

---

## DevOps / Platform Engineer

### Role Summary
Builds and maintains the infrastructure, CI/CD pipelines, and platform reliability of services.

### Responsibilities
- Maintain CI/CD, observability, and environment provisioning
- Support deployments and performance/scalability initiatives
- Implement infrastructure-as-code and runbook content

### Typical Interactions
- Works with Developers and Release Manager on pipeline and deployment changes
- Provides runbooks to Support and PMs for incident handling

---

## Security Champion

### Role Summary
Represents security best practices within the delivery team and coordinates with central security teams.

### Responsibilities
- Advise on threat modeling and secure design
- Triage and validate security findings
- Ensure required security scans/gates are included in the pipeline

### Typical Interactions
- Works with Developers, QA, and PdMs to mitigate security concerns
- Escalates critical security issues to Security on-call

---

## Data Analyst / Data Scientist (where applicable)

### Role Summary
Supports product discovery and post-release measurement by defining metrics, dashboards, and experiments.

### Responsibilities
- Define and instrument success metrics and events
- Build dashboards and run analyses for feature impact
- Support A/B testing and experiments

### Typical Interactions
- Collaborates with Product Managers on success metrics
- Shares findings with PMs and stakeholders to inform prioritization

---

## How to use these personas in our processes

- For new or updated roles, use the role definition template in docs/templates/role-definition-template.md to capture responsibilities, RACI, onboarding notes, and interactions.
- Use the release-readiness checklist to ensure role-level sign-offs before releases.
- Review personas during planning and kickoff to ensure owners are assigned for each deliverable.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
