# Multimodal-Agentic-RAG-with-Mistral-Manager
A Python-based multimodal Agentic RAG system with QA, Task, and Analysis agents coordinated by a Mistral-style manager. Integrates FAISS for memory, BLIP for image captioning, and a domain-specific knowledge base for scalable, interpretable, and context-aware AI decision-making.
# Multimodal Agentic RAG with Mistral Manager

## 🧠 Overview
This repository contains a **Python-based multimodal Agentic RAG system** featuring a Mistral-style manager agent that coordinates multiple specialized sub-agents — QA, Task, and Analysis — for intelligent and context-aware AI reasoning.

## ⚙️ Key Features
- **Manager–Agent Architecture:** Dynamic routing of tasks between agents.  
- **Multimodal Input Support:** Handles both text and image queries.  
- **FAISS-Powered Memory:** Efficient vector-based semantic retrieval.  
- **BLIP Integration:** Automatic image captioning for visual understanding.  
- **Explainable Decision-Making:** Transparent, interpretable outputs for research and analysis.

## 🧩 Components
1. **Manager Agent (Mistral-inspired)** – Directs queries intelligently.  
2. **QA Agent** – Retrieves answers from text corpus.  
3. **Task Agent** – Executes procedural or reasoning tasks.  
4. **Analysis Agent** – Performs evaluation and summarization.  
5. **FAISS Memory Store** – Embedding-based similarity search.  
6. **BLIP Captioner** – Converts image inputs into text for processing.  

## 🚀 Installation
```bash
!pip install transformers accelerate torch sentence-transformers faiss-cpu blip requests Pillow
🧰 Dependencies

transformers

langchain

faiss-cpu

sentence-transformers

blip

Pillow

numpy, pandas
User Input → Mistral Manager → Sub-Agent (QA / Task / Analysis)
                  ↓
             FAISS Memory Retrieval
                  ↓
             Output Response (Text or Image-Based)
## 🧾 License
This project is open for educational and research purposes.

---

## 👨‍💻 Author
Developed by **Adnan Karamat**,  
Lecturer in Computer Science | Researcher in AI, NLP, and Multimodal Systems.
