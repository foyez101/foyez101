# Hi there, I'm Abdullah Al Mamun (Foyez) 👋

### Full-Stack & AI Engineer | React · Next.js · Node.js · NestJS · TypeScript | RAG · LLMs · NLP

I build web applications that real businesses use, and I add AI where it actually helps, from a live order management system for a garment buying house to a RAG app that answers questions about company annual reports.

---

## 👨‍💻 About Me

I'm a Computer Science & Engineering graduate (BUBT) who works across the full stack and applied AI:

- **Full-stack:** I've built and delivered a live, multi-role web app for a real client, and I'm building an e-commerce platform for a clothing brand.
- **AI / NLP:** I've built a RAG system with hybrid retrieval and fine-tuned speech and summarization models for Bengali.

I like owning a feature end to end: database design, backend APIs, frontend UX and deployment.

📍 Dhaka, Bangladesh · Open to **Junior Software Engineer**, **Full-Stack** and **AI Engineer** roles

---

## 🚀 Featured Projects

### 🏭 Order Management System – Wing Fat Enterprise Ltd
*Client project · Live: [uhobd.com](https://uhobd.com)*

A web-based order management system for a garment buying house, covering the full order lifecycle from pre-order, CAD and sampling to QC inspection, purchase order and shipment.

- **Stack:** React (Vite) · Tailwind CSS · Node.js · Express.js · MySQL · JWT · bcrypt · Web Push · PWA
- Role-based access for **5 roles** (Managing Director, Merchandiser Manager, Merchandiser, QC, Office), with department-level data isolation enforced in the API
- Role-specific dashboards (monthly revenue, overdue orders, department comparison) with custom SVG charts, plus in-app and device push notifications
- Rate limiting, email OTP codes and a forced password change on first login
- Deployed on a VPS with a custom domain behind Cloudflare

### 📊 Financial Report Analyzer – RAG Question Answering
*AI project · [github.com/foyez101/financial-report-analyzer](https://github.com/foyez101/financial-report-analyzer)*

Ask a question about a company's annual report and get an answer with page citations, or "Not found in the report" instead of a guess.

- **Stack:** Python · PyMuPDF · Sentence-Transformers (bge-small) · ChromaDB · BM25 · Google Gemini API · Streamlit
- Covers 4 Bangladeshi annual reports (Square Pharmaceuticals, Grameenphone, BRAC Bank), about 2,500 indexed chunks
- Rebuilds financial-table rows from word positions and automatically splits two-page spreads
- **Hybrid retrieval** (BM25 + vectors, fused with RRF) raised MRR from **0.51 to 0.66** over vector search alone
- Answered **15/15** test questions correctly and refused **4/4** unanswerable ones

### 🎙️ Bengali Audio Transcription and Summarization with a Newly Developed Dataset
*Undergraduate thesis · [GitHub](https://github.com/foyez101/Automatic-Bengali-Meeting-Minutes-Generation-using-Fine-Tuned-Speech-Recognition-and-Summarization)*

Upload Bengali audio and get a transcript plus a concise summary.

- **Stack:** Python · PyTorch · Hugging Face Transformers · Whisper-small · BanglaT5 · FastAPI · FFmpeg · Kaggle
- Built a new dataset of **1,160** Bengali audio clips with verbatim transcripts and reference summaries
- Fine-tuned Whisper-small: word error rate **55.0% → 17.3%**, character error rate **22.6% → 6.0%**
- Fine-tuned BanglaT5 for abstractive summarization: ROUGE-L **14.5 → 25.3** over the earlier mT5-small model

### 👕 NEON MAN – Clothing E-commerce Platform
*Client project · in development (private repo)*

- **Stack:** Next.js · React (Vite) · NestJS · TypeScript · PostgreSQL · Prisma ORM · Resend
- Next.js storefront and React admin panel for products, stock and orders
- Cash-on-delivery checkout that reserves stock at order time and releases it on cancellation
- Email OTP verification at sign-up and password reset by emailed code

<details>
<summary><b>Earlier projects</b></summary>

- 🎓 **[Scholario](https://github.com/foyez101/Scholario)**: full-stack assignment and submission platform (Next.js, Express, Prisma, PostgreSQL) with Admin, Teacher and Student roles
- 🐍 **Python mini-projects**: ATM simulator, text-to-speech tool, password generator, table generator

</details>

---

## 🛠 Technical Skills

**Languages:** JavaScript, TypeScript, Python, C, C++, SQL, HTML/CSS

**Frontend:** React, Next.js, Vite, Tailwind CSS

**Backend:** Node.js, Express.js, NestJS, FastAPI, REST APIs, JWT authentication, role-based access control

**AI / ML:** RAG, hybrid search (BM25 + embeddings), LLM APIs (Google Gemini), NLP, speech recognition (Whisper), text summarization (BanglaT5, mT5), model fine-tuning, PyTorch, Hugging Face Transformers, Sentence-Transformers

**Databases:** MySQL, PostgreSQL, Prisma ORM, ChromaDB (vector database)

**Tools & Deployment:** Git, GitHub, Linux VPS, Cloudflare, Kaggle, Google Colab, Streamlit, Figma

---

## 📊 GitHub Stats

![](https://github-stats-extended.vercel.app/api?username=foyez101&show_icons=true&theme=tokyonight)

![](https://github-stats-extended.vercel.app/api/top-langs/?username=foyez101&layout=compact&theme=tokyonight)

---

## 🤝 Let's Connect

📧 **Email:** [abdullahfoyez110@gmail.com](mailto:abdullahfoyez110@gmail.com)

💼 **LinkedIn:** [linkedin.com/in/abdullahalmamun-dev](https://www.linkedin.com/in/abdullahalmamun-dev)

🌐 **Portfolio:** [foyez101.github.io/portfolio](https://foyez101.github.io/portfolio)

💻 **GitHub:** [github.com/foyez101](https://github.com/foyez101)

---

> Building software that real people use, and adding AI where it actually helps.
