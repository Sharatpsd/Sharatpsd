<!--
  README.md — GitHub Profile
  Owner: Sharat Acharja Mugdho (github.com/Sharatpsd)

  Notes:
    - Repo must be named exactly "Sharatpsd" (same as username) to render as the profile README.
    - Snake animation requires the companion workflow file:
        .github/workflows/snake.yml
      It needs one push / manual Action run before the SVG exists.
    - Project screenshots are intentionally NOT included yet. Search for
      "ADD SCREENSHOT" comments below to find the exact spots to drop real images
      (recommended: 1200x630 PNG/WebP, committed to an /assets folder in this repo).

  REDESIGN NOTE (2026):
    - Restructured into: Hero → Currently Building → Engineering Snapshot → About →
      Tech Stack → Architecture → Featured Projects → Experience → Research →
      Engineering Principles → GitHub Activity → Exploring Next → Beyond Code → Contact.
    - Badge count reduced sharply; tech stack is now text-based and grouped.
    - All original links, projects, experience, research, and credentials preserved.
-->

<!-- ============================== HERO ============================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:0D1117,50:10B981,100:0D1117" alt="" />

<br><br>

# Sharat Acharja Mugdho

**Backend Engineer • Django • Odoo • PostgreSQL**

Building production-oriented backend systems, REST APIs and enterprise ERP solutions.

<br>

<img
  src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=17&pause=3200&color=10B981&center=true&vCenter=true&width=520&height=32&lines=Backend+Systems+with+Django;Enterprise+ERP+with+Odoo+19;REST+APIs+%E2%80%A2+PostgreSQL+%E2%80%A2+Redis;Production-Oriented+Software"
  alt="Backend Systems with Django — Enterprise ERP with Odoo 19 — REST APIs, PostgreSQL, Redis — Production-Oriented Software"
/>

<br>

<a href="https://sharatpsd.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logoColor=10B981" alt="Portfolio" /></a>
<a href="https://github.com/Sharatpsd"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=10B981" alt="GitHub" /></a>
<a href="https://linkedin.com/in/sharat-acharjya"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=10B981" alt="LinkedIn" /></a>
<a href="mailto:sharatacharjee6@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=10B981" alt="Email" /></a>

<sub>Dhaka, Bangladesh</sub>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:0D1117,50:10B981,100:0D1117" alt="" />

</div>

<br>

<!-- ============================== CURRENTLY BUILDING ============================== -->

## ⚡ Currently Building

Enterprise ERP work at **Betopia Group** — customizing Odoo 19 for real business workflows.

<table width="100%">
<tr>
<td align="center" width="33%"><strong>Odoo 19 ERP</strong><br><sub>Custom module development</sub></td>
<td align="center" width="33%"><strong>Workflow Customization</strong><br><sub>Enterprise business processes</sub></td>
<td align="center" width="33%"><strong>Python Backend</strong><br><sub>Odoo ORM &amp; server logic</sub></td>
</tr>
<tr>
<td align="center"><strong>PostgreSQL</strong><br><sub>Database operations</sub></td>
<td align="center"><strong>ERP Automation</strong><br><sub>Actions, menus &amp; rules</sub></td>
<td align="center"><strong>Process Optimization</strong><br><sub>Access rights &amp; record rules</sub></td>
</tr>
</table>

<br>

<!-- ============================== ENGINEERING SNAPSHOT ============================== -->

## Engineering Snapshot

<table width="100%">
<tr>
<td align="center" width="16%"><sub>BACKEND</sub><br><strong>Django / DRF</strong></td>
<td align="center" width="16%"><sub>ENTERPRISE</sub><br><strong>Odoo 19</strong></td>
<td align="center" width="16%"><sub>DATABASE</sub><br><strong>PostgreSQL</strong></td>
<td align="center" width="16%"><sub>ASYNC</sub><br><strong>Redis / Celery</strong></td>
<td align="center" width="16%"><sub>DEVOPS</sub><br><strong>Docker / CI-CD</strong></td>
<td align="center" width="16%"><sub>RESEARCH</sub><br><strong>Explainable AI</strong></td>
</tr>
</table>

<br>

<!-- ============================== ABOUT ============================== -->

## About

I build backend systems that are meant to run in production, not just in a demo: Django and DRF services with clear API contracts, JWT/RBAC authentication, PostgreSQL schemas designed for real query patterns, and Celery + Redis for background work and caching. Everything ships Dockerized, with CI/CD through GitHub Actions and a Linux-first workflow — every project on this profile is deployed and live.

Currently I work as a **Trainee Executive — MIS & ERP at Betopia Group**, developing and customizing **Odoo 19** modules in a live production environment: Odoo ORM, XML views, business workflow customization, access rights and record rules. On the research side, I've published IEEE work on explainable deep learning (ResNet50, Grad-CAM, SHAP) — the engineering problems I care most about are correctness under real usage, query performance, and systems that stay auditable and maintainable as they grow.

