# rag-app
A Rag application 
You can upload your own pdfs and ask questions related to the pdfs.
It uses the locally run mistral as local llm

---

#  README for **PDF Summarization RAG App**
**(Python + Streamlit + RAG)**

```markdown
# PDF Summarization RAG App 📄🤖
A **Retrieval-Augmented Generation (RAG)** application that allows users to query and summarize large PDF documents.

##  Overview
This project helps users extract meaningful summaries from long academic or technical PDFs using a retrieval-first approach.

##  Features
- PDF upload and parsing
- Text chunking and preprocessing
- Query-based document retrieval
- Context-aware summarization
- Simple web UI using Streamlit

##  Tech Stack
- **Language:** Python
- **Data Handling:** Pandas, NumPy
- **Framework:** Streamlit
- **Concepts:** Retrieval-Augmented Generation (RAG)

##  Architecture
1. PDF ingestion and text extraction  
2. Data cleaning and preprocessing (Pandas)  
3. Chunking and retrieval pipeline  
4. Query-based response generation  

##  Installation & Setup
```bash
git clone https://github.com/SkandhaNeupane/rag-app.git
cd rag-app
pip install -r requirements.txt
streamlit run app.py
