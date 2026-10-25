# Sprint 5 Retrospective
Date: 2026-06-25
Attendees: Balasubramaniyam Thushakaran, Keerthi Gopalavannan, Aswini Parameswaran, Tharshana Sarathchandar

Sprint theme: Foundation & Infrastructure (May – June 2026)

## Delivered
Repositories created; Spring Boot project initialised; all JPA entities and repositories (data layer); Checkstyle configuration and first CI pipeline; authentication (register, login, JWT access token, hashed rotating refresh token); custom exceptions and global exception handler.

## Went Well
1. The data layer was split by domain (user/appointment, product/order, cart/invoice/payment, maintenance/feedback) so all four members worked in parallel without conflicts.
2. Checkstyle and a first CI pipeline were in place in the second week, so formatting problems were caught early.
3. Authentication was designed carefully: refresh tokens are hashed and rotated, which avoided later security rework.

## To Improve
1. Several commits only fixed formatting (missing newlines, star imports); running Checkstyle locally before pushing would avoid noise.
2. No unit tests were written alongside the entities and authentication code.
3. Development paused during July and August, so Sprint 6 started with a large backlog of feature work.

## Action Items
| Action | Owner | Due |
|--------|-------|-----|
| Run `./mvnw checkstyle:check` before every push | All | Sprint 6, Week 1 |
| Write unit tests together with each new service | All | Sprint 6 |
| Agree the Sprint 6 scope and issue owners before the break ends | B. Thushakaran | Sprint 6, Week 1 |

## Metrics
- Pull requests merged: 3 (backend)
- CI pipeline: Pipeline introduced
- Test coverage: Not measured
