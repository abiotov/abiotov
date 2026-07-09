<!-- Profile README for Etienne Tovimafa -->

<h1 align="center">Etienne Tov</h1>

<p align="center">
  <b>Agentic AI Engineer</b>, building AI agents that do real work
</p>

<p align="center">
  <img alt="Focus areas" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=900&center=true&vCenter=true&width=640&color=2F81F7&lines=AI+Agents+%26+Multi-Agent+Systems;Agentic+Search+%26+Agentic+RAG;LLM+Orchestration+%2B+Tool+Use;Generative+AI%2C+shipped+and+evaluated">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/etiennetovi"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/abiotov"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <img alt="Open source" src="https://img.shields.io/badge/Open%20Source%20at%20heart-3DA639?style=for-the-badge&logo=opensourceinitiative&logoColor=white">
</p>

---

### 👋 About

I'm an Agentic AI engineer. I build **AI agents and multi-agent systems**: LLMs wired to real tools, memory, and retrieval so they can plan, act, and get useful work done.

Before agents, I shipped search and applied NLP systems (real-time retrieval, summarization, translation, Q&A). That production experience shapes how I build today: most of my effort goes into the engineering **around** the model (orchestration, retrieval, evaluation, guardrails) because that is what turns a good demo into something people can rely on.

> The demo is the easy part. An agent that is reliable, evaluated, and safe in production is the real work.

---

### 🔭 Current focus

- 🤖 **Multi-agent orchestration**: planning, tool and function calling, routing, state, and human-in-the-loop.
- 🔎 **Agentic search and agentic RAG**: query planning, hybrid retrieval, reranking, and validation loops instead of retrieve-once-and-hope.
- 📊 **Evaluation and reliability**: eval suites, tracing, guardrails, and cost control treated as part of the build, not an afterthought.
- 🌱 **Open source**: building and contributing in the agents, retrieval, and evals ecosystem.

---

### 🧩 Track record

- **Real-time retrieval for search**: low-latency retrieval and candidate generation over large corpora, with hybrid dense and sparse search.
- **Summarization**: abstractive and long-document summarization, including map-reduce pipelines for long inputs.
- **Machine translation**: neural and LLM-based translation, with domain adaptation.
- **Question answering**: RAG and extractive Q&A over documents and knowledge bases, with retrieval, reranking, and grounded citations.

---

### ⚙️ How I build agentic retrieval

`Plan the query` → `route to the right source` → `hybrid retrieval (dense + keyword)` → `rerank` → `validate, and retry if needed` → `answer with citations`

Agents earn their extra latency and cost only on multi-part, context-dependent questions. When a single call is enough, I keep it simple.

---

### 🛠️ Tech stack

**Agents & orchestration** &nbsp;
<img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img alt="CrewAI" src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square">
<img alt="AutoGen" src="https://img.shields.io/badge/AutoGen-0078D4?style=flat-square">
<img alt="LlamaIndex" src="https://img.shields.io/badge/LlamaIndex-3A3A3A?style=flat-square">

**Retrieval & memory** &nbsp;
<img alt="RAG" src="https://img.shields.io/badge/RAG%20%2F%20Agentic%20RAG-4B8BBE?style=flat-square">
<img alt="Pinecone" src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white">
<img alt="pgvector" src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img alt="Chroma" src="https://img.shields.io/badge/Chroma-FF6F61?style=flat-square">
<img alt="FAISS" src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square">

**Protocols & tools** &nbsp;
<img alt="Model Context Protocol" src="https://img.shields.io/badge/Model%20Context%20Protocol%20(MCP)-000000?style=flat-square">
<img alt="Function calling" src="https://img.shields.io/badge/Function%20%2F%20Tool%20Calling-5A5A5A?style=flat-square">

**Evals & observability** &nbsp;
<img alt="LangSmith" src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square">
<img alt="Opik" src="https://img.shields.io/badge/Opik-3267E5?style=flat-square">
<img alt="Langfuse" src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square">

**Models** &nbsp;
<img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
<img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white">
<img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
<img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white">
<img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">

**Core** &nbsp;
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">

---

### 🧭 How I work

- **Reliability first**: correctness, observability, and failure modes before features.
- **Evaluation as infrastructure**: checks that gate a change, not a one-off accuracy number.
- **Right-sized systems**: reach for agents when the problem needs them, not by default.
- **Safety by default**: guardrails, careful data handling, and responsible release.

---

### 💬 Let's build

I like talking about **AI agents, agentic search and RAG, orchestration, and evaluation**. Happy to pair, review, or think through a hard problem, and open to collaborating on open-source agentic AI or with teams building agentic products.

<p align="center">
  <a href="https://www.linkedin.com/in/etiennetovi"><img alt="Reach out on LinkedIn" src="https://img.shields.io/badge/Reach%20out-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>
