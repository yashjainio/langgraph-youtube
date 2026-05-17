# **LangGraph Series**

Welcome to the **LangGraph Playlist** repository!  
This playlist is designed to help you understand LangGraph from the ground up — starting with basic graph concepts like nodes and edges, all the way to advanced topics like tool nodes, multi-agent systems, persistence, and human-in-the-loop workflows.  
Each video walks you through real, practical examples so you can build production‑ready AI applications using stateful, graph-based pipelines.

---

## 🐍 **Install Python Using Miniconda / Miniforge**

To keep your AI projects clean and organized, it is recommended to use **conda environments**. Follow the steps below to install Miniforge and set up your environment.

---

### 🔗 **Download Miniforge for macOS (ARM64)**

Download from the official repository:  
https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh

---

### 💻 **Install Miniforge**

Run the following commands:

```bash
chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh
sh ~/Downloads/Miniforge3-MacOSX-arm64.sh
source ~/miniforge3/bin/activate
```

---

### 🧱 **Create a project-specific conda environment**

```bash
conda create --prefix ./env python=3.13
conda activate ./env
```

---

### 📦 **Install packages from requirements.txt**

```bash
pip install -r requirements.txt
```

Your LangGraph environment is ready to build powerful AI apps 🚀

---

# **📺 Playlist Breakdown**

### **1. Basic Graph**

- Introduction to LangGraph fundamentals.
- Understanding **nodes**, **edges**, and **state** in a graph.

### **2. Sequential Graph**

- Building graphs where nodes execute **one after another**.
- Understanding how data flows through a linear pipeline.

### **3. Conditional Graph**

- Adding **conditional edges** to route execution based on state.
- Implementing dynamic decision-making within a graph.

### **4. Looping Graph**

- Creating graphs with **cycles and loops** for iterative processing.
- Understanding when and how to break out of loops.

### **5. Parallel Graph**

- Running multiple nodes **in parallel** to improve efficiency.
- Fan-out and fan-in patterns in LangGraph.

### **6. Reducers in Graph**

- Understanding **state reducers** to manage and merge state updates.
- Using custom reducers for complex state management.

### **7. LLM in Graph**

- Integrating a **Language Model** as a node inside the graph.
- Passing state context to and from the LLM.

### **8. LLM with Conditional in Graph**

- Combining **LLM calls with conditional routing** for smarter pipelines.
- Building graphs that adapt based on LLM output.

### **9. Multi-Turn Chatbot**

- Building a **conversational chatbot** using LangGraph state management.
- Maintaining context across multiple turns of a conversation.

### **10. Stream Response in Graph**

- Implementing **streaming responses** from LLMs inside a graph.
- Delivering real-time output to the user as tokens are generated.

### **11. Tool Node in Graph**

- Adding **tool nodes** that can call external functions and APIs.
- Connecting LangGraph with real-world capabilities.

### **12. Tool Node with LLM in Graph**

- Combining **LLM reasoning with tool execution** in a unified graph.
- Building an agent-like pipeline that decides when to use tools.

### **13. Persistence & Checkpoint Memory in Graph**

- Adding **checkpointing** to save and restore graph state.
- Enabling long-running and resumable workflows.

### **14. Human-in-the-Loop in Graph**

- Pausing graph execution to **incorporate human feedback**.
- Building workflows where humans can review, approve, or correct AI actions.

### **15. Subgraph in LangGraph**

- Composing complex systems using **nested subgraphs**.
- Encapsulating reusable graph logic into modular components.

### **16. Send API in Graph**

- Using LangGraph's **Send API** to dynamically dispatch messages to nodes.
- Enabling fine-grained control over node execution and state passing.

### **17. Multi-Agent in Graph**

- Orchestrating **multiple AI agents** within a single LangGraph system.
- Building collaborative agent networks for complex, multi-step tasks.

### **18. Agentic RAG in Graph**

- Implementing **Retrieval-Augmented Generation (RAG) inside a LangGraph agent**.
- Combining vector search, LLM reasoning, and graph state for intelligent document Q&A.

---

# **📄 requirements.txt**

```
langgraph
langchain
langchain-openai
langchain-core
python-dotenv
notebook
```

---

# **🤝 Contributing**

Got suggestions or improvements?  
Feel free to open an issue or submit a pull request.

---

# **📜 License**

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

---

# **📬 Stay Connected**

- [YouTube Channel](https://www.youtube.com/@yashjaincodex)
- [LinkedIn](https://www.linkedin.com/in/yashjaincodex)

---

Thank you for checking out the **LangGraph Playlist**!  
Happy building with AI 🚀
