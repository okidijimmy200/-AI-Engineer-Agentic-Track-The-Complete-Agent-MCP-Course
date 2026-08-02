# 🤖 Agentic AI Engineering: Build & Deploy Autonomous Agents

> **From Zero to Agentic AI Expert in 6 Weeks**  
> *21 hours • 8 Real-World Projects • 6 Major Frameworks*

[![Course Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/yourusername/agentic-ai-course)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg)](https://www.python.org/)
[![Made with](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/yourusername)

---

## 📚 Table of Contents

- [Course Overview](#-course-overview)
- [What You'll Build](#-what-youll-build)
- [Course Curriculum](#-course-curriculum)
- [Prerequisites](#-prerequisites)
- [Course Features](#-course-features)
- [Why This Course](#-why-this-course)
- [Who This Is For](#-who-this-is-for)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 📖 Course Overview

Welcome to the **Agentic AI Engineering** course — your comprehensive 6-week journey into the world of autonomous AI agents. This hands-on program is designed to transform you from an AI enthusiast into a proficient Agentic AI engineer capable of designing, building, and deploying production-ready autonomous agents that solve real-world problems.

### Course Details

| Aspect | Specification |
|--------|--------------|
| **Format** | 21 hours on-demand video • 132 lectures • 6 sections |
| **Duration** | 6-week intensive program |
| **Projects** | 8 real-world agentic applications |
| **Includes** | 1 article • Mobile & TV access • Closed captions • Certificate of completion |

---

## 🚀 What You'll Build

This course takes you from foundational concepts to advanced multi-agent systems through eight carefully designed projects:

| # | Project | Description | Framework/Tool |
|---|---------|-------------|----------------|
| 1 | **Career Digital Twin** | Build and deploy your own AI agent representing you to potential employers | n8n, OpenAI SDK |
| 2 | **SDR Agent** | Create Sales Representatives that craft and send professional emails | OpenAI Agents SDK |
| 3 | **Deep Research** | Build a team of agents that conduct extensive research on any topic | OpenAI Agents SDK |
| 4 | **Stock Picker** | Automate your search for investment opportunities | CrewAI |
| 5 | **Engineering Team** | Deploy a 4-agent team that manages, builds, and tests software | CrewAI, Docker |
| 6 | **Operator Agent** | Build your own version of OpenAI's Operator—a browser-sidekick | LangGraph |
| 7 | **Agent Creator** | Build an agent that creates and launches new agents | AutoGen |
| 8 | **Trading Floor** | 🏆 Deploy 4 agents making autonomous trades with 44 tools & 6 MCP servers | Multi-framework |

---

## 📋 Course Curriculum

### 🗓️ Week 1: Foundations of Agentic AI

Begin your journey by mastering the fundamentals. This week covers the essential concepts, environment setup, and your first interactions with LLMs and agents.

<details>
<summary><strong>Day 1: Introduction & Setup</strong></summary>

- Course roadmap and environment configuration
- UV package management, API keys setup
- Cross-platform installation (Windows & Mac)
- Your first OpenAI API call and chaining LLM calls
</details>

<details>
<summary><strong>Day 2: Agent Fundamentals</strong></summary>

- What defines an AI agent? Workflows vs. Agents
- Agentic design patterns: Chaining, Routing, Orchestrator
- Risks, guardrails, evaluations, and common pitfalls
</details>

<details>
<summary><strong>Day 3: LLM Landscape</strong></summary>

- Comparing providers: OpenAI, Claude, Gemini, Ollama, Groq
- Multi-LLM integration using OpenAI-compatible APIs
- Running local models with Ollama
- LLM-as-a-judge for ranking models
</details>

<details>
<summary><strong>Day 4: Building Your First Agent</strong></summary>

- Understanding the agent landscape: Frameworks, runtimes, tools
- How tool calling works in AI agents
- Build your Digital Twin: PDF reading & system prompts
- Create a chat UI with Gradio
- Build the agent loop from scratch with while-loop tool calling
</details>

<details>
<summary><strong>Day 5: Context Engineering</strong></summary>

- Memory, tools, and RAG for AI agents
- Adding Pushover notifications to your agent
- Multi-tool handling with the globals trick
- Refactoring into Python modules
- Deploying to Hugging Face Spaces
- Building visible agent loops with checklist tools
</details>

---

### 🗓️ Week 2: OpenAI Agents SDK – Deep Dive

Master the most popular agent framework through hands-on project development.

<details>
<summary><strong>Day 1: SDK Fundamentals</strong></summary>

- Async Python (asyncio) explained
- Core concepts: Agent, Trace, Runner.run
- Build your first agent
- Adding tools with `function_tool` decorator
- Memory management with sessions and SQLiteSession
</details>

<details>
<summary><strong>Day 2: Multi-Agent Orchestration</strong></summary>

- Build a multi-agent sales team
- Email sending tools for sales agents
- Orchestration by code vs. by LLM
- Three orchestration patterns: gather, tools, handoffs
</details>

<details>
<summary><strong>Day 3: Advanced SDK Features</strong></summary>

- Using any LLM (Gemini, Groq, and more)
- Structured outputs with Pydantic
- Guardrails, sandboxes, and MCP integration
</details>

<details>
<summary><strong>Day 4-5: Deep Research Project</strong></summary>

- Plan and build a web search agent
- Planner, Writer, and Email agents with structured outputs
- Full orchestrated research pipeline
- Deploy with Gradio UI to Hugging Face
</details>

---

### 🗓️ Week 3: CrewAI – Multi-Agent Collaboration

Learn CrewAI's powerful framework for building collaborative agent teams.

<details>
<summary><strong>Day 1: Framework Introduction</strong></summary>

- Crews, Flows, and the open-source framework
- Core concepts: Agents, Tasks, Crews, YAML configuration
- Installation and setup with uv
- Build your first debate crew
</details>

<details>
<summary><strong>Day 2-3: Building Financial Agents</strong></summary>

- The 5-step process for any CrewAI project
- Financial researcher crew with YAML, context, and tools
- Serper tool integration
- Stock picker with structured outputs and memory
- Custom tools and hierarchical processes
</details>

<details>
<summary><strong>Day 4-5: Engineering Team Project</strong></summary>

- Docker setup and sandbox tools
- Build a 4-agent engineering team
- Context7 MCP integration
- UV sandbox tools and multi-LLM orchestration
</details>

---

### 🗓️ Week 4: LangGraph & Agentic Workflows

Master LangChain's graph-based agent architecture.

<details>
<summary><strong>Day 1: LangChain Ecosystem</strong></summary>

- The four layers of LangChain
- ChatOpenAI, invoke, stream, and tool decorators
- Tool binding and structured outputs
</details>

<details>
<summary><strong>Day 2: LangGraph Fundamentals</strong></summary>

- Graphs, state, nodes, edges, and reducers
- Build your first graph with tool calling
- LangSmith, supersteps, and checkpoints
- Memory and time travel capabilities
</details>

<details>
<summary><strong>Day 3: Browser Automation</strong></summary>

- create_agent: The easy way
- Node.js and Playwright integration
- Web research agent with MCP
</details>

<details>
<summary><strong>Day 4-5: Deep Agents & Sidekick</strong></summary>

- Deep Agents for long-running tasks
- SKILL.md and progressive disclosure
- File system and to-do tools
- Human-in-the-loop workflows
- Gradio UI for your Sidekick agent
</details>

---

### 🗓️ Week 5: Multi-Framework Mastery

Explore the broader agent ecosystem and build a multi-framework project.

<details>
<summary><strong>Days 1-4: Framework Exploration</strong></summary>

- Google ADK and Agent Development Kit
- A2A Protocol and Agent Cards
- AWS Strands Agents with Bedrock
- Pydantic AI with structured outputs
- Microsoft Agent Framework, AutoGen, and Semantic Kernel
- Agno: The fast, lightweight framework
- Mastra: TypeScript-native agents
</details>

<details>
<summary><strong>Day 5: Multi-Agent Loop Project</strong></summary>

- Multi-framework agent architecture
- Orchestrator, QA, and CSS agents
- Parallel execution across six frameworks
</details>

---

### 🗓️ Week 6: MCP & Capstone Project

Master the Model Context Protocol and build your ultimate agent application.

<details>
<summary><strong>Day 1: MCP Fundamentals</strong></summary>

- Host, client, and server architecture
- Local vs. remote servers
- Node-based MCP servers
- Transport mechanisms
- Web-browsing agent with MCP
</details>

<details>
<summary><strong>Days 2-3: Building MCP Servers</strong></summary>

- When to build custom MCP servers
- Marketplaces and FastMCP
- Context engineering with MCP
- Long-term memory and web search
- Agentic RAG with Qdrant
- Market data and progressive disclosure
</details>

<details>
<summary><strong>Days 4-5: Capstone: Trading Floor</strong></summary>

- Build an autonomous trading floor
- Trader and researcher agents
- Researcher-as-tool pattern
- Gradio dashboard
- Observability, evaluation, and feedback
- FastAPI backend and React frontend
- Trace inspection and final challenge
</details>

---

## 🎯 Prerequisites

| Requirement | Details |
|-------------|---------|
| **Programming** | Python experience is ideal but not mandatory |
| **LLM Experience** | Some familiarity helpful but not required |
| **Patience** | ✅ The only hard requirement! |

> **📌 Note:** A full folder of self-study labs covers foundational technical and programming skills for beginners.

### 💰 API Budget

| Option | Details |
|--------|---------|
| **Minimum** | Complete the entire course with no API spend |
| **Recommended** | Typical spend under \$5 for frontier models |
| **Maximum** | Additional capabilities available at minimal cost |

---

## ✨ Course Features

- ✅ **21 hours** of comprehensive on-demand video content
- ✅ **8 real-world projects** with practical applications
- ✅ **Hands-on approach** with code-along instruction
- ✅ **Multiple frameworks**: OpenAI SDK, CrewAI, LangGraph, AutoGen, and more
- ✅ **Production deployment** to Hugging Face Spaces
- ✅ **MCP mastery** with server building and integration
- ✅ **Certificate of completion**
- ✅ Access on mobile, tablet, and TV
- ✅ Closed captions available

---

## 💡 Why This Course

> *"2026 is a watershed moment for AI Agents. It has never been more important to be an expert with Agentic AI."*

This intensive program will equip you with the skills and expertise to:

- 🎯 Design and build production-ready AI agents
- 🔧 Master all major agent frameworks
- ⚠️ Navigate the strengths and pitfalls of Agentic AI
- 🚀 Deploy autonomous agents for commercial applications
- 🤝 Build multi-agent systems for complex problem-solving

---

## 👥 Who This Is For

| Audience | Why This Course |
|----------|-----------------|
| **AI Engineers** | Specialize in agentic systems |
| **Developers** | Build autonomous applications |
| **Entrepreneurs** | Leverage AI for business automation |
| **Tech Enthusiasts** | Explore cutting-edge AI |
| **Students & Researchers** | Study the frontier of Agentic AI |

> *"Whether you're fascinated by the potential of Agents or hungry to create powerful Agentic AI – you've come to the right place."*

---

## 🗺️ Your Journey

```mermaid
graph LR
    W1[Week 1<br/>Foundations] --> W2[Week 2<br/>OpenAI SDK]
    W2 --> W3[Week 3<br/>CrewAI]
    W3 --> W4[Week 4<br/>LangGraph]
    W4 --> W5[Week 5<br/>Multi-Framework]
    W5 --> W6[Week 6<br/>MCP & Capstone]
