<h1 align="center">Hi there! I'm Tymur 🚀</h1>
<h3 align="center">Founder & 0→1 Product Architect | space+ultra</h3>

<p align="center">
  <a href="https://spaceplusultra.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-space%2Bultra-black?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://www.linkedin.com/in/ttsch/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:tymurcherkasov@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I am a 2x founder and the architect behind **space+ultra**, an AI Product Lab based in Berlin. 

I build systems that don't fall apart when the LLM hallucinates.  At space+ultra, I treat AI not as magic, but as a volatile, high-entropy component that needs a strong architectural wrapper. I spend my time building deterministic boundaries, state machines, and evaluation pipelines that make agentic systems predictable enough to actually run in production.  I’m less interested in prompt engineering and more interested in systems that reliably bridge the gap between "AI proof-of-concept" and "enterprise-grade infrastructure".

### 🔭 Recent & Active Architectures

* **`Baumind`** — An enterprise AI Copilot for BIM model auditing and building code compliance. Architected a LangGraph multi-agent swarm grounded in a **Hybrid Graph RAG** pipeline (Neo4j, pgvector). Designed a custom **Zero-Payload C# MCP server** to securely execute agentic logic inside legacy CAD environments (Revit API) without exposing sensitive 3D IP over the wire.
* **`em•dash`** — A proactive AI agent for B2B SaaS powered by a proprietary **Causal Conversion Engine**. It leverages Double Machine Learning (DoWhy, EconML) and a sub-30ms Rust/WASM edge tracker to evaluate "digital body language," mathematically prove Net Incremental Revenue (NIR), and generate dynamic Agent-to-User Interfaces (A2UI).
* **`UE5 Workflow Automator`** — Embedded automation architecture for commercial 3D staging. Orchestrated autonomous AI coding agents to design and deploy a **94,000 LOC C++ Unreal Engine 5 plugin** in just 10 weeks, enforcing strict game-thread concurrency and memory safety.

### 🛠️ Architecture & Agentic Tech Stack

[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-333333?style=flat-square&logo=langchain&logoColor=white)](https://www.langchain.com/langgraph)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)](https://webassembly.org/)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)](https://neo4j.com/)
[![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/pgvector/pgvector)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005863?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)

**Core Paradigms & Implementation:**
* **Multi-Agent Orchestration:** LangGraph (Supervisor-Worker topologies), Pydantic-AI, and custom Zero-Payload Model Context Protocol (MCP) servers.
* **Evaluation & Governance:** LLM Observability (Langfuse), LLM-as-a-judge pipelines, and custom cost-per-request tracking to ensure robust production governance.
* **Causal Inference & RLHF:** DoWhy and EconML (Double Machine Learning) for isolating persuasion effects. Edge-Native LinUCB Contextual Bandits using fixed-point arithmetic (`Q16x16`).
* **Knowledge & Memory:** Neo4j (Spatial Property Graphs for architectural topologies) and Hybrid RAG pipelines (pgvector + BM25 keyword fallback) for high-availability regulatory grounding.
* **Edge & High-Performance Compute:** Rust/WASM (zero-copy ring buffers over `SharedArrayBuffer`) for 50Hz edge telemetry, and C++ for Unreal Engine 5 concurrency.
* **Security & Infrastructure:** GCP GenAI Stack (Vertex AI, Gemini), ZK Privacy (Groth16 zero-knowledge proofs), and Supabase PostgreSQL with strictly enforced Row Level Security (RLS).

---

<details>
<summary><b>🌌 Why space+ultra? (Click to expand)</b></summary>

**`space+ultra`** is an experimental AI product lab. Our name reflects how we push past the "limits" of standard LLM application.

**`"Space"`** refers to the architectural white space—the complex, often ignored structural gaps between legacy systems and modern AI.  Whether it’s the latent space of user intent, the topological complexity of 3D building models, or the bottlenecks in a production pipeline, we treat these "invisible" gaps as the primary design surface. We don't just fill these spaces with AI; we build the bridges that make them coherent.  

**`"Ultra"`** signifies our approach to systematic reliability.  
We move ultra (beyond) the conventional "wrapper" paradigm:
Beyond passive calls: We architect autonomous, agentic orchestrations that take responsibility for outcomes.  
Beyond probabilistic guessing: We wrap volatile AI components in deterministic state machines to ensure enterprise-grade predictability.  
Beyond manual implementation: We use AI-native coding agents to manage complex, multi-language stacks—from low-level C++ plugin logic to high-level Graph RAG pipelines—with a speed that defies manual engineering constraints.  

We’re here to go beyond the **`"non plus ultra"`**—pushing past the current boundaries of system design to see what happens when AI is treated as a deterministic engineering component rather than a magic trick. 

</details>
