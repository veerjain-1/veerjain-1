<div align="center">

# Hi, I'm Veer Jain 👋
### Distributed Systems • AI Systems & Security • High-Throughput Pipelines

[![Portfolio](https://img.shields.io/badge/Portfolio-0284c7?style=for-the-badge&logo=react&logoColor=white)](https://veerjain-1.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veerjain1/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:veer.spam.jain@gmail.com)

<br/>

**Computer Science & Artificial Intelligence (Double Major) @ Purdue University**  
*Ex-AWS • Ex-Lockheed Martin • Ex-Textron • Ex-John Deere*

</div>

---

### 🚀 About Me

I'm a systems engineer and builder focused on **distributed systems**, **ML infrastructure**, and **high-throughput data pipelines**. I enjoy taking complex engineering challenges down to their first principles—whether that's serving real-time **CodeBERT inference through a Rust gRPC engine**, building distributed event-driven pipelines over **Apache Kafka**, or designing sub-millisecond deterministic security & reliability evaluation frameworks for autonomous AI agents.

- 🔭 **Current Focus:** Distributed systems, low-latency microservices, ML inference infrastructure, scalable backend architectures, and AI agent evaluation & security.
- 💡 **Engineering Philosophy:** Building high-performance, resilient software that scales horizontally, minimizes latency overhead, and operates reliably under heavy production workloads.

---

### 🌐 Open Source Contributions

I actively contribute upstream to foundational machine learning frameworks, distributed workflow engines, and developer tooling:

| Project | PR | Technical Contribution | Domain / Subsystem |
|:---|:---:|:---|:---|
| **[tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)** | [#125400](https://github.com/tensorflow/tensorflow/pull/125400) | Added bounds check on `seq_len_max` in BlockLSTM ops to prevent out-of-bounds memory access | Deep Learning C++ Kernel Safety |
| **[microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)** | [#14284](https://github.com/microsoft/semantic-kernel/pull/14284) | Implemented Vertex AI `:batchEmbedContents` routing for `gemini-embedding` models | LLM Embedding Infrastructure |
| **[cadence-workflow/cadence](https://github.com/cadence-workflow/cadence)** | [#8525](https://github.com/cadence-workflow/cadence/pull/8525) | Replaced fixed sleeps with concurrent domain notification polling in integration tests | Distributed Orchestration CI Engine |
| **[run-llama/llama_index](https://github.com/run-llama/llama_index)** | [#23127](https://github.com/run-llama/llama_index/pull/23127) | Parallelized recursive retrieval using concurrent `run_jobs` while preserving exact rank order | Query Retrieval Latency Optimization |
| **[microsoft/vscode-containers](https://github.com/microsoft/vscode-containers)** | [#598](https://github.com/microsoft/vscode-containers/pull/598) | Added Docker Compose `pull` support across palettes, context menus, and tree views | Cloud Developer Environments |
| **[kirodotdev/KiroCrew](https://github.com/kirodotdev/KiroCrew)** | [#3146](https://github.com/kirodotdev/KiroCrew/pull/3146) | Bounded interpreter probe with POSIX watchdog to prevent hangs on macOS | CLI Tooling & Process Safety |

---

### 🌟 Featured Systems & Architectures

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/veerjain-1/code-anomaly-engine">code-anomaly-engine</a></h3>
      <p><strong>Real-time Code Anomaly & Vulnerability Detection Platform</strong></p>
      <ul>
        <li>Polyglot event-driven microservices architecture in <strong>Go + Rust + Kafka + React</strong>.</li>
        <li>Sub-50ms ML inference via custom-trained <strong>CodeBERT</strong> exported with dynamic axes running on <strong>ONNX Runtime</strong> in Rust over <strong>gRPC</strong>.</li>
        <li>Buffered through Apache Kafka (KRaft mode) with live WebSocket streaming to an analytics dashboard.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/Rust-black?style=flat-square&logo=rust&logoColor=white" />
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
        <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/veerjain-1/agent-guard-eval">agent-guard-eval</a></h3>
      <p><strong>Deterministic Security, Guardrail & Eval Framework for AI Agents</strong></p>
      <ul>
        <li>Sub-millisecond trace evaluation engine eliminating flaky and costly "LLM-as-a-judge" overhead.</li>
        <li>Deterministic rules detecting infinite execution loops, schema drift, command injection, path traversal, and credential leakage.</li>
        <li>Adversarial prompt injection fuzzer and native <strong>SARIF v2.1.0</strong> export for GitHub Security alerts.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
        <img src="https://img.shields.io/badge/SARIF-v2.1.0-purple?style=flat-square" />
        <img src="https://img.shields.io/badge/CLI-Click-black?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/veerjain-1/agentic-cicd-orchestrator">agentic-cicd-orchestrator</a></h3>
      <p><strong>Autonomous CI/CD Workflow & Code Review Controller</strong></p>
      <ul>
        <li>Orchestrates multi-stage build workflows and real-time dependency validation using <strong>Java (Spring Boot)</strong> and <strong>LangGraph</strong>.</li>
        <li>Asynchronous Kafka message queues trigger recursive LLM agents for deep-dive code analysis and comprehensive PR summaries.</li>
        <li>Stateful workflow observability with full <strong>Prometheus & Grafana</strong> instrumentation.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/veerjain-1/finance-slm-rag">finance-slm-rag</a></h3>
      <p><strong>Domain-Specific Financial SLM with SFT & RAG</strong></p>
      <ul>
        <li>Supervised fine-tuning (SFT) pipeline on financial datasets utilizing <strong>PyTorch</strong> and <strong>Hugging Face Transformers</strong>.</li>
        <li>Leverages Apple <strong>Metal Performance Shaders (MPS)</strong> for 7x–10x local training acceleration over CPU.</li>
        <li>Domain-adapted retrieval-augmented generation (RAG) with FAISS vector indexing for high-precision financial QA.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/FAISS-Vector_Search-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 💻 Technical Arsenal

<div align="center">

| Category | Technologies |
|:---|:---|
| **Languages** | `Go` • `Rust` • `Python` • `Java` • `C++` • `C` • `TypeScript` • `JavaScript` • `SQL` |
| **Distributed & Cloud** | `Apache Kafka` • `AWS (Bedrock, Fargate, CDK, DynamoDB)` • `Docker` • `Kubernetes` • `gRPC / Protobuf` • `Redis` |
| **ML Infrastructure & Evals** | `PyTorch` • `ONNX Runtime` • `CodeBERT` • `Hugging Face` • `LangGraph` • `Deterministic Evals` • `Red-Teaming` |
| **Databases & Storage** | `PostgreSQL` • `MongoDB` • `Apache Spark` • `FAISS` • `MySQL` |
| **Frontend & UI** | `React` • `Tailwind CSS` • `Framer Motion` • `Recharts` • `Vite` |

</div>

---

<div align="center">
  <sub>Built with care by <a href="https://github.com/veerjain-1">Veer Jain</a> • Explore more on my <a href="https://veerjain-1.github.io/">Portfolio</a></sub>
</div>
