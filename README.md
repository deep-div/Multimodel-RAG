# Multimodal RAG for PDF Ingestion and Text-Image Output

This project implements a **Multimodal Retrieval-Augmented Generation (RAG)** system that ingests PDF documents and generates outputs containing both **text** and **images** extracted or referenced from the PDFs.

The code leverages two advanced frameworks for enhanced retrieval and embedding capabilities:

* **LangChain**: Utilizes a specialized architecture for PDF processing, optimized for handling document structure and content.
* **LlamaIndex**: Employs CLIP embeddings behind the scenes to enable powerful multimodal representation, especially for linking textual and visual content.

## Features

* Ingests PDF files and processes text and images contained within.
* Generates combined outputs with relevant text and images.
* Supports multimodal querying via Retrieval-Augmented Generation.
* Modular design using LangChain and LlamaIndex for flexible embedding and retrieval strategies.

