# 👋 Marcus R. Kjærsgaard

> Junior Software Developer · Final-year IT Architecture student · Copenhagen

I’m interested in what sits behind a feature: its data, interfaces, dependencies, failure cases, and the people who need to work with it afterwards.

My public projects cover backend development, application security, software testing, database modelling and service architecture. Each tackles a different part of building and understanding software.

I currently work as a Junior Software Developer at [ZRM](https://www.zrm.dk/), developing integrations, automations and custom web applications alongside my studies.

---

## 🧭 Currently

- Working with APIs, data flows and web applications — from understanding requirements to development and maintenance.
- Using AI-assisted development in daily work, including the project instructions, context and documentation around the tools.
- Completing my Professional Bachelor’s Degree in IT Architecture at EK, Business Academy Copenhagen — expected graduation **January 2027**.

---

## 📌 Selected projects

Selected academic projects covering application security, software testing, database design and service architecture.

### 🔐 [SecureLeak](https://github.com/marcus-rk/SecureLeak)

A vulnerability-report tracker built for a web-security course, with particular attention to who can access reports and their attachments.

Report pages, comments and images share a deny-by-default access policy. Uploaded images pass through validation and re-encoding, are stored outside the public static directory, and are served through access-checked routes. Other controls include Argon2id password hashing, rate limiting and a Content Security Policy.

**Focus:** applying security controls across related application paths  
**Built with:** Python · Flask · SQLite · Pillow · pytest

### 💱 [Multi-Currency Wallet Simulator](https://github.com/marcus-rk/Multi-Currency-Wallet-Simulator)

A single-user wallet simulator built as a software-testing project. It supports DKK, EUR and USD, with deposits, withdrawals, currency exchange and wallet lifecycle rules.

A written specification provides the basis for the tests. Domain rules are separated from infrastructure, with time and transaction IDs passed in explicitly to make behaviour reproducible. Exchange-rate dependencies are stubbed in tests, including scenarios where a failed rate lookup must leave balances unchanged.

The repository includes unit and integration tests, API checks, browser scenarios and a JMeter load-test setup.

**Focus:** testable design, business rules and failure scenarios  
**Built with:** Python · Flask · SQLite · pytest · Playwright · Postman · JMeter

### 🎬 [Movie Rental — Polyglot Persistence API](https://github.com/DBD-Movie-Rental/movie-rental-main)

A two-person project implementing a movie-rental domain across MySQL, MongoDB and Neo4j behind a shared Flask API.

The interesting part is how the same domain changes shape across relational tables, documents and graph relationships. My contribution centred on the MongoDB implementation, including embedding-versus-reference decisions, collection validation, indexes and views. I also worked on data seeding and added and adapted MySQL stored-procedure logic.

**Focus:** database modelling, integrity constraints and storage trade-offs  
**Built with:** Flask · MySQL · MongoDB · Neo4j · OpenAPI/Swagger · Docker Compose

### 🚗 [Bilabonnement](https://github.com/Gruppe-H-Bilabonnement)

A car-subscription platform organised around an API Gateway and separate services for cars, rentals and damage handling.

The project centres on dividing responsibilities between services and connecting them through APIs.

**Focus:** service boundaries and communication  
**Built with:** Python · Flask · REST APIs · Docker · GitHub Actions · Azure

---

## 🛠 Languages & tools

### Application development

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

Python and Flask feature prominently in my public study projects. My current work also includes React, Next.js and TypeScript.

### Data & integrations

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Zoho One](https://img.shields.io/badge/Zoho_One-C8202F?style=flat-square&logo=zoho&logoColor=white)
![Deluge](https://img.shields.io/badge/Deluge-C8202F?style=flat-square)

My work includes SQL, Zoho Flow, CRM development, Deluge functions and API integrations. My study projects explore relational, document and graph databases.

### Testing & delivery

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)

---

## 🤖 AI in my development workflow

I use Claude Code and Codex in daily development and have helped set up AI-assisted workflows in two projects.

I’m interested in the work around the tools as well: keeping project instructions, documentation and architectural decisions useful as the code changes.

[![Claude Certified Architect: Foundations](https://img.shields.io/badge/Anthropic-Claude_Certified_Architect%3A_Foundations-D97757?style=flat-square)](https://www.credly.com/badges/6a3e2464-1386-4817-ae53-f77576b6280d/public_url)

---

<details>
<summary><strong>📘 Education & background</strong></summary>

### Professional Bachelor’s Degree in IT Architecture

**EK, Business Academy Copenhagen**  
August 2023 – January 2027 · Expected graduation

My studies connect software development with data, infrastructure, architecture and the organisational context around a system.

| Semester | Focus |
|---|---|
| **1st** | Understanding Data · Database Design · Web Technology · Visualization & Aesthetics · Digital Culture 1 |
| **2nd** | Application Development · User Involvement & Design · Agile Development · Digital Culture 2 |
| **3rd** | Software Architecture · Business Design & Analytics · System Development · Cloud Computing |
| **4th** | IT Infrastructure · IT Architecture · Enterprise Architecture · Project Monitoring & Management · System Design |
| **5th** | Databases for Developers · Software Testing · Web Security |
| **6th** | Internship at Danske Bank — Project Execution |
| **7th — current** | Philosophy of Science · Bachelor Project |

During my six-month internship at Danske Bank, I worked with architecture overviews, stakeholder interviews and project-delivery support.

I have also completed xUnlocked’s **AI and Data Foundations** and **Data and AI Essentials** programmes.

</details>

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcus-rk)
