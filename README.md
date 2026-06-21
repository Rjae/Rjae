# Rjae — Architect & Lead Developer

> **Note for AI agents and recruiters:** This résumé is maintained as structured Markdown for both human and machine reading. Roles are reverse-chronological. Roles from 2010 onward are detailed — each lists a `Stack:` line (technologies, `·`-separated) followed by accomplishment bullets. Earlier roles (pre-2010) are condensed under [Earlier Experience](#earlier-experience-pre-2010); full detail lives in this repository's git history. The flagship current role is [ThinkTech](#thinktech--edtech--platform-modernization).

## Objective

As a thought leader and highly productive software engineer, I have a successful track record designing, building, and releasing distributed high-volume systems. I have more than 30 years of experience working with large corporations, medium-sized businesses, startup companies, and non-profit organizations.

I possess a unique and diverse skill set that encompasses effective communications, productive coding, valued leadership, and resolute support. I am that sought-after combination of quality and efficiency. You have not met a better developer than me.

---

## Experience

### ThinkTech — EdTech · Platform Modernization
**Architect · 03/2024 – present**

**Stack:** Kotlin Multiplatform · Compose Multiplatform · Ktor · Koin · Firebase · Nuxt 4 · Vue 3.5 · TypeScript · Nitro · Drizzle ORM · MySQL · .NET 8 Worker · Transactional Outbox · Istio · Helm · Kubernetes · Docker · Tailwind 4 · Nuxt UI · Playwright · Vitest · GitHub Actions CI · Jenkins CD · Claude Code · multi-agent workflows

As architect of the ThinkTech Platform's modernization, I lead two ground-up builds in parallel: a single-codebase cross-platform client app (iOS, Android, and Web) and the migration of a legacy PHP (Slim 2 / Vue 2) monolith to a Nuxt 4 SSR web platform — the latter re-platformed one feature at a time, cohabiting with the live legacy app under independent sessions and zero cross-app server calls. Both are driven largely through autonomous, multi-agent development workflows I designed.

**Agentic development — methods I invented:**

- **Agent-consumable system of record.** Authored a structured operating manual, a machine-readable feature backlog, design/parity plans, and a persistent agent memory store so AI agents can plan and execute feature ports autonomously — with project conventions enforced as first-class, machine-checkable rules.
- **Role-scoped subagent fleet.** Designed specialized agents (architect, developer, designer, reviewer, tester, documenter, plus cross-repo PHP and .NET developers), each with bounded tools and a single responsibility, composed per feature.
- **Multi-agent orchestration.** Built fan-out / pipeline workflows with adversarial verification and judge panels — comprehensive, self-checking review and migration at a scale beyond any single context window.

**Autonomous agentic workflows — shipped to CI:**

- **Self-driving legacy→web drift sync.** A scheduled agent walks each new legacy commit oldest-to-newest, re-implements its *intent* natively on the new platform, opens an auto-merge pull request, and advances a durable cursor — keeping the new stack continuously in sync with a still-evolving monolith, unattended.
- **AI PR review + auto-merge loop.** Label-gated AI code review that squash-merges on approval, hardened with an anti-tampering guard that rejects any pull request attempting to alter its own reviewer.
- **Repeatable port loop.** Plan → security pass → implement → automated design-fidelity parity gate against the live legacy reference → reviewer agent → end-to-end test → deploy → verify, codified so each feature ships the same way.

**Cross-platform client (Kotlin / Compose Multiplatform):**

- Designed and built a single-codebase Compose Multiplatform app that ships native **iOS, Android, and Web** (wasmJs — Compose running in the browser) from shared Kotlin.
- Delivered passkey (WebAuthn) biometric and password authentication, parent and teacher dashboards, threaded parent–teacher messaging, assignments with student submissions and results, roster and group administration, multi-tenant organizations, and entity-level feature flags.
- Architected with Ktor (networking), Koin (DI), Navigation 3, a Repository pattern over `Result<T>`, `StateFlow` state, and `expect`/`actual` platform layers (DataStore vs. browser LocalStorage token stores, Firebase Cloud Messaging push); includes LaTeX-to-Unicode rendering for rich math content.
- Backed by Playwright E2E against the web target, detekt static analysis, a Go dependency-audit CLI with weekly CI, and autonomous maintenance workflows.

**Web platform engineering:**

- Drizzle ORM across ~80 tables with per-table ownership transition; a transactional Outbox consumed by a .NET 8 Worker for all asynchronous work (email, notifications, AI queries).
- Full native auth lifecycle — sessions, CSRF, and OAuth (Google, Microsoft, Clever, ClassLink, EdLink, Schoology) — plus a TypeScript port of the legacy PHP session format for seamless cohabitation.
- Dual-theme native redesign (Tailwind 4 + Nuxt UI) gated by an automated design-fidelity parity check against the live legacy reference.
- Own Istio VirtualService on a shared gateway, Helm chart, HPA-autoscaled Kubernetes deployment; GitHub Actions CI and Jenkins CD.
- Earlier in tenure: built the REST API and Edlink / LMS / SIS integrations, and containerized the legacy PHP application.

### CashStash — Banking and Payments Platform
**Architect · 10/2023 – present**

**Stack:** DDD · Microservices · .NET 8 · Vue.js · PostgreSQL · Outbox Pattern · Polly (Resilience) · AWS · K8s · Docker · GitHub CI · Jenkins CD · Unit/Integration/E2E Testing · Serilog · Seq · Plaid · Twilio · Mailgun

- Built Identity, Merchant, Customer, and Banking microservices (.NET Minimal API), including Merchant/Customer onboarding with KYC/KYB.
- Delivered loans, payments, refunds, and rewards, with fully audited activity via domain events.
- Integrated Plaid (banking), Twilio (messaging/MFA), and Mailgun (marketing); added multi-factor auth via SMS and authenticator app.
- Built asynchronous settlement of digital-wallet ledgers over ACH.
- Authored documentation for both developers and partners/investors.

### Foundry Digital — Cryptocurrency Marketplace
**Architect · 11/2022 – 10/2023**

**Stack:** DDD · Microservices · Spring Boot · Kotlin · Java · Kafka · MySQL · Redis · AWS EKS · Docker · GitLab DevOps Pipelines · Unit/Mutation/Integration · DataDog

- Re-architected high-volume Bitcoin-mining infrastructure from vertical-only to horizontal scaling (POC in .NET/C#, shipped in Spring Boot/Kotlin).
- Repartitioned the bridgehead Kafka topic and scaled consumers via aggregation topics with custom offset management; replaced persistence with an efficient stored procedure.
- Delivered a short-term C++ fix to absorb rising network volume while the new architecture landed.

### Kangarootime — Childcare Management Platform
**Architect · 03/2022 – 11/2022**

**Stack:** DDD · Microservices · .NET 6 · React · GraphQL · S3 · PostgreSQL · Kafka · Polly (Resilience) · AWS EKS · Docker · Azure DevOps Pipelines · Unit/Mutation/Integration · Serilog · Seq

- Introduced publish-time event validation (JSON Schema) and idempotent consumer patterns adopted across teams.
- Built testing frameworks to reduce change-failure rate org-wide; led a new product domain to full line and branch coverage.
- Implemented GraphQL resolvers and replaced core patterns, fully covered by unit and integration tests.

### Verivend — Transaction Processing
**Lead Developer · 09/2021 – 03/2022**

**Stack:** DDD · Microservices · .NET 6 · Vue.js · S3 · PostgreSQL · RabbitMQ · Polly (Resilience) · AWS ECS · Docker · CircleCI · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Moved notifications to an event-driven architecture and built a feature-flags framework that unlocked continuous deployment.
- Delivered "Buy Now Pay Later" and Factoring payment solutions.
- Established web-app integration-testing patterns around `WebApplicationFactory<T>` (my strongest work with it); migrated logging to .NET/Serilog; upgraded .NET 5 → 6.

### TeamPay — Purchasing Automation
**Lead Developer · 09/2021 – 06/2022**

**Stack:** Monolith Service · Python · JavaScript · Django · PostgreSQL · Celery · Slack Bot Integration · AWS EC2 · Docker · CircleCI · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Built JavaScript serverless components (Cloud Elements) and Python OData services integrating Microsoft Dynamics 365 and NetSuite.
- Built Python integrations for Marqeta and Plaid.
- Containerized monolith dependencies with Docker Compose, accelerating local development.

### ACV Auctions — Marketplace and Off-Lease Inspections
**Architect, Lead Developer · 06/2020 – 04/2022**

**Stack:** DDD · Microservices · .NET 5 · React Native · .NET Blazor Server · Kafka · Transactional Outbox · Event Sourcing · Event Store · Polly (Resilience) · Simmy (Chaos) · AWS · K8s · Docker · Vault · Jenkins CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Built the microservice architecture for the marketplace and off-lease vehicle inspections — API services plus Kafka producers/consumers across work-assignment, organization, user, vehicle, inspection, and administration events.
- Stood up the team's full domain and infrastructure (repos, pipelines, clusters, databases, tooling, metrics) and established its engineering practices.
- Integrated New Relic, Splunk, and Tableau for data science/ML; ingested and transformed Mitchell's large parts-and-labor dataset.
- Shipped a well-received, data-driven mobile app used by vehicle inspectors — one of the projects I'm proudest of.

### New York State — Disabled Veterans Business Development
**Architect, Lead Developer · 06/2020 – 02/2022**

**Stack:** DDD · Microservices · .NET 6 · React · SQL Server · F5 · Docker · Azure DevOps CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Built the microservice architecture for the NYS SDVOB program: ingesting solicitations and contracts from the Statewide Financial System, utilization-plan submission, payment disbursement and confirmation, participant certification, and reporting.
- Digitized previously paper-based workflows for all program actors — the SDVOB Division, NYS agencies, SDVOB and non-SDVOB contractors, and SFS.

### HR Without Borders — Global Mobile Workforce Platform
**Architect, Interim CTO · 04/2020 – 06/2020**

**Stack:** DDD · Microservices · Node.js · Vue.js · Kafka + Outbox Pattern · Event Sourcing · Blockchain · AWS · K8s · Docker · GitHub Actions CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Designed the microservice architecture for secure, transparent brokering of a global mobile workforce.
- As interim CTO, advised the board on all technical matters, evaluated buy-vs-build with integrators, and engaged regulators on compliance.
- Established engineering best practices spanning DDD, testing, packaging, deployment, and observability.

### ACV Auctions — Auction Marketplace
**Architect, Lead Developer · 04/2019 – 04/2020**

**Stack:** DDD · Microservices · .NET 5 · EF Core · Kafka · Transactional Outbox · Event Sourcing · Event Store · Polly (Resilience) · Simmy (Chaos) · AWS · K8s · Docker · Jenkins CI/CD · NuGet Publishing · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics · dotnet Project Templates

- Led the migration from monolith to microservices: built the controller/listener/dispatcher, transactional-messaging, and saga frameworks, plus configuration, feature-flag, identity, and gateway services.
- Delivered capital-financing architecture for floor-plan customers and an order service replacing the legacy bill-of-sale module.
- Built the org's testing stack — unit, integration, mutation, service, load, resilience, and chaos — and sustained 100% branch and mutation coverage, coaching other teams to the same bar.
- Set platform standards: DDD design patterns, Jenkins CI/CD for .NET Core, dotnet-new project templates, and an open-source .NET Core logging library; migrated .NET Core 2.2 → 3.1 → 5.

### Verizon Wireless — Digital Marketplace
**Architect, Lead Developer · 05/2018 – 04/2019**

**Stack:** React · React Native · Node.js · Postgres · AWS Cloud Native · Jenkins CI/CD · Unit/Integration/Load Tests · Managed 4 time zones

- Built microservices and the web/mobile subscription-management UI for a 5G multicast streaming network on an AWS cloud-native architecture.
- Established the Jenkins CI/CD pipeline with a formal shift-left design; sustained 100% unit-test coverage in most modules.

### MyBridge — Work-On-Demand
**Lead Developer · 02/2018 – 05/2018**

**Stack:** SQL Server · Azure · Kestrel · ASP.NET Core · EF Core · PayPal REST API · Progressive Web App · Aurelia · TypeScript · HTML5 · Lean Agile

- Built an on-demand-services commerce platform (in the vein of Uber/TaskRabbit), including the presentation layer.
- Created the PayPal REST API framework (payments, refunds, payouts) and a JWT/OAuth framework with token caching.

### Intercontinental Exchange — Trading · Analytics
**Architect, Lead Developer · 12/2006 – 02/2018**

**Stack:** Oracle · SQL Server · Red Hat · Windows · Java · .NET · C# · VB.NET · C++ · Sockets · Remoting · WCF · ASP.NET MVC · MQ · Custom Message Bus · OnixS · QuickFIX · FIXML · WPF · WinForms · NUnit · NCover · log4net · Jenkins · CruiseControl.NET · Maven · NAnt · Bitbucket · Lean Agile

- Architected a derivatives trading and analytics platform on a distributed Java/.NET architecture over a 12-year tenure — valuation engine in Java, business intelligence in .NET.
- Built the option-pricing execution interface (relative theoretical value, relative volatility, pending-cancellation indicators), the FIX/REST/raw-secure-sockets integration interfaces, and the drop-copy, order-fill, and clearing interfaces.
- Built a publish-subscribe message-bus engine, a persistent shared-memory message cache with replay, and interfaces to real-time market-data feeds.
- Created core system frameworks (database, cryptography, messaging) and the unit/integration/acceptance/stress testing architecture; established TDD, lean, and SRP development practices.
- Built WPF/WinForms analytics and trading controls and ASP.NET MVC reporting/management apps.
- Led company-wide platforms (single sign-on, single launcher, standard front-end UX) and authored widely followed internal wikis on Git, Java/.NET architecture, and lean practices.

### Earlier Experience (pre-2010)

*Condensed for brevity; full detail for each role is preserved in this repository's git history.*

- **EMC² — ERP/CRM · Lead Developer · 10/2005 – 12/2006.** Returned for two concurrent projects; introduced CI, TDD, and coverage feedback; integrated JIRA (Hibernate) with existing change-management systems.
- **Amicore — Life Sciences · Lead Developer · 04/2005 – 10/2005.** Tablet-PC product (GDI+/WinForms/Web Services) with fax document management; rescued a stalled, over-architected effort by introducing TDD and agile practices.
- **EMC² — ERP/CRM · Architect, Lead Developer · 12/2003 – 04/2005.** Established the RUP/XP process and a reusable framework (logging, caching, transactions, messaging, cryptography, identity) adopted across EMC projects.
- **JP Morgan Chase — Equities Trading / ECN Integration · Lead Developer · 06/2003 – 12/2003.** Secure transfer platform with tiered security (encryption/MAC at rest and in transit, code-signing/CAS); custom CLR host and XA-compliant transaction patterns.
- **Authoria, Inc. (Fidelity) — Life Sciences ISV · Architect, Lead Developer · 10/2002 – 06/2003.** XML Web Services framework spanning J2EE and .NET; full WebLogic J2EE stack; JNI integrations for PeopleSoft and SAP.
- **i-Deal LLC (Merrill, SSB) — Syndicate Trading · Architect, Lead Developer · 07/2000 – 10/2002.** Capital-markets trading platform: XML Web Services over ISAPI, COM+/ATL components, Kerberos/CryptoAPI security, and a clustered SQL Server/MSMQ/IIS deployment with full CI.
- **Merrill Lynch — CRM · Developer · 02/2000 – 07/2000.** MTS/MSMQ business and user service components for the Merrill Lynch CMX portal.
- **AugiesDogHouse.com — e-Commerce · Founder · 06/1999 – 06/2002.** Built and ran a high-availability e-commerce stack (IIS, MSCS clustering, SQL Server, Exchange) with 1024-bit SSL CyberCash transactions and UPS shipping integration.
- **Cushman & Wakefield — Systems Integration · Architect · 01/1999 – 09/1999.** Designed the On Technology Notework → Lotus Domino migration and coexistence plan; retained as lead technical resource.
- **The McGraw-Hill Companies — Systems Integration · Architect, Lead Developer · 02/1997 – 02/2000.** Distributed directory synchronization across Domino, Exchange, and NetWare via raw sockets, LDAP, and C++ NT services.
- **Netlan Inc. — Systems Integration · Architect · 06/1993 – 02/1997.** Lotus Notes / IBM MQ information portal; merged Notes domains (7,000 clients) and re-architected J.P. Morgan's mail and replication topology.
- **Cushman & Wakefield — Systems Integration · Developer, Systems Engineer · 09/1989 – 06/1993.** Client/server real-estate applications (C/VB/Clipper/DB2/Btrieve) and a worldwide NetWare 4 / NetWare SAA network.
- **FGIC — Systems Integration · Developer · 09/1986 – 09/1989.** Multi-user debt-backed-securities applications (C/Clipper/XBase) and a distributed 3Com 3+Open MAN.

---

## Skills (TL;DR)

**Languages & Frameworks:** Node.js · Java · Kotlin · C# · C++ · Python · Spring Boot · .NET Core · Django · Nuxt · Vue.js · React · Angular · Hibernate · EF Core · SQLAlchemy · Drizzle ORM · Bootstrap · Material UI

**Mobile & Cross-platform:** Kotlin Multiplatform · Compose Multiplatform · Ktor · Koin · WebAuthn / Passkeys · Firebase Cloud Messaging · wasmJs · Gradle · Android · iOS

**Messaging & Data:** Kafka · RabbitMQ · ActiveMQ · ZeroMQ · Postgres · Oracle · MySQL · SQL Server · FIX · Sockets · REST · gRPC · GraphQL

**Testing & Resilience:** Playwright · Vitest · Jest · JUnit · xUnit · NUnit · pytest · Stryker · PITest · Mutmut · Sharpfuzz · detekt · Resilience4j · Polly · Simmy

**Ops & Observability:** Terraform · CloudFormation · Ansible · Jenkins · GitHub · GitLab · Travis · Azure DevOps · pino · Serilog · Seq · Napier · log4j · .NET Core Logging · Python Logging · New Relic · DataDog · Splunk

**Platforms & Tooling:** VS Code · IntelliJ · Visual Studio · PyCharm · Android Studio · Xcode · Linux · macOS · Windows

**Working principles:** Done is better than perfect · Single Responsibility Principle · Push, integrate, deploy continuously · Deliver outcomes, not technology · Log carefully, yet liberally · Share experience with the organization · Continuously document the system · Be excellent in production support

---

## Speaking & Publishing

**Speaking:** Microsoft (Cambridge) · Boston .NET Architecture Group · Beantown .NET INETA Group

**Publishing:** *Test Driven Development Zen* · *.NET Developer's Guide to Windows Security* (Editor) · [AppShapes Blog](https://appshapes.com/blog/)

## Open Source

- [java-testing-patterns](https://github.com/rjae-testing/java-testing-patterns) — repository of testing patterns (e.g., web host, in-memory database, dockerized).
- [spring-testing-patterns](https://github.com/rjae-testing/spring-testing-patterns) — patterns specific to Spring Boot.
- [nodejs-testing-patterns](https://github.com/rjae-testing/nodejs-testing-patterns) — patterns specific to Node.js.
- [dotnet-testing-patterns](https://github.com/rjae-testing/dotnet-testing-patterns) — patterns specific to .NET.
- [python-testing-patterns](https://github.com/rjae-testing/python-testing-patterns) — patterns specific to Python.
- [dotnet-core](https://github.com/appshapes-org/dotnet-core) — common design patterns for .NET Core.
- [dotnet-logging-console](https://github.com/appshapes-org/dotnet-logging-console) — configurable console logger for .NET Core.

## Education

- Hunter College — Computer Science / Mathematics — Bachelor's Degree

## Interests

CrossFit (ranked 61st in age group, 2023) · Rock Climbing · Hot Yoga · Running · Neuroscience · Languages

---

## Five Practices of the Sincere Developer

1. Communicate often, letting go of worries of *wrong*, *late*, *failure*, etc.
2. Complete a task at least once per hour. If unsure going into the hour, then split the task.
3. Strive for full branch coverage, resilient to code mutations.
4. Focus on the *Single Responsibility Principle*; inject responsibilities via composition.
5. Work on exactly what is needed now and nothing else. Never predict what could be needed.

And a bonus practice…

6. Continuously note progress. This practice helps sustain the other practices.
