# LinguaBuddy 🌍

**LinguaBuddy** is an AI-powered language learning companion designed to help users practice conversation, understand tone, and learn cultural nuances. Perfect for students, travelers, or anyone looking to improve their communication skills in a new language.

---

## Features

- **Interactive Chat** – Talk with an AI in real-time.  
- **Tone Feedback** – Get insights like Formal, Casual, Polite, Rude, or Neutral.  
- **Cultural Tips** – Learn how to communicate naturally in different countries.  
- **Roleplay Scenarios** – Practice real-life situations like interviews, travel, and restaurants.  
- **Mistake History** – Track past errors to improve over time.  

---

## Tech Stack

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** FastAPI, Uvicorn  
- **AI:** AWS Bedrock (Titan Text Premier)  
- **Database:** AWS DynamoDB  
- **HTTP Requests:** Axios  

---

## How It Works

1. User sends a message through the frontend.  
2. Backend sends the message to AWS Bedrock AI.  
3. AI generates a reply, tone feedback, or cultural tip.  
4. Backend responds to the frontend and optionally saves mistakes to DynamoDB.  

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/jacklim-gif/LinguaBuddy.git
