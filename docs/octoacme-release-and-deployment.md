# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA Lead sign-off on release readiness
- Release notes drafted (Communications Specialist coordinates)
- Rollback / mitigation plan documented
- Smoke tests prepared and executed by QA team

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead validates)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA Lead confirms)
- [ ] Announce release to stakeholders and support (Communications Specialist executes)
- [ ] Project Sponsor notified of successful deployment

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
