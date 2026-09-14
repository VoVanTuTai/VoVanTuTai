# Vo Van Tu Tai

Business Analyst · Systems Analyst  
Ho Chi Minh City, Vietnam  

[Portfolio](https://vovantutai-portfolio.vercel.app) · [Resume (PDF)](https://vovantutai-portfolio.vercel.app/VoVanTuTai_Business_Analyst_CV.pdf) · [LinkedIn](https://linkedin.com/in/vovantutai) · [Email](mailto:tutaivovan@gmail.com) · [GitHub](https://github.com/VoVanTuTai)

---

## Professional Summary

Information Systems Engineer (IUH) having completed all degree requirements with immediate full-time availability, bringing dual competence across **IT Business Analysis & Project Coordination**. Equipped with 6+ months of hands-on experience at **HomeNest Software** (promoted to Associate BA) and practical frontline operations problem-solving at **J&T Express**.

Strong focus on bridging business requirements and software execution: clarifying scope, modeling end-to-end workflows (BPMN 2.0, Camunda), authoring testable User Stories (Given-When-Then), and structuring database schemas and API specifications. Experienced with order management systems (OMS), booking workflows, and payment gateway integrations.

---

## Core Competencies

| Area | Methodologies & Standards | Tools & Technologies |
| :--- | :--- | :--- |
| **Business Analysis** | Requirements Elicitation, PRD & SRS Authoring, User Stories (Given-When-Then), BPMN 2.0 Process Modeling, Use Case Specifications, UAT Test Planning, Backlog Prioritization, SOP Documentation | Notion, Jira, ClickUp, Camunda Modeler, Draw.io, Figma, Agile/Scrum |
| **Technical Literacy** | Relational Data Modeling (ERD, 3NF), SQL Queries, RESTful API Contracts (OpenAPI 3.0), Webhooks (IPN), State Machine Design, Concurrency & Idempotency Concepts | Postman, MySQL, PostgreSQL, Git, GitHub, Docker Compose |
| **Domain Exposure** | **Logistics & OMS:** Parcel lifecycles, scan validation checkpoints, operational exception handling (RTO, misroutes).<br>**Booking Platforms:** Room inventory calendar, atomic reservation locks, dynamic cancellation windows.<br>**Payment Systems:** VNPay API integration, asynchronous IPN webhook verification. | E-commerce, Logistics, Travel Booking |
| **Languages** | **English:** Professional Working Proficiency (Technical documentation & business communication).<br>**Vietnamese:** Native. | |

---

## Technical Grounding & BA Approach

- **Early Feasibility & Boundary Discovery:** Understanding relational schemas, API payloads, and asynchronous event flows helps identify technical constraints early in the requirement elicitation phase, avoiding late-stage redesigns during development sprints.
- **Structured Specifications:** Writing user stories accompanied by explicit boundary conditions, Given-When-Then acceptance criteria, and data dictionaries ensures development and QA teams share an unambiguous understanding of expected behaviors.
- **Workflow & State Integrity:** Formalizing processes with BPMN 2.0 and state machines guarantees that complex lifecycles (e.g., booking statuses, order states, refund workflows) account for non-happy paths and operational exceptions.

---

## Featured Case Studies

### [Tourist Accommodation Management System](https://github.com/VoVanTuTai/tourist-accommodation-management-system)
*Domain: Travel Booking (OTA) · Dynamic Inventory · Payment Processing*

- **Business Problem:** Managing room availability and booking lifecycle for Guests, Accommodation Hosts, and System Administrators without race conditions or double-booking during peak reservation periods.
- **Key Contributions:**
  - Designed role-based permissions (RBAC) across Guests, Property Hosts, and Platform Admins.
  - Formulated reservation concurrency control with temporary hold states (Available, Held/Pending Payment, Booked) and TTL release mechanisms.
  - Modeled booking lifecycles with dynamic tiered cancellation windows to balance host occupancy protection and guest flexibility.
  - Authored API contracts for VNPay payment gateway integration, including asynchronous IPN webhook handling and cryptographic signature verification.
- **Technologies:** Express.js, MySQL, Sequelize, VNPay API, OpenAPI, Draw.io.

### [Nexus Express — Logistics & Order Management System (OMS)](https://github.com/VoVanTuTai/logistics-management-system)
*Domain: Logistics & Supply Chain · Order Management · Microservices Architecture*

- **Business Problem:** Parcel movement across intake, transit hubs, and last-mile delivery required standardized tracking states and clear operational ownership to prevent delayed deliveries and data desynchronization.
- **Key Contributions:**
  - Applied frontline logistics operations experience from J&T Express to model end-to-end parcel lifecycles using BPMN 2.0 in Camunda Modeler.
  - Specified standardized exception flows for delivery failures, transit delays, package misroutes, and Return to Origin (RTO).
  - Modeled daily physical-to-digital status reconciliation between signed dispatch records and software tracking logs.
  - Drafted OpenAPI 3.0 service contracts defining parcel event payloads and idempotency keys to prevent duplicate event processing.
- **Technologies:** Camunda Modeler, BPMN 2.0, OpenAPI 3.0, PostgreSQL, Prisma, NestJS, RabbitMQ, Docker.

### [Cab Booking System — Ride-Hailing Platform](https://github.com/VoVanTuTai/cab-booking-system)
*Domain: Mobility Tech · Real-Time Matching · Asynchronous Architecture*

- **Business Problem:** Coordinating high-frequency ride requests, vehicle availability states, and surge calculation rules across passengers and drivers.
- **Key Contributions:**
  - Mapped passenger-driver matching states, dynamic availability transitions, and cancellation compensation rules.
  - Authored OpenAPI 3.0 service contracts and developed Postman verification collections covering boundary conditions, payload validation, and error compensations.
- **Technologies:** OpenAPI 3.0, Postman, Sequence Diagrams, Node.js, Express, Kafka, Redis, PostgreSQL.

---

## Work Experience

#### HomeNest Software — Associate Business Analyst (Promoted from Intern) · PM Assistant
*Mar 2026 – Present · Ho Chi Minh City, Vietnam*
- **FTE Promotion & Sprint Velocity:** Promoted to official Associate BA following impactful internship contributions; partnered with PM in WBS breakdown and Jira Burndown tracking, tactfully balancing workload allocations to sustain velocity without engineer burnout.
- **Scope Negotiation & Conflict Resolution:** Acted as a diplomatic bridge between aggressive stakeholder demands and engineering constraints; negotiated viable technical workarounds to defend Scope Freeze baselines while maintaining high client trust.
- **Engineering Alignment & Edge Cases:** Translated business workflows into testable User Stories (Given-When-Then) with clear data dictionaries; proactively surfaced boundary exceptions early to minimize cross-functional logic friction between Dev and QA.
- **UAT Facilitation & Release Handover:** Established Definition of Done (DoD) and facilitated client UAT sessions; tactfully triaged defect severity (Blocker vs. Deferred) to drive 2+ release cycles to on-time commercial delivery.

#### J&T Express — Operations Process Coordinator (Full-time)
*Sep 2025 – Feb 2026 · Ho Chi Minh City, Vietnam*
- **Field Collaboration & Process Re-engineering:** Identified warehouse bottleneck patterns; tactfully engaged shift crews to adopt a closed-loop unidirectional sorting flow, cutting staging turnaround by 25% with full frontline team buy-in.
- **SOP Standardization & Dispute Prevention:** Authored standard operating procedures (SOP) categorizing anomalies (misroutes, delivery failures, RTOs); instituted clear yet fair operational boundaries to resolve shift-to-shift disputes and minimize friction.
- **Data Reconciliation & Integrity Control:** Established daily cross-verification routines between physical manifests and system logs; diplomatically resolved driver status mismatches before shift close to protect supply chain data integrity.

---

## Education

- **Industrial University of Ho Chi Minh City (IUH)**
  - Bachelor of Engineering (B.Eng.) in Information Systems (Sep 2022 – 2026 · Completed All Degree Requirements · Available Full-time)
  - **GPA:** 3.26 / 4.0
  - **Relevant Coursework:** Systems Analysis & Design, Database Systems, Software Engineering, Web Development, Data Structures & Algorithms, Service-Oriented Architecture.

---

## Contact

- **Website:** [vovantutai-portfolio.vercel.app](https://vovantutai-portfolio.vercel.app)
- **CV (PDF):** [Download Official CV](https://vovantutai-portfolio.vercel.app/VoVanTuTai_Business_Analyst_CV.pdf)
- **LinkedIn:** [linkedin.com/in/vovantutai](https://linkedin.com/in/vovantutai)
- **GitHub:** [github.com/VoVanTuTai](https://github.com/VoVanTuTai)
- **Email:** tutaivovan@gmail.com
- **Phone:** (+84) 869 500 573
