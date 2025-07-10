# My-chatbot-using-Open-AI-and-Hugging-face-offline-

This project is a local document-based chatbot that allows users to upload a PDF and ask natural language questions about its content. It supports two powerful approaches for answering questions:

🚀 Key Features
--
📄 Upload and parse PDF documents

🔍 Smart chunking and embedding using LangChain

🧠 Vector similarity search with ChromaDB

💬 Ask questions in a Gradio interface

🤖 Answer generation using:

✅ Method 1: OpenAI GPT-3.5-Turbo via API

✅ Method 2: HuggingFace Phi-3-mini locally

🛠️ How to Use
--
✅ Method 1: OpenAI GPT-3.5 (Cloud)

Uses OpenAI for both embeddings and answering.

Requires an API key.

Run the notebook: OpenAI_PDF_Chatbot.ipynb

✅ Method 2: HuggingFace Phi-3 (Local)

Uses sentence-transformers + local Phi-3 model.

Fully offline (requires GPU).

Run the notebook: PDF_Local.ipynb
