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

---

## Risk and Escalation Checklist for Teams

Use this checklist to ensure comprehensive risk management and timely escalation throughout your project lifecycle.

### Risk Identification Checklist

Complete this checklist during project initiation, sprint planning, and whenever significant changes occur:

#### Technical Risks
- [ ] **Dependencies**: Have we identified all external dependencies (APIs, services, libraries)?
- [ ] **Technical Debt**: Are there existing tech debt areas that could slow us down?
- [ ] **Infrastructure**: Do we have capacity, performance, and scaling concerns?
- [ ] **Integration Points**: Are there complex integration points that could fail?
- [ ] **Technology Choices**: Are we using unfamiliar technologies that could cause delays?
- [ ] **Data Migration**: Is data migration required? What could go wrong?
- [ ] **Testing Coverage**: Are there areas with low test coverage that increase risk?

#### Resource Risks
- [ ] **Team Availability**: Are team members available for the full project duration?
- [ ] **Skills Gaps**: Do we have the right expertise? Do we need training or external help?
- [ ] **Competing Priorities**: Are team members pulled by other high-priority work?
- [ ] **Key Person Dependencies**: Are we over-reliant on specific individuals?
- [ ] **Budget Constraints**: Is budget sufficient for the full scope?

#### Schedule Risks
- [ ] **Timeline Realism**: Are estimates realistic given team velocity and complexity?
- [ ] **Buffer Time**: Have we included buffer for unknowns and unexpected issues?
- [ ] **Critical Path**: Have we identified the critical path and potential bottlenecks?
- [ ] **External Deadlines**: Are there fixed external deadlines (conferences, compliance, customer commitments)?
- [ ] **Dependency Delays**: Could delays in dependencies block our progress?

#### Scope Risks
- [ ] **Requirements Clarity**: Are requirements clear and well-documented?
- [ ] **Scope Creep**: Are there requests or features that could expand scope?
- [ ] **Acceptance Criteria**: Are acceptance criteria well-defined and testable?
- [ ] **Stakeholder Alignment**: Do all stakeholders agree on scope and priorities?

#### Security & Compliance Risks
- [ ] **Security Review**: Has security reviewed the design and implementation plan?
- [ ] **Compliance Requirements**: Are there regulatory or compliance requirements (GDPR, SOC2, etc.)?
- [ ] **Vulnerability Management**: Are there known vulnerabilities in dependencies?
- [ ] **Access Control**: Are access controls and permissions properly configured?
- [ ] **Data Privacy**: Are we handling sensitive data appropriately?

#### Communication & Organizational Risks
- [ ] **Stakeholder Engagement**: Are stakeholders engaged and available for decisions?
- [ ] **Cross-Team Dependencies**: Have we aligned with other teams on shared work?
- [ ] **Decision-Making**: Are decision-makers identified and available?
- [ ] **Change Management**: Will this change require user training or documentation?

### Risk Assessment and Documentation

For each identified risk:
1. **Document in Risk Register**: Add to the project risk register with:
   - Unique ID (e.g., RISK-001)
   - Clear description
   - Impact rating (High/Medium/Low)
   - Likelihood rating (High/Medium/Low)
   - Risk score (Impact × Likelihood)

2. **Assign Owner**: Every risk needs an owner responsible for monitoring and mitigation

3. **Define Mitigation Plan**: Document how you'll reduce likelihood or impact:
   - Preventive actions (reduce likelihood)
   - Contingency plans (reduce impact if it occurs)
   - Acceptance criteria (when can we close this risk?)

4. **Set Review Cadence**: High-priority risks reviewed weekly, others bi-weekly

### Escalation Decision Tree

Use this decision tree to determine when and how to escalate:

#### When to Escalate to Project Manager
Escalate immediately if:
- [ ] A risk becomes a blocker preventing progress on critical path work
- [ ] Estimated timeline slips by more than 2 days on a sprint goal
- [ ] A team member is unexpectedly unavailable for more than 2 days
- [ ] You need a decision from a stakeholder and can't reach them
- [ ] Scope change requests come from stakeholders mid-sprint
- [ ] Technical complexity is significantly higher than estimated

