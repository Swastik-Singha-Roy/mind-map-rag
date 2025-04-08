# 📘 GraphRAG: Graph-based Retrieval-Augmented Generation using LangChain

GraphRAG is a powerful notebook implementation leveraging **LangChain**, **Neo4j**, and **LLMs** to perform **Retrieval-Augmented Generation (RAG)** with graph-based knowledge representation. This project enhances document understanding and querying by transforming PDF content into a semantic graph, enabling efficient reasoning and advanced search capabilities.

---

## 🚀 Features

- 📄 **PDF Ingestion** using `LangChain`'s `PyPDFLoader`
- ✂️ **Smart Text Chunking** with `RecursiveCharacterTextSplitter`
- 🧠 **Embedding Generation** using HuggingFace transformers
- 🗃️ **Knowledge Graph Creation** via `Neo4j`
- 🔎 **RAG Pipeline** with Graph-based semantic retrieval
- 📊 **Graph Visualization** using `yfiles_jupyter_graphs`

---

## 🛠️ Installation

Make sure to install the required libraries. The notebook installs them via Colab magic commands:

```bash
pip install --upgrade langchain langchain-community langchain-experimental
pip install --upgrade langchain-groq langchain-huggingface sentence-transformers
pip install --upgrade transformers neo4j tiktoken yfiles_jupyter_graphs pypdf
```

---

## 🧾 Usage

1. **Upload a PDF file** through the notebook's file upload prompt.
2. **Text is chunked**, embedded, and **indexed** for querying.
3. Data is used to **construct a knowledge graph** using Neo4j.
4. Graph reasoning + LLMs enable **contextual and connected answers**.

---

## 📂 Folder Structure

```
GraphRag.ipynb     <- Main Jupyter Notebook
requirements.txt   <- (Optional) Dependency list
README.md          <- Project overview and usage
```

---

## 🧠 Technologies Used

- **LangChain**
- **Neo4j**
- **HuggingFace Transformers**
- **Sentence Transformers**
- **Google Colab**
- **yFiles Graph Visualizer**

---

## 📌 Goals

- Enhance traditional RAG pipelines with **graph intelligence**
- Improve **multi-hop question answering** through graph traversal
- Demonstrate how unstructured data can be semantically structured

---

## 📎 License

MIT license
