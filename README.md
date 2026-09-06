# 🦜 LangChain & LangGraph Basics

A collection of my **LangChain and LangGraph learning journey, experiments, and practical examples**.

This repository covers the fundamentals of building **LLM-powered applications, workflows, and AI agents**, starting from the basics and gradually moving toward more advanced LangGraph architectures.

---

## 🚀 What's Inside?

* 🦜 LangChain Basics
* 🤖 LLM Integration
* 💬 Prompt Templates
* 🔗 Chains & Runnables
* 📤 Structured Outputs
* 🛠️ Tools
* 🧠 Embeddings
* 📚 Document Loaders
* 🔍 Retrievers
* 🗄️ Vector Stores
* 🧩 RAG Basics
* 🕸️ LangGraph Basics
* 🔄 Graph-based Workflows
* 💾 State Management
* 🤖 Agent Workflows
* 🧪 Experiments with Different LLMs

---

## 🗂️ Repository Structure

```text
LangChain-LangGraph-Basics/
│
├── langchain/
│   ├── llms/
│   ├── prompts/
│   ├── chains/
│   ├── runnables/
│   ├── tools/
│   ├── structured_output/
│   ├── embeddings/
│   ├── document_loaders/
│   └── retrievers/
│
├── rag/
│   ├── ingestion/
│   ├── chunking/
│   ├── embeddings/
│   ├── vectorstores/
│   └── retrieval/
│
├── langgraph/
│   ├── state/
│   ├── nodes/
│   ├── edges/
│   ├── workflows/
│   └── agents/
│
├── projects/
│   └── ...
│
├── requirements.txt
├── .env.example
└── README.md
```

---

## 🧰 Tech Stack

* **Python**
* **LangChain**
* **LangGraph**
* **LangChain Community**
* **LangChain Integrations**
* **LLMs**
* **Pydantic**
* **Vector Databases**
* **RAG**

---

## 🦜 LangChain

The LangChain section focuses on the building blocks used to create LLM applications.

Topics include:

```text
LLM
 ↓
Prompt
 ↓
Runnable
 ↓
Chain
 ↓
Tool
 ↓
Retriever
 ↓
RAG Application
```

---

## 🕸️ LangGraph

LangGraph is used to build more **stateful and controllable AI workflows**.

The basic idea:

```text
             ┌──────────────┐
             │    START     │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │     Node     │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │    State     │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │ Conditional  │
             │     Edge     │
             └──────┬───────┘
                ┌───┴───┐
                ↓       ↓
             Node A   Node B
                │       │
                └───┬───┘
                    ↓
                   END
```

---

## 🧠 Concepts I'm Exploring

### LangChain

* Chat Models
* Prompt Templates
* Messages
* Runnables
* LCEL
* Chains
* Tools
* Output Parsers
* Structured Outputs
* Embeddings
* Retrievers
* Vector Stores
* RAG

### LangGraph

* State
* Nodes
* Edges
* Conditional Edges
* Graphs
* Checkpoints
* Memory
* Human-in-the-loop
* Agentic Workflows
* Multi-step Reasoning

---

## 🔥 Example Workflow

A simple LangGraph agent can follow:

```text
User Input
    ↓
Understand Request
    ↓
Decide Action
    ↓
┌───────────────┐
│ Need a Tool?  │
└───────┬───────┘
        │
    ┌───┴───┐
   YES      NO
    ↓        ↓
  Tool     Answer
    ↓
 Process Result
    ↓
  Generate
   Answer
```

---

## 📚 RAG

This repository also explores the fundamentals of **Retrieval-Augmented Generation**:

```text
Documents
    ↓
Load
    ↓
Split / Chunk
    ↓
Embeddings
    ↓
Vector Store
    ↓
Retriever
    ↓
Relevant Context
    ↓
LLM
    ↓
Answer
```

---

## 🔐 Environment Variables

Create a `.env` file and add the API keys required by each example.

Example:

```env
OPENAI_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
```

> Never commit your `.env` file or API keys to GitHub.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/langchain-langgraph-basics.git
cd langchain-langgraph-basics
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running Examples

Most examples can be executed directly:

```bash
python filename.py
```

For LangGraph examples, check the corresponding folder for the specific entry point and configuration.

---

## 📈 Learning Roadmap

```text
Python
  ↓
LLMs
  ↓
LangChain Basics
  ↓
Runnables & LCEL
  ↓
Tools
  ↓
Embeddings & Vector Stores
  ↓
RAG
  ↓
LangGraph
  ↓
Stateful Workflows
  ↓
Agents
  ↓
Advanced Agentic Systems
```

---

## 🎯 Goal

The goal of this repository is to **learn by building**.

I'm using LangChain and LangGraph to understand how modern LLM applications are designed, how different components communicate, and how simple chains can evolve into **stateful, tool-using, agentic workflows**.

---

## 📌 Status

🚧 **Actively developing**

This repository will continue to grow as I explore more concepts, experiments, and real-world AI applications.

---

## 👨‍💻 Author

**Bishoy Amgad**

Computer Science Student | AI & Machine Learning Enthusiast

---

⭐ If you find something useful here, feel free to star the repository.
