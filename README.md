# 🧠 Semantic Search Engine (Python)

## 📌 Project Overview

This project demonstrates a **Semantic Search Engine** using transformer-based embeddings.
Unlike traditional keyword search, this system understands the **meaning of text** and retrieves the most relevant results based on similarity.

---

## 🚀 Features

* 🔍 Semantic search using AI embeddings
* 🧠 Uses transformer model (`all-MiniLM-L6-v2`)
* 📊 Cosine similarity for ranking results
* 💻 Interactive command-line interface
* ⚡ Fast and lightweight (single file project)

---

## 🛠️ How to Run

### 1. Install dependencies

```bash
pip install sentence-transformers
```

### 2. Run the application

```bash
python app.py
```

### 3. Example usage

```
Enter your query: AI

Top matches:
1. AI in healthcare
2. How to learn AI
3. What is machine learning
```

---

## 🧠 How It Uses Vector Search Concepts

This project is based on **vector search (semantic search)** principles:

### 1. Text → Vector (Embeddings)

* Each sentence is converted into a numerical vector using a transformer model.
* These vectors capture the **semantic meaning** of the text.

### 2. Similarity Measurement

* The system uses **cosine similarity** to compare vectors.
* Higher similarity = more relevant result.

### 3. Retrieval

* All document vectors are compared with the query vector.
* The top matching results are returned.

---

## 🔍 Why Semantic Search?

Traditional search:

* Matches keywords ❌
* Fails on meaning ❌

Semantic search:

* Understands context ✅
* Finds related concepts ✅

Example:
Query: `AI`
→ Returns:

* "Machine learning"
* "Deep learning"
* "AI in healthcare"

---

## 🏆 Tech Stack

* Python
* Sentence Transformers
* NumPy

---

## 📌 Future Improvements

* 🌐 Web interface (Streamlit)
* ⚡ Faster search using FAISS / HNSW
* 🤖 RAG-based chatbot
* 📂 Load large datasets

---

## 👨‍💻 Author

Mathesh B

---

## ⭐ Conclusion

This project demonstrates how modern AI systems perform **meaning-based search using vector embeddings**, a core concept behind systems like ChatGPT, recommendation engines, and search platforms.
