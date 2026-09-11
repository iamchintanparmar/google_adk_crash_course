# 🚀 Google ADK Crash Course

A comprehensive, hands-on tutorial series for learning **Google's Agent Development Kit (ADK)** — from your first agent to advanced multi-agent systems. This crash course takes you from zero to hero in building production-ready AI agents.

> **📌 Note:** This course has been updated for the new **Gemini 3 Flash** model. All tutorials use `gemini-3-flash-preview` unless otherwise noted.

---

## 📖 What is Google ADK?

Google ADK (Agent Development Kit) is a flexible, modular framework for **developing and deploying AI agents**. It's optimized for Gemini and the broader Google ecosystem, but it's **model-agnostic** and **deployment-agnostic** — meaning it plays nicely with other frameworks and LLM providers too.

### ✨ Key Features

| Feature | Description |
|---|---|
| **Flexible Orchestration** | Define workflows using workflow agents or LLM-driven dynamic routing |
| **Multi-Agent Architecture** | Build modular applications composed of multiple specialized agents |
| **Rich Tool Ecosystem** | Use pre-built tools, write custom functions, or integrate 3rd-party libraries |
| **Deployment Ready** | Containerize and deploy agents anywhere |
| **Built-in Evaluation** | Systematically assess agent performance |
| **Safety & Security** | Built-in patterns for trustworthy, guardrailed agents |

---

## 🗺️ Learning Path

| # | Tutorial | Covers |
|---|---|---|
| 1 | **Starter Agent** | Basic agent creation, the ADK workflow, simple text processing |
| 2 | **Model-Agnostic Agent** | 2.1 OpenAI integration · 2.2 Anthropic Claude integration |
| 3 | **Structured Output Agent** | 3.1 Customer support tickets (Pydantic) · 3.2 Email agent with data validation |
| 4 | **Tool-Using Agent** | 4.1 Built-in tools (search, code execution) · 4.2 Custom function tools · 4.3 Third-party tools (LangChain, CrewAI) · 4.4 MCP tools |
| 5 | **Memory Agent** | 5.1 In-memory conversation · 5.2 Persistent conversation (SQLite) |
| 6 | **Callbacks** | 6.1 Agent lifecycle · 6.2 LLM interaction · 6.3 Tool execution |
| 7 | **Plugins** | Global callback management, request/response modification, error handling, usage analytics |
| 8 | **Simple Multi-Agent** | 8.1 Multi-agent researcher — coordinator + sub-agents, sequential Research → Summarize → Critique pipeline with web search |
| 9 | **Multi-Agent Patterns** | 9.1 Sequential agent (Draft → Critique → Improve) · 9.2 Loop agent (iterative refinement with a stop condition) · 9.3 Parallel agent (concurrent sub-agents, merged results) |

---

## ✅ Prerequisites

- **Python 3.11+**
- **Google AI API Key**
- Basic familiarity with Python and APIs

---

## 📂 Tutorial Structure

Each tutorial folder follows a consistent layout:

```
tutorial_name/
├── README.md          # Concept explanation and learning objectives
├── agent.py           # Agent implementation + Streamlit app
└── requirements.txt   # Dependencies for the tutorial
```

## 🧭 How to Use This Course

1. **Read** the tutorial's README to understand the concept
2. **Examine** the code to see how it's implemented
3. **Run** the example to see it in action
4. **Experiment** by modifying the code yourself
5. **Move on** to the next tutorial when you're ready

---

## 🎯 What Every Tutorial Includes

- Clear concept explanations
- Minimal, working code examples
- Real-world use cases
- Step-by-step instructions
- Best practices and practical tips

---

## 🏁 Getting Started

```bash
# Clone the repository
git clone https://github.com/iamchintanparmar/google_adk_course-main
cd google-adk-course-main

# Set up a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies for a tutorial
cd 1_starter_agent
pip install -r requirements.txt

# Set your API key
export GOOGLE_API_KEY="your-api-key-here"

# Run the tutorial
streamlit run agent.py
```

---

## 🤝 Contributing

Found an issue or have an idea for a new tutorial? Contributions are welcome — feel free to open an issue or submit a pull request.

## 📄 License

Add your license information here.


## Author 

chintan parmar
