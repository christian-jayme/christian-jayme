<h1 align="center">Christian Jayme</h1>

<p align="center">
  <b>Software Engineer</b> — Mobile, Frontend &amp; AI Features
  <br>
  <sub>6+ years shipping production apps · 3 Android apps shipped to the Play Store · Cebu, Philippines 🇵🇭</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/christian-jayme-4435601b7"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://about.me/christian-jayme"><img src="https://img.shields.io/badge/Portfolio-1F2328?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:christian.jayme26@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I build the product layer — mobile apps, web front ends, and increasingly the **AI features inside them**.

Started in native Android at **Kyocera**, where I went from engineer to Android Tech Lead and Scrum Master, and shipped three apps to the Play Store, two of which are still live. Now at **Tahche**, working across a five-app recruitment platform and building LLM-powered features that real users touch every day — not demos.

The work I'm proudest of isn't the model call. It's everything around it: what happens when generation fails, how a user edits AI output without losing their draft, and how you ship the same AI experience into two different apps without forking the code.

---

## Featured work

### 🤖 AI Job Post Generator — LLM wizard shipped into two production apps
A multi-step wizard that turns a one-line role description into a complete job post: overview, responsibilities, requirements, benefits, and screening questions. Every field stays editable, drafts survive a refresh, and generation failures degrade to a usable form instead of a dead end.

Packaged as a **versioned library bundle** so the same experience runs identically inside Tahche Client Web and the internal Recruitment Portal — one codebase, two hosts, no duplication.

`Vue 3` `TypeScript` `Claude API` `structured-output prompting` `Pinia`

### 🧩 Tahche recruitment platform — 5 connected apps
Frontend contributor across the suite, with end-to-end ownership of specific modules.

- **Recruitment Portal** — joined an existing codebase and took ownership of the **job approval and review flow**: the full job edit modal, screening-questions module, and approve/reject workflow, including "For Review" state handling, status gating, and the downstream effects on what clients see.
- **Client Web** — shipped the web hiring flow (job creation, drafts, submit-for-review, editing, notifications) while holding feature parity with the React Native mobile app.
- **Client App** — contributed to the React Native app that the rest of the suite was built around.
- **Career Portal** — candidate-facing job browsing and application flows.
- **Payment Portal** — scaffolded the project and early client onboarding and billing flows.

`Vue 3` `TypeScript` `React Native` `Supabase (PostgreSQL, RLS)` `Node.js` `TanStack Query`

### 📱 Shipped to the Play Store — Kyocera
Native Android work with real install bases, plus the release infrastructure behind it: Firebase (Analytics, Crashlytics, In-App Messaging, Push, Auth) and CI/CD with Jenkins + Fastlane.

| App | What it does |
|---|---|
| **ServiceNAVI Plus** <sub>— since retired by Kyocera</sub> | Field-service app that helped technicians diagnose and resolve issues on Kyocera MFP devices, cutting on-site service time. |
| [**KYOCERA Mobile Print**](https://play.google.com/store/apps/details?id=com.kyocera.kyoprint) | Discovers compatible printers on the local network and enables mobile printing from Android. |
| [**KYOCERA MyPanel**](https://play.google.com/store/apps/details?id=com.kyocera.externalpanel) | Remote control surface for print and imaging features on supported Kyocera printers and MFPs. |

`Kotlin` `Java` `Flutter` `Firebase` `Jenkins` `Fastlane`

<sub>Also served as **Product Owner** on a confidential Flutter project — translating stakeholder requirements into a prioritized backlog and leading delivery.</sub>

---

## Stack

**Web** · Vue 3 (Composition API, `<script setup>`), TypeScript, Pinia, TanStack Query, Vite, Tailwind, SCSS<br>
**Mobile** · React Native, Flutter / Dart, native Android (Kotlin, Java), Material Design<br>
**AI** · Anthropic Claude API, OpenAI-compatible APIs, prompt design for structured outputs, AI-first form flows<br>
**Backend & data** · Node.js, Express, Supabase (PostgreSQL, RLS, migrations), PostgREST, REST API design<br>
**Delivery** · Git, GitHub Actions, Jenkins, Fastlane, Jira, Scrum / Kanban, release management

<p>
  <img src="https://skillicons.dev/icons?i=vue,ts,react,kotlin,flutter,nodejs,supabase,postgres,firebase,tailwind,git,figma&theme=dark" alt="Stack icons">
</p>

---

## Here on GitHub

My production work lives in private company repos. What's public here is smaller, but it's where you can actually read how I structure an app.

| Repo | What it is |
|---|---|
| [**movie-list-application**](https://github.com/christian-jayme/movie-list-application) | Offline-first Android movie browser (iTunes API). MVVM + repository pattern, Room as the single source of truth behind a `networkBoundResource` cache, Hilt DI, Retrofit/OkHttp, Navigation component, MotionLayout carousel. Unit tested with JUnit 5, Robolectric and MockWebServer. |
| [**weather-application**](https://github.com/christian-jayme/weather-application) | Jetpack Compose + Material 3 weather client (Open-Meteo). Clean architecture — domain / data / presentation split, repository interface behind an impl, `LocationTracker` abstraction over Play Services, DTO→domain mappers, Hilt DI. |
| [**react-native-coachmark**](https://github.com/christian-jayme/react-native-coachmark) | Contributor to a published React Native onboarding-tooltip library (`@edwardloopez/react-native-coachmark`) — added the `AnimatedMask` exports and hooks API. |
| [**brainwave**](https://github.com/christian-jayme/brainwave) | React + Vite + Tailwind landing page. Built following a JS Mastery tutorial — kept public as a frontend layout reference. |

---

## Working together

I take on **mobile app builds, Vue 3 / React Native feature work, AI feature integration**, and rescue projects — inherited codebase, no docs, needs to ship.

Email **christian.jayme26@gmail.com** with what you're building, the platforms you need, and your rough timeline. You'll get scope, an approach, and an honest read on whether I'm the right fit.

<p align="center"><sub>Cebu, Philippines (UTC+8) · Regularly overlapping with US teams</sub></p>