#### When Project Manager Escalates to Product Lead
Project Manager should escalate if:
- [ ] Timeline delay exceeds 1 week or threatens a milestone
- [ ] Scope changes would require re-prioritizing other roadmap items
- [ ] Resource conflicts can't be resolved at PM level
- [ ] Cross-team dependencies are blocked and not resolving
- [ ] Budget overrun is projected or already occurred
- [ ] Stakeholder conflicts on priorities require product leadership decision

#### When to Escalate to Executive Sponsor
Product Lead should escalate if:
- [ ] Project is at risk of missing a major customer commitment
- [ ] Significant budget increase required to deliver on commitments
- [ ] Strategic direction change needed (pivot, cancel, or major scope change)
- [ ] Legal, compliance, or regulatory issues identified
- [ ] Organizational resource conflicts require executive decision
- [ ] Reputational risk to company if not addressed

#### Security-Specific Escalation Paths
Escalate to Security Lead immediately if:
- [ ] A security vulnerability is discovered in production (any severity)
- [ ] Sensitive data exposure or breach is suspected or confirmed
- [ ] Third-party dependency has a critical CVE affecting our systems
- [ ] Compliance violation is identified (GDPR, SOC2, etc.)
- [ ] Suspicious activity or potential security incident detected

For **Critical (P0) Security Incidents**:
- Notify Security on-call immediately (within 15 minutes of discovery)
- Follow security incident runbook
- Escalate to executive team for critical customer-impacting issues

### Escalation Communication Template

When escalating, include:

```
**Escalation Request**

**From**: [Your Name, Role]
**To**: [Escalation Target Name, Role]
**Date**: [Date/Time]
**Project**: [Project Name]
**Severity**: [High / Medium / Low]

**Issue Summary**:
[1-2 sentence description of the issue]

**Impact**:
- Timeline impact: [X days/weeks delay OR On schedule but at risk]
- Scope impact: [What features/deliverables affected]
- Business impact: [Customer commitments, revenue, reputation]

**What We've Tried**:
- [Action 1 taken]
- [Action 2 taken]
- [Why these haven't resolved the issue]

**Decision/Action Needed**:
[Specific ask – what decision or action is needed from the escalation target]

**Urgency**:
[When decision is needed by – be specific]

**Additional Context**:
[Links to project docs, risk register, relevant Slack threads]
```

### Risk Monitoring Cadence

- **Daily Standups**: Quickly surface new blockers or risks
- **Weekly Status Updates**: Review top 5 risks, update status, check mitigation progress
- **Sprint Planning**: Identify risks for upcoming sprint, plan mitigation activities
- **Milestone Reviews**: Comprehensive risk register review, close resolved risks
- **Post-Incident Reviews**: Identify systemic risks revealed by incidents

### Risk Closure Criteria

A risk can be closed when:
- [ ] The risk has been fully mitigated (likelihood reduced to negligible)
- [ ] The risk is no longer relevant (context changed, feature cancelled, etc.)
- [ ] The risk has occurred and been resolved (moved to lessons learned)
- [ ] A decision was made to accept the risk with documented rationale

Document lessons learned from closed risks in retrospectives to improve future risk identification.

---

## Related Documentation

For detailed communication templates, see:
- [Stakeholder Communication Template](octoacme-stakeholder-communication-template.md) – Standard formats for status updates, incident communication, and stakeholder meetings

For understanding cross-functional collaboration and escalation paths:
- [Cross-Functional Onboarding Matrix](octoacme-cross-functional-onboarding-matrix.md) – Role interaction patterns and onboarding checklists
- [Roles and Personas](octoacme-roles-and-personas.md) – Detailed role definitions and responsibilities

---

*This document supports Issue [#4](https://github.com/jeetu-rathore/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) – Implementing targeted process improvements including comprehensive risk identification checklists, escalation decision trees, and risk monitoring procedures for proactive risk management.*
