# 📚 AI PDF Study Assistant

## 📌 About the Project

**AI PDF Study Assistant** is a Python-based AI application designed to make studying and understanding PDF documents easier. It allows users to upload PDF files, generate summaries, search for information using AI, and create questions from PDF content.

The project uses **Streamlit** to provide a simple and interactive user interface and Google's Gemini AI to support AI-powered features.

## ✨ Features

- 📄 **PDF Upload:** Upload PDF documents for analysis.
- 🤖 **AI Search:** Ask questions about the uploaded PDF and get AI-generated answers.
- 📝 **PDF Summarization:** Generate summaries of PDF content.
- ❓ **Question Generator:** Generate questions based on the uploaded PDF to support learning and revision.
- 💻 **Interactive Interface:** Easy-to-use interface built with Streamlit.
- 📚 **Study Assistance:** Helps students understand lengthy documents more efficiently.

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini AI
- PyMuPDF (fitz)
- Python-dotenv

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd your-project-folder
```

**3. Install the required libraries**

```bash
pip install streamlit pymupdf python-dotenv google-genai
```

**4. Configure your API key**

Create a `.env` file in the project folder and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

Make sure you keep your API key private and do not upload the `.env` file to GitHub.

**5. Run the application**

```bash
streamlit run app.py
```

## 🎯 Project Objective

The main objective of this project is to make PDF-based learning smarter, faster, and more interactive using Artificial Intelligence. It is especially useful for students who want to summarize study materials, find specific information, and generate questions for revision.

## 🚀 Future Improvements

- Support for more document formats.
- Improved AI search and answer accuracy.
- Downloadable summaries and generated questions.
- Additional study and revision tools.

## 👨‍💻 Author

**Prateek Mishra**

BCA Student | Python Developer | Aspiring Data Analyst

I enjoy building Python projects and exploring how AI can solve real-world problems. I look forward to developing more useful and innovative applications.

---

⭐ If you find this project useful, consider giving the repository a star!
