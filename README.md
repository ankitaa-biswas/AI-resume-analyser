# AI Resume Analyzer

AI-powered resume analyzer that evaluates resumes against job descriptions and provides an ATS score with improvement suggestions.

Built using React + TypeScript with React Router for routing and Puter for authentication and backend storage. Deployed on Vercel.

## Features
- Upload resume (PDF)
- Enter job title, company name, and job description
- AI-based resume analysis
- ATS score generation
- Feedback on missing skills and improvements
- Secure authentication using Puter

## Tech Stack
Frontend: React, TypeScript, React Router, Tailwind CSS  
Backend/Auth: Puter  
Deployment: Vercel  

## How It Works
User logs in using Puter → uploads resume → enters job details → resume is analyzed → ATS score and feedback are generated.

## Run Locally
```bash
git clone https://github.com/ankitaa-biswas/AI-resume-analyzer.git
cd AI-resume-analyzer
npm install
npm run dev
```
App runs on Locally:
```
http://localhost:5173
```
Live Demo:
```
https://ai-resume-analyser-eight-red.vercel.app/auth?next=/
```

