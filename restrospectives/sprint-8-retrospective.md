# Sprint 8 Retrospective
Date: 2026-10-24
Attendees: Balasubramaniyam Thushakaran, Keerthi Gopalavannan, Aswini Parameswaran, Tharshana Sarathchandar

Sprint theme: Quality & Release (October 2026 (weeks 3–4))

## Delivered
Unit test completion (218 tests); 13 API integration test suites (253 executions) in the tests repository; frontend unit and integration tests; Spotless/ESLint/Prettier formatting gates; Dockerfiles and Compose stacks; reusable CI/CD workflows with Trivy and npm audit; deployment to AWS EC2 behind Caddy; releases v0.1.0 and v0.1.1.

## Went Well
1. 218 unit tests and 253 integration test executions were written and all pass; merged backend line coverage reached 91.3%.
2. The CI/CD pipeline was moved into reusable workflows in the infra repository with Trivy and npm audit security scans.
3. The system was containerised and a deployment to AWS EC2 with automatic HTTPS was prepared.
4. Releases v0.1.0 and v0.1.1 were tagged following semantic versioning.

## To Improve
1. Frontend page components have no automated tests (overall frontend line coverage 4.92%).
2. Testing was concentrated in the last sprint instead of being part of each feature's Definition of Done.
3. Some features requested by the client (estimated delivery date, return requests) and the custom design screens were not delivered.
4. The EC2 deployment change was still on a branch when the sprint closed.

## Action Items
| Action | Owner | Due |
|--------|-------|-----|
| Merge the EC2 deployment branch and publish the staging URL in the READMEs | K. Gopalavannan | Before demonstration |
| Add component tests for checkout, cart and order pages | All | Next release |
| Implement estimated delivery date and return requests | Team | Next release |

## Metrics
- Pull requests merged: 10 (backend), 15 (frontend), 1 (infra), 1 (tests)
- CI pipeline: All stages passing locally
- Test coverage: Backend 91.3% lines; frontend gated files ≥ 80%
- Automated tests: 508 (all passing)
