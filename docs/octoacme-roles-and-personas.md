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

## QA / Testing Specialist

### Role Summary
QA/Testing Specialists validate quality and acceptance criteria for features and releases. They design test strategies, execute test plans, and ensure that deliverables meet standards before reaching production.

### Responsibilities
- Develop and maintain test plans and test cases
- Execute manual and automated testing (unit, integration, end-to-end)
- Validate acceptance criteria and Definition of Done
- Report and track defects with clear reproduction steps
- Collaborate on testability and quality improvements
- Participate in release verification and smoke testing

### Goals
- Ensure high-quality, reliable releases
- Catch defects early in the development cycle
- Improve test coverage and automation
- Reduce production incidents through thorough validation

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test results in issue trackers
- Test plan reviews and QA sign-offs before releases
- Collaboration with developers on testability

### Interactions with Other Roles
- **Developers**: Collaborate on test strategies, report defects, and verify fixes
- **Product Managers**: Validate acceptance criteria and user scenarios
- **Project Managers**: Report testing status, flag risks, and coordinate release readiness
- **Release Manager**: Coordinate smoke tests and post-release verification
- **Security Lead**: Execute security test cases and validate compliance

---

## Release Manager

### Role Summary
Release Managers coordinate the scheduling and execution of releases, ensuring smooth deployments to production. They oversee release processes, post-release verification, and communicate status to teams and stakeholders.

### Responsibilities
- Plan and schedule release windows and deployment activities
- Coordinate release readiness across teams (dev, QA, operations)
- Execute deployment procedures and monitor for issues
- Perform post-release verification and smoke tests
- Maintain release notes and deployment documentation
- Manage rollback procedures when necessary
- Communicate release status to stakeholders

### Goals
- Ensure reliable, low-risk deployments
- Minimize downtime and production incidents
- Maintain clear release documentation and runbooks
- Continuously improve release processes

### Typical Communication
- Release schedules and deployment notifications
- Release notes and change logs
- Post-deployment status updates
- Incident notifications during problematic releases

### Interactions with Other Roles
- **Developers**: Coordinate merge timelines, deployment procedures, and hotfix releases
- **QA/Testing Specialist**: Collaborate on pre-release validation and smoke testing
- **Project Managers**: Align release schedules with project milestones
- **Security Lead**: Ensure security scans pass before release
- **Support Specialist**: Communicate release changes and known issues
- **Stakeholders**: Provide release updates and manage expectations

---

## Security Lead

### Role Summary
Security Leads own security reviews, establish secure coding practices, respond to security incidents, and maintain compliance with security standards. They ensure that security is integrated throughout the development lifecycle.

### Responsibilities
- Conduct security reviews and threat modeling
- Define and enforce secure coding standards
- Manage security scanning tools and remediate findings
- Respond to security incidents and coordinate mitigation
- Maintain security documentation and compliance records
- Train teams on security best practices
- Review and approve high-risk changes

### Goals
- Minimize security vulnerabilities in production
- Ensure compliance with security policies and regulations
- Build security awareness across development teams
- Respond rapidly to security incidents with minimal impact

### Typical Communication
- Security review findings and remediation plans
- Security incident reports and post-mortems
- Security training and awareness updates
- Compliance status reports to leadership

### Interactions with Other Roles
- **Developers**: Review code for security issues, provide guidance on secure practices
- **QA/Testing Specialist**: Collaborate on security test cases and validation
- **Project Managers**: Report security risks and coordinate remediation timelines
- **Release Manager**: Approve releases based on security scan results
- **Product Managers**: Advise on security requirements and trade-offs
- **Stakeholders**: Report on security posture and compliance status

---

## Support Specialist

### Role Summary
Support Specialists manage incoming support requests, triage issues, and escalate to technical teams when needed. They maintain user-facing documentation and FAQs to reduce support burden and improve user experience.

### Responsibilities
- Respond to user inquiries and support tickets
- Triage and categorize issues (bug, feature request, user error)
- Escalate critical issues to development teams with context
- Maintain knowledge base, FAQs, and troubleshooting guides
- Track common issues and advocate for fixes or improvements
- Gather user feedback and pain points
- Communicate known issues and workarounds to users

### Goals
- Provide timely, helpful support to users
- Reduce mean time to resolution for user issues
- Identify and escalate systemic problems
- Improve self-service documentation to reduce ticket volume

### Typical Communication
- Support ticket responses and status updates
- Escalation reports to development teams
- Knowledge base articles and FAQ updates
- Trend reports on common issues

### Interactions with Other Roles
- **Developers**: Escalate bugs and provide reproduction steps
- **Project Managers**: Report on support trends and request prioritization
- **Product Managers**: Share user feedback and pain points
- **User Advocate**: Collaborate on user-centric improvements
- **Release Manager**: Stay informed about release changes and known issues
- **QA/Testing Specialist**: Provide real-world test cases from user reports

---

## User Advocate

### Role Summary
User Advocates collect and represent user feedback, helping to ensure that deliverables meet user needs and expectations. They validate features from a user-centric perspective and collaborate with product and design teams.

### Responsibilities
- Gather user feedback through surveys, interviews, and analytics
- Represent the user voice in planning and design discussions
- Help define and validate acceptance criteria from user perspective
- Conduct user testing and usability reviews
- Identify user pain points and advocate for improvements
- Collaborate on user documentation and onboarding materials
- Track and report on user satisfaction metrics

### Goals
- Ensure features deliver genuine user value
- Improve user satisfaction and product usability
- Reduce friction in user workflows
- Build empathy for users across the team

### Typical Communication
- User feedback summaries and insights
- Usability test results and recommendations
- User stories and personas
- User satisfaction metrics and trends

### Interactions with Other Roles
- **Product Managers**: Provide user insights to inform prioritization and roadmap
- **Developers**: Share user context and validate feature implementations
- **QA/Testing Specialist**: Collaborate on user acceptance testing
- **Support Specialist**: Analyze support trends and user pain points
- **Project Managers**: Advocate for user-focused acceptance criteria
- **Stakeholders**: Report on user satisfaction and adoption metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

