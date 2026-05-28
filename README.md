# 🏦 Mortgage Assistant

> Upload any mortgage document and get plain-English answers instantly — powered by LLaMA 3.3 via Groq.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Groq](https://img.shields.io/badge/Groq-LLaMA_3.3-orange?style=flat-square)
![Gradio](https://img.shields.io/badge/Gradio-UI-purple?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Deployed-HuggingFace-yellow?style=flat-square)

---

## 📌 What It Does

Mortgage documents are dense, jargon-heavy, and overwhelming. This tool lets you upload any mortgage-related file and ask questions in plain English. The AI reads the document and returns clear, accurate answers — extracting rates, fees, borrower names, dates, and more on demand.

**Live demo generated 918+ LinkedIn impressions.**

---

## 📸 Demo

> Upload a document → Ask a question → Get a plain-English answer

![Mortgage Assistant Demo](screenshots/demo.jpg)

---

## 🚀 Features

- Supports **PDF, DOCX, XLSX, CSV, and TXT** file formats
- Ask natural language questions about rates, terms, fees, borrower info, and more
- Full conversation history — ask follow-up questions in context
- Powered by **LLaMA 3.3 70B** via Groq API for fast, accurate responses
- Clean dark UI built with Gradio
- Deployed and publicly accessible on Hugging Face Spaces

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language Model | LLaMA 3.3 70B (via Groq) |
| PDF Parsing | pypdf |
| Word/Excel Parsing | python-docx, openpyxl |
| Frontend | Gradio |
| Deployment | Hugging Face Spaces |

---

## 🏃 How to Run

```bash
# Clone the repo
git clone https://github.com/Nateit1/mortgage-assistant.git
cd mortgage-assistant

# Install dependencies
pip install -r requirements.txt

# Add your Groq API key
export GROQ_API_KEY=your_key_here

# Run the app
python app.py
```

Or deploy directly to Hugging Face Spaces — add `GROQ_API_KEY` as a Space secret.

---

## 🔗 Links

- 🤗 [Live Demo on Hugging Face](https://huggingface.co/spaces/Nateit1/Mortgage1)
- 💼 [LinkedIn](https://linkedin.com/in/nathantsega)
- 🌐 [Portfolio](https://af19o4udzm.mobirisesite.com/)
