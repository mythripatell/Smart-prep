Smart Prep AI – AI Mock Interview Agent
Smart Prep AI is a full-stack web application that uses artificial intelligence to conduct realistic mock interviews for job seekers. Built with Vite, React.js, HTML, and CSS, this application simulates technical and behavioral interviews, provides instant feedback, and helps candidates improve their performance with personalized practice sessions.

Features
AI-driven technical and behavioral interview questions tailored to the user's profile.

Real-time feedback using AI APIs for improvement tips.

Secure user authentication and registration.

Personalized and job-specific interview sessions, with progress tracking.

Data persistence for user history and session analytics.

Responsive user interface optimized for desktop and mobile.

Tech Stack
Frontend: Vite, React.js, HTML, CSS

Backend: Node.js

Database:  Firebase 

Authentication: Clerk 

AI Integration: Gemini API 

Package Manager: pnpm

Getting Started
Prerequisites
Node.js (latest LTS recommended)

pnpm (install with npm install -g pnpm)

(If applicable) MongoDB Atlas/Firebase project, necessary API keys

Installation
Clone the repository:

text
git clone https://github.com/your-username/smart-prep-ai.git
cd smart-prep-ai
Install dependencies:

text
pnpm install
Set up environment variables:

Create a .env file in the project root.

Example:

text
VITE_GEMINI_API_KEY=your_key
Run the application in development mode:

text
pnpm run dev
For full-stack setup, run the backend in a separate terminal as per /server/README.md or backend folder instructions.

Usage
Register or log in to your account.

Start a mock interview by selecting job role and difficulty.

Answer AI-generated questions in real time.

Review instant feedback and suggestions for improvement.

Track your progress and revisit past sessions from your profile.

Folder Structure
text
/smart-prep-ai
|-- /src
|   |-- /components
|   |-- /pages
|   |-- /assets
|-- /server (backend, if included)
|-- package.json
|-- pnpm-lock.yaml
|-- vite.config.js
|-- README.md
Contributing
Fork this repository

Create a new branch (git checkout -b feature/feature-name)

Make your changes and commit (git commit -m 'Add some feature')

Push to the branch (git push origin feature/feature-name)

Open a pull request for review

License
MIT License. Please see the LICENSE file.
