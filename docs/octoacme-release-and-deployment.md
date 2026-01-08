# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. See [OctoAcme Personas](octoacme-roles-and-personas.md) for role descriptions.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (validated by Security Lead if applicable)
- Release notes drafted
- Rollback / mitigation plan documented (coordinate with DevOps Engineer)
- Smoke tests prepared
- Customer-facing documentation updated (coordinate with Customer Support if applicable)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable, coordinate with DevOps Engineer)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred, managed by DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders, support team, and users

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (including DevOps Engineer and Security Lead if needed)
  - Rollback to last known-good release if necessary (coordinate with DevOps Engineer)
  - Triage root cause and capture action items
  - Communicate status to Customer Support for user impact management

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
