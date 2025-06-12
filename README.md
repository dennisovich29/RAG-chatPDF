# RAG-chatPDF

# 📚 PDF Question Answering with Hugging Face + LangChain (Colab)

This Colab notebook enables you to:
1. Upload a PDF file.
2. Extract and chunk the text using `pdfminer`.
3. Convert the chunks into embeddings using Hugging Face (`all-MiniLM-L6-v2`).
4. Store them in a FAISS vector store.
5. Ask natural language questions about the PDF using the FLAN-T5 model.

---

## 🚀 Features

- ✅ Runs entirely in Google Colab
- 📄 Upload and extract PDF content
- ✂️ Smart chunking of text with overlap
- 🧠 Hugging Face Sentence Transformers for free embeddings
- 🔍 FAISS vector store for efficient retrieval
- 🤖 FLAN-T5-based Question Answering 

---

## 🧰 Requirements

Make sure the following Python packages are installed 

```bash
pip install langchain faiss-cpu sentence-transformers pdfminer.six transformers
