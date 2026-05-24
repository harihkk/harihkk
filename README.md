<div align="center">

<h1>Hari Kancharla</h1>

<h3>AI Software Engineer building systems where AI actually does the work.</h3>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=900&color=2563EB&center=true&vCenter=true&width=820&lines=Production-grade+LLM+systems;Agentic+workflows+with+tools%2C+evals%2C+and+recovery;RAG+platforms+with+citations+and+validation;Scalable+AI+infrastructure%2C+not+just+demos" alt="Typing animation" />

<p>
  <a href="https://harihkk.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/hari-kancharla/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/harihkk/surf-agentic-browser"><img alt="Surf Agent" src="https://img.shields.io/badge/Surf_Agent-2563EB?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://github.com/harihkk"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

<p>
  <code>Agents</code> · <code>RAG</code> · <code>Evals</code> · <code>Tool Calling</code> · <code>FastAPI</code> · <code>Kubernetes</code>
</p>

</div>

---

## Snapshot

I build AI systems around LLMs, retrieval, agents, tools, and reliability. I care about the engineering around the model: clean APIs, measurable retrieval, eval loops, latency, observability, and recovery from real failure modes.

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Agentic systems</strong><br>
      Tool use, browser automation, stateful planning, fallbacks, and repair loops.
    </td>
    <td width="33%" valign="top">
      <strong>RAG platforms</strong><br>
      Ingestion, retrieval quality, citation checks, validation, and traceable answers.
    </td>
    <td width="33%" valign="top">
      <strong>AI infrastructure</strong><br>
      APIs, observability, serving performance, deployment, and production reliability.
    </td>
  </tr>
</table>

---

## Selected Systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/harihkk/surf-agentic-browser">Surf</a></h3>
      Autonomous browser agent that turns natural-language goals into Playwright actions.<br><br>
      <strong>Hard parts:</strong> browser state, tool calls, bad actions, loops, provider fallback.<br><br>
      <code>FastAPI</code> <code>Playwright</code> <code>WebSockets</code> <code>Groq</code> <code>Gemini</code> <code>Ollama</code>
    </td>
    <td width="50%" valign="top">
      <h3>AskRC</h3>
      Production-style RAG platform for technical documentation and research workflows.<br><br>
      <strong>Hard parts:</strong> ingestion, retrieval quality, citation validation, answer checks.<br><br>
      <code>LangChain</code> <code>vector databases</code> <code>MLflow</code> <code>DVC</code> <code>Azure Search</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Prompt-Budd</h3>
      Prompt optimization system with scoring, rewriting, PII detection, and MCP support.<br><br>
      <strong>Hard parts:</strong> real-time UX, safe rewriting, prompt quality feedback.<br><br>
      <code>Chrome Extension</code> <code>FastAPI</code> <code>MCP</code> <code>Gemini</code> <code>OpenAI</code>
    </td>
    <td width="50%" valign="top">
      <h3>GenBI</h3>
      Natural-language BI assistant that turns datasets into charts, tables, and answers.<br><br>
      <strong>Hard parts:</strong> routing analytical questions into reliable visual/data outputs.<br><br>
      <code>Python</code> <code>FastAPI</code> <code>LangChain</code> <code>Plotly</code> <code>Pandas</code>
    </td>
  </tr>
</table>

---

## System Design Lens

```mermaid
flowchart LR
    A["User goal"] --> B["Plan"]
    B --> C["Retrieve context"]
    B --> D["Call tools"]
    C --> E["Validate"]
    D --> F["Act / execute"]
    F --> E
    E --> G["Final output"]
    E -- "retry / repair" --> B
```

---

## Current Focus

| Area | What I am tuning |
|---|---|
| Browser-agent reliability | Better action selection, state handling, loop prevention, and provider fallback. |
| RAG validation | Retrieval measurement, grounded citations, answer checks, and failure analysis. |
| Agent eval traces | Step-level scoring for tool calls, recoveries, and final-answer quality. |
| Production AI case studies | Systems that are readable, deployable, observable, and honest about tradeoffs. |

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,java,kotlin,fastapi,spring,docker,kubernetes,aws,gcp,azure,postgres,redis,git,githubactions&theme=dark" alt="Python, TypeScript, Java, Kotlin, FastAPI, Spring, Docker, Kubernetes, AWS, GCP, Azure, Postgres, Redis, Git, GitHub Actions" />

</div>

---

## GitHub Signal

<div align="center">

<a href="https://github.com/harihkk/surf-agentic-browser">
  <img height="135" src="https://github-readme-stats.vercel.app/api/pin/?username=harihkk&repo=surf-agentic-browser&theme=transparent&hide_border=true&title_color=2563EB&text_color=64748B&icon_color=2563EB" alt="Surf Agent repository card" />
</a>

<br>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=harihkk&show_icons=true&hide_border=true&rank_icon=github&theme=transparent&title_color=2563EB&text_color=64748B&icon_color=2563EB" alt="Hari's GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harihkk&layout=compact&hide_border=true&theme=transparent&title_color=2563EB&text_color=64748B" alt="Hari's top languages" />

</div>

---

<div align="center">

<strong>Building AI systems that do more than demo well.</strong>
<br>
They retrieve context, call tools, handle failure, validate outputs, and ship.

</div>
