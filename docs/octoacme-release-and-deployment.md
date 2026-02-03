# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (DevOps Engineer)
- Release notes drafted (Product Manager + Project Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA Automation Specialist)
- Infrastructure readiness confirmed (DevOps Engineer)
- Design verification completed for UI changes (UX Designer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - Project Manager
- [ ] Backup or snapshot (if applicable) - DevOps Engineer
- [ ] Deploy to staging and run smoke tests - DevOps Engineer + QA Automation Specialist
- [ ] Deploy to production (automated pipeline preferred) - DevOps Engineer
- [ ] Run post-deploy verifications - DevOps Engineer + QA Automation Specialist
- [ ] Announce release to stakeholders and support - Product Manager + Project Manager
- [ ] Monitor system metrics and error rates - DevOps Engineer

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Triage root cause and capture action items (DevOps Engineer + relevant team members)
  - Communicate status to stakeholders (Project Manager)
  - Document incident and learnings (Project Manager + DevOps Engineer)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
