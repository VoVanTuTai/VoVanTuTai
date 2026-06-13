# Vo Van Tu Tai

**Backend-focused Information Systems Student | Business Workflows & Technical Analysis**

Information Systems student at Industrial University of Ho Chi Minh City (IUH), seeking a **Backend / Full-stack Developer Internship**. I build business systems across backend, API, database, and web layers using PHP, Node.js/TypeScript, MySQL/PostgreSQL, and Docker. My understanding of workflows, requirements, and logistics operations helps me design software around real users, rules, and edge cases.

[Portfolio](https://vovantutai-portfolio.vercel.app) |
[Developer CV](https://raw.githubusercontent.com/VoVanTuTai/portfolio/feature/academic-skill-pages/public/VoVanTuTai_Backend_Fullstack_Intern_CV.pdf) |
[Business Analyst CV](https://raw.githubusercontent.com/VoVanTuTai/portfolio/feature/academic-skill-pages/public/VoVanTuTai_Business_Analyst_Intern_CV.pdf) |
[LinkedIn](https://linkedin.com/in/vovantutai) |
[Email](mailto:tutaivovan@gmail.com) |
Phone: +84 869 500 573

## Engineering Focus

- Build backend and full-stack applications with authentication, authorization, relational data, reporting, and role-based workflows.
- Design REST APIs, service boundaries, database ownership, and asynchronous workflows from explicit business requirements.
- Trace failures across UI, API, service, and data layers instead of treating features in isolation.
- Make projects reproducible through Docker Compose, seed data, tests, API contracts, and technical documentation.

## Technical Profile

| Area | Evidence-based experience |
| --- | --- |
| Backend and API | PHP, Node.js, Express/EJS, REST APIs, authentication, authorization, validation |
| Languages | PHP, JavaScript, TypeScript; Java 21 foundation |
| Data | MySQL, PostgreSQL, SQL, Prisma, JPA, Flyway; MongoDB and Redis project exposure |
| Architecture | NestJS, Gateway/BFF, RabbitMQ, Kafka, database-per-service, outbox and idempotency concepts |
| Frontend | HTML/CSS, Bootstrap, EJS, React/Vite project work |
| Delivery | Git, GitHub, Postman, Docker Compose, MockMvc, OpenAPI, repository documentation |

## Selected Engineering Case Studies

### [Nexus Express System](https://github.com/VoVanTuTai/logistics-management-system)

**Problem:** Shipment status, scan location, tracking, reporting, and COD can become ambiguous when several teams and services touch the same shipment.

**Engineering work:** Organized 12 domain services behind a Gateway/BFF; modeled PostgreSQL/Prisma ownership, RabbitMQ events, OpenAPI contracts, outbox/idempotency patterns, and Docker infrastructure.

**Analysis advantage:** Used first-hand J&T Express experience to define actors, shipment states, scan points, exception paths, COD flows, and source-of-truth boundaries before mapping them to services.

**Stack:** TypeScript, NestJS, React/Vite, PostgreSQL, Prisma, RabbitMQ, Docker

### [Tourist Accommodation Management System](https://github.com/VoVanTuTai/tourist-accommodation-management-system)

**Problem:** Customer, provider, and administrator journeys share accommodation and booking data but require different permissions and business rules.

**Engineering work:** Built Express/EJS/MySQL screens, session authentication, role guards, booking management, VNPay/QR pages, email support, dashboards, and PDF/Excel exports.

**Analysis advantage:** Separated customer, provider, and administrator rules for availability, booking, payment, cancellation, review, moderation, and commission reporting.

**Stack:** Node.js, Express.js, EJS, MySQL, Sequelize

### [Song Tai Shop](https://github.com/VoVanTuTai/php-online-store)

**Problem:** A legacy student project was difficult to run consistently and needed clearer authorization and safer destructive operations.

**Engineering work:** Added role checks, password hashing, safer output/database handling, POST-based deletion, Docker Compose, seed data, and demo documentation.

**Analysis advantage:** Reviewed customer/admin permissions, checkout and order states, and control gaps before changing the legacy workflows.

**Stack:** PHP, MySQL, Bootstrap, JavaScript, Docker Compose

### [DevFlow - Current Build](https://github.com/VoVanTuTai/devflow)

Building a project and task management system to strengthen Java backend fundamentals. The current foundation includes a PostgreSQL schema for users, projects, members, tasks, comments, and activity logs; JPA entities and auditing; Flyway migration; shared API/error responses; and focused MockMvc tests.

**Stack:** Java 21, Spring Boot, JPA, Flyway, PostgreSQL, React/Vite

## Additional Architecture Practice

[Cab Booking System](https://github.com/VoVanTuTai/cab-booking-system) explores ride, driver, pricing, payment, notification, and review workflows using REST/event contracts, Kafka, Redis, multiple databases, reliability patterns, and Docker-based observability.

## Business Analysis Advantage

Business analysis is a supporting engineering skill in my profile. I use it to reduce ambiguity before implementation and to keep code aligned with operational behavior.

| Capability | Engineering benefit |
| --- | --- |
| Requirements and business rules | Clarify actors, permissions, preconditions, exceptions, and acceptance-ready outcomes |
| Process and state modeling | Make multi-step workflows and invalid transitions explicit before coding |
| Data analysis | Define entities, validation rules, relationships, reporting needs, and source-of-truth ownership |
| Technical analysis | Connect screens and business behavior to APIs, services, databases, and events |
| Validation | Build happy-path and edge-case scenarios, review gaps, and trace results back to evidence |

**Methods and tools:** use cases, functional requirements, acceptance criteria, as-is/to-be workflows, sequence/state diagrams, ERD, BPMN/UML familiarity, Mermaid, Draw.io, Postman, SQL, OpenAPI, Jira and Figma familiarity.

### Analysis Evidence

- [System scope and ownership](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/PROJECT-OVERVIEW.md)
- [End-to-end shipment lifecycle](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/order-lifecycle-report.md)
- [Operations sequence diagrams](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/ops-staff-mermaid-code.md)
- [Merchant sequence and state diagrams](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/merchant-mermaid-code.md)
- [OpenAPI contracts](https://github.com/VoVanTuTai/logistics-management-system/tree/main/contracts/openapi)
- [Operations readiness and gap analysis](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/ops-web-production-readiness-report.md)
- [80-scenario test and gap report](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/Nexus-Express-Test-Case-Report-Applicable-After-Fix.docx)

## Experience And Education

- **Post Office Operations Staff, J&T Express:** full-time, December 29, 2025 - March 31, 2026
- **Bachelor of Information Systems, IUH:** 2022 - Present, GPA 3.22/4.0, expected graduation 2027
- **Location:** Ho Chi Minh City, Vietnam

## GitHub Activity

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=VoVanTuTai&theme=github" alt="Vo Van Tu Tai GitHub contribution summary" />
</p>
