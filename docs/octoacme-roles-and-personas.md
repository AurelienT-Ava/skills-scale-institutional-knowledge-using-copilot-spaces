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
Engineering Leads define and guide technical implementation for project delivery. They align architecture and engineering practices with product goals while helping teams execute predictably.

### Primary Responsibilities
- Set technical direction and implementation approach for features and platform changes
- Break down complex work and guide estimation with developers and project managers
- Identify technical risks, dependencies, and required trade-offs early
- Maintain engineering quality standards across design, code review, and delivery

### Interactions with Existing Roles
- Partner with Product Managers on scope trade-offs, feasibility, and sequencing
- Work with Project Managers on technical dependencies, milestones, and risk mitigation plans
- Support Developers through architecture guidance, technical reviews, and unblocker decisions

### Typical Communication Cadence / Touchpoints
- Daily engineering syncs and standups
- Sprint planning and backlog refinement sessions
- Technical design reviews and architecture decision record updates

### Common Decisions Influenced or Owned
- Service and component design approaches
- Buy-vs-build and implementation pattern choices
- Technical debt prioritization and remediation timing

---

## QA Lead / Test Owner

### Role Summary
QA Leads define the quality strategy for project increments and ensure that release candidates meet agreed standards before production rollout.

### Primary Responsibilities
- Define test strategy and quality gates for features, integrations, and regressions
- Ensure acceptance criteria are testable and fully covered by validation plans
- Coordinate test execution, defect triage, and release-readiness quality reporting
- Track quality trends and recommend process improvements

### Interactions with Existing Roles
- Collaborate with Developers on test automation coverage and defect resolution
- Partner with Product Managers to validate acceptance outcomes and user scenarios
- Coordinate with Project Managers to align testing timelines and risk status

### Typical Communication Cadence / Touchpoints
- Daily defect triage during active testing windows
- Sprint-level test planning and readiness checkpoints
- Go/no-go quality updates before release decisions

### Common Decisions Influenced or Owned
- Entry/exit criteria for test phases
- Severity and priority classification for defects
- Recommendation to proceed, hold, or rollback based on quality risk

---

## Release Manager

### Role Summary
Release Managers orchestrate release planning and execution across teams to deliver changes safely, predictably, and with clear stakeholder communication.

### Primary Responsibilities
- Build and maintain release plans, checklists, and deployment timelines
- Coordinate readiness across engineering, QA, product, and operations
- Ensure rollback plans, change records, and communication plans are complete
- Track release outcomes and lead post-release follow-up

### Interactions with Existing Roles
- Work with Project Managers on schedule alignment and dependency tracking
- Coordinate with Engineering Leads and Developers on deploy sequencing and risk controls
- Align with QA Leads on quality sign-off and unresolved risk visibility
- Partner with Support/Operations on customer-impact communications and monitoring

### Typical Communication Cadence / Touchpoints
- Weekly release readiness reviews
- Pre-release go/no-go checkpoints
- Real-time communication during deployment windows and post-release summaries

### Common Decisions Influenced or Owned
- Release timing and phased rollout strategy
- Go/no-go decisions based on cross-functional readiness
- Rollback activation when deployment risk or incidents exceed thresholds

---

## UX / Design Lead

### Role Summary
UX/Design Leads ensure solutions are usable, consistent, and aligned with customer needs across planning, implementation, and release.

### Primary Responsibilities
- Define interaction patterns, user flows, and design standards for project scope
- Translate product requirements into validated design solutions
- Run or coordinate usability reviews and incorporate findings into iteration plans
- Maintain consistency with design systems and accessibility expectations

### Interactions with Existing Roles
- Partner with Product Managers to clarify user problems and success outcomes
- Collaborate with Developers and Engineering Leads on implementation feasibility and fidelity
- Work with QA Leads to validate UX quality and accessibility acceptance criteria

### Typical Communication Cadence / Touchpoints
- Discovery and refinement sessions during planning
- Design handoff checkpoints before implementation
- Feedback loops during sprint reviews and user testing cycles

### Common Decisions Influenced or Owned
- UX patterns and interaction model choices
- Prioritization of usability and accessibility improvements
- Acceptance of design fidelity before release

---

## Security / Compliance Reviewer

### Role Summary
Security/Compliance Reviewers assess changes for security, privacy, and regulatory risk and ensure required controls are met before release.

### Primary Responsibilities
- Review solution designs and changes for security and compliance impacts
- Define required controls, evidence, and approval checkpoints for sensitive work
- Identify vulnerabilities or control gaps and drive remediation requirements
- Support audit readiness through clear risk and control documentation

### Interactions with Existing Roles
- Collaborate with Engineering Leads and Developers on secure design and remediation
- Coordinate with Project Managers on compliance milestones and risk tracking
- Partner with Release Managers on security sign-off criteria for deployment

### Typical Communication Cadence / Touchpoints
- Early architecture/security review during planning
- Control and evidence checks before release
- Incident follow-up and periodic compliance reviews

### Common Decisions Influenced or Owned
- Required security controls for features and integrations
- Risk acceptance or escalation when gaps remain
- Compliance sign-off recommendations for release approval

---

## Support / Operations Representative

### Role Summary
Support/Operations Representatives bring production and customer-impact perspective into planning, release readiness, and post-release operations.

### Primary Responsibilities
- Provide operational readiness input for monitoring, runbooks, and alerting
- Represent customer support trends and incident learnings in planning decisions
- Coordinate launch communications, support enablement, and escalation paths
- Track post-release health indicators and operational follow-through

### Interactions with Existing Roles
- Work with Project Managers on operational dependencies and service readiness
- Partner with Release Managers on release communications and hypercare coverage
- Collaborate with Product Managers and Developers on issue prioritization from production feedback

### Typical Communication Cadence / Touchpoints
- Planning touchpoints for operational readiness and launch support
- Active participation during release windows and hypercare periods
- Regular incident/problem review and customer feedback loops

### Common Decisions Influenced or Owned
- Operational readiness status and support launch criteria
- Escalation paths and incident communication actions
- Prioritization recommendations based on customer-impact trends

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
