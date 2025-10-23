# AI Cognitive Workbench

Conversational AI with Text-to-Image and Image-to-Text capabilities powered by Gemini 2.5 Flash.

## Setup

```bash
pip install -r requirements.txt
```

Update `.env` with your API key.

## Run

```bash
streamlit run streamlit.py
```

This starts both FastAPI backend (port 8000) and Streamlit frontend (port 8501).

## Features

- **💬 Chat**: Natural conversations with memory (temporary, clears on reload)
- **🎨 Text-to-Image**: Generate images from text prompts
- **🔍 Image-to-Text**: Analyze and describe uploaded images
