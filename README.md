<div align="center">

# Samarth Pratap Singh

### AI/ML Engineer building retrieval, agent, and document-intelligence systems

`VIT Bhopal '27` &nbsp;·&nbsp; `AI/ML Engineering Intern @ AmberFlux EdgeAI` &nbsp;·&nbsp; `India`

[Portfolio](https://portfolio-noviciusss.vercel.app/) ·
[LinkedIn](https://www.linkedin.com/in/spsamar/) ·
[Email](mailto:samarthsin2006@gmail.com) ·
[Hugging Face](https://huggingface.co/noviciusss)

<br/>

<a href="https://git.io/streak-stats">
  <img
    src="https://streak-stats.demolab.com?user=noviciusss&background=0B0D0C&hide_border=true&stroke=1D3325&ring=7FE08A&fire=FFB020&currStreakNum=EDEBE4&sideNums=EDEBE4&currStreakLabel=7FE08A&sideLabels=8F978F&dates=6E766F&border_radius=0"
    alt="GitHub contribution streak"
  />
</a>

</div>

<br/>

> I build the boring-but-hard parts of AI products: retrieval that is measured,
> agents that are observable, and memory that survives beyond one conversation.

```txt
NOW        AI/ML Engineering Intern @ AmberFlux EdgeAI
FOCUS      Production RAG · Multi-agent systems · LLM evaluation
SEEKING    2027 full-time AI Engineer · Applied AI · SDE + AI roles
EDUCATION  B.Tech CSE, VIT Bhopal · 2023—2027 · CGPA 8.61
```

<br/>

## `// start_here`

If you have two minutes:

```txt
01  DoCopilot    → production RAG, hybrid retrieval, evaluation, guardrails
02  Argus        → LangGraph orchestration, HITL review, LangSmith tracing
03  ContextCore  → FastMCP, persistent memory, agent tool execution
```

<br/>

## `// selected_systems`

<table>
<tr>
<td width="50%" valign="top">

### 01 / DoCopilot

**Multi-tenant RAG platform**

`FastAPI` `Qdrant` `PostgreSQL` `Next.js` `Azure`

Document Q&A with tenant-scoped hybrid retrieval: BM25, dense vectors,
RRF fusion, and cross-encoder reranking. Includes async PDF/TXT ingestion,
prompt-injection detection, PII redaction, and source-cited streaming.

```txt
89.2%  correctness
90.5%  relevance
2.86s  average latency
40     evaluated queries
```

[Explore repository →](https://github.com/noviciusss/DoCopilot)

</td>
<td width="50%" valign="top">

### 02 / Argus

**Multi-agent research engine**

`LangGraph` `FastAPI` `LangSmith` `Docker`

Supervisor-led research workflow coordinating planner, researcher, critic,
writer, and supervisor agents. Built for explicit routing, human review,
streamed execution, and traceable decisions.

```txt
5      specialist agents
3      research-depth tiers
30–90s report turnaround
HITL   review via LangGraph interrupts
```

[Explore repository →](https://github.com/noviciusss/Argus)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 03 / ContextCore

**Stateful memory agent**

`LangGraph` `FastMCP` `PostgreSQL` `Qdrant` `MongoDB`

A dual-memory architecture that separates conversation checkpointing,
semantic recall, and persistent user profiles. A FastMCP server exposes
task and note tools directly to the agent workflow.

```txt
17/17  evaluation tests passing
3      memory layers
MCP    callable tool server
```

[Explore repository →](https://github.com/noviciusss/ContextCore-CLI)

</td>
<td width="50%" valign="top">

### 04 / Dialogue Summarizer

**Parameter-efficient summarization**

`PyTorch` `Transformers` `PEFT / LoRA`

LoRA fine-tuning of FLAN-T5-base on SAMSum, updating only 2% of
the model parameters.

```txt
49.01  ROUGE-1
72.25  BERTScore F1
42.51  METEOR
2%     trainable parameters
```

[Try the demo →](https://huggingface.co/spaces/noviciusss/dialogue-summarizer)

</td>
</tr>
</table>

<br/>

## `// on_deck`

```txt
BUILDING       Agent Guard — static analysis for safer agent workflows
HARDENING      Evaluation harnesses for retrieval, tool calling, and routing
INTERESTED IN  AI systems that fail visibly, recover predictably, and improve from traces
```

### Agent Guard

`Python` `AST` `CLI` `GitHub Actions` · **in development**

A static-analysis tool for identifying common failure patterns in agent code:

```txt
→ unbounded retry loops
→ unsafe shared state in concurrent fan-out branches
→ LLM / HTTP calls without explicit timeouts
→ missing failure boundaries in agent workflows
```

<br/>

## `// toolkit`

```txt
agents       LangGraph · LangChain · MCP / FastMCP · Tool Calling
retrieval    Qdrant · FAISS · BM25 · Hybrid Search · RRF · Reranking
backend      Python · FastAPI · PostgreSQL · Redis · Celery
delivery     Docker · Azure Container Apps · GitHub Actions · Linux
evaluation   LangSmith · Ragas · LLM-as-Judge · ROUGE · BERTScore
ml           PyTorch · Transformers · PEFT / LoRA · scikit-learn
languages    Python · C++ · TypeScript · SQL
```

<br/>

<div align="center">

```txt
offline: DSA · gaming · sci-fi / thrillers · manhwa · EDM / lo-fi / metal
```

**Building systems with evidence, not buzzwords.**

</div>
