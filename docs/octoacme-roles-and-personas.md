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

## QA / Testing

### Role Summary
QA engineers validate that features meet acceptance criteria and quality standards before release. They design test plans, execute manual and automated tests, and surface issues early to reduce rework.

### Responsibilities
- Design and execute test plans aligned to acceptance criteria
- Build and maintain automated test suites
- Log, triage, and track defects to resolution
- Coordinate with Developers and Product Managers on edge cases and coverage
- Support release readiness by signing off on pre-release checklists

### Goals
- Prevent defects from reaching production
- Maintain fast feedback loops for the delivery team
- Improve test coverage and automation rate over time

### Typical Communication
- Sprint reviews and bug triage meetings
- Test reports and release sign-off notes
- Collaboration with Developers on test feasibility

---

## UX Designer

### Role Summary
UX Designers create user-centered interfaces and experiences that meet product requirements. They conduct usability research, produce wireframes and prototypes, and ensure that designs are both intuitive and technically feasible.

### Responsibilities
- Design user interfaces and interaction flows that satisfy product requirements
- Facilitate usability testing and synthesize user feedback into actionable improvements
- Produce wireframes, prototypes, and design specifications for Developers
- Collaborate with Product Managers to refine acceptance criteria from a user perspective
- Work with QA to validate usability and accessibility during testing

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce usability-related defects and post-release design rework
- Improve onboarding and task-completion rates for end users

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Usability test reports shared with the broader team
- Handoff documentation (specs, assets) in shared design tools

### Handoffs & Cross-functional Touchpoints
- **→ Product Manager**: receive requirements and prioritized user stories; provide UX research findings that inform backlog decisions
- **→ Developers**: hand off design specs and assets; validate implementation against designs
- **→ QA**: share acceptance criteria for UI/UX scenarios; collaborate on usability and accessibility test cases
- **→ Customer Support Specialist**: receive post-release user feedback to inform iterative improvements

---

## Data Analyst

### Role Summary
Data Analysts provide data-driven insights to support planning, track product metrics, and enable evidence-based decision-making throughout the project lifecycle.

### Responsibilities
- Define, instrument, and monitor key product and delivery metrics
- Produce dashboards and reports for Project Managers and Product Managers
- Analyze trends and surface insights that guide prioritization and roadmap decisions
- Collaborate with Developers to ensure correct data collection and instrumentation
- Support post-release analysis to measure the impact of shipped features

### Goals
- Enable data-informed prioritization and outcome measurement
- Reduce decision-making latency by making key metrics visible and accessible
- Identify risks and opportunities early through trend analysis

### Typical Communication
- Weekly metric reviews with Project Managers and Product Managers
- Sprint retrospective contributions (quantitative insights)
- Ad-hoc analysis reports as requested

### Handoffs & Cross-functional Touchpoints
- **→ Product Manager**: provide metric definitions and outcome data to support roadmap decisions
- **→ Project Manager**: deliver regular status reports and progress dashboards
- **→ Developers**: specify data collection requirements and validate instrumentation accuracy
- **→ Security Lead**: flag anomalous data access patterns that may indicate security concerns

---

## DevOps Engineer

### Role Summary
DevOps Engineers enable rapid and reliable delivery by managing CI/CD pipelines, automating testing and deployment, and maintaining the infrastructure that the team depends on.

### Responsibilities
- Design, build, and maintain CI/CD pipelines for automated testing and deployment
- Manage infrastructure provisioning, configuration, and monitoring
- Automate repetitive operational tasks to reduce toil and human error
- Troubleshoot build, deployment, and infrastructure issues in collaboration with Developers
- Coordinate release windows and deployment activities with Project Managers

### Goals
- Maximize deployment frequency while minimizing change failure rate
- Reduce mean time to recovery (MTTR) for production incidents
- Ensure infrastructure reliability, scalability, and cost efficiency

### Typical Communication
- Release planning sessions with Project Managers and Developers
- Incident response coordination with on-call and Security Lead
- Pipeline and infrastructure runbooks kept up to date

### Handoffs & Cross-functional Touchpoints
- **→ Developers**: provide deployment guidance; merge deployment requirements into pipelines
- **→ QA**: integrate automated test suites into CI pipelines; share test environment management
- **→ Project Manager**: coordinate release windows and communicate deployment status
- **→ Security Lead**: implement security controls (scanning, secrets management) in pipelines
- **→ Customer Support Specialist**: provide deployment status during releases to aid support readiness

---

## Security Lead

### Role Summary
The Security Lead oversees security reviews and threat modeling, and ensures that the team follows organizational security policies and best practices across the entire delivery lifecycle.

### Responsibilities
- Conduct threat modeling and security reviews for new features and architectural changes
- Define and enforce security standards and compliance requirements
- Integrate security scanning and policy checks into CI/CD pipelines with DevOps Engineers
- Maintain the security risk register and escalate high-severity findings to Project Managers
- Advise Developers on secure coding practices and vulnerability remediation

### Goals
- Prevent security vulnerabilities from reaching production
- Reduce exposure window for identified risks through rapid remediation
- Maintain compliance with organizational and regulatory requirements

### Typical Communication
- Security review sessions at design and pre-release gates
- Findings reports shared with Developers and Project Managers
- Incident response participation for security-related events

### Handoffs & Cross-functional Touchpoints
- **→ Developers**: provide secure coding guidance; review implementation for vulnerabilities
- **→ Project Manager**: track security risks in the risk register; align on remediation timelines
- **→ Product Manager**: ensure policy and compliance requirements are reflected in acceptance criteria
- **→ DevOps Engineer**: collaborate on pipeline security controls (SAST, dependency scanning, secrets management)
- **→ Data Analyst**: review data handling practices for compliance with privacy and security policies

---

## Customer Support Specialist

### Role Summary
Customer Support Specialists serve as the frontline liaison between end users and the product team. They relay user feedback, support release readiness activities, and contribute post-release insights that drive continuous improvement.

### Responsibilities
- Provide frontline user support during and after releases, triaging and escalating issues
- Document recurring user issues and aggregate feedback for Product Managers and QA
- Contribute real-world scenarios and edge cases to QA test plans
- Communicate release changes and known issues to affected users
- Track and follow up on escalated tickets until resolution

### Goals
- Minimize user-facing disruption during and after releases
- Accelerate issue resolution by providing high-quality reproduction steps and context
- Feed user insights back into the product roadmap and quality improvements

### Typical Communication
- Pre-release briefings to understand upcoming changes and known issues
- Post-release incident updates shared with Project Managers
- Ongoing feedback summaries delivered to Product Managers and QA

### Handoffs & Cross-functional Touchpoints
- **→ Product Manager**: escalate user-reported tickets and aggregate feedback that informs backlog prioritization
- **→ Project Manager**: communicate incident status and support load during releases
- **→ QA**: provide reproduction steps and real-world scenarios to support defect investigation
- **→ UX Designer**: surface usability pain points identified through user interactions
- **→ DevOps Engineer**: relay production issue symptoms that may indicate deployment or infrastructure problems

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional handoffs between roles are documented in [docs/octoacme-handoff-checklist.md](octoacme-handoff-checklist.md).
- New team members should follow the onboarding flow in [docs/octoacme-onboarding-flow.md](octoacme-onboarding-flow.md).
- For stakeholder communication patterns, see [docs/octoacme-stakeholder-comms-template.md](octoacme-stakeholder-comms-template.md).

