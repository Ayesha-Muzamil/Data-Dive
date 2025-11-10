# 🌊 Data Dive

Explore. Extract. Engage.
A Conversational AI Document Analysis Tool

# Overview

Data Dive is a next-generation document processing and Q&A platform that redefines how users interact with PDF documents using Natural Language Processing (NLP) and conversational AI.

Upload your PDFs, ask questions, and let Data Dive extract insights directly from your documents — all through an intuitive chat interface.

# 🚀 Features

✅ Secure PDF upload and text extraction via PyPDF2
✅ Smart text chunking for optimized document analysis
✅ Context-aware Q&A powered by LangChain and OpenAI/Hugging Face models
✅ Lightning-fast similarity search with FAISS
✅ Clean, interactive Streamlit interface
✅ SQLite-based authentication for secure user access

# 🧩 Tech Stack
Layer	Technology
Frontend / UI	Streamlit
Backend	Python
Text Extraction	PyPDF2
Vector Search	FAISS
Conversational AI	LangChain + OpenAI / Hugging Face
Database	SQLite
Authentication	Streamlit Auth / SQLite
Deployment	Streamlit Cloud / Local
💡 How It Works

Upload PDF: Securely upload your document to the app.

Text Extraction: PyPDF2 extracts the text and divides it into optimized chunks.

Embedding & Indexing: Text chunks are converted to embeddings and stored in a FAISS vector database.

Ask Questions: User queries are compared against the document embeddings.

Get Insights: The system returns accurate, context-aware answers using the best-matching sections of your file.


# Install Dependencies
pip install -r requirements.txt

# Run the App
streamlit run app.py

🧑‍💻 Usage

Run the Streamlit app.

Create an account or log in.

Upload your PDF file.

Ask any question about the document in natural language.

Receive AI-generated, context-aware answers instantly.

🔒 Security

Data Dive ensures data privacy with:

Encrypted storage for credentials

Local processing (no external file uploads unless configured)

Access control via SQLite-based authentication

📈 Future Enhancements

Support for multiple document formats (Word, TXT, etc.)

Cloud storage integration

Multi-user collaboration

Summary generation for documents

Voice-based query support

# 🧑‍🎓 About

Developed by Ayesha Muzamil: Introduction to Computer Science final project.
This project showcases the practical integration of AI, NLP, and full-stack development skills.

# 📜 License

This project is licensed under the MIT License
