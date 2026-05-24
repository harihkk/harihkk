<div align="center">

# Hari Kancharla

**AI Software Engineer**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2600&pause=900&color=2563EB&center=true&vCenter=true&width=760&lines=Building+reliable+AI+systems+around+LLMs;Agentic+workflows+with+tools%2C+evals%2C+and+recovery;RAG+platforms+with+citations+and+validation;Production+AI+infrastructure%2C+not+just+demos" alt="Typing animation" />

Production-grade LLM systems, agentic workflows, RAG platforms, eval loops, and scalable AI infrastructure.

<p>
  <a href="https://harihkk.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/hari-kancharla/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/harihkk/surf-agentic-browser"><img alt="Surf Agent" src="https://img.shields.io/badge/Surf_Agent-2563EB?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://github.com/harihkk"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

</div>

---

## About

I build AI systems around LLMs, retrieval, agents, tools, and reliability. I care about the engineering around the model: clean APIs, measurable retrieval, eval loops, latency, observability, and recovery from real failure modes.

---

## Featured Builds

| Project | What it does | Hard parts | Stack |
|---|---|---|---|
| [**Surf**](https://github.com/harihkk/surf-agentic-browser) | Autonomous browser agent that turns natural-language goals into Playwright actions. | Browser state, tool calls, bad actions, loops, provider fallback. | `FastAPI` `Playwright` `WebSockets` `Groq` `Gemini` `Ollama` |
| **AskRC** | Production-style RAG platform for technical documentation and research workflows. | Ingestion, retrieval quality, citation validation, answer checks. | `LangChain` `vector databases` `MLflow` `DVC` `Azure Search` |
| **Prompt-Budd** | Prompt optimization system with scoring, rewriting, PII detection, and MCP support. | Real-time UX, safe rewriting, prompt quality feedback. | `Chrome Extension` `FastAPI` `MCP` `Gemini` `OpenAI` |
| **GenBI** | Natural-language BI assistant that turns datasets into charts, tables, and answers. | Routing analytical questions into reliable visual/data outputs. | `Python` `FastAPI` `LangChain` `Plotly` `Pandas` |

<div align="center">

<a href="https://github.com/harihkk/surf-agentic-browser">
  <img height="135" src="https://github-readme-stats.vercel.app/api/pin/?username=harihkk&repo=surf-agentic-browser&theme=transparent&hide_border=true&title_color=2563EB&text_color=64748B&icon_color=2563EB" alt="Surf Agent repository card" />
</a>

</div>

---

## System Design Lens

```mermaid
flowchart LR
    A[User Goal] --> B[Planner]
    B --> C[Retrieve Context]
    B --> D[Call Tools]
    C --> E[Validate]
    D --> F[Act or Execute]
    F --> E
    E --> G[Final Output]
    E -- retry / repair --> B
```

---

## Currently Building

| Focus | Why it matters |
|---|---|
| Browser-agent reliability | Better state tracking, action quality, loop prevention, and recovery. |
| RAG answer validation | Measurable retrieval, grounded citations, and answer checks. |
| Eval traces for agent workflows | Step-level scoring, failure analysis, and repair loops. |
| Production-style AI case studies | Clean architecture, observability, and systems that can ship. |

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,java,kotlin,fastapi,spring,docker,kubernetes,aws,gcp,azure,postgres,redis,git,githubactions&theme=dark" alt="Python, TypeScript, Java, Kotlin, FastAPI, Spring, Docker, Kubernetes, AWS, GCP, Azure, Postgres, Redis, Git, GitHub Actions" />

</div>

---

## GitHub Signal

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=harihkk&show_icons=true&hide_border=true&rank_icon=github&theme=transparent&title_color=2563EB&text_color=64748B&icon_color=2563EB" alt="Hari's GitHub stats" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harihkk&layout=compact&hide_border=true&theme=transparent&title_color=2563EB&text_color=64748B" alt="Hari's top languages" />

</div>

---

<div align="center">

**Building AI systems that do more than demo well.**
<br>
They retrieve context, call tools, handle failure, validate outputs, and ship.

</div>
