LinguaBuddy 🌍
LinguaBuddy is an AI-powered language learning companion designed to help users practice conversation, understand tone, and learn cultural nuances. Perfect for students, travelers, or anyone looking to improve their communication skills in a new language.

Features
Interactive Chat – Talk with an AI in real-time.
Tone Feedback – Get insights like Formal, Casual, Polite, Rude, or Neutral.
Cultural Tips – Learn how to communicate naturally in different countries.
Roleplay Scenarios – Practice real-life situations like interviews, travel, and restaurants.
Mistake History – Track past errors to improve over time.

Tech Stack
Frontend: React.js, Tailwind CSS
Backend: FastAPI, Uvicorn
AI: AWS Bedrock (Titan Text Premier)
Database: AWS DynamoDB
HTTP Requests: Axios

How It Works
User sends a message through the frontend.
Backend sends the message to AWS Bedrock AI.
AI generates a reply, tone feedback, or cultural tip.
Backend responds to the frontend and optionally saves mistakes to DynamoDB.
Getting Started

Clone the repo:
git clone https://github.com/yourusername/LinguaBuddy.git

Set up the backend environment and install dependencies.
Run the backend server with uvicorn main:app --reload.
Run the frontend with npm install && npm start.
Maximum message length is 150 characters to avoid slow responses or server errors.

AWS Bedrock credentials and DynamoDB table setup are required.
