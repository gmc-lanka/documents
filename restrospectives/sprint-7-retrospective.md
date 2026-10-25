# Sprint 7 Retrospective
Date: 2026-10-19
Attendees: Balasubramaniyam Thushakaran, Keerthi Gopalavannan, Aswini Parameswaran, Tharshana Sarathchandar

Sprint theme: Integration & UX (October 2026 (weeks 1–3))

## Delivered
Admin module (users, orders, appointments, feedback, complaints, invoices, maintenance, categories); technician task module; user profile and avatars; OpenAPI documentation; Stripe PaymentIntents and webhook; checkout pricing; rate limiting and password reset; React frontend (all customer, admin and technician pages); first unit test suites.

## Went Well
1. Admin and technician modules completed the feature set of the backend.
2. Stripe PaymentIntents, signed webhooks and automatic refunds were implemented with server-side verification.
3. Security hardening (rate limiting, password reset, upload restrictions) was added before release.
4. The first unit test suites were written for exceptions, feedback, security, appointments, products and cart.

## To Improve
1. The frontend was started only at the end of the sprint, leaving little time for UI testing.
2. Branches such as fix/17-enhancements grew large and needed several rebases.
3. Integration tests had not been started, so the 80% coverage gate could not yet be measured.

## Action Items
| Action | Owner | Due |
|--------|-------|-----|
| Write API integration tests for every controller | All (one controller group each) | Sprint 8, Week 1 |
| Build all remaining pages in parallel using the shared components | All | Sprint 8 |
| Add Docker images and the deployment stages to CI | B. Thushakaran, K. Gopalavannan | Sprint 8 |

## Metrics
- Pull requests merged: 11 (backend)
- Test coverage: Unit tests only
