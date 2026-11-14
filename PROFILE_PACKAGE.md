# Profile Package — Prachi Zala

This document compiles the complete profile package across the 4 production repositories:
1. `smartcampus-ai`
2. `studybuddy-rag`
3. `mindtrack`
4. `bizdesk`

---

## 1. GitHub Profile README

```markdown
<div align="center">

  <a href="https://github.com/prachizala">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1200&color=3B47D9&center=true&vCenter=true&width=720&lines=Hi+there!+👋+I'm+Prachi+Zala;Python+Developer+%7C+AI+%26+Backend+Engineer;Building+Practical%2C+Data-Driven+Software;Open+to+Internships+%26+Software+Roles+🚀" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>📍 Ahmedabad, Gujarat, India</strong> • <strong>🎓 BCA Student (Focus: Python, AI & Backend Systems)</strong> • <strong>⚡ Hackathon Enthusiast</strong>
  </p>

  <p align="center">
    <a href="https://github.com/prachizala"><img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>&nbsp;
    <a href="https://www.linkedin.com/in/prachi-zala-74a08b334/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:prachizala2003@gmail.com"><img src="https://img.shields.io/badge/Gmail-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://prachizala.github.io/prachi-portfolio/" target="_blank"><img src="https://img.shields.io/badge/Live_Portfolio-Website-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  </p>

</div>

---

### 👩‍💻 About Me

I am a Bachelor of Computer Applications (BCA) student from Ahmedabad, Gujarat, focused on **Python backend systems, applied AI, and data analytics**. I specialize in building practical, end-to-end applications with clean architectures, verifiable logic, and strong guardrails—from computer vision biometrics and grounded retrieval systems to encrypted personal tracking and interval scheduling engines.

- 🐍 **Primary Focus:** Python (FastAPI), REST APIs, Machine Learning pipelines, and secure data handling.
- 💡 **Philosophy:** Writing clean, testable, beginner-readable code that solves real problems with verifiable math and zero fluff.
- 🎯 **Current Focus:** Shipping robust full-stack applications with automated testing, CI/CD, and production readiness.

---

### 🛠️ Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, SQL (SQLite, PostgreSQL), JavaScript, HTML5/CSS3, Java |
| **Backend & APIs** | FastAPI, Pydantic v2, RESTful API Design, Starlette, Uvicorn |
| **AI, ML & NLP** | OpenCV, Scikit-Learn, Pandas, NumPy, Vector Search / Cosine Similarity, PyMuPDF |
| **Security & Cryptography** | Fernet (AES-256-CBC + HMAC), SHA-256 Key Derivation, Input Sanitization |
| **Testing & Tools** | Pytest, TestClient, Git & GitHub Actions (CI/CD), Postman |

---

### 🌟 Featured Projects

#### 1. [SmartCampus AI — Campus Biometrics & Student Risk Early Warning](https://github.com/prachizala/smartcampus-ai)
> **Stack:** `FastAPI` • `OpenCV` • `Scikit-Learn` • `SQLite` • `HTML5/CSS3`  
> **Key Result:** Integrates 128-d spatial facial feature matching ($D_{cos} \ge 0.70$) with a multi-factor academic risk scoring model (attendance 45%, midterm 25%, assignments 15%, backlogs 15%) to identify at-risk students before finals, complete with live CSV reporting.

#### 2. [StudyBuddy RAG — Grounded Document QA & Study Suite](https://github.com/prachizala/studybuddy-rag)
> **Stack:** `FastAPI` • `PyMuPDF` • `Cosine Similarity Engine` • `SQLite` • `HTML5/CSS3`  
> **Key Result:** Extracts PDF content via binary stream indexing with 300-word sliding windows, enforces a 100% strict refusal guardrail for ungrounded queries, and generates 5-question multiple choice quizzes and structured summaries.

#### 3. [MindTrack — Encrypted Mental Health & Journaling Companion](https://github.com/prachizala/mindtrack)
> **Stack:** `FastAPI` • `Cryptography (AES-256 Fernet)` • `Regex Sentinel` • `SQLite` • `HTML5/CSS3`  
> **Key Result:** Guarantees zero plain-text storage of sensitive journal entries via AES-256-CBC field-level encryption with SHA-256 fallback, combined with an automated regex crisis sentinel connecting directly to 24/7 national helplines (Tele-MANAS, Vandrevala).

#### 4. [BizDesk — Appointment Scheduling & Vector PDF Invoicing ERP](https://github.com/prachizala/bizdesk)
> **Stack:** `FastAPI` • `Pydantic v2` • `PyMuPDF` • `SQLite` • `HTML5/CSS3`  
> **Key Result:** Eliminates double-booking through deterministic non-overlap interval math `(start_a < end_b) & (end_a > start_b)`, paired with server-side vector PDF invoice rendering and real-time revenue analytics.

---

### 📬 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/prachi-zala-74a08b334](https://www.linkedin.com/in/prachi-zala-74a08b334/)
- 🌐 **Portfolio:** [prachizala.github.io/prachi-portfolio](https://prachizala.github.io/prachi-portfolio/)
- 📧 **Email:** [prachizala2003@gmail.com](mailto:prachizala2003@gmail.com)
- 📍 **Location:** Ahmedabad, Gujarat, India
```

