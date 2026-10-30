AI Interview Preparation Platform

An AI-powered interview preparation web application that helps users analyze their resumes, identify skill gaps, prepare interview questions, and generate personalized interview reports.

Features

- User registration and login
- JWT-based authentication
- Resume PDF upload and processing
- AI-powered interview preparation using Google Gemini
- Technical and behavioral interview questions
- Personalized skill-gap analysis and preparation roadmap
- Interview report storage using MongoDB
- Resume PDF generation and download

Features listed above should be retained only if implemented and tested in the current version.

Tech Stack

Frontend

- React
- Vite
- JavaScript
- Sass

Backend

- Node.js
- Express.js
- MongoDB and Mongoose
- JSON Web Tokens (JWT)
- Google Gemini API
- Multer
- Puppeteer

Prerequisites

- Node.js and npm
- A MongoDB database (MongoDB Atlas or local MongoDB)
- A Google Gemini API key

Installation

1. Clone this repository

git clone YOUR_REPOSITORY_URL
cd AI-Interview-Preparation

2. Install backend dependencies

cd Backend
npm install

3. Configure environment variables

Create a ".env" file inside the "Backend" directory. Use the variable names required by the source code.

Example template:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_private_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key

Check the backend source code for any additional required variables.

Never commit your actual ".env" file or expose API keys and database credentials.

4. Start the backend

npm run dev

The current backend entry point starts the server on port "3000".

5. Install frontend dependencies

Open a second terminal from the project root:

cd Frontend
npm install

6. Start the frontend

npm run dev

Open the local URL displayed by Vite in your browser, usually "http://localhost:5173".

