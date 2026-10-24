# AI Doc Assistant

A simple AI-powered document assistant that extracts text from PDFs, DOCX, and TXT files, then summarizes them into:

- summary
- key points
- action items
- risks
- tags

## Demo

Upload a document and the app will generate a structured analysis.

## Tech Stack

- Python
- Streamlit
- OpenAI API
- PyMuPDF
- python-docx

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
```

Then fill in your API key in `.env`.

Run:

```bash
streamlit run app.py
```

## Features

- PDF text extraction
- DOCX text extraction
- TXT / Markdown processing
- AI-based summarization
- JSON export

## Future Ideas

- multi-file batch processing
- semantic search
- saved history
- document comparison
- web app deployment
