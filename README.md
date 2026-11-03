# ✨ PRESENTRA
### AI-Based Intelligent Presentation Assistant

<p align="center">
  **Create Smarter Presentations. Deliver with Confidence.**
  
  *Create • Present • Interact*
</p>

---

## 💡 About the Project

**PRESENTRA** is an AI-powered presentation assistant that transforms documents and ideas into engaging presentations.

From generating slides and speaker scripts to AI voice narration and live question-answering, PRESENTRA brings the entire presentation experience together in one intelligent platform.

## 🎯 What Makes PRESENTRA Special?

- 📄 **Smart Document Upload** — Upload PDF and DOCX files.
- 🧠 **AI-Powered Research** — Turn topics into structured presentation content.
- 🎨 **Intelligent Slide Generation** — Create organized presentation slides.
- 📝 **Speaker Scripts** — Generate speaking notes for 5, 10, and 15-minute presentations.
- 🔊 **AI Voice Narration** — Listen to your presentation with AI-generated speech.
- 💬 **Live AI Q&A** — Ask questions and get answers based on presentation content.
- 📥 **PowerPoint Export** — Download presentations in PPTX format.

## 🎓 Designed for Everyone

| Mode | Purpose |
|---|---|
| 👩‍🏫 Teacher Mode | Educational lectures and lessons |
| 🎓 Student Mode | Academic presentations |
| 🚀 Startup Founder Mode | Startup pitches and business ideas |
| 🔬 Researcher Mode | Research findings and projects |

<text color="secondary" size="xs">Primary demonstration: Teacher Mode · Secondary demonstration: Startup Founder Mode</text>

## 🔄 How It Works

```text
       USER INPUT
            │
     ┌──────┴──────┐
     │             │
 Upload File   Enter Topic
     │             │
     └──────┬──────┘
            ↓
    AI CONTENT ANALYSIS
            ↓
   PRESENTATION OUTLINE
            ↓
     SLIDE GENERATION
            ↓
     SPEAKER SCRIPTS
            ↓
    ┌───────┴────────┐
    ↓                ↓
 AI NARRATION    PPT DOWNLOAD
    ↓
 PRESENTATION DELIVERY
    ↓
   LIVE AI Q&A
```

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js, Tailwind CSS, JavaScript |
| Backend | Python, FastAPI |
| AI Model | Google Gemini API |
| AI Orchestration | LangChain / Custom Integration |
| RAG & Vector Database | ChromaDB / FAISS |
| Document Processing | PyMuPDF, python-docx |
| PowerPoint | python-pptx |
| Speech | OpenAI Whisper, Open-source TTS |
| Database | PostgreSQL / Supabase |
| Authentication | Supabase Auth / JWT |
| Visualization | Chart.js / Plotly |

<text color="secondary" size="xs">*Technologies represent the planned stack; final selections may change during development.*</text>

## 🏗️ Project Architecture

PRESENTRA is organized into four main layers:

- **Frontend:** User interface, document uploads, slides, and presentation controls.
- **Backend:** APIs, document processing, presentation generation, and application logic.
- **AI Processing:** Content understanding, RAG retrieval, AI responses, and voice generation.
- **Database & Storage:** User data, presentation history, documents, and vector storage.

## 📁 Project Structure

```text
PRESENTRA/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── modes/
│       ├── services/
│       ├── hooks/
│       ├── utils/
│       ├── App.jsx
│       └── main.jsx
│
├── backend/
│   ├── app/
│   │   ├── api/routes/
│   │   ├── core/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── database/
│   │   ├── services/
│   │   ├── utils/
│   │   └── main.py
│   ├── tests/
│   └── requirements.txt
│
├── docs/
│   ├── PRESENTRA_Project_Proposal.pdf
│   ├── diagrams/
│   ├── screenshots/
│   └── reports/
│
├── uploads/
├── .env.example
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Python 3.10+
- Node.js and npm
- Git
- Visual Studio Code

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd PRESENTRA
```

### 2. Setup Backend

Open your first terminal:

```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Setup Frontend

Open a second terminal from the project root:

```bash
cd frontend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Keep your API keys private. Never upload `.env` to GitHub.

## ▶️ Run PRESENTRA

**Backend — Terminal 1**

From the `backend` directory, with the virtual environment activated:

```bash
uvicorn app.main:app --reload
```

Backend: `http://127.0.0.1:8000`

API Documentation: `http://127.0.0.1:8000/docs`

**Frontend — Terminal 2**

From the `frontend` directory:

```bash
npm run dev
```

Frontend: `http://localhost:5173`

<text color="secondary" size="xs">Both terminals must remain running. These commands assume the FastAPI entry point and Vite frontend configuration have been implemented.</text>

## 🗺️ Development Roadmap

- [ ] Repository and project setup
- [ ] Frontend UI development
- [ ] Backend API development
- [ ] AI and document integration
- [ ] RAG and knowledge retrieval
- [ ] Slide and speaker script generation
- [ ] AI voice narration
- [ ] Live AI Q&A
- [ ] Database and authentication
- [ ] Testing and deployment

---

## 🚧 Project Status

**Currently in Development**

PRESENTRA is being developed as an AI-powered presentation solution. Features will be implemented and tested progressively.

---

<p align="center">

  ### ✨ PRESENTRA
  
  **Present Smarter. Communicate Better.**

</p>