---

## 2. Repo Descriptions, Topics & Pinned List

### A. Descriptions and Topics
- **`smartcampus-ai`**
  - *Description:* Campus operations platform featuring OpenCV facial recognition attendance, weighted multi-factor academic risk prediction (attendance, midterms, backlogs), and live CSV exports. Built with FastAPI and SQLite.
  - *Topics:* `fastapi`, `python`, `opencv`, `facial-recognition`, `machine-learning`, `academic-warning-system`, `sqlite`, `rest-api`
- **`studybuddy-rag`**
  - *Description:* Grounded document QA and study platform with PyMuPDF binary indexing, 300-word sliding window chunking, cosine similarity retrieval, strict zero-hallucination refusal guardrails, and automated MCQ generation.
  - *Topics:* `rag`, `retrieval-augmented-generation`, `fastapi`, `python`, `pymupdf`, `vector-search`, `nlp`, `quiz-generator`
- **`mindtrack`**
  - *Description:* Privacy-first mental health companion with AES-256 field-level encryption, deterministic regex crisis sentinel with immediate helpline escalation (Tele-MANAS), sentiment tracking, and weekly AI reflections.
  - *Topics:* `fastapi`, `python`, `cryptography`, `aes-256`, `fernet`, `mental-health`, `crisis-prevention`, `data-privacy`
- **`bizdesk`**
  - *Description:* Lightweight business operations engine featuring double-booking collision prevention via non-overlap interval math, server-side vector PDF invoice generation with PyMuPDF, customer CRM, and KPI dashboard.
  - *Topics:* `fastapi`, `python`, `erp`, `scheduling-algorithm`, `invoice-generator`, `pymupdf`, `pydantic-v2`, `sqlite`

### B. List of 6 Repos to Pin
1. `smartcampus-ai`
2. `studybuddy-rag`
3. `mindtrack`
4. `bizdesk`
5. `AI_Smart_Attendance_System`
6. `prachi-portfolio`

---

## 3. LinkedIn Posts (One Per Project)

