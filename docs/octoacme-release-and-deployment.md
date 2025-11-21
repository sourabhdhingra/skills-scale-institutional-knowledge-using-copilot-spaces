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
- Release notes drafted (coordinated by Product Manager and DevOps/Release Engineer)
- Rollback / mitigation plan documented by DevOps/Release Engineer
- Smoke tests prepared by QA
- Support documentation updated (Support Lead confirms readiness)
- UX validation completed for user-facing changes
- Infrastructure and monitoring ready (DevOps/Release Engineer confirms)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — coordinated by DevOps/Release Engineer and Project Manager
- [ ] Backup or snapshot (if applicable) — performed by DevOps/Release Engineer
- [ ] Deploy to staging and run smoke tests — QA validates
- [ ] Deploy to production (automated pipeline preferred) — executed by DevOps/Release Engineer
- [ ] Run post-deploy verifications — QA and DevOps/Release Engineer collaborate
- [ ] Announce release to stakeholders and support — Project Manager and Support Lead coordinate
- [ ] Support team briefed on changes and known issues — Support Lead confirms readiness
- [ ] Monitoring and alerting verified — DevOps/Release Engineer confirms

For detailed role responsibilities during deployment, see [Role Handoff Checklist - QA to Release](octoacme-role-handoff-checklist.md#qa-to-release-handoff) and [Deployment to Support Handoff](octoacme-role-handoff-checklist.md#deployment-to-support-handoff).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps/Release Engineer leads)
  - Rollback to last known-good release if necessary (DevOps/Release Engineer executes)
  - Support Lead coordinates customer communication and impact assessment
  - Triage root cause and capture action items (cross-functional team effort)
  - Product Manager and Project Manager assess business impact and prioritize fixes

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
