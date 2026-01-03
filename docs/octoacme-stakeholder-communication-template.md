# OctoAcme Stakeholder Communication Template

## Purpose
This document provides standardized templates for consistent, transparent stakeholder communication. Using these templates ensures all stakeholders receive the information they need in a predictable format, reducing confusion and enabling better decision-making.

---

## Weekly Status Update Template

Use this template for regular project status updates to stakeholders. Send weekly (or at the agreed cadence) to maintain transparency and alignment.

### Template

```
## [Project Name] – Weekly Status Update for [Week of Date]

### 📊 Executive Summary
[1-2 sentence overview of project health: On Track / At Risk / Blocked]

### ✅ Progress This Week
- [Key accomplishment 1]
- [Key accomplishment 2]
- [Key accomplishment 3]

### 🎯 Next Week's Focus
- [Planned work item 1]
- [Planned work item 2]
- [Planned work item 3]

### 🚧 Risks & Blockers
| Risk/Blocker | Impact | Mitigation/Action Needed | Owner |
|--------------|--------|--------------------------|-------|
| [Description] | [High/Med/Low] | [What's being done or needed] | [Name] |

### 📈 Key Metrics
- **Velocity**: [X story points completed] ([+/-Y vs. last week])
- **Scope**: [X% complete] ([Z features/stories remaining])
- **Timeline**: [On track / At risk of [X days] delay]
- **Budget**: [X% consumed] ([remaining budget/runway])

### 🤝 Decisions Needed / Ask
- [Decision point 1 – Who needs to decide by when]
- [Decision point 2 – Who needs to decide by when]
- [Support needed or resource request]

### 📎 Additional Context
- [Link to project board]
- [Link to detailed project plan]
- [Link to release notes or demo]

---
**Next Update**: [Date of next status update]
**Questions?** Contact [Project Manager Name] at [contact info]
```

### When to Use
- **Frequency**: Weekly, or at the cadence agreed with stakeholders
- **Audience**: Project sponsors, executive leadership, cross-functional partners
- **Delivery Method**: Email, Slack post, or centralized project document

### Tips for Effective Status Updates
- **Be Concise**: Respect stakeholder time – keep it scannable and focused
- **Use Consistent Formatting**: Same structure every week builds trust and predictability
- **Highlight Blockers Early**: Don't hide problems – surface them with proposed solutions
- **Quantify Progress**: Use metrics, percentages, or story points to show concrete progress
- **Make Asks Explicit**: Clearly state what decisions or actions you need from stakeholders

---

## Incident Communication Template

Use this template when communicating about production incidents, service disruptions, or critical issues requiring immediate stakeholder awareness.

### Initial Incident Notification Template

```
## 🚨 INCIDENT NOTIFICATION: [Brief Incident Description]

**Incident ID**: [INC-####]
**Severity**: [P0 / P1 / P2] ([Severity definition: e.g., P0 = Service down])
**Status**: [Investigating / Identified / Monitoring / Resolved]
**Detected At**: [Time, Timezone]
**Reported By**: [Name/System]

### Impact
- **Affected Services/Features**: [What is impacted]
- **User Impact**: [How many users affected, what functionality is unavailable]
- **Business Impact**: [Revenue, SLA, customer commitments affected]

### Current Situation
[2-3 sentences describing what is currently known about the incident]

### Actions Being Taken
- [Action 1] – Owner: [Name]
- [Action 2] – Owner: [Name]
- [Action 3] – Owner: [Name]

### Next Update
**Scheduled for**: [Time] or when status changes significantly

### Incident Commander
**Name**: [Name]
**Contact**: [Slack/Phone/Email]

### Where to Follow Along
- [Link to incident channel/war room]
- [Link to status page if public-facing]
```

### Incident Update Template (During Resolution)

