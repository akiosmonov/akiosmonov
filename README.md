# Akbar Osmonov

**Full-Stack Developer** — Bishkek, Kyrgyzstan · Open to remote, hybrid, or relocation  
I build production-grade web applications with **TypeScript, Next.js, and Node.js**, backed by **PostgreSQL and Prisma ORM**. Most of my work sits on full-stack architecture: transactional logic, concurrency control, state-synchronized UIs, real-time pipelines, and security middleware.

---

### What I work with

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)


**Frontend** · JavaScript (ES6+) · TypeScript · React · Next.js (App Router, Server Actions) · Zustand · Tailwind CSS · Framer Motion<br>

**Backend** · Node.js · Prisma ORM · PostgreSQL · REST APIs<br>

**Data & Security** · Database Transactions · Race Condition Prevention · Query Optimization · JWT Cookies · CSP · Timing-Attack Protection

**Infra** Docker · Vercel · Pusher (WebSockets) · Resend API · Telegram Bot API · Git / GitHub

### Selected work

**🏢 Grayton — Enterprise PMS & CRM SaaS Platform**
A commercial-grade SaaS platform for hotel automation and property management built with Next.js 15, PostgreSQL, and Prisma ORM.

Concurrency & Safety: The core challenge was concurrent bookings causing overbooking race conditions. I eliminated this entirely at the database level using atomic Prisma transactions rather than application-layer checks.

Interactive UI: Developed a state-synchronized booking grid ("shahmatka") and an interactive SVG floor map with live room-status filtering and seamless DB binding.

Real-Time & Automation: Integrated Pusher WebSockets for instant status updates and live audio alerts across connected front-desk operators. Built and containerized automated Telegram management bots using Docker.

Security Framework: Engineered middleware with rate limiting, strict Content Security Policies (CSP), protection against timing attacks via crypto.timingSafeEqual, and secure JWT cookie authentication.

**🛒 Organick — E-Commerce Grocery Marketplace**
A high-performance grocery marketplace built on React and TypeScript.

Designed a lightweight global state management pipeline using Zustand with persistent client cart states.

Implemented modular component architecture and optimized client-side price/cart calculations.

**🎬 MovieDB — TMDB Media Discovery Platform**
A media aggregator built on React and TMDB REST API.

Focused on client-side bookmarking, local storage caching, sub-second page transitions, and complete multi-language localization (i18n).

**📚 Bookshop — E-Commerce & Admin Platform**
A functional book marketplace featuring an administrative dashboard and an intelligent multi-endpoint API rate-limit bypass handler.

Work & Mentorship Experience
Mentor Assistant & Technical Code Reviewer — Navis Academy

Conducted architectural audits and code reviews for developers on advanced React.js and TypeScript tracks.

Assisted in state management refactoring, component tree optimization, and Vercel/Git deployment troubleshooting.

### How I work
I integrate AI tooling (Cursor, Claude AI) into my daily workflow to accelerate prototyping, boilerplate code generation, and complex logic architecture. I maintain 100% ownership over the code that ships: architectural decisions — like the transaction model in Grayton and security middleware — are choices I designed, implemented, and can defend line by line.

### Currently
Going deeper into Next.js 15 Server Actions optimization, advanced PostgreSQL concurrency/indexing models, and scalable backend microservice architectures.

📫 darken452@gmail.com ·  [LinkedIn](https://www.linkedin.com/in/akbar-osmonov-245b6a3bb/) · English B2
