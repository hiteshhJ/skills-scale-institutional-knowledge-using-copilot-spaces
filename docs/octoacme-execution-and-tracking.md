# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

**Key Roles**: See [Project Manager](octoacme-roles-and-personas.md#project-managers), [Developers](octoacme-roles-and-personas.md#developers), [QA/Testing Specialist](octoacme-roles-and-personas.md#qa--testing-specialist), and [Support Specialist](octoacme-roles-and-personas.md#support-specialist) for detailed responsibilities.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Support Triage Template
Use this template when escalating support issues to the development team:

**Support Ticket ID**: [e.g., SUPP-1234]  
**Severity**: [Critical / High / Medium / Low]  
**Issue Type**: [Bug / Feature Request / Configuration / User Error]  
**Affected Users**: [Number of users or accounts impacted]  
**First Reported**: [Date/Time]

**Summary**:  
[Brief description of the issue]

**Reproduction Steps**:  
1. [Step 1]
2. [Step 2]
3. [Expected vs. Actual behavior]

**Environment**:  
- Version/Release: [e.g., v2.3.1]
- Platform/Browser: [if applicable]
- Configuration: [relevant settings]

**User Impact**:  
[Description of how this affects users and their workflows]

**Temporary Workaround** (if available):  
[Steps users can take to work around the issue]

**Supporting Information**:  
- Logs: [attached or linked]
- Screenshots: [attached or linked]
- Related tickets: [SUPP-xxx, SUPP-yyy]

**Recommended Action**:  
[Support Specialist's recommendation: immediate fix, plan for next sprint, document as known issue, etc.]

---

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Support escalation process documented and shared with team
