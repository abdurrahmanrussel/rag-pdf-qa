# RAG-based PDF QA System

A **Retrieval-Augmented Generation (RAG)** system to answer questions from PDF documents using **LLaMA-2 4-bit** models, embeddings, and vector search.

---

## Features

- Extract text from PDFs using **OCR** (`PyPDF2`, `pytesseract`, `pdf2image`)  
- Chunk text for efficient retrieval using **LangChain**  
- Create embeddings with **Sentence-Transformers** and search with **FAISS**  
- Answer queries with a **4-bit LLaMA-2 model** and optional LoRA adapters  
- Supports multi-page PDFs and complex queries  

---

## Screenshots

**1. Upload PDFs and text extraction:**  
![Upload PDFs](images/upload_pdf.png)  

**2. Question & Ans:**  
![Question & Ans](images/a&a_1.png)  

**3. Question and Ans part 2**  
![Generated Answer](images/a&a_2.png)  

---



