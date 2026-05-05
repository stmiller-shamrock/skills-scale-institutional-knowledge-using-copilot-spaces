# OctoAcme — Cross-Functional Roles Reference

## Purpose
Provide a concise, actionable reference for how roles collaborate during key project phases. Use this alongside [Roles and Personas](octoacme-roles-and-personas.md) to clarify ownership, handoffs, and escalation paths across the full project lifecycle.

---

## RACI Matrix

> **R** = Responsible (does the work) | **A** = Accountable (final decision/sign-off) | **C** = Consulted (input required) | **I** = Informed (kept in the loop)

| Activity | Project Manager | Product Manager | Tech Lead | Engineering Manager | Developers | QA Lead | UX Designer | DevOps Engineer | Business Analyst | Customer Success Manager |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project charter / one-pager | R | A | C | C | I | I | I | I | C | I |
| Requirements gathering & backlog | C | A | C | I | C | C | C | I | R | C |
| UX design & prototyping | I | C | C | I | C | C | A/R | I | C | C |
| Technical architecture | C | I | A/R | C | C | I | I | C | I | I |
| Sprint planning | A/R | C | C | C | R | C | C | I | C | I |
| Implementation | I | I | C | I | A/R | C | C | C | I | I |
| CI/CD pipeline & environments | I | I | C | C | C | C | I | A/R | I | I |
| QA & testing | C | C | C | I | R | A/R | C | C | C | I |
| Release readiness sign-off | A | C | C | C | C | R | I | R | I | C |
| Deployment | C | I | C | I | C | I | I | A/R | I | I |
| Customer communications | R | C | I | I | I | I | I | I | I | A/R |
| Post-launch feedback & metrics | I | A | C | I | I | I | C | I | I | R |
| Incident triage & escalation | A/R | C | C | C | R | C | I | R | I | C |
| Retrospective facilitation | A/R | C | C | C | C | C | C | C | C | C |

---

## Key Handoff Points

### Initiation → Planning
- **Business Analyst** hands off finalized requirements and use cases to **Product Manager** and **Tech Lead**.
- **UX Designer** delivers initial wireframes to **Developers** before sprint planning begins.
- **Engineering Manager** confirms team capacity with **Project Manager**.

### Planning → Execution
- **Tech Lead** communicates architecture decisions and coding standards to **Developers** and **DevOps Engineer**.
- **QA Lead** reviews acceptance criteria with **Business Analyst** and **Product Manager** to ensure testability.
- **DevOps Engineer** confirms CI/CD pipeline and environment readiness before the first sprint starts.

### Execution → Release
- **QA Lead** issues a QA sign-off before deployment is scheduled.
- **DevOps Engineer** prepares and validates deployment runbook with **Tech Lead**.
- **Project Manager** confirms stakeholder communications plan with **Customer Success Manager**.

### Release → Post-Launch
- **Customer Success Manager** collects early adoption feedback and shares summaries with **Product Manager**.
- **DevOps Engineer** monitors deployment health and shares metrics with the team.
- **Project Manager** schedules the retrospective and closes out the project plan.

---

## Escalation Paths

| Situation | First Contact | Escalate To |
|---|---|---|
| Technical blocker or design decision | Tech Lead | Engineering Manager → Project Manager |
| Scope change or priority conflict | Product Manager | Project Manager → Sponsor |
| Quality risk threatening release | QA Lead | Project Manager → Product Manager |
| Customer-impacting production issue | DevOps Engineer | Tech Lead → Engineering Manager → Customer Success Manager |
| Resourcing or team capacity constraint | Engineering Manager | Project Manager → Sponsor |
| Unresolved requirements ambiguity | Business Analyst | Product Manager → Project Manager |

---

## Onboarding Checklist for New Team Members

Use this checklist when a new person joins a project mid-flight to ensure they are quickly oriented.

- [ ] Share this document and [Roles and Personas](octoacme-roles-and-personas.md)
- [ ] Introduce them to their role's primary counterparts (see RACI above)
- [ ] Walk through the current project charter and backlog
- [ ] Ensure access to: project board, repository, CI/CD tooling, communication channels
- [ ] Assign a buddy from an overlapping role for the first two weeks
- [ ] Schedule a 30-minute kickoff with the Project Manager
- [ ] Confirm understanding of Definition of Done and current sprint goals

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