### Post 1: SmartCampus AI
```text
Manual attendance taking in university lecture halls wastes 10 to 15 minutes every single session, while academic intervention teams often identify struggling students too late—usually after semester final results are declared.

To address both challenges in a unified system, I built SmartCampus AI: an operations portal that brings automated facial attendance and early academic risk detection together.

Key highlights:
• Computer Vision Attendance: Captures webcam feeds and matches 128-dimensional spatial face feature vectors against enrolled student embeddings using cosine similarity (threshold >= 0.70).
• Early Warning Engine: A multi-factor penalty model weighing attendance deficiency (45%), midterm performance (25%), assignments (15%), and backlog counts (15 points) to segment students into Low, Medium, and High risk tiers before exams arrive.
• Direct Admin Exports: Native streaming CSV generator for daily and subject-level faculty audits.

Tech Stack: Python, FastAPI, OpenCV, Scikit-Learn, SQLite, HTML5/CSS3.

What I learned:
Handling state transitions in camera pipelines. A subtle edge case arose when absent students were scanned on camera—the endpoint originally blocked them with an "already marked" validation error. Reworking the query logic to allow clean status transitions from absent to present with updated confidence timestamps made the verification workflow far more reliable.

Check out the code & documentation:
https://github.com/prachizala/smartcampus-ai

#Python #FastAPI #OpenCV #MachineLearning #EdTech #SoftwareEngineering
```

### Post 2: StudyBuddy RAG
```text
When students study dense academic textbooks or lecture notes using standard generative chatbots, subtle hallucinations and out-of-context answers can quietly mislead exam preparation.

I designed StudyBuddy RAG to enforce a grounded question-answering workflow where the engine is strictly prohibited from guessing.

Key highlights:
• Binary Stream PDF Ingestion: Processes multi-page PDF documents in-memory using PyMuPDF without writing unencrypted temporary files to disk.
• Sliding Window Chunking: Slices documents into 300-word windows with 50-word overlaps to preserve semantic continuity across sentence boundaries.
• Strict Grounding Guardrail: Evaluates query relevance via character-trigram cosine vector matching. If the maximum similarity falls below threshold, it returns a deterministic refusal: "The uploaded material does not contain this information." (tested with 100% pass on out-of-context queries).
• Study Tools: Generates 5-question multiple choice quizzes with distractors and structured summaries directly from verified document chunks.

Tech Stack: Python, FastAPI, PyMuPDF, SQLite, TestClient, Pytest.

What I learned:
Handling raw binary payloads in REST APIs. When processing user-uploaded PDFs, decoding content as raw text causes immediate UnicodeDecodeErrors on binary headers. Switching to in-memory byte streams with PyMuPDF resolved the issue and simplified PDF indexing.

Code and test suites are available here:
https://github.com/prachizala/studybuddy-rag

#RAG #InformationRetrieval #FastAPI #Python #EdTech #NLP
```

### Post 3: MindTrack
```text
Digital wellness and journaling applications handle some of the most sensitive personal data a user can write. Storing journal entries in plain text in an application database exposes users to severe privacy risks.

I built MindTrack: a privacy-first mental health tracker designed around client-isolated data encryption and safety escalation.

Key highlights:
• AES-256 Field-Level Encryption: Journal entries are encrypted in application memory using Fernet (AES-128-CBC + HMAC-SHA256 authenticated encryption) before hitting SQLite. Zero plain text is ever stored on disk.
• Automated Crisis Sentinel: A deterministic regex engine evaluates unencrypted journal text during submission for explicit crisis patterns. If detected, it immediately prioritizes verified 24/7 national support resources (Tele-MANAS 14416 and Vandrevala Foundation) directly in the UI.
• Trend Analytics: Lexicon sentiment polarity scoring (-1.0 to +1.0) and 7-day emotional velocity charts to help users reflect on mood patterns over time.

Tech Stack: Python, FastAPI, Cryptography (Fernet), SQLite, HTML5/CSS3.

What I learned:
Cryptographic key management in lightweight deployments. Fernet strictly requires 32 url-safe base64-encoded bytes. If an environment injects an arbitrary passphrase, runtime initialization fails. Implementing a SHA-256 key derivation fallback ensured robust initialization without compromising key entropy.

Explore the repository:
https://github.com/prachizala/mindtrack

#CyberSecurity #DataPrivacy #Python #FastAPI #MentalHealth #Encryption
```

