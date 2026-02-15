# Learnexa - AI Study Companion Design

## System Architecture
- **Frontend:** HTML, CSS, JavaScript for interactive UI.
- **Backend:** PHP for handling API requests, user management, and quiz logic.
- **Database:** MySQL for storing user data, quizzes, and analytics.
- **AI Services:** Ollama API for:
  - Topic summarization
  - MCQ quiz generation
  - Personalized study roadmap
  - Question-answer assistant

## Component Diagram
1. **User Interface**
   - Login/Signup pages
   - Dashboard
   - Quiz interface
   - Analytics view

2. **Backend API (PHP)**
   - Auth API
   - Quiz API
   - Analytics API
   - Ollama AI API integration

3. **AI Layer (Ollama API)**
   - Topic Summarization Engine
   - MCQ Generation Engine
   - Personalized Study Roadmap Engine
   - Question-Answer Engine

4. **Database Layer (MySQL)**
   - User profiles
   - Quiz history
   - Progress analytics

## Data Flow
1. Student logs in → PHP backend validates → Dashboard loads.
2. Student selects topic → PHP calls Ollama API → Quiz/summary generated → Displayed to user.
3. Backend stores results → Analytics updated → Study recommendations suggested.
4. Student asks question → Ollama AI API responds → Answer displayed instantly.

## UI/UX Design
- Responsive design using HTML/CSS/JS.
- Session-based dashboard for real-time progress tracking.
- Visual highlights for weak areas and suggested topics.

## Technology Stack
- HTML, CSS, JavaScript (Frontend)
- PHP (Backend)
- MySQL (Database)
- Ollama API (AI Services)
- Optional: Chart.js / D3.js for analytics visualization