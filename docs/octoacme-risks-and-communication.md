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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Role-Specific Communication Flows

**Product Manager**
- Weekly roadmap updates to stakeholders and leadership
- Feature acceptance decisions to Project Manager and team
- Customer feedback and prioritization rationale to all team members

**Project Manager**
- Weekly status updates to stakeholders (see template below)
- Daily coordination with delivery team via standups
- Risk escalations to Product Manager and sponsors
- Cross-team dependency coordination

**Developers**
- Technical updates in standups and PR descriptions
- Design feasibility feedback to UX Designer
- Infrastructure and deployment needs to DevOps Engineer
- Instrumentation questions to Data Analyst/Data Scientist

**UX Designer**
- Design specifications and wireframes to Developers
- User research findings to Product Manager and stakeholders
- Design reviews and critiques with design team
- Usability test results to Product Manager and Developers

**Data Analyst / Data Scientist**
- Weekly metrics reports to Product Manager and leadership
- Experiment results and insights to Product Manager
- Data quality issues to Developers and DevOps Engineer
- Dashboard updates and definitions to stakeholders

**DevOps Engineer**
- Deployment status and health to Project Manager and Developers
- Incident notifications to all relevant teams and Customer Support
- Infrastructure changes to Developers and Project Manager
- Capacity and performance reports to Product Manager

**Customer Support / Advocacy Lead**
- Customer feedback synthesis to Product Manager and UX Designer
- Escalations and bug reports to Developers and Project Manager
- Release readiness and customer impact to Project Manager
- Post-release customer sentiment to Product Manager and team

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication Template:
- Incident summary and impact
- Actions being taken and owners
- Expected timeline for resolution
- Communication plan (who needs to know, how often)
- Post-incident blameless retrospective scheduled

**Incident Communication Roles:**
- **DevOps Engineer**: Technical incident response, mitigation actions, status updates
- **Project Manager**: Stakeholder coordination, communication cadence, escalation
- **Customer Support/Advocacy Lead**: Customer communication, support team coordination
- **Product Manager**: Impact assessment, prioritization of fixes, stakeholder updates
- **Developers**: Technical troubleshooting, implementation of fixes

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
