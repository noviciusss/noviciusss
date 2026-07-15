<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2200&pause=700&color=7FE08A&center=true&vCenter=true&width=780&lines=%3E+loading+samarth_pratap_singh.env...;%3E+role%3A+AI%2FML+Engineer+%7C+LangGraph+%C2%B7+RAG+%C2%B7+Agents;%3E+status%3A+open_to_offers+%E2%80%94+2027+batch;%3E+ready." alt="terminal typing" />

<br/>

![static](https://img.shields.io/badge/build-passing-7FE08A?style=flat-square&labelColor=0D1117)
![static](https://img.shields.io/badge/latency-90s_(from_7min)-FFB020?style=flat-square&labelColor=0D1117)
![static](https://img.shields.io/badge/uptime-open_to_work-7FE08A?style=flat-square&labelColor=0D1117)

</div>

<br/>

## `$ whoami`

```
Samarth Pratap Singh — B.Tech CSE, VIT Bhopal ('23–'27) · CGPA 8.57
AI/ML Engineer Intern @ AmberFlux EdgeAI

I build the boring-but-hard parts of AI products: agent orchestration
that doesn't fall over, retrieval that's actually measured, and memory
that persists across sessions. Every project below ships with numbers,
not adjectives.
```

<br/>

## `$ neofetch`

```text
        ▗▄▄▄▖               samarth@vit-bhopal
       ▐▓▓▓▓▓▌              ─────────────────────────────
      ▐▓▓▓▓▓▓▓▌             OS ............ VIT Bhopal, CSE '27
   ▄▄▄▝▜▓▓▓▓▓▛▘▄▄▄          Host ........... AmberFlux EdgeAI (intern)
  █▓▓▓▓▄ ▝▀▀▀▘ ▄▓▓▓▓█       Kernel ......... LangGraph + FastAPI
  █▓▓▓▓▓▓▄▄▄▄▄▓▓▓▓▓▓█       Shell .......... python3 --strict
   ▀▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▀        Uptime ......... 240+ DSA · 4 shipped pipelines
     ▀▀▜▓▓▓▓▓▓▓▛▀▀          CPU ............ caffeine (98% util)
        ▝▀▀▀▀▀▘             Memory ......... Postgres · Qdrant · MongoDB
                            Theme .......... Signal Block [neubrutalist]
                            Status ......... seeking full-time, Aug 2026
```

<br/>

## `$ cat capabilities.json`

```json
{
  "orchestration": ["LangGraph", "multi-agent supervisors", "conditional routing"],
  "retrieval": ["hybrid search (BM25 + dense)", "RRF fusion", "cross-encoder rerank"],
  "memory_protocol": ["MCP / FastMCP", "Postgres checkpointing", "Qdrant semantic recall"],
  "serving": ["FastAPI", "Next.js", "Docker"],
  "eval": ["LLM-as-Judge", "Ragas", "ROUGE / BERTScore / METEOR"],
  "core_ml": ["PyTorch", "Transformers", "PEFT / LoRA"],
  "observability": ["LangSmith", "MLflow", "W&B"],
  "languages": ["Python", "C++", "TypeScript", "SQL"]
}
```

<br/>

## `$ ls pipelines/ --status`

**01. `doc_copilot/`** ![](https://img.shields.io/badge/-deployed-7FE08A?style=flat-square&labelColor=0D1117)
RAG document Q&A — hybrid retrieval (BM25 + dense) with RRF fusion and cross-encoder rerank.
```
correctness   89.2%   (+31 pts over keyword-matching baseline)
guardrails    prompt-injection detection · PII redaction
stack         Qdrant · Groq Llama-4-Scout · Next.js · FastAPI
```
[→ github.com/noviciusss/DoCopilot](https://github.com/noviciusss/DoCopilot)

---

**02. `argus/`** ![](https://img.shields.io/badge/-deployed-7FE08A?style=flat-square&labelColor=0D1117)
Multi-agent research engine — supervisor routes planner → researcher → critic → writer.
```
turnaround    30–90s   (was: hours, done manually)
control       critic agent auto-rejects weak drafts and re-routes
tracing       fully traced in LangSmith, async submit → poll → fetch
```
[→ github.com/noviciusss/Argus](https://github.com/noviciusss/Argus)

---

**03. `contextcore/`** ![](https://img.shields.io/badge/-deployed-7FE08A?style=flat-square&labelColor=0D1117)
Stateful memory agent with a custom FastMCP server exposing tools over MCP.
```
memory        Postgres checkpointing + Qdrant recall + MongoDB profiles
router        intent-based, conditional LangGraph edges — no mode-switch
tests         17/17 passing
```
[→ github.com/noviciusss/ContextCore-CLI](https://github.com/noviciusss/ContextCore-CLI)

---

**04. `dialogue_summarizer/`** ![](https://img.shields.io/badge/-deployed-7FE08A?style=flat-square&labelColor=0D1117)
LoRA fine-tune of FLAN-T5-base on SAMSum — 2% of parameters updated.
```
rouge-1       49.01     bertscore_f1   72.25     meteor   42.51
result        matches full fine-tuning at a fraction of the compute
```
[→ huggingface.co/spaces/noviciusss/dialogue-summarizer](https://huggingface.co/spaces/noviciusss/dialogue-summarizer)

---

**05. `agent_guard/`** ![](https://img.shields.io/badge/-in__dev-FFB020?style=flat-square&labelColor=0D1117)
AST-based static analysis for agent code — catches unbounded retry loops, unsafe shared state in fan-out branches, and timeout-less LLM/HTTP calls. CLI + GitHub Action. No ship date, no pressure.

<br/>

## `$ cat model_card.yaml`

```yaml
model_name: samarth-pratap-singh
version: v4.2027-final-year
architecture: human · caffeinated · stubborn about eval numbers
parameters: underestimated (probably)
training_data:
  - 240+ leetcode problems (DP · graphs · trees — still hardening)
  - 4 shipped agent/RAG pipelines with real benchmarks
  - 1 internship, 2 codebases, 0 patience for vague specs
known_limitations:
  - will not ship a metric it hasn't personally verified
  - allergic to "production-grade" claims without a database to back it
intended_use: SDE / AI-ML full-time roles, 2027 batch
license: open-to-work
```

<br/>

## `$ curl /telemetry`

<div align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=noviciusss&theme=react&hide_border=true&background=0D1117&stroke=7FE08A&ring=7FE08A&fire=FFB020&currStreakLabel=7FE08A" height="165" />
</div>

<br/>

## `$ connect --to=samarth`

<div align="center">

[![Email](https://img.shields.io/badge/email-samarthsin2006%40gmail.com-0D1117?style=flat-square&logo=gmail&logoColor=7FE08A)](mailto:samarthsin2006@gmail.com)
[![Portfolio](https://img.shields.io/badge/portfolio-live-0D1117?style=flat-square&logo=vercel&logoColor=7FE08A)](https://portfolio-noviciusss.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/linkedin-spsamar-0D1117?style=flat-square&logo=linkedin&logoColor=7FE08A)](https://www.linkedin.com/in/spsamar/)
[![HuggingFace](https://img.shields.io/badge/huggingface-noviciusss-0D1117?style=flat-square&logo=huggingface&logoColor=FFB020)](https://huggingface.co/noviciusss)

</div>

<br/>

<div align="center">

```
$ off_duty --list
gaming · edm / lo-fi / metal · manhwa · sci-fi & thrillers
```

<sub>process exited 0 · thanks for reading the logs</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:14532d,100:0D1117&height=100&section=footer" width="100%"/>

</div>

<!--
SETUP NOTES:
1. Streak stats: self-hosted fork on Vercel if the public instance rate-limits.
2. Update pipelines/ + model_card.yaml whenever eval numbers change.
-->
