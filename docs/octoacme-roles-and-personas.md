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

## QA / Quality Assurance

### Role Summary
QA engineers validate that features meet acceptance criteria, quality standards, and user expectations. They design test strategies, execute test plans, and work closely with developers to ensure defects are identified and resolved before release.

### Responsibilities
- Design and implement test automation strategies
- Develop and execute test plans and test cases
- Validate acceptance criteria for user stories and features
- Perform manual exploratory testing when needed
- Report, track, and verify bug fixes
- Collaborate with developers on testability and test automation

### Goals
- Ensure high product quality and user satisfaction
- Minimize production defects and regressions
- Reduce time-to-market through efficient testing

### Typical Communication
- Daily standups to report testing progress and blockers
- Bug reports and test case documentation
- Test summary reports before releases
- Collaboration with developers on test strategies

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with vested interest in the project outcome. They may include executive sponsors, department leads, customers, or partner teams who provide input, funding, or approvals.

### Responsibilities
- Provide business requirements and constraints
- Review and approve key decisions and deliverables
- Allocate resources and budget when needed
- Give feedback on demos and prototypes
- Champion the project within their organization

### Goals
- Ensure project delivers expected business value
- Protect organizational interests and priorities
- Stay informed on progress and risks

### Typical Communication
- Monthly status updates and milestone reviews
- Decision points and approval gates
- Escalation path for critical issues

---

## UX Designer

### Role Summary
UX Designers craft user experiences that are intuitive, accessible, and delightful. They conduct user research, create wireframes and prototypes, and collaborate with product managers and developers to ensure solutions meet user needs while aligning with business goals.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define information architecture and user flows
- Establish design systems and UI patterns
- Validate designs with users and iterate based on feedback
- Collaborate with developers on implementation feasibility

### Goals
- Maximize user satisfaction and engagement
- Reduce user friction and support burden
- Ensure accessibility and inclusive design
- Maintain design consistency across the product

### Typical Communication
- Design review sessions with product and engineering teams
- User research findings and personas
- Design handoff documentation and specifications
- Participation in sprint planning and refinement

### Interactions with Other Roles
- **Product Managers**: Collaborate on feature requirements and user stories; validate that designs align with business goals and success metrics
- **Developers**: Provide design specifications and assets; review implementations to ensure design fidelity; collaborate on technical constraints
- **QA**: Define expected user behaviors and acceptance criteria from a UX perspective; participate in usability validation
- **Project Managers**: Communicate design timeline and dependencies; flag risks related to user experience scope
- **Business Analysts**: Align on user needs and business process requirements; validate that designs support business workflows
- **Stakeholders**: Present design concepts for feedback; demonstrate prototypes to gather early input

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers design, build, and maintain the infrastructure and automation required for continuous integration, delivery, and deployment. They ensure code moves smoothly from development to production with reliability, speed, and observability.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment infrastructure and environments (dev, staging, production)
- Monitor system performance, availability, and deployment health
- Implement infrastructure as code and configuration management
- Support incident response and troubleshooting
- Establish deployment best practices and standards

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and downtime
- Improve system observability and reliability
- Reduce manual toil through automation

### Typical Communication
- Deployment status updates and release windows
- Infrastructure and pipeline documentation
- Incident response and post-mortems
- Collaboration on deployment strategies and rollback plans

### Interactions with Other Roles
- **Developers**: Provide CI/CD tooling and pipeline support; collaborate on build and deployment requirements; assist with environment troubleshooting
- **QA**: Ensure test environments are properly configured; support automated test integration in pipelines
- **Project Managers**: Communicate deployment schedules and risks; report on pipeline health and release readiness
- **Product Managers**: Align on release timing and feature flags; provide visibility into deployment capabilities
- **Support Lead**: Coordinate on production changes; provide monitoring and logging access for support cases
- **Security/Compliance roles**: Implement security scanning and compliance checks in pipelines

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, analyze, and document business requirements, define processes, and ensure solutions deliver measurable business value.

### Responsibilities
- Gather and document business requirements
- Analyze existing business processes and identify improvement opportunities
- Create functional specifications and user stories
- Facilitate requirements workshops and stakeholder meetings
- Validate that delivered solutions meet business needs
- Track and report on business metrics and KPIs

### Goals
- Ensure clear understanding of business needs across teams
- Maximize business value and ROI from technical solutions
- Reduce miscommunication and rework
- Support data-driven decision making

### Typical Communication
- Requirements documentation and user stories
- Business process diagrams and workflows
- Stakeholder meetings and workshops
- Success metrics and business impact reports

### Interactions with Other Roles
- **Product Managers**: Collaborate on roadmap prioritization and business case development; align on success metrics and value propositions
- **Project Managers**: Provide requirements clarity and scope definition; help estimate business impact of changes
- **Developers**: Translate business requirements into technical specifications; clarify acceptance criteria and business logic
- **UX Designers**: Share user research and business context; ensure designs support business workflows and objectives
- **QA**: Define business acceptance criteria and validation scenarios; participate in acceptance testing
- **Stakeholders**: Act as liaison between business and technical teams; gather requirements and communicate progress
- **Support Lead**: Analyze support trends to identify business process improvements; help define support escalation criteria

---

## Support Lead

### Role Summary
Support Leads manage the post-deployment customer experience, ensuring users get timely help and issues are resolved efficiently. They coordinate support operations, analyze trends, and feed insights back into product development to improve usability and reduce support burden.

### Responsibilities
- Manage support ticket triage, routing, and resolution
- Define and maintain support documentation and knowledge bases
- Train support team members on new features and changes
- Escalate critical issues to engineering when needed
- Analyze support metrics and identify recurring issues
- Collaborate with product and engineering to improve supportability

### Goals
- Maximize customer satisfaction and rapid issue resolution
- Minimize support escalations and repeat issues
- Build effective self-service resources
- Improve product quality through feedback loops

### Typical Communication
- Support ticket updates and escalations
- Knowledge base articles and runbooks
- Support metrics dashboards and trend reports
- Feedback to product and engineering teams

### Interactions with Other Roles
- **Developers**: Escalate complex technical issues; provide feedback on supportability and common user errors; request bug fixes and improvements
- **Product Managers**: Share customer feedback and pain points; influence roadmap with support-driven insights; provide input on feature usability
- **QA**: Report issues found in production; help validate fixes; provide real-world usage scenarios for testing
- **Project Managers**: Communicate support readiness for releases; flag support risks and training needs
- **DevOps/Release Engineers**: Request access to logs and monitoring for troubleshooting; coordinate on deployment timing and communication
- **UX Designers**: Share usability issues and confusion points from support tickets; provide user perspective for design improvements
- **Business Analysts**: Provide data on support trends and business impact; collaborate on process improvements to reduce support volume
- **Stakeholders**: Report on support health and customer satisfaction; escalate critical customer issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

