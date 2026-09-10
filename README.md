# Vo Van Tu Tai (Tai Vo)

<p align="left">
  <strong>Business Analyst · Systems Analyst</strong><br>
  <em>Bridging Business Vision & Engineering Execution with Strong Technical Literacy & Domain Ownership</em>
</p>

<p align="left">
  <a href="https://vovantutai-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live%20Site-000000?style=flat-square&logo=vercel" alt="Portfolio" /></a>
  <a href="https://vovantutai-portfolio.vercel.app/VoVanTuTai_Business_Analyst_Intern_CV.pdf"><img src="https://img.shields.io/badge/Resume-BA%20CV%20(PDF)-red?style=flat-square&logo=adobe-acrobat-reader" alt="BA CV PDF" /></a>
  <a href="https://linkedin.com/in/vovantutai"><img src="https://img.shields.io/badge/LinkedIn-Vo%20Van%20Tu%20Tai-blue?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:tutaivovan@gmail.com"><img src="https://img.shields.io/badge/Email-tutaivovan%40gmail.com-critical?style=flat-square&logo=gmail" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Ho%20Chi%20Minh%20City%2C%20Vietnam-success?style=flat-square&logo=google-maps" alt="Location" />
</p>

---

## 💡 Professional Philosophy & Commitment

> *"A dedicated Business Analyst does not merely transcribe client requests into Jira tickets; they dig deep to uncover the root business problem, design resilient process workflows, evaluate technical feasibility, and take relentless ownership from the initial discovery workshop to production UAT and user onboarding."*

As a final-year **Information Systems** student at **Industrial University of Ho Chi Minh City (IUH)** with hands-on Business Analyst experience at **HomeNest Software** and frontline logistics operations at **J&T Express**, I bring a rare combination of **business empathy, operational rigor, and solid technical foundations**. 

My core mission is to eliminate ambiguity in software development: translating complex business rules into crystal-clear **PRDs, SRS, BPMN 2.0 workflows, and testable Gherkin User Stories** so that engineering teams build the right features right the first time.

---

## ⚡ Why Technical Depth is My Superpower as a BA

Having hands-on experience building and modeling software architectures (relational databases, REST APIs, microservices boundaries, state machines), I bridge the communication gap between non-technical stakeholders and developers:

- **Feasibility & Boundary Discovery:** I understand data constraints, API contract structures, and async event handoffs, preventing "technically impossible" specifications and surfacing edge cases during the requirement phase rather than in production.
- **Precision Specification (No Ambiguity):** I author User Stories paired with strict **Given-When-Then Acceptance Criteria**, detailed sequence diagrams, and data dictionaries, giving Dev and QA teams absolute clarity on *What* to build and *Why*.
- **Data & Process Integrity:** I model business logic with formal **BPMN 2.0 (Camunda)**, entity relationships (ERD in 3NF), and robust state machines, ensuring seamless lifecycle transitions (e.g., booking statuses, order lifecycles, and financial settlement reconciliations).

---

## 🛠️ Core Competencies & Toolkit

| Dimension | Key Capabilities & Methodologies | Tools & Standards |
| :--- | :--- | :--- |
| **Business Analysis & Modeling** | Requirement Elicitation, PRD & SRS Documentation, User Stories with Acceptance Criteria (Gherkin Given-When-Then), BPMN 2.0 Process Modeling, Use Case Specs, UAT Verification Matrices, Backlog Prioritization, User Manuals & Training. | **Notion**, **Jira**, **ClickUp**, **Camunda Modeler**, **Draw.io**, **Figma**, Agile / Scrum |
| **Technical Literacy & Architecture** | Relational Data Modeling (ERD, 3NF), SQL Querying, RESTful API Contracts (OpenAPI 3.0, JSON Schemas), Webhooks / IPN Protocols, State Machine Design, Idempotency & Concurrency Rules. | **Postman**, **MySQL**, **PostgreSQL**, **Git**, **GitHub**, **Docker Compose** |
| **Domain Grounding** | **Travel & Booking Platforms:** Dynamic room inventory, live availability calendars, overbooking prevention, tiered cancellation/refund policies, RBAC.<br>**Payment & Settlement:** Payment gateway integration (VNPay API), asynchronous IPN webhook reconciliation, transaction audit trails.<br>**Logistics & OMS:** End-to-end parcel lifecycles, barcode scan validation, operational data auditing, exception flow SOPs (RTO, misroutes). | E-commerce / Travel / Logistics Operations |
| **Languages** | **English:** Professional Working Proficiency (Fluent in writing technical specifications & business documentation).<br>**Vietnamese:** Native. | — |

