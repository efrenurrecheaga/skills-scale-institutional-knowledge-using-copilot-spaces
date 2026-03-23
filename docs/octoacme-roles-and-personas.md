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

## Release Manager

### Role Summary
The Release Manager coordinates release planning and deployment schedules, owns the release gate process, and ensures post-release quality checkpoints are completed and documented.

### Responsibilities
- Maintain the release calendar and communicate dates across teams
- Own the release checklist and go/no-go decision process
- Coordinate with QA Lead, Project Manager, and DevOps to validate readiness
- Track post-release metrics and own rollback decisions when necessary
- Archive release notes and deployment records

### Key Deliverables / Decision Rights
- Release plan and deployment schedule
- Go/no-go sign-off at each release gate
- Post-release summary and incident retrospective (if applicable)

### Collaboration Touchpoints
- **Project Manager:** aligns release dates with project milestones and stakeholder expectations
- **QA Lead:** confirms test coverage and open defect status before gate
- **DevOps / Platform:** schedules and executes deployment steps
- **Support Coordinator:** hands off release notes and known-issues list before go-live

### Lifecycle Fit
Active from **Planning** through **Release & Close**; peak activity during the Release phase.

### Typical Communication
- Release readiness meetings and go/no-go calls
- Release notes and deployment runbooks
- Post-release incident or rollback reports

---

## QA Lead

### Role Summary
The QA Lead owns final testing coverage, validates acceptance criteria, and drives test-automation strategy across the project lifecycle.

### Responsibilities
- Define and maintain the test strategy, test plan, and coverage goals
- Validate acceptance criteria are testable and traceable to requirements
- Own defect triage and resolution tracking
- Champion test automation and ensure CI pipelines include meaningful coverage
- Provide final quality sign-off before each release gate

### Key Deliverables / Decision Rights
- Test plan and traceability matrix
- Defect register and resolution status
- Quality sign-off report for release gate
- Test-automation coverage metrics

### Collaboration Touchpoints
- **Developers:** pair on testability and review test coverage during code reviews
- **Business Analyst:** validates that test cases map to business requirements
- **Release Manager:** provides defect status and quality sign-off for go/no-go
- **Project Manager:** surfaces quality risks and schedule impacts early

### Lifecycle Fit
Engaged from **Planning** (test strategy) through **Release** (final sign-off); feeds retrospective data into **Close & Retrospective**.

### Typical Communication
- Sprint/iteration test reports
- Defect triage meetings with Developers
- Go/no-go quality summary for Release Manager

---

## Business Analyst

### Role Summary
The Business Analyst defines and clarifies business requirements, ensures traceability from business need to delivered feature, and resolves ambiguity before it reaches development.

### Responsibilities
- Elicit, document, and validate business requirements with stakeholders
- Maintain requirements traceability throughout the project lifecycle
- Partner with the Product Manager to refine the backlog and acceptance criteria
- Identify and resolve scope ambiguity early to reduce rework
- Produce process maps or workflow diagrams when complexity warrants it

### Key Deliverables / Decision Rights
- Requirements document or user-story elaborations
- Requirements traceability matrix
- Scope decision log (what is in/out and why)
- Signed-off acceptance criteria per feature

### Collaboration Touchpoints
- **Product Manager:** co-owns backlog refinement and prioritization rationale
- **Project Manager:** flags scope changes that affect timeline or resources
- **QA Lead:** ensures acceptance criteria are testable and complete
- **Developers:** answers requirements questions and clarifies edge cases during sprints

### Lifecycle Fit
Primarily active during **Initiation** and **Planning**; continues into **Execution** to handle clarifications; provides traceability evidence at **Release**.

### Typical Communication
- Requirements review sessions and backlog refinement meetings
- Written requirement clarifications in issue/ticket comments
- Scope change requests with impact assessment

---

## Support Coordinator

### Role Summary
The Support Coordinator bridges the project/product team and customer support. They prepare support documentation, training materials, and incident-response plans so that go-live is smooth and post-launch issues are handled efficiently.

### Responsibilities
- Produce user-facing documentation, FAQs, and support runbooks ahead of each release
- Coordinate internal training for support and success teams
- Define and communicate incident escalation paths for new features
- Collect early post-launch feedback from support channels and surface trends to the team
- Participate in release readiness reviews to confirm support-readiness criteria

### Key Deliverables / Decision Rights
- Support runbook and FAQ for each release
- Training materials and recorded demos for support teams
- Incident escalation matrix
- Post-launch feedback report (first 30 days)

### Collaboration Touchpoints
- **Release Manager:** receives release notes and known-issues list; confirms support readiness at gate
- **Product Manager:** aligns on messaging and known limitations
- **Project Manager:** ensures support-readiness tasks appear in the release plan
- **Business Analyst:** obtains detailed feature documentation for support content creation

### Lifecycle Fit
Joins the project during **Planning** (capacity and content planning); most active at **Release** (readiness gate and launch); owns post-launch feedback loop through **Close & Retrospective**.

### Typical Communication
- Release readiness review (support-readiness section)
- Handoff meeting with Release Manager before go-live
- Weekly post-launch support-volume report during stabilization period

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-raci-matrix.md`](octoacme-raci-matrix.md) for a cross-role accountability summary.
- See [`octoacme-release-readiness-checklist.md`](octoacme-release-readiness-checklist.md) for the handoff and release gate checklist.

