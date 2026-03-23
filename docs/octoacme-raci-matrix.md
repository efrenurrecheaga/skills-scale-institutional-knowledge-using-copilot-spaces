# OctoAcme RACI Matrix

This matrix maps key project activities to the roles defined in [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

**Key:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## Matrix

| Activity | Project Manager | Product Manager | Developer | QA Lead | Business Analyst | Release Manager | Support Coordinator |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Define problem statement & goals | C | A/R | I | I | R | I | I |
| Backlog creation & prioritization | C | A/R | C | C | R | I | I |
| Requirements elaboration & traceability | C | C | C | C | A/R | I | I |
| Project plan & milestone schedule | A/R | C | C | C | C | C | I |
| Test strategy & test plan | I | I | C | A/R | C | I | I |
| Sprint execution & feature delivery | C | C | A/R | C | C | I | I |
| Defect triage & resolution | I | I | R | A | C | I | I |
| Release planning & schedule | A | C | I | C | I | R | C |
| Go/no-go decision | C | C | I | C | I | A/R | C |
| Deployment execution | I | I | R | I | I | A | I |
| Support documentation & training | I | C | I | I | C | C | A/R |
| Post-launch feedback collection | I | C | I | I | I | I | A/R |
| Retrospective facilitation | A/R | C | C | C | C | C | C |
| Risk & dependency management | A/R | C | C | C | C | C | I |
| Stakeholder status communications | A/R | C | I | I | I | C | I |

---

## Role Boundary Notes

- **Project Manager vs. Release Manager:** The PM owns overall schedule and stakeholder communications; the Release Manager owns the release gate specifically—go/no-go, deployment runbook, and post-release quality checks.
- **Product Manager vs. Business Analyst:** The PdM owns *what* gets built and *why*; the BA owns the detailed *how* of requirements, ensuring traceability and resolving edge-case ambiguity before development begins.
- **Developer vs. QA Lead:** Developers write and own unit/integration tests; the QA Lead owns the end-to-end test strategy, acceptance validation, and the quality sign-off required for release.
- **Release Manager vs. Support Coordinator:** Release Manager hands off release notes and known-issues before go-live; Support Coordinator takes ownership of user-facing content and post-launch feedback from that point on.

---

## Handoff Points

| From | To | Trigger | Artifact |
|---|---|---|---|
| Business Analyst | Developer | Requirements sign-off | Requirements doc / elaborated user stories |
| Developer | QA Lead | Feature branch merged to staging | Test-ready build + acceptance criteria |
| QA Lead | Release Manager | All tests pass, defects resolved | Quality sign-off report |
| Release Manager | Support Coordinator | Go/no-go approved | Release notes + known-issues list |
| Support Coordinator | Product Manager | Post-launch feedback report | First-30-days support-volume report |
| Release Manager | Project Manager | Deployment complete | Post-release summary |
