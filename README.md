<!-- ===========================
   Samarth Pratap Singh — README
   =========================== -->

<div align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&pause=900&color=BD93F9&center=true&vCenter=true&width=860&lines=Hi%2C+I'm+Samarth+Pratap+Singh;AI%2FML+Engineer+%7C+LangGraph+%C2%B7+RAG+%C2%B7+Agents;Multi-Agent+Systems+%7C+RAG+Pipelines+%7C+LLMOps;LangGraph+%7C+FastAPI+%7C+Qdrant+%7C+MCP;Open+to+SDE+%2F+AI+%2F+ML+Roles+(2027)"
      alt="Typing SVG"
    />
  </a>

  <p>
    <em>Building production-grade AI systems: retrieval, agents, evals — shipped with clean APIs and real metrics.</em>
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
    <a href="https://huggingface.co/noviciusss" target="_blank">
      <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
    </a>
  </p>

  <p>
    <img src="https://komarev.com/ghpvc/?username=noviciusss&style=for-the-badge&color=blueviolet" alt="Profile Views" />
  </p>
</div>

<br/>

## ⚡ TL;DR

- 🎓 B.Tech CSE @ VIT Bhopal (2023–2027) · CGPA **8.57**
- 🛠️ **AI/ML Engineer Intern @ AmberFlux EdgeAI** — building document intelligence pipelines using vision LLMs on real architectural drawings (up to 400 pages), cutting extraction latency from ~7 min to ~90 sec
- 🤖 Core focus: **multi-agent orchestration** (LangGraph), **RAG with hybrid retrieval + evals**, **stateful memory agents** (MCP protocol)
- 📊 I ship with numbers attached — correctness, recall, latency, and named baselines — not just "built a model"

<br/>

## 🧭 Current Stack

<div align="center">
  <img src="https://img.shields.io/badge/LangGraph-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-0B6E4F?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/LangSmith-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
</div>

<br/>

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/noviciusss/DoCopilot">🔍 DoCopilot</a></h3>
      <p><em>RAG Document Q&A — Next.js · FastAPI · Qdrant Hybrid Search</em></p>
      <ul>
        <li>Hybrid retrieval (BM25 + dense) with RRF fusion + cross-encoder reranking</li>
        <li><b>89.2%</b> avg correctness — a <b>31-point</b> lift over a keyword-matching baseline (57.7%)</li>
        <li>Full 40-query LLM-as-Judge ablation study across chunking + retrieval strategies</li>
        <li>Guardrails: prompt-injection detection, PII redaction, source-grounding checks</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/noviciusss/Argus">🧠 Argus</a></h3>
      <p><em>Multi-Agent Research Engine — LangGraph · FastAPI · Docker</em></p>
      <ul>
        <li>Supervisor-based pipeline with 5 specialist agents (planner, researcher, critic, writer, supervisor)</li>
        <li>LLM-driven <code>Command(goto)</code> routing — manual research time cut from hours to <b>30–90 sec</b></li>
        <li>Critic agent rejects low-quality drafts and re-routes autonomously before writing</li>
        <li>Async submit → poll → fetch job flow, fully traced in LangSmith</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/noviciusss/ContextCore-CLI">🗂️ ContextCore</a></h3>
      <p><em>Stateful Memory Agent — LangGraph · PostgreSQL · Qdrant · MongoDB · MCP</em></p>
      <ul>
        <li>Custom <b>FastMCP server</b> exposing task/note management as callable tools</li>
        <li>Dual-memory architecture: PostgreSQL checkpointing, Qdrant semantic recall, MongoDB profiles</li>
        <li>Intent router with conditional LangGraph edges — no manual mode-switching</li>
        <li>LLM-as-Judge eval harness tracking memory recall accuracy + hallucination rate</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://huggingface.co/spaces/noviciusss/dialogue-summarizer">✂️ FLAN-T5 Dialogue Summarizer</a></h3>
      <p><em>PEFT / LoRA Fine-Tuning — Transformers · Gradio</em></p>
      <ul>
        <li>LoRA fine-tuned FLAN-T5-base on SAMSum (14.7K dialogues), updating only <b>2%</b> of parameters</li>
        <li><b>49.01</b> ROUGE-1 · <b>72.25</b> BERTScore F1 · <b>42.51</b> METEOR — matching full fine-tuning at a fraction of the compute cost</li>
        <li>Reproducible eval suite (ROUGE, BERTScore, METEOR, BLEU) + full model card on Hugging Face</li>
        <li>Deployed as an interactive Gradio app with configurable beam search</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

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
  <summary><strong>ML / DL</strong></summary>
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
  <summary><strong>LLM / Agents / Retrieval</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/LangGraph-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
    <img src="https://img.shields.io/badge/LangChain-0B6E4F?style=for-the-badge&logo=langchain&logoColor=white" />
    <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" />
    <img src="https://img.shields.io/badge/FAISS-009688?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  </div>
</details>

<details>
  <summary><strong>Evaluation</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/LLM--as--Judge-8A2BE2?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/ROUGE%20%2F%20BERTScore-4B8BBE?style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/Ragas-FF4B4B?style=for-the-badge&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>MLOps / Observability</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/LangSmith-1A1A1A?style=for-the-badge&logo=langchain&logoColor=white" />
    <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
    <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black" />
    <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>Backend / Full-Stack / DevTools</strong></summary>
  <br/>
  <div align="center">
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
    <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  </div>
</details>

<br/>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=noviciusss&theme=dracula&hide_border=true&border_radius=10" height="175" />
</p>

<br/>


## 🎮 Off-screen

Gaming · EDM / lo-fi / metal · Manhwa & webtoons · Sci-fi & thrillers

<br/>

<div align="center">
  <sub>Built with curiosity, caffeine, and commits.</sub>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</div>

<!--
SETUP NOTES:
1. Snake: add Platane/snk GitHub Action → outputs to /output/github-contribution-grid-snake.svg
2. Stats/streak: self-host on Vercel if public endpoints get rate-limited
3. Update "Featured Projects" table whenever ContextCore eval numbers are finalized
-->
