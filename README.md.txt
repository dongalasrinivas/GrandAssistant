# Voice-First AI Assistant for Elderly Parents

A real-time, voice-activated AI memory and reminder assistant built for elderly parents living independently. It leverages the Gemini Live API via WebSockets to enable bidirectional conversational tracking, utility reminders, financial memory, and health logging.

## Core Features
- **Voice-First Interface:** No typing required. A large, accessible button initiates a live listening session.
- **Code-Mixing Support:** Natural Language Processing instructed to understand and speak a mix of regional English and Telugu seamlessly.
- **Memory & Tracking:** Uses Gemini Tool Calling to log blood pressure readings, remind about gas/electricity bills, and securely track financial lending to friends and family.
- **Noise-Tolerant Conversational AI:** System persona is designed to ask polite clarification questions ("Amma, did you say...") instead of failing when TV noise interferes.

## Prerequisites
- Docker and Docker Compose
- A Google Gemini API Key (Must have access to `gemini-3.8-live` or standard Live API variants).

## Setup Instructions

1. **Clone the repository:**
   Ensure your directory structure looks like this:
   ```text
   /project
     ├── templates/
     │   └── index.html
     ├── app.py
     ├── requirements.txt
     ├── Dockerfile
     ├── docker-compose.yml
     └── .env