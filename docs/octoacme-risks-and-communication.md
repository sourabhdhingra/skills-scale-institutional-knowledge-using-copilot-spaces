# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, executives)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Tailor communication to audience:
  - **Technical stakeholders** (Developers, DevOps, QA): detailed technical updates, architecture decisions
  - **Product stakeholders** (Product Managers, UX Designers): feature progress, user impact, design decisions
  - **Business stakeholders** (Business Analysts, executives): business value, ROI, timeline, risks
  - **Operations stakeholders** (Support Lead, DevOps): deployment schedules, support readiness, monitoring
- Leverage Business Analyst for translating technical progress to business stakeholders
- Engage Support Lead early for customer-facing changes

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
- For deployment issues, DevOps/Release Engineer escalates to PM -> Product Lead
- For customer-impacting issues, Support Lead escalates through Support → Product Manager → Sponsor
- For design/UX conflicts, UX Designer and Product Manager collaborate; escalate to Product Lead if unresolved
