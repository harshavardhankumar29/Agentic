# Agentic

A learning and development repository focused on building agentic workflows using **LangChain** and **LangGraph**.

## Repository Structure

The project is organized into structured notebooks covering various aspects of LLM integration and agent design:

### 🦜 [Langchain](file:///Users/harsha/Desktop/Agentic/Langchain)
Interactive notebooks demonstrating the foundations of the LangChain framework:
1. **Introduction to LangChain** (`1-langchainintro.ipynb`): Core concepts and initialization.
2. **Model Integration** (`2-modelintegration.ipynb`): Connecting, prompting, and querying different LLM providers.
3. **Tools** (`3-tools.ipynb`): Defining and binding custom tools/functions for models to call.
4. **Messages** (`4-messages.ipynb`): Handling conversation history, chat templates, and message structures.
5. **Structured Output** (`5-structuredoutput.ipynb`): Extracting typed JSON or Pydantic structures from models.
6. **Middleware & Custom Behavior** (`6-middleware.ipynb`): Hooking into callbacks, runnables, and custom chains.

### 🕸️ [Langgraph](file:///Users/harsha/Desktop/Agentic/Langgraph)
Advanced orchestration for stateful, multi-actor applications built on LangGraph:
- **Basic Chatbot** (`1-BasicChatbot/chatbot.ipynb`): Building a stateful, tool-using chatbot with message history.

---

## Getting Started

This repository uses **`uv`** as the package manager for fast and reproducible environments.

### 1. Installation
Ensure you have `uv` installed, then synchronize dependencies:
```bash
uv pip install -r requirements.txt
```

### 2. Environment Variables
Create a `.env` file in the root directory to store your API credentials:
```env
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
GOOGLE_API_KEY=your_gemini_key
TAVILY_API_KEY=your_tavily_key
LANGSMITH_API_KEY=your_langsmith_key
```
