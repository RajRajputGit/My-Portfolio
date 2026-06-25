# 📐 Portfolio Blueprint — `Brajmohan Rajput | AI/ML Engineer`

> **Purpose:** Align the portfolio at `/Users/apple/Desktop/Portfolio/portfolio/` to perfectly mirror the canonical resume `BrajResumeAiml_18062026.pdf`. This blueprint is a **planning document only** — no project code is being modified until you approve.

---

## 1️⃣ Folder Structure Audit

### 🔴 Current Structure (as-is)
```
Portfolio/
├── Resume/                          ← duplicate, unused on site
│   └── Braj_Resume_2.pdf            ← OLD resume (superseded)
└── portfolio/
    ├── index.html                   ← portfolio entry
    ├── README.md                    ← generic readme
    ├── assets/                      ← EMPTY folder (dead weight)
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
        ├── project1.jpg
        ├── project2.jpg
        ├── project3.jpg
        ├── profile.jpg
        └── profile.png              ← duplicate profile image
```

### 🟢 Recommended Structure (target)
```
portfolio/
├── index.html                       ← single-page site
├── README.md                        ← updated to reflect site
├── assets/                          ← future SVGs/icons (kept empty for now)
├── css/
│   └── style.css                    ← refined tokens + section styles
├── js/
│   └── script.js                    ← theme toggle, smooth scroll, form, year
├── images/
│   ├── profile.jpg                  ← keep ONE profile image
│   ├── project-source-analyser.png  ← RAG project thumbnail
│   ├── project-job-analyzer.png     ← ELK/K8s project thumbnail
│   └── project-loan-ml.png          ← ML pipeline thumbnail
└── Resume/
    └── BrajRajput_AI_ML_Engineer.pdf  ← NEW resume (downloaded copy)
```

### 📌 Action Items (Phase 2)
- **Delete** old `Resume/Braj_Resume_2.pdf` from inside `portfolio/`.
- **Copy** `BrajResumeAiml_18062026.pdf` from `~/Desktop/Resume/` into `portfolio/Resume/` and rename to `BrajRajput_AI_ML_Engineer.pdf`.
- **Delete** duplicate `images/profile.png` (keep `.jpg`).
- **Rename** `project1.jpg`, `project2.jpg`, `project3.jpg` to semantic names (only if you regenerate art; otherwise keep filenames).
- Update the `Download Resume` link in HTML to point to the new file.

---

## 2️⃣ Hero & About Section Mapping

### 🎯 Resume's Professional Summary (verbatim)
> *"AI/ML Engineer (B.Tech, 2027) with hands-on experience building production-ready Generative AI applications, cloud-native systems, and end-to-end ML pipelines. Skilled in conversational RAG, LLM-powered FastAPI backends, Kubernetes deployments with ELK Stack observability, and scalable MLOps practices using Docker, AWS, and GitHub Actions."*

### 🅷 Hero Section — Recommended Copy

| Element | Current (❌ outdated) | Recommended (✅ aligned) |
|---|---|---|
| **Page Title** | `Portfolio - Machine Learning & Cloud Engineer` | `Brajmohan Rajput — AI/ML Engineer \| GenAI & MLOps` |
| **Name** | `Brajmohan Rajput` | ✅ Keep |
| **Role** | `Data Scientist & ML Engineer` | `AI/ML Engineer` |
| **Tagline (1-liner above intro)** | *(none)* | `Building production-ready GenAI systems, RAG pipelines, and cloud-native ML.` |
| **Intro paragraph** | Long, mentions Azure AI Foundry, Snowflake, React — **drift from resume** | See below ↓ |

### ✍️ New Hero Intro (resume-aligned, ~3 sentences)
> *"I'm an AI/ML Engineer (B.Tech, 2027) building **production-ready Generative AI applications** powered by **conversational RAG**, **LLM-backed FastAPI services**, and **LangChain**. I deploy cloud-native systems on **Kubernetes with ELK Stack observability** and ship reliable ML through **Docker, AWS, and GitHub Actions** CI/CD. Currently focused on scalable **MLOps** workflows that turn prototypes into live, monitored services."*

### 🅰 About Section — Recommended Copy

**About-me paragraph (3 short paragraphs):**
> *"I'm a B.Tech candidate at S.G.S.I.T.S. Indore (CGPA 7.0/10), specializing in Generative AI, applied ML, and MLOps. My work spans the full lifecycle — from data preprocessing and model training to containerized deployment and real-time log observability.*
>
> *I build **conversational RAG systems** that let users query entire codebases semantically, **GenAI screening tools** running on Kubernetes with full ELK monitoring, and **end-to-end ML pipelines** using Scikit-learn Pipelines and GridSearchCV.*
>
> *I'm actively looking for **Summer 2026 internships and full-time AI/ML Engineer roles** where I can contribute to impactful GenAI and MLOps work."*

