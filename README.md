# Hari Krishna Kancharla

**AI Software Engineer building production LLM, RAG, and agentic systems**

Boston, MA · AI Software Engineer at Morgan Stanley

[Portfolio](https://harihkk.github.io) · [LinkedIn](https://www.linkedin.com/in/hari-kancharla/) · [Resume](https://harihkk.github.io/resume.pdf) · [Surf Agent](https://github.com/harihkk/surf-agentic-browser)

---

I design and ship production AI systems end to end: retrieval pipelines, agentic workflows, inference services, platform APIs, and reliability layers around LLMs. At Morgan Stanley, I work on low-latency AI platforms with full-stack ownership across frontend, backend, infrastructure, observability, CI/CD, and on-call operations.

## CURRENT_STATE

- Building production AI platforms for RAG, agentic workflows, tool use, and LLM serving.
- Specializing in LangGraph/MCP agents, retrieval quality, eval loops, and inference optimization.
- Optimizing for reliability: p95 latency, SLOs, traceability, graceful failure, and systems that survive real usage.

## FEATURED_SYSTEMS

### [Surf](https://github.com/harihkk/surf-agentic-browser)

Autonomous browser agent that turns natural-language goals into Playwright actions.

Why it matters: it treats browser automation as a stateful agent runtime, with loop detection, structured tool calls, session recording, and a Groq → Gemini → Ollama fallback cascade so provider limits do not stall execution.

`FastAPI` `Playwright` `WebSockets` `Groq` `Gemini` `Ollama`

### [AskRC](https://github.com/harihkk/AskRC)

Production-style RAG and MLOps pipeline for research computing documentation.

Why it matters: it connects ingestion, preprocessing, Azure Search indexing, DVC versioning, MLflow tracking, testing, and validation into one traceable retrieval workflow instead of a one-off chatbot.

`Python` `Azure Search` `Airflow` `DVC` `MLflow` `Docker`

### [Prompt-Budd](https://github.com/harihkk/Prompt-Budd)

LLM prompt tooling system with scoring, rewriting, PII detection, and MCP support.

Why it matters: it moves prompt quality checks closer to the user workflow, combining browser-extension UX with backend model routing, safe rewriting, and real-time feedback.

`Chrome Extension` `FastAPI` `Gemini` `OpenAI` `Groq` `MCP`

### [GenBI](https://github.com/harihkk/GenBI)

Natural-language BI assistant that turns datasets into charts, tables, and answers.

Why it matters: it routes analytical intent into reliable outputs by separating classification, data manipulation, visualization, table generation, and response synthesis.

`FastAPI` `LangChain` `GPT-4o` `Plotly` `Pandas` `Firebase`

## DEPLOYMENT_HISTORY

| Signal | Impact |
|---|---|
| 1M+ daily Kubernetes requests | Built and operated AI platform services at production traffic scale. |
| 99.9% availability SLOs | Worked across CI/CD, observability, Datadog, on-call, and service reliability. |
| 3.5x lower p95 inference latency | Optimized model serving with batching, quantization, ONNX/TensorRT, and deployment tuning. |

## STACK_TRACE

| Area | Tools |
|---|---|
| Languages / Frontend | Python, TypeScript, JavaScript, Kotlin, Java, React |
| Backend / APIs | FastAPI, Spring Boot, GraphQL, REST, WebSockets, microservices |
| AI / LLM Systems | LangChain, LangGraph, MCP, RAG, agents, tool calling, evals |
| Infra / Cloud / Observability | Kubernetes, Docker, AWS, GCP, Azure, GitHub Actions, Datadog, SLOs |

## CONTACT

[Portfolio](https://harihkk.github.io) · [LinkedIn](https://www.linkedin.com/in/hari-kancharla/) · [Resume](https://harihkk.github.io/resume.pdf) · Email available on resume

---

Building AI systems that retrieve context, call tools, handle failure, validate outputs, and ship.