---

## 📂 Featured Business Analysis Case Studies

### 🏨 [Tourist Accommodation Platform — Multi-Role Travel Booking System](https://github.com/VoVanTuTai/tourist-accommodation-management-system)
*Domain: Travel Tech · Online Travel Booking (OTA) · Dynamic Inventory · Payment Systems*

- **Business Problem:** Resolving operational conflicts among 3 distinct stakeholder groups (Guests, Accommodation Hosts, Platform Admins) sharing room inventory and booking records while preventing double-booking during peak traffic surges.
- **Key BA Deliverables & Solutions:**
  - **Multi-Stakeholder Alignment & RBAC:** Mapped end-to-end user journeys and drafted a strict Role-Based Access Control matrix separating Guest discovery/checkout, Host room inventory/seasonal pricing, and Admin moderation/commission settlement.
  - **Concurrency Control & Overbooking Prevention:** Designed atomic reservation logic and dynamic availability states (`Available`, `Held/Pending Payment`, `Booked`, `Blocked`) to eliminate race conditions.
  - **Booking State Machine & Tiered Refund Policy:** Formulated a resilient booking lifecycle (`Pending Payment` → `Confirmed` → `Checked-in` → `Completed` / `Cancelled`) with automated tiered refund rules calculated dynamically against cancellation windows based on cancellation timeframes to protect host occupancy while providing guest flexibility.
  - **Payment Gateway Integration & Order Settlement:** Specified API contracts for **VNPay API** (payment URL creation, asynchronous IPN webhook validation, callback verification), handling timeout compensations and automated invoice generation.
- **Tech & Tools:** Express.js, MySQL, Sequelize, VNPay API, Draw.io, OpenAPI.

---

### 📦 [Nexus Express — Logistics & Order Management System (OMS)](https://github.com/VoVanTuTai/logistics-management-system)
*Domain: Logistics & Supply Chain · Order Management (OMS) · Microservices Architecture*

- **Business Problem:** Fragmented parcel ownership across merchants, branch staging, sorting hubs, and last-mile couriers created tracking blind spots, delayed deliveries, and financial discrepancies in Cash on Delivery (COD).
- **Key BA Deliverables & Solutions:**
  - **Ground-Truth Process Modeling:** Transferred 6 months of hands-on J&T Express operational experience into complete **BPMN 2.0** workflows in Camunda Modeler, covering package intake, barcode checkpoints, staging, and courier dispatch.
  - **Order State Machine & Exception SOPs:** Specified parcel state lifecycles (`Pending` → `In Transit` → `Out for Delivery` → `Delivered` / `RTO`) and formulated standard procedures for failure flows: misroutes, transit delays, and customer address re-routing.
  - **3-Way Financial Reconciliation:** Modeled COD settlement workflows (physical cash collected vs. courier delivery receipts vs. digital ledger) to ensure zero financial discrepancies.
  - **Contract-First Architecture:** Authored OpenAPI 3.0 specifications for 12 domain microservices behind an API Gateway, defining event schemas and idempotency rules to prevent duplicate billing.
- **Tech & Tools:** Camunda Modeler, BPMN 2.0, OpenAPI 3.0, PostgreSQL, Prisma, NestJS, RabbitMQ, Docker.

---

### 🚖 [Cab Booking System — Distributed Ride-Hailing Platform](https://github.com/VoVanTuTai/cab-booking-system)
*Domain: Mobility Tech · Real-Time Matching · Dynamic Pricing · Asynchronous Architecture*

