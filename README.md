# LLM-Based Email Summarization and Response Generation

This project implements an LLM-powered email assistant designed to help users efficiently understand and respond to long or complex emails. It combines email summarization with controlled response generation, ensuring accuracy, relevance, and adherence to user-defined constraints. The system is built using LangChain and integrates Meta LLaMA 3.1 via the Groq API for fast, high-quality natural language processing.

---

## 🚀 Key Features

- Summarizes long emails into concise, meaningful summaries  
- Handles long inputs using recursive text chunking  
- Generates response emails strictly based on summarized content  
- User-configurable response length (short, medium, long)  
- User-configurable tone (formal, casual, polite)  
- Prevents hallucinations through strict prompt constraints  
- Preserves names and sender/recipient roles  
- Supports pasted email text or uploaded `.txt` files  
- Exports generated responses as downloadable text files  

---

## 🧠 System Architecture

Email Input → Text Chunking → Chunk-Level Summarization → Final Summary → Controlled Response Generation → Exported Response

---

## 🧪 Model & Frameworks

- LLM: Meta LLaMA 3.1 (8B Instant)  
- LLM Provider: Groq  
- Framework: LangChain  
- Backend Language: Python  

---

## 📦 Tech Stack

- Python  
- LangChain  
- Groq API  
- Meta LLaMA 3.1  
- HuggingFace Transformers  
- PyTorch  
- Jupyter Notebook  

---

## 🔑 API Key Setup

This project requires a free Groq API key.

Create a key at: https://console.groq.com/keys

Set the environment variable:

Linux / macOS:
```bash
export GROQ_API_KEY="your_api_key_here"