<br>

<!-- ============================== TECH STACK ============================== -->

## Tech Stack

<table width="100%">
<tr>
<td valign="top" width="50%">

**Backend**
<br>Python · Django · Django REST Framework · FastAPI · Celery · JWT

**Enterprise / ERP**
<br>Odoo 19 · Odoo ORM · XML Views · OWL · Record Rules · Access Rights

**Database**
<br>PostgreSQL · Redis · MySQL · SQLite

</td>
<td valign="top" width="50%">

**Frontend**
<br>React · TypeScript · JavaScript · Tailwind CSS · Vite

**DevOps & Cloud**
<br>Docker · Linux · GitHub Actions · Render · Vercel · Netlify · Cloudinary

**Tools & AI/ML**
<br>Git · VS Code · Postman · Swagger · PyTorch · scikit-learn · Pandas

</td>
</tr>
</table>

<br>

<!-- ============================== ARCHITECTURE ============================== -->

## How I Build Systems

**Django backend architecture** — the shape most of my API projects follow:

```mermaid
flowchart TD
    A[Client] --> B[Frontend — React / TypeScript]
    B --> C[Django REST API]
    C --> D[Business Logic]
    D --> E[(PostgreSQL)]
    D --> F[Redis + Celery — cache & background jobs]
    C --> G[Docker / CI-CD — GitHub Actions]
```

**Odoo 19 architecture** — how enterprise customization flows at the ERP layer:

```mermaid
flowchart TD
    A[Odoo UI] --> B[XML / OWL Views]
    B --> C[Odoo Models — Python]
    C --> D[Odoo ORM]
    D --> E[(PostgreSQL)]
```

<br>

<!-- ============================== FEATURED PROJECTS ============================== -->

## Featured Projects

<table>
<tr>
<td width="33%" valign="top">

### Bite — Food Delivery Platform

<!-- ADD SCREENSHOT: replace this comment with
<img src="assets/bite.png" alt="Bite food delivery platform — customer ordering interface" width="100%" />
Recommended: 1200x630 real screenshot of the live app. -->

Production-deployed food delivery platform for customers, vendors, and administrators. Implemented multi-role ordering workflow with authenticated checkout, JWT-secured REST APIs, and role-based access control across the platform.

`Django` `DRF` `React` `PostgreSQL` `JWT` `Tailwind CSS`

- Multi-role authentication (Customer, Vendor, Admin)
- JWT authentication with RBAC
- Cart, checkout & order management workflow
- Production-ready REST API layer

<a href="https://github.com/Sharatpsd/Food-Delivery-App-"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=10B981" alt="Bite on GitHub" /></a>
<a href="https://bite-bd.onrender.com/"><img src="https://img.shields.io/badge/Live_Demo-10B981?style=for-the-badge&logoColor=0D1117" alt="Bite live demo" /></a>

</td>
<td width="33%" valign="top">

### Daily Dairy Shop

<!-- ADD SCREENSHOT: replace this comment with
<img src="assets/daily-dairy-shop.png" alt="Daily Dairy Shop — product catalog and cart" width="100%" />
Recommended: 1200x630 real screenshot of the live app. -->

E-commerce backend deployed as a Dockerized service with automated CI/CD. Covers authentication, product and inventory management, cart and order processing, with Cloudinary handling media storage.

`Django` `PostgreSQL` `Docker` `Cloudinary` `GitHub Actions`

- Product & inventory management
- Shopping cart & order processing
- Dockerized deployment pipeline
- CI/CD automation with GitHub Actions

<a href="https://github.com/Sharatpsd/DailyDairyShop"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=10B981" alt="Daily Dairy Shop on GitHub" /></a>
<a href="https://dailydairyshop-3.onrender.com/"><img src="https://img.shields.io/badge/Live_Demo-10B981?style=for-the-badge&logoColor=0D1117" alt="Daily Dairy Shop live demo" /></a>

</td>
<td width="33%" valign="top">

### Chai Order System

<!-- ADD SCREENSHOT: replace this comment with
<img src="assets/chai-order-system.png" alt="Chai Order System — order management dashboard" width="100%" />
Recommended: 1200x630 real screenshot of the live app. -->

Order management system built around asynchronous processing: Celery background jobs with Redis for caching, a dynamic pricing engine, and role-based access control — packaged in a modular, Dockerized backend.

`Django` `Redis` `Celery` `SQLite` `Docker`

- Dynamic pricing engine
- Celery background task processing
- Redis caching integration
- Modular backend architecture

<a href="https://github.com/Sharatpsd/chai-order-system"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=10B981" alt="Chai Order System on GitHub" /></a>
<a href="https://chai-order-system-5.onrender.com/"><img src="https://img.shields.io/badge/Live_Demo-10B981?style=for-the-badge&logoColor=0D1117" alt="Chai Order System live demo" /></a>

