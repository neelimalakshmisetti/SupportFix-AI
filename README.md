<div align="center">
  
# 🤖 SupportFix AI

An intelligent, AI-powered IT support assistant designed to instantly troubleshoot common technical issues. SupportFix AI uses Google's Gemini models to analyze user complaints, categorize the issue, and provide step-by-step resolution guides in a beautiful, chat-like interface.

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Here-blue?style=for-the-badge)](https://supportfix-ai-neelima.netlify.app/)
[![Backend Status](https://img.shields.io/badge/API-Render-green?style=for-the-badge)](https://supportfix-ai-backend.onrender.com)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)

</div>

---

## ✨ Features

- **Conversational AI Interface:** A sleek, modern chat interface for users to describe their tech problems.
- **Intelligent Classification:** Uses Gemini LLMs to automatically classify the issue (e.g., WiFi, Printer, Login, Slow System).
- **Step-by-Step Troubleshooting:** Fetches and formats actionable troubleshooting steps from a custom knowledge base.
- **Glassmorphism Design:** Premium frontend UI built with Tailwind CSS and Framer Motion for smooth micro-animations.
- **Full-Stack Architecture:** Decoupled Vite/React frontend and Python/FastAPI backend.

## 🚀 Live Demo

- **Frontend Application:** [https://supportfix-ai-neelima.netlify.app/](https://supportfix-ai-neelima.netlify.app/)
- **Backend API:** [https://supportfix-ai-backend.onrender.com](https://supportfix-ai-backend.onrender.com)

---

## 🛠️ Tech Stack

**Frontend:**
- React 18
- Vite
- Tailwind CSS
- Framer Motion

**Backend:**
- Python 3
- FastAPI
- Uvicorn
- Google Gemini API (via OpenAI compatible endpoint)

---

## 💻 Local Setup Instructions

Want to run this project on your own machine? Follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/neelimalakshmisetti/SupportFix-AI.git
cd SupportFix-AI
```

### 2. Backend Setup
Navigate to the backend directory, install dependencies, and set up your environment variables.
```bash
cd backend
pip install -r requirements.txt
```
Create a `.env` file in the `backend` folder and add your Gemini API Key:
```env
GEMINI_API_KEY=your_gemini_api_key_here
GEMINI_MODEL=gemini-2.5-flash
```
Start the backend server:
```bash
uvicorn main:app --reload --port 8000
```

### 3. Frontend Setup
Open a new terminal window, navigate to the frontend directory, and start the development server.
```bash
cd frontend
npm install
npm run dev
```

The frontend will be running at `http://localhost:5173` and the backend at `http://localhost:8000`.

---

## 📂 Folder Structure

```text
SupportFix-AI/
├── backend/
│   ├── main.py                # FastAPI server and Gemini integration
│   ├── troubleshooting.json   # Knowledge base of troubleshooting steps
│   ├── requirements.txt       # Python dependencies
│   └── .env.example           # Example environment variables
└── frontend/
    ├── src/
    │   ├── components/        # React components (Chat, Message)
    │   ├── App.jsx            # Main App layout
    │   └── index.css          # Tailwind CSS styling
    ├── package.json           # Node dependencies
    ├── vite.config.js         # Vite configuration
    └── tailwind.config.js     # Tailwind design system configuration
```

---

<div align="center">
  <i>Built with ❤️ by Neelima Lakshmisetti</i>
</div>
