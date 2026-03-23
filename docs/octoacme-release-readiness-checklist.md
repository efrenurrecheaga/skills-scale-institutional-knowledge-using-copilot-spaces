# OctoAcme Release Readiness Checklist

Use this checklist before every release gate. The Release Manager owns completion; each section is signed off by the indicated role.

---

## 1. Planning & Scope (Business Analyst + Project Manager)

- [ ] All acceptance criteria are documented and signed off
- [ ] Scope changes since last gate are logged with impact assessment
- [ ] Dependencies on external teams or third-party systems are resolved or mitigated
- [ ] Release version and target date are confirmed with stakeholders

---

## 2. Quality & Testing (QA Lead)

- [ ] Test plan executed; test results attached or linked
- [ ] All critical and high-severity defects are resolved or have approved workarounds
- [ ] Regression suite passes on the release candidate build
- [ ] Test-automation coverage meets agreed threshold
- [ ] Acceptance criteria validated for all in-scope features
- [ ] Performance / load tests completed (if applicable)

---

## 3. Release Coordination (Release Manager)

- [ ] Release notes drafted and reviewed by Product Manager
- [ ] Deployment runbook is current and reviewed with DevOps
- [ ] Rollback plan documented and rehearsed if needed
- [ ] Release calendar entry confirmed; downstream teams notified
- [ ] Go/no-go meeting scheduled with required stakeholders

---

## 4. Support Readiness (Support Coordinator)

- [ ] User-facing documentation and FAQs published or staged for publication
- [ ] Support team trained on new features and known limitations
- [ ] Incident escalation path defined and communicated
- [ ] Support tooling (e.g., tags, routing rules) updated for new features
- [ ] Known-issues list handed off from Release Manager

---

## 5. Go / No-Go Sign-Off

| Role | Sign-Off | Date | Notes |
|---|---|---|---|
| QA Lead | ☐ | | |
| Business Analyst | ☐ | | |
| Release Manager | ☐ | | |
| Support Coordinator | ☐ | | |
| Project Manager | ☐ | | |
| Product Manager | ☐ | | |

> **Go criteria:** All sections above are checked, or exceptions are documented and accepted by the Project Manager and Product Manager.

---

## 6. Post-Release (Release Manager + Support Coordinator)

- [ ] Deployment verified in production (smoke tests passed)
- [ ] Monitoring / alerting confirmed active for new components
- [ ] Release notes published to stakeholders
- [ ] Support Coordinator notified of go-live; post-launch watch period begins
- [ ] Post-release retrospective item created if any gate item was unresolved at go/no-go
