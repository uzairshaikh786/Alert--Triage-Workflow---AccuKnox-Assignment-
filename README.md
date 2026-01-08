# Alert--Triage--Workflow---AccuKnox-Assignment-
Alert Management Dashboard for Cloud Security Engineer 

Figma screens link - https://www.figma.com/design/7t3KxabM6IVeJvyHSuJ61S/Alert-Management-Dashboard?node-id=0-1&t=efJCnLQ4Pw54cKrx-1

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Problem Statement & User Persona

Problem Statement - 
Security engineers receive a high volume of cloud security alerts daily. Many alerts lack context, leading to slow investigation, alert fatigue, and delayed remediation. Engineers need a simple and structured workflow to quickly understand alert severity, investigate root causes, and take action efficiently.


User Persona - 
Primary Persona: Cloud Security Engineer
Experience: 2–6 years
Manages alerts across multiple cloud accounts (AWS/GCP/Azure)

Responsible for:
Investigating security alerts,
Identifying misconfigurations,
Coordinating fixes or resolving directly

Pain points:
Too many alerts, not all critical,
Switching between tools for context,
Difficulty prioritizing what needs immediate action


# 2. Proposed Features & Prioritization
Core Features (MVP)
•	Severity-Based Alert List (P0)
Alerts are automatically sorted by severity so critical risks are visible first. This helps engineers focus on high-impact issues without manually scanning long lists.
•	Smart Filtering (P0)
Filters by severity, status, cloud account, and time allow engineers to quickly narrow down relevant alerts during triage.
•	Contextual Alert Details (P0)
A single alert details page shows the alert summary, affected resource, risk explanation, and suggested next steps. This reduces context switching during investigation.
•	Structured Resolution Actions (P1)
Alerts can be marked as Resolved, False Positive, or Accepted Risk, with optional comments to maintain clear audit history.
________________________________________

# 3. Design Rationale (Wireframes)
•	Alert List View
Severity-first sorting reduces alert fatigue and ensures critical issues are always visible. Filters provide flexibility without overwhelming the user.
•	Alert Details View
Information is organized to follow the investigation flow: what happened, where it happened, why it matters, and how to fix it.
•	Resolution View
Clear resolution options help engineers confidently close alerts while maintaining documentation for audits and future reference.
________________________________________

# 4. Success Metrics
Primary Metrics (Weekly):
•	MTTA: < 15 minutes for critical alerts
•	MTTR: 30% reduction within 3 months
•	Alert Triage Time: 40% reduction
•	Audit Trail Completion: 100% documentation
Quality Metrics (Monthly):
•	False Positive Rate: 20% reduction in 6 months
•	Alert Recurrence: < 5% for resolved alerts
•	User Satisfaction: NPS > 40
•	Tool Adoption: 80% of team within 2 months
________________________________________

# 5. NEXT STEPS & VALIDATION
User Testing Plan: Conduct 5 usability sessions with security engineers, measure task completion time and error rate, A/B test severity sorting vs. time-based sorting.
Success Criteria: Achieve 30% MTTR reduction and 80% user adoption within 3 months.
________________________________________

# 6. Bonus: Development Considerations
•	APIs for alert ingestion and status updates
•	Severity scoring logic
•	Audit logging for alert actions
•	Integrations with tools like Jira or Slack
________________________________________

