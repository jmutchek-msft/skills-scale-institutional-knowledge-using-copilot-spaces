# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) facilitated by Scrum Master — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone with Product Manager, UX Designer, and stakeholders
- Regular design reviews with UX Designer for feature validation

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable coordinated by QA Lead
- End-to-end smoke tests for critical flows before release
- Security scanning in CI reviewed by Solutions Architect
- Manual QA for feature acceptance when needed led by QA Lead
- Accessibility testing validated by UX Designer and QA Lead
- Architecture review by Solutions Architect for significant changes

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup facilitated by Scrum Master
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Technical blockers: Solutions Architect provides guidance and architectural decisions
- Customer-impacting issues: Support/Success Manager coordinates customer communication

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with stakeholders and UX Designer
- [ ] Risk register updated weekly by Project Manager
- [ ] Sprint ceremonies facilitated by Scrum Master
- [ ] Test strategy and acceptance criteria defined by QA Lead
- [ ] Architecture decisions documented by Solutions Architect
- [ ] Customer communication plan coordinated by Support/Success Manager
