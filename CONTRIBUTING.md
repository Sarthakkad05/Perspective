# 🌟 Contributing to Perspective

Hi there! Thank you for considering contributing to PictoPy – we’re excited to collaborate with you. Whether you're fixing a bug, improving documentation, or suggesting a new feature — you're welcome here!

NOTE: Please do not open a PR for the issue which is not yet reviewed and labelled by the maintainer. Wait for the maintainer to give a green light.


# 🛠 Setting Up the Project

Follow these steps to run Perspective locally.

Install:

- Node.js 18+
- Python 3.10+
- uv package manager → https://docs.astral.sh/uv/
- API keys:
  - OpenAI/Groq
  - Pinecone (or other Vector DB)
  - Google Custom Search

## Clone Repository

```bash
git clone https://github.com/AOSSIE-Org/Perspective.git
cd Perspective
```

## Frontend (Next.js)

1. Install dependencies
```bash 
cd frontend
npm install
```

2. Configure environment
```bash
cp .env.example .env
```
Edit the .env file

3. Start development server
```bash
npm run dev
```

Frontend runs at:
http://localhost:3000

