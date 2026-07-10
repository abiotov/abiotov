<!-- Profile README for Etienne Tovimafa -->

<h1 align="center">Etienne Tov</h1>

<p align="center">
  <b>Agentic AI Engineer</b>, building AI agents that do real work in production
</p>

<p align="center">
  <img alt="Focus areas" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=900&center=true&vCenter=true&width=640&color=2F81F7&lines=AI+Agents+%26+Multi-Agent+Systems;Agentic+Search+%26+Agentic+RAG;Real-Time+Voice+Agents;LLM+Evaluation+%26+Observability">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/etiennetovi"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/abiotov"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <img alt="Open source" src="https://img.shields.io/badge/Open%20Source%20at%20heart-3DA639?style=for-the-badge&logo=opensourceinitiative&logoColor=white">
</p>

---

### 👋 About

I'm an Agentic AI engineer with ~3 years designing and shipping **LLM systems that run in production under real traffic**: agentic RAG with verified citations, real-time voice agents, and resilient multi-provider infrastructure.

Most of my effort goes into the engineering **around** the model (orchestration, retrieval, evaluation, observability) because that is what turns a good demo into something people rely on. I started in IT security, and it shows in how I build: failure modes and guardrails come first.

> The demo is the easy part. An agent that is reliable, evaluated, and safe in production is the real work.

---

### 🧩 Track record

- **Agentic RAG in production**: multi-mode agent orchestration with parallel retrieval and structured citations, serving real users daily.
- **Citation verification (anti-hallucination)**: every reference checked for existence, accuracy, and validity before display; anything unverifiable is neutralized before it reaches the user.
- **Hybrid retrieval at scale**: vector + keyword + reranking over 30,000+ domain documents, search latency cut 5x.
- **Real-time voice agents**: a multi-tenant conversational voice platform (WebRTC, interruption handling), in pilot with a major bank.
- **Continuous evaluation**: LLM-as-judge on self-hosted Opik, catching quality regressions before every release.
- **Performance engineering**: critical production endpoints taken from 90 s to 1.9 s response time.

---

### 🔭 Current focus

- 🤖 **Multi-agent orchestration**: planning, tool and function calling, routing, state, and human-in-the-loop.
- 🔎 **Agentic search and agentic RAG**: query planning, hybrid retrieval, reranking, and validation loops instead of retrieve-once-and-hope.
- 📊 **Evaluation and reliability**: eval suites, tracing, guardrails, and cost control treated as part of the build, not an afterthought.
- 🌱 **Open source**: building and contributing in the agents, retrieval, and evals ecosystem.

---

### ⚙️ How I build agentic retrieval

`Plan the query` → `route to the right source` → `hybrid retrieval (dense + keyword)` → `rerank` → `validate, and retry if needed` → `answer with verified citations`

Agents earn their extra latency and cost only on multi-part, context-dependent questions. When a single call is enough, I keep it simple.

---

### 🛠️ Tech stack

**Agents & orchestration** &nbsp;
<img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img alt="LiteLLM" src="https://img.shields.io/badge/LiteLLM-2E5BFF?style=flat-square">
<img alt="Tool calling" src="https://img.shields.io/badge/Tool%20%2F%20Function%20Calling-5A5A5A?style=flat-square">

**Retrieval & RAG** &nbsp;
<img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square">
<img alt="Hybrid search" src="https://img.shields.io/badge/Hybrid%20Search%20(BM25%20%2B%20RRF)-4B8BBE?style=flat-square">
<img alt="Cohere Rerank" src="https://img.shields.io/badge/Cohere%20Rerank-39594D?style=flat-square">
<img alt="Embeddings" src="https://img.shields.io/badge/Embeddings-6C3EF5?style=flat-square">

**Voice AI** &nbsp;
<img alt="LiveKit" src="https://img.shields.io/badge/LiveKit-FF4F00?style=flat-square">
<img alt="Deepgram" src="https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logoColor=black">
<img alt="WebRTC" src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white">
<img alt="ElevenLabs" src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square">

**Evals & observability** &nbsp;
<img alt="Opik" src="https://img.shields.io/badge/Opik-3267E5?style=flat-square">
<img alt="LangSmith" src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square">
<img alt="LLM-as-judge" src="https://img.shields.io/badge/LLM--as--judge-8250DF?style=flat-square">

**Models** &nbsp;
<img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
<img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white">
<img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
<img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">

**Backend & data** &nbsp;
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white">
<img alt="Neo4j" src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white">
<img alt="Airflow" src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">

---

### 🧭 How I work

- **Reliability first**: correctness, observability, and failure modes before features.
- **Evaluation as infrastructure**: checks that gate a release, not a one-off accuracy number.
- **Right-sized systems**: reach for agents when the problem needs them, not by default.
- **Safety by default**: guardrails, careful data handling, and responsible release.

---

### 💬 Let's build

I like talking about **AI agents, agentic search and RAG, voice agents, and evaluation**. Happy to pair, review, or think through a hard problem, and open to collaborating on open-source agentic AI or with teams building agentic products.

<p align="center">
  <a href="https://www.linkedin.com/in/etiennetovi"><img alt="Reach out on LinkedIn" src="https://img.shields.io/badge/Reach%20out-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>
