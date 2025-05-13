# LangChain Zero-to-Mastery

## 🧠 About

This repository is a hands-on, structured journey to mastering **LangChain**, the powerful framework for building LLM-driven applications. Each notebook in the series builds on the last — from fundamentals to advanced workflows like tool integration, workflow automation, and multi-agent systems.

## 📁 Structure

---

### 1. Introduction to LangChain [`1-Introduction-to-LangChain.ipynb`]

Learn what LangChain is and how to get started:

- Core concepts: Chains, Memory, Tools
- Setting up API keys (OpenAI, etc.)
- Building your first `LLMChain` with `PromptTemplate`

---

### 2. Chains and Memories [`2-Chains-Memories.ipynb`]

Master sequential logic and stateful memory:

- Chaining LLM outputs into multi-step logic
- Using `ConversationBufferMemory` for context-aware chatbots

---

### 3. Document Processing with RAG [`3-Document-Processing-with-RAG.ipynb`]

Build a Retrieval-Augmented Generation (RAG) pipeline:

- Split documents into chunks
- Create and query a vector store (e.g., FAISS + OpenAI Embeddings)
- Construct `RetrievalQA` systems for PDF Q&A

---

### 4. Custom Agents and Tool Integration [`4-Custom-Agents-and-Tool-Integration.ipynb`]

Go beyond chains with **LangChain Agents**:

- Build your own tools (functions)
- Create agents using `create_openai_functions_agent`
- Use structured prompts to guide agent behavior

---

### 5. Workflow Automation [`5-Workflow-Automation.ipynb`]

Automate multi-step processes using tools:

- Chain agents to simulate task pipelines
- Practical use cases: data cleaning, summarization, and content classification
- Error handling and control flow in agent-based tasks

---

### 6. Multi-Agent Systems [`6-MultiAgent-LangChain.ipynb`]

Design intelligent workflows using multiple specialized agents:

- Create distinct agents (Retriever, Summarizer, Synthesizer)
- Orchestrate collaboration between them
- Build reusable agent pipelines

---

### 7. Conversational State Machine with LangGraph [`7-LangGraph-Conversation-StateMachine.ipynb`]

This notebook introduces LangGraph through a **conversation-driven state machine**.

Key highlights:

- Defines a `StateGraph` with typed input/output.
- Classifies user input as a "question", "exit", or "unknown".
- Uses conditional edges and callable logic to route the state.
- Builds a dynamic agent that responds and gracefully exits.

It also includes an interactive chat loop using the compiled graph; a perfect stepping stone toward adaptive, multi-turn LLM agents.

---

## 🚧 Upcoming Topics

Stay tuned for:

- LangServe deployment examples
- Knowledge graphs
- Production-ready LangChain patterns

---

## 🤝 Contributions Welcome

Feel free to:

- Submit PRs to improve or extend notebooks
- Open issues with questions or suggestions
- Share your own use cases built with this repo

---

Happy building! 🚀