**Core Strengths (right column):**
1. ✅ Conversational RAG & LLM Application Development
2. ✅ Cloud-Native & Kubernetes Orchestration
3. ✅ ELK Stack Observability & Centralized Logging
4. ✅ End-to-End ML Pipelines (Scikit-learn, GridSearchCV)
5. ✅ MLOps & CI/CD Automation (Docker, AWS, GitHub Actions)

**About-info cards (small facts):**
- **Availability:** Open to Summer 2026 Internships & Full-time AI/ML Roles
- **Location:** Indore, Madhya Pradesh, India
- **Focus Areas:** Generative AI · MLOps · Cloud-Native ML

---

## 3️⃣ Skills Alignment Matrix

### 🔴 Current Portfolio Skills (gaps & bloat)
- ❌ Mentions `Java` (not on resume) → **REMOVE**
- ❌ Mentions `React`, `Terraform`, `Snowflake` (not on resume) → **REMOVE**
- ⚠️ Mentions `Git/GitHub` under "Web Technologies" — wrong category
- ❌ Soft Skills category — keep brief, but trim
- ⚠️ Missing: **LangChain, ChromaDB, HuggingFace, Groq, GPT-4, MLflow, ELK Stack, PostgreSQL, Linux**

### 🟢 Recommended Skills Taxonomy (mirrors resume exactly)

#### 🧠 Generative AI & LLMs
`GPT-4` · `LLM Applications` · `Retrieval-Augmented Generation (RAG)` · `LangChain` · `Prompt Engineering` · `HuggingFace Embeddings` · `ChromaDB` · `Conversation Memory`

#### 🤖 Machine Learning
`Scikit-learn` · `Feature Engineering` · `Model Training & Evaluation` · `GridSearchCV (Hyperparameter Tuning)` · `Classification` · `Regression`

#### ⚙️ Backend Development
`Python` · `FastAPI` · `REST APIs` · `Streamlit`

#### ☁️ Cloud & DevOps
`AWS (S3, EC2, Lambda, CodePipeline)` · `Azure AI Foundry` · `Docker` · `Kubernetes (Minikube)` · `GitHub Actions` · `CI/CD Pipelines`

#### 📊 Logging & Observability
`ELK Stack (Filebeat, Logstash, Elasticsearch, Kibana)` · `Centralized Log Management` · `Real-Time Monitoring Dashboards` · `MLflow`

#### 🗄️ Data Engineering
`Apache Airflow` · `Apache Spark` · `PostgreSQL` · `SQL` · `ETL/ELT Pipelines`

#### 🛠 Developer Tools
`Git` · `GitHub` · `Linux` · `VS Code`

### 💡 High-impact skills to ADD (resume-aligned, not fluff)
None needed — the resume is the source of truth. We just need to **add the categories that exist on the resume but are missing on the site** (notably **Generative AI & LLMs**, **Logging & Observability**, and **Data Engineering**).

### 🗑 Skills to REMOVE (not on resume)
- `Java`
- `React`
- `Terraform`
- `Snowflake`
- The "Soft Skills" category (replace with 3-4 crisp badges OR drop entirely)

---

## 4️⃣ Projects Synchronization

### 🔴 Current Portfolio Projects (mismatch with resume)
| # | Current Title | Current Tech | Issue |
|---|---|---|---|
| 1 | "2 Stage Loan Approval & Valuation System" | Python, Scikit-learn, Streamlit | ✅ Aligns with **resume Project #3** — needs polish |
| 2 | "LLM Fine-Tuning & CI/CD GenAI Web App" | Azure AI Foundry, React, AWS | ❌ Not on resume — **REMOVE** |
| 3 | "MLOps Jenkins Shared Library CI/CD Project" | Jenkins, Docker, K8s, GCP | ❌ Not on resume — **REMOVE** |

### 🟢 Final Project Lineup (must match resume exactly)

---

