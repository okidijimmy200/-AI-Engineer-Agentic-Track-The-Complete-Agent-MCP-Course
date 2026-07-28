# 1.1 What is Agentic AI?
Agentic AI refers to AI systems that can do more than generate responses.

A normal chatbot receives a question and returns an answer. An AI agent, by contrast, can take actions, make decisions, and execute multi-step workflows to accomplish a goal.

> **Definition:** An AI agent is an LLM called in a loop with tools to achieve a goal.

---

# 1.2 Course Introduction
Welcome to Week 1, Day 1 of the **AI Engineer Agentic Track** — the complete Agent and MCP course.

Over six weeks, we'll build eight projects together. This is the second recording of the material, updated with the latest models and techniques.

*We skip introductions and dive straight into building.*

---

# 1.3 Building Your First Agent (n8n Demo)
We use n8n, a low-code platform, for a visual demo. The course itself uses code, but this provides intuition.

### 1.3.1 Setup
1. Go to [n8n.io](https://n8n.io)
2. Click **"Get Started"** (personal email works)
3. Complete verification and start free 14-day trial
4. Create workflow from scratch

### 1.3.2 Agent Components
An agent requires three things:

| Component | Description |
| :--- | :--- |
| **Model** | LLM (OpenAI, Gemini, OpenRouter) |
| **Memory** | Context retention across interactions |
| **Tools** | External capabilities the agent can use |

### 1.3.3 Adding Tools
* **MarketStack (Stock Prices)**
  * Fetches real-time stock data
  * Free tier: ~100 lookups/month
  * Setup: API key from [marketstack.com](https://marketstack.com)
* **Google Sheets Tools**
  * **Read:** Retrieves portfolio data
  * **Write:** Appends new rows to spreadsheet

### 1.3.4 Autonomy Demo
#### Portfolio (Google Sheet):

| Ticker | Shares |
| :--- | :--- |
| Amazon | 10 |
| Apple | 2 |

#### Interaction 1
```text
User: "What's the value of my stock portfolio?"
Agent: Reads sheet → Fetches prices → Calculates total → Returns result
```

#### Interaction 2
```text
User: "Suggest an investment to balance my portfolio. Add to my sheet. You decide ticker and shares."
Agent: Analyzes portfolio → Chooses SPY (1 share) → Updates sheet → Explains reasoning
```

#### Interaction 3
```text
User: "Add something defensive."
Agent: Chooses BND (2 shares) → Updates sheet autonomously
```

---

# 1.4 Key Takeaways

| Concept | Meaning |
| :--- | :--- |
| **Agent** | LLM + loop + tools |
| **Tool** | External function an agent calls (API, spreadsheet, etc.) |
| **Autonomy** | Agent makes decisions independently |

---

# 1.5 What's Next
The demo gives visual understanding. The rest of this course builds agents through code.

**Practice:** Spend 20 minutes exploring n8n integrations on your own.
