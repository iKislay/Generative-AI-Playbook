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

## 📂 Repository Structure

### [00. Foundations](./00-foundations/)
The mathematical bedrock. Linear Algebra, Probability, and Calculus specifically for AI.

### [01. Architectures](./01-architectures/)
- **[From Scratch](./01-architectures/from-scratch/):** Building GPT, Tokenizers, and Transformers with pure code.
- **[Papers](./01-architectures/papers/):** Deep dives into *Attention Is All You Need*, *LoRA*, *Mamba*, and more.

### [02. Agent Tutorials](./02-all-tutorials/)
Practical, ready-to-use implementations of modern AI Agent patterns using LangGraph, CrewAI, and AutoGen.

### [03. Production & LLMOps](./03-production-llmops/)
The "Last Mile" of AI: Caching, Quantization, Evaluation, and Cost Optimization.

---

## 🛠️ Full Implementation Registry

| # | Category | Agent Name | Framework | Key Features |
|:---|:---|:---|:---|:---|
| 1 | 🌱 **Beginner** | [Simple Conversational Agent](./02-all-tutorials/01-basics/simple_conversational_agent.ipynb) | LangChain | Context-aware, history management |
| 2 | 🌱 **Beginner** | [Simple Question Answering](./02-all-tutorials/01-basics/simple_question_answering_agent.ipynb) | LangChain | Query understanding, concise answers |
| 3 | 🌱 **Beginner** | [Simple Data Analysis](./02-all-tutorials/01-basics/simple_data_analysis_agent.ipynb) | LangChain | Dataset interpretation, NL queries |
| 4 | 🔧 **Framework** | [Introduction to LangGraph](./02-all-tutorials/02-agentic-frameworks/langgraph_tutorial.ipynb) | LangGraph | Modular AI workflows, state management |
| 5 | 🔧 **Framework** | [Model Context Protocol (MCP)](./02-all-tutorials/02-agentic-frameworks/mcp_tutorial.ipynb) | MCP | AI-external resource integration |
| 6 | 🎓 **Educational** | [ATLAS: Academic Task System](./02-all-tutorials/04-industry-solutions/academic_task_learning_agent.ipynb) | LangGraph | Multi-agent academic planning |
| 7 | 🎓 **Educational** | [Scientific Paper Agent](./02-all-tutorials/04-industry-solutions/scientific_paper_agent.ipynb) | LangGraph | Literature review automation |
| 8 | 🎓 **Educational** | [Chiron - Learning Agent](./02-all-tutorials/04-industry-solutions/chiron_learning_agent.ipynb) | LangGraph | Adaptive learning, Feynman method |
| 9 | 💼 **Business** | [Customer Support Agent](./02-all-tutorials/04-industry-solutions/customer_support_agent.ipynb) | LangGraph | Query categorization, sentiment analysis |
| 10 | 💼 **Business** | [Essay Grading Agent](./02-all-tutorials/04-industry-solutions/essay_grading_system.ipynb) | LangGraph | Automated grading, multiple criteria |
| 11 | 💼 **Business** | [Travel Planning Agent](./02-all-tutorials/01-basics/simple_travel_planner.ipynb) | LangGraph | Personalized itineraries |
| 12 | 💼 **Business** | [GenAI Career Assistant](./02-all-tutorials/04-industry-solutions/career_assistant_agent.ipynb) | LangGraph | Career guidance, learning paths |
| 13 | 💼 **Business** | [Project Manager Assistant](./02-all-tutorials/05-creative-utility/project_manager_assistant.ipynb) | LangGraph | Task generation, risk assessment |
| 14 | 💼 **Business** | [Contract Analysis Assistant](./02-all-tutorials/04-industry-solutions/clause_ai.ipynb) | LangGraph | Clause analysis, compliance checking |
| 15 | 💼 **Business** | [E2E Testing Agent](./02-all-tutorials/03-advanced-patterns/e2e_testing_agent.ipynb) | LangGraph | Test automation, browser control |
| 16 | 🎨 **Creative** | [GIF Animation Generator](./02-all-tutorials/05-creative-utility/gif_animation_generator.ipynb) | LangGraph | Text-to-animation pipeline |
| 17 | 🎨 **Creative** | [TTS Poem Generator](./02-all-tutorials/05-creative-utility/tts_poem_generator.ipynb) | LangGraph | Text classification, speech synthesis |
| 18 | 🎨 **Creative** | [Music Compositor](./02-all-tutorials/05-creative-utility/music_compositor.ipynb) | LangGraph | AI music composition |
| 19 | 🎨 **Creative** | [Content Intelligence](./02-all-tutorials/04-industry-solutions/content_intelligence.ipynb) | LangGraph | Multi-platform content generation |
| 20 | 🎨 **Creative** | [Business Meme Generator](./02-all-tutorials/05-creative-utility/business_meme_generator.ipynb) | LangGraph | Brand-aligned meme creation |
| 21 | 🎨 **Creative** | [Murder Mystery Game](./02-all-tutorials/05-creative-utility/murder_mystery_game.ipynb) | LangGraph | Procedural story generation |
| 22 | 📊 **Analysis** | [Memory-Enhanced Conversational](./02-all-tutorials/03-advanced-patterns/memory_enhanced_agent.ipynb) | LangChain | Short/long-term memory |
| 23 | 📊 **Analysis** | [Multi-Agent Collaboration](./02-all-tutorials/03-advanced-patterns/multi_agent_collaboration.ipynb) | LangChain | Historical research, data analysis |
| 24 | 📊 **Analysis** | [Self-Improving Agent](./02-all-tutorials/03-advanced-patterns/self_improving_agent.ipynb) | LangChain | Learning from interactions |
| 25 | 📊 **Analysis** | [Task-Oriented Agent](./02-all-tutorials/03-advanced-patterns/task_oriented_agent.ipynb) | LangChain | Text summarization, translation |
| 26 | 📊 **Analysis** | [Internet Search Agent](./02-all-tutorials/05-creative-utility/web_search_summarizer.ipynb) | LangChain | Web research, summarization |
| 27 | 📊 **Analysis** | [Research Team - Autogen](./02-all-tutorials/02-agentic-frameworks/research_team_autogen.ipynb) | AutoGen | Multi-agent research collaboration |
| 28 | 📊 **Analysis** | [Sales Call Analyzer](./02-all-tutorials/04-industry-solutions/sales_call_analyzer.ipynb) | LangGraph | Audio transcription, NLP analysis |
| 29 | 📊 **Analysis** | [Weather Emergency System](./02-all-tutorials/04-industry-solutions/weather_disaster_management.ipynb) | LangGraph | Real-time data processing |
| 30 | 📊 **Analysis** | [Self-Healing Codebase](./02-all-tutorials/03-advanced-patterns/self_healing_code.ipynb) | LangGraph | Error detection, automated fixes |
| 31 | 📊 **Analysis** | [DataScribe](./02-all-tutorials/03-advanced-patterns/database_discovery_fleet.ipynb) | LangGraph | Schema exploration, query planning |
| 32 | 📊 **Analysis** | [Memory-Enhanced Email](./02-all-tutorials/02-agentic-frameworks/memory_agent_tutorial.ipynb) | LangGraph | Email triage, response generation |
| 33 | 📰 **News** | [News TL;DR](./02-all-tutorials/05-creative-utility/news_tldr.ipynb) | LangGraph | News summarization, API integration |
| 34 | 📰 **News** | [AInsight](./02-all-tutorials/04-industry-solutions/ainsight_analytics.ipynb) | LangGraph | AI/ML news aggregation |
| 35 | 📰 **News** | [Journalism Assistant](./02-all-tutorials/04-industry-solutions/journalism_ai_assistant.ipynb) | LangGraph | Fact-checking, bias detection |
| 36 | 📰 **News** | [Blog Writer](./02-all-tutorials/02-agentic-frameworks/blog_writer_swarm.ipynb) | OpenAI Swarm | Collaborative content creation |
| 37 | 📰 **News** | [Podcast Generator](./02-all-tutorials/05-creative-utility/podcast_generator.ipynb) | LangGraph | Content search, audio generation |
| 38 | 🛍️ **Shopping** | [ShopGenie](./02-all-tutorials/04-industry-solutions/shop_genie.ipynb) | LangGraph | Product comparison, recommendations |
| 39 | 🛍️ **Shopping** | [Car Buyer Agent](./02-all-tutorials/04-industry-solutions/car_buyer_agent.ipynb) | LangGraph | Web scraping, decision support |
| 40 | 🎯 **Task Management** | [Taskifier](./02-all-tutorials/03-advanced-patterns/taskifier.ipynb) | LangGraph | Work style analysis, task breakdown |
| 41 | 🎯 **Task Management** | [Grocery Management](./02-all-tutorials/04-industry-solutions/grocery_management_system.ipynb) | CrewAI | Inventory tracking, recipe suggestions |
| 42 | 🔍 **QA** | [LangGraph Inspector](./02-all-tutorials/03-advanced-patterns/graph_inspector_system.ipynb) | LangGraph | System testing, vulnerability detection |
| 43 | 🔍 **QA** | [EU Green Deal Bot](./02-all-tutorials/04-industry-solutions/eu_green_compliance_bot.ipynb) | LangGraph | Regulatory compliance, FAQ system |
| 44 | 🔍 **QA** | [Systematic Review](./02-all-tutorials/04-industry-solutions/scientific_article_review.ipynb) | LangGraph | Academic paper processing |

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
