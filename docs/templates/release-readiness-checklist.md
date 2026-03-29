# Release Readiness Checklist

Use this checklist to confirm role-level signoffs before a release.

Release: [name / number]
Date: [YYYY-MM-DD]
Prepared by: [Release Manager]

Pre-release checks
- [ ] Acceptance criteria for all release items met (PdM / Feature Owner)
- [ ] CI green and security scans passed (Developers / DevOps)
- [ ] QA sign-off on release candidate (QA Engineer)
- [ ] UX/Design review completed for UI changes (UX Designer)
- [ ] Performance smoke test results acceptable (DevOps / Developers)
- [ ] Rollback / mitigation plan documented (Release Manager)
- [ ] Release notes drafted (Release Manager / PdM)
- [ ] Support readiness: support docs, runbooks, and escalation contacts confirmed (Support Specialist)
- [ ] Stakeholders notified of window and expected impact (Project Manager)

Role approvals (initial / date)
- Product Manager (PdM): _______
- Project Manager (PM): _______
- Release Manager: _______
- QA Engineer: _______
- DevOps / Platform: _______
- Support Specialist: _______
- Security Champion (if security-affecting): _______

Post-release checks
- [ ] Smoke tests passed in production (Release Manager / DevOps)
- [ ] Monitoring dashboards validated (DevOps / Data Analyst)
- [ ] Customer-impacting issues logged and triaged (Support Specialist)
- [ ] Post-release retrospective scheduled (PM / PdM)

Notes & exceptions:
- [Add any exceptions or manual verification steps here]
