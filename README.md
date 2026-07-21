# 📄 AI PDF Chatbot

An AI-powered PDF Chatbot that allows users to upload PDF documents and ask questions in natural language. The application extracts text from PDFs, processes the content, and generates intelligent responses using Hugging Face language models, LangChain, ChromaDB, and Gradio.

---
## How to run it?
1. Open the Google Colab notebook.
2. Run all cells sequentially.
3. Install the required dependencies (if prompted).
4. Upload a PDF document when requested.
5. Wait for the retrieval pipeline to initialize.
6. Open the generated Gradio Live URL.
7. Upload your PDF and start asking questions in natural language.

## 🚀 Features

- 📂 Upload PDF documents
- 💬 Ask questions about the uploaded PDF
- 📖 Automatic text extraction
- 🔍 Context-aware question answering
- ⚡ Interactive Gradio web interface
- 🧠 Lightweight Hugging Face model integration
- 📚 Vector database powered by ChromaDB

---

## 🛠️ Tech Stack

- Python
- Hugging Face Transformers
- LangChain
- ChromaDB
- Gradio
- PyPDF2
- Google Colab

---

## 📂 Project Structure

```
AI-PDF-Chatbot/
│
├── AI_PDF_Chatbot.ipynb
├── README.md
├── requirements.txt
├── assets/
│   ├── interface.png
│   └── demo.png
└── sample.pdf
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/parth-thepale/AI-PDF-Chatbot.git
```

Move into the project directory

```bash
cd AI-PDF-Chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Google Colab.

---

## 📌 How It Works

1. Upload a PDF document.
2. Extract text from the PDF.
3. Split the text into manageable chunks.
4. Store embeddings in ChromaDB.
5. Retrieve the most relevant context.
6. Generate answers using a Hugging Face language model.
7. Display responses through the Gradio interface.

---


## 📈 Future Improvements

- Support multiple PDF uploads
- Better retrieval pipeline
- Conversation memory
- Faster embedding models
- Deploy on Hugging Face Spaces
- User authentication

---

## 📝 Note

This project currently uses a lightweight Hugging Face model for demonstration purposes in Google Colab. The model can be replaced with more advanced instruction-tuned models for improved response quality.

---

## 👨‍💻 Author

**Parth Thepale**

LinkedIn: www.linkedin.com/in/parth-thepale-32864b3a2

---

⭐ If you found this project useful, consider giving it a star!
