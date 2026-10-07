<p align="center">
  <img src="assets/hero.svg" alt="Johnson Oduri — Software Engineer, Full-Stack, Backend, Applied AI" width="100%">
</p>

<p align="center">
Full-stack and backend engineer building production systems — real-time marketplaces, role-based platforms, and AI-native applications powered by RAG and LLM pipelines.
</p>

<p align="center">
  <a href="https://github.com/JohnsonOduri"><img src="https://img.shields.io/badge/GitHub-JohnsonOduri-0d1117?style=flat-square&logo=github&logoColor=38bdf8&labelColor=0d1117" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/JohnsonOduri/"><img src="https://img.shields.io/badge/LinkedIn-Johnson%20Oduri-0d1117?style=flat-square&logo=linkedin&logoColor=38bdf8&labelColor=0d1117" alt="LinkedIn"></a>
  <a href="mailto:oduri.johnson@gmail.com"><img src="https://img.shields.io/badge/Email-oduri.johnson%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=38bdf8&labelColor=0d1117" alt="Email"></a>
</p>

<br>

## About

Computer Science undergraduate at IIIT Kottayam who ships complete systems end to end — frontend, backend, database and deployment. Most of my work has gone into production platforms used by real customers: a hyperlocal commerce app with live order tracking, a client-facing laundry booking service processing real payments, and an AI campus assistant built on a retrieval-first RAG architecture. Comfortable moving between React/React Native interfaces, Node/Flask/FastAPI services, SQL and NoSQL data layers, and Gemini-powered AI workflows.

<br>

## Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

**Full-Stack Systems**
End-to-end products — responsive interfaces wired to REST APIs, authentication and databases, shipped to real users rather than left as demos.

</td>
<td width="50%" valign="top">

**Backend Engineering**
API design, role-based access control, transaction/payment validation and workflow automation across Node.js, Flask and FastAPI.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Real-Time & Data Systems**
Firestore/Supabase-backed platforms with live order tracking, security rules, and multi-role data flows that update instantly across clients.

</td>
<td width="50%" valign="top">

**Applied AI**
Retrieval-grounded LLM features — RAG pipelines over pgvector, Gemini API integrations, and scikit-learn inference services.

</td>
</tr>
</table>

<br>

## Tech Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=cpp,python,ts,js" alt="C++, Python, TypeScript, JavaScript" height="42">
<br><sub>C++ · Python · TypeScript · JavaScript · SQL</sub>

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,reactnative" alt="React, Next.js, Tailwind CSS, React Native" height="42">

**Backend**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,flask,fastapi" alt="Node.js, Express, Flask, FastAPI" height="42">

**Databases & Cloud**
<br>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,firebase,supabase" alt="PostgreSQL, MySQL, MongoDB, Firebase, Supabase" height="42">

**Tools & DevOps**
<br>
<img src="https://skillicons.dev/icons?i=git,github,docker,linux,vercel,postman" alt="Git, GitHub, Docker, Linux, Vercel, Postman" height="42">

**Applied AI**
<br>
<sub>Gemini API · Retrieval-Augmented Generation · Vector Search (pgvector) · LLM Workflows · Scikit-learn</sub>

<br>

## Featured Projects

### ORION — AI Campus Assistant
RAG-grounded campus assistant for IIIT Kottayam — answers are retrieved from Postgres and vector search first, then phrased by Gemini, never invented from model memory.

<img src="https://skillicons.dev/icons?i=react,fastapi,postgres,supabase" alt="React, FastAPI, PostgreSQL, Supabase" height="32">

- Retrieval-first architecture: SQL + pgvector search runs before any LLM call, so Gemini explains grounded data instead of hallucinating
- FastAPI backend with Google OAuth, httpOnly session cookies, and role-based access for students, faculty, CRs and admins
- OCR ingestion pipeline (Tesseract) that turns PDFs, timetables and notices into searchable Gemini embeddings

