# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Use it alongside the planning, execution, release, risk, and retrospective guides to clarify ownership, handoffs, and approvals across the project lifecycle.

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

## QA / Test Engineers

### Role Summary
QA / Test Engineers help the team deliver changes that are ready for release. They turn acceptance criteria into a practical test approach, validate feature quality, and surface risks early enough for the team to respond.

### Responsibilities
- Define the test approach during planning and refinement
- Validate acceptance criteria, regressions, and critical user flows
- Document quality risks, defects, and release readiness concerns
- Coordinate smoke testing for staging and production releases
- Contribute quality learnings to retrospectives and process improvements

### Goals
- Prevent avoidable defects from reaching customers
- Make release readiness visible before deployment
- Improve confidence in acceptance, regression, and smoke test coverage

### Typical Communication
- Test plans, bug reports, and release readiness updates
- Daily collaboration in standups, ticket comments, and PR follow-up
- Quality risk summaries for milestone reviews and go/no-go conversations

### How the role collaborates with existing roles
- With Developers: clarify edge cases early, verify fixes quickly, and align on automation opportunities during execution.
- With Product Managers: confirm acceptance readiness, expected behavior, and customer-impacting trade-offs before release.
- With Project Managers: flag test dependencies, quality risks, and entry/exit criteria in planning, tracking, and risk reviews.

---

## Engineering Managers / Engineering Leads

### Role Summary
Engineering Managers / Engineering Leads provide technical delivery leadership. They align engineering capacity with commitments, guide major technical decisions, and help the team stay unblocked through planning, execution, and release.

### Responsibilities
- Support staffing, sequencing, and technical feasibility during planning
- Guide architecture and implementation trade-offs
- Unblock engineering execution and escalate delivery risks when needed
- Reinforce quality, maintainability, and operational readiness expectations
- Support retrospective follow-through on engineering improvement actions

### Goals
- Keep delivery commitments realistic and sustainable
- Maintain strong engineering quality while shipping iteratively
- Reduce delays caused by unclear technical ownership or resourcing gaps

### Typical Communication
- Planning and estimation discussions with PMs and Product Managers
- Technical decision records, design reviews, and escalation threads
- Delivery risk and capacity updates for milestone planning

### How the role collaborates with existing roles
- With Developers: provide direction on design, sequencing, and technical blockers during execution.
- With Product Managers: align product scope with technical trade-offs, capacity, and release constraints.
- With Project Managers: manage schedule risk, dependencies, and escalation paths when engineering delivery is at risk.

---

## Designers / UX Designers

### Role Summary
Designers / UX Designers shape how solutions work for customers. They translate product goals into flows, wireframes, and experience guidance that help the team make usable decisions early and validate them during delivery.

### Responsibilities
- Define user journeys, flows, and interface expectations
- Contribute design inputs to planning, backlog refinement, and acceptance criteria
- Validate usability risks and edge cases before implementation starts
- Partner with QA and Developers to confirm the delivered experience matches intent
- Capture user-experience lessons for future iterations and retrospectives

### Goals
- Improve usability and reduce rework caused by unclear experience requirements
- Help the team make faster decisions with shared design context
- Ensure customer workflows stay coherent across releases

### Typical Communication
- Design reviews, mockups, prototypes, and annotated specs
- Backlog refinement discussions and async feedback on implementation details
- Demo feedback and post-release usability observations

### How the role collaborates with existing roles
- With Developers: align on implementation feasibility, UI edge cases, and design intent during execution.
- With Product Managers: refine problem framing, user outcomes, and acceptance inputs during planning.
- With Project Managers: make design dependencies, review milestones, and decision points visible in the delivery plan.

---

## Support / Customer Success

### Role Summary
Support / Customer Success brings customer context into delivery and helps teams prepare for change. They surface recurring pain points, support release communications, and close the loop with post-release feedback.

### Responsibilities
- Share customer issues, recurring questions, and adoption risks during initiation and planning
- Prepare enablement materials, FAQs, and escalation guidance for releases
- Coordinate customer-facing communications with PM and product leads
- Monitor incoming feedback after release and route themes back to the team
- Contribute customer-impact insights to retrospectives and follow-up actions

### Goals
- Reduce surprise for customer-facing teams during releases
- Improve release readiness and customer adoption
- Make post-release feedback actionable for roadmap and process improvements

### Typical Communication
- Customer trend summaries, launch readiness notes, and support briefings
- Escalation updates during incidents or high-risk releases
- Post-release feedback loops with Product, PM, and engineering

### How the role collaborates with existing roles
- With Developers: share high-friction customer issues and help validate whether fixes address real support pain points.
- With Product Managers: provide customer insights that influence prioritization, readiness messaging, and post-release follow-up.
- With Project Managers: coordinate launch communications, support readiness checkpoints, and escalation handling for customer-impacting issues.

---

## Stakeholders / Executive Sponsors

### Role Summary
Stakeholders / Executive Sponsors provide strategic direction, funding context, and escalation support. They help teams confirm priorities, make key decisions, and keep work aligned with business outcomes.

### Responsibilities
- Confirm business goals, priority, and success measures during initiation
- Approve major scope, timeline, or investment decisions when needed
- Resolve escalations that exceed team-level authority
- Review milestone progress and release impact at the right level of detail
- Reinforce accountability for follow-through on major risks and improvement actions

### Goals
- Ensure delivery stays aligned with business priorities
- Speed up critical decisions when trade-offs or escalations arise
- Increase confidence that releases deliver intended business outcomes

### Typical Communication
- Kickoff reviews, milestone updates, and decision meetings
- Escalation summaries and approval requests
- Outcome reviews tied to launch goals, risks, and next steps

### How the role collaborates with existing roles
- With Product Managers: align on business priorities, success metrics, and scope trade-offs across the lifecycle.
- With Project Managers: review delivery health, approve major changes, and support escalation paths when risks threaten milestones.
- With Developers: stay informed through demos and milestone updates rather than directing day-to-day implementation work.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
