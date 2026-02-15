# JanSaathi Requirements Document

## Project Overview
JanSaathi is an offline AI-powered voice assistant designed to help rural Indian citizens access healthcare and government welfare schemes easily in their local languages.

---

## Functional Requirements

### 1. Voice-Based User Interaction
- Users should be able to speak their queries
- System must support multilingual input
- Convert speech to text for processing

### 2. Government Scheme Eligibility Detection
- Collect user details through voice input
- Match user data with scheme database
- Display eligible schemes

### 3. Prescription Explainer
- Upload prescription image
- Extract text using OCR
- Explain medicine usage in simple language

### 4. Smart Reminder System
- Vaccination reminders
- Medication reminders
- Health checkup reminders

### 5. Farmer Mode
- Provide crop subsidy schemes
- Show insurance eligibility
- Provide mandi information

---

## Non Functional Requirements

- Must work in low bandwidth environments
- Mobile-first design
- Offline-first functionality
- Local language support
- Simple UI for accessibility

---

## System Requirements

- React Frontend
- FastAPI Backend
- OCR Integration
- Speech Recognition
