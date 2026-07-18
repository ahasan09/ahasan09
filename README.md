<div align="center">

# Abul Hasan

### Senior Staff Software Engineer · [Cefalo](https://www.cefalo.com) · M.Sc. CSE · Dhaka, Bangladesh

I architect and ship frontends for **nation-scale platforms**.

<p>
  <a href="https://www.linkedin.com/in/ahasan09/">
    <img src="https://img.shields.io/badge/LinkedIn-ahasan09-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/ahasan09">
    <img src="https://img.shields.io/badge/GitHub-ahasan09-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:abul.hasan@cefalo.com">
    <img src="https://img.shields.io/badge/Email-abul.hasan%40cefalo.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=ahasan09&label=Profile%20Views&color=58A6FF&style=for-the-badge" alt="profile views" />
  <img src="https://img.shields.io/github/followers/ahasan09?label=Followers&style=for-the-badge&color=58A6FF" alt="followers" />
</p>

</div>

---

## Impact

- **13+ years** shipping production software across frontend, backend, and platform architecture
- **1M+ users** on the Norwegian National Archive's public Arkivportalen portal I own at Cefalo — plus 10,000+ archivists on the internal systems
- **100,000+ users** on the Swiss Life Select EU fintech platform I previously led
- **5 repositories** modernized — four from Angular 14 to 21, one to the latest React — with a team reduced from 10 to 5 engineers

At senior staff level, I focus on architecture that survives scale, delivery pressure, and team changes. I write production code, drive technical direction, and mentor engineers with shipping velocity as the outcome.

**How I build:** I run an agentic development workflow end-to-end — an agent pipeline picks up a Jira ticket, analyzes the requirement, generates a design spec and plan, implements it, then runs code review and security review, while I direct the architecture and own every merge. Custom skills encode team conventions into the pipeline.

---

## Experience

### Cefalo — Senior Staff Software Engineer
**Aug 2022 – Present**

**Client:** Norwegian National Archive (Asta), Norway

**Problem**
- Frontend platform spread across 5 repositories with increasing feature demand
- Team rebalanced from 10 to 5 engineers before the migration began

**Approach**
- Drove Angular 14→21 and React migrations across all 5 repositories — pilot repo first, then the rest in overlap
- Own the frontend of all 5 modules, plus the Arkivportalen portal and requisition backends — leading the team day-to-day, with oversight of backend work on the remaining modules
- Built dynamic permission engine and Elasticsearch-backed search capabilities
- Built a Kafka CDC pipeline keeping Elasticsearch and cross-module shared data in sync with PostgreSQL/MongoDB
- Built a digital archive middleware in Python — gradually pulls portal data into its own PostgreSQL and reconciles it against an external digital-media system (where content is published from many sources) to track each item's publish status; a separate portal-side scheduler pulls that status into portal Elasticsearch, so the portal never calls the media system directly — with retries, failure handling, and last-success checkpoints on both sides
- Implemented WebSocket live notifications; drove UI improvements and Google Analytics integration on the portal
- Set up self-hosted Bitbucket Pipelines runners on Azure VMs for CI
- Standardized testing and CI patterns across frontend codebases

**Outcome**
- Production system serving **10,000+ archivists** and a public portal with **1M+ users**
- Migration roadmap delivered with a **50% leaner team**
- Consistent cross-repo engineering standards for frontend delivery

**Core Stack:** Angular, React, TypeScript, Kotlin, Java 26, Spring Boot, Python, PostgreSQL, MongoDB, Elasticsearch, Kafka, ActiveMQ

### SELISE Digital Platforms — Principal Software Engineer
**2018 – Jul 2022 (4 years)**

**Client:** Swiss Life Select Fintech Platform, EU

**Scale**
- Frontend platform serving **100,000+ users across the EU**
- Multi-tenant, microservice-backed architecture

**Ownership**
- Owned core frontend architecture decisions and led frontend engineers
- Delivered SSO, multi-tenancy, PWA, and push notifications
- Implemented real-time integrations with SignalR and RabbitMQ
- Built data-intensive dashboard experiences using Chart.js and AG Grid

