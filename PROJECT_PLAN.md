# 90-Day Engineering Career Roadmap & Project Plan
**Developer:** Prachi Zala (BCA Student, Ahmedabad, Gujarat)  
**Target Profile:** Python Developer / AI & Data Analytics Engineer  
**GitHub:** [github.com/prachizala](https://github.com/prachizala) | **Current Date:** November 2026  
**Project Manager & Lead Engineer Execution Plan**

---

## 🎯 Executive Goals & Success Criteria

1. **Portfolio Breadth & Depth:**
   - Maintain **4 upgraded legacy projects** (Portfolio, MindTracker, MATHSPRINT, AI Smart Attendance).
   - Build **4 brand-new industry-grade projects** (Student Performance Predictor, Mood Tracker with NLP, Sales & Expense Analytics Dashboard, AI Chatbot with LLM API).
   - Achieve **8+ public, polished repositories** with production READMEs, architecture diagrams, unit tests, automated CI workflows, and live deployment links.
2. **Technical Mastery & Interview Readiness:**
   - Master Python, Pandas, Scikit-Learn, Streamlit, OpenCV, SQLite, Plotly, and LLM APIs.
   - Clean, modular codebases with inline explanatory comments so every line can be defended in technical interviews.
3. **Public Visibility & Professional Profile:**
   - Transform GitHub profile (`prachizala/prachizala`) into a high-signal recruiter magnet.
   - Deploy interactive live web demos on Render / Streamlit Community Cloud / GitHub Pages.
   - Publish 3 high-quality Kaggle data science notebooks and participate in 1–2 hackathons.
   - Create a tailored 1-page ATS-optimized resume and weekly LinkedIn engineering logs.

---

## 📅 90-Day Roadmap: 3 Monthly Milestones

```
+---------------------------------------------------------------------------------------------------+
| MONTH 1: Days 1–30 | REPO AUDIT, LEGACY UPGRADE & CORE ML FOUNDATION                              |
| - Audit & polish existing repos (Portfolio, MindTracker Android, MATHSPRINT)                      |
| - Upgrade AI_Smart_Attendance_System with Streamlit UI, SQLite DB & CSV Export                   |
| - Build Project 1: Student Performance Predictor (Pandas + Scikit-Learn + Streamlit)              |
+---------------------------------------------------------------------------------------------------+
                                                  |
                                                  v
+---------------------------------------------------------------------------------------------------+
| MONTH 2: Days 31–60 | DATA ANALYTICS, NLP & VISUALIZATION POWERHOUSE                             |
| - Build Project 2: Mood Tracker with Sentiment Analysis (NLP + Interactive Charts)                |
| - Build Project 3: Sales/Expense Analytics Dashboard (Plotly + Advanced Data Cleaning)            |
| - GitHub Profile README overhaul + Portfolio site update with live project cards                  |
| - Hackathon scouting & team formation                                                             |
+---------------------------------------------------------------------------------------------------+
                                                  |
                                                  v
+---------------------------------------------------------------------------------------------------+
| MONTH 3: Days 61–90 | GENERATIVE AI, HACKATHON PARTICIPATION & CAREER LAUNCH                      |
| - Build Project 4: Production AI Chatbot (LLM API + Prompt Design + Context History)              |
| - Publish 3 Kaggle Notebooks (EDA, ML Modeling, NLP Analysis)                                     |
| - Hackathon submission, pitch deck, and video demo recording                                      |
| - Final 1-Page Resume, LinkedIn thought leadership series, and FINAL_REPORT.md                     |
+---------------------------------------------------------------------------------------------------+
```

---

## 🗓️ Weekly Task Breakdown (Weeks 1 – 12)

### Month 1: Foundation, Upgrades & Supervised Learning
- **Week 1 (Days 1–7): Deep Audit & Legacy Standardization**
  - Execute comprehensive repository audit across code quality, tests, docs, and assets.
  - Fix `prachi-portfolio`: add HTML5/CSS automated validation checks, live demo badges, responsive styling audit.
  - Fix `mental-health-tracker-android`: add Gradle wrapper configuration, JUnit test for SQLite `DatabaseHelper`, architecture documentation, and APK release link.
  - Fix `MATHSPRINT`: declutter large binary slide decks from root into documentation, standardize test scripts, and write comprehensive API/architecture docs.
- **Week 2 (Days 8–14): AI Smart Attendance System Evolution**
  - Build a clean, self-contained Streamlit/Flask Web UI for the attendance system.
  - Implement SQLite database integration (`attendance.db`) tracking employees, timestamps, geofence status, and biometric match confidence.
  - Add single-click CSV attendance report export with filterable date ranges and department filters.
  - Add mock webcam/demo image upload mode for seamless recruiter testing without hardware camera access.
  - Write Pytest test suite and GitHub Actions CI workflow.
- **Week 3 (Days 15–21): Project 1 — Student Performance Predictor (Data & Modeling)**
  - Source and curate representative student academic dataset (demographics, study habits, test scores).
  - Perform exploratory data analysis (EDA), missing value handling, feature encoding, and feature scaling using Pandas/NumPy.
  - Train and benchmark multiple regression/classification models (Linear Regression, Decision Tree, Random Forest, Gradient Boosting) using `scikit-learn`.
  - Evaluate with $R^2$, RMSE, MAE, and cross-validation scores.
- **Week 4 (Days 22–30): Project 1 — Deployment & Month 1 Review**
  - Build interactive Streamlit dashboard allowing users to input study hours, attendance rate, and quiz scores to get real-time predicted final grades.
  - Add feature importance plots and what-if simulation sliders.
  - Write comprehensive README, setup instructions, and deploy live on Streamlit Cloud.
  - Month 1 progress review and retrospective.

---

### Month 2: NLP, Business Intelligence & Profile Modernization
- **Week 5 (Days 31–37): Project 2 — Mood Tracker with Sentiment Analysis (Core NLP)**
  - Design NLP pipeline for text sentiment analysis using VADER / TextBlob / Hugging Face Transformers.
  - Build data pipeline for daily mood journal entries with timestamping and category tagging.
  - Implement emotion classification (Joy, Sadness, Anxiety, Calm, Anger).
- **Week 6 (Days 38–44): Project 2 — Interactive Dashboard & Visualization**
  - Build Streamlit/Dash interactive interface displaying rolling 7-day and 30-day sentiment trendlines.
  - Add word clouds, trigger keyword extraction, and automated wellness tips based on sentiment scores.
  - Write Pytest tests for NLP scoring edge cases (negations, emojis, mixed sentiments).
  - Deploy with sample demonstration data and push to GitHub.
- **Week 7 (Days 45–51): Project 3 — Sales & Expense Analytics Dashboard (BI & Plotly)**
  - Assemble realistic multi-year business sales and expense dataset (E-commerce / Retail).
  - Implement robust data cleaning pipeline: anomaly detection, missing data imputation, currency normalization, and outlier trimming.
  - Build dynamic Plotly dashboard: revenue trends, profit margin breakdowns, category sunbursts, regional sales heatmaps, and expense burn-rate gauges.
- **Week 8 (Days 52–60): Project 3 — Deployment & Profile Transformation**
  - Package dashboard with customizable date pickers, department filters, and automated Executive Summary PDF/CSV download.
  - Redesign GitHub Profile README (`prachizala/prachizala`): dynamic stats, tech badges, curated project showpieces with live demo badges.
  - Update `prachi-portfolio` website to highlight newly completed data/AI projects with screenshots and links.

---

### Month 3: Generative AI, Competitive Edge & Career Launch
- **Week 9 (Days 61–67): Project 4 — Production AI Chatbot (Architecture & API)**
  - Implement Python AI Chatbot using official Gemini / OpenAI API with secure environment variable loading.
  - Engineer system prompts for specialized domain personas (e.g. Academic Tutor or Data Assistant).
  - Implement conversational memory / multi-turn session chat history management with token pruning.
- **Week 10 (Days 68–74): Project 4 — UI, Guardrails & Production Polish**
  - Build clean Streamlit/FastAPI web interface featuring streaming chat responses, message editing, and clear conversation history.
  - Add safety guardrails, input validation, and markdown code syntax highlighting in responses.
  - Write automated tests mocking LLM responses; deploy live application.
- **Week 11 (Days 75–81): Hackathons & Kaggle Portfolio**
  - Publish 3 Kaggle Notebooks:
    1. Student Academic Performance EDA & Predictive Modeling
    2. Sentiment & Emotion Analysis on Journal Texts
    3. Retail Sales Forecasting & Business Metric Optimization
  - Register and execute a targeted hackathon (Unstop / Devpost / Hackerearth).
  - Prepare a 3-minute video demo walkthrough and concise slide deck using the structured pitch framework.
- **Week 12 (Days 82–90): Final Launch, Resume & Job Hunting Readiness**
  - Finalize 1-page ATS-compliant resume highlighting metrics, tech stack, and GitHub project links.
  - Draft LinkedIn showcase posts for all projects with screenshots and architectural breakdowns.
  - Generate `FINAL_REPORT.md` documenting repositories, execution guidelines, and interview talking points.

---

## ⚖️ Priorities & Risk Matrix

| Priority | Focus Area | Risk | Mitigation Strategy |
| :--- | :--- | :--- | :--- |
| **P0** | **Runnable, Error-Free Code** | Broken dependencies or OS incompatibility (Windows vs Linux) | Pin strict versions in `requirements.txt`, use virtual environments (`venv`), and test clean installs. |
| **P0** | **Authenticity (Anti-Hallucination)** | Claiming fake metrics or exaggerated user numbers | Use explicit `[ADD RESULT]` placeholders for personal metrics; focus on measurable technical architecture rather than vanity numbers. |
| **P1** | **Live Deployable Demos** | Cloud hosting timeouts or free-tier sleep delays | Deploy to Streamlit Community Cloud / Render with pre-cached sample datasets for instant loading. |
| **P1** | **Interview Explainability** | Writing overly complex boilerplate that is hard to explain in viva/interviews | Keep code modular, strictly adherence to PEP 8, and include explanatory docstrings and inline comments. |
| **P2** | **GitHub Activity Consistency** | Irregular burst commits looking artificial | Maintain an authentic daily/weekly commit cadence with atomic, conventional commit messages (`feat:`, `fix:`, `docs:`, `test:`). |

---

## 📌 Sensible Assumptions Made
1. **Local Operating System:** Windows 11 with PowerShell shell environment.
2. **Primary Languages & Runtimes:** Python 3.10+ as the primary focus; existing Java (Android) and TypeScript (React Native/Node) maintained as secondary supporting assets.
3. **Hardware Constraints:** Webcam access may vary during grading/interviews; biometric systems must include a "Demo Upload" fallback mode.
4. **Cloud/Hosting:** Free tier cloud services (Streamlit Cloud, Render, GitHub Pages, Hugging Face Spaces) utilized for zero hosting expenses.
