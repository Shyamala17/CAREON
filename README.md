CAREON (Community Awareness & Reporting Online Network)
📌 Overview
CAREON is a full‑stack application built to empower students, youngsters, NGOs, government agencies, health workers, and the public. It provides a multilingual platform for reporting incidents, tracking community hotspots, and predicting health risks. CAREON integrates a backend API, a modern frontend, an AI robotic agent, and a YouTube welcome video to deliver a complete, accessible solution.

🔧 Tech Stack
Backend: Node.js, Express, MongoDB, Redis

Frontend: React / Next.js

Deployment: Vercel (frontend), Render/Heroku (backend)

AI Agent: Multilingual chatbot + voice assistant (Tamil, English, Hindi, French, Malayalam, etc.)

Video: YouTube welcome demo embedded in dashboard

🚀 Features
Secure JWT authentication (signup/login)

Report submission and paginated listings

Search filters for location/date

Hotspot prediction with Redis caching

Rate limiting + error handling middleware

Swagger API docs at /api-docs

Responsive frontend with charts/maps

AI robotic agent for text + audio guidance

Welcome video explaining CAREON’s purpose and usage

📹 Welcome Video Content
Why CAREON was created: community safety, health transparency, real‑time awareness

Who can use it: students, youngsters, NGOs, government, health workers, public

Problems solved: delayed reporting, lack of transparency, no multilingual guidance

How to use: login → submit report → view dashboard → check predictions

Future vision: expansion to more cities, integration with government systems, real‑time alerts

✅ Benefits
Community Safety: Easy reporting of incidents

Health Transparency: Predict outbreak zones

Government/NGO Integration: Share real‑time alerts

User Empowerment: Multilingual AI guidance

Future Expansion: AI analytics, IoT integration, dashboards for authorities

🖥️ Deployment
Backend: Push to GitHub → Deploy on Render/Heroku

Frontend: Push to GitHub → Deploy on Vercel

Configure environment variables:

MONGO_URI

JWT_SECRET

REDIS_URL

PORT

🎯 Final Output
Backend logs:

Code
✅ MongoDB Connected
✅ Redis Connected
🚀 Server running on port 5000
Endpoints: /api-docs, /api/auth/signup, /api/auth/login, /api/reports, /api/predict

Frontend: login, dashboard, reports, predictions, AI chatbot, embedded welcome video

YouTube video: animated, multilingual, professional, explaining CAREON fully
