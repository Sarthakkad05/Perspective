# 🌟 Contributing to Perspective

Hi there! 👋  
Thank you for considering contributing to **Perspective** — we’re excited to collaborate with you.

Whether you're:
- fixing bugs
- improving documentation
- adding features
- or suggesting ideas

You're welcome here!

---

## ⚠️ Before You Start

- Please check existing issues first
- Comment on the issue before working on it
- Wait for maintainer approval/assignment
- Avoid duplicate PRs

---

# 🛠 Setting Up the Project

Follow these steps to run Perspective locally.

---

## Prerequisites

Install:

- Node.js 18+
- Python 3.10+
- uv package manager → https://docs.astral.sh/uv/
- API keys:
  - OpenAI/Groq
  - Pinecone (or other Vector DB)
  - Google Custom Search

---

## Frontend Setup

```bash
cd frontend
cp .env.example .env
npm install
npm run dev
```
Frontend runs at:
http://localhost:3000

Backend Setup
```bash
cd backend
uv sync
cp .env.example .env
uv run main.py
```
Backend runs at:
http://localhost:8000

🧪 Testing
Frontend
cd frontend
npm test
Backend
cd backend
pytest
Make sure all tests pass before submitting a PR.

📂 Project Structure
frontend/   → Next.js UI
backend/    → FastAPI + AI logic
docs/       → architecture & documentation
🚀 Contribution Workflow
1. Fork the repo
Click Fork on GitHub

2. Clone
git clone https://github.com/<your-username>/Perspective.git
3. Create a branch
git checkout -b feat/your-feature-name
4. Make changes
Follow existing code style and structure.

5. Commit clearly
Use prefixes:

feat:

fix:

docs:

refactor:

test:

Example:

feat: add caching for article analysis
6. Push & open PR
git push origin feat/your-feature-name
Open a Pull Request on GitHub.

