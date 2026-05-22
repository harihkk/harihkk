<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=245&color=0:0B1020,45:172554,100:7AA2F7&text=Hari%20Kancharla&fontColor=E6EDF3&fontSize=54&fontAlignY=38&animation=fadeIn&desc=AI%20Software%20Engineer%20%E2%80%A2%20Agents%20%E2%80%A2%20RAG%20%E2%80%A2%20Evals%20%E2%80%A2%20Infrastructure&descSize=17&descAlignY=58" alt="Hari Kancharla - AI Software Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=900&color=7AA2F7&center=true&vCenter=true&width=820&lines=Building+production-grade+LLM+systems;Designing+agentic+workflows+that+recover+from+failure;Shipping+RAG+platforms%2C+eval+loops%2C+and+AI+infrastructure" alt="Typing SVG" />

<p>
  <strong>AI Software Engineer building reliable systems around LLMs, retrieval, agents, tools, evaluation, and scalable infrastructure.</strong>
</p>

<p>
  <a href="https://harihkk.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=7AA2F7&labelColor=0B1020"></a>
  <a href="https://www.linkedin.com/in/hari-kancharla/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-111827?style=for-the-badge&logo=linkedin&logoColor=7AA2F7&labelColor=0B1020"></a>
  <a href="https://github.com/harihkk/surf-agentic-browser"><img alt="Surf Agent" src="https://img.shields.io/badge/Surf_Agent-111827?style=for-the-badge&logo=github&logoColor=7AA2F7&labelColor=0B1020"></a>
</p>

<p>
  <img alt="LLM Systems" src="https://img.shields.io/badge/LLM%20Systems-172554?style=flat-square&labelColor=0B1020&color=1E3A8A">
  <img alt="Agentic Workflows" src="https://img.shields.io/badge/Agentic%20Workflows-172554?style=flat-square&labelColor=0B1020&color=1E40AF">
  <img alt="RAG Platforms" src="https://img.shields.io/badge/RAG%20Platforms-172554?style=flat-square&labelColor=0B1020&color=2563EB">
  <img alt="Eval Loops" src="https://img.shields.io/badge/Eval%20Loops-172554?style=flat-square&labelColor=0B1020&color=3B82F6">
  <img alt="AI Infrastructure" src="https://img.shields.io/badge/AI%20Infrastructure-172554?style=flat-square&labelColor=0B1020&color=60A5FA">
</p>

</div>

---

## What I Build

I build AI systems around LLMs, retrieval, agents, tools, and reliability. I care about the engineering around the model: clean APIs, measurable retrieval, eval loops, latency, observability, and recovery from real failure modes.

<table>
  <tr>
    <td width="25%" align="center"><strong>Plan</strong><br><sub>decompose goals into reliable steps</sub></td>
    <td width="25%" align="center"><strong>Retrieve</strong><br><sub>measure context quality and citations</sub></td>
    <td width="25%" align="center"><strong>Act</strong><br><sub>call tools with state and guardrails</sub></td>
    <td width="25%" align="center"><strong>Validate</strong><br><sub>score outputs, trace failures, repair</sub></td>
  </tr>
</table>

---

## Featured Builds

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/harihkk/surf-agentic-browser">Surf</a></h3>
      <p><strong>Autonomous browser agent</strong> that turns natural-language goals into Playwright actions.</p>
      <p><strong>Hard parts:</strong> browser state, tool calls, bad actions, loops, provider fallback.</p>
      <p><code>FastAPI</code> <code>Playwright</code> <code>WebSockets</code> <code>Groq</code> <code>Gemini</code> <code>Ollama</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>AskRC</h3>
      <p><strong>Production-style RAG platform</strong> for technical documentation and research workflows.</p>
      <p><strong>Hard parts:</strong> ingestion, retrieval quality, citation validation, answer checks.</p>
      <p><code>LangChain</code> <code>vector databases</code> <code>MLflow</code> <code>DVC</code> <code>Azure Search</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Prompt-Budd</h3>
      <p><strong>Prompt optimization system</strong> with scoring, rewriting, PII detection, and MCP support.</p>
      <p><strong>Hard parts:</strong> real-time UX, safe rewriting, prompt quality feedback.</p>
      <p><code>Chrome Extension</code> <code>FastAPI</code> <code>MCP</code> <code>Gemini</code> <code>OpenAI</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>GenBI</h3>
      <p><strong>Natural-language BI assistant</strong> that turns datasets into charts, tables, and answers.</p>
      <p><strong>Hard parts:</strong> routing analytical questions into reliable visual/data outputs.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>LangChain</code> <code>Plotly</code> <code>Pandas</code></p>
    </td>
  </tr>
</table>

<div align="center">

<a href="https://github.com/harihkk/surf-agentic-browser">
  <img height="145" src="https://github-readme-stats.vercel.app/api/pin/?username=harihkk&repo=surf-agentic-browser&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=7AA2F7&text_color=C9D1D9&icon_color=7AA2F7" alt="Surf agentic browser repository" />
</a>

</div>

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

<table>
  <tr>
    <td width="50%"><strong>Browser-agent reliability</strong><br><sub>state, action quality, loops, tool recovery</sub></td>
    <td width="50%"><strong>RAG answer validation</strong><br><sub>retrieval measurement, citations, answer checks</sub></td>
  </tr>
  <tr>
    <td width="50%"><strong>Eval traces for agents</strong><br><sub>step-level scoring, failure analysis, repair loops</sub></td>
    <td width="50%"><strong>Production-style case studies</strong><br><sub>clean architecture, observability, deployable systems</sub></td>
  </tr>
</table>

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,java,kotlin,fastapi,spring,docker,kubernetes,aws,gcp,azure,postgres,redis,git,githubactions&theme=dark" alt="Python, TypeScript, Java, Kotlin, FastAPI, Spring, Docker, Kubernetes, AWS, GCP, Azure, Postgres, Redis, Git, GitHub Actions" />

<br><br>

<img alt="Python" src="https://img.shields.io/badge/Python-0B1020?style=flat-square&logo=python&logoColor=7AA2F7">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-0B1020?style=flat-square&logo=typescript&logoColor=7AA2F7">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0B1020?style=flat-square&logo=fastapi&logoColor=7AA2F7">
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-0B1020?style=flat-square&logo=chainlink&logoColor=7AA2F7">
<img alt="Docker" src="https://img.shields.io/badge/Docker-0B1020?style=flat-square&logo=docker&logoColor=7AA2F7">
<img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-0B1020?style=flat-square&logo=kubernetes&logoColor=7AA2F7">

</div>

---

## GitHub Signal

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=harihkk&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&bg_color=0B1020&title_color=7AA2F7&text_color=C9D1D9&icon_color=7AA2F7" alt="Hari's GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harihkk&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=7AA2F7&text_color=C9D1D9" alt="Hari's top languages" />

<br>

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=harihkk&theme=tokyo-night&hide_border=true&bg_color=0B1020&color=7AA2F7&line=7AA2F7&point=C9D1D9&area=true&area_color=1E3A8A&custom_title=Contribution%20Graph" alt="Hari's GitHub contribution graph" />

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3200&pause=1000&color=C9D1D9&center=true&vCenter=true&width=760&lines=Building+AI+systems+that+do+more+than+demo+well.;They+retrieve+context%2C+call+tools%2C+handle+failure%2C+validate+outputs%2C+and+ship." alt="Closing statement" />

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=115&section=footer&color=0:7AA2F7,55:172554,100:0B1020" alt="Footer wave" />

</div>
