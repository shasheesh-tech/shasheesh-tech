![Shasheesh — CSE Student at Vardhaman College of Engineering](assets/hero.svg)

# SHASHEESH

**CSE student at Vardhaman College of Engineering, Hyderabad.**  
*Turning terminal noise, raw caffeine, and neural weights into living systems.*  
*Chasing the sweet spot where low-level speed meets autonomous intelligence.*

[Featured Projects](#-featured-projects) · [Mini Projects](#-mini-projects) · [Engineering Toolkit](#-engineering-toolkit) · [Hackathons & Milestones](#-hackathons--milestones) · [GitHub Activity](#-github-activity) · [How I Build](#-how-i-build)

---

## ⚡ Featured Projects

### 🛡️ TrustGuardian AI — Enterprise Trust Intelligence Platform

> **Collaborative Project** · Repository: [Riddhii-2007/TrustGuardian-AI](https://github.com/Riddhii-2007/TrustGuardian-AI)  
> **Team Achievement:** 🥈 **Second Place** at IARE Hackathon (₹50,000 team prize among 367 competing teams)

An AI-assisted email threat intelligence system designed to combat Business Email Compromise (BEC), CEO fraud, sender spoofing, and social engineering. Rather than simply tagging messages as malicious, it models historical relationships and multi-source signals to evaluate whether an organization should trust a business request.

* **What it does:** Combines deterministic verification (SPF/DKIM/DMARC, VirusTotal API, PII redaction) with an explainable AI reasoning layer, multi-LLM routing with automatic failover, and Neo4j relationship graphs.
* **My confirmed contributions:** Component integration, frontend-to-backend connectivity, security scoring implementation, API and data-persistence debugging, end-to-end testing, and hackathon preparation.
* **Stack:** React 19 · TypeScript · Vite · FastAPI · Python · Supabase (PostgreSQL) · Neo4j Aura · Gemini 2.5 Flash · Groq (Llama 3) · Gmail API · Google OAuth · VirusTotal · Three.js · Cytoscape.js
* **Status:** Actively developed — core detection pipeline and Trust Engine implemented; dashboard analytics, Decision Sandbox, and Trust Replay in active iteration.

---

### 🎯 FOCUS — AI Career Learning Operating System

> **Collaborative Project** · Repository: [rendlavishnutej-hub/hackathonZ-team_FOCUS](https://github.com/rendlavishnutej-hub/hackathonZ-team_FOCUS)  
> **Event:** Built for Hack2Hire 24-Hour Hackathon at Malla Reddy University  
> **Reported Demo:** [focus-five-eta.vercel.app](https://focus-five-eta.vercel.app/) *(author-supplied deployment; not independently benchmarked)*

A multi-agent learning and career platform built to replace fragmented study tools with a continuous feedback loop: personalized curriculum paths, document-grounded quizzes, and an interactive mock interview simulator.

* **What it does:** Orchestrates on-demand AI agents (Research, Teacher, Roadmap, Quiz, and Interview) to generate dynamic learning roadmaps, evaluate submitted documents via RAG, and simulate real interview dynamics.
* **My confirmed contributions:** Frontend architecture and AI integration, including multi-agent orchestration workflows and building the AI mock-interview experience with voice-interactive speech input and automated audio/text feedback.
* **Stack:** Next.js 15 · React 19 · TypeScript · Tailwind CSS 4 · Supabase · PostgreSQL · Gemini / OpenAI APIs · RAG Vector Search
* **Status:** Functional hackathon release.

---

### 📈 MarketAutopsy AI — Market Intelligence & Risk Analysis Platform

> **Collaborative Project** · Repository: [SaiArnav/Market-Autopsy](https://github.com/SaiArnav/Market-Autopsy)  
> **Event:** DevOps Hackathon

An AI-driven intelligence platform designed to conduct on-demand deep analysis of corporate public signals across news, hiring patterns, patents, customer sentiment, leadership shifts, and funding rounds to deliver explainable risk scores and strategic reports.

* **What it does:** Runs multi-source data ingestion through an agentic tool-use pipeline, combines real-time evidence evaluation with OpenAI models, and generates validated JSON risk profiles across multiple market dimensions.
* **My confirmed contributions:** Integration of responsive frontend UI elements, creating the comprehensive platform walkthrough demo video, and delivering the technical voiceover presentation explaining the platform's features and architecture.
* **Stack:** Next.js 14 · TypeScript · Tailwind CSS · Prisma · PostgreSQL · Framer Motion · Three.js · Recharts · OpenAI APIs
* **Status:** Functional hackathon release.

---

### 🎮 AIMGOD Trainer — 3D Browser Aim Training Lab

> **Personal Project** · Repository: [shasheesh-tech/AIMGOD_trainer](https://github.com/shasheesh-tech/AIMGOD_trainer)  
> **Authorship:** Sole creator and developer

A browser-native 3D aim-training application created to practice spatial awareness, target tracking, and reaction-time measurement without installing native client binaries.

* **What it does:** Features interactive 3D training arenas with 6 procedural target geometries (spheres, boxes, cylinders, toruses, diamonds, triangles), 7 cyber and tactical themes, custom target millimeter scaling (30 mm – 400 mm), adjustable timers (15s – 180s), and local session analytics tracking hits, misses, accuracy percentages, and average reaction latency.
* **My confirmed contributions:** Sole author — designed and implemented the full 3D canvas, state machine, procedural geometry rendering, HUD telemetry, and session persistence.
* **Stack:** React 18 · TypeScript · Vite · Three.js · React Three Fiber · React Three Drei · Tailwind CSS · Lucide React
* **Status:** Foundation completed with working 3D arena, session storage, and results dashboard.

---

### 📦 StockSense — AI-Assisted Inventory Execution & Ledger

> **Collaborative Project** · Repository: [Riddhii-2007/StockSense](https://github.com/Riddhii-2007/StockSense)  
> **Authorship:** Primary frontend contributor (7 commits)

An inventory management system engineered around deterministic ledger safety and verified execution rules, preventing discrepancies between UI previews and committed transactions.

* **What it does:** Enforces a strict preview-then-post execution pipeline where commits verify against server-side ledger constraints, provides role-based access for Administrators, Managers, and Staff, and parses natural-language stock commands as untrusted inputs through guarded SQL validation.
* **My confirmed contributions:** Primary frontend developer — built the complete user interface, authentication and login security flows, and client API communication layers.
* **Stack:** React 18 · Vite · Tailwind CSS v3 · Node.js · Express.js · SQLite (`node:sqlite`) · Anthropic Claude API (optional)
* **Status:** Complete local system backed by 59 automated end-to-end verification checks.

---

### 🚇 Metro Seat Availability — Hardware & IoT Prototype

> **Personal/Team Hardware Prototype** *(no public software repository)*

A miniature physical proof-of-concept for real-time transit seat occupancy monitoring.

* **What it does:** Incorporates 4 miniature seats wired to mechanical contact switches and dual-state red/green LED indicators. An ESP32-CAM module provides overhead visual cross-validation while protecting passenger privacy by transmitting only discrete occupancy status instead of identifiable video streams.
* **Status:** Functional physical prototype.

---

## 🛠️ Mini Projects & Coursework

Focused academic and course-end applications demonstrating desktop software engineering, object-oriented design, and systems programming:

### 🏥 [Hospital Patient Record Management System](https://github.com/shasheesh-tech/Hospital-patient-Record-system)
> **Academic Mini Project** · Summer Project 2025–26 at Vardhaman College of Engineering

A comprehensive terminal-based healthcare operations system built in modern C++. Simulates real-world hospital workflows with interconnected patient records, specialist doctor allocations, appointment queues, itemized billing with GST and senior citizen discounts, and an automated symptom triage recommendation helper.
* **Role:** **Project Mentor** for the student development team.
* **Stack:** C++ · OOP (Encapsulation, Inheritance, Polymorphism, Abstraction) · File Handling Persistence · STL Containers (`std::vector`)

---

### 🔍 [FINDIT — Campus Lost & Found System](https://github.com/shasheesh-tech/FINDIT)
> **Academic Mini Project** · Java Semester Course-End Project at Vardhaman College of Engineering

A standalone Java desktop application built to streamline the lost-and-found process within a university campus, demonstrating comprehensive implementation of Java Swing and AWT GUI components taught throughout the semester.
* **What it does:** Provides an interactive multi-screen desktop dashboard where campus members can report lost or found belongings, browse active item cards, filter and search listings, view detailed item attributes, and coordinate claiming and return workflows with structured data repositories.
* **Authorship:** Personal course-end implementation.
* **Stack:** Java · Java Swing / AWT (Frames, Cards, Layout Managers, Custom Themes) · Object-Oriented Architecture · Repository & Data Models

---

### 📚 Algorithmic Foundations & Coursework Drills

* **[DSL Programs](https://github.com/shasheesh-tech/DSL-programs)** — Coursework implementations of classical and advanced data structures in C++: AVL trees, expression parse trees, open and closed hash tables, linked skip lists, dynamic queues, stacks, and polish notation evaluators.  
  *Stack:* C++ · Algorithmic Data Structures
* **[C++ Practice](https://github.com/shasheesh-tech/cpp)** — Foundational drills in pointer manipulation, recursion, memory layout, and modular C++ algorithms.  
  *Stack:* C++

---

## 🧰 Engineering Toolkit

A categorized overview of technologies I actively build with or have practiced across academic, hackathon, and personal projects.

### Core & Active Technologies
Technologies I frequently use in current builds and architectures:

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Backend & APIs** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Databases & Graph** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **AI & Integrations** | ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square&logo=virustotal&logoColor=white) |
| **Workflow & VCS** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

### Practiced & Explored Technologies
Foundational tools and languages explored in coursework or domain-specific experiments:

* **Languages & Runtimes:** C · Java (Core, JDBC, Swing/AWT) · Node.js  
* **Markup & Styling:** HTML5 · CSS3  
* **Databases:** MySQL  
* **APIs & Protocols:** Gmail API · Google OAuth 2.0 · RESTful Architecture  

> *Note: This toolkit represents technologies I actively apply or have practiced; it does not claim expert-level mastery in every item.*

---

## 🏆 Hackathons & Milestones

* **🥈 Second Place — IARE Hackathon**  
  *Project:* TrustGuardian AI  
  *Recognition:* Awarded 2nd place and a ₹50,000 team prize among 367 participating teams for an explainable email threat intelligence platform.
* **🚀 Hack2Hire 24-Hour Hackathon — Malla Reddy University**  
  *Project:* FOCUS  
  *Recognition:* Developed and shipped a full multi-agent career learning system and voice-interactive mock interview simulator within 24 hours.
* **⚡ DevOps Hackathon**  
  *Project:* MarketAutopsy AI  
  *Recognition:* Contributed frontend UI element integration and produced the comprehensive platform walkthrough demo and technical voiceover explanation.
* **🎓 Summer Project 2025–26 — Vardhaman College of Engineering**  
  *Project:* Hospital Patient Record Management System  
  *Recognition:* Served as project mentor for a 5-member student engineering team delivering an OOP-driven healthcare workflow system in C++.
* **🎓 Java Semester Course-End Project — Vardhaman College of Engineering**  
  *Project:* FINDIT (Campus Lost & Found System)  
  *Recognition:* Engineered a campus lost-and-found desktop application in Java Swing/AWT with custom themes, filtering, and repository persistence.

---

## 📡 GitHub Activity

[![GitHub Contribution Graph for shasheesh-tech](https://ghchart.rshah.org/00f5d4/shasheesh-tech)](https://github.com/shasheesh-tech)

[**Explore all public repositories on GitHub →**](https://github.com/shasheesh-tech?tab=repositories)

---

## 🌌 How I Build

1. **Deconstruct the workflow:** Break down complex problems into verifiable data models, clear API boundaries, and isolated modules.
2. **Build with deterministic guarantees:** Ensure databases, authentication, and state rules protect the system before adding automated AI layers.
3. **Verify by shipping:** Test end-to-end user journeys under realistic constraints (hackathons, edge cases, integration tests) to uncover what actually breaks.
4. **Iterate for clarity:** Prefer transparent architecture, clean documentation, and explainable logic over black-box complexity.

---

<div align="center">
  <sub>Engineering ideas into working systems · <a href="https://github.com/shasheesh-tech">github.com/shasheesh-tech</a></sub>
</div>
