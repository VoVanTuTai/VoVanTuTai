# Vo Van Tu Tai

**Backend / Full-stack Developer Intern | Technical Business Analyst Intern**

Information Systems student at Industrial University of Ho Chi Minh City (IUH), building business systems across backend, web, API, and data layers. I combine software implementation with process and data analysis, strengthened by hands-on logistics operations experience at J&T Express.

[Portfolio](https://vovantutai-portfolio.vercel.app) |
[Developer CV](https://raw.githubusercontent.com/VoVanTuTai/portfolio/feature/academic-skill-pages/public/VoVanTuTai_Backend_Fullstack_Intern_CV.pdf) |
[Business Analyst CV](https://raw.githubusercontent.com/VoVanTuTai/portfolio/feature/academic-skill-pages/public/VoVanTuTai_Business_Analyst_Intern_CV.pdf) |
[LinkedIn](https://linkedin.com/in/vovantutai) |
[Email](mailto:tutaivovan@gmail.com) |
Phone: +84 869 500 573

## What I Bring

- Build working business applications across UI, backend, authentication, relational data, and reporting.
- Translate operational problems into actors, workflows, business rules, data models, and API contracts.
- Trace edge cases across screens, services, and data ownership instead of treating features in isolation.
- Make projects reviewable through Docker Compose, seed data, tests, diagrams, and clear documentation.

## Business Analysis Profile

| Capability | How I apply it |
| --- | --- |
| Requirements analysis | Identify actors, goals, functional scope, business rules, preconditions, exceptions, and acceptance-ready outcomes |
| Process modeling | Map as-is operations and to-be system flows using use cases, sequence diagrams, state transitions, and BPMN/UML concepts |
| Data analysis | Define entities, relationships, field meanings, validation rules, ownership boundaries, and reporting requirements |
| Product thinking | Separate MVP scope from future enhancements and evaluate workflows from user, operations, and system perspectives |
| Technical analysis | Read source code, databases, REST/OpenAPI contracts, and events to keep requirements feasible and traceable |
| Validation and handoff | Review edge cases, prepare test scenarios, document decisions, and connect business behavior to implementation evidence |

### Methods And Tools

- **Requirements:** use cases, functional requirements, business rules, acceptance criteria, permissions, and exception paths
- **Modeling:** as-is/to-be workflows, sequence and state diagrams, ERD, BPMN/UML familiarity, Mermaid, and Draw.io
- **Validation:** Postman, SQL, source review, test scenarios, gap analysis, and regression evidence
- **Collaboration:** OpenAPI, GitHub documentation, technical handoff, plus Jira and Figma familiarity for backlog and UI-flow work

### How I Approach A BA Problem

1. **Understand the current operation:** identify users, goals, pain points, manual steps, and terminology.
2. **Define scope and rules:** separate required behavior, exceptions, permissions, states, and out-of-scope items.
3. **Model the solution:** create process flows, use cases, data relationships, state transitions, and system boundaries.
4. **Align with implementation:** map screens and requirements to APIs, services, databases, and integration contracts.
5. **Validate the result:** check happy paths and edge cases through working software, test scenarios, and repository documentation.

## Software Engineering Profile

| Area | Evidence-based experience |
| --- | --- |
| Application development | PHP, JavaScript, Node.js, Express/EJS, HTML/CSS, Bootstrap, MySQL, REST APIs |
| Architecture projects | TypeScript, NestJS, React/Vite, PostgreSQL, Prisma, RabbitMQ, Kafka, Redis, Docker |
| Current Java foundation | Java 21, Spring Boot, JPA, Flyway, PostgreSQL, MockMvc |
| Delivery tools | Git, GitHub, Postman, Docker Compose, repository documentation |

## BA Evidence And Artifacts

The strongest public evidence comes from **Nexus Express**, where I applied first-hand logistics operations knowledge to system analysis and documentation:

| Artifact | What it demonstrates |
| --- | --- |
| [Project overview](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/PROJECT-OVERVIEW.md) | Problem context, actors, functional scope, service responsibilities, workflows, data ownership, and system constraints |
| [Shipment lifecycle analysis](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/order-lifecycle-report.md) | End-to-end process analysis from order creation through pickup, hub, delivery, exception, return, and COD |
| [Data ownership model](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/PROJECT-OVERVIEW.md#11-data-ownership) | Source-of-truth decisions and boundaries between transactional services and reporting/tracking read models |
| [Operations sequence diagrams](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/ops-staff-mermaid-code.md) | Actor interactions, validations, alternate paths, and service handoffs for operations workflows |
| [Merchant sequence and state diagrams](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/merchant-mermaid-code.md) | User journeys, status transitions, payment/COD flows, and exception scenarios |
| [OpenAPI contracts](https://github.com/VoVanTuTai/logistics-management-system/tree/main/contracts/openapi) | Traceability from functional behavior to request, response, validation, and integration boundaries |
| [Operations readiness review](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/ops-web-production-readiness-report.md) | Gap analysis separating production-like core workflows from prototypes and future scope |
| [Test-case and gap report](https://github.com/VoVanTuTai/logistics-management-system/blob/main/docs/Nexus-Express-Test-Case-Report-Applicable-After-Fix.docx) | 80 applicable scenarios covering core flows, validation, integration, consistency, security, deployment, resilience, and remaining gaps |

## Selected Case Studies

### [Nexus Express System](https://github.com/VoVanTuTai/logistics-management-system)

**Problem:** Shipment status, scan location, tracking, reporting, and COD can become ambiguous when several teams and services touch the same shipment.

**BA contribution:** Converted branch operations into actors, business flows, exception paths, state transitions, reporting needs, and source-of-truth decisions.

**Technical contribution:** Organized 12 domain services behind a Gateway/BFF and documented HTTP/event handoffs, database ownership, and reliability patterns.

**Evidence:** Five client apps, OpenAPI contracts, Prisma models, RabbitMQ events, outbox/idempotency patterns, Docker infrastructure, and system documentation.

**Stack:** TypeScript, NestJS, React/Vite, PostgreSQL, Prisma, RabbitMQ, Docker

### [Tourist Accommodation Management System](https://github.com/VoVanTuTai/tourist-accommodation-management-system)

**Problem:** Customer, provider, and administrator journeys share accommodation and booking data but require different permissions and business rules.

**BA contribution:** Separated role-based journeys and defined rules for availability, booking, payment, cancellation, review, moderation, dashboards, and commission reporting.

**Technical contribution:** Translated those flows into session authentication, route guards, database-backed screens, and report exports.

**Evidence:** Working Express/EJS/MySQL screens, session authentication, role guards, VNPay/QR pages, email support, dashboards, and PDF/Excel exports.

**Stack:** Node.js, Express.js, EJS, MySQL, Sequelize

### [Song Tai Shop](https://github.com/VoVanTuTai/php-online-store)

**Problem:** A legacy student project was difficult to run consistently and needed clearer authorization and safer destructive operations.

**BA contribution:** Reviewed customer/admin use cases, permissions, checkout/order states, and control gaps.

**Technical contribution:** Added role checks, password hashing, safer output/database handling, POST-based deletion, Docker Compose, seed data, and demo documentation.

**Evidence:** Reproducible PHP/MySQL setup with customer checkout, order tracking, and admin product/order workflows.

**Stack:** PHP, MySQL, Bootstrap, JavaScript, Docker Compose

### [DevFlow - Current Build](https://github.com/VoVanTuTai/devflow)

Building a project and task management system to strengthen Java backend fundamentals. The current foundation includes a PostgreSQL schema for users, projects, members, tasks, comments, and activity logs; JPA entities and auditing; Flyway migration; shared API/error responses; and focused MockMvc tests.

**Stack:** Java 21, Spring Boot, JPA, Flyway, PostgreSQL, React/Vite

## Additional Architecture Practice

[Cab Booking System](https://github.com/VoVanTuTai/cab-booking-system) explores ride, driver, pricing, payment, notification, and review workflows using REST/event contracts, Kafka, Redis, multiple databases, reliability patterns, and Docker-based observability.

## Experience And Education

- **Post Office Operations Staff, J&T Express:** full-time, December 29, 2025 - March 31, 2026
- **Bachelor of Information Systems, IUH:** 2022 - Present, GPA 3.22/4.0, expected graduation 2027
- **Location:** Ho Chi Minh City, Vietnam

## GitHub Activity

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=VoVanTuTai&theme=github" alt="Vo Van Tu Tai GitHub contribution summary" />
</p>
