 
# 📄 Multimodal RAG for PDF Ingestion and Text-Image Output 

This project implements a **Multimodal Retrieval-Augmented Generation (RAG)** system that ingests PDF documents and generates outputs containing both **text** and **images** extracted or referenced from the PDFs.

The code leverages two advanced frameworks for enhanced retrieval and embedding capabilities:

* **LangChain**: Utilizes a specialized architecture for PDF processing, optimized for handling document structure and content.
* **LlamaIndex**: Employs CLIP embeddings behind the scenes to enable powerful multimodal representation, especially for linking textual and visual content.

---

## ✨ Features

* Ingests PDF files and processes both textual and visual content.
* Generates outputs containing relevant **text and images** from the source.
* Supports **multimodal querying** via Retrieval-Augmented Generation.
* Modular design built on **LangChain** and **LlamaIndex**, allowing flexible embedding and retrieval strategies.

---

## ⚙️ Working

* **`main.ipynb`**: A complete and direct implementation of the **Multimodal RAG** pipeline using both text and image extraction logic. Use this notebook to quickly test the full workflow end-to-end.

* **`tutorials/` folder**:

  * Contains two subfolders: `langchain/` and `llamaindex/`.
  * Both subfolders showcase **independent implementations** of the same task using different frameworks and methodologies:

    * `langchain/`: Demonstrates how to use LangChain for document ingestion and multimodal retrieval. Also includes examples of integrating **models like Mistral** for generation tasks.
    * `llamaindex/`: Uses LlamaIndex's CLIP-based embeddings for connecting text and image content across the PDF.

---

Let me know if you'd like to add installation instructions, model dependencies, or example outputs next.
