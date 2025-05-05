# Image Caption Generator (LLaVA)

    This project uses the **LLaVA model** via Ollama to generate captions for uploaded images.

    ## Features
    - Vision-Language Model (LLaVA)
    - FastAPI backend
    - Streamlit UI

    ## How to Run-Instructions
    1. Pull model: `ollama pull llava`
    2. Start backend: `uvicorn backend.main:app --reload`
    3. Start frontend: `streamlit run frontend/app.py`
    4. Upload an image and generate captions
