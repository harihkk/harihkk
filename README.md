# Hari Krishna Kancharla

**Production AI systems engineer: LLM runtimes, RAG platforms, agent workflows, and inference infrastructure.**

Boston, MA · AI Software Engineer at Morgan Stanley

[Portfolio](https://harihkk.github.io) · [LinkedIn](https://www.linkedin.com/in/hari-kancharla/) · [Resume](https://harihkk.github.io/resume.pdf) · [Surf Agent](https://github.com/harihkk/surf-agentic-browser)

---

I work on the systems layer around AI: retrieval, tools, orchestration, serving, observability, and failure recovery. At Morgan Stanley, my runtime is production: Kubernetes traffic, SLOs, inference latency, CI/CD, Datadog, and on-call ownership.

## CURRENT_STATE

- Building RAG, agentic workflow, and LLM serving platforms with end-to-end ownership.
- Operating close to the metal: p95 latency, trace quality, eval coverage, rollback paths, and SLOs.
- Turning AI prototypes into systems with deployment discipline and useful failure signals.

## FEATURED_SYSTEMS

### [Surf](https://github.com/harihkk/surf-agentic-browser)

Autonomous browser agent that converts natural-language goals into Playwright actions. The interesting part is not the prompt; it is the runtime around it: browser state, tool execution, loop detection, session recording, and provider fallback across Groq, Gemini, and Ollama.

`FastAPI` `Playwright` `WebSockets` `Groq` `Gemini` `Ollama`

### [AskRC](https://github.com/harihkk/AskRC)

RAG + MLOps pipeline for research computing documentation. Built as a deployment path, not a chatbot demo: ingestion, Azure Search indexing, DVC versioning, MLflow tracking, Airflow orchestration, and validation checkpoints.

`Python` `Azure Search` `Airflow` `DVC` `MLflow` `Docker`

### [Prompt-Budd](https://github.com/harihkk/Prompt-Budd)

Operator-side prompt tooling for scoring, rewriting, PII checks, and MCP-backed workflows. It brings prompt quality feedback into the browser where the work happens, with model routing and backend safeguards behind the interface.

`Chrome Extension` `FastAPI` `Gemini` `OpenAI` `Groq` `MCP`

### [GenBI](https://github.com/harihkk/GenBI)

Natural-language BI assistant for turning datasets into charts, tables, and answers. The system separates analytical intent, data operations, visualization, and response synthesis so the output is inspectable instead of magical.

`FastAPI` `LangChain` `GPT-4o` `Plotly` `Pandas` `Firebase`

## DEPLOYMENT_HISTORY

- **1M+ daily Kubernetes requests** across production AI platform services.
- **99.9% availability SLOs** with CI/CD, observability, Datadog, on-call, and service ownership.
- **3.5x reduction in p95 inference latency** through batching, quantization, ONNX/TensorRT, and deployment tuning.

## STACK_TRACE

**Languages / Frontend:** Python, TypeScript, JavaScript, Kotlin, Java, React

**Backend / APIs:** FastAPI, Spring Boot, GraphQL, REST, WebSockets, microservices

**AI / LLM Systems:** LangChain, LangGraph, MCP, RAG, agents, tool calling, evals

**Infra / Signal:** Kubernetes, Docker, AWS, GCP, Azure, GitHub Actions, Datadog, SLOs

## OPERATOR_CONSOLE

[Portfolio](https://harihkk.github.io) · [LinkedIn](https://www.linkedin.com/in/hari-kancharla/) · [Resume](https://harihkk.github.io/resume.pdf) · Email available on resume

---

Building AI systems that retrieve context, call tools, handle failure, validate outputs, and ship.
