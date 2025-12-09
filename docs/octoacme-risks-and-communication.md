# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

**Key Roles**: See [Project Manager](octoacme-roles-and-personas.md#project-managers), [Security Lead](octoacme-roles-and-personas.md#security-lead), and [Support Specialist](octoacme-roles-and-personas.md#support-specialist) for detailed communication and escalation responsibilities.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For release issues: Support Specialist -> Release Manager -> PM -> Sponsor
- For user experience concerns: User Advocate -> Product Manager -> Sponsor

## Role Hand-off Checklist
Use this checklist when transitioning responsibilities between team members or bringing new roles onto a project:

### For Outgoing Team Member
- [ ] Document current state and in-progress work
- [ ] List all active responsibilities and ownership areas
- [ ] Share passwords/credentials (via secure method) if applicable
- [ ] Introduce replacement to key stakeholders
- [ ] Schedule knowledge transfer sessions
- [ ] Update team contact lists and on-call rotations

### For Incoming Team Member
- [ ] Review project charter and one-pager
- [ ] Read relevant process documentation (see [docs index](README.md))
- [ ] Review [roles and personas](octoacme-roles-and-personas.md) for your role
- [ ] Access to required systems and repositories granted
- [ ] Added to communication channels (Slack, email lists)
- [ ] Shadowing period scheduled with outgoing member (if applicable)
- [ ] First week check-in scheduled with PM

### For Project Manager (Facilitating Hand-off)
- [ ] Create transition plan with timeline
- [ ] Identify critical knowledge areas for transfer
- [ ] Schedule overlap time if possible
- [ ] Update project documentation with new contact
- [ ] Communicate changes to stakeholders
- [ ] Monitor for gaps or issues during transition period
