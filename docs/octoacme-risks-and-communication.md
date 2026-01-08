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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, security, UX)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- See [OctoAcme Personas](octoacme-roles-and-personas.md) for detailed role descriptions and communication patterns

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
- For security incidents, escalate to Security Lead immediately and follow the security incident runbook
- For critical customer issues, escalate through Customer Support -> PM -> Product Lead
- For infrastructure/deployment issues, escalate to DevOps Engineer and PM
- For UX/accessibility concerns, consult UX Designer early in the process