[Repository](https://github.com/JohnsonOduri/orion-campus-nest) · [Live](https://orion-iiitk.vercel.app)
<br>
<img src="https://img.shields.io/github/last-commit/JohnsonOduri/orion-campus-nest?style=flat-square&color=8b5cf6&labelColor=0d1117" alt="Last commit">

---

### NearFind — Hyperlocal Commerce Platform
A four-role marketplace — customer, retailer, delivery partner, admin — with live order tracking over Firestore.

<img src="https://skillicons.dev/icons?i=reactnative,ts,firebase" alt="React Native, TypeScript, Firebase" height="32">

- Firestore `onSnapshot` listeners drive every screen in real time, from inventory toggles to delivery status, with no manual refresh
- Role-based Firestore security rules enforce order-state transitions (placed → accepted → packed → picked up → delivered) server-side
- Multi-store cart splits a single order across retailers and resolves delivery eligibility only once every store is ready

[Repository](https://github.com/JohnsonOduri/NearFind) · [Demo Walkthrough](https://youtu.be/glEheV8mdWo)
<br>
<img src="https://img.shields.io/github/stars/JohnsonOduri/NearFind?style=flat-square&color=38bdf8&labelColor=0d1117&logo=github&logoColor=38bdf8" alt="Stars">
<img src="https://img.shields.io/github/last-commit/JohnsonOduri/NearFind?style=flat-square&color=8b5cf6&labelColor=0d1117" alt="Last commit">

---

### VK Wash — Service Booking Platform
Production booking and billing platform running real customer orders for a laundry service business.

<img src="https://skillicons.dev/icons?i=react,ts,firebase" alt="React, TypeScript, Firebase" height="32">

- PhonePe payment integration with callback handling and order-status reconciliation
- Firebase-backed order, billing and service-history workflows used in daily operations
- Cloudinary-based invoice generation shared directly with customers over WhatsApp

[Repository](https://github.com/JohnsonOduri/vk-wash-web) · [Live](https://vkwash.in)
<br>
<img src="https://img.shields.io/github/stars/JohnsonOduri/vk-wash-web?style=flat-square&color=38bdf8&labelColor=0d1117&logo=github&logoColor=38bdf8" alt="Stars">
<img src="https://img.shields.io/github/last-commit/JohnsonOduri/vk-wash-web?style=flat-square&color=8b5cf6&labelColor=0d1117" alt="Last commit">

---

### SecondMind — AI Knowledge Platform
AI second brain that enriches saved notes with Gemini and answers questions only from what's actually been stored.

<img src="https://skillicons.dev/icons?i=nextjs,ts,supabase" alt="Next.js, TypeScript, Supabase" height="32">

- Ingestion pipeline auto-generates summaries and tags on every note via Gemini, backed by a normalized Postgres schema
- Grounded query endpoint retrieves candidate notes by tag overlap and full-text search before asking Gemini to answer
- Public query API route for programmatic, infrastructure-style access to the knowledge base

[Repository](https://github.com/JohnsonOduri/SecondMind) · [Live](https://secondmind-altibbe.vercel.app)
<br>
<img src="https://img.shields.io/github/stars/JohnsonOduri/SecondMind?style=flat-square&color=38bdf8&labelColor=0d1117&logo=github&logoColor=38bdf8" alt="Stars">
<img src="https://img.shields.io/github/last-commit/JohnsonOduri/SecondMind?style=flat-square&color=8b5cf6&labelColor=0d1117" alt="Last commit">

---

### SalaryPilot — AI Salary & Career Platform
ML and AI platform that predicts salary ranges, scores resumes, and plans career switches.

<img src="https://skillicons.dev/icons?i=react,flask,python" alt="React, Flask, Python" height="32">

- Trained scikit-learn regression model served through a Flask inference API
- Resume parsing (PyMuPDF/mammoth) feeding a skill-gap analysis and AI-generated resume score via Gemini
- Career-switch planner mapping current role and skills to salary deltas and required skills

[Repository](https://github.com/JohnsonOduri/salary-pilot-web) · [Live](https://salary-pilot-web.vercel.app)
<br>
<img src="https://img.shields.io/github/last-commit/JohnsonOduri/salary-pilot-web?style=flat-square&color=8b5cf6&labelColor=0d1117" alt="Last commit">

<br>

## System Architecture

<p align="center">
  <img src="assets/architecture.svg" alt="Representative architecture: client layer, API and backend, authentication, data layer, applied AI, deployment" width="100%">
</p>

<br>

## Experience

**Freelance Software Developer** — VK Wash · Smart Tech Solutions · Bhoomi
<br><sub>2024 – Present</sub>
<br>Shipped production web and mobile applications for business clients — backend APIs, authentication, database design and PhonePe payment integration.

**Software Project Contributor** — IBM SkillsBuild, Edunet Foundation
<br><sub>Jun 2025 – Jul 2025</sub>
<br>Contributed to SalaryPilot — ML feature development, debugging, and AI/LLM integration as part of an industry-aligned software project.

**Technical Volunteer** — Google Developer Student Club
<br><sub>Jan 2025 – Present</sub>
<br>Cross-functional technical support for community-run events and initiatives.

<br>

## Achievements

**TechSprint Winner — Google Developer Student Club**
<br>Won for pitching the campus platform that became ORION — unifying events, academics and AI-assisted information access for IIIT Kottayam.

<br>

## GitHub Activity

<table>
<tr>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api?username=JohnsonOduri&show_icons=true&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=c9d1d9&icon_color=8b5cf6&count_private=false" alt="Johnson Oduri's GitHub stats" width="100%">
</td>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JohnsonOduri&layout=compact&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=c9d1d9&langs_count=8" alt="Johnson Oduri's most used languages" width="100%">
</td>
</tr>
</table>

<br>

## Education

**Indian Institute of Information Technology Kottayam**
<br>B.Tech, Computer Science and Engineering · CGPA 8.32/10 · Aug 2024 – Present

<br>

## Contact

<p align="center">
Open to software engineering roles and ambitious collaborations.
</p>

<p align="center">
  <a href="https://github.com/JohnsonOduri"><img src="https://img.shields.io/badge/GitHub-JohnsonOduri-0d1117?style=flat-square&logo=github&logoColor=38bdf8&labelColor=0d1117" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/JohnsonOduri/"><img src="https://img.shields.io/badge/LinkedIn-Johnson%20Oduri-0d1117?style=flat-square&logo=linkedin&logoColor=38bdf8&labelColor=0d1117" alt="LinkedIn"></a>
  <a href="mailto:oduri.johnson@gmail.com"><img src="https://img.shields.io/badge/Email-oduri.johnson%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=38bdf8&labelColor=0d1117" alt="Email"></a>
</p>
