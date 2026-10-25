# Sprint 6 Retrospective
Date: 2026-09-29
Attendees: Balasubramaniyam Thushakaran, Keerthi Gopalavannan, Aswini Parameswaran, Tharshana Sarathchandar

Sprint theme: Core Features (September 2026)

## Delivered
Product and category management; cart; order placement and order service; notifications; feedback; appointments (booking, rescheduling, cancellation); complaints; custom design requests; payment processing service.

## Went Well
1. Core business modules – products and categories, cart, orders, notifications, feedback, appointments, complaints, custom designs and payments – were all delivered.
2. Each module was developed on its own feature branch and merged through a pull request.
3. DTOs were used consistently, so entities are never exposed directly by the API.

## To Improve
1. Unit tests were again postponed; most service classes had no tests at the end of the sprint.
2. Some pull requests were large (complete modules), which made review slow.
3. Work on the frontend had not started.

## Action Items
| Action | Owner | Due |
|--------|-------|-----|
| Start unit tests for completed services in Sprint 7 | All | Sprint 7, Week 1 |
| Keep pull requests to one issue and under a few hundred lines | All | Sprint 7 |
| Set up the frontend project, API layer and shared components | B. Thushakaran | Sprint 7 |

## Metrics
- Pull requests merged: 4 (backend)
- CI pipeline: Passed
- Test coverage: Not measured
