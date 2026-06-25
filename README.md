# RAGApp 🚀

RAGApp is a production-ready, event-driven Retrieval-Augmented Generation (RAG) application. It leverages a modern AI and asynchronous tech stack to ingest documents, index them into a vector database, and provide an interactive chat interface for answering queries based on the ingested knowledge base.

## 🛠️ Tech Stack

- **Orchestration & RAG Framework:** [LlamaIndex](https://www.llamaindex.ai/)
- **Frontend UI:** [Streamlit](https://streamlit.io/)
- **Vector Database:** [Qdrant](https://qdrant.tech/)
- **Asynchronous Event/Job Queue:** [Inngest](https://www.inngest.com/)
- **LLM & Embeddings:** [OpenAI](https://openai.com/) (GPT and Text-Embedding models)
- **Language:** Python 3.10+

## ✨ Features

- **Document Ingestion Pipeline:** Upload, parse, and process unstructured data into clean text chunks.
- **Asynchronous Background Processing:** Heavy ingestion and embedding jobs are offloaded to **Inngest**, ensuring the user interface remains snappy and responsive.
- **Vector Storage:** High-performance vector indexing and semantic similarity search powered by **Qdrant**.
- **Contextual Chat Interface:** A streamlined, conversational UI built with **Streamlit** to query your documents with streaming responses.
