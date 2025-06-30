# 📄 PDFQ&A — Intelligent PDF Assistant with Local LLM

Ask natural language questions about your PDF files — locally, privately, and intelligently. This project combines a local Large Language Model (LLM), semantic search with FAISS, and a clean Streamlit interface. It’s built to scale far beyond Q&A: multilingual support, summarization, style adaptation, and more.

---

## 🚀 Features (Phase 1 MVP)

✅ Upload any PDF file  
✅ Extract and split the text into chunks  
✅ Embed text using `sentence-transformers`  
✅ Build semantic search with `FAISS`  
✅ Ask a question → retrieve relevant chunks → get an answer from a local LLM (Mistral via Ollama)  
✅ Streamlit-based user interface  
✅ Fully offline, private, and free

---

## 🧭 Planned Additions (Coming Soon)

- [ ] PDF summarization (auto-executive summary)
- [ ] Multilingual detection and interaction (FR/EN)
- [ ] Highlighting answers in context
- [ ] Multi-PDF support
- [ ] Multi-turn conversation memory
- [ ] Response style adaptation (simple, legal, academic)
- [ ] Dockerized deployment
- [ ] Unit tests and CI/CD

---

## 🧱 Tech Stack

| Component       | Tool / Library                        |
|----------------|----------------------------------------|
| PDF Processing | [PyMuPDF](https://pymupdf.readthedocs.io/) |
| Embeddings     | [SentenceTransformers](https://www.sbert.net/) |
| Vector Search  | [FAISS](https://github.com/facebookresearch/faiss) |
| LLM            | [Mistral](https://mistral.ai/) via [Ollama](https://ollama.com) |
| UI             | [Streamlit](https://streamlit.io) |
| Deployment     | Docker (optional, in progress)         |

---

## ▶️ Getting Started

### 1. Clone the repo
```bash
git clone git remote add origin https://github.com/DanAbergel/PDFQ-A.git
cd PDFQ-A
