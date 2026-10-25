# GMC Lanka Creations — Documents

Central home for the project documentation of **GMC Lanka Creations**, a full-stack web application for a Sri Lankan CNC wood and acrylic product business. Built as the SENG 34213 capstone project at the University of Kelaniya.

**Live site:** [gmc-lanka.lk](https://gmc-lanka.lk/)

This repository holds the written artifacts only. Source code lives in the sibling repositories listed below.

## What's in here

| Folder | Contents |
| --- | --- |
| `srs/` | Software Requirements Specification (latest version plus revision history) |
| `sds/` | Software Design Specification: architecture, data model, API design |
| `adr/` | Architecture Decision Records, one file per decision |

## Related repositories

| Repository | Purpose | Stack |
| --- | --- | --- |
| [frontend](https://github.com/gmc-lanka/frontend) | Client-side application | React 18, Tailwind CSS |
| [backend](https://github.com/gmc-lanka/backend) | Server-side REST API | Spring Boot 3.x, Java 21, JWT, MySQL |
| [Infra](https://github.com/gmc-lanka/Infra) | Infrastructure as Code | Docker |
| [tests](https://github.com/gmc-lanka/tests) | Integration and end-to-end test suites | Java |
| [documents](https://github.com/gmc-lanka/documents) | Project documentation (this repo) | Markdown |

## System overview

The platform supports four user roles:

- **Guest**: browse products without an account
- **Customer**: place and track orders
- **Technician**: handle fabrication and production tasks
- **Admin**: manage products, users, and orders

## Document conventions

- **Format:** Markdown (`.md`) for everything that can be, so changes are easy to diff and review.
- **Versioning:** Record each SRS/SDS revision in a version table at the top of the file (version, date, author, summary of changes).
- **Naming:** lowercase, hyphen-separated file names, e.g. `user-authentication-design.md`.
- **ADRs:** numbered sequentially, e.g. `adr/0001-use-jwt-for-authentication.md`. Never edit an accepted ADR. Supersede it with a new one and link the two.
- **Meeting notes:** include date, attendees, agenda, decisions, and action items with owners.

## Contributing

1. Create a branch from `main`: `docs/<short-description>`.
2. Make your changes and keep each pull request focused on one document or topic.
3. Open a pull request and request review from at least one teammate.
4. Merge after approval.

Keep documents in sync with the code: if a pull request in `backend` or `frontend` changes behavior described in the SRS or SDS, update the relevant document in the same sprint.

## Team

| Name | Role |
| --- | --- |
| Thushakaran | Student developer |
| Aswini Parameswaran | Student developer |
| Keerthi Gopalavannan | Student developer |
| Tharshana Sarathchandar | Student developer |

**Supervisor:** Dr. Nalin Warnajith, University of Kelaniya

## License

This repository is part of an academic project. All rights reserved by the project team unless stated otherwise.
