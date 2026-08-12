<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ANIMATED BANNER                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=shark&color=FFFFFF&text=Rahul%20Kata&fontColor=89B4FA&fontSize=55&animation=fadeIn&fontAlignY=55&desc=Java%20Backend%20Developer%20%7C%20Spring%20Boot%20%7C%20Microservices%20%7C%20AI%20Integration&descAlignY=75&descColor=89B4FA&descSize=17&height=175" />

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     TYPING SVG                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=3000&pause=900&color=89B4FA&center=true&vCenter=true&width=620&lines=%24+whoami+%E2%86%92+Java+Backend+Developer;%24+stack+%E2%86%92+Java+%7C+Spring+Boot+%7C+Kafka+%7C+Redis;%24+building+%E2%86%92+Secure+REST+APIs+%2B+AI+Applications;%24+focus+%E2%86%92+Microservices+%7C+Spring+AI+%7C+RAG;%24+open_to+%E2%86%92+Java+Backend+%2F+Software+Engineering+Roles)](https://git.io/typing-svg)

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   CONTACT BUTTONS                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

[![GitHub](https://img.shields.io/badge/GitHub-Kata--rahul15-89B4FA?style=for-the-badge&logo=github&logoColor=89B4FA&labelColor=FFFFFF)](https://github.com/Kata-rahul15)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kata--rahul-89B4FA?style=for-the-badge&logo=linkedin&logoColor=89B4FA&labelColor=FFFFFF)](https://www.linkedin.com/in/kata-rahul)
[![LeetCode](https://img.shields.io/badge/LeetCode-kata--rahul-89B4FA?style=for-the-badge&logo=leetcode&logoColor=89B4FA&labelColor=FFFFFF)](https://leetcode.com/u/kata-rahul/)
[![Gmail](https://img.shields.io/badge/Email-katarahul8@gmail.com-89B4FA?style=for-the-badge&logo=gmail&logoColor=89B4FA&labelColor=FFFFFF)](mailto:katarahul8@gmail.com)

<img src="https://komarev.com/ghpvc/?username=Kata-rahul15&label=Profile+Views&color=89B4FA&style=flat-square" alt="profile views" />

</div>

---

## About Me

Backend-focused developer building practical Java applications with Spring Boot. I design and implement secure REST APIs, work with distributed systems using Kafka and Redis, and apply transactional consistency principles to real engineering problems. Currently pursuing B.Tech in CSE and exploring AI-integrated backend development using Spring AI and RAG.

**Location:** Hyderabad, India &nbsp;|&nbsp; **Seeking:** Java Backend / Software Engineering Roles

---

## `> whoami`

```bash
ROLE      = Java Backend Developer
LOCATION  = Hyderabad, India
FOCUS     = Backend Engineering + AI Integration
LANGUAGE  = Java 17
BACKEND   = Spring Boot | Spring MVC | Spring Data JPA | Hibernate
SECURITY  = Spring Security | JWT | OAuth2
DATA      = MySQL | PostgreSQL | MongoDB | Redis
SYSTEMS   = Apache Kafka | Microservices Architecture
AI        = Spring AI 2.0 | Google Gemini | RAG | pgvector  [in progress]
BUILDING  = Resume RAG + AI Job Matching | TalentPrep
OPEN_TO   = Java Backend / Spring Boot / Software Engineering Roles
```

---

## 🛠 Tech Stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=java,python,js,html,css&theme=dark" />
</p>

### Backend & Frameworks
<p>
  <img src="https://skillicons.dev/icons?i=spring,maven&theme=dark" />
  &nbsp;
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white" />
</p>

### Databases & Caching
<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgresql,mongodb,redis&theme=dark" />
</p>

### Distributed Systems & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=kafka,docker,git,github,postman&theme=dark" />
</p>

### Security & APIs
<p>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-00D4FF?style=flat-square&logo=fastapi&logoColor=white" />
</p>

---

## 📊 Backend Expertise

| Area | Technologies | What I Build |
|:---|:---|:---|
| **Backend** | Java 17, Spring Boot, Spring MVC | Secure REST APIs and backend services |
| **Security** | Spring Security, JWT, OAuth2 | Stateless auth flows and access control |
| **Data** | JPA, Hibernate, Spring Data | Database-driven, persistence-layer systems |
| **Caching** | Redis | OTP storage, session caching |
| **Messaging** | Apache Kafka | Async event-driven communication |
| **Architecture** | Microservices | Modular, independently deployable services |
| **AI (building)** | Spring AI, RAG, pgvector | AI-powered backend features |

---

## 🚀 Featured Projects

<details>
<summary><b>🔐 TalentPrep — Secure Authentication Backend</b></summary>

<br/>

> A production-oriented, stateless authentication system built for the TalentPrep platform. Handles full-lifecycle user authentication with social login, email OTP verification, and asynchronous communication.

### Architecture

```
React Frontend (Vercel)
         │
         ▼
  Authentication API  ←── Spring Security Filter Chain
         │
    ┌────┼────────────────────┐
    ▼    ▼                    ▼
 MySQL  Redis (OTP cache)   Kafka
         │                   │
         └───► Email Service ◄┘
```

### What I Built

- **Authentication Flows:** User registration, credentials login, forgot/reset password, email OTP verification
- **Social Login:** Google OAuth2 and GitHub OAuth2 integration via Spring Security OAuth2 client
- **JWT Security:** Stateless token-based authentication with custom filter chain
- **OTP Handling:** Redis-backed time-limited OTP cache; OTP delivery via asynchronous Kafka events
- **Role-based Authorization:** Spring Security method-level and endpoint-level access control
- **Email Service:** Dedicated microservice module consuming Kafka events for email delivery
- **Global Exception Handling:** Structured error responses across all endpoints
- **REST API Design:** Clean API contract with proper status codes and response models
- **Database Persistence:** Spring Data JPA + MySQL with proper entity design

### Engineering Stack
`Java 17` `Spring Boot` `Spring Security` `Spring Data JPA` `JWT` `OAuth2 (Google + GitHub)` `Redis` `Apache Kafka` `MySQL` `REST APIs` `Maven`

### Repositories
- 🔗 [Authentication-System](https://github.com/Kata-rahul15/Authentication-System) — Standalone auth backend (deployed on Render)
- 🔗 [TalentPrep-Backend](https://github.com/Kata-rahul15/TalentPrep-Backend) — Multi-module: auth-service, email-service, common-events
- 🔗 [TalentPrep-Frontend](https://github.com/Kata-rahul15/TalentPrep-Frontend) — React/TypeScript frontend (deployed on Vercel)

</details>

---

<details>
<summary><b>💳 Banking Transaction Processing System</b></summary>

<br/>

> An ACID-compliant banking backend built to handle concurrent financial operations with strict data consistency guarantees. Designed around concurrency-safe patterns and proper transaction management.

### Architecture

```
REST Controller
      │
      ▼
 Service Layer  ──── @Transactional
      │
  ┌───┴───────────────┐
  ▼                   ▼
MySQL (JPA)        Kafka (post-commit events)
PESSIMISTIC_WRITE
```

### What I Built

- **ACID Transactions:** All financial operations wrapped in Spring `@Transactional` with rollback safety
- **Pessimistic Locking:** `PESSIMISTIC_WRITE` locking on account entities to prevent race conditions under concurrent requests
- **Deadlock Prevention:** Accounts locked in deterministic sorted order during transfers to avoid circular waits
- **BigDecimal Arithmetic:** Precision-safe monetary calculations throughout
- **Event-Driven Extension:** Kafka event publishing after successful commit (post-transaction)
- **Account Operations:** Create account, deposit, withdraw, transfer, transaction history
- **Data Integrity:** Guards against negative balances, partial transactions, and inconsistent state
- **Global Exception Handling:** Structured error responses for all failure paths
- **Unit Testing:** JUnit and Mockito for service-layer coverage

### Engineering Stack
`Java 17` `Spring Boot 3.1.5` `Spring Data JPA` `MySQL` `Apache Kafka` `JUnit` `Mockito` `Lombok`

### Repository
🔗 [banking-transaction-system](https://github.com/Kata-rahul15/banking-transaction-system)

</details>

---

<details>
<summary><b>📰 News Verification System — Secure Backend</b></summary>

<br/>

> A Spring Boot backend providing secure API endpoints for user-submitted news classification. Full authentication and authorization layer with custom JWT security filters and role-based access control.

### What I Built

- **JWT Authentication:** Custom JWT filter integrated into Spring Security filter chain
- **Stateless API Design:** No server-side session; all auth state carried in JWT
- **Role-based Access Control:** `USER` and `ADMIN` roles with endpoint-level enforcement
- **Request Validation:** Bean Validation on incoming request payloads
- **MySQL Persistence:** User, article, and classification data via Spring Data JPA
- **Global Exception Handling:** Unified error structure for auth errors, validation errors, and server errors
- **Secure REST Endpoints:** Proper HTTP method + role mapping for all resources

### Engineering Stack
`Java` `Spring Boot 3.2.3` `Spring Security` `Spring Data JPA` `JWT` `MySQL` `REST APIs`

### Repositories
- 🔗 [fake-news-backend](https://github.com/Kata-rahul15/fake-news-backend) — Spring Boot security backend
- 🔗 [fake-news-fastapi-ml](https://github.com/Kata-rahul15/fake-news-fastapi-ml) — FastAPI ML classification service (Python)
- 🔗 [fake-news-frontend](https://github.com/Kata-rahul15/fake-news-frontend) — React frontend

</details>

---

<details>
<summary><b>🤖 Resume RAG + AI Job Matching System &nbsp;<code>[ Currently Building ]</code></b></summary>

<br/>

> ⚠️ **Work in progress — not yet published to GitHub**

A backend system that parses resumes, generates semantic embeddings, stores them in a vector database, and uses RAG (Retrieval-Augmented Generation) to provide AI-powered insights and job matching.

### Architecture (in development)

```
Resume Upload (PDF / DOCX)
         │
         ▼
  Apache Tika (text extraction)
         │
         ▼
  Spring AI Embedding Service
  (PostgresML Embeddings)
         │
         ▼
  pgvector (PostgreSQL)  ←── Vector Store
         │
         ▼
  RAG Pipeline + Google Gemini
         │
         ▼
  REST API (Spring Boot)
```

### Technologies Being Used
`Spring Boot 4.1.0` `Spring AI 2.0.0` `Google Gemini` `PostgresML Embeddings` `PostgreSQL` `pgvector` `Apache Tika` `Spring Data JPA` `REST APIs` `Java 17`

### What I Am Building
- Resume parsing from PDF and DOCX using Apache Tika
- Semantic vector embeddings via PostgresML
- Vector similarity search using pgvector
- RAG pipeline with Google Gemini for intelligent Q&A
- REST APIs for resume upload, parsing, and AI-assisted job matching

> *Repository will be published once the core pipeline is stable.*

</details>

---

## 📈 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Kata-rahul15&show_icons=true&theme=transparent&title_color=00D4FF&icon_color=00FF94&text_color=C9D1D9&border_color=30363D&hide_border=false&count_private=true&include_all_commits=true" />
&nbsp;&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kata-rahul15&layout=compact&theme=transparent&title_color=00D4FF&text_color=C9D1D9&border_color=30363D&langs_count=7" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Kata-rahul15&theme=transparent&hide_border=false&stroke=30363D&ring=00D4FF&fire=00FF94&currStreakLabel=00D4FF&sideLabels=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="GitHub Streak" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Kata-rahul15&theme=react-dark&bg_color=0D1117&color=00D4FF&line=00FF94&point=00D4FF&area_color=00D4FF&area=true&hide_border=false&border_color=30363D&custom_title=Contribution%20Activity" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Kata-rahul15&theme=darkhub&no-frame=true&no-bg=true&column=6&margin-w=8&margin-h=8&rank=SECRET,SSS,SS,S,AAA,AA,A,B" />
</div>

---

## `> leetcode`

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-Practice%20%26%20DSA-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0D1117)](https://leetcode.com/u/kata-rahul/)

Practicing Data Structures and Algorithms in Java. &nbsp;[→ View Profile](https://leetcode.com/u/kata-rahul/)

</div>

---

## `> cat current-focus.yaml`

```yaml
learning:
  - Spring Boot & Spring Security
  - Microservices Architecture
  - System Design
  - Spring AI & RAG Pipelines

building:
  - Resume RAG + AI Job Matching System  # In progress
  - Backend-focused Spring Boot projects

improving:
  - Data Structures & Algorithms (Java)
  - Backend Architecture & Design Patterns
  - Distributed Systems (Kafka, Redis)

open_to:
  - Java Backend Developer
  - Spring Boot Developer
  - Software Engineer
  - Backend Engineer
  - AI-integrated Backend Roles
```

---

## 🎓 Education

| Degree | Institution | Year | Score |
|:---|:---|:---|:---|
| **B.Tech — Computer Science & Engineering** | Vignana Bharathi Institute of Technology, Ghatkesar | 2022 – 2026 | CGPA: 7.88 |
| Intermediate (Class XII) | Sri Chaitanya Junior College, ECIL | 2020 – 2022 | 83% |
| SSC | Balaji High School, Malkajgiri | 2019 – 2020 | GPA: 9.5 |

---

## 📜 Certifications & Programs

| Credential | Issuer | Type |
|:---|:---|:---|
| Foundations of Prompt Engineering | AWS Educate | Certification |
| Software Engineering Virtual Experience | JP Morgan Chase & Co. (Forage) | Virtual Experience |
| Java Full Stack | Wipro | Certification |
| Career Edge — Young Professional | TCS iON | Program |

> ℹ️ The JP Morgan Chase program is a **virtual experience** on the Forage platform, not employment at JPMorgan Chase.

---

## 🤝 Connect

<div align="center">

**Open to Java Backend, Spring Boot, and Software Engineering roles.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kata-rahul)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-00D4FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kata-rahul15)
[![Email](https://img.shields.io/badge/Email-katarahul8@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:katarahul8@gmail.com)

</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kata-rahul15/Kata-rahul15/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kata-rahul15/Kata-rahul15/output/github-snake.svg" />
    <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Kata-rahul15/Kata-rahul15/output/github-snake-dark.svg" />
  </picture>
</div>

---

<div align="center">

*Building backend systems, learning distributed architecture, and exploring practical AI integration.*

[![GitHub](https://img.shields.io/badge/-Kata--rahul15-00D4FF?style=flat-square&logo=github&logoColor=white)](https://github.com/Kata-rahul15)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/-kata--rahul-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kata-rahul)

<!-- Java Backend Developer | Spring Boot | Kafka | Redis | Microservices | Spring AI | RAG | Hyderabad -->
<!-- Keywords: java developer java backend developer spring boot developer backend developer spring boot java rest api spring security jwt oauth2 kafka redis microservices jpa hibernate mysql postgresql mongodb spring ai rag ai integration hyderabad india -->

</div>