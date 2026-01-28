# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Role-Specific Execution Workflows

### Developer Workflow
- Pick items from "Ready" column that have clear acceptance criteria
- Create feature branch and implement changes with tests
- Submit PR with description linking to issue and design specs (if applicable)
- Address code review feedback and ensure CI passes
- Coordinate with DevOps Engineer on deployment and monitoring needs
- Validate implementation against design specs with UX Designer (for UI changes)

### UX Designer Workflow
- Monitor "In Progress" items that involve UI/UX work
- Provide design clarifications and feedback during implementation
- Review PRs for design fidelity and accessibility
- Conduct usability testing on staged features before release
- Update design documentation based on implementation learnings

### Data Analyst / Data Scientist Workflow
- Monitor instrumentation and tracking implementation in PRs
- Validate data collection and metric definitions during code review
- Set up or update dashboards as features are released
- Track success metrics and report on progress toward goals
- Conduct analysis and experiments to inform iteration

### DevOps Engineer Workflow
- Monitor infrastructure and resource usage during development
- Review and approve infrastructure changes and deployment scripts
- Coordinate deployment windows and release logistics
- Monitor deployments and rollout health
- Respond to incidents and maintain runbooks

### Customer Support / Advocacy Lead Workflow
- Monitor for customer-reported issues and escalations during development
- Test features from customer perspective before release
- Prepare support documentation and FAQs
- Brief support team on new features and changes
- Gather post-release feedback and communicate to Product and Engineering

### Product Manager Workflow
- Monitor backlog and adjust priorities based on new information
- Review completed features against acceptance criteria and goals
- Make go/no-go decisions for releases based on quality and completeness
- Gather customer feedback and inform next iteration
- Update roadmap and communicate progress to stakeholders

### Project Manager Workflow
- Facilitate daily standups and track progress
- Update project status and communicate risks
- Coordinate cross-team dependencies and handoffs
- Escalate blockers and facilitate resolution
- Maintain project artifacts (timeline, risk register, decision log)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
