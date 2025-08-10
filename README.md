# 🧠 Agentic Graphs Practice

This repository contains my practice work for building **agent workflows** using **graphs** — a powerful approach to design modular, flexible, and reusable AI agent pipelines.  

## 📌 What are Agentic Graphs?
Agentic graphs represent **agents** and their **tasks** as interconnected nodes in a directed graph structure.  
- **Nodes** → Functions or agents that perform a specific operation.  
- **Edges** → Define the flow of data/state between nodes.  
- **State** → A shared structure (dictionary/class) that moves between nodes.  

By modeling an AI system as a graph:
- You can clearly define **order of execution**.
- Easily **add, remove, or replace** components.
- Run **parallel** or **conditional** paths.
- Debug more easily by visualizing each step.

---

## 🛠 Tech Stack
- **Python**
- **LangGraph** (for building agent graphs)
- **LangChain** (optional integration with LLMs)
- **Custom AgentState** classes for structured data flow

---

## 📂 Repository Structure
Agentic-graphs-practice/
│
├── examples/ # Example agent graph workflows
├── nodes/ # Custom node functions (math ops, API calls, etc.)
├── state/ # AgentState definitions
├── main.py # Entry point to run the graphs
└── README.md # This file
