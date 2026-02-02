# 📐 Diagram / P&ID / Circuit Text Extractor

AI-powered OCR tool that extracts all visible text from engineering diagrams, P&ID drawings, circuit schematics, and PDFs.

## Features

- Upload PDF / PNG / JPG
- Extract diagram titles, variables, labels, equations
- OpenCV preprocessing for better OCR
- Multi-page PDF support
- Download extracted text
- Streamlit web UI

## Tech Stack

Python  
Streamlit  
OpenCV  
Tesseract OCR  
pdf2image  
Pillow  

## How to Run

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
