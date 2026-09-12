# ✦ Sastra AI — Capacity Connect
### Digital Capacity Building AI Learning Operating System (Govt of Odisha)

This project is configured for 1-click deployment on **Vercel** with fullstack support (React + Vite Frontend and Python Serverless Backend).

## 🚀 Deployment on Vercel

1. **Import this repository** in [Vercel Dashboard](https://vercel.com/new).
2. **Environment Variables**:
   - GEMINI_API_KEY: Your Google Gemini API Key
   - LLM_PROVIDER: gemini
   - JWT_SECRET: Any random secure string (e.g. sastra-odisha-capacity-2026)
3. Click **Deploy**.

## 💻 Local Development

- **Frontend**:
  cd frontend
  npm install
  npm run dev

- **Backend**:
  cd capacity-connect-chatbot
  pip install -r requirements.txt
  python app.py
