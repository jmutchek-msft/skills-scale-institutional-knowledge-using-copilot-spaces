# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans reviewed by Solutions Architect
- Release notes drafted with input from Product Manager
- Rollback / mitigation plan documented by Solutions Architect and QA Lead
- Smoke tests prepared by QA Lead
- Customer communication plan finalized by Support/Success Manager
- UX Designer validation for user-facing changes

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests coordinated by QA Lead
- [ ] Solutions Architect review of deployment configuration
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications by QA Lead
- [ ] Announce release to stakeholders and support via Support/Success Manager
- [ ] Customer-facing documentation updated

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Support/Success Manager coordinates customer communication
  - Solutions Architect and QA Lead assess impact and rollback options
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Scrum Master facilitates post-incident retrospective

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