- **Business Problem:** Ride-hailing platforms require high-throughput coordination between passenger ride requests, dynamic vehicle availability, surge pricing calculations, and payment settlements without state desynchronization.
- **Key BA Deliverables & Solutions:**
  - **State Transitions & Business Rules:** Mapped passenger-driver matching workflows, vehicle availability states, surge pricing calculation algorithms, and ride cancellation compensation paths using sequence and state diagrams.
  - **API Contract Specifications & Postman Verification:** Authored 12 OpenAPI 3.0 service contracts and developed 10 Postman test collections with 100+ automated verification test scenarios covering boundary conditions, payload validation, and timeout compensations.
- **Tech & Tools:** OpenAPI 3.0, Postman, Sequence Diagrams, Node.js, Express, Kafka, Redis, PostgreSQL.

---

## 💼 Work Experience

#### **HomeNest Software** — *Business Analyst Intern · PM Assistant*
*Jun 2026 – Sep 2026 · Ho Chi Minh City, Vietnam*
- **Requirement Elicitation & PRD/SRS Documentation:** Spearheaded discovery workshops with internal teams and external stakeholders; analyzed business pain points, structured Meeting Minutes (MoM), and authored comprehensive PRD/SRS specifications detailing functional workflows and business rules.
- **User Stories & Acceptance Criteria (Gherkin):** Decomposed business needs into prioritized Epics and granular User Stories with testable **Given-When-Then** Acceptance Criteria, ensuring engineering clarity on both "What" to build and "Why".
- **Product Manager Collaboration & Backlog Governance:** Partnered closely with the Product Manager to manage and groom the product backlog in **Notion / Jira**, evaluate sprint release readiness, and conduct sprint demo sessions for business stakeholders.
- **Dev/QA Support & UAT Verification:** Served as the primary liaison for Dev/QA teams to clarify business logic; defined data schemas (ERD/API contracts), authored structured UAT verification matrices, and resolved logic blockers during implementation.
- **User Onboarding & Training:** Authored intuitive user manuals and standard operating procedures (SOPs), facilitating interactive onboarding and training sessions for internal operations and client teams.

#### **J&T Express** — *Logistics Operations Staff (Full-time)*
*Sep 2025 – Feb 2026 · Ho Chi Minh City, Vietnam*
- **End-to-End Process Analysis & Bottleneck Elimination:** Mapped and analyzed physical branch workflows handling 300+ daily parcels across intake, dimensional weighing, barcode checkpoints, and courier dispatch, identifying staging bottlenecks to optimize throughput.
- **Exception Flows & Root Cause Analysis (RCA):** Formulated standardized procedures (SOPs) for operational failure modes: package misroutes, transit delays, damaged goods claims, address re-routing, and Return to Origin (RTO).
- **Physical-to-Digital Status Consistency:** Conducted daily cross-checks between signed physical delivery sheets and digital software logs, ensuring parcel tracking statuses remained transparent and synchronized.
- **Domain-to-System Functional Translation:** Transferred operational pain points, scan validation rules, and parcel state machine lifecycles into functional requirements and ERDs for order management software.

---

## 🎓 Education & Credentials

- **Industrial University of Ho Chi Minh City (IUH)**
  - *Bachelor of Science in Information Systems* (Sep 2022 – Present · Expected 2027)
  - **GPA:** **3.26 / 4.0**
  - **Relevant Coursework:** Systems Analysis & Design, Database Systems, Software Engineering, Web Development, Data Structures & Algorithms, Service-Oriented Architecture.

---

## 📬 Connect With Me

I am actively seeking opportunities as a **Business Analyst (Fresher) / Systems Analyst**, particularly within tech-driven domains like **Travel Tech, Booking Platforms, E-commerce, and Order Management Systems (OMS)**.

- 🌐 **Portfolio Website:** [vovantutai-portfolio.vercel.app](https://vovantutai-portfolio.vercel.app)
- 📄 **Business Analyst CV (PDF):** [Download Official CV](https://vovantutai-portfolio.vercel.app/VoVanTuTai_Business_Analyst_Intern_CV.pdf)
- 💼 **LinkedIn:** [linkedin.com/in/vovantutai](https://linkedin.com/in/vovantutai)
- 📧 **Email:** [tutaivovan@gmail.com](mailto:tutaivovan@gmail.com)
- 📞 **Phone:** [+84 869 500 573](tel:+84869500573)

---

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=VoVanTuTai&theme=github" alt="Vo Van Tu Tai GitHub contribution summary" />
</p>