### Post 4: BizDesk
```text
For freelance consultants and small service agencies, scheduling conflicts and manual invoicing remain continuous operational pain points. Many off-the-shelf tools are either bloated or fail to strictly prevent overlapping bookings.

To solve this cleanly, I engineered BizDesk: a business operations ERP for appointment scheduling, client management, and instant invoice generation.

Key highlights:
• Collision Prevention: Implemented non-overlap interval math (A_start < B_end) & (A_end > B_start) in SQL and FastAPI service logic. Any attempted appointment that collides with an existing slot is blocked with an explicit conflict message.
• Vector PDF Invoicing: Generates clean, production-grade PDF invoices on the server using PyMuPDF vector drawing primitives, calculating line totals, tax rates, and payment terms on the fly.
• CRM & Revenue Analytics: Real-time dashboard calculating gross billings, outstanding balances, and monthly appointment volume.

Tech Stack: Python, FastAPI, Pydantic v2, PyMuPDF, SQLite, Pytest.

What I learned:
Strict API boundary validation. A client sending an appointment payload where start_time >= end_time previously triggered an unhandled exception inside the database query. Adding a Pydantic @field_validator caught chronological inversions at the schema boundary, returning an immediate, clean HTTP 422 before touching the database.

Full source code and test setup:
https://github.com/prachizala/bizdesk

#Python #FastAPI #BackendDevelopment #Pydantic #SystemDesign #SoftwareEngineering
```

---

## 4. One-Page Resume (Technical Focus)

```markdown
# PRACHI ZALA
📍 Ahmedabad, Gujarat, India | 📧 prachizala2003@gmail.com | 📱 [PLACEHOLDER: Phone Number]
💼 linkedin.com/in/prachi-zala-74a08b334 | 🌐 prachizala.github.io/prachi-portfolio | 🐙 github.com/prachizala

---

### EDUCATION
**Bachelor of Computer Applications (BCA)** | [PLACEHOLDER: University Name], Ahmedabad, Gujarat  
*Expected Graduation: 2026* | CGPA: [PLACEHOLDER: CGPA / Percentage]  
*Relevant Coursework:* Data Structures & Algorithms, Database Management Systems (DBMS), Object-Oriented Programming (Python/Java), Web Development, Operating Systems.

---

### TECHNICAL SKILLS
- **Programming Languages:** Python, SQL (SQLite, PostgreSQL), JavaScript, Java, HTML5, CSS3
- **Backend & APIs:** FastAPI, Pydantic v2, RESTful Architecture, Uvicorn, Starlette
- **Data & Applied AI:** OpenCV, Scikit-Learn, Pandas, NumPy, Vector Cosine Search, PyMuPDF
- **Security & Reliability:** AES-256 / Fernet Encryption, SHA-256 Key Derivation, Input Validation
- **Tools & DevOps:** Git, GitHub Actions (CI/CD), Pytest, TestClient, Postman, Linux/Bash basics

---

### FEATURED TECHNICAL PROJECTS

**SmartCampus AI — Campus Biometrics & Early Warning System** | *Python, FastAPI, OpenCV, SQLite*  
*(GitHub: github.com/prachizala/smartcampus-ai)*
- Built an automated attendance system using 128-dimensional facial spatial feature extraction with cosine similarity matching (D_cos >= 0.70).
- Developed an early academic warning model combining attendance deficiency (45%), midterm scores (25%), assignments (15%), and backlogs (15%) to classify student dropout risk into Low, Medium, and High tiers.
- Built a streaming CSV data export endpoint for faculty administration and verified API stability with 5/5 automated test suites.

**StudyBuddy RAG — Grounded Document QA & Study Platform** | *Python, FastAPI, PyMuPDF, SQLite*  
*(GitHub: github.com/prachizala/studybuddy-rag)*
- Developed an in-memory document indexing pipeline using PyMuPDF to extract text from binary PDF streams without temporary disk writes.
- Implemented 300-word sliding window chunking with 50-word overlaps and 256-dimensional sparse trigram cosine similarity retrieval.
- Engineered a zero-hallucination refusal guardrail returning deterministic refusals for ungrounded queries (verified 100% refusal rate on out-of-context test suites).
- Built automated 5-question multiple choice quiz generation with distractors and structured study summaries.

**MindTrack — Privacy-First Mental Health & Journaling Engine** | *Python, FastAPI, Cryptography, SQLite*  
*(GitHub: github.com/prachizala/mindtrack)*
- Implemented AES-256 field-level encryption via Fernet (CBC mode + HMAC authentication) with SHA-256 key derivation fallback, ensuring zero plain-text storage of personal thoughts.
- Built a deterministic crisis detection sentinel using regex pattern matching that flags distress keywords and immediately surfaces 24/7 national emergency helplines (Tele-MANAS 14416).
- Programmed a lexicon-based sentiment analysis tracker calculating emotional velocity across 7-day journaling windows.

**BizDesk — Appointment Scheduling & Vector PDF Invoicing ERP** | *Python, FastAPI, Pydantic v2, PyMuPDF*  
*(GitHub: github.com/prachizala/bizdesk)*
- Engineered an appointment booking engine with deterministic collision prevention using interval math (start_a < end_b) & (end_a > start_b).
- Developed a server-side vector PDF invoice generator using PyMuPDF drawing primitives with explicit resource reclamation (try...finally: doc.close()).
- Designed a business health dashboard tracking gross revenue, pending invoices, and monthly appointment volume with full Pydantic v2 data validation schemas.

---

### HONORS & CERTIFICATIONS
- **Hackathon Finalist / Team Lead:** [PLACEHOLDER: Hackathon Name, e.g., HACKCULT '26 or College Hackathon]
- **Certification:** [PLACEHOLDER: e.g., Python for Data Science / Full Stack Python — Provider Name]
```