```
## INCIDENT UPDATE: [Brief Incident Description] – [Time]

**Incident ID**: [INC-####]
**Status**: [Investigating / Identified / Monitoring / Resolved]
**Duration**: [X hours/minutes since detection]

### What's Changed Since Last Update
[Summary of progress made since last communication]

### Current Actions
- [In-progress action 1] – ETA: [Time]
- [In-progress action 2] – ETA: [Time]

### Impact Update
[Any changes to scope of impact, number of users affected, etc.]

### Estimated Time to Resolution
[Best estimate based on current knowledge, or "Still investigating"]

### Next Update
**Scheduled for**: [Time] or when status changes significantly
```

### Incident Resolution Template

```
## ✅ INCIDENT RESOLVED: [Brief Incident Description]

**Incident ID**: [INC-####]
**Status**: RESOLVED
**Resolution Time**: [Time, Timezone]
**Total Duration**: [X hours/minutes]

### Resolution Summary
[Brief explanation of what was done to resolve the incident]

### Root Cause (Preliminary)
[Initial understanding of what caused the incident – note if still under investigation]

### User Impact Summary
- **Users Affected**: [Number/percentage]
- **Services Impacted**: [List]
- **Duration of Impact**: [Time period]

### Next Steps
- [ ] Full Root Cause Analysis (RCA) to be completed by [Date]
- [ ] Post-Incident Review scheduled for [Date/Time]
- [ ] [Any immediate follow-up actions or monitoring]

### Post-Incident Review
**When**: [Date/Time]
**Where**: [Meeting link]
**Who Should Attend**: [Roles/names]

### Questions or Concerns?
Contact [Incident Commander Name] at [contact info]

---
Thank you to everyone who contributed to resolving this incident.
```

### When to Use
- **Initial Notification**: Immediately upon confirming a high-severity incident (within 15-30 minutes)
- **Updates**: Every 30-60 minutes during active incidents, or when status changes
- **Resolution Notice**: Immediately upon resolution, with preliminary details
- **Frequency**: Adjust based on severity – P0 incidents need more frequent updates than P2

### Tips for Incident Communication
- **Speed Over Perfection**: It's better to communicate quickly with partial information than delay
- **Set Expectations**: Tell stakeholders when they'll hear from you next
- **Avoid Speculation**: Stick to confirmed facts; note what is still being investigated
- **Use Clear Severity Levels**: Define P0/P1/P2 so stakeholders understand urgency
- **Acknowledge Impact**: Show empathy for affected users and business impact
- **Follow Through**: Always close the loop with a resolution notice and post-incident review

---

## Milestone / Release Communication Template

Use this template for major milestone achievements or product releases.

### Template

```
## 🎉 [Milestone Name] – Release Announcement

**Release Date**: [Date]
**Version**: [Version number]
**Release Type**: [Major / Minor / Patch / Hotfix]

### What's New
#### Major Features
- **[Feature 1 Name]**: [Brief description of feature and value]
- **[Feature 2 Name]**: [Brief description of feature and value]

#### Improvements
- [Improvement 1]
- [Improvement 2]

#### Bug Fixes
- [Fix 1]
- [Fix 2]

### Who This Impacts
- **End Users**: [How users benefit from this release]
- **Internal Teams**: [Any new tools, processes, or workflows affected]
- **Integrations/APIs**: [Any breaking changes or new integrations]

### How to Access
[Instructions for accessing new features or upgrading]

### Documentation & Support
- [Link to release notes]
- [Link to user documentation]
- [Link to migration guide if breaking changes]
- [Support contact for questions]

### Known Issues
[Any known limitations or issues to be aware of – or "None at this time"]

### What's Next
[Preview of upcoming milestones or features in the roadmap]

### Feedback Welcome
We'd love to hear your feedback! [Link to feedback form or contact]

---
**Release Team**: [Thank team members who contributed]
```

---

## Stakeholder Alignment Meeting Template

Use this template to structure stakeholder alignment meetings (sprint demos, milestone reviews, roadmap planning).

### Pre-Meeting (Agenda Distributed 24-48 Hours in Advance)

