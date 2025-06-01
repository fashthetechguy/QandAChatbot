
#  1. LLAMA3 Chatbot with LangChain & Streamlit

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



# 2. LangChain + OpenAI Chatbot Demo (Streamlit)

A minimal conversational AI application that integrates **LangChain**, **OpenAI GPT-3.5**, and **Streamlit** to deliver a simple, clean question-answering chatbot interface. This app uses structured prompt templates and an LLM pipeline to demonstrate basic LangChain chaining with OpenAI's models.

---

## ✨ Features

- 💬 Chat interface powered by GPT-3.5-turbo
- 🧠 Clean LangChain pipeline using prompt templates and parsers
- 🧾 Simple Streamlit UI for fast prototyping
- 🔐 `.env` file support for API key management
- 🧩 Easily extendable to RAG or other chains

---

## 🛠️ Tech Stack

| Component        | Technology                        |
|------------------|-----------------------------------|
| LLM Provider     | OpenAI (GPT-3.5-turbo)            |
| Framework        | LangChain                         |
| UI Framework     | Streamlit                         |
| Config Mgmt      | python-dotenv (`.env`)            |

---

## 🧩 Architecture

The app uses LangChain to create a simple 3-stage pipeline:

1. **Prompt Template** – System and user roles defined for structured LLM interaction.
2. **LLM Chain** – Uses OpenAI's GPT-3.5 for natural language responses.
3. **Output Parser** – Formats and parses the raw output.


