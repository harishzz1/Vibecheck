VibeCheck - AI-Powered Vulnerability Scanner 

Your next-gen AI security assistant — lightning-fast vulnerability detection paired with an intelligent chat companion powered by Google Gemini.


 Critical Security Update: CWE-489 Fix

Removed dangerous debug=True in production Flask server

Secure setup via environment variables — no hardcoded secrets

Hardened for safe deployment from day one


 AI Powered Security Assistant Sidebar

Sleek, professional dark theme UI designed for seamless workflow

Built-in AI chat with Google Gemini models (1.5 Flash/Pro, 2.0 Flash/Pro)

Context-aware, security-focused conversations about your code

Auto model fallback ensures smooth experience even with quota limits

Real-time typing indicators & smart error recovery keep you productive


 Get Started in Seconds

Start frontend and backend services:

npm run dev       # Runs Next.js frontend (port 3000/3001)
python scanner_service.py --debug  # Runs Python vulnerability scanner (port 5000)


Open a project folder in the app

Click Analyze to scan for vulnerabilities

Chat with your AI assistant — ask questions, get fix advice

Click vulnerabilities to explore details & remediation tips

Switch between Gemini models for different response styles


 Why VibeCheck?

Smart Vulnerability Detection: Automatically identifies 50+ vulnerability types

Interactive Exploration: Click issues, get instant AI-driven insights & fixes

Context-Aware: AI understands your current code context for targeted advice

Professional UI: Minimalist, responsive design crafted for developer focus

Robust AI Integration: Multi-model support with graceful quota fallback

Secure & Privacy-Focused: No data stored, secure API key management, local file control

 Security You Can Trust

No debug flags enabled in production

Environment variables for all secrets

Input validation and safe file handling

HTTPS-encrypted API communication

Zero persistent storage of your code or conversations


 Tech Stack

Frontend: Next.js 14, TypeScript, Tailwind CSS, Framer Motion, Radix UI, Monaco Editor

Backend: Flask + Semgrep vulnerability scanning

AI: Google Gemini API with smart token & quota management

Model Options
Model	Speed	Accuracy	Cost	Ideal Use Case
Gemini 1.5 Flash ⭐	Very Fast	Good	Low	Quick scans & simple queries
Gemini 1.5 Pro	Medium	High	Medium	Detailed analysis & fixes
Gemini 2.0 Flash	Fast	Very High	Medium	Cutting-edge experimental use
Gemini 2.0 Pro	Slow	Highest	High	Deep research & complex issues
