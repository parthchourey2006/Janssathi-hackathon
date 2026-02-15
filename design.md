JanSaathi System Design Document

Architecture Overview

JanSaathi follows a modular AI-powered architecture designed for offline-first accessibility.

---

 Frontend

- Built using React.js
- Tailwind CSS for UI styling
- Mobile-first responsive design
- Voice input interface

---

Backend

- FastAPI based REST API
- Handles AI model communication
- Processes scheme eligibility logic

---

AI Components

 Speech Processing
- Converts voice input to text

 NLP Engine
- Extracts user information
- Detects scheme eligibility

 OCR Engine
- Reads prescription images
- Converts medical data to text

---

Database

- SQLite for offline storage
- Government scheme dataset
- Healthcare reference dataset

---

Workflow

1. User provides voice input
2. Speech-to-text processing
3. AI processes extracted data
4. Database matching
5. Voice/text response generated

---

UI Design

- Clean card-based layout
- Rounded elements
- Deep Blue + Light Green theme
- Accessible typography

---

Scalability

- Can support multiple Indian languages
- Government system integration possible
- Expandable AI modules
