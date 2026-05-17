📘 Smart Notes Summarizer
A simple NLP-based application that allows users to upload notes (PDF/Text) and generates short, exam-ready summaries using Hugging Face Transformers.

🚀 Features:
📄 Upload PDF notes
🧠 Automatic text extraction from PDFs
✂️ Generates concise summaries
⚡ Uses state-of-the-art NLP model (facebook/bart-large-cnn)
🧩 Easy to understand and extend
🎓 Perfect for students and exam preparation

🛠️ Tech Stack: 
Python 3.9+
pypdf – PDF text extraction
Transformers (Hugging Face) – Text summarization
Torch
(Optional) Streamlit for UI

📂 Project Structure
Smart-Notes-Summarizer/
│
├── smart_notes_summarizer.py
├── README.md
├── requirements.txt
└── sample_notes.pdf

🧠How It Works:
User uploads a PDF file
Text is extracted using pypdf
Text is processed and summarized using facebook/bart-large-cnn
A short, exam-focused summary is generated

🎯 Use Cases:
Exam revision
Quick note summarization
Academic projects
NLP learning demo
Updated for merging
