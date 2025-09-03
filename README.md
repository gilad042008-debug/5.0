# Streamlit Chart Bot

Ready-to-deploy Streamlit app that analyzes chart screenshots and returns a visual annotated chart plus a short trade recommendation (Buy / Sell / Hold) with entry / stop / target and confidence.

## Features
- Image ingestion (PNG/JPG)
- Price extraction via OCR (Tesseract)
- Indicators: SMA20, RSI14
- Rule-based pattern signal + ML stub
- Annotated chart output
- Downloadable CSV
- Dockerfile & Streamlit deployment ready

## Quick start
1. Install Python 3.11 and Tesseract OCR.
2. Clone this repo.
3. `pip install -r requirements.txt`
4. `streamlit run app.py`

## Deploy
- **Streamlit Cloud**: connect GitHub repo, point to `app.py`.
- **Hugging Face Spaces**: create Streamlit Space and upload repo.
