# 🚀 InterviewAce AI — Smart AI Interview Preparation Platform

**InterviewAce AI** is an AI-powered interview preparation platform that helps students and job seekers improve their technical knowledge, communication skills, and interview confidence through personalized mock interviews and AI-driven feedback.

## ✨ Features

- 🎤 **AI Mock Interviews** — Practice technical, HR, behavioral, and mixed interviews.
- 🤖 **AI Answer Evaluation** — Get scores, feedback, strengths, and suggested answers.
- 📄 **Resume Analyzer** — Analyze resumes and identify skills to improve.
- 💻 **Coding Practice** — Practice programming questions across multiple difficulty levels.
- 📊 **Progress Dashboard** — Track interview performance and learning progress.
- 🎯 **Skill Gap Analysis** — Identify skills to develop for your target job role.
- 🔐 **Secure Authentication** — User registration, login, and personalized history.
- 📱 **Responsive UI** — Access the platform on desktop and mobile devices.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML, CSS, JavaScript | Frontend |
| Python FastAPI | Backend and REST APIs |
| MongoDB Atlas | Database |
| Google Gemini API | AI question generation and feedback |
| Chart.js | Progress visualization |
| Browser Speech APIs | Voice-based interview interaction |

## 🏗️ Architecture

```text
InterviewAce-AI/
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── .env.example
├── tests/
├── README.md
└── .gitignore
```

*The actual folder structure may differ depending on the Replit Agent's implementation.*

## ⚙️ Setup and Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd InterviewAce-AI
```

### 2. Install dependencies

Create a virtual environment and install the backend requirements:

```bash
python -m venv .venv
```

Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install dependencies:

```bash
pip install -r backend/requirements.txt
```

### 3. Configure environment variables

Create a `.env` file using `.env.example` and configure:

```env
GEMINI_API_KEY=your_gemini_api_key
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET_KEY=your_secure_random_secret
```

Never commit your actual `.env` file or API keys to GitHub.

### 4. Run the application

If the FastAPI entry point is `backend/main.py`, run:

```bash
uvicorn main:app --reload
```

Run the command from the backend directory. Follow the project's actual README if the generated structure differs.

API documentation:

```text
http://127.0.0.1:8000/docs
```

## 🔑 Environment Setup

- **Gemini API:** https://aistudio.google.com/
- **MongoDB Atlas:** https://www.mongodb.com/atlas
- **Replit:** https://replit.com/

Configure secrets in Replit's Secrets panel when deploying on Replit.

## 🎯 Project Objectives

- Help students prepare for real-world technical interviews.
- Provide personalized, actionable AI feedback.
- Improve interview readiness through repeated practice.
- Identify skill gaps and suggest targeted learning paths.
- Combine AI, full-stack development, and database technologies in one application.

## 🔮 Future Enhancements

- Company-specific interview preparation.
- AI-generated personalized study plans.
- Advanced speech and communication analysis.
- Coding assessment with secure sandbox execution.
- Interview question recommendations based on performance.
- Deployment with a public demo URL.

## 🔒 Security

- Hash passwords securely.
- Protect private endpoints with authentication.
- Validate uploaded files and user inputs.
- Keep API keys in environment variables.
- Isolate submitted code during execution.

## 👨‍💻 Author

**Mahesh Thota**

GitHub: [@maheshthota2007-dev](https://github.com/maheshthota2007-dev)

LinkedIn: [Mahesh Thota](https://www.linkedin.com/in/mahesh-thota-889773376/)

---

⭐ If you find this project useful, consider giving the repository a star.

*Built to make interview preparation smarter, more accessible, and more personalized with AI.*
