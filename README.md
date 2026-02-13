# Hi there 👋, I'm Roberto

 Software Engineer & Computer Science Student

I focus on building robust, production-ready systems. I prioritize clean architecture, strict type safety, and performance optimization to create maintainable software.

Active Open Source Contributor developing features and ensuring engineering best practices.

## 🔭 Featured Project

### 📼 [Video RAG Pro](https://github.com/uahroberto/video-rag-pro)

A **Multimodal AI Engine** that enables users to "chat" with video content by analyzing both **audio speech** and **visual screen context** (OCR).

Unlike simple text-wrappers, this project is engineered for depth and reliability:
* **👁️ Visual RAG:** Implements an OCR pipeline to "read" code and slides from video frames, capturing context that is shown but not spoken.
* **🧠 Hybrid Search:** Uses **Qdrant** to combine semantic embeddings with keyword search (BM25) for precise technical retrieval.
* **⚡ Performance:** Achieved **0.14 RTF** on CPU using custom int8 quantization.
* **🛡️ Engineering:** Fully Dockerized ETL pipeline with strict type safety guarantees.

## 🌱 Open Source Contributions
*I believe in improving the tools I use daily.*

* **[roboflow/supervision](https://github.com/roboflow/supervision)**: Led the **strict typing migration** for the `metrics` module (+700 lines refactored) and ensured full compatibility with **NumPy 2.0**. Refactored core calculation logic in `MeanAveragePrecision` to align the library with production-grade engineering standards.
* **[qdrant/qdrant-client](https://github.com/qdrant/qdrant-client)**: Enhanced **Developer Experience (DX)** by standardizing type hints across the client interface, streamlining hybrid search (Dense + Sparse) integration for gRPC and HTTP users.
* **[SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)**: Proposing architectural patterns for **Dynamic Batching** and request queuing to solve latency bottlenecks in high-concurrency GPU environments.
* **[pyDeprecate](https://github.com/AndreiFahm/pyDeprecate)**: Contributed to core design discussions on **decorator deprecation lifecycles**, advocating for "Fail Fast" import-time warnings to prevent silent technical debt in production systems.
## 🛠️ Tech Stack

* **Core & Backend:** Python 3.12 (Strict Typing), Docker, FastAPI/Streamlit.
* **AI & Data:** OpenAI, Faster-Whisper, **RapidOCR**, Sentence-Transformers.
* **Vector Search:** **Qdrant** (Hybrid Search: Dense + Sparse).
* **Quality & DevOps:** Mypy, Ruff, Pre-commit hooks, GitHub Actions.


