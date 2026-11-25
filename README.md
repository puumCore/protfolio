# Mandela Murithi

**Senior Backend Engineer · Java · Go · Payments**

Senior backend engineer with six years of experience building payment and banking systems for a tier-1 bank (KCB Group) and Africa's largest mobile money platform (Safaricom M-Pesa). I design event-driven services, partner APIs and settlement flows that keep money correct when the systems around them fail.

**Nairobi, Kenya (UTC+3)** · Open to remote opportunities and relocation
[puumInc@outlook.com](mailto:puumInc@outlook.com) · [LinkedIn](https://www.linkedin.com/in/mandela-murithi) · [GitHub](https://github.com/puumCore)

---

## Highlights

- **Payments at scale.** I build and own services on a multi-tenant payments platform serving **seven East African markets**, processing millions of transactions daily across mobile, card, agent and ATM channels.
- **Cross-bank settlement.** I designed and delivered loan settlement with **four partner institutions**, using idempotency and reconciliation to keep balances correct when a partner fails mid-transaction.
- **National-scale impact.** At Safaricom I worked on the marine cargo insurance platform that became the foundation of **Kenya's national digital marine insurance system**, live since July 2026.
- **Integration breadth.** I've enabled **300+ organisations** to integrate with M-Pesa and secured APIs for **20+ merchants and institutions** through WSO2 API Manager.
- **Production discipline.** I practise test-driven development, roll out changes in phases across countries, and monitor production for at least six months after release.
- **Giving back.** I built and run **[Vitruvian](https://vitruvian.puumcore.dev)**, a free chemistry learning platform for Kenyan secondary school learners and their teachers. I host it myself at no cost to schools or families.

---

## Technical Skills

| Area | Technologies |
| --- | --- |
| **Languages** | Java (8–25), Go, SQL, C++ (working knowledge) |
| **Backend** | Spring Boot, Spring Security, Spring Cloud Gateway, Spring Data JPA / Hibernate, Apache Camel, Gin, Echo, gRPC |
| **Data** | PostgreSQL, Oracle, MongoDB, Redis, Flyway |
| **Messaging & Integration** | Apache Kafka, RabbitMQ, WSO2 API Manager, REST, gRPC, webhooks, OAuth2 / JWT, CIAM |
| **Cloud & Platforms** | Microsoft Azure, Red Hat OpenShift, Kubernetes, Docker, Podman, Cloudflare |
| **CI/CD & Quality** | Azure DevOps, Jenkins, GitHub Actions, Harbor, SonarQube, Checkmarx, Trivy |
| **Observability** | Prometheus, Grafana, Jaeger |
| **Testing** | Test-driven development, JUnit, Mockito, integration testing |
| **Practices** | Event-driven architecture, idempotency and reconciliation, multi-tenant design, code review, Scrum, AI-assisted development (Claude Code) |

---

## Experience

### Backend Developer — KCB Group
*Nov 2024 – Present · Nairobi, Kenya*

- Build and own Java/Spring Boot services on a scalable multi-tenant payments platform serving seven East African markets.
- Designed and delivered cross-bank loan settlement with four partner institutions, with idempotency and reconciliation across independently operated systems.
- Built webhooks for merchant M-Pesa STK Push APIs exposed over the internet. Transactions, notifications and audit logs flow through Kafka with retries and dead-letter handling to raise success rates.
- Engineered event-driven services where the same financial record is read and updated by several services that autoscale on OpenShift, keeping processing idempotent and consistent.
- Integrated and secured partner APIs for 20+ merchants and institutions through WSO2 API Manager, including custom XSLT/XPath mediation, and delivered CIAM for the public developer portal.
- Manage Flyway schema migrations across per-country deployments, released in phases (pilot, per-country pre-release, then release) and monitored for at least six months afterwards.
- Contributed to an Azure AD single sign-on rollout across internal bank systems.

**Stack:** Java, Spring Boot, JPA, Kafka, PostgreSQL, Oracle, Flyway, WSO2 API Manager, Azure, OpenShift, Azure Pipelines, SonarQube, Prometheus, Grafana, Jaeger

### M-Pesa Engineer — Safaricom PLC
*Mar 2023 – Nov 2024 · Nairobi, Kenya*

- Worked on the early marine cargo insurance platform, integrating the Insurance Regulatory Authority, the Kenya Revenue Authority and local underwriters so importers could insure sea shipments from their phones. It became the foundation of Kenya's national digital marine insurance system.
- Built Java/Spring Boot microservices for health, marine cargo and travel insurance products sold through M-Pesa, integrating insurers, regulators and hospital networks.
- Enabled 300+ organisations to integrate with M-Pesa for payment processing.
- Re-architected insurance APIs onto an event-driven pattern with Spring Cloud Gateway and Kafka, making processing idempotent under load.
- Designed PostgreSQL schemas, chose transaction isolation levels and ran migrations on live data without downtime.

**Stack:** Java, Spring Boot, Spring Cloud Gateway, Kafka, PostgreSQL, JPA, JUnit, Mockito

### Software Engineer — Sybyl Kenya
*Feb 2022 – Mar 2023 · Nairobi, Kenya*

- Rolled out WSO2 API Manager at Stima Sacco, the Kenya Revenue Authority and Family Bank as a secure exposure layer for core banking and tax systems, with authentication, throttling and mediation policies.
- Gathered requirements with client stakeholders and architects, and documented solutions and APIs.

**Stack:** WSO2 API Manager, Java, OAuth2

### Freelance Software Developer
*2018 – Present · Remote*

- Delivered full-stack Java applications for point-of-sale, real estate and streaming clients (2018 – 2022).
- Build and host custom software, including client sites, on my own self-managed platform behind a WSO2 API Manager gateway and Cloudflare:
  - **Vitruvian (community project):** free chemistry learning platform for Kenyan secondary schools, with practice, educator-set exams, 3D atom and reaction models, and school, county and national rankings · [vitruvian.puumcore.dev](https://vitruvian.puumcore.dev)
  - **Viper Tattoos:** booking and portfolio platform for tattoo and piercing artists, with art visualisation before booking and MFA-secured accounts · [viper.puumcore.dev](https://viper.puumcore.dev)
  - **Self-hosted mail server:** sends email to Gmail, Microsoft and Yahoo inboxes, with webmail access · [webmail.puumcore.dev](https://webmail.puumcore.dev)
  - **NRE (Nyumba Real Estate):** SaaS property-management platform integrating smart utility meters, gate access control, maintenance requests and billing · [nre.puumcore.dev](https://nre.puumcore.dev)

**Stack:** Java 8, JavaFX, JFoenix · Java, Spring Boot, WSO2 API Manager, Podman, Cloudflare Tunnel

---

## Projects

| Project | Description | Stack | Status |
| --- | --- | --- | --- |
| **[IAM-grpc](https://github.com/puumCore)** | Authentication service exposing gRPC endpoints over Redis and PostgreSQL | Go, gRPC, Redis, PostgreSQL | Public |
| **[Vitruvian](https://vitruvian.puumcore.dev)** | Free chemistry learning platform for Kenyan secondary school learners: guided practice on formulas and equations, educator-set exams, 3D atom and reaction models, and live school, county and national rankings (details below) | Node.js, Express, MongoDB, three.js, WSO2, Cloudflare Tunnel | Live · free community project |
| **Self-hosted platform** | Two-node infrastructure that runs my own services in production, with replication and backups (details below) | Podman, PostgreSQL, Redis, RabbitMQ, WSO2, Cloudflare Tunnel, Jenkins | Live |
| **[NRE: Nyumba Real Estate](https://nre.puumcore.dev)** | SaaS property-management platform that unifies live smart electricity and water meter readings, gate access control (fingerprint, face recognition, NFC cards and tags), tenant maintenance requests and landlord billing | Java, Spring Boot, PostgreSQL | In development · private repository |
| **[Viper Tattoos](https://viper.puumcore.dev)** | Tattoo parlour platform: artists receive and plan client bookings, sell piercings, and curate categorised portfolios; clients preview a tattoo or piercing on themselves before deciding, and share healed-result photos; artists can onboard collaborators. Accounts are secured with MFA (Microsoft or Google Authenticator) | Self-hosted behind WSO2 API Manager | Live · private repository |
| **[Mail server](https://webmail.puumcore.dev)** | Self-hosted mail server with webmail, delivering to Gmail, Microsoft and Yahoo | Podman, Cloudflare | Live |
| **Document management with redaction** | Version control and redaction for Word and PDF documents | Java, Spring Boot, Vue.js | In development |

<!-- TO DO before publishing:
     - Link any repository that is public; for private ones you can leave the name unlinked. -->

### Featured: Vitruvian, Giving Back Through Free Chemistry Learning

**[vitruvian.puumcore.dev](https://vitruvian.puumcore.dev)** · Free to use · Built and hosted by me

Many Kenyan secondary school learners struggle with writing chemical formulas and balancing equations. These skills underpin the rest of the chemistry syllabus. Yet many schools have few lab resources and large classes, so learners rarely get one-to-one feedback. I built Vitruvian to give every learner a patient, always-available practice partner, and every teacher a free way to set and mark work. It costs schools and families nothing, carries no ads or third-party tracking, and I host and maintain it on my own infrastructure.

**What it gives learners and teachers**

- **Guided practice with real feedback.** Seven topics, from the criss-cross method to ionic equations. A chemistry-aware marker counts atoms and charges instead of comparing text, so any correct way of writing an answer is accepted. After a wrong answer, learners get a targeted hint (for example, "Count the O atoms on each side") and a second try before the solution is shown, so they learn the method rather than copy the answer.
- **Seeing the chemistry.** All 118 elements in an interactive periodic table, 3D atom models showing how ions form, and a Formula Lab that builds compounds, balances any equation and animates atoms rearranging in a reaction. Every 3D model can be turned, zoomed in and out (with on-screen buttons, the mouse wheel, a two-finger pinch or the keyboard) and reset to its starting view in one tap. All of this works without an account.
- **Free tools for teachers.** Educators set exams, then share them with their own class, by access code or publicly. They schedule timed or take-away exams and see which questions their learners fail most. Educators also vote on each other's best questions, so good material reaches more learners.
- **Motivation through community.** Live school, county and national rankings, a school league and a county map. They give learners in every county a way to see their progress next to their peers.

**Built for the learners who need it most**

- **Low-end phones and slow connections:** plain JavaScript modules with no build step and self-hosted fonts, so pages stay light. The periodic table, Lab, dashboards and rankings each fit on one screen, on phones and desktops alike.
- **Comfortable to study day or night:** light and dark themes follow the device's own setting, and a header switch lets learners choose one, which is remembered. Both themes keep text at WCAG AA contrast, the 3D models included, and the theme and 3D controls are labelled for screen readers and work from the keyboard.
- **Privacy by design for young learners:** learners' personal details are encrypted at rest, and leaderboards show only a display name, school and county. The county picker matches location on the device, and the position is never sent to the server. Every account is protected by two-step sign-in.
- **Fair under shared connections:** a whole class often shares one school internet connection. Rate limits at the WSO2 gateway and in the app count each real visitor separately, so a class revising together is never blocked as if it were one heavy user, while abuse from a single address still is.
- **Honest content:** all questions are original sample questions written for the platform, and are clearly labelled as not official KNEC material.

**Stack:** Node.js, Express, MongoDB, three.js, WSO2 API Manager (gateway and per-client throttling), Cloudflare Tunnel, Podman

### Featured: Self-Hosted Production Platform

I host my own services on infrastructure I operate end to end, applying the same standards I use for banking systems at home: data integrity first, controlled exposure, and automated delivery.

```mermaid
flowchart LR
    U[Users] --> CF[Cloudflare<br/>one subdomain per service]
    CF -->|Cloudflare Tunnel| GW[WSO2 API Manager]
    subgraph A[Node A · primary]
        GW --> S[Services<br/>Podman]
        S --> PG[(PostgreSQL)]
        S --> R[(Redis)]
        S --> MQ[[RabbitMQ]]
    end
    subgraph B[Node B · standby]
        PG2[(PostgreSQL replica)]
    end
    PG -- replication --> PG2
    PG -- pgBackRest --> BK[(Backups)]
    GH[GitHub] -- webhook --> J[Jenkins] --> S
```

**Key design decisions**

- **Data integrity first.** A replicated standby node, pgBackRest backups and a UPS protect against power loss and disk failure.
- **Low-latency data access.** Services and their data stores share the primary node, and the standby exists for recovery rather than load.
- **Controlled exposure.** Podman gives explicit control over exposed ports. Cloudflare Tunnel publishes each service on its own subdomain without a public IP, and WSO2 API Manager acts as the gateway in front of every service.
- **Automated delivery.** GitHub webhooks trigger Jenkins CI pipelines.

---

## Certifications & Education

| Certification | Issuer | Year |
| --- | --- | --- |
| [WSO2 API Manager (v4) Developer](https://certification.wso2.com/web/certificate/CID-03713313) | WSO2 | 2022 |
| Spring Security | Amigos Code | 2024 |
| [AI Developer Practitioner](https://skillsoft.digitalbadges-eu.skillsoft.com/profile/eu-mandelamurithimuriuki856708/wallet) | Skillsoft | 2024 |
| Java Programming & Object-Oriented Design | Institute of Advanced Technology | 2018 |

**BSc Software Engineering** · Murang'a University of Technology · 2021

---

## Let's Talk

I'm interested in backend roles in **payments and fintech**, especially where correctness, reliability and integration with external systems matter. I also enjoy building focused websites for niche audiences, and using my engineering skills to give back, as with Vitruvian, a free learning platform for Kenyan schools.

[puumInc@outlook.com](mailto:puumInc@outlook.com) · [LinkedIn](https://www.linkedin.com/in/mandela-murithi)