</td>
</tr>
</table>

<div align="center">
<sub>More projects, architecture notes and live demos on the <a href="https://sharatpsd.netlify.app/">portfolio</a>.</sub>
</div>

<br>

<!-- ============================== EXPERIENCE ============================== -->

## Experience

**Trainee Executive — MIS & ERP** · Betopia Group, Dhaka
<br><sub>July 15, 2026 – Present</sub>

Developing and customizing Odoo 19 ERP modules in production. Backend development in Python with the Odoo ORM and XML views; business workflow customization; access rights and record rules; actions and menu configuration; PostgreSQL database operations and bug fixing in a Linux + Git environment.

---

**Backend Developer Intern** · Robo Tech Valley, Dhaka
<br><sub>2025</sub>

Built and maintained REST APIs with Django REST Framework. Implemented JWT auth, refresh-token workflows, and RBAC for multi-role applications. Worked on ORM/query optimization and collaborated with frontend developers on API integration. → Certificate under Research & Credentials below.

---

**B.Sc. in Computer Science & Engineering** · Green University of Bangladesh
<br><sub>Graduated January 2026</sub>

<br>

<!-- ============================== RESEARCH ============================== -->

## Research & Credentials

<table width="100%">
<tr><td>

**📄 IEEE Published — Explainable Deep Learning for Multi-Disease Ocular Classification and Severity-Aware Myopia Analysis**

An end-to-end deep learning pipeline for multi-disease retinal classification built around a **ResNet50** backbone, with explainability layers — **Grad-CAM** for visual attention mapping and **SHAP** for feature-level interpretability — so predictions stay auditable rather than acting as a black box.

<a href="https://drive.google.com/file/d/1XVzO6kOMtIVtVqfTo52M3sQzBVn16Mk2/view"><img src="https://img.shields.io/badge/Read_the_Paper-0D1117?style=for-the-badge&logo=googlescholar&logoColor=10B981" alt="Read the paper" /></a>

</td></tr>
<tr><td>

**🎓 Backend Developer Intern Certificate — Robo Tech Valley**

<a href="https://drive.google.com/file/d/1Jw82jFGXPvliJHYxBPOUh6oIlpm-j8mE/view"><img src="https://img.shields.io/badge/View_Certificate-0D1117?style=for-the-badge&logo=googledrive&logoColor=10B981" alt="View certificate" /></a>

</td></tr>
</table>

<br>

<!-- ============================== ENGINEERING PRINCIPLES ============================== -->

## 🧠 Engineering Principles

<table width="100%">
<tr>
<td valign="top" width="50%">

- API-first design with clear contracts
- Secure authentication (JWT, RBAC)
- Database-aware development
- Query optimization under real usage
- Background processing for slow work

</td>
<td valign="top" width="50%">

- Modular architecture & separation of concerns
- Production debugging over guesswork
- CI/CD as the default, not an afterthought
- Maintainability as a feature
- Auditable systems — no black boxes

</td>
</tr>
</table>

<br>

<!-- ============================== GITHUB ACTIVITY ============================== -->

## GitHub Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Sharatpsd&theme=react-dark&bg_color=0D1117&color=10B981&line=10B981&point=FFFFFF&area=true&hide_border=true" alt="GitHub contribution activity graph" />

<img width="100%" src="https://raw.githubusercontent.com/Sharatpsd/Sharatpsd/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation" />

</div>

<br>

<!-- ============================== EXPLORING NEXT ============================== -->

## 🔭 Exploring Next

Areas I'm actively learning and deepening — distinct from my professional experience above:

`FastAPI` · `Advanced PostgreSQL` · `Redis patterns` · `Celery at scale` · `System Design` · `Cloud / DevOps` · `Odoo OWL framework`

<br>

<!-- ============================== BEYOND CODE ============================== -->

## Beyond Code

Photography · Travel · Football — Real Madrid 🤍

<br>

<!-- ============================== CONTACT ============================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:0D1117,50:10B981,100:0D1117" alt="" />

<br><br>

### Let's build something useful.

<a href="https://sharatpsd.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logoColor=10B981" alt="Portfolio" /></a>
<a href="https://github.com/Sharatpsd"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=10B981" alt="GitHub" /></a>
<a href="https://linkedin.com/in/sharat-acharjya"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=10B981" alt="LinkedIn" /></a>
<a href="mailto:sharatacharjee6@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=10B981" alt="Email" /></a>
<a href="https://wa.me/8801783720914"><img src="https://img.shields.io/badge/WhatsApp-0D1117?style=for-the-badge&logo=whatsapp&logoColor=10B981" alt="WhatsApp" /></a>

<br><br>
<sub>Dhaka, Bangladesh</sub>

</div>