---

## 5. Two-Minute Interview Pitches (One Per Project)

### Pitch 1: SmartCampus AI
> **"SmartCampus AI is an enterprise operations platform for colleges designed to solve two core administrative problems: proxy attendance and late detection of academic failure.**
>
> **My Role:** I designed and implemented the full architecture—from the database models and computer vision matching pipeline to the FastAPI REST endpoints and the faculty frontend.
>
> **Architecture:** The application runs on FastAPI with SQLite. When an image is received from the webcam, OpenCV extracts a normalized 128-dimensional spatial feature vector. We calculate the cosine similarity against enrolled student embeddings; matches at or above 0.70 confidence mark the student present. On the academic side, we built a weighted heuristic penalty model: attendance carries 45% weight, midterms 25%, assignments 15%, and backlogs 15 points. This generates a composite score from 0 to 100 that categorizes students into Low, Medium, or High risk tiers before end-of-term exams.
>
> **A Hard Bug I Fixed:** During Day 8 triage, webcam scans failed whenever a student was pre-marked 'absent' by faculty—the endpoint raised an HTTP 400 stating 'Attendance already marked for today'. In reality, students arriving late should be updated to 'present'. I updated the attendance service to detect existing records and cleanly transition status from 'absent' to 'present' with updated timestamps and confidence metrics, verifying it with automated tests.
>
> **What I Would Improve:** In production, I would upgrade the spatial block feature extractor to a deep metric model like FaceNet or InsightFace with an active anti-spoofing liveness check to prevent photo-on-screen replay attacks."