**Core Stack:** Angular, TypeScript, .NET Core, C#, MongoDB, Redis, RabbitMQ, SignalR, JWT, PWA

### Earlier Career (2013 – 2017)

- **Senior Software Engineer** — Swiss Life ePrivateWealth (2017): Internal/external insurance portal with AngularJS + .NET Core microservice stack and SignalR real-time integrations.
- **Software Engineer** — Ruf Informatik E-Service (2016): Reservation platform, social-feed aggregation, and public statistics dashboards.
- **Developer** — Computer Source Bangladesh (2013 – 2015): End-to-end ERP covering inventory, RMA, sales, POS, accounts, and PMS.

---

## Stack

### Frontend
Angular, React, TypeScript, JavaScript, RxJS, Redux, Angular Material, PrimeNG, Chakra UI, Bootstrap, PWA

### Backend
NestJS, Node.js, Express, Kotlin, Java, Spring Boot, .NET Core, C#, Python, Django, REST, GraphQL, JWT, SSO

### Data and Messaging
PostgreSQL, MongoDB, MSSQL, Redis, Elasticsearch, RabbitMQ, Apache Kafka, ActiveMQ, SignalR, WebSocket

### Cloud and Delivery
Docker, Bitbucket Pipelines, Microsoft Azure, AWS, Azure DevOps, Jenkins, GitHub Actions, Application Insights, Azure Blob Storage

### Quality and Practice
Playwright, Jest, Jasmine, Karma, TDD, DDD, SOLID, Design Patterns, Clean Architecture, Agile/Scrum, Agentic development (Claude Code)

---

## Case Studies

Deep dives into the architecture decisions behind my production work — the problem, the options I weighed, and what happened:

- **[Migrating 5 codebases to Angular 21 with half the team](https://ahasan09.github.io/case-studies/angular-migration.html)** — sequencing, risk, and CI standardization when the team went from 10 to 5.
- **[An agentic workflow: from Jira ticket to reviewed PR](https://ahasan09.github.io/case-studies/agentic-workflow.html)** — an agent pipeline for spec, plan, implementation, and review, with a human owning every merge.
- **[CDC with Kafka: keeping Elasticsearch in sync](https://ahasan09.github.io/case-studies/kafka-cdc-search.html)** — why change data capture beat dual writes and batch reindexing.
- **[A multi-tenant fintech platform for 100K EU users](https://ahasan09.github.io/case-studies/swiss-life-platform.html)** — SSO, tenancy isolation, PWA, and real-time delivery.

My repositories here are mostly focused exercises and experiments — the production work lives in client systems and is described above. [All repositories →](https://github.com/ahasan09?tab=repositories)

---

## Recommendations

> "Working closely with Hasan the last three years has been more than a pleasure. He is smart, passionate, talented and articulate. He brought leadership and vision to building Front-End micro-services even with limited guidance."

**Md. Towhidul Islam** — Software Architect, Head of Technology (Direct Manager)

> "I have seen him transform from a developer to a leader of a team of developers within a very short time. He manages his own tasks while ensuring the team stays on track with release plans."

**Shabab Akhter** — People and Product Manager, Data and AI CoE (Same Team)

> "Hasan is a highly skilled problem solver and a very good team player. He takes ownership of his work and has strong leadership skill."

**Md Shahi Dullah** — Tech Lead, Solution Architect (Cross-team)

More recommendations: https://www.linkedin.com/in/ahasan09/details/recommendations/

---

## Education and Certification

| Program | Institution |
|---|---|
| M.Sc. in Computer Science and Engineering | Jahangirnagar University |
| B.Sc. in Computer Science and Engineering | Patuakhali Science and Technology University |
| C# .NET Certification (2013) | BASIS |

---

## Contact

If you are hiring for senior/staff engineering roles or want to collaborate on architecture-heavy frontend/platform work, I would be glad to connect.

- LinkedIn: https://www.linkedin.com/in/ahasan09/
- GitHub: https://github.com/ahasan09
- Email: mailto:abul.hasan@cefalo.com

Portfolio: https://ahasan09.github.io/
