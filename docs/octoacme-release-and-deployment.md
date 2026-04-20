# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Roles in Release & Deployment

| Role | Responsibility |
|---|---|
| Release Engineer / DevOps | Owns deployment pipeline, schedules deployment windows, runs smoke tests, monitors deploy health |
| Project Manager | Confirms release readiness (acceptance criteria, QA sign-off), coordinates stakeholder announcements |
| QA / Testing | Validates staging deployment; provides go/no-go signal |
| Customer Support Lead | Prepares support team and customer communications before and after release |
| Developers | Resolve last-minute build/pipeline issues; available during deployment window |

See [Roles and Personas](./octoacme-roles-and-personas.md) for full role descriptions.

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented and reviewed with Release Engineer
- Smoke tests prepared
- Customer Support Lead briefed on changes and known issues

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (Release Engineer)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (Release Engineer + QA)
- [ ] QA sign-off on staging validation
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (PM + Customer Support Lead)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Engineer)
  - Notify Customer Support Lead so they can communicate status to affected customers
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
