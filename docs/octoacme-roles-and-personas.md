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

## Project Sponsor

### Role Summary
Project Sponsors provide strategic direction, secure necessary resources, and ensure project alignment with organizational goals. They are accountable for overall project success and serve as executive champions.

### Responsibilities
- Define and approve project vision and strategic objectives
- Secure budget, resources, and organizational commitment
- Approve major milestones, scope changes, and key decisions
- Remove organizational barriers and escalate critical issues
- Ensure alignment with business strategy and portfolio priorities

### Goals
- Maximize return on investment and business value
- Ensure project aligns with strategic initiatives
- Provide executive-level support and advocacy

### Typical Communication
- Monthly steering committee meetings
- Milestone reviews and go/no-go decisions
- Escalation resolution and strategic guidance
- Executive status reports

### Key Interactions
- **Project Manager**: Receives status updates, resolves escalations, approves major changes
- **Product Manager**: Aligns on strategic direction and business outcomes
- **Stakeholders**: Represents organizational priorities and champions project value

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholder needs and project goals. They elicit, analyze, and document requirements, ensuring deliverables meet business objectives.

### Responsibilities
- Elicit and document business requirements and use cases
- Translate business needs into actionable user stories and acceptance criteria
- Facilitate requirements workshops and stakeholder interviews
- Validate deliverables against business requirements
- Support change impact analysis and scope management

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize rework through upfront clarity
- Maintain traceability between business needs and solutions

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story refinement sessions
- Business requirement documents and process flows
- Acceptance criteria and validation sessions

### Key Interactions
- **Stakeholders**: Gathers requirements and validates business needs
- **Project Manager**: Collaborates on scope definition and change management
- **Product Manager**: Aligns requirements with product vision
- **Developers**: Clarifies requirements and acceptance criteria
- **QA Lead**: Defines acceptance criteria for test planning

---

## QA Lead

### Role Summary
QA Leads oversee testing strategy, quality gates, and release readiness. They ensure deliverables meet quality standards and coordinate testing activities across the team.

### Responsibilities
- Design and implement comprehensive testing strategies
- Define quality gates and acceptance criteria
- Coordinate test planning, execution, and defect management
- Ensure test automation coverage for critical flows
- Validate release readiness and sign off on deployments

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and automation
- Ensure consistent quality standards across releases

### Typical Communication
- Test plan reviews and quality gate definitions
- Daily defect triage and testing status updates
- Release readiness reviews and sign-off meetings
- Quality metrics and test coverage reports

### Key Interactions
- **Developers**: Collaborates on testability, reviews test coverage, triages defects
- **Project Manager**: Reports testing status, identifies quality risks, validates timelines
- **Product Manager**: Validates acceptance criteria and user scenarios
- **Business Analyst**: Ensures test cases align with requirements
- **Stakeholders**: Provides quality confidence for releases

---

## Communications Specialist

### Role Summary
Communications Specialists develop and execute project communication strategies, manage stakeholder messaging, and ensure consistent internal and external communications.

### Responsibilities
- Develop project communication plans and stakeholder maps
- Create and distribute status updates, newsletters, and announcements
- Manage change communication and stakeholder engagement
- Coordinate messaging between project team and business units
- Maintain communication channels and documentation repositories

### Goals
- Ensure stakeholders are informed and engaged
- Maintain consistent messaging across all channels
- Build awareness and support for project initiatives

### Typical Communication
- Weekly stakeholder newsletters and status updates
- Launch announcements and change communications
- Communication plan templates and stakeholder matrices
- Town halls and all-hands presentations

### Key Interactions
- **Project Manager**: Collaborates on status reporting and stakeholder updates
- **Project Sponsor**: Aligns executive messaging and strategic communications
- **Product Manager**: Translates product value into stakeholder messages
- **Stakeholders**: Delivers targeted communications based on stakeholder needs
- **All team members**: Gathers input for status updates and announcements

---

## Risk Manager

### Role Summary
Risk Managers focus on proactive risk identification, assessment, and mitigation coordination. They maintain risk visibility and ensure appropriate risk response strategies are in place.

### Responsibilities
- Identify and assess project risks and dependencies
- Maintain and update the risk register
- Coordinate risk mitigation planning and tracking
- Facilitate risk reviews and escalate critical risks
- Monitor risk indicators and trigger contingency plans

### Goals
- Minimize project impact from identified risks
- Maintain proactive risk management culture
- Ensure visibility of risks to decision-makers

### Typical Communication
- Weekly risk reviews and register updates
- Risk assessment workshops and mitigation planning
- Escalation reports for high-priority risks
- Risk dashboards and trend analysis

### Key Interactions
- **Project Manager**: Collaborates on risk identification and mitigation planning
- **Project Sponsor**: Escalates critical risks requiring executive decisions
- **QA Lead**: Coordinates on quality and technical risks
- **Developers**: Identifies technical risks and feasibility concerns
- **Business Analyst**: Assesses requirements and scope-related risks
- **All team members**: Facilitates risk identification across all project areas

---

## Collaboration and Handoff Paths

### Cross-Role Collaboration Model
Clear handoffs and collaboration patterns ensure smooth project execution:

**Initiation Phase:**
- **Project Sponsor** → **Project Manager**: Authorizes project, provides strategic direction
- **Project Manager** → **Business Analyst**: Initiates requirements gathering
- **Business Analyst** → **Stakeholders**: Conducts requirements workshops
- **Risk Manager** → **Project Manager**: Delivers initial risk assessment

**Planning Phase:**
- **Business Analyst** → **Product Manager**: Validates business requirements against product vision
- **Product Manager** → **Developers**: Prioritizes backlog and defines acceptance criteria
- **QA Lead** → **Developers**: Reviews testability and defines quality gates
- **Communications Specialist** → **Project Manager**: Develops communication plan
- **Risk Manager** → **All roles**: Facilitates risk identification workshop

**Execution Phase:**
- **Developers** → **QA Lead**: Submits code for testing
- **QA Lead** → **Developers**: Reports defects and quality issues
- **Business Analyst** → **Developers**: Clarifies requirements and acceptance criteria
- **Project Manager** → **Communications Specialist**: Provides status for stakeholder updates
- **Risk Manager** → **Project Manager**: Reports emerging risks and mitigation status
- **All roles** → **Project Manager**: Daily standup updates and blocker escalation

**Release Phase:**
- **QA Lead** → **Project Manager**: Provides release readiness sign-off
- **Project Manager** → **Project Sponsor**: Requests deployment approval
- **Communications Specialist** → **Stakeholders**: Distributes launch communications
- **Developers** → **QA Lead**: Supports production validation

**Retrospective Phase:**
- **All roles** → **Project Manager**: Contributes lessons learned
- **Project Manager** → **Risk Manager**: Shares risk lessons for future projects
- **Communications Specialist** → **Stakeholders**: Communicates project outcomes

### Escalation Paths
- **Team-level issues** → **Project Manager**
- **Significant risks/blockers** → **Risk Manager** → **Project Sponsor**
- **Requirements conflicts** → **Business Analyst** → **Product Manager** → **Project Sponsor**
- **Quality concerns** → **QA Lead** → **Project Manager** → **Project Sponsor**
- **Communication issues** → **Communications Specialist** → **Project Manager**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

