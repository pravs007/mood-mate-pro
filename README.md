# MoodMate Pro — AI-Powered Emotion-Based Music Recommendation System

MoodMate Pro is an AI-powered full-stack application that detects user emotions from text or facial input and recommends songs based on the detected mood in real time.

The project combines Artificial Intelligence, Machine Learning, Emotion Recognition, and REST APIs to create a personalized music recommendation experience.

---

## Problem Statement

Traditional music recommendation platforms mainly rely on listening history and popularity trends without understanding the user’s emotional state.

MoodMate Pro solves this problem by:
- Detecting emotions using AI models
- Understanding user mood from text and facial expressions
- Generating personalized music recommendations
- Creating an emotionally adaptive user experience

---

## Features

- AI-based emotion detection
- Text emotion analysis
- Facial emotion recognition
- Mood-based song recommendation system
- End-to-end AI recommendation pipeline
- Flask REST API backend
- Frontend-backend integration
- JSON-based API communication

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask
- Flask-CORS

### AI / Machine Learning
- NLP-based Emotion Detection
- Facial Emotion Recognition
- Recommendation System

---

## Project Structure

```bash
moodmate-pro/
│
├── backend/
│   ├── app.py
│   ├── full_pipeline.py
│   ├── music_recommender.py
│   ├── requirements.txt
│   │
│   ├── pipeline1/
│   │   └── emotion_router.py
│   │
│   ├── pipeline2/
│   ├── models/
│   └── notebooks/
│
├── Procfile
├── index.html
└── .gitignore
