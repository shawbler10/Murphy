Murphy - Your AI Onboarding Buddy
Murphy is an intelligent, friendly, and proactive AI-powered companion designed to streamline the onboarding process for new hires. It aims to transform a potentially overwhelming experience into an engaging, supportive, and efficient journey, ensuring every new team member feels welcomed, informed, and ready to contribute from day one.

🎯 The Problem
Traditional onboarding can be fragmented and impersonal. New hires are often inundated with documents, unsure of who to ask for simple questions, and struggle to understand company culture and unwritten rules. This can lead to:

Slower ramp-up time and productivity loss.

Increased anxiety and confusion for the new hire.

A heavy, repetitive burden on HR staff, managers, and teammates.

✨ The Solution: Murphy
Murphy acts as a 24/7 personal guide for new employees. By leveraging the power of a Large Language Model (like the Gemini API), it provides instant, accurate, and context-aware answers to a wide range of questions, from "Where do I find the benefits enrollment form?" to "What's the best place to get coffee near the office?"

Key Features
🤖 Conversational Q&A: Get instant answers to questions about HR policies, company tools, team members, and cultural norms.

✅ Personalized Task Checklists: Murphy delivers a dynamic onboarding plan, guiding new hires through their Day 1, Week 1, and Month 1 tasks.

🗓️ Smart Calendar Integration: Proactively reminds new hires about important meetings, 1:1s, and training sessions. It can even suggest talking points!

🤝 Team & Culture Introductions: Provides friendly introductions to key team members and shares insights into the company's culture and values.

🧠 Context-Aware Support: Murphy learns from company documentation (Confluence, Google Drive, etc.) to provide answers that are always up-to-date and relevant.

💬 Seamless Integration: Designed to live where you work, with integrations for Slack, Microsoft Teams, and email.

🛠️ Built With
This project is conceptual, but the proposed technology stack would be:

AI Engine: Google Gemini API

Backend: Python with FastAPI

Frontend: React with TypeScript

Database: PostgreSQL for structured data and Pinecone for vector embeddings.

Integrations: Slack API, Microsoft Graph API, Google Workspace API.

Deployment: Docker, Kubernetes, Google Cloud Platform / AWS.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
You will need to have the following installed on your local machine:

Python 3.9+

Node.js v18+ and npm

Git

Installation
Clone the repo

Bash

git clone https://github.com/your-username/murphy-ai-onboarding.git
cd murphy-ai-onboarding
Set up the Backend (Python)

Bash

# Navigate to the backend directory
cd server

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
Set up the Frontend (React)

Bash

# Navigate to the frontend directory
cd ../client

# Install NPM packages
npm install
Configure Environment Variables
Create a .env file in the server directory and add your API keys and configuration:

Code snippet

# .env Example
GEMINI_API_KEY='YOUR_API_KEY'
DATABASE_URL='postgresql://user:password@localhost/murphy'
SLACK_BOT_TOKEN='YOUR_SLACK_TOKEN'
Usage
Run the Backend Server:
From the server directory:

Bash

uvicorn main:app --reload
Run the Frontend Application:
From the client directory:

Bash

npm run dev
Open http://localhost:3000 to view it in your browser.

🗺️ Roadmap
[ ] Phase 1: Core Q&A and Task Management

[x] Basic conversational interface.

[ ] Ingest and index company documents.

[ ] Static onboarding checklists.

[ ] Phase 2: Proactive Assistance & Integrations

[ ] Slack/Teams integration.

[ ] Google/Outlook Calendar integration for smart reminders.

[ ] Phase 3: Advanced Personalization

[ ] Role-based onboarding paths (e.g., Engineer vs. Sales).

[ ] Sentiment analysis to gauge new hire satisfaction.

[ ] Manager dashboard to track new hire progress.

See the open issues for a full list of proposed features (and known issues).

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
See lisence.txt

📧 Contact
Mike Shaw - mikeshaw@treasuryprime.com
