# Generative AI Playbook 🚀

A comprehensive repository for mastering Generative AI—from mathematical foundations to production-grade agentic systems.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/kislayy)

---

## 📖 Philosophy
Most AI resources are either too theoretical (all math, no code) or too shallow (all APIs, no understanding). This playbook bridges that gap.

1.  **Understand the Math** (Foundations)
2.  **Build the Architecture** (From Scratch)
3.  **Implement the Pattern** (Tutorials)
4.  **Optimize for Users** (Production)

---

## 🗺️ Recommended Learning Paths

### 🚀 The "Hacker" Path (Build Apps Fast)
*Goal: Build functional AI applications as quickly as possible.*
1. **[Simple Conversational Agent](./02-all-tutorials/01-basics/simple_conversational_agent.ipynb)**
2. **[Simple Data Analysis Agent](./02-all-tutorials/01-basics/simple_data_analysis_agent.ipynb)**
3. **[Introduction to LangGraph](./02-all-tutorials/02-agentic-frameworks/langgraph_tutorial.ipynb)**

### 🧠 The "Core Engineer" Path (The Deep Dive)
*Goal: Understand the "Why" and build architectures from scratch.*
1. **[Foundations](./00-foundations/)** (Math & Python)
2. **[Attention from Scratch](./01-architectures/from-scratch/build-attention-from-scratch.ipynb)**
3. **[Transformer Architecture](./01-architectures/from-scratch/build-transformer.ipynb)**
4. **[Paper Summaries](./01-architectures/papers/)**

### 🛠️ The "Production" Path (LLMOps)
*Goal: Deploy, evaluate, and optimize AI systems for real users.*
1. **[Production & LLMOps](./03-production-llmops/)** (Cost, Caching, Quantization)
2. **[Evaluation](./03-production-llmops/evaluation.ipynb)**
3. **[Hallucination Debugging](./03-production-llmops/hallucination-debugging.ipynb)**

---

## 🛠️ Implementation Registry

| Category | Tutorial Name | Framework | Key Features |
| :--- | :--- | :--- | :--- |
| 🌱 **Beginner** | [Simple Conversational Agent](./02-all-tutorials/01-basics/simple_conversational_agent.ipynb) | LangChain | History management, Context-aware |
| 🌱 **Beginner** | [Simple Data Analysis](./02-all-tutorials/01-basics/simple_data_analysis_agent.ipynb) | LangChain | Natural language queries on CSVs |
| 🔧 **Framework** | [Introduction to LangGraph](./02-all-tutorials/02-agentic-frameworks/langgraph_tutorial.ipynb) | LangGraph | State management, Cyclic workflows |
| 🎓 **Educational** | [Academic Task System](./02-all-tutorials/04-industry-solutions/academic_task_learning_agent.ipynb) | LangGraph | Multi-agent academic planning |
| 💼 **Business** | [Customer Support Agent](./02-all-tutorials/04-industry-solutions/customer_support_agent.ipynb) | LangGraph | Sentiment analysis, Routing |
| 🎨 **Creative** | [GIF Animation Generator](./02-all-tutorials/05-creative-utility/gif_animation_generator.ipynb) | LangGraph | Text-to-animation pipeline |
| 📊 **Analysis** | [Self-Healing Codebase](./02-all-tutorials/03-advanced-patterns/self_healing_code.ipynb) | LangGraph | Automated error detection & fixes |
| 🔍 **QA** | [EU Green Deal Bot](./02-all-tutorials/04-industry-solutions/eu_green_compliance_bot.ipynb) | LangGraph | RAG-based regulatory compliance |
| 🌟 **Advanced** | [Multi-Agent Collaboration](./02-all-tutorials/03-advanced-patterns/multi_agent_collaboration.ipynb) | LangGraph | Research & Data teams working together |

---

## 📂 Repository Structure

### [00. Foundations](./00-foundations/)
The mathematical bedrock. Linear Algebra, Probability, and Calculus specifically for AI.

### [01. Architectures](./01-architectures/)
- **From Scratch:** Building GPT, Tokenizers, and Transformers with pure code.
- **Papers:** Deep dives into *Attention Is All You Need*, *LoRA*, *Mamba*, and more.

### [02. Agent Tutorials](./02-all-tutorials/)
Practical, ready-to-use implementations of modern AI Agent patterns.
- **[01. Basics](./02-all-tutorials/01-basics/):** Foundational QA and data analysis.
- **[02. Agentic Frameworks](./02-all-tutorials/02-agentic-frameworks/):** LangGraph, PydanticAI, Swarm, and AutoGen.
- **[03. Advanced Patterns](./02-all-tutorials/03-advanced-patterns/):** Memory, Self-healing, and Multi-agent systems.
- **[04. Industry Solutions](./02-all-tutorials/04-industry-solutions/):** HR, Legal, Healthcare, and E-commerce.
- **[05. Creative & Utility](./02-all-tutorials/05-creative-utility/):** Creative AI and productivity tools.

### [03. Production & LLMOps](./03-production-llmops/)
The "Last Mile" of AI: Caching, Quantization, Evaluation, and Cost Optimization.

---

## 🛠️ Setup
```bash
git clone https://github.com/iKislay/Generative-AI-Playbook.git
cd Generative-AI-Playbook
pip install -r requirements.txt
```

---

## 🤝 Credits
This project incorporates tutorials and patterns inspired by the excellent work in [NirDiamant/GenAI_Agents](https://github.com/NirDiamant/GenAI_Agents).

Created and maintained by **Kislay**.
- X (Twitter): [@whykislayy](https://x.com/whykislayy)
- LinkedIn: [kislayy](https://www.linkedin.com/in/kislayy)
