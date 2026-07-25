<div align="center">

# Hi, I'm Ishan Chhaparwal 👋

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Final-Year+Computer+Engineering+Student;AI%2FML+Developer;Full-Stack+(MERN)+Developer" alt="Typing SVG" />
</a>

I build end-to-end AI products — from LLM-powered agents and RAG pipelines to full-stack web apps and ML models — and ship them with real UIs, not just notebooks.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ishan-chhaparwal/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ishan-1104)
[![Location](https://img.shields.io/badge/Based%20in-Pune%2C%20India-orange?style=for-the-badge)]()

</div>

---

## 🧭 About Me

- 🎓 Final-year Computer Engineering student, focused on **AI, Machine Learning, Deep Learning, and Generative AI**
- 🌐 Full-Stack (MERN) developer, comfortable owning a product from database to UI
- 🤖 Currently deep-diving into **LLM agents, RAG pipelines, LangChain, and MLOps**
- 🚀 Ships projects with real deployments on **Vercel and Streamlit Cloud**, not just local demos
- 💼 Open to **AI/ML and Full-Stack development internships** and opportunities

---

## 🐍 Contribution Snake

A GitHub Action regenerates this daily from my contribution graph:

<div align="center">

![snake gif](https://raw.githubusercontent.com/Ishan-1104/Ishan-1104/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 🚀 Featured Projects

### 🧠 [ResearchMind — Multi-Agent AI Research System](https://github.com/Ishan-1104/Multi_Agent_System)
**[🔗 Live Demo](https://research-mind-18.streamlit.app/)**

- 🔍 **Orchestrated multi-agent pipeline:** a Search Agent (Tavily + Mistral tool-calling) finds relevant sources, a Scraper (BeautifulSoup, with a URL fallback) pulls the full page content, and the whole flow is chained end-to-end with LangChain so each stage feeds the next automatically.
- ✍️ **Self-critiquing report generation:** the Writer Chain drafts a structured 900–1200 word report from the scraped material, then a separate Critic Chain reviews and self-scores that output, giving the pipeline a built-in quality-check step instead of a single-pass generation.
- 📊 **Real-time Streamlit interface:** tracks pipeline stage progress live as the agents work, keeps a history of past runs for reference, and lets users export the final report directly to Markdown.

`Python` `LangChain` `Mistral AI` `Tavily` `BeautifulSoup4` `Streamlit`

---

### 🎥 [AI Video Assistant (Video-Agent)](https://github.com/Ishan-1104/Video-Agent)
**[🔗 Live Demo](https://video-agent-18.streamlit.app/)**

- 🎙️ **Bilingual transcription and summarization:** takes any meeting recording or YouTube video in English or Hinglish and automatically generates a title, summary, action items, and open questions, turning raw audio into a structured meeting record.
- 💬 **RAG-based chat over the transcript:** builds a Chroma vector store from the transcript using HuggingFace sentence-transformer embeddings, then lets users ask follow-up questions answered through a LangChain LCEL pipeline backed by Mistral AI.
- 🖥️ **Dual interface design:** ships as both a scriptable CLI for automation/batch use and a full Streamlit web UI with live pipeline status, so it works equally well in a terminal workflow or as a standalone app.

`Python` `LangChain` `Mistral AI` `ChromaDB` `Sentence-Transformers` `Streamlit`

---

### 💬 [Streamify](https://github.com/Ishan-1104/Streamify)
**[🔗 Live Demo](https://streamify-1-gesi.onrender.com)**

- 📹 **Real-time video calling:** integrates in-app video communication directly into the platform, so users can move from text to face-to-face conversation without leaving the app.
- 💭 **One-on-one and group text chat:** supports both individual conversations and group chat rooms with a responsive, modern UI built for real-time message delivery.
- 🔐 **Authentication and contact management:** implements protected routes behind login, plus a friends/connections system so users can manage who they chat and call with.

`Node.js` `Express` `React` — deployed on Vercel/Render

---

### 📝 [ResumeForge AI](https://github.com/Ishan-1104/resumeforge-ai-1)
**[🔗 Live Demo](https://resumeforge-ai-five.vercel.app)**

- ⚡ **Fast LLM-powered content generation:** turns raw, unstructured project descriptions into polished, ATS-ready resume content using Groq's `llama-3.3-70b-versatile` model for low-latency inference.
- 📋 **Structured resume-building output:** generates bullet points, professional summaries, and skills lists tailored to the input, rather than a single block of generic text.
- 🎨 **Production-quality SaaS-style frontend:** built as a full Next.js 15 application with TypeScript and Tailwind CSS, giving it a polished, deployable interface rather than being just a bare script or CLI tool.

`Next.js 15` `TypeScript` `Tailwind CSS` `Groq API`

---

### 🎬 [CineAI](https://github.com/Ishan-1104/CineAI)
**[🔗 Live Demo](https://cineai-6ygv.onrender.com)**

- 🧩 **Client/server architecture:** separates the recommendation logic into a dedicated server layer from the JavaScript client, following a MERN-style split so the recommendation engine can evolve independently of the UI.
- 🎞️ **AI-powered movie recommendations:** analyzes input to surface relevant movie suggestions, rather than relying on a static, pre-defined list.
- ☁️ **Live cloud deployment:** hosted and accessible online rather than left as a local-only demo, so the recommendation flow can be tested end-to-end by anyone.

`JavaScript` (MERN-style client/server split)

---

### 🩺 [Multi-Disease Prediction System](https://github.com/Ishan-1104/multi-diseases)
**[🔗 Live Demo](https://multi-diseases-xahsafbhcqcsgfpvpkqgu2.streamlit.app/)**

- 📈 **Multi-condition prediction:** predicts the likelihood of diabetes, heart disease, and Parkinson's disease from patient input data using separately trained models for each condition.
- 🧪 **Trained scikit-learn models:** each disease model is trained on relevant patient datasets, serialized, and served through a dedicated Python prediction script for fast inference.
- 📦 **Interactive app, not just a notebook:** packaged as a full Streamlit application with an input interface for patient data, making the models actually usable rather than just a one-off analysis result.

`Python` `scikit-learn` `Pandas`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)


**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)


**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)


**AI / ML / GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)


**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ishan-1104&theme=radical&hide_border=true" alt="GitHub Streak" height="165"/>

</div>

---

## 📚 Currently Learning / Building

- **Learning:** LLM architectures, LangChain internals, RAG system design, vector databases, MLOps
- **Building:** production-grade AI applications (agentic pipelines, RAG assistants) and MERN full-stack products

---

## 🤝 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ishan-chhaparwal/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ishan-1104)

**If a project here caught your eye, a ⭐ means a lot — thanks for stopping by!**

</div>

---
