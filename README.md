<div align="center">
  <img width="100%" src="banner4.jpg" alt="Profile Banner" />

  # Ashikur Rahaman
  ### **Full-Stack Software Developer**
  **Next.js · React · Node.js · Backend & Database Engineering**

  <p align="center">
    Building business-oriented web applications with a focus on backend architecture, authentication, data integrity, and maintainable application design.
  </p>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mdaashikur)
  [![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mdaashikur@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/aashikur)
</div>

---

### 👨‍💻 Profile & Overview

I build full-stack web applications focused on solving practical business problems. My work spans frontend development, backend architecture, API design, authentication, database modeling, and third-party integrations.

I enjoy turning complex requirements into maintainable software — from e-commerce platforms and financial applications to learning management systems.

- 📍 **Location:** Bangladesh *(Available for Worldwide Remote Roles)*
- 💻 **Core Focus:** Full-Stack Development & Backend Engineering
- 🏗️ **Current Work:** Building business-oriented applications and independent products
- 🌱 **Actively Improving:** TypeScript, Software Testing, System Design, and Database Engineering

---

### 🛠️ Technical Skills

| Domain | Technologies & Competencies |
| :--- | :--- |
| **Frontend Development** | React.js, Next.js (App Router), JavaScript (ES6+), TypeScript *(actively improving)*, HTML5, CSS3, Tailwind CSS, Redux Toolkit / RTK Query, Responsive UI Development |
| **Backend Development** | Node.js, Express.js, RESTful API Design, Authentication & Authorization, Role-Based Access Control (RBAC), Request Validation (Zod), API Integration, Server-side Business Logic |
| **Databases & Storage** | MongoDB & Mongoose, PostgreSQL, Prisma ORM, Drizzle ORM, IndexedDB (Dexie.js), Cloudflare R2 |
| **Auth & Integrations** | Better Auth, JWT & HTTP-only Cookies, Google OAuth, SSLCommerz, Stripe, Cloudinary & Vimeo APIs, Third-party REST APIs |
| **Tools & Deployment** | Git, GitHub, Postman, VS Code, Vercel, Linux / VPS, PM2, Cloudflare, AWS S3-compatible SDK |

---

### 🚀 Featured Engineering Projects

#### 1. 💼 Aurem — Config-Driven E-Commerce Platform
> *A full-stack headless e-commerce platform and merchant management system built with Next.js 16, React 19, and MongoDB.*

* **Layered Architecture:** Separated transport, domain services, persistence, and adapter responsibilities to keep business logic independent of HTTP handlers.
* **Transactional Inventory:** Implemented server-authoritative pricing and conditional atomic stock updates to reduce overselling risks during concurrent checkout.
* **Authentication & RBAC:** Integrated Better Auth with secure HTTP-only sessions and role-based administrative access.
* **Media Infrastructure:** Integrated Cloudflare R2 through the S3 SDK, image optimization, and Cloudinary fallback.
* **Bangladesh Logistics:** Implemented localized checkout validation, delivery zones, and Steadfast Courier API integration.
* **Caching Strategy:** Used tag-based caching and targeted cache invalidation for application data.
* **Tech Stack:** `Next.js 16` · `React 19` · `TypeScript` · `MongoDB` · `Mongoose` · `Better Auth` · `Tailwind CSS v4` · `Cloudflare R2` · `AWS S3 SDK`
* **Links:** [🌐 Live Application](#) • [💻 Client Repo](#) • [⚙️ Server Repo](#)

---

#### 2. 📒 CashBook — Offline-First Financial Ledger PWA
> *A multi-tenant expense management Progressive Web App designed around local-first data access, background synchronization, and long-term financial record management.*

* **Offline-First Architecture:** Used Dexie.js and IndexedDB for local CRUD operations, cached records, and background synchronization.
* **Synchronization Engine:** Implemented delta-sync workflows and idempotency keys to support reliable synchronization between local and remote data.
* **Financial Data Integrity:** Used integer-based paisa/cents representation to avoid floating-point precision issues in financial calculations.
* **Cloud Storage:** Integrated Cloudflare R2 with presigned S3-compatible upload URLs and client-side image compression.
* **Multi-Tenant Security:** Implemented organization-scoped access control using Better Auth and Admin / Viewer roles.
* **Database Design:** Structured PostgreSQL data using Drizzle ORM, with composite indexes for organization and fiscal-period queries.
* **Tech Stack:** `Next.js 15` · `React 19` · `TypeScript` · `PostgreSQL` · `Neon` · `Drizzle ORM` · `Dexie.js` · `IndexedDB` · `Better Auth` · `Cloudflare R2` · `Zustand` · `Zod`
* **Links:** [🌐 Live Application](#) • [💻 Client Repo](#) • [⚙️ Server Repo](#)

---

#### 3. 🏋️ VectorFitLab — Fitness LMS & Digital Commerce Platform
> *A full-stack fitness education and digital marketplace platform built for course delivery, athlete management, and online training workflows.*

* **Feature-Based Architecture:** Organized application features into reusable components, hooks, services, and types.
* **Course Management:** Implemented courses, learning modules, lessons, batch scheduling, assignments, and progress tracking.
* **Video Infrastructure:** Integrated Vimeo APIs, resumable TUS uploads, and media processing workflows.
* **Payments & Enrollment:** Integrated SSLCommerz with manual payment verification, coupon validation, and enrollment management.
* **Role-Based Security:** Implemented JWT authentication, HTTP-only cookies, and Admin / Trainer / Athlete permissions.
* **Runtime Validation:** Used Zod for request validation and application data contracts.
* **Tech Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `Redux Toolkit` · `RTK Query` · `Tailwind CSS v4` · `Zod` · `SSLCommerz` · `Vimeo API`
* **Links:** [🌐 Live Application](https://vectorfitlab.com) • [💻 Client Repo](https://github.com/aashikur/vectorfitlab-client) • [⚙️ Server Repo](https://github.com/aashikur/vectorfitlab-server)

---

#### 4. 🎓 RedLabStudio — Learning Management System
> *A client-oriented learning management and video course delivery platform built to support online education operations and multi-role administration.*

* **Role-Based Access Control:** Implemented Admin, Instructor, and Student access permissions.
* **Learning Management:** Developed course, module, lesson, enrollment, and learning progression workflows.
* **Media Delivery:** Integrated video delivery infrastructure and resumable upload workflows.
* **Payment Integration:** Implemented SSLCommerz payment workflows, coupon validation, and enrollment tracking.
* **Content Management:** Integrated Tiptap rich-text editing and certificate generation.
* **Data Validation:** Applied Zod schemas for runtime validation across application workflows.
* **Tech Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `Redux Toolkit` · `RTK Query` · `Tailwind CSS v4` · `Zod` · `SSLCommerz` · `Vimeo / Bunny CDN`
* **Links:** [🌐 Live Application](https://redlabstudio.com) • [💻 Client Repo](https://github.com/aashikur/redlabstudio-client) • [⚙️ Server Repo](https://github.com/aashikur/redlabstudio-server)

---

### 🎯 Current Engineering Focus

* Deepening TypeScript knowledge and type-safe application development.
* Improving backend architecture, modularity, and separation of concerns.
* Designing reliable database schemas and robust data access layers.
* Understanding transaction safety, concurrency, and data consistency.
* Strengthening authentication, authorization, and application security.
* Learning unit, integration, and end-to-end testing practices.
* Improving deployment, monitoring, and production debugging workflows.

---

### 💡 Engineering Principles

* **Build for Business:** Align architectural choices with real business requirements, not hype.
* **Separation of Concerns:** Keep core domain and business logic distinct from transport and infrastructure.
* **Data Integrity First:** Prioritize schema validation, consistent typing, and transactional consistency.
* **Pragmatic Simplicity:** Avoid premature abstraction and overengineering; write code that is easy to read and maintain.
* **Clear Documentation:** Document architecture decisions and contracts so team members can onboard quickly.

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aashikur&theme=github-compact&hide_border=true" width="100%" alt="GitHub Activity Graph" />
</p>

---

### 📫 Let's Connect

I am actively open to discussing software engineering roles, contract projects, and technical collaborations.

* 📧 **Email:** [mdaashikur@gmail.com](mailto:mdaashikur@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/mdaashikur](https://linkedin.com/in/mdaashikur)
* 🐙 **GitHub:** [github.com/aashikur](https://github.com/aashikur)

<div align="center">
  <sub><i>“Build practical software. Learn through engineering.”</i></sub>
</div>
