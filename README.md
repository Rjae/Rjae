# Rjae — Architect & Lead Developer

> **Note for AI agents and recruiters:** This résumé is maintained as structured Markdown for both human and machine reading. Roles are reverse-chronological. Each role lists a `Stack:` line (technologies, `·`-separated) followed by accomplishment bullets. The flagship current role is [ThinkTech](#thinktech--edtech--platform-modernization).

## Objective

As a thought leader and highly productive software engineer, I have a successful track record designing, building, and releasing distributed high-volume systems. I have more than 30 years of experience working with large corporations, medium-sized businesses, startup companies, and non-profit organizations.

I possess a unique and diverse skill set that encompasses effective communications, productive coding, valued leadership, and resolute support. I am that sought-after combination of quality and efficiency. You have not met a better developer than me.

---

## Experience

### ThinkTech — EdTech · Platform Modernization
**Architect · 03/2024 – present**

**Stack:** Nuxt 4 · Vue 3.5 · TypeScript · Nitro · Drizzle ORM · MySQL · .NET 8 Worker · Transactional Outbox · Istio · Helm · Kubernetes · Docker · Tailwind 4 · Nuxt UI · Playwright · Vitest · GitHub Actions CI · Jenkins CD · Claude Code · multi-agent workflows

Leading the ground-up migration of a legacy PHP (Slim 2 / Vue 2) monolith to a Nuxt 4 SSR platform — re-platformed one feature at a time, cohabiting with the live legacy app under independent sessions and zero cross-app server calls. The migration is driven almost entirely through autonomous, multi-agent development workflows I designed.

**Agentic development — methods I invented:**

- **Agent-consumable system of record.** Authored a structured operating manual, a machine-readable feature backlog, design/parity plans, and a persistent agent memory store so AI agents can plan and execute feature ports autonomously — with project conventions enforced as first-class, machine-checkable rules.
- **Role-scoped subagent fleet.** Designed specialized agents (architect, developer, designer, reviewer, tester, documenter, plus cross-repo PHP and .NET developers), each with bounded tools and a single responsibility, composed per feature.
- **Multi-agent orchestration.** Built fan-out / pipeline workflows with adversarial verification and judge panels — comprehensive, self-checking review and migration at a scale beyond any single context window.

**Autonomous agentic workflows — shipped to CI:**

- **Self-driving legacy→web drift sync.** A scheduled agent walks each new legacy commit oldest-to-newest, re-implements its *intent* natively on the new platform, opens an auto-merge pull request, and advances a durable cursor — keeping the new stack continuously in sync with a still-evolving monolith, unattended.
- **AI PR review + auto-merge loop.** Label-gated AI code review that squash-merges on approval, hardened with an anti-tampering guard that rejects any pull request attempting to alter its own reviewer.
- **Repeatable port loop.** Plan → security pass → implement → automated design-fidelity parity gate against the live legacy reference → reviewer agent → end-to-end test → deploy → verify, codified so each feature ships the same way.

**Platform engineering:**

- Drizzle ORM across ~80 tables with per-table ownership transition; a transactional Outbox consumed by a .NET 8 Worker for all asynchronous work (email, notifications, AI queries).
- Full native auth lifecycle — sessions, CSRF, and OAuth (Google, Microsoft, Clever, ClassLink, EdLink, Schoology) — plus a TypeScript port of the legacy PHP session format for seamless cohabitation.
- Dual-theme native redesign (Tailwind 4 + Nuxt UI) gated by an automated design-fidelity parity check against the live legacy reference.
- Own Istio VirtualService on a shared gateway, Helm chart, HPA-autoscaled Kubernetes deployment; GitHub Actions CI and Jenkins CD.
- Earlier in tenure: built the REST API and Edlink / LMS / SIS integrations, and containerized the legacy PHP application.

### CashStash — Banking and Payments Platform
**Architect · 10/2023 – present**

**Stack:** DDD · Microservices · .NET 8 · Vue.js · PostgreSQL · Outbox Pattern · Polly (Resilience) · AWS · K8s · Docker · GitHub CI · Jenkins CD · Unit/Integration/E2E Testing · Serilog · Seq · Plaid · Twilio · Mailgun

- Created Identity, Merchant, Customer, and Banking microservices using .NET Minimal API.
- Created registration for Merchants and Customers including KYC, KYB.
- Created loans, payments, refunds, and rewards features.
- Created fully audited activity using domain events.
- Created integration services for Plaid (banking), Twilio (messaging), and Mailgun (marketing).
- Created multi-factor authentication features (SMS, authenticator app).
- Created asynchronous settlement of digital wallet ledgers using ACH integration services.
- Created rich documentation for developers as well as partners/investors.

### Foundry Digital — Cryptocurrency Marketplace
**Architect · 11/2022 – 10/2023**

**Stack:** DDD · Microservices · Spring Boot · Kotlin · Java · Kafka · MySQL · Redis · AWS EKS · Docker · GitLab DevOps Pipelines · Unit/Mutation/Integration · DataDog

- Created scaling solution for high-volume Bitcoin mining.
- Created migration plan from an existing vertical-scaling-only architecture to a modern horizontal scaling architecture. POC in .NET/C#, final solution in Spring Boot and Kotlin.
- Repartitioned bridgehead messaging topic, scaled messaging consumers via aggregation topics, scaled aggregation consumers, added custom offset management, and replaced persistence with an efficient stored procedure.
- Also provided a short-term solution to C++ architecture to handle the increase in network volume.

### Kangarootime — Childcare Management Platform
**Architect · 03/2022 – 11/2022**

**Stack:** DDD · Microservices · .NET 6 · React · GraphQL · S3 · PostgreSQL · Kafka · Polly (Resilience) · AWS EKS · Docker · Azure DevOps Pipelines · Unit/Mutation/Integration · Serilog · Seq

- Created event validation via JSON Schema at point of publishing.
- Created idempotent consumer patterns for teams to adopt.
- Created testing frameworks to help address change failure rates across all teams.
- Led new product domain to sustain full line and branch coverage.
- Implemented GraphQL resolvers.
- Improved and replaced many core patterns, all fully covered with unit and integration tests.

### Verivend — Transaction Processing
**Lead Developer · 09/2021 – 03/2022**

**Stack:** DDD · Microservices · .NET 6 · Vue.js · S3 · PostgreSQL · RabbitMQ · Polly (Resilience) · AWS ECS · Docker · CircleCI · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Transformed notification features to event-driven architecture.
- Created a feature-flags framework, opening the door for continuous deployment.
- Migrated custom logging to .NET logging and Serilog.
- Created various testing patterns including web-app integration testing; by far the best work I have done around `WebApplicationFactory<T>`.
- Created "Buy Now Pay Later" and Factoring payment solutions.
- Upgraded from .NET 5 to .NET 6.

### TeamPay — Purchasing Automation
**Lead Developer · 09/2021 – 06/2022**

**Stack:** Monolith Service · Python · JavaScript · Django · PostgreSQL · Celery · Slack Bot Integration · AWS EC2 · Docker · CircleCI · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Developed JavaScript serverless components in Cloud Elements.
- Developed Python OData services for Microsoft Dynamics 365 and NetSuite integrations.
- Developed Python components for Marqeta and Plaid integrations.
- Created Docker Compose for monolith dependencies, speeding up local development.

### ACV Auctions — Marketplace and Off-Lease Inspections
**Architect, Lead Developer · 06/2020 – 04/2022**

**Stack:** DDD · Microservices · .NET 5 · React Native · .NET Blazor Server · Kafka · Transactional Outbox · Event Sourcing · Event Store · Polly (Resilience) · Simmy (Chaos) · AWS · K8s · Docker · Vault · Jenkins CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Created microservice architecture for marketplace and off-lease vehicle inspections.
- Implemented API services as well as Kafka consumers and producers for work assignment, organization, user, vehicle, inspection, and administration events.
- Created team, domain, and infrastructure: repos, pipelines, clusters, databases, tools, metrics.
- Implemented New Relic, Splunk, and Tableau integrations for data science and ML.
- Extremely well-received data-driven mobile app used by vehicle inspectors.
- Ingestion and transformation of large parts and labor data set from Mitchell.
- Established and supported patterns, practices, and principles for the development team.
- While not the largest project of mine, one of the top five I am proud of.

### New York State — Disabled Veterans Business Development
**Architect, Lead Developer · 06/2020 – 02/2022**

**Stack:** DDD · Microservices · .NET 6 · React · SQL Server · F5 · Docker · Azure DevOps CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Created microservice architecture for the management of the NYS SDVOB program: ingestion of solicitations and contracts from the Statewide Financial System (SFS), submission of utilization plans, disbursement and confirmation of payments, certification of participants, and reporting.
- Implemented workflow for all program actors, including: Division of Service Disabled Veteran Owned Businesses, NYS agencies, SDVOB and non-SDVOB Contractors, and SFS. Previously these workflows were mostly paper-based.

### HR Without Borders — Global Mobile Workforce Platform
**Architect, Interim CTO · 04/2020 – 06/2020**

**Stack:** DDD · Microservices · Node.js · Vue.js · Kafka + Outbox Pattern · Event Sourcing · Blockchain · AWS · K8s · Docker · GitHub Actions CI/CD · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics

- Created microservice designs for secure and transparent brokering of a mobile workforce.
- Advised the board on all technical matters in the startup of the company.
- Met with integrators and advised on buy-vs-build options.
- Discussed regulatory requirements with governmental representatives.
- Established best practices for DDD, microservice pattern, testing, packaging, deployment, as well as logging, tracing, and metrics.

### ACV Auctions — Auction Marketplace
**Architect, Lead Developer · 04/2019 – 04/2020**

**Stack:** DDD · Microservices · .NET 5 · EF Core · Kafka · Transactional Outbox · Event Sourcing · Event Store · Polly (Resilience) · Simmy (Chaos) · AWS · K8s · Docker · Jenkins CI/CD · NuGet Publishing · Unit/Mutation/Integration · System/Load Tests · Logging · Tracing · Metrics · dotnet Project Templates

- Created microservice architecture for migration from monolithic services.
- Created frameworks for controllers, listeners, dispatchers, transactional messaging, sagas.
- Created configuration service, feature flag service, identity service, gateway services.
- Created capital financing architecture for floor-plan customers.
- Created order service to migrate from legacy bill-of-sale module.
- Created frameworks for unit testing, integration testing, mutation testing, service testing, load testing, resilience and chaos engineering.
- Migrated architecture from .NET Core 2.2 to 3.1, and then to 5.
- Created design patterns for DDD entities, primitive wrappers, DbContext.
- Established best practices for logging, tracing, and metrics.
- Provided guidance for teams on UI, design, testing, C#, .NET Core, tools, etc.
- Established Jenkins CI/CD standards for .NET Core microservices.
- Created an open-source library of .NET Core logging providers.
- Created dotnet-new project templates for all project types.
- Sustained 100% branch and mutation coverage. Provided guidance to other teams on how to reach that level of code coverage.

### Verizon Wireless — Digital Marketplace
**Architect, Lead Developer · 05/2018 – 04/2019**

**Stack:** React · React Native · Node.js · Postgres · AWS Cloud Native · Jenkins CI/CD · Unit/Integration/Load Tests · Managed 4 time zones

- Created microservices for a 5G multicast streaming network.
- Created web and mobile UI for managing network subscription.
- Designed AWS cloud-native architecture.
- Created Jenkins CI/CD pipeline, formal shift-left design.
- Maintained 100% unit test coverage in most modules.

### MyBridge — Work-On-Demand
**Lead Developer · 02/2018 – 05/2018**

**Stack:** SQL Server · Azure · Kestrel · ASP.NET Core · EF Core · PayPal REST API · Progressive Web App · Aurelia · TypeScript · HTML5 · Lean Agile

- Created a commerce platform for on-demand service provision (e.g. Uber, TaskRabbit).
- Created model and framework for the PayPal REST API (payments, refunds, payouts).
- Created JSON Web Token framework, including OAuth caching.
- Created views and controllers for presentation concerns.

### Intercontinental Exchange — Trading · Analytics
**Architect, Lead Developer · 12/2006 – 02/2018**

**Stack:** Oracle Database · Red Hat · SQL Server · Windows · Java Runtime · .NET Runtime · Sockets · Remoting · WCF · ASP.NET MVC · JavaScript · Java · C# · VB.NET · C++ · MQ · Custom Message Bus · OnixS · QuickFIX · FIXML · WPF · WinForms · DotNetBar · ReSharper · NUnit · NCover · log4net · log4j · log4js · Jenkins · CruiseControl.NET · Maven · bash · NAnt · PowerShell · JIRA · Confluence · Bitbucket · ClickOnce · InstallAware · Lean Agile

- Created derivatives trading and analytics platform using distributed Java and .NET architecture. Valuation engine in Java, other business intelligence in .NET.
- Created option pricing interface for order execution. Indicators include relative theoretical value, relative volatility, and pending cancellation.
- Created FIX, REST, and raw secure sockets interfaces for external integration. Created persistent, shared-memory message cache supporting message replay. Created drop-copy, order fill, and clearing interfaces.
- Created publish-subscribe message bus engine for decoupled event management. Created interfaces to various real-time market data feed providers.
- Created architecture for unit, integration, acceptance, and stress processes. Created system frameworks (e.g., database, cryptography, messaging).
- Created development practices (e.g. TDD, lean coding, SRP, and traceable code).
- Created WPF and WinForms controls for analytics, modeling, and trading modules.
- Created web apps for reporting and management services using ASP.NET MVC.
- Lead member of multiple company-wide platforms: single sign-on, single launcher, standard front-end design and user experience specification.
- Authored heavily followed wikis on Git techniques, Java and .NET architecture, and lean development patterns and practices.

### EMC² — ERP · CRM
**Lead Developer · 10/2005 – 12/2006**

**Stack:** SQL Server 2000 · Win2K3 · Java · Swing · Hibernate · Eclipse · JUnit · Log4J · CruiseControl · JIRA

- Returned to EMC for two concurrent projects. Promoted software pattern and practice improvements. Introduced continuous integration, test-driven development, and test-coverage feedback.
- Implemented JIRA on a LAMP stack. Developed JIRA services using Hibernate to integrate with existing change management systems.

### Amicore — Life Sciences · Accounting
**Lead Developer · 04/2005 – 10/2005**

**Stack:** SQL Server 2000 · Win2K3 · .NET Framework (C#) · WinForms · GDI+ · DirectX · .NET Remoting · Interop · .NET Web Services · NAnt · NUnit · NDoc · FxCop · Scrum Agile

- Developed product for Tablet PC. Developed GDI+ components, WinForms, and Web Services. Completed fax document management module — including text, image, and voice annotations.
- Product depended on a hybrid distributed architecture for connected and disconnected operations. A classic over-architecture, the development process had slowed to a crawl. Promoted software pattern and practice improvements. Introduced agile software development practices, most notably test-driven development.

### EMC² — ERP · CRM
**Architect, Lead Developer · 12/2003 – 04/2005**

**Stack:** Oracle 9i RAC · Linux · .NET Framework (C#) · .NET Remoting · Interop · .NET Web Services · NAnt · NUnit · NDoc · FxCop · Flash MX Remoting · XP Agile

- Established standard software specification and development process (RUP). Established test-driven development practices (XP). Developed software build and release management (NAnt), including source-controlled PL/SQL.
- Developed framework: logging, caching, exception management, data management, context management, transaction management, distributed messaging, cryptography, performance analysis, and identity and profile management. Framework was adopted for common use by other EMC projects. Developed SOA façade for Flash Remoting.

### JP Morgan Chase — Equities Trading · ECN Integration
**Lead Developer · 06/2003 – 12/2003**

**Stack:** SQL Server 2000 · Win2K · .NET Framework (C#, C++) · .NET Remoting · Interop · .NET CLR hosting · NUnit · NDoc · Log4Net

- Architect and developer of a secure transfer services platform. High degree of tiered security: encryption and MAC at rest; code-signing and CAS in assemblies; hook filters for keyboard and mouse; encryption and MAC in transit (TCP listeners, SNA LUs).
- Developed custom CLR host for extending the assembly loader and type reflection. Developed XA-compliant transaction patterns. Developed an extensible state machine in a remote singleton pattern. Used singleton instance publishing pattern to improve remoting performance.

### Authoria, Inc. (Fidelity) — Life Sciences · ISV
**Architect, Lead Developer · 10/2002 – 06/2003**

**Stack:** SQL Server 2000 · Win2K · .NET Framework (C#) · Java · Python · WebLogic · Apache Axis · JMS · JNI · JNDI · JDBC · ClearCase · ClearQuest

- Architect and developer of an XML Web Services framework for J2EE and .NET product lines. Developed full J2EE stack implementation in WebLogic.
- Developed Java multi-threaded context management. Developed JNI for PeopleSoft and SAP integration. Developed EAR delivery, versioning, and dependency system in Python.
- Developed .NET patterns to replace DNA architecture: Windows Forms, ASP.NET, ADO.NET, Windows Services, .NET Interop.

### i-Deal LLC (Merrill, SSB) — Syndicate Trading
**Architect, Lead Developer · 07/2000 – 10/2002**

**Stack:** SQL Server 2000 · Win2K · COM(+) · ATL · STL · SOAP · WSDL · UDDI · XML · XSL · XSLT · XPath · ADSI · AD Extension · ASP · ISAPI · SSL Auth · Queued Components · .NET Framework (C++) · WMI Instrumentation · Crypto API · Kerberos API · Locale API · TMX Exchange · InstallShield · SQL DMO · XP Agile

- i-Deal provides a unified trading platform for capital markets (equity, debt, municipals).
- Developed ATL/STL adapters for IObjectControl, IObjectConstruct, ISupportErrorInfo, IStream. Developed XML Web Services using ISAPI extensions, listeners, type mappers, WSDL generator, and cryptographic key distribution.
- Developed security context management (thread identity impersonation) using ISecurityBlanket and CryptoAPI. Developed type library wrappers for ASP, ADODB, MSXML, ActiveDS, MSMQ, BizTalk, and COM+. Developed components for localization, logging, exception handling, ADO.NET, and cryptography. Architected a migration from COM+ events to a CLR delegate framework.
- Developed web client, web service, and sockets interfaces. Developed ISAPI filter authentication (URL-safe tokens). Developed a std::map based shared-memory cache for Kerberos TGT handles. Ported eXtreme framework to C++ for unit testing. Developed TMX translation services for localization.
- Developed a continuous-integration system for full-cycle deployment (dev, QA, staging, production). Designed clustered SQL Server, MSMQ, and IIS farm. Designed replication for SQL Server and Active Directory. Deployed SSL accelerator for single and mutual certificate authentication. Developed WMI framework for component instrumentation (FinalConstruct, FinalRelease, Activate, Deactivate, exceptions).

### Merrill Lynch — CRM
**Developer · 02/2000 – 07/2000**

**Stack:** SQL Server 2000 · Win2K · COM · MTS · MSMQ · ATL · STL · ASP · ISAPI

- Member of the financial application group within the Merrill Lynch CMX portal. Developed business and user service components for MTS and MSMQ. Developed presentation services in VBScript and JavaScript.

### AugiesDogHouse.com — e-Commerce
**Founder · 06/1999 – 06/2002**

**Stack:** SQL Server 7 · Windows NT · Exchange Server 5.5 · COM · MTS · MSCS · ATL · STL · ASP · ISAPI

- Developed high-availability systems including web, messaging, database, advertising, firewall security, and transaction processing. AugiesDogHouse.com runs on IIS, MSCS 3.0, SQL Server 7, and Exchange 5.5. Secure transactions, using 1024-bit SSL, are scripted into the MSCS Pipeline via CyberCash MTS components. Additional components include UPS PLD API for electronic shipment and delivery services.

### Cushman & Wakefield, Inc. — Systems Integration
**Architect · 01/1999 – 09/1999**

**Stack:** Lotus Domino

- Designed a migration and coexistence plan from On Technology Notework to Lotus Domino. Retained as lead technical resource throughout project implementation.

### The McGraw-Hill Companies — Systems Integration
**Architect, Lead Developer · 02/1997 – 02/2000**

**Stack:** Oracle 8 · Sun Solaris · Windows NT · LDAP · Exchange · Lotus Domino · sockets · MAPI · DAPI · SMTP · X.400

- Developed distributed architecture for directory synchronization between Lotus Domino, Microsoft Exchange, and Novell NetWare. Design based on raw sockets, Oracle database, Notes Services, Exchange Extensions, NetWare loadable modules, and LDAP.
- Developed NT Services in C++ using MAPI, DAPI, Notes API, and NLM.

### Netlan Inc. — Systems Integration
**Architect · 06/1993 – 02/1997**

**Stack:** Microsoft Exchange · Winsock Messaging · IBM MQ Series · Lotus Notes · Groupware · Unix SVR4 · HP-UX · Linux · Netware · Banyan Vines

- Architected an information portal using Lotus Notes and IBM MQ Series.
- Developed electronic software distribution services for various companies.
- Merged multiple Lotus Notes domains into one domain of 7,000 clients.
- Re-architected J.P. Morgan Lotus Notes mail and database replication topology. Analysis revealed latency issues, ping-pong messaging, undeliverable mail, database replication failures, conflicts, and low server availability. Upgraded Notes servers, deployed TCP/IP throughput domain, optimized mail router, and database replication.

### Cushman & Wakefield, Inc. — Systems Integration
**Developer, Systems Engineer · 09/1989 – 06/1993**

**Stack:** Btrieve · XBase · DB2 · C · Visual Basic · Clipper · MHS · X.400 · X.500 · Netware 4 · Netware SAA

- Developed client/server applications for commercial, industrial, residential, and management real estate. Systems developed using C, Visual Basic, Clipper, DB2, Btrieve, and XBase.
- Architected a distributed worldwide network with Netware 4 and Netware SAA. Deployed messaging system organization-wide.

### FGIC — Systems Integration
**Developer · 09/1986 – 09/1989**

**Stack:** Btrieve · XBase · C · Clipper · MHS · X.400 · X.500 · 3Com 3+ Open

- Developed multi-user applications for debt-backed securities. Systems developed using C, Clipper, and XBase.
- Architected a distributed MAN with 3Com 3+ Open.
- Deployed messaging system organization-wide.

---

## Skills (TL;DR)

**Languages & Frameworks:** Node.js · Java · C# · C++ · Python · Spring Boot · .NET Core · Django · Hibernate · EF Core · SQLAlchemy · React · Angular · Vue.js · Bootstrap · Material UI

**Messaging & Data:** Kafka · RabbitMQ · ActiveMQ · ZeroMQ · Postgres · Oracle · MySQL · SQL Server · FIX · Sockets · REST · gRPC · GraphQL

**Testing & Resilience:** Jest · JUnit · xUnit · NUnit · pytest · Stryker · PITest · Mutmut · Sharpfuzz · Resilience4j · Polly · Simmy

**Ops & Observability:** Terraform · CloudFormation · Ansible · Jenkins · GitHub · GitLab · Travis · Azure DevOps · pino · log4j · .NET Core Logging · Python Logging · New Relic · Splunk

**Platforms & Tooling:** VS Code · IntelliJ · Visual Studio · PyCharm · Linux · macOS · Windows · Android · iOS

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
