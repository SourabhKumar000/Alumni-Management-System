# Alumni-Management-System
A full-stack web application designed to connect students with alumni for mentorship, networking, and career growth.

✨ Features
AI Resume Analyzer: Automatic skill extraction and improvement suggestions.
Mentor Matching: Connect with alumni based on career goals and interests.
Real-time Chat: Seamless communication between students and mentors.
Job Board: Alumni can post opportunities; students can apply.
Firebase Integration: Secure authentication and storage.
🚀 Getting Started
Follow these steps to set up the project locally.

Prerequisites
Node.js (v16+ recommended)
NPM or Yarn
A Firebase Project (for Auth, Firestore, and Storage)
1. Clone the Repository
git clone https://github.com/anuraag004/Alumni-Management-System.git
cd Alumni-Management-System
2. Backend Setup (Server)
Navigate to the server directory:
cd server
Install dependencies:
npm install
Configure environment variables:
Copy .env.example to .env
Fill in your JWT_SECRET, Firebase Admin SDK credentials, and SMTP settings.
Start the server:
npm run dev
3. Frontend Setup (Client)
Navigate to the client directory (from the root):
cd client
Install dependencies:
npm install
Configure environment variables:
Copy .env.example to .env
Add your Firebase Client SDK configuration.
Start the development server:
npm run dev
🛠️ Tech Stack
Frontend: React.js, Vite, Tailwind CSS
Backend: Node.js, Express.js
Database: Firebase (Firestore)
Real-time: Socket.io
AI: Integration with resume parsing logic
🔒 Security Note
Never commit your .env files. The project contains a .gitignore that automatically excludes these for your safety. Always use the provided .env.example templates for deployment.