### Pitch 2: StudyBuddy RAG
> **"StudyBuddy RAG is an academic document question-answering system built specifically to eliminate hallucinations when students revise complex course materials.**
>
> **My Role:** I engineered the end-to-end document processing pipeline, vector retrieval logic, strict refusal guardrail, and quiz generator.
>
> **Architecture:** The core ingestion pipeline uses PyMuPDF to extract text directly from in-memory binary streams upon upload. We split the text into 300-word chunks with a 50-word sliding overlap to prevent context clipping. We generate sparse character-trigram frequency vectors and rank chunks using cosine similarity against the user query. The key differentiator is our grounding engine: if the maximum cosine similarity falls below our threshold, the system is strictly forbidden from answering and returns a deterministic refusal: *'The uploaded material does not contain this information.'*
>
> **A Hard Bug I Fixed:** When testing with real binary PDF files, the API crashed with `UnicodeDecodeError` because the initial parser attempted to read uploaded files as UTF-8 text strings. I refactored the file ingestion layer to pass binary streams directly to `fitz.open(stream=content, filetype="pdf")`, completely eliminating encoding failures. I also resolved a database foreign key constraint violation by ensuring sessions auto-provision prior to message persistence.
>
> **What I Would Improve:** I would integrate dense semantic vector embeddings via a local embedding model (like `all-MiniLM-L6-v2`) backed by ChromaDB or FAISS to handle synonymy and paraphrasing better than character n-grams."

### Pitch 3: MindTrack
> **"MindTrack is a privacy-first mental health journaling companion built on the premise that emotional and personal health data must never be readable in plain text on a database server.**
>
> **My Role:** I was responsible for the backend security architecture, cryptographic lifecycle, sentiment scoring algorithms, and the crisis intervention sentinel.
>
> **Architecture:** When a user logs a journal entry, the text is evaluated by an in-memory safety sentinel before persistent storage. The sentinel runs deterministic regex patterns to flag explicit crisis keywords. If triggered, the response payload immediately delivers verified 24/7 national support helplines (Tele-MANAS and Vandrevala Foundation). Simultaneously, the text is encrypted using Fernet (AES-128-CBC with HMAC-SHA256 authenticated encryption) before being written to SQLite. Plain text is never stored. For user reflections, a lexicon sentiment engine scores entries between -1.0 and +1.0 to plot weekly emotional velocity.
>
> **A Hard Bug I Fixed:** During setup, if an arbitrary 32-character passphrase was passed via environment variables, Fernet threw an unhandled exception because it requires a 32-byte url-safe base64 string. I introduced a robust SHA-256 key derivation fallback that hashes any raw secret into 32 bytes and base64-encodes it, preventing startup crashes.
>
> **What I Would Improve:** I would move the encryption boundary entirely to the client side using the Web Crypto API, so that decryption keys never touch the backend server, achieving zero-knowledge privacy."

### Pitch 4: BizDesk
> **"BizDesk is a focused business operations backend for service providers that automates appointment scheduling, client records, and vector PDF invoice generation.**
>
> **My Role:** I designed the schema models, implemented the interval collision detection logic, built the PDF drawing engine, and created the financial metrics dashboard.
>
> **Architecture:** The backend is built with FastAPI and SQLite, using Pydantic v2 schemas for strict boundary validation. The core scheduling engine evaluates time intervals mathematically: an appointment $[A_{start}, A_{end}]$ conflicts with an existing $[B_{start}, B_{end}]$ if and only if $(A_{start} < B_{end}) \land (A_{end} > B_{start})$. This prevents double-booking at the database query level. When an invoice is finalized, PyMuPDF builds a vector PDF dynamically in memory with line item calculations, taxes, and payment instructions.
>
> **A Hard Bug I Fixed:** In early testing, passing a payload where `start_time >= end_time` bypassed endpoint checks and caused an unhandled database exception that returned an HTTP 500 error. I implemented a Pydantic `@field_validator('end_time')` that checks timestamps at the deserialization stage, rejecting chronologically invalid payloads with an immediate, clear HTTP 422 error.
>
> **What I Would Improve:** I would add recurrence rules (i.e., RRULE support) for repeating weekly appointments and integrate asynchronous webhook workers to dispatch automated email and SMS appointment reminders."

---

## 6. Interview Questions and Answers per Project
Dedicated files have been added to the root of each project repository:
- `smartcampus-ai/INTERVIEW_QA.md`
- `studybuddy-rag/INTERVIEW_QA.md`
- `mindtrack/INTERVIEW_QA.md`
- `bizdesk/INTERVIEW_QA.md`
