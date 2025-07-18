# 📊 **Stock Trading Agent Simulation using LangGraph + LangSmith**

## 🚀 Overview
Meet my **Agentic AI Stock Trader** 🤖💹 — a project that brings together **autonomy**, **safety**, and **human oversight** in one smart agent!  
Using **LangGraph** & **LangSmith**, this simulation demonstrates:  
- 🔄 **Graph-based stateful orchestration** for complex agent workflows  
- 🛠️ **Tool-augmented reasoning** to fetch **real-time stock prices** (MSFT example)  
- 👨‍⚖️ **Human-in-the-loop (HITL)** buy/sell approvals — you’re always in control  
- 🧠 **Memory-enabled** adaptive decision-making  
- 🔍 **LangSmith tracing** to peek inside your agent’s reasoning, step by step  

---

## ✨ **Key Features**
- 📡 **Real-time Stock Price Checker** — Fetches the latest MSFT stock price on demand  
- 🧠 **Decision Planner** — Smartly decides whether to **Buy** 🟢 or **Hold** ⏸  
- ⏸️ **Human Approval Flow** — Uses `interrupt` & `command` to pause for your ✅/❌  
- 🧩 **Stateful Graph Nodes** — Each node mutates a shared agent state across steps  
- 🔬 **LangSmith Tracing** — See your agent’s reasoning in action with full transparency  

---

## 🛠 **Tech Stack**
- **LangGraph** – 📊 Graph-based AI agent framework for building stateful, reliable agents  
- **LangSmith** – 🧪 Real-time tracing, debugging, and monitoring of agent flows  
- **Python** – 💻 Command/resume orchestration logic  
- **LLM + Memory + Tool Use** – 🧠 Context-aware decision-making  
- **HITL** – 🧑‍💼 Human-in-the-loop approvals for safe autonomous execution  

---

## 🧭 **How It Works**
1. **Agent checks MSFT stock price** 📈 using a connected tool.
2. **Plans a trading action** — Buy 🟢 or Hold ⏸ — based on memory and reasoning.
3. **Pauses for your input** ⏸️ → waits for human approval via `command("yes")` or `command("no")`.
4. **Executes the action** if approved ✅ and updates its state.
5. **LangSmith tracing** gives you a **step-by-step “thought log”** of your agent’s reasoning.

---
