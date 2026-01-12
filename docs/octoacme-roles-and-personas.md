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
The QA Lead oversees the testing strategy, quality metrics, and validation activities across the project. They ensure defects are identified early, tracked, and resolved before release.

### Responsibilities
- Define and maintain the overall test strategy and approach
- Coordinate all QA activities across the team
- Review and approve test plans and test cases
- Track quality metrics and defect trends
- Ensure comprehensive test coverage for all features
- Coordinate defect triage and follow-up with developers
- Advocate for quality throughout the development lifecycle

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and automation rates
- Reduce mean time to detect and resolve issues
- Enable confident, reliable releases

### Typical Communication
- Daily standups to report on testing status and blockers
- Weekly quality reviews with PM and Product Manager
- Test plan reviews with Developers and Product Manager
- Release readiness assessments
- Defect triage meetings

### Interactions with Other Roles
- **Developers**: Collaborates on test coverage, provides feedback on testability, and partners on defect resolution
- **Product Manager**: Validates acceptance criteria and ensures quality aligns with customer expectations
- **Project Manager**: Reports on testing progress, risks, and release readiness
- **DevOps Engineer**: Partners on test automation infrastructure and CI/CD quality gates

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-facing workflows, interfaces, and experiences that meet business objectives and usability standards. They balance user needs with technical constraints and business goals.

### Responsibilities
- Design wireframes, mockups, and interactive prototypes
- Conduct user research and usability testing
- Create and maintain design systems and style guides
- Gather and incorporate feedback from stakeholders and users
- Ensure accessibility and inclusive design practices
- Validate designs with real users before implementation

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support adoption
- Ensure design consistency across the product
- Drive user satisfaction and engagement

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Prototype walkthroughs with Developers
- User research findings presentations
- Design handoff sessions with development team

### Interactions with Other Roles
- **Product Manager**: Partners to understand requirements and translate them into user-centered designs
- **Developers**: Collaborates closely during implementation to ensure design fidelity and feasibility
- **QA Lead**: Provides design specifications for validation and usability testing
- **Business Analyst**: Works together to map user workflows and business processes
- **Customer Success Manager**: Incorporates user feedback to improve designs iteratively

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain release pipelines, infrastructure automation, and system reliability. They enable fast, safe, and repeatable deployments.

### Responsibilities
- Develop and maintain CI/CD pipelines and automation
- Manage infrastructure as code and environment provisioning
- Monitor system health, performance, and operational metrics
- Implement deployment strategies (blue-green, canary, rollback)
- Ensure security and compliance in the release process
- Support incident response and system troubleshooting

### Goals
- Enable frequent, reliable releases with minimal manual intervention
- Maintain high system availability and performance
- Reduce deployment risks and rollback time
- Improve observability and incident response

### Typical Communication
- Daily standups for deployment status and infrastructure updates
- Weekly sync with Developers and Project Manager on release planning
- Incident postmortems and runbook updates
- Infrastructure and tooling roadmap reviews

### Interactions with Other Roles
- **Developers**: Partners on build optimization, deployment automation, and troubleshooting
- **QA Lead**: Collaborates on test automation infrastructure and quality gates in CI/CD
- **Project Manager**: Coordinates release schedules and communicates deployment risks
- **Technical Writer**: Works together on deployment documentation and runbooks

---

## Technical Writer

### Role Summary
Technical Writers ensure clarity, completeness, and accessibility of all project documentation. They make complex technical information understandable for diverse audiences.

### Responsibilities
- Author and maintain internal and user-facing documentation
- Create process guides, API docs, and release notes
- Ensure documentation accuracy and consistency
- Manage documentation lifecycle and versioning
- Collaborate with SMEs to gather technical details
- Implement documentation standards and style guides

### Goals
- Provide clear, accurate documentation that reduces support burden
- Enable self-service for users and team members
- Maintain comprehensive knowledge base
- Support smooth onboarding and knowledge transfer

### Typical Communication
- Weekly syncs with Product Manager and Developers for content updates
- Documentation reviews with stakeholders
- Release notes coordination with DevOps and Project Manager
- User feedback sessions to improve documentation quality

### Interactions with Other Roles
- **All Roles**: Collaborates with everyone to gather information and keep documentation current
- **Developers**: Works closely to document APIs, architecture, and technical processes
- **DevOps Engineer**: Partners on deployment guides, runbooks, and operational documentation
- **Customer Success Manager**: Incorporates user feedback and common support issues into docs
- **Project Manager**: Ensures process documentation stays aligned with current practices

---

## Business Analyst

### Role Summary
Business Analysts translate business needs into clear requirements and actionable tasks. They bridge the gap between stakeholders, product vision, and technical implementation.

### Responsibilities
- Gather and document detailed business requirements
- Define acceptance criteria and success metrics
- Map business workflows and process flows
- Analyze data to inform decision-making
- Facilitate requirements workshops and stakeholder interviews
- Validate that solutions meet business objectives

### Goals
- Ensure shared understanding of requirements across all teams
- Reduce rework by clarifying expectations upfront
- Enable data-driven prioritization and trade-off decisions
- Support smooth handoffs from business to technical teams

### Typical Communication
- Requirements workshops with stakeholders
- Backlog refinement sessions with Product Manager and Developers
- Data analysis presentations
- Process mapping reviews

### Interactions with Other Roles
- **Product Manager**: Partners closely to refine product vision into detailed requirements
- **Developers**: Clarifies requirements, answers questions, and validates implementation
- **QA Lead**: Collaborates on acceptance criteria and test scenarios
- **Project Manager**: Supports planning by providing detailed estimates and dependency analysis
- **UX/UI Designer**: Works together to ensure business processes align with user workflows

---

## Customer Success Manager

### Role Summary
Customer Success Managers advocate for customer needs and ensure solutions deliver ongoing value after release. They are the voice of the customer throughout the product lifecycle.

### Responsibilities
- Track and analyze post-deployment customer feedback
- Guide users through adoption and onboarding
- Identify and escalate customer pain points
- Champion continuous improvement based on customer insights
- Monitor customer health metrics and satisfaction scores
- Coordinate customer training and support resources

### Goals
- Maximize customer satisfaction and retention
- Drive product adoption and feature usage
- Reduce customer churn and support escalations
- Provide actionable customer insights to product teams

### Typical Communication
- Weekly customer health reviews
- Monthly feedback summaries to Product Manager
- Customer advisory board meetings
- Support escalation coordination

### Interactions with Other Roles
- **Product Manager**: Provides customer insights to inform roadmap and prioritization decisions
- **Technical Writer**: Partners on user documentation, help articles, and training materials
- **QA Lead**: Shares real-world user scenarios for testing and validation
- **UX/UI Designer**: Provides user feedback to improve design and usability
- **Business Analyst**: Collaborates on understanding customer workflows and requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

