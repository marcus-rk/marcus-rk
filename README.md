# 📍 Marcus R. Kjærsgaard - IT Architecture (Student)

I study **IT Architecture at Business Academy Copenhagen** and work where **business goals, system design, and implementation** meet.

Currently interning at **Danske Bank - Large Corporate & Execution (Business & Strategy)**, getting hands-on experience with how enterprise work actually happens: stakeholders, governance, delivery constraints, and decisions that must survive reality.

I enjoy translating “we need X” into:
- clear **system boundaries and models** (UML/BPMN)
- practical **APIs + data designs**
- solutions that are **secure, maintainable, and testable**

---

## 🎯 Current focus
- **Architecture & modelling:** UML, BPMN, system boundaries, documentation that people *use*
- **Secure backend design:** auth, input validation, threat-driven controls
- **Quality engineering:** testing from unit → integration → E2E, CI fundamentals
- **Data & integration:** relational/document/graph trade-offs, migrations, API contracts

---

## 📌 Selected projects

### 🔐 [SecureLeak](https://github.com/marcus-rk/SecureLeak)
A “fun meta” vulnerability/bug tracker built as a security-by-design playground: the app itself is the lesson.  
Focus is **OWASP Top 10-style mitigations** and layered controls rather than just “feature shipping”.
- Hardened auth (modern hashing + safe session/cookie practices)
- CSRF protection, XSS mitigations (templates + headers/policies), safer access control patterns
- SQL injection prevention via safe DB access patterns
- Secure file upload handling (validation + safe handling)
- Rate limiting + logging/auditability to support abuse resistance and traceability  
**Stack:** Python • Flask • SQLite • pytest

### 💱 [Multi-Currency Wallet Simulator](https://github.com/marcus-rk/Multi-Currency-Wallet-Simulator)
Backend-first wallet simulator with deposits, withdrawals, exchange, and transaction history — built to be **cleanly testable and integration-friendly**.
- Clear separation: domain rules vs services vs persistence (easier change + easier testing)
- External FX rates integration designed to be test-stubbable (no flaky tests)
- Strong testing focus across levels (API tests, E2E, performance tooling, etc.)  
**Stack:** Python • Flask • SQLite • Docker • testing toolchain

### 🎬 [Movie Rental — Polyglot Persistence API](https://github.com/DBD-Movie-Rental/movie-rental-main)
Same movie-rental domain exposed through one API, implemented across **MySQL, MongoDB, and Neo4j**.  
The point is to show what changes when the storage model changes — and how you keep an API contract stable.
- Three implementations side-by-side (relational / document / graph)
- Migration scripts between stores + seeding
- OpenAPI/Swagger + Docker Compose to run the whole system locally  
**Stack:** Flask • MySQL • MongoDB • Neo4j • OpenAPI/Swagger • Docker Compose

### 🎵 [Beatmaker — Online Sequencer](https://github.com/marcus-rk/beatmaker)
Interactive browser sequencer for creating rhythms. Built to practice **UI flow, responsiveness, and turning user interactions into a coherent experience**.  
**Stack:** JavaScript • HTML • CSS

---

## 🛠 Tech stack & tools (badges because yes)

### Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & APIs
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Swagger](https://img.shields.io/badge/OpenAPI%2FSwagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Data
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018bff?style=for-the-badge&logo=neo4j&logoColor=white)

### DevOps & testing/tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Modelling & architecture
![UML](https://img.shields.io/badge/UML-02569B?style=for-the-badge&logoColor=white)
![BPMN](https://img.shields.io/badge/BPMN-000000?style=for-the-badge&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda-FFCC00?style=for-the-badge&logo=camunda&logoColor=black)

---

## 📘 Semester overview (courses + what I took from them)

| Semester | Courses | What I learned / practiced |
|---|---|---|
| **1st** | Understanding Data • Database Design • Web Tech • Visualization & Aesthetics • Digital Culture 1 | Data basics, relational thinking, building for users (not just for code), communicating visually |
| **2nd** | App Development • User Involvement & Design • Agile Development • Digital Culture 2 | User-centered development, iterative delivery, requirement shaping, teamwork rhythms |
| **3rd** | Software Architecture • Business Design & Analytics • System Development • Cloud Computing | Architecture foundations, aligning systems to business goals, cloud as design constraints |
| **4th** | IT Infrastructure • IT Architecture • Enterprise Architecture • Project Monitoring/Management • System Design | Enterprise-level thinking: systems-of-systems, governance, documentation, and delivery trade-offs |
| **5th** | Software Testing • Security for Web Developers • Advanced Databases | Quality as a system property, threat-aware design, database design beyond CRUD (performance, consistency, modeling) |

---

## 🔗 Contact
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcus-rk)

---

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=marcus-rk&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=marcus-rk&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=marcus-rk&theme=github)
