<!-- ===========================
   Samarth Pratap Singh — README
   =========================== -->

<div align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&pause=900&color=BD93F9&center=true&vCenter=true&width=900&lines=Hi%2C+I'm+Samarth+Pratap+Singh;AI+%2F+ML+Engineer+%2B+Full-Stack+Developer;Multi-Agent+Systems+%7C+RAG+%7C+LLMOps;LangGraph+%7C+FastAPI+%7C+Next.js+%7C+Docker;Open+to+Internships+(AI+%2F+ML+%2F+SDE)"
      alt="Typing SVG"
    />
  </a>

  <p>
    <em>Building production-grade AI systems: multi-agent pipelines, hybrid RAG, and evals — deployed end-to-end.</em>
  </p>

  <p>
    <a href="mailto:samarthsin2006@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://portfolio-noviciusss.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-8A2BE2?style=for-the-badge&logo=about.me&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/spsamar/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/noviciusss">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://huggingface.co/" target="_blank">
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
    </a>
  </p>

  <p>
    <a href="https://github.com/noviciusss/github-profile-views-counter">
      <img src="https://komarev.com/ghpvc/?username=noviciusss&style=for-the-badge&color=blueviolet" alt="Profile Views" />
    </a>
  </p>
</div>

---

## ⚡ TL;DR

- 🎓 **B.Tech CSE** @ VIT Bhopal (2023–2027) · CGPA **8.45**
- 🤖 **AI/ML** — Multi-agent systems (LangGraph), RAG pipelines, fine-tuning (LoRA/PEFT), evals
- 🧩 **Full-Stack** — Next.js + FastAPI + PostgreSQL + Docker, deployed on Render/AWS
- 📌 **Open to** AI / ML / SDE internships (placements Aug 2026)

---

## 🚀 Featured Projects

### 🔬 Argus — Autonomous Research Engine
> `LangGraph` `FastAPI` `Groq` `Docker` `LangSmith` · **Feb 2026**

- Production-grade **multi-agent pipeline** using LangGraph supervisor pattern with 5 specialist agents (planner, researcher, critic, writer, supervisor) orchestrated via LLM-driven `Command(goto)` routing
- Async job architecture (`submit → poll → fetch`) with SQLite persistence + LangGraph checkpointing — jobs survive agent failures; every LLM call traced end-to-end in **LangSmith**
- Containerized with Docker, deployed on Render; integrated **Tavily**, ArXiv & Wikipedia to synthesize cited Markdown reports in **30–90 seconds**

---

### 📄 DoCopilot — RAG Document Q&A
> `Next.js` `FastAPI` `Qdrant (Hybrid)` `Reranking` `Groq` · **Dec 2025**

- Full-stack RAG app: upload PDFs/TXT → index via **Qdrant hybrid search** (BM25 + dense vectors) → answer with source citations
- Retrieval pipeline: RRF fusion + **cross-encoder reranking** → top-k context selection to suppress noise before generation
- Guardrails (prompt-injection detection, PII redaction, source-grounding) + **LLM-as-Judge** evaluation on 40 queries: **89.2% correctness · 90.5% relevance · 100% source rate · 2.86s avg latency**

---

### 🗣️ FLAN-T5 Dialogue Summarizer
> `PEFT` `LoRA` `Transformers` `Gradio` · **Oct 2025**

- Fine-tuned **FLAN-T5-base** with LoRA (r=16, α=32) on SAMSum (14.7K dialogues) — updated only **2% of parameters** via FP16 mixed precision
- Achieved **ROUGE-1: 49.01 · BERTScore F1: 72.25 · METEOR: 42.51**
- Deployed interactive **Gradio app** on HuggingFace Spaces with beam search decoding + published reproducible evaluation suite (ROUGE, BERTScore, METEOR, BLEU)

---

### 🏦 RoBERTa — Banking Intent Classifier (Banking77)
> `PyTorch` `Transformers` `CUDA` · **Sep 2025**

- Fine-tuned **RoBERTa-base** on Banking77 (77 intents, 13K queries) → **93.7% accuracy · 93.6% macro-F1**
- AdamW + weight decay (LR 2e-5, batch 16/32, 5 epochs), FP16 on GPU — best-checkpoint selection via per-epoch tracking
- Experiment hygiene: fixed seeds, consistent tokenization/padding, minimal inference loading script for reproducibility

---

## 🧭 Current Focus

<div align="center">
  <img src="https://img.shields.io/badge/LangGraph-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-0B6E4F?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-FF4B5C?style=for-the-badge&logo=qdrant&logoColor=white" />
</div>

**What I'm building:**
- Agentic systems: tool-use, memory, routing, multi-step workflows (LangGraph supervisor & subgraph patterns)
- RAG internals: chunking strategies, hybrid retrieval, reranking, hallucination guardrails
- Production habits: async FastAPI services, eval loops (LLM-as-Judge), AWS-friendly deployment

---

## 🧰 Tech Stack

<details>
  <summary><strong>Languages</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>AI / ML</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
    <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
    <img src="https://img.shields.io/badge/PEFT%2FLoRA-8A2BE2?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>LLMs / Agents / RAG</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/LangGraph-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
    <img src="https://img.shields.io/badge/LangChain-0B6E4F?style=for-the-badge&logo=langchain&logoColor=white" />
    <img src="https://img.shields.io/badge/Qdrant-FF4B5C?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/FAISS-0096FF?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/LangSmith-7B2FF7?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/Groq-00B4D8?style=for-the-badge&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>MLOps / Observability</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/LangSmith-7B2FF7?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
    <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>Frontend / Backend</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>Cloud / DevTools</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
    <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  </div>
</details>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=noviciusss&theme=dracula&hide_border=true&border_radius=10" height="175" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=noviciusss&layout=compact&theme=dracula&hide_border=true&v=2" height="160" />
</p>

---

## 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
</picture>

---

## 🎯 Fun Zone

<div align="center">
  <img src="https://readme-jokes.vercel.app/api?theme=dracula" alt="Random Dev Joke" />
</div>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dracula" alt="Quote" />
</div>

---

## 🎮 Off-screen side quests
- 🎮 Gaming (PC / mobile)
- 🎵 Music (EDM · lo-fi · metal)
- 📖 Manhwa / webtoons
- 🚀 Sci-fi & thrillers

---

<div align="center">
  <sub>Built with curiosity, caffeine, and commits.</sub>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:BD93F9,100:7B2FF7&height=100&section=footer"/>
</div>

<!--
SETUP NOTES:
1. Snake animation: Add GitHub Action using https://github.com/Platane/snk
   - Generates /output/github-contribution-grid-snake.svg automatically on push/schedule
2. Stats widgets: If rate-limited, self-host github-readme-stats on your own Vercel
3. Add LeetCode badge: https://leetcode-badge-showcase.vercel.app/
-->