#### 🟣 Project 1 — **Source Code Analyser** (Conversation RAG)
| Field | Content |
|---|---|
| **Title** | Source Code Analyser |
| **Subtitle** | Production-Ready Conversational RAG over GitHub Repositories |
| **Date** | Apr 2026 |
| **Tech Stack** | `Python` · `FastAPI` · `Streamlit` · `LangChain` · `ChromaDB` · `HuggingFace Embeddings` · `Groq API` |
| **Description (bullet-led, resume verbatim)** | • Built a production-ready conversational RAG system that indexes entire GitHub repositories into a **ChromaDB** vector store, enabling **semantic code search** and repository-aware Q&A over complex codebases.<br>• Architected a modular **FastAPI** backend with **LangChain**, isolating retrieval, vector storage, session management, and rolling conversation summarization into dedicated, independently testable components.<br>• Reduced prompt token usage in extended sessions by implementing **session-scoped memory with automatic conversation summarization**, preserving long-term context without exceeding LLM context limits. |
| **Live Demo link** | *(provide GitHub repo URL)* |
| **Recommended UI** | Add a "Key Features" pill row: `Semantic Search` · `Session Memory` · `Repo Ingestion` · `LangChain Modular Backend`. Consider a small architecture diagram (Retriever → Vector Store → LLM → UI). |
| **Image alt** | `Source Code Analyser — RAG Architecture Preview` |

---

#### 🔵 Project 2 — **AI Powered Job Analyzer** (ELK + K8s)
| Field | Content |
|---|---|
| **Title** | AI Powered Job Analyzer |
| **Subtitle** | GenAI Resume Screener with ELK Observability on Kubernetes |
| **Date** | Jun 2026 |
| **Tech Stack** | `Python` · `GPT-4 API` · `FastAPI` · `Streamlit` · `Filebeat` · `Logstash` · `Elasticsearch` · `Kibana` · `Docker` · `Kubernetes (Minikube)` |
| **Description** | • Engineered a cloud-native **GenAI** application that leverages **GPT-4** to automatically screen resumes against job descriptions, producing **match percentages, skill gap analysis, and hiring decision summaries**.<br>• Deployed the application as a containerized pod on a **Minikube Kubernetes cluster** inside a VM, demonstrating production-grade container orchestration with horizontal scaling capability.<br>• Implemented a full **ELK Stack observability pipeline** using **Filebeat** as a sidecar agent to ship application logs to **Logstash** for processing, **Elasticsearch** for indexed storage, and **Kibana** for real-time system health dashboards. |
| **Live Demo link** | *(provide GitHub repo URL)* |
| **Recommended UI** | Highlight a "Monitoring" badge row: `ELK Pipeline` · `K8s Pods` · `Kibana Dashboards` · `GPT-4 Match Scoring`. Add a "Architecture" mini-diagram (App Pod ↔ Filebeat → Logstash → ES → Kibana). |
| **Image alt** | `AI Powered Job Analyzer — ELK + Kubernetes Dashboard Preview` |

---

#### 🟢 Project 3 — **Two-Stage Loan Approval & Valuation ML System**
| Field | Content |
|---|---|
| **Title** | Two-Stage Loan Approval & Valuation ML System |
| **Subtitle** | End-to-End Scikit-learn Pipeline with Hyperparameter Tuning |
| **Date** | Nov 2025 |
| **Tech Stack** | `Python` · `Scikit-learn` · `Streamlit Cloud` · `GridSearchCV` |
| **Description** | • Architected a **two-stage ML inference pipeline** that chains a classification model (loan approval) with a regression model (loan amount estimation), enabling a unified, sequential prediction workflow in a single user request.<br>• Engineered end-to-end **Scikit-learn Pipelines** with modular preprocessing and feature engineering stages; applied **GridSearchCV** hyperparameter tuning to optimize model performance across both stages.<br>• Deployed a production-style interactive ML application on **Streamlit Cloud**, demonstrating full-cycle capability from data preprocessing and model training to live inference and user-facing UI. |
| **Live Demo link** | *(provide Streamlit Cloud URL)* |
| **Recommended UI** | Add small badges: `Two-Stage Inference` · `GridSearchCV Optimized` · `Streamlit Cloud Deployed`. |
| **Image alt** | `Loan Approval & Valuation ML — Streamlit App Preview` |

---

### 📌 Project-Section Action Items (Phase 2)
- ❌ **Remove** current "LLM Fine-Tuning & CI/CD GenAI Web App" card.
- ❌ **Remove** current "MLOps Jenkins Shared Library CI/CD Project" card.
- ✅ **Keep** loan project but rewrite title, subtitle, tech stack, description.
- ✅ **Replace** Project 1 with **Source Code Analyser**.
- ✅ **Replace** Project 2 with **AI Powered Job Analyzer**.
- ✅ **Order** by recency (newest first): Source Code Analyser (Apr 2026) → Job Analyzer (Jun 2026) → Loan ML (Nov 2025). *If you want strict chronological desc, swap 1 and 2.*
- ✅ Replace placeholder "Key Achievements" lists with real metrics — currently they say `[X]%` placeholders which look unfinished.

