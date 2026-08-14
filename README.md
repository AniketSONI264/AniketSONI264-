<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=6E40C9&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Aniket+Soni+%F0%9F%91%8B;Full-Stack+%2F+Backend+Developer;TypeScript+%C2%B7+Node.js+%C2%B7+PostgreSQL;Building+systems%2C+not+just+features;open_to_work+%3D%3D+true" alt="Typing SVG" />

<br>

<a href="https://www.linkedin.com/in/ani--ket">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:aniketsoni3529@hgmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://medisetu.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=vercel&logoColor=white" />
</a>

 

<img src="https://komarev.com/ghpvc/?username=AniketSONI264&label=profile+views&color=6E40C9&style=flat-square" />

</div>

---

```text
$ whoami --verbose

┌─[aniket@dev]─[~]
│
│  name:        Aniket Soni
│  role:        Full-Stack / Backend Developer
│  focus:       Backend Engineering · APIs · Databases · System Design
│  stack:       TypeScript · Node.js · PostgreSQL · React / Next.js
│  education:   MCA · AKS University · 2025 · CGPA 8.12
│  location:    Satna, Madhya Pradesh, IN
│  status:      seeking full-time opportunities
│  relocation:  open
│
└─[$] _
```

## `> cat about.md`

I’m a **Full-Stack / Backend Developer** with an MCA background and hands-on experience building web applications across the MERN ecosystem and beyond.

My primary interest is backend engineering — designing APIs, authentication flows, business logic, database models, integrations, and systems that remain understandable after the initial excitement of shipping is gone.

I’m currently moving deeper into **TypeScript, PostgreSQL, system design, testing, CI/CD, and production-oriented architecture**.

```text
frontend
   │
   ▼
React / Next.js
   │
   ▼
API layer
   │
   ▼
Business logic
   │
   ▼
PostgreSQL / MongoDB / MySQL
   │
   ▼
Docker · CI/CD · Cloud
```

> `make it work → make it correct → make it maintainable`

---

## `> ls ./experience`

```text
Site Guru/             Full Stack Developer Intern      Jan 2025 – Mar 2025
YourLab.in/            Backend Developer Intern         Jul 2024 – Oct 2024
Bharat Intl School/    IT & CS Instructor
```

---

## `> ./stack --show`

<div align="center">

### Languages & Runtime

<img src="https://skillicons.dev/icons?i=js,ts,py,nodejs" />

### Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,vue,tailwind" />

### Backend & APIs

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi" />

### Databases

<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis" />

### DevOps & Tooling

<img src="https://skillicons.dev/icons?i=git,github,docker,githubactions,pnpm,vercel" />

</div>

---

## `> ./projects --featured`

<table>
<tr>

<td width="50%" valign="top">

### 🧾 LedgerPilot

`building` · engineering-first backend system

```text
architecture:
  modular monolith

apps:
  api     → NestJS
  web     → Next.js
  ai      → FastAPI

data:
  PostgreSQL

infra:
  Redis · BullMQ

engineering:
  TypeScript
  testing
  validation
  CI/CD
```

**LedgerPilot** is my current flagship project and a deliberate move toward more serious backend engineering.

The goal isn't another CRUD demo.

It's an exploration of how to structure a maintainable system around clear boundaries, relational data, asynchronous workloads, AI capabilities, testing, and production-oriented engineering practices.

`TypeScript` `NestJS` `Next.js` `FastAPI` `PostgreSQL` `Redis` `BullMQ`

</td>

<td width="50%" valign="top">

### 🛒 MJS PRO

<a href="https://mjspro.in/">live →</a> · multi-vendor e-commerce

```text
+ vendor onboarding
+ product & inventory management
+ 30+ REST endpoints
+ order workflows
+ Razorpay payments
+ webhook handling
+ RBAC
+ normalized SQL schema
```

A full-stack marketplace handling vendor, product, payment, and order workflows end-to-end.

Built to solve actual business workflows rather than stopping at a shopping-cart UI.

`Node.js` `Express` `MySQL` `Razorpay`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🏥 MediSetu

<a href="https://medisetu.vercel.app/">live →</a> · telehealth platform

```text
+ JWT authentication
+ Google OAuth
+ doctor verification
+ appointment scheduling
+ consultation workflows
+ admin dashboard
+ media management
```

A healthcare platform connecting patients and providers through authentication, scheduling, consultation, and administrative workflows.

`Next.js` `MongoDB` `OAuth 2.0` `Cloudinary`

</td>

<td width="50%" valign="top">

### 🤖 DevSense AI

`building` · AI-assisted developer tooling

```text
+ FastAPI backend
+ Celery workers
+ Redis
+ pgvector
+ semantic search
+ OpenAI API
+ background processing
```

Exploring AI-powered code review and developer productivity through LLMs, semantic context, and asynchronous backend processing.

`FastAPI` `PostgreSQL` `pgvector` `Celery` `OpenAI`

</td>

</tr>
</table>

---

## `> tail -f currently_learning.log`

```text
[backend]      TypeScript · API architecture · validation · auth
[database]     PostgreSQL · indexing · transactions · query optimization
[architecture] modular monolith · clean architecture · system design
[infra]        Docker · CI/CD · background jobs
[ai]           embeddings · semantic search · LLM integrations
[practice]     JavaScript DSA · technical interviews
```

---

## `> cat architecture.md`

One of the areas I'm actively improving is understanding **why systems are designed the way they are**, not just how to make individual features work.

```text
                    ┌───────────────┐
                    │    Client     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   API Layer   │
                    └───────┬───────┘
                            │
                    ┌───────▼───────┐
                    │  Application  │
                    │    Layer      │
                    └───────┬───────┘
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
        ┌──────────┐  ┌──────────┐  ┌──────────┐
        │  Domain  │  │  Queue   │  │   AI     │
        │  Logic   │  │ Workers  │  │ Services │
        └────┬─────┘  └────┬─────┘  └────┬─────┘
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                    ┌───────────────┐
                    │  PostgreSQL   │
                    └───────────────┘
```

The current focus is on **clear boundaries, predictable data flow, testability, and keeping complexity where it actually belongs.**

---

## `> git log --oneline --philosophy`

```text
* readable code > clever code
* explicit boundaries > accidental architecture
* tests > assumptions
* simple abstractions > abstraction for its own sake
* observability > debugging production blindly
* ship → measure → improve
```

---

## `> ./github-stats --render`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AniketSONI264&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AniketSONI264&layout=compact&theme=tokyonight&hide_border=true" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=AniketSONI264&theme=tokyonight&hide_border=true" />

</div>

---

## `> cat certifications.txt`

```text
[x] SQL (Intermediate)                         — HackerRank
[x] Advanced Java                              — Anudip Foundation
[x] JavaScript                                 — Scaler Topics
[x] Software Development Job Simulation        — Datacom · Forage
```

---

## `> ./connect --with-me`

<div align="center">

Currently looking for **Full-Stack / Backend / Software Developer** opportunities.

I'm particularly interested in teams where I can work on real products, improve my backend engineering skills, and contribute to systems that need to be maintained — not just demoed.

<br>

<a href="https://www.linkedin.com/in/ani--ket">
<img src="https://img.shields.io/badge/Let's_talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://medisetu.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<br><br>

```text
$ git status

On branch main
Your branch is up to date.

nothing to commit,
keep building.

> _
```

<br>

<code>01001000 01100101 01101100 01101100 01101111 👾</code>

</div>
