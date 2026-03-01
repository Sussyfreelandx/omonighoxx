# Omonighoxx - Defense & Aerospace Corporate Website (Scaffold)

This repository contains a scaffold for an enterprise-level defense, aerospace, and security technology company website with a Careers/job portal and Telegram-backed application notifications. It is designed for deployment on Netlify using Next.js and Netlify Functions.

## Overview
- Frontend: Next.js + Tailwind CSS (React)
- Serverless: Netlify Functions (Node.js) for application handling and Telegram notifications
- Storage: configurable (MongoDB Atlas / PostgreSQL / Firestore). This scaffold uses API placeholders — configure DATABASE_URL or adapt functions to your DB.

## Environment variables (set in Netlify deploy settings):
- TELEGRAM_BOT_TOKEN - Bot token from @BotFather
- TELEGRAM_CHAT_ID - Chat or group ID where HR gets notified
- DATABASE_URL - optional DB connection string
- NEXT_PUBLIC_API_BASE - optional API base URL for client-side calls

## How to run locally
1. Install deps: npm install
2. Run dev: npm run dev
3. Netlify functions: use netlify dev or the Netlify CLI for local function testing.

## Notes
- This is a scaffold focused on structure, API endpoints, and Telegram integration points. Implement secure DB storage, file uploads (S3/Cloud Storage), and GDPR-compliant retention in production.
