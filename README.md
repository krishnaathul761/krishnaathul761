# Hi there, I'm Athul Krishna A! 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=500&lines=Software+Development+Engineer;Backend+%26+Applied+AI+Developer;Python+%7C+FastAPI+%7C+JavaScript;Chrome+Manifest+V3+%7C+PostgreSQL" alt="Typing SVG" />
</div>

## 🚀 About Me

- 💻 Software Development Engineer focused on **Python, FastAPI, JavaScript (ES6+), Relational Databases (PostgreSQL/SQLAlchemy), and Applied AI**
- 🎓 Completed **Software Development Engineering with Applied AI** at **Masai School in collaboration with IIT Patna (Vishlesan i-Hub)** (August 2026)
- 🎓 B.Tech Engineering Graduate — **Kerala Technological University, 2024**
- 🛠️ Creator of **ZOMATO-NOTES** (AI-augmented internal engineering knowledge base with 1.0 MRR vector search) and **AI-Browser** (Multimodal Chrome Manifest V3 extension copilot)
- 🧠 Actively solving problems on **LeetCode** with a focus on algorithmic complexity, data structures, and optimization
- 🔧 Experienced in **REST API design, database connection pooling, cryptographic authentication (bcrypt), automated testing (unittest/CI), and cloud deployment**
- 📫 Reach me at **[krishnaathul761@gmail.com](mailto:krishnaathul761@gmail.com)** | **[LinkedIn](https://linkedin.com/in/athulkrishnaatk)**

---

## 🛠️ Technical Skills

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & API Engineering
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)

### Databases & Cloud Deployment
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