---

## 5️⃣ Section Layout Plan

### 🔴 Current Order (with issues)
```
Hero → About → Education → Skills → Projects → Experience → Certifications → Achievements → Profiles → Contact
```
**Problems:**
- "Experience" is full of `[Placeholder]` text.
- "Certifications" is full of `[Placeholder]` text.
- "Achievements" is full of `[Placeholder]` text.
- "Profiles" has fake placeholder usernames.
- "Education" comes before Skills (kills the narrative momentum).

### 🟢 Recommended Order (resume-aligned, recruiter-friendly)
```
1.  🅷 Hero
        Name, Role, tagline, 3-sentence intro, CTA buttons
        ↓
2.  🅰 About
        Bio + Core Strengths + (Availability · Location · Focus)
        ↓
3.  🛠 Skills
        7 categories, badge grid, hover lift
        ↓
4.  📁 Projects
        3 cards in featured-grid (RAG → ELK/K8s → Loan ML)
        ↓
5.  🎓 Education
        Single SGSITS card (CGPA, expected 2027)
        ↓
6.  📜 Certifications
        CLLMSP — Red Team Leaders (June 2026)
        ↓
7.  💼 Experience
        Either: (a) hide the section until you have content, or (b) convert to a "Currently seeking" call-out
        ↓
8.  🔗 Profiles
        GitHub · LinkedIn · Portfolio links (no fake Stack Overflow / LeetCode unless real)
        ↓
9.  ✉ Contact
        Email · Phone · Location + minimal form (or link to mailto:)
        ↓
Footer
```

### 📌 Section-level Action Items (Phase 2)
- **Hide or repurpose Experience** — no real experience entries exist on resume; suggest a small card: *"Actively seeking AI/ML Engineer internships and full-time opportunities for 2026–2027."*
- **Replace placeholder Certifications** with the single CLLMSP entry from resume.
- **Remove placeholder Achievements** section entirely (resume has no achievements — adding fake ones hurts credibility).
- **Remove fake Stack Overflow / LeetCode cards** from Profiles unless you actually have accounts.
- **Add GitHub profile link** with a real handle (your `RajRajputGit`).
- **Update navbar** to drop `achievements` link, keep the rest.

---

## 6️⃣ Misc / Cleanup Notes

- **`<title>` tag** — currently generic, should match the resume headline.
- **`<meta name="description">`** — re-write for SEO using resume summary keywords (`AI/ML Engineer`, `Generative AI`, `RAG`, `Kubernetes`, `ELK Stack`).
- **Resume download button** — currently points to `Resume/Braj_Resume_2.pdf` (old file). Should point to the new `BrajRajput_AI_ML_Engineer.pdf`.
- **Contact form** — currently has your own name/email as placeholder text inside `input` fields, which is odd UX. Change to generic placeholders.
- **Footer copyright** — looks fine, just verify the year.
- **Footer social icons** — `#` placeholders; replace with real GitHub & LinkedIn URLs.

---

## ✅ Phase 1 Summary — Approval Checklist

Before we touch any code, please confirm the following decisions:

| # | Decision | Default Recommendation |
|---|---|---|
| 1 | Adopt the recommended folder structure | ✅ Yes |
| 2 | Replace 3 project cards with the 3 resume projects in the order above | ✅ Yes |
| 3 | Trim skills to exactly what's on the resume (drop Java/React/Terraform/Snowflake) | ✅ Yes |
| 4 | Hide "Experience" section (or use a "Currently seeking" card) | ✅ Hide / repurpose |
| 5 | Drop "Achievements" section | ✅ Drop |
| 6 | Drop fake Stack Overflow & LeetCode profiles | ✅ Drop |
| 7 | Update resume download link to new PDF | ✅ Yes |
| 8 | Update page `<title>` and meta description | ✅ Yes |

---

## ⏸ PHASE 2 — AWAITING YOUR CONFIRMATION

Once you approve (or suggest edits to) the blueprint above, I'll proceed **one file at a time** to keep token usage low:

1. `index.html` — full content rewrite (sections, copy, links)
2. `css/style.css` — minimal polish only (palette, spacing, badges) **unless you want a deeper redesign**
3. `js/script.js` — keep as-is (works fine), unless behavior needs adjusting
4. New `Resume/BrajRajput_AI_ML_Engineer.pdf` placeholder
5. Folder cleanup (remove duplicate profile image, unused `assets/` if confirmed)

> ✋ **Please review the blueprint above and reply with:**
> - "Approved, proceed to Phase 2" (I'll start with `index.html`), **or**
> - Specific edits you want me to make to the blueprint first.