<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=2600&pause=900&color=7AA2F7&center=true&vCenter=true&width=760&lines=Hari+Kancharla;AI+Software+Engineer;Agents+%E2%80%A2+RAG+%E2%80%A2+Evals+%E2%80%A2+Infrastructure;Building+reliable+AI+systems+around+LLMs" alt="Hari Kancharla - AI Software Engineer" />

<p>
  <strong>AI Software Engineer building production-grade LLM systems, agentic workflows, RAG platforms, eval loops, and scalable AI infrastructure.</strong>
</p>

<p>
  <a href="https://harihkk.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=7AA2F7"></a>
  <a href="https://www.linkedin.com/in/hari-kancharla/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0F172A?style=for-the-badge&logo=linkedin&logoColor=7AA2F7"></a>
  <a href="https://github.com/harihkk/surf-agentic-browser"><img alt="Surf Agent" src="https://img.shields.io/badge/Surf_Agent-0F172A?style=for-the-badge&logo=github&logoColor=7AA2F7"></a>
</p>

</div>

---

## About

I build AI systems around LLMs, retrieval, agents, tools, and reliability. I care about the engineering around the model: clean APIs, measurable retrieval, eval loops, latency, observability, and recovery from real failure modes.

---

## Featured Builds

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/harihkk/surf-agentic-browser">Surf</a></h3>
      <p>Autonomous browser agent that turns natural-language goals into Playwright actions.</p>
      <p><strong>Hard parts:</strong> browser state, tool calls, bad actions, loops, provider fallback.</p>
      <p><code>FastAPI</code> <code>Playwright</code> <code>WebSockets</code> <code>Groq</code> <code>Gemini</code> <code>Ollama</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>AskRC</h3>
      <p>Production-style RAG platform for technical documentation and research workflows.</p>
      <p><strong>Hard parts:</strong> ingestion, retrieval quality, citation validation, answer checks.</p>
      <p><code>LangChain</code> <code>vector databases</code> <code>MLflow</code> <code>DVC</code> <code>Azure Search</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Prompt-Budd</h3>
      <p>Prompt optimization system with scoring, rewriting, PII detection, and MCP support.</p>
      <p><strong>Hard parts:</strong> real-time UX, safe rewriting, prompt quality feedback.</p>
      <p><code>Chrome Extension</code> <code>FastAPI</code> <code>MCP</code> <code>Gemini</code> <code>OpenAI</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>GenBI</h3>
      <p>Natural-language BI assistant that turns datasets into charts, tables, and answers.</p>
      <p><strong>Hard parts:</strong> routing analytical questions into reliable visual/data outputs.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>LangChain</code> <code>Plotly</code> <code>Pandas</code></p>
    </td>
  </tr>
</table>

---

## System Design Lens

```mermaid
flowchart LR
    A[User Goal] --> B[Planner]
    B --> C[Retrieve Context]
    B --> D[Call Tools]
    D --> E[Act or Execute]
    C --> F[Validate]
    E --> F
    F --> G[Final Output]
    F -- retry / repair --> B
```

---

## Current Focus

- Browser-agent reliability
- RAG answer validation and citation checks
- Eval traces for agent workflows
- Production-style AI case studies

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,java,kotlin,fastapi,spring,docker,kubernetes,aws,gcp,azure,postgres,redis,git,githubactions&theme=dark" alt="Python, TypeScript, Java, Kotlin, FastAPI, Spring, Docker, Kubernetes, AWS, GCP, Azure, Postgres, Redis, Git, GitHub Actions" />

</div>

---

## GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=harihkk&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="Hari's GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harihkk&layout=compact&theme=tokyonight&hide_border=true" alt="Hari's top languages" />

</div>

---

<div align="center">

<strong>Building AI systems that do more than demo well.</strong>
<br />
They retrieve context, call tools, handle failure, validate outputs, and ship.

</div>
