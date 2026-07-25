# Ishan Chhaparwal

**Final-Year Computer Engineering Student · AI/ML & Full-Stack (MERN) Developer**

LinkedIn: [linkedin.com/in/ishan-chhaparwal](https://www.linkedin.com/in/ishan-chhaparwal/) · GitHub: [github.com/Ishan-1104](https://github.com/Ishan-1104) · Based in Pune, India

I build end-to-end AI products — from LLM-powered agents and RAG pipelines to full-stack web apps and ML models — and ship them with real UIs, not just notebooks.

---

## About Me

- Final-year Computer Engineering student, focused on AI, Machine Learning, Deep Learning, and Generative AI
- Full-Stack (MERN) developer, comfortable owning a product from database to UI
- Currently deep-diving into LLM agents, RAG pipelines, LangChain, and MLOps
- Ships projects with real deployments on Vercel and Streamlit Cloud, not just local demos
- Open to AI/ML and Full-Stack development internships and opportunities

---

## Contribution Snake

A GitHub Action regenerates this daily from my contribution graph:

```
https://raw.githubusercontent.com/Ishan-1104/Ishan-1104/output/github-contribution-grid-snake-dark.svg
```

Setup instructions are at the bottom of this file. Once the workflow has run at least once, this can be embedded directly in the README as an image if you change your mind on images later — for now it's left as a link so nothing here can show up broken.

---

## Featured Projects

### ResearchMind — Multi-Agent AI Research System
[github.com/Ishan-1104/Multi_Agent_System](https://github.com/Ishan-1104/Multi_Agent_System) · [Live demo](https://research-mind-18.streamlit.app/)

- Multi-agent pipeline that searches the web, scrapes full content, drafts a structured report, and critiques its own output — orchestrated end-to-end with LangChain
- Pipeline stages: Search Agent (Tavily + Mistral tool-calling) → Scraper (BeautifulSoup, with URL fallback) → Writer Chain (900–1200 word report) → Critic Chain (self-scored feedback)
- Streamlit UI with real-time stage tracking, run history, and Markdown export

**Stack:** Python, LangChain, Mistral AI, Tavily, BeautifulSoup4, Streamlit

### AI Video Assistant (Video-Agent)
[github.com/Ishan-1104/Video-Agent](https://github.com/Ishan-1104/Video-Agent) · [Live demo](https://video-agent-18.streamlit.app/)

- Transcribes any meeting recording or YouTube video (English + Hinglish) and auto-generates a title, summary, action items, and open questions
- RAG-based chat over the transcript using a Chroma vector store, HuggingFace embeddings, and LangChain LCEL with Mistral AI
- Ships as both a scriptable CLI and a full Streamlit web UI with live pipeline status and export

**Stack:** Python, LangChain, Mistral AI, ChromaDB, Sentence-Transformers, Streamlit

### Streamify
[github.com/Ishan-1104/Streamify](https://github.com/Ishan-1104/Streamify) · [Live demo](https://streamify-1-gesi.onrender.com)

- Full-stack, real-time chat and video communication platform with a responsive, modern UI
- In-app video calling alongside one-on-one and group text chat
- Authentication with protected routes, plus a friends/connections system for managing contacts

**Stack:** Node.js, Express, React — deployed on Vercel/Render

### ResumeForge AI
[github.com/Ishan-1104/resumeforge-ai-1](https://github.com/Ishan-1104/resumeforge-ai-1) · [Live demo](https://resumeforge-ai-five.vercel.app)

- Turns raw project descriptions into ATS-ready resume content — bullet points, summaries, and skills lists
- Powered by Groq's `llama-3.3-70b-versatile` for fast inference
- Built as a polished SaaS-style tool rather than a bare script, with a full Next.js frontend

**Stack:** Next.js 15, TypeScript, Tailwind CSS, Groq API

### CineAI
[github.com/Ishan-1104/CineAI](https://github.com/Ishan-1104/CineAI) · [Live demo](https://cineai-6ygv.onrender.com)

- AI-powered movie recommendation platform built on a client/server architecture
- Separates recommendation logic on the server from a JavaScript client, MERN-style
- Deployed live rather than left as a local-only demo

**Stack:** JavaScript (MERN-style client/server split)

### Multi-Disease Prediction System
[github.com/Ishan-1104/multi-diseases](https://github.com/Ishan-1104/multi-diseases) · [Live demo](https://multi-diseases-xahsafbhcqcsgfpvpkqgu2.streamlit.app/)

- Predicts the likelihood of diabetes, heart disease, and Parkinson's disease from patient data
- Trained scikit-learn models serialized and served through a Python prediction script
- Packaged as an interactive Streamlit app rather than a notebook-only result

**Stack:** Python, scikit-learn, Pandas

---

## Tech Stack

**Languages:** Python, JavaScript, TypeScript, C++

**Frontend:** React, Next.js, Tailwind CSS, HTML5, CSS3

**Backend & Databases:** Node.js, Express, MongoDB

**AI / ML / GenAI:** LangChain, scikit-learn, Pandas, NumPy, Streamlit, Mistral AI

**Tools & Platforms:** Git, GitHub, Vercel, VS Code

---

## Currently Learning / Building

- **Learning:** LLM architectures, LangChain internals, RAG system design, vector databases, MLOps
- **Building:** production-grade AI applications (agentic pipelines, RAG assistants) and MERN full-stack products

---

## Connect

LinkedIn: [linkedin.com/in/ishan-chhaparwal](https://www.linkedin.com/in/ishan-chhaparwal/)
GitHub: [github.com/Ishan-1104](https://github.com/Ishan-1104)

If a project here caught your eye, a star means a lot — thanks for stopping by.

---

## Setting up the Contribution Snake

The snake animation is generated by the [Platane/snk](https://github.com/Platane/snk) GitHub Action, not by markdown alone:

1. Add the included `snake.yml` to this repo at `.github/workflows/snake.yml`.
2. In Settings → Actions → General → Workflow permissions, enable "Read and write permissions."
3. Commit, then run the workflow once manually from the Actions tab.
4. An `output` branch appears holding the generated SVGs. At that point you can embed it as an image if you want it visible in the README — until then it's left as a plain link above so nothing renders broken.