```
## [Meeting Name] – [Date]

**Time**: [Time, Timezone]
**Duration**: [X minutes]
**Location**: [Meeting link / Room]
**Attendees**: [List of expected attendees]

### Agenda
1. **Project Status Overview** (5 min) – [Presenter Name]
   - Progress since last meeting
   - Key metrics update

2. **Demo: [Feature/Milestone Name]** (15 min) – [Presenter Name]
   - Live demonstration of completed work
   - Q&A

3. **Upcoming Priorities** (10 min) – [Presenter Name]
   - Next sprint/milestone goals
   - Dependency discussion

4. **Risks & Decisions Needed** (10 min) – [Facilitator Name]
   - Current blockers or risks
   - Decisions required from stakeholders

5. **Open Discussion / Q&A** (10 min) – All

### Pre-Reading
- [Link to status document]
- [Link to demo script or prototype]

### Decisions to Be Made
- [Decision point 1]
- [Decision point 2]

### Questions to Consider
- [Question 1 for stakeholders to think about]
- [Question 2 for stakeholders to think about]
```

### Post-Meeting (Notes Distributed Within 24 Hours)

```
## [Meeting Name] – Meeting Notes – [Date]

**Attendees**: [Who attended]
**Absent**: [Who was absent – for visibility]

### Key Decisions Made
| Decision | Rationale | Owner | By When |
|----------|-----------|-------|---------|
| [Decision 1] | [Why this was decided] | [Name] | [Date] |
| [Decision 2] | [Why this was decided] | [Name] | [Date] |

### Action Items
| Action | Owner | Due Date | Status |
|--------|-------|----------|--------|
| [Action 1] | [Name] | [Date] | Not Started |
| [Action 2] | [Name] | [Date] | In Progress |

### Discussion Summary
[High-level summary of key discussions and outcomes]

### Parking Lot / Follow-Up Items
[Items raised but not resolved – to be addressed async or in future meeting]

### Next Meeting
**Date**: [Date]
**Focus**: [What we'll cover next time]
```

---

## Quick Communication Guidelines by Audience

### For Executive Leadership
- **Focus**: Business impact, risks, budget, high-level timeline
- **Length**: Brief – 1-2 paragraphs or bullet points
- **Frequency**: Monthly or at milestones, unless at-risk
- **Tone**: Strategic, outcome-focused

### For Project Sponsors
- **Focus**: Scope, timeline, budget, decisions needed
- **Length**: Moderate – 1 page weekly status
- **Frequency**: Weekly during active phases
- **Tone**: Transparent, solution-oriented

### For Cross-Functional Partners
- **Focus**: Dependencies, handoffs, integration points
- **Length**: Detailed where relevant to their work
- **Frequency**: As needed, or weekly during high-collaboration phases
- **Tone**: Collaborative, specific

### For End Users / Customers
- **Focus**: Value delivered, how to use features, known issues
- **Length**: Scannable with links to details
- **Frequency**: At releases or when customer-impacting incidents occur
- **Tone**: User-centric, empathetic, helpful

---

## Communication Checklist

Before sending any stakeholder communication, ask yourself:

- [ ] **Audience**: Is this going to the right people? Anyone missing who should be included?
- [ ] **Clarity**: Can someone unfamiliar with the project understand the key points?
- [ ] **Actionability**: Are asks and decisions clearly stated with owners and due dates?
- [ ] **Timeliness**: Am I sending this at the right time (not too early, not too late)?
- [ ] **Tone**: Is the tone appropriate for the situation (urgent, celebratory, informative)?
- [ ] **Follow-Through**: Have I set expectations for next communication or action?

---

## Related Documentation
- [Risks and Communication](octoacme-risks-and-communication.md) – Risk management and escalation paths
- [Project Management Overview](octoacme-project-management-overview.md) – OctoAcme's project framework
- [Cross-Functional Onboarding Matrix](octoacme-cross-functional-onboarding-matrix.md) – Role interaction patterns

---

*This document supports Issue [#4](https://github.com/jeetu-rathore/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) – Implementing targeted process improvements for consistent stakeholder communication.*
