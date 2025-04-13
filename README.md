# pakistan-penal-code-qa
AI-powered question answering system based on the Pakistan Penal Code, using PDF parsing, semantic search, and language models.

Here’s a clean and professional `README.md` file tailored for your notebook and GitHub repo that builds a QA system on the **Pakistan Penal Code**:

---

# 🇵🇰 Pakistan Penal Code QA

**Pakistan Penal Code QA** is an AI-powered question answering system built on the official legal text of the Pakistan Penal Code. This project parses the PPC from PDF, semantically indexes it using vector embeddings, and enables users to query it in natural language for relevant, law-grounded answers.

---

## 📌 Features

- ✅ Extracts and processes PPC from PDF format
- ✅ Splits content into chunks suitable for semantic search
- ✅ Generates embeddings using HuggingFace transformer models
- ✅ Stores embeddings in FAISS vector database for efficient similarity search
- ✅ Enables legal question answering using LangChain’s RetrievalQA
- ✅ Provides a quick preview of extracted legal text

---

## 🛠️ Technologies Used

- **Python**
- **PyMuPDF** (`fitz`) – for PDF parsing  
- **LangChain** – for LLM integration and QA pipeline  
- **HuggingFace Transformers** – for text embeddings  
- **FAISS** – for similarity search  
- *(Optional: Gradio or Streamlit for UI)*

---

## 📂 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pakistan-penal-code-qa.git
   cd pakistan-penal-code-qa
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Add your PPC PDF**
   - Place your `pakistan_penal_code.pdf` in the root directory.

4. **Run the notebook**
   - Open `pakistan_panel_code.ipynb` in Jupyter Notebook or JupyterLab.
   - Follow the steps to extract text, embed content, and run queries.

---

## 🧪 Example

Ask a question like:

> “What is the punishment for theft under the Pakistan Penal Code?”

The system will return the relevant section and details from the legal text.

---

## 🤖 Future Improvements

- Add a Gradio or Streamlit interface
- Extend support to other Pakistani laws (e.g., CPC, CRPC, Evidence Act)
- Build a chatbot or WhatsApp bot using this QA pipeline

---

## 📜 License

This project is for educational and informational use only. Not intended for official legal advice.

---

Let me know if you want me to include a `requirements.txt` too or link to a live demo.
