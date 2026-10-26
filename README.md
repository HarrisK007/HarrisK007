<h1>Hi, I'm Harris 👋</h1>

**AI Engineer** · building production AI at SofDigital Systems · Karachi, Pakistan · BS Artificial Intelligence (QUEST, 2025)

I build LLM systems that run in production: retrieval, text-to-SQL, AI agents and the APIs around them.

### 🔭 What I'm working on

A **multilingual AI assistant for an HR/HCM platform**. Employees and executives ask questions like *"Who is absent today?"* or *"Show my salary slip"* in English, Urdu, Roman Urdu or Arabic, and get accurate answers from the HR database.

- **Retrieval:** fine-tuned Qwen3-Embedding-0.6B with LoRA on 43K+ question phrasings, reaching **99.4% top-5 recall** over 2,300+ verified SQL templates on an independent test set
- **Generation:** an LLM agent (PydanticAI + Claude) fills in the matched query or asks a clarifying question
- **Safety:** every generated query is validated as read-only (sqlglot), with bind variables, row caps and rate limits; the service never touches employee data
- **Production:** multi-tenant FastAPI service with per-client keys, cost tracking, prompt caching, and eval + live acceptance suites

*(Company code, so it's private, but I'm happy to talk about how it works.)*

### 🧰 Tech

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PydanticAI](https://img.shields.io/badge/PydanticAI-E92063?logo=pydantic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?logo=onnx&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_SQL-F80000?logo=oracle&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [Voice AI Patient Registration API](https://github.com/HarrisK007/Vapi-AI-Voice-agent-Api) | Backend for a phone-based voice AI agent that registers patients: validated CRUD, soft deletes, tests | FastAPI, Pydantic v2, SQLAlchemy, Vapi |
| [YouTube-RAG](https://github.com/HarrisK007/Youtube-Rag-System) | Chat with any YouTube video; answers point to the exact timestamp | LangChain, ChromaDB, Gemini, Streamlit |
| [DOCX-Bot](https://github.com/HarrisK007/DOCUMENT-RAG-USING--LANGCHAIN) | Chat with PDF, DOCX, CSV, JSON or TXT files using RAG; export the chat as a PDF | LangChain, Gemini, Streamlit |
| [Multi-role AI Chatbot](https://github.com/HarrisK007/AI-Chatbot-using-langchain) | Multi-session chatbot with role-based answers for healthcare, finance and education | LangChain, Gemini, Streamlit |
| [Pacman Path-Finding](https://github.com/HarrisK007/Path_Finding_Algorithms_with_Pacman) | BFS, Uniform Cost and A* search agents compared across mazes | Python |

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harris--akhtar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harris-akhtar/)

Open to **AI Engineer / LLM Engineer** roles, remote or in Karachi.
