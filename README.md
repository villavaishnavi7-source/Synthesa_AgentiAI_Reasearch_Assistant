# 🧠 Synthesa – Agentic AI Research Assistant

<img width="1600" height="639" alt="WhatsApp Image 2026-07-18 at 22 58 58" src="https://github.com/user-attachments/assets/de9effdf-d903-4f34-bb0e-b3f58de94867" />

---

# 🚀 Overview

**Synthesa** is an **Agentic AI Research Assistant** designed to make academic research faster, smarter, and more interactive.

Unlike conventional search engines that rely on keyword matching, Synthesa understands the semantic meaning of research queries, retrieves the most relevant research papers using vector similarity search, and employs a **Groq-powered AI agent** to provide intelligent explanations, summaries, keyword extraction, named entity recognition, and conversational assistance.

Synthesa bridges the gap between **Information Retrieval** and **Generative AI**, enabling users to interact naturally with research papers rather than simply searching for them.

---

# ✨ Key Features

## 🤖 Agentic AI Research Assistant

- AI Agent powered by **Groq**
- Llama 3.1 8B Instant model
- Natural language interaction
- Context-aware reasoning
- Conversational research assistance

---

## 🔍 Semantic Search

- Meaning-based paper retrieval
- Sentence Transformer embeddings
- Contextual similarity matching
- More accurate than keyword search

---

## ⚡ Vector Database Search

- FAISS vector indexing
- Lightning-fast similarity search
- Efficient retrieval across thousands of papers

---

## 📄 AI Paper Summaries

- Generates concise summaries
- Explains research in simpler language
- Highlights important findings

---

## 🏷 Named Entity Recognition (NER)

Automatically detects:

- People
- Organizations
- Technologies
- Datasets
- Models
- Research concepts

---

## 🔑 Keyword Extraction

Extracts important research topics from papers for quicker understanding.

---

## 💬 Conversational AI

Instead of searching using keywords, users can ask questions naturally such as:

> Explain Vision Transformers.

> Find recent papers on Medical AI.

> Summarize the best paper on Semantic Search.

---

## 🎯 Intelligent Recommendations

Synthesa combines semantic retrieval with LLM reasoning to recommend highly relevant papers based on user intent.

---

# 🏗 System Architecture

```text
                User Query
                     │
                     ▼
         Groq AI Agent (Llama 3.1)
                     │
                     ▼
        LangChain Agent Framework
                     │
                     ▼
      Semantic Search Retrieval Tool
                     │
                     ▼
Sentence Transformer Embeddings
                     │
                     ▼
           FAISS Vector Database
                     │
                     ▼
       Relevant Research Papers
                     │
                     ▼
      AI Analysis & Reasoning
                     │
                     ▼
     Intelligent Final Response
```

---

# ⚙ Workflow

1. Load research paper dataset.
2. Clean and preprocess text.
3. Generate semantic embeddings.
4. Store embeddings in FAISS.
5. User submits a natural language query.
6. AI agent invokes semantic retrieval.
7. Most relevant papers are retrieved.
8. Groq LLM analyzes retrieved context.
9. AI generates summaries, explanations, keywords, and insights.

---

# 🛠 Tech Stack

### Programming

- Python

### AI & LLM

- Groq API
- Llama 3.1 8B Instant
- LangChain

### NLP

- Sentence Transformers
- Hugging Face Transformers
- Named Entity Recognition
- Keyword Extraction
- Semantic Search

### Vector Database

- FAISS

### Data Processing

- Pandas
- NumPy
- Hugging Face Datasets

---

# 📂 Project Structure

```
Synthesa
│
├── Synthesa.ipynb
├── README.md
├── sample_output/

```

---
# 💬 Example Queries

Synthesa supports natural language interactions with research papers through its AI agent. Below are some example queries demonstrating its capabilities.

---

### 🔍 Query 1

**User Prompt**

> Find the top 3 research papers on Vision Transformers and summarize each of them.

**Sample Response**

```
Top 3 Relevant Papers

1. An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale
Similarity Score: 0.91

Summary:
Introduced the Vision Transformer (ViT), demonstrating that transformer architectures can outperform convolutional networks for image classification when trained on large-scale datasets.

----------------------------------------------------

2. Data-efficient Image Transformers (DeiT)
Similarity Score: 0.88

Summary:
Improves Vision Transformer training efficiency using knowledge distillation and reduced computational requirements.

----------------------------------------------------

3. Swin Transformer
Similarity Score: 0.86

Summary:
Introduces hierarchical vision transformers using shifted windows for efficient and scalable computer vision tasks.
```

---

### 🏷 Query 2

**User Prompt**

> Extract the top five keywords from research papers related to Deep Learning for Medical Image Reconstruction.

**Sample Response**

```
Top Keywords

• Deep Learning
• Medical Imaging
• MRI Reconstruction
• Image Restoration
• Convolutional Neural Networks

Detected Research Areas

✓ Computer Vision
✓ Medical AI
✓ Image Processing
```

---

### ⚖ Query 3

**User Prompt**

> Compare a research paper on Vision Transformers with a research paper on Convolutional Neural Networks.

**Sample Response**

| Feature | Vision Transformer | Convolutional Neural Network |
|---------|--------------------|------------------------------|
| Architecture | Transformer-based | Convolution-based |
| Data Requirement | Large datasets | Moderate datasets |
| Global Context | Excellent | Limited receptive field |
| Computational Cost | Higher | Lower |
| Performance | State-of-the-art on many benchmarks | Strong baseline for many tasks |

**AI Insight**

Vision Transformers generally achieve higher accuracy on large datasets due to their ability to model global relationships. CNNs remain computationally efficient and continue to perform exceptionally well when training data is limited.

---

### 🤖 Query 4

**User Prompt**

> Explain Vision Transformers in simple language.

**Sample Response**

```
Vision Transformers divide an image into small patches and process them similarly to words in a sentence. Instead of using convolution filters, they rely on self-attention mechanisms to understand relationships between different parts of the image, enabling them to capture global information effectively.
```

---

### 📄 Query 5

**User Prompt**

> Recommend research papers similar to "Attention Is All You Need".

**Sample Response**

```
Recommended Papers

1. BERT: Pre-training of Deep Bidirectional Transformers
Similarity Score: 0.90

2. GPT: Improving Language Understanding
Similarity Score: 0.88

3. Vision Transformer
Similarity Score: 0.86

Reason:
These papers build upon transformer architectures and extend self-attention mechanisms to different domains, including language understanding and computer vision.
```

---

# 💡 Why Synthesa?

Traditional research search engines return papers.

Synthesa goes beyond retrieval by understanding user intent, reasoning over retrieved papers, and generating intelligent responses through an AI agent.

Instead of simply finding research papers, Synthesa helps users understand, compare, and explore academic literature through natural conversation.

---

# 📈 Skills Demonstrated

- Agentic AI
- Large Language Models (LLMs)
- LangChain Agents
- Semantic Search
- Vector Databases
- Prompt Engineering
- Retrieval-Augmented AI
- Natural Language Processing
- Information Retrieval
- Generative AI

---

# 🌍 Applications

- Academic Research
- Literature Reviews
- Research Discovery
- AI-assisted Learning
- Knowledge Exploration
- Research Summarization
- Student Projects



---

# 👩‍💻 Author

**Vaishnavi Vashisht**





---

⭐ If you found this project interesting, consider giving it a star!# Synthesa_AgentiAI_Reasearch_Assistant
