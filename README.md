# Hi there 👋, I'm Roberto

Computer Science Student & AI Software Engineer.

I focus on building robust, production-ready systems. I prioritize clean architecture, strict type safety, and performance optimization to create maintainable software.

🔭 Active Open Source Contributor developing features and ensuring engineering best practices in Computer Vision and Audio Intelligence ecosystems.

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
* **[SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)**: Contributor in architectural discussions regarding **production scaling** and high-concurrency patterns.


## 🛠️ Tech Stack

* **Core & Backend:** Python 3.12 (Strict Typing), Docker, FastAPI/Streamlit.
* **AI & Data:** OpenAI, Faster-Whisper, **RapidOCR**, Sentence-Transformers.
* **Vector Search:** **Qdrant** (Hybrid Search: Dense + Sparse).
* **Quality & DevOps:** Mypy, Ruff, Pre-commit hooks, GitHub Actions.


## ⚡ GitHub Stats

<div align="center">
<a href="https://github.com/uahroberto">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=uahroberto&show_icons=true&theme=radical&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=uahroberto&layout=compact&theme=radical"/>
</a>
</div>
