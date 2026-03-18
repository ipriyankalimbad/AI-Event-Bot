AI Event Bot – Internship Project
Overview

This repository contains the implementation of an AI-powered Event Assistant Bot developed during my internship as part of an internal innovation initiative focused on enhancing participant experience in technical workshops.
The system is designed to act as a conversational assistant that provides real-time event support, personalized recommendations, and intelligent interaction using Google Gemini AI.

Project Context
Role: AI/ML Intern
Project Duration: October 2025 – December 2025
Project Type: Applied AI / Conversational Systems
Objective: Improve user engagement and streamline event navigation using AI

Key Features
1. User Authentication
Validates participant registration against a dataset
Provides personalized onboarding experience

2. Resume Processing & Personalization
Extracts skills, technologies, and experience using Google Gemini
Maps user profiles to relevant workshop sessions
Generates tailored recommendations

3. Event Information System
Provides complete workshop agenda
Supports real-time session updates
Handles logistical queries (venue navigation, facilities, etc.)
Time-aware responses (e.g., session countdowns)

4. Intelligent Networking
Identifies participants with similar skill sets
Enables meaningful peer connections

5. Feedback Collection System
Collects session-wise feedback conversationally
Supports rating (1–5) and qualitative comments
Stores structured feedback for analysis

Technical Architecture
Backend (Python Flask)
Authentication and user validation module
Resume parsing and skill extraction using Gemini API
Recommendation engine for session matching
Event query handling system (time-aware logic)
Feedback storage and processing
Frontend (HTML, CSS, JavaScript)
Responsive UI (mobile + desktop compatible)
Interactive chatbot interface
Quick-access buttons for common queries
Dynamic session display
Feedback input interface
AI Integration (Google Gemini)
Natural Language Understanding (NLU)
Context-aware conversational responses
Resume intelligence and semantic parsing
Personalized recommendation generation

System Workflow
User → Authentication → Resume Input → Chatbot Interface
                                      ↓
                          ┌───────────┴───────────┐
                          ↓                       ↓
                 Information Retrieval     Feedback Collection
                          ↓                       ↓
               Personalized Suggestions     Ratings & Insights
Implementation Details
User Validation
User enters name
System checks against registered dataset
Grants or restricts access accordingly
Resume Intelligence
Accepts resume text input
Extracts skills and experience
Matches with session topics
Generates personalized recommendations
Event Query Engine
Handles queries such as:
Session schedules and agenda
Current/next session details
Time-based queries
Venue navigation and logistics
Feedback System
Prompts after sessions
Collects ratings and comments
Stores structured feedback data
Deployment Instructions
Clone the repository

Install dependencies:
pip install -r requirements.txt
Configure API key:
export GOOGLE_API_KEY="your_api_key_here"

Run the application:
python app.py
Access locally:
http://localhost:5000

Key Learnings
Applied LLM integration (Google Gemini) in a real-world use case
Designed context-aware conversational systems
Built end-to-end AI pipeline (input → processing → recommendation → response)
Implemented user-centric system design with personalization
Gained experience in Flask-based backend development

Future Enhancements
Multi-language conversational support
Advanced participant clustering for networking
Integration with calendar and notifications
Post-event analytics dashboard
Speaker/session metadata enrichment

Conclusion
This project demonstrates the practical application of AI in event automation and user experience enhancement. It combines natural language processing, recommendation systems, and full-stack development to deliver a scalable and intelligent assistant.

The solution highlights my ability to design and implement AI-driven systems in a production-like environment, making it a strong contribution during my internship tenure.
