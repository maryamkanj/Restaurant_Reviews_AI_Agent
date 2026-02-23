# 🍕 Restaurant Reviews AI Assistant

An AI-powered assistant that answers questions about pizza restaurants using **real customer reviews**, ensuring **factual, grounded responses with zero hallucinations**.

This project was built as a **learning project** to explore modern AI engineering concepts such as **Retrieval-Augmented Generation (RAG)**, **vector databases**, and **LLM orchestration**.

---

## 🚀 Project Overview

The Restaurant Reviews AI Assistant allows users to ask natural language questions about pizza restaurants and receive answers **directly grounded in real customer reviews**.

Instead of relying on generic model knowledge, the assistant retrieves relevant reviews and uses them as context to generate **accurate and trustworthy answers**.

---

## 🧠 Key Concepts Learned

This project was created for learning and hands-on practice with:

- Retrieval-Augmented Generation (RAG)
- Semantic Search using Embeddings
- Vector Databases
- Prompt Engineering
- LLM + Retriever Pipelines
- Context-grounded AI responses
- Building AI QA systems

---

## 🏗️ Tech Stack

- **LangChain** – for chaining prompts and retrieval pipelines
- **Chroma** – vector database for storing and querying embeddings
- **Ollama**
  - `mxbai-embed-large` – for generating embeddings
  - `llama3.2` – for generating grounded answers
- **Python** – core programming language

---

## ⚙️ How It Works

1. **Data Collection**
   - 100+ real pizza restaurant reviews are used as the knowledge base.

2. **Embedding**
   - Reviews are converted into semantic vectors using `OllamaEmbeddings`.

3. **Storage**
   - Embeddings are stored in **ChromaDB** for fast similarity search.

4. **Retrieval**
   - When a user asks a question, the system retrieves the most relevant reviews.

5. **Generation**
   - The LLM (`llama3.2`) generates an answer **using only the retrieved context**.

---

## 🎯 Features

- ✅ Answers grounded in real customer reviews  
- ✅ No hallucinated information  
- ✅ Fast semantic similarity search  
- ✅ Context-aware responses  
- ✅ Clean modular RAG pipeline  

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/restaurant-reviews-ai-assistant.git](https://github.com/maryamkanj/Restaurant_Reviews_AI_Agent.git
cd Restaurant_Reviews_AI_Agent
```
2. Create Virtual Environment
python -m venv .venv

Activate it:

Windows:

.venv\Scripts\activate

Mac/Linux:

source .venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
4. Run the App
python app.py
💡 Example Use Cases

Discover top-rated pizzas

Find kid-friendly menu options

Identify dietary-friendly choices

Analyze customer sentiment

⚠️ Disclaimer

This project is built strictly for learning purposes to practice AI engineering concepts and tools such as LangChain, vector databases, and local LLMs.

It is not intended for production use.
