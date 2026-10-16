<div align="center">

# Hi, I'm Veer Jain 👋
### Distributed Systems • AI Systems & Security • High-Throughput Telemetry

[![Portfolio](https://img.shields.io/badge/Portfolio-veerjain--1.github.io-0ea5e9?style=for-the-badge&logo=react&logoColor=white)](https://veerjain-1.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Veer_Jain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veer-jain/)
[![GitHub](https://img.shields.io/badge/GitHub-veerjain--1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/veerjain-1)

<br/>

**Undergraduate in Computer Science @ Purdue University**  
*Incoming SDE Intern @ AWS (Summer 2026) • Ex-Lockheed Martin • Ex-Textron Systems • Ex-John Deere*

</div>

---

### 🚀 About Me

I specialize in **distributed systems**, **low-latency inference**, and **autonomous agent security & evaluation**. I enjoy taking complex engineering challenges down to their first principles—whether that's parsing gigabyte-scale autonomous vehicle MCAP telemetry, routing real-time CodeBERT inference through a Rust/gRPC engine, or designing multi-agent red-teaming pipelines that uncover production infrastructure vulnerabilities.

- 🔭 **Current Focus:** Sub-50ms inference microservices, deterministic agent evaluation frameworks, and event-driven architectures.
- 🛠️ **Industry Experience:**
  - **Amazon Web Services (AWS)** — SDE Intern (Summer '26): AI Security Analyzer, multi-agent red-teaming, deterministic eval frameworks.
  - **Lockheed Martin** — SWE Intern: Real-time ML inference platform, defense-grade microservices, PySpark telemetry streaming over Kafka.
  - **Textron Systems** — SWE Intern: Warfare simulator threat detection algorithms, sensor telemetry indexing.
  - **John Deere** — ML Research Engineer Intern: Time-series forecasting and inventory optimization.
- 🌐 **Open Source:** Active upstream contributor to [Microsoft VS Code Containers](https://github.com/microsoft/vscode-containers), [Uber Cadence Workflow](https://github.com/cadence-workflow/cadence), [Microsoft Semantic Kernel](https://github.com/microsoft/semantic-kernel), and [LlamaIndex](https://github.com/run-llama/llama_index).

---

### 🌟 Featured Systems & Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/veerjain-1/code-anomaly-engine">code-anomaly-engine</a></h3>
      <p><strong>Real-time Code Anomaly & Vulnerability Detection Engine</strong></p>
      <ul>
        <li>Polyglot event-driven microservices architecture in <strong>Go + Rust + Kafka + React</strong>.</li>
        <li>Sub-50ms ML inference via custom-trained <strong>CodeBERT</strong> exported with dynamic axes running on <strong>ONNX Runtime (ort)</strong> in Rust over <strong>gRPC</strong>.</li>
        <li>Buffered through Apache Kafka (KRaft mode) with live WebSocket streaming to a real-time metrics dashboard.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/Rust-black?style=flat-square&logo=rust&logoColor=white" />
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🚗 <a href="https://github.com/veerjain-1/av-drive-triage">av-drive-triage</a></h3>
      <p><strong>Autonomous Vehicle Drive Log & Telemetry Triage Platform</strong></p>
      <ul>
        <li>Parses multi-gigabyte <strong>nuScenes MCAP</strong> drive logs to detect unexplained decelerations, cut-ins, and obstacle near-misses.</li>
        <li>Synchronizes 3D ego-pose coordinate transforms with forward camera JPEG frames on a unified time axis.</li>
        <li>Rules-first triage queue with automated Markdown escalation reports and false-positive label generation.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
        <img src="https://img.shields.io/badge/MCAP-Telemetry-orange?style=flat-square" />
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
        <li>Domain-adapted retrieval-augmented generation (RAG) with vector embeddings for complex financial QA.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 🌐 Open Source Contributions

I contribute upstream to open-source developer tooling, distributed orchestrators, and AI frameworks:

| Project | PR | Summary | Impact |
|:---|:---:|:---|:---|
| **[microsoft/vscode-containers](https://github.com/microsoft/vscode-containers)** | [#598](https://github.com/microsoft/vscode-containers/pull/598) | Contributed Docker Compose `pull` support across palettes, context menus, and tree views with automated unit tests | Closes feature gap across Docker/Podman/Finch Compose runtimes |
| **[cadence-workflow/cadence](https://github.com/cadence-workflow/cadence)** | [#8525](https://github.com/cadence-workflow/cadence/pull/8525) | Replaced fixed integration test sleeps with concurrent domain registration and persistence notification polling | Accelerates integration CI suites; approved by maintainers |
| **[microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)** | [#14284](https://github.com/microsoft/semantic-kernel/pull/14284) | Implemented Vertex AI `:batchEmbedContents` routing for `gemini-embedding-*` models | Unlocks modern Gemini embedding models in Semantic Kernel .NET |
| **[run-llama/llama_index](https://github.com/run-llama/llama_index)** | [#23127](https://github.com/run-llama/llama_index/pull/23127) | Parallelized recursive retrieval using concurrent `run_jobs` while preserving exact node ranking | Significantly reduces recursive query retrieval latency |

---

### 💻 Technical Arsenal

<div align="center">

| Category | Technologies |
|:---|:---|
| **Languages** | `Go` • `Rust` • `Python` • `Java` • `C++` • `C` • `TypeScript` • `JavaScript` • `SQL` |
| **Distributed & Cloud** | `Apache Kafka` • `AWS (Bedrock, Fargate, CDK, DynamoDB)` • `Azure` • `Docker` • `Kubernetes` • `gRPC / Protobuf` • `Redis` |
| **AI / ML & Evals** | `PyTorch` • `ONNX Runtime` • `CodeBERT` • `Hugging Face` • `LangGraph` • `LangChain` • `Agent Red-Teaming` • `Deterministic Evals` |
| **Data & Storage** | `PostgreSQL` • `MongoDB` • `Apache Spark` • `nuScenes (MCAP)` • `MySQL` |
| **Frontend & Visualization** | `React` • `Tailwind CSS` • `Framer Motion` • `Recharts` • `Vite` |

</div>

---

<div align="center">
  <sub>Built with care by <a href="https://github.com/veerjain-1">Veer Jain</a> • Check out my interactive portfolio at <a href="https://veerjain-1.github.io/">veerjain-1.github.io</a></sub>
</div>
