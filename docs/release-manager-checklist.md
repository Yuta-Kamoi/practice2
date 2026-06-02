# Release Manager — Pre-release & Deployment Checklist

Purpose: A practical checklist for Release Managers to verify readiness and execute releases reliably.

## Pre-release (before deploying to production)
- [ ] Release date/time confirmed and stakeholders notified
- [ ] All PRs merged and CI status is green
- [ ] Security and dependency scans passed
- [ ] Migration scripts reviewed and tested in staging
- [ ] Rollback plan documented and tested
- [ ] Release notes drafted and reviewed
- [ ] Support and on-call teams notified with runbook

## Staging verification
- [ ] Deploy to staging successful
- [ ] Run smoke tests (automated and manual) — pass
- [ ] Performance sanity checks executed
- [ ] Critical flows validated by product/QA/UX

## Production deployment
- [ ] Take backup/snapshot if applicable
- [ ] Trigger production deployment pipeline
- [ ] Monitor deploy logs and health checks
- [ ] Execute post-deploy smoke tests
- [ ] Announce completion to stakeholders

## Post-release
- [ ] Monitor metrics & error dashboards for 24–72 hours
- [ ] Capture any regressions and assign issues
- [ ] Update release notes with known issues and follow-ups
- [ ] Schedule post-release retrospective if needed
