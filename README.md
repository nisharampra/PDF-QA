# PDF-QA
# AskMyPDF 🤖📄  
An AI-powered smart assistant that lets you upload any educational or coursework-related PDF, automatically summarize its contents, and ask natural language questions like:

- "What is Exercise 2 about?"
- "What files do I need to submit?"
- "What tools should I use in Exercise 1?"

Built using Hugging Face Transformers in Python with a lightweight pipeline that works directly in Google Colab.

---

## 🔍 Features

- 📂 Upload any PDF
- 🧠 Summarize long academic documents with BART
- ❓ Ask open-ended questions with DistilBERT QA pipeline
- 🗂️ Named Entity Recognition for better understanding
- ✨ Clean, formatted output for summaries and entities
- 💬 Easily customizable for coursework, contracts, legal, or technical docs

---

## 🛠 Tech Stack

- Python 3.x
- Hugging Face `transformers`
- `pdfminer.six` for PDF text extraction
- `spaCy` for Named Entity Recognition (NER)
- Google Colab (for frontend and backend dev)

---

## 📁 How to Use

1. Open the notebook: [`PDF_QA.ipynb`](PDF_QA.ipynb)
2. Upload a PDF file (e.g., coursework guidelines or a report)
3. Run the cells to:
    - Extract and display the text
    - Summarize the document
    - Ask custom questions and receive answers
4. (Optional) Export the summary and answers to a `.txt` file

---

## 🚀 Example Questions You Can Ask

```python
"What is Exercise 3 about?"
"What tools are required for video conversion?"
"What is the video format specified by the film festival?"
"How long should the video demo be?"
"What are the total marks and their breakdown?"
