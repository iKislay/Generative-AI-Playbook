# Generative AI Playbook 🚀

A complete open-source journey from **beginner → expert** in Generative AI.

This repository is designed for people who want to go from **zero knowledge** to building production-grade AI systems. Most GenAI resources are either too theoretical or too code-heavy; this playbook balances both using a unique pedagogical approach.

## 🌟 Repository Philosophy: The "Why-to-How" Framework

Every chapter in this playbook follows a strict flow to ensure deep understanding:

**Concept** → **Visual Intuition** → **Math** → **Code** → **Build** → **Production** → **Research**

Every lesson helps you answer:
1. **What is this?** (Definition)
2. **Why is it needed?** (Motivation & Problem Statement)
3. **How does it work?** (Intuition, Math, Architecture)
4. **Code it!** (Implementation from scratch and using libraries)
5. **Real Project** (Practical application)
6. **Production Issues** (Latency, cost, scaling, hallucinations)

---

## 🛤️ Learning Paths

Choose your journey based on your goals:

### 🛠️ The Builder Path
*Focus: Speed to market, building applications, and integration.*
- **Outcome:** Build startups, internal tools, and AI features.
- **Key Modules:** Prompting → APIs → RAG → Agents → Deployment.
- **Skip:** Heavy math and training internals.

### ⚙️ The Engineer Path
*Focus: Understanding the "engine" and optimization.*
- **Outcome:** LLM Engineer / ML Engineer.
- **Key Modules:** Math → DL → Transformers → Fine-tuning → LLMOps.

### 🧪 The Research Path
*Focus: Pushing the boundaries and understanding fundamentals.*
- **Outcome:** AI Researcher / Core Model Developer.
- **Key Modules:** Advanced Math → Paper Implementation → Alignment → Training Dynamics.

---

## 📚 Chapters

### 0. Setup & Foundations
- [ ] [Environment Setup](./setup/environment.ipynb)
- [ ] [Python Refresher](./setup/python-refresher.ipynb)
- [ ] [GPU & Hardware Setup](./setup/gpu-setup.ipynb)
- [ ] [Python for AI](./00-foundations/01-python-for-ai.ipynb)
- [ ] [Linear Algebra](./00-foundations/02-linear-algebra.ipynb)
- [ ] [Probability](./00-foundations/03-probability.ipynb)
- [ ] [Statistics](./00-foundations/04-statistics.ipynb)
- [ ] [Calculus](./00-foundations/05-calculus.ipynb)

### 1. Machine Learning & Deep Learning
- [ ] Classical ML for NLP
- [ ] Neural Networks from Scratch
- [ ] Backpropagation & Optimization

### 2. NLP & Transformers
- [ ] Word Embeddings (Word2Vec, GloVe)
- [ ] RNNs & LSTMs (Why they failed)
- [ ] **Attention Mechanism (The Breakthrough)**
- [ ] Transformer Architecture (Encoder-Decoder)

### 3. Large Language Models (LLMs)
- [ ] BERT, GPT, T5
- [ ] Tokenization (BPE, SentencePiece)
- [ ] Decoding Strategies (Greedy, Beam, Top-K/P)

### 4. Applied GenAI (The "Stack")
- [ ] **Prompt Engineering:** Techniques & Versioning
- [ ] **RAG (Retrieval Augmented Generation):** Vector DBs, Chunking, Retrieval strategies
- [ ] **Agents:** Tool use, Reasoning (ReAct), Planning

### 5. Advanced Implementation
- [ ] **Fine-tuning:** PEFT, LoRA, QLoRA
- [ ] **Evaluation:** RAGAS, G-Eval, Human-in-the-loop
- [ ] **LLMOps:** Deployment, Quantization, Cost Optimization

---

## 🏗️ Progressive Projects

| Level | Project | Description |
| :--- | :--- | :--- |
| **Beginner** | Chatbot | Basic OpenAI/Anthropic API integration |
| **Beginner** | PDF Q&A | Simple RAG with LangChain/LlamaIndex |
| **Intermediate** | Meeting Summarizer | Audio-to-text with structured extraction |
| **Intermediate** | Docs AI | Technical documentation search engine |
| **Advanced** | Multi-Agent System | Autonomous team for software dev |
| **Expert** | Mini GPT | Train a small transformer on custom text |

---

## 🛠️ "From Scratch" Series
Master the internals by building them yourself:
- [Build a Tokenizer](./from-scratch/build-tokenizer-from-scratch.ipynb)
- [Build Attention Mechanism](./from-scratch/build-attention-from-scratch.ipynb)
- [Build a Transformer](./from-scratch/build-transformer.ipynb)
- [Build a Vector DB](./from-scratch/build-vector-db.ipynb)

---

## 📄 Paper Explainers
Deep dives into the research that changed the world:
- [Attention Is All You Need](./papers/attention-is-all-you-need.ipynb)
- [LoRA: Low-Rank Adaptation](./papers/lora.ipynb)
- [RAG Paper](./papers/rag-paper.ipynb)

---

## 🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
*Maintained with ❤️ by Kislay.*
