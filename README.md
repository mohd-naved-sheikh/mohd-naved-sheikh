# 👋 Hi, I'm Mohd Naved

### 🚀 Software Development Engineer (SDE) | Java • Spring Boot • Backend • Distributed Systems

<p align="left">
  <a href="https://mohdnaved.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-mohdnaved.vercel.app-111111?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/mohd-naved-sheikh">
    <img src="https://img.shields.io/badge/LinkedIn-Mohd%20Naved-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:navedsheikh7983@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🧑‍💻 About Me

I'm **Mohd Naved**, a Software Development Engineer focused on building
secure, scalable, and production-oriented backend systems using **Java and
Spring Boot**.

My primary interests include:

- Backend Engineering
- Distributed Systems
- REST API Design
- Authentication & Authorization
- Database Engineering
- Caching & Performance Optimization
- Cloud Integration
- AI-powered Applications

I enjoy taking a system from **architecture → implementation → security →
database → deployment** and turning complex requirements into maintainable
software.

🎓 **B.Tech in Computer Science & Engineering**  
📍 **Bareilly, Uttar Pradesh, India**

---

## ⚡ What I Work With

| Area | Technologies |
|------|--------------|
| **Language** | Java |
| **Backend** | Spring Boot, Spring MVC, Spring Security |
| **Data Access** | Spring Data JPA, Hibernate |
| **APIs** | REST APIs |
| **Security** | OAuth2, JWT, RBAC, BCrypt |
| **Databases** | MySQL, MongoDB |
| **Caching** | Redis |
| **Cloud** | AWS S3 |
| **Frontend** | HTML, CSS, JavaScript, Thymeleaf, Bootstrap |
| **AI** | Google Gemini AI |
| **Payments** | Razorpay |
| **Build Tools** | Maven, Gradle |
| **Development** | Git, GitHub, Postman |
| **Architecture** | MVC, Layered Architecture, Clean Code |
| **Concepts** | OOP, DSA, DBMS, Software Design |

---

# 🏆 Featured Projects

## 🛒 AuraMart — AI-Powered Full-Stack E-Commerce Platform

> A production-oriented e-commerce platform built with Java and Spring Boot,
> featuring authentication, authorization, AI assistance, caching, cloud
> storage and online payments.

### 🔥 Core Features

- 🔐 Spring Security authentication & authorization
- 👥 Role-Based Access Control (RBAC)
- 🔑 Google OAuth2 authentication
- 🤖 **Aura AI** shopping assistant powered by Google Gemini
- 🛍️ Product, cart and order management
- 💳 Razorpay payment integration
- ☁️ AWS S3 cloud image storage
- ⚡ Redis caching
- 📧 Spring Mail integration
- 🗄️ MySQL + Hibernate + Spring Data JPA
- 🌐 RESTful API architecture
- 🏗️ Layered MVC architecture
- 🚀 HikariCP connection pooling

### 🧩 Architecture

```text
                    ┌─────────────────────┐
                    │      Frontend       │
                    │ Thymeleaf + HTML/CSS│
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Spring Security  │
                    │ OAuth2 • RBAC • JWT │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Spring Boot      │
                    │ Controllers / APIs   │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
            ┌────────┐    ┌────────┐   ┌──────────┐
            │ MySQL  │    │ Redis  │   │ AWS S3   │
            │Database│    │ Cache  │   │ Storage  │
            └────────┘    └────────┘   └──────────┘
                               │
                               ▼
                       ┌──────────────┐
                       │   Aura AI    │
                       │ Gemini API   │
                       └──────────────┘
