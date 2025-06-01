
#  LLAMA3 Chatbot with LangChain & Streamlit

A lightweight conversational chatbot powered by **Meta’s LLAMA2** using **LangChain** and deployed through a **Streamlit web interface**. This assistant is designed for interactive Q&A, demonstrating how to integrate a local LLM via Ollama with LangChain components and custom prompts.

---

##  Features

- 💬 Chatbot interface with Streamlit
- 🧠 Local LLM inference using **LLAMA2 via Ollama**
- 🧩 Modular chain setup using LangChain
- 🔐 `.env` support for secure environment configuration
- 🧾 Clean prompt templating with system/user separation

---

##  Tech Stack

| Component        | Tech Used                          |
|------------------|------------------------------------|
| Language Model   | LLAMA2 via Ollama (local)          |
| Orchestration    | LangChain                          |
| Interface        | Streamlit                          |
| Deployment       | Local / Cloud (optional)           |
| Environment Vars | dotenv (`.env`)                    |

---

##  Architecture

This app uses **LangChain's functional chaining** to create a natural conversation pipeline:

1. **PromptTemplate**: System and user roles defined.
2. **LLM Layer**: LLAMA2 model invoked via Ollama.
3. **Output Parser**: Raw output formatted into clean strings.
4. **Frontend**: User inputs handled via Streamlit.
