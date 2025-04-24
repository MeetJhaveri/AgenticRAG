# 🧠 AgenticRAG

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline to answer questions related to happiness using information from online blog articles. It combines **LangChain**, **LangGraph**, and **OpenAI LLMs** to build an intelligent, multi-step reasoning system that retrieves, grades, rewrites, and answers user queries.

---

## 🚀 Features

- 🔍 **Web-Based Document Retrieval** using `WebBaseLoader` from blog URLs
- 🧠 **Semantic Search & Vector Embeddings** using ChromaDB + OpenAI embeddings
- ✅ **Relevance Grading** via a structured OpenAI model output
- 🔄 **Question Rewriting** to improve retrieval effectiveness
- ✍️ **Answer Generation** using `gpt-3.5-turbo` or `gpt-4` with a custom RAG prompt
- 🔧 **Stateful Workflow Orchestration** using `LangGraph`'s `
