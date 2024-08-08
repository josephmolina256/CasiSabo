# CasiSabo
## A Spanish Language Learning App

This project is a full-stack web application designed to help users learn Spanish by having conversations with an AI chatbot. The application transcribes spoken Spanish, highlights grammatical errors, and generates AI-driven responses to improve the user's conversational skills.

## Features

- **Speech-to-Text Transcription:** Convert spoken Spanish into text using advanced speech recognition models.
- **Grammar Checking:** Identify and highlight grammatical errors in the transcribed text to help users learn correct grammar.
- **AI Chatbot:** Engage in conversations with an AI that responds intelligently in Spanish.
- **Real-time Feedback:** Receive instant feedback on spoken Spanish, with errors highlighted in red.
- **Text-to-Speech:** Hear the AI's responses in Spanish, enhancing auditory learning.

## Technologies Used

- **Backend:**
  - [FastAPI](https://fastapi.tiangolo.com/): A modern, fast web framework for building APIs with Python.
  - **Speech-to-Text Models:** Options include Whisper, faster-whisper, or WhisperX for accurate transcription.
  - **Grammar Checking:** LanguageTool or similar APIs for checking Spanish grammar.

- **Frontend:**
  - [Svelte](https://svelte.dev/): A front-end framework for building fast, interactive user interfaces.
  - [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for styling.
  - **Audio Recording:** HTML5 `MediaRecorder` API for capturing audio.

## Installation

### Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Node.js and npm](https://nodejs.org/)
- [Docker](https://www.docker.com/) (optional, for containerization)

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/spanish-learning-app.git
   cd spanish-learning-app/backend
