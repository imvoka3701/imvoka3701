# DANH ĐỨC
### AI Systems & Software Engineer

> Specializing in Generative AI Architecture, Large Language Model Pipelines, and Resilient Backend Infrastructure.

[![Email](https://img.shields.io/badge/Email-Contact-0D1117?style=flat-square&logo=gmail&logoColor=white)](mailto:your_email@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-imvoka3701-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/imvoka3701)
[![Focus](https://img.shields.io/badge/Focus-GenAI%20%7C%20Backend-0D1117?style=flat-square)](https://github.com/imvoka3701)

---

### Core Competencies

* **Generative AI & LLM Systems:** Production RAG pipelines, Multi-Agent orchestration, context-window optimization, Prompt Engineering, and model evaluation.
* **Model Training & Fine-Tuning:** Supervised Fine-Tuning (SFT), Parameter-Efficient Fine-Tuning (PEFT via LoRA/QLoRA), and local inference deployment.
* **Backend & System Architecture:** High-throughput REST/gRPC APIs, microservices integration, relational/vector database indexing, and container orchestration.

---

### Technical Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Artificial Intelligence** | PyTorch, Hugging Face, LangChain, LlamaIndex, CrewAI, AutoGen, Ollama, vLLM |
| **Vector & Data Storage** | PostgreSQL, pgvector, ChromaDB, Pinecone, SQLite |
| **Backend Engineering** | Python, FastAPI, ASP.NET Core (.NET), C, Node.js |
| **DevOps & Infrastructure** | Docker, Docker Compose, Nginx, Linux (Ubuntu), Git CI/CD |
| **Frontend & Interfaces** | Vue.js, TypeScript, Tailwind CSS |

---

### Key Architectural Focus

```text
+-------------------+      +-----------------------+      +--------------------+
|  Client Interface | ---> |   API Gateway / Auth  | ---> | Backend / Services |
+-------------------+      +-----------------------+      +--------------------+
                                                             |          |
                          +----------------------------------+          |
                          v                                             v
               +--------------------+                       +--------------------+
               | Vector DB / RAG    |                       | LLM Engine / Agents|
               | (pgvector/Chroma)  |                       | (Local / Inference)|
               +--------------------+                       +--------------------+
