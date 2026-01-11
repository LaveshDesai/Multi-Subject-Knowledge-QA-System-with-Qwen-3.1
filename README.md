# 🏆 Huawei Tech Arena Hackathon Project  
**Top 10 Finalist out of 500+ Teams**

## 📌 Overview
This project was developed as part of the **Huawei Tech Arena Hackathon**, where our team secured a **Top 10 position among 500+ teams**. The solution focuses on building an **LLM-powered Question Answering system** that combines retrieval and generation to deliver accurate, context-aware responses.

---

## 🧠 Problem Statement
Your objective is to create an efficient Large Language Model (LLM) inference pipeline
for single-round question answering. Therefore, the pipeline does not need to retain
any conversational history. Common LLM inference optimization techniques include:
• Context and Orchestration - RAG, knowledge graphs, tools (e.g. calculators),
prompt engineering, etc.
• Deployment and Serving - specialized accelerators, asynchronous serving, prefix
and response caching, etc.
• Model Design - quantization, pruning, optimized attention mechanisms, token fusion,
model merging, low-rank factorization, etc.
The proposed solution will be assessed against the following performance metrics:
• Accuracy through an LLM-as-a-Judge
• End-to-End Latency

---

## ⚙️ Solution Architecture
The system follows a **Retrieval-Augmented Generation (RAG)** pipeline:
1. Retrieve relevant documents from a custom knowledge base using BM25.
2. Inject retrieved context into structured prompts.
3. Generate accurate answers using a Large Language Model.

---

## 🛠️ Tech Stack
- **Language:** Python
- **Framework:** PyTorch  
- **LLM & NLP:** Hugging Face Transformers, Qwen LLM  
- **Retrieval:** BM25 (rank_bm25)  
- **Techniques:**  
  - Retrieval-Augmented Generation (RAG)  
  - Prompt Engineering  
  - Few-Shot Learning  
  - Hyperparameter Tuning  
  - Chroma Database

---

## 🔍 Key Features
- Developed an **LLM-powered question-answering system** using Qwen LLM.
- Implemented **BM25-based retrieval** for relevant context extraction.
- Improved response relevance and consistency using **prompt engineering and few-shot structured inputs**.
- Optimized inference performance by tuning **temperature, top-k, top-p, and max token limits**.

---

## 📈 Performance Optimization
- Reduced hallucinations by grounding responses with retrieved knowledge.
- Balanced response quality and latency through controlled generation parameters.
- Ensured consistent and structured outputs across queries.

---

## 🏅 Hackathon Achievement
- **Event:** Huawei Tech Arena Hackathon,Dublin ,Ireland
- **Teams Participated:** 500+ 
- **Result:** Top 10 Finalist  

---

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="40" height="40"/>
  <img src="https://huggingface.co/front/assets/huggingface_logo.svg" width="40" height="40"/>
</p>

