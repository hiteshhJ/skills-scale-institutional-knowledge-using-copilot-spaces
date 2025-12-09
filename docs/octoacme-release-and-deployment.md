# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

**Key Roles**: See [Release Manager](octoacme-roles-and-personas.md#release-manager), [Security Lead](octoacme-roles-and-personas.md#security-lead), and [QA/Testing Specialist](octoacme-roles-and-personas.md#qa--testing-specialist) for detailed responsibilities related to releases.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Incident Response Checklist
Use this checklist when responding to production incidents:

### Immediate Response (First 15 minutes)
- [ ] Assess severity and impact (critical/high/medium/low)
- [ ] Notify incident commander (typically Release Manager or PM)
- [ ] Create incident communication channel
- [ ] Notify affected stakeholders with initial update
- [ ] Assemble response team (Developers, Release Manager, Security Lead if needed)
- [ ] Document incident start time and initial symptoms

### Triage and Mitigation (First hour)
- [ ] Identify root cause or narrow down suspects
- [ ] Decide: rollback vs. hotfix vs. workaround
- [ ] Execute mitigation plan (rollback/hotfix)
- [ ] Verify mitigation effectiveness
- [ ] Send status update to stakeholders (every 30 minutes minimum)
- [ ] Document all actions taken with timestamps

### Post-Incident (After resolution)
- [ ] Confirm full service restoration
- [ ] Send final status update to stakeholders
- [ ] Schedule post-incident retrospective (within 48 hours)
- [ ] Document timeline and root cause analysis
- [ ] Create action items to prevent recurrence
- [ ] Update runbooks based on learnings
- [ ] Close incident and archive communication channel

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
