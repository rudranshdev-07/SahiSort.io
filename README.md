# SahiSort — Sort it right. Give it a second life.

AI-powered everyday object identification, source-grounded municipal disposal guidance, and RE:CREATE reuse studio.

## 1. Setup & Execution Instructions

### Backend (FastAPI + SQLite + Gemini AI + Evidence Engine)
```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp ../.env.example .env    # Optional: set GEMINI_API_KEY in backend/.env for live vision
uvicorn main:app --reload --port 8000