# LegalEase LK — AI-Powered Civil Law Assistance Platform for Sri Lankan Citizens

**Project ID:** 25-26J-553
**Student:** Vimansa D. A. S — IT21346668
**Degree:** BSc (Hons) in Information Technology Specializing in Information Technology
**Institution:** Sri Lanka Institute of Information Technology (SLIIT)
**Faculty:** Faculty of Computing
**Supervisor:** Ms. Uthpala Samarakoon — Senior Lecturer, Faculty of Computing, SLIIT
**External Supervisor:** Samadhi Bandara — Attorney-at-Law of the Supreme Court
**Year:** 2025 / 2026

---

## Description

LegalEase LK is an AI-powered legal assistance platform designed to make civil law information accessible to ordinary Sri Lankan citizens. Most existing legal platforms such as LankaLAW and LawMate are built for lawyers and legal professionals, leaving the general public without simple, understandable legal guidance.

This platform addresses that gap by providing a bilingual (Sinhala and English) AI chatbot powered by a custom fine-tuned Large Language Model (LLaMA 3 8B), trained on Sri Lankan civil law sources. Users can ask legal questions in plain language and receive clear, citation-based explanations. The system also includes a smart lawyer recommendation feature that connects citizens with certified legal professionals based on their legal issue category and geographic district.

The platform covers three core civil law domains:

- Property Law
- Vehicles & Highways
- Marriage & Divorce

---

## Live Site

https://it21346668.github.io/legalease-research-website/

---

## Technology Stack

| Layer | Technologies |
|---|---|
| AI / ML | LLaMA 3 8B, Unsloth fine-tuning, GGUF, RAG |
| Frontend | React.js, HTML, CSS, JavaScript |
| Backend | Node.js, Express.js, REST API |
| Database | MongoDB Atlas, Supabase PostgreSQL |
| Deployment | GitHub Pages (website), Cloud (system) |

---

## System Diagrams

### Overall System Diagram

The overall architecture of LegalEase LK consists of five interconnected components: Users & Data Input, AI Legal Q&A Processing, System Services, AI Legal Chat Interface, and the Lawyer & User Management System.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/bc986a3a-db9c-4fbc-a018-4da7fd14fdc3" />


---

### Use Case Diagram

The use case diagram illustrates the interactions between three actors — Citizen, Lawyer, and Admin — and the 16 use cases supported by the platform.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/54d5e51f-0a0c-464f-95db-cd810ad76db3" />


---

### Sequence Diagram — Legal Q&A Flow

This diagram shows the step-by-step flow of a citizen's legal question through the system: from the web interface through the server, AI model, and database, returning a bilingual answer.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/a5ff9f58-32cf-417a-851d-5d7437bcb707" />

---

### Sequence Diagram — Lawyer Recommendation Flow

This diagram shows how the system recommends suitable lawyers after processing a legal query, using the recommendation engine to filter and rank profiles from MongoDB by specialisation and experience.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/3217a330-cf2f-442b-b982-7221f230300e" />

---

### SDLC Agile Methodology

The project follows the Agile Software Development Life Cycle (SDLC) using the Scrum framework. Development is organised into iterative sprints covering six phases: Requirements, Design, Development, Testing, Deployment, and Review & Retrospective.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/ba9e092d-9a3d-482a-84f5-53f6787a4d0e" />

---

### Work Breakdown Structure

The Work Breakdown Structure organises the full project scope into six phases — Requirements & Analysis, AI & Data, Frontend, Backend, Testing & QA, and Final Submission — each with three levels of sub-tasks.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/bbfc41d8-9f86-4a97-8ad4-883bb82f50a2" />

---

### Gantt Chart

The Gantt Chart maps all project tasks and milestones across the full project timeline from December 2024 to June 2026, covering six submission phases with four key milestones: PP1, PP2, Final Submission, and Publication.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/05dc3acc-c577-4e91-aa6d-91d7e6874cb9" />

---

## Repository Structure

```
├── index.html       # Project website (all sections)
└── README.md        # Project overview
└── assets/
    ├── images/
    │   └── ladyJusticeLogo.png        ← Brand logo (Lady Justice)
    ├── docs/
    │   ├── project-charter.pdf        ← Place Project Charter PDF here
    │   ├── project-proposal.pdf       ← Place Project Proposal Report PDF here
    │   └── checklist-documents.pdf    ← Place Check List Documents PDF here
    └── slides/
        ├── pp01-proposal.pdf          ← Place PP-01 Proposal slides here
        ├── pp02-progress1.pdf         ← Place PP-02 Progress I slides here
        └── pp03-progress2.pdf         ← Place PP-03 Progress II slides here
```

---

## Project Website

This repository hosts the official research project website for **25-26J-553**, built as a single-page HTML site with all project information including the domain, milestones, documents, presentations, team details, and contact information.

---

*Sri Lanka Institute of Information Technology (SLIIT) — Faculty of Computing — 2025/2026*
