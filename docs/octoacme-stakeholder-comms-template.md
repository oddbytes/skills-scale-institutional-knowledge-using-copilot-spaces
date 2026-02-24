# OctoAcme — Stakeholder Communications Template

## Purpose
Provide ready-to-use communication templates for common stakeholder-facing interactions across OctoAcme projects. Consistent communication reduces ambiguity, builds trust, and ensures stakeholders have the information they need to act.

> **Rationale (issue #4):** Cross-team communication gaps are a key driver of accountability and delivery risks. These templates standardize how information flows between roles—particularly as the team expands to include UX Designers, Data Analysts, DevOps Engineers, Security Leads, and Customer Support Specialists.

---

## 1. Weekly Status Update

**Audience:** Stakeholders, Product Manager, Project Manager  
**Sent by:** Project Manager  
**Cadence:** Weekly

```
Subject: [Project Name] — Weekly Status Update (Week of YYYY-MM-DD)

## Summary
[1–2 sentence high-level status: on track / at risk / blocked]

## Progress This Week
- [Completed item 1]
- [Completed item 2]

## Planned for Next Week
- [Planned item 1]
- [Planned item 2]

## Risks & Blockers
| Risk/Blocker | Owner | Mitigation / Next Step |
|--------------|-------|------------------------|
| [Description] | [Name] | [Action] |

## Metrics Snapshot
[Key metric 1]: [Value vs. target]
[Key metric 2]: [Value vs. target]

## Decisions Needed
- [Decision or ask, with deadline if applicable]

## Links
- Project board: [URL]
- Risk register: [URL]
```

---

## 2. Release Announcement

**Audience:** All stakeholders, Customer Support Specialist, end users (as applicable)  
**Sent by:** Project Manager or Product Manager  
**Cadence:** Per release

```
Subject: [Product/Feature Name] Release — [Version or Date]

## What's New
[Brief summary of the release: features, fixes, improvements]

## Notable Changes
- [Change 1]
- [Change 2]

## Known Issues
- [Issue 1 — workaround if available]

## Migration / Action Required
[Any steps users or operators must take, or "No action required"]

## Who to Contact for Support
[Support channel / Customer Support Specialist contact / escalation path]

## Links
- Release notes: [URL]
- Documentation: [URL]
```

---

## 3. Risk Escalation Notice

**Audience:** Project sponsor, Product Manager, affected stakeholders  
**Sent by:** Project Manager or Security Lead  
**Cadence:** As needed (when a risk moves to High impact/likelihood)

```
Subject: [RISK ESCALATION] [Project Name] — [Brief Risk Title]

## Risk Summary
[One sentence description of the risk]

## Impact
[What could happen if this risk materializes — delivery, quality, security, compliance]

## Likelihood
[High / Medium / Low — and brief rationale]

## Current Mitigation
[What is being done now to reduce the risk]

## Decision or Action Required
[What you need from the escalation audience, with deadline]

## Owner
[Name of risk owner]

## Next Update
[Date of next status update on this risk]
```

---

## 4. Incident Communication

**Audience:** Stakeholders, Customer Support Specialist, affected users  
**Sent by:** Project Manager or DevOps Engineer  
**Cadence:** During and after a production incident

### Initial Notification
```
Subject: [INCIDENT] [Service/Feature] — [Brief Description] [YYYY-MM-DD HH:MM UTC]

We are investigating an issue with [service/feature]. [Brief description of user impact.]

Status: Investigating
Next update by: [time]
Contact: [on-call or support channel]
```

### Update
```
Subject: [INCIDENT UPDATE] [Service/Feature] — [Status]

Status: [Investigating / Mitigating / Resolved]
Summary: [What we know and what actions are underway]
User impact: [Current or residual impact]
Next update by: [time or "final update to follow"]
```

### Resolution Notice
```
Subject: [RESOLVED] [Service/Feature] — [Brief Description]

The incident has been resolved as of [time UTC].

Root cause (preliminary): [Summary]
Duration: [Start time] to [End time]
Impact: [Who/what was affected and how]
Next steps: [Post-incident review scheduled for [date]]
```

---

## 5. Sprint / Milestone Review Summary

**Audience:** Product Manager, stakeholders, Developers, QA  
**Sent by:** Project Manager  
**Cadence:** End of sprint or milestone

```
Subject: [Project Name] — Sprint [N] / [Milestone] Review Summary

## Goals vs. Outcomes
| Goal | Status | Notes |
|------|--------|-------|
| [Goal 1] | ✅ Done / ⚠️ Partial / ❌ Not started | [Notes] |
| [Goal 2] | ✅ Done / ⚠️ Partial / ❌ Not started | [Notes] |

## Key Metrics
[Metric 1]: [Value]
[Metric 2]: [Value]

## Carry-overs to Next Sprint
- [Item 1]

## Retrospective Actions
- [Action 1 — Owner — Due date]

## Next Sprint Goals (Preview)
- [Goal 1]
- [Goal 2]
```

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Handoff Checklist](octoacme-handoff-checklist.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