### Applied AI & Search
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-FFD21E?style=for-the-badge)
![Embeddings](https://img.shields.io/badge/Dense%20Embeddings-FF6F00?style=for-the-badge)
![Semantic Search](https://img.shields.io/badge/Semantic%20Search%20(Cosine)-6A5ACD?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq%20LLM%20(LLaMA%203.1%2F3.3)-F05032?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini%20Flash-8E75C2?style=for-the-badge&logo=google&logoColor=white)

### Testing, DevOps & Browser Platform
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions%20CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Unittest](https://img.shields.io/badge/Python%20unittest-3776AB?style=for-the-badge)
![Chrome Extensions](https://img.shields.io/badge/Chrome%20Manifest%20V3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🌟 Featured Engineering Projects

### 1. 🍴 [ZOMATO-NOTES — Incident Knowledge Base & Semantic Retrieval Platform](https://github.com/krishnaathul761/ZOMATO-NOTES)

[![CI](https://github.com/krishnaathul761/ZOMATO-NOTES/actions/workflows/ci.yml/badge.svg)](https://github.com/krishnaathul761/ZOMATO-NOTES/actions/workflows/ci.yml)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.141.1-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Supabase-316192?style=flat-square&logo=postgresql&logoColor=white)](https://supabase.com)
[![Tests](https://img.shields.io/badge/Tests-32%20Passed%20(100%25)-brightgreen?style=flat-square)](https://github.com/krishnaathul761/ZOMATO-NOTES)

> An internal engineering knowledge-base and incident postmortem service supporting rapid categorization, structured analytics, and semantic vector retrieval.

**Key Engineering Highlights & Verified Evidence:**
- **Relational Data Modeling & Analytics:** Designed a 3NF relational schema in **SQLAlchemy ORM** connected to **Supabase PostgreSQL** with connection pooling (`pool_pre_ping=True`, 300s recycle) and foreign key ownership cascade rules (`cascade="all, delete-orphan"`). Authored 3 parameterized raw SQL analytical reporting queries (`GROUP BY ... HAVING`, subquery content length analysis, and multi-table left joins).
- **Dense Semantic Vector Search:** Integrated HuggingFace `sentence-transformers/all-MiniLM-L6-v2` generating 384-dimensional dense vectors with NumPy cosine similarity math, achieving **MRR = 1.0000** and **Precision@3 = 0.5417** across technical query benchmarks (**+60.0% ranking gain** over keyword search).
- **Algorithmic Profiling & Sub-3 Microsecond Lookups:** Implemented and profiled custom Insertion Sort ($O(n^2)$) vs Binary Search ($O(\log n)$), achieving sub-3 microsecond lookups (<0.003 ms) across datasets up to 1,000 records.
- **Hybrid AI Pipeline:** Integrated **Groq LLaMA-3.1-8B** for structured JSON auto-tagging with a deterministic offline regex fallback (`_mock_response`) guaranteeing zero user-facing 500 errors during API outages.
- **Security & Authentication:** Hardened user authentication using **salted cryptographic password hashing (`bcrypt` with 12 work rounds)** and Pydantic validation.
- **Automated Testing & CI/CD Pipeline:** Built a **32-test automated regression suite** (100% pass rate in <1s) running on **GitHub Actions CI** on every push and pull request.

**Tech Stack:** `Python` `FastAPI` `PostgreSQL (Supabase)` `SQLite` `SQLAlchemy ORM` `Pydantic` `bcrypt` `Sentence-Transformers` `Groq LLaMA-3.1` `GitHub Actions CI`  
🔗 **[View Source Code](https://github.com/krishnaathul761/ZOMATO-NOTES)** | 🌐 **[Live Application](https://krishnaathul761.github.io/ZOMATO-NOTES/)** | 📚 **[Interactive API Docs (Swagger)](https://zomato-notes.onrender.com/docs)**

---

### 2. 🧭 [AI-Browser (Sahayak) — Multimodal AI Copilot (Chrome MV3 Extension)](https://github.com/krishnaathul761/AI-Browser)

[![Chrome MV3](https://img.shields.io/badge/Chrome-Manifest%20V3-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://developer.chrome.com/docs/extensions/mv3/intro/)
[![Vanilla JS](https://img.shields.io/badge/Vanilla%20JS-Zero--Build-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Gemini](https://img.shields.io/badge/Google-Gemini%201.5%20Flash-8E75C2?style=flat-square&logo=google&logoColor=white)](https://ai.google.dev/)
[![Groq](https://img.shields.io/badge/Groq-LLaMA%203.3%2070B-F05032?style=flat-square)](https://groq.com)

> A client-side multimodal AI assistant built on Chrome Manifest V3 operating directly within the Chrome Side Panel for page reading, video analysis, in-page grounded chat, and visual question answering.

**Key Engineering Highlights & Verified Evidence:**
- **Multi-Runtime Isolation Architecture:** Architected across 4 distinct Chromium execution contexts (Isolated Content Script, Ephemeral Background Service Worker, Sidepanel UI, and Options Page) communicating via asynchronous message passing and `chrome.storage.local`.
- **Dual-Engine LLM Fallback Routing:** Implemented intelligent model router prioritizing **Google Gemini 1.5 Flash** with automated fallback to **Groq LLaMA 3.3 70B Versatile**, gracefully mitigating API rate limits, timeouts, and network drops.
- **DOM Cloning & Content Extraction:** Sanitizes host web pages by cloning document nodes (`document.cloneNode(true)`) and running Mozilla Readability to extract structured article markdown without mutating live host page state.
- **Multimodal Video Intelligence & In-Tab Seeking:** Analyzes public YouTube videos via watch URL, extracting chapter timestamps with a statistical cutoff filter ($\le 1.2 	imes 	ext{secondToLast} + 30	ext{s}$) to prune hallucinations, enabling direct in-tab video seeking (`&t=SECONDS`).
- **Interactive HTML5 Canvas Drag-to-Crop Engine:** Built a custom canvas screenshot engine that maps 320px responsive sidepanel coordinates to full-resolution device bitmaps with a 4× zoom loupe for Visual Question Answering (VQA).
- **Grounded Chat with State Invalidation:** Maintains in-page conversational history bounded by a 50-item LRU cache, with automatic tab navigation listeners to reset history upon page changes.
- **Zero-Build Architecture:** Engineered 3,450+ lines of modular, clean ES6+ JavaScript with zero node_modules or runtime bundlers.

**Tech Stack:** `JavaScript (ES6+)` `Chrome Manifest V3` `Service Workers` `HTML5 Canvas API` `Mozilla Readability` `Google Gemini API` `Groq SDK` `DOM APIs`  
🔗 **[View Source Code](https://github.com/krishnaathul761/AI-Browser)** | 📑 **[Architecture Documentation](https://github.com/krishnaathul761/AI-Browser/tree/main/Docs)**

---

## 🧠 Data Structures & Algorithms

I am actively sharpening my algorithmic problem-solving skills on **LeetCode**, focusing on algorithmic patterns, space/time complexity trade-offs, and clean implementation.

### LeetCode Progress

| Metric | Details |
| :--- | :--- |
| **Problems Solved** | **25** (11 Easy, 14 Medium, 0 Hard) |
| **Core Algorithmic Focus** | Arrays, Two Pointers, Sliding Window, Binary Search, Hash Maps, Greedy, Dynamic Programming |
| **Profile Link** | **[leetcode.com/u/athulkrishna761/](https://leetcode.com/u/athulkrishna761/)** |

---

## 🎓 Education & Training

### Software Development Engineering with Applied AI
**Masai School × IIT Patna (Vishlesan i-Hub)** | *Completed — August 2026*
- Core Focus: Full-Stack Engineering, Backend Architecture (FastAPI), Relational Database Design, Data Structures & Algorithms, Applied AI & LLM Integration, Cloud Deployment.

### Bachelor of Technology — Engineering
**Kerala Technological University** | *Graduated — 2024*
- Engineering foundation in analytical thinking, mathematical problem-solving, and systems-oriented engineering principles.

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/athulkrishnaatk)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krishnaathul761@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/athulkrishna761/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/krishnaathul761)

</div>

---

<div align="center">

### 💭 *"Code is like humor. When you have to explain it, it's bad."* — Cory House

![Profile Views](https://komarev.com/ghpvc/?username=krishnaathul761&color=blueviolet&style=for-the-badge)

</div>
