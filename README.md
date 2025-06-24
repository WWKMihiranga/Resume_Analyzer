# 🧠 AI Resume Analyzer

This project is a smart, interactive **Resume Analyzer** built using **Python**, **Streamlit**, and **Google Gemini AI**. It helps candidates understand how well their resume aligns with specific job descriptions and provides feedback, strengths, weaknesses, and improvement suggestions.

---

## 🚀 Features

- 📄 Upload and analyze resumes in PDF format
- 🔍 Extracts text using `pdfplumber` and OCR (`pytesseract`) as fallback
- 💬 Uses **Gemini AI** for evaluating resume quality
- 🧩 Compares resume content with a job description (optional)
- ✅ Suggests relevant skills and improvement areas
- 🌐 Easy-to-use Streamlit web interface

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Streamlit** – Web UI
- **Google Generative AI (Gemini)** – Resume evaluation and suggestions
- **pdfplumber** – Text extraction from PDFs
- **pytesseract** – OCR for image-based PDFs
- **dotenv** – Environment variable management

---

## 💻 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/resume-analyzer.git
   cd resume-analyzer
   
2. **Create a .env file with your Gemini API Key**  
   ```bash
   GOOGLE_API_KEY=your_gemini_api_key_here

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt

4. **Run the app**  
   ```bash
   streamlit run app.py

---

## 🧑‍💻 Author

Built by Kavindu Mihiranga

---
