# Signoasis – Real-Time Sign Language Learning & Interpretation Platform 
## Overview
Signoasis is a Machine Learning–based web platform designed to improve communication accessibility for Deaf, Hard of Hearing, visually impaired, and non-signing individuals. The platform combines an interactive sign language learning environment with a real-time sign language interpreter to create an inclusive communication experience.Using Computer Vision, MediaPipe, and an LSTM-based Deep Learning model, the system captures hand gestures through a webcam, recognizes sign movements in real time, and converts them into text and speech output. The platform also provides interactive learning modules, quizzes, and progress tracking for effective sign language learning. 

# Problem Statement 
Communication barriers between hearing-impaired individuals and non-signers create challenges in education, workplaces, healthcare, and everyday communication. Existing solutions are often expensive, hardware-dependent, or lack accessibility-focused features.Signoasis aims to bridge this gap through a real-time, web-based sign language interpretation and learning system. 

# Features 
## Learning Platform 
- Interactive sign language tutorials
- Flashcards and practice modules
- Quiz and self-assessment system
- Progress tracking
  
## Real-Time Interpreter
- Webcam-based gesture capture
- Real-time sign language recognition
- Text output generation
- Speech output using Text-to-Speech (TTS)

## Accessibility Features 
- Voice-assisted communication
- User-friendly interface
- Inclusive communication support

# Tech Stack 
## Frontend 
- HTML
- CSS
- JavaScript
## Backend 
- Python
- PHP
## Machine Learning & Computer Vision 
- TensorFlow
- LSTM
- MediaPipe
- OpenCV
- NumPy
- Pandas
## Database 
- MySQL
## Development Tools 
- Jupyter Notebook
- Visual Studio Code
- Git & GitHub

# System Workflow 
1. Webcam captures live gesture frames
2. MediaPipe extracts face, hand, and body landmarks
3. Keypoints are converted into NumPy arrays
4. LSTM model processes temporal gesture sequences 
5. Model predicts the corresponding sign
6. Output is displayed as text and speech

# Why LSTM?
LSTM (Long Short-Term Memory) was selected because sign language recognition involves sequential movement patterns over time.
## Advantages of LSTM 
- Handles long-term dependencies
- Avoids vanishing gradient issues
- Performs well on sequential gesture recognition
- Maintains contextual understanding across frames

# Modules
## 1. Learning Module Provides users with:
- Tutorials
- Interactive lessons
- Quizzes
- Progress monitoring
## 2. Interpreter Module Provides: 
- Real-time gesture recognition
- Gesture-to-text conversion
- Gesture-to-speech conversion

# Project Goals 
- Improve accessibility through assistive technology
- Enable independent communication
- Create an interactive learning experience
- Build a scalable real-time recognition system 

# Results 
- Successful real-time gesture recognition
- Improved feature extraction using MediaPipe landmarks
- Real-time text and speech generation
- Tested under multiple lighting and gesture conditions

# Future Enhancements 
- Sentence-level recognition
- Multilingual sign language support
- Mobile application deployment
- Transformer-based gesture recognition
- AI chatbot integration

# Author

Sabitha V  
MBA (Business Analysis Major | HR Minor)  
B.Sc Computer Science  

Sanjana B  
M.Sc AI & ML  
B.Sc Computer Science  

# Installation 
```bash git clone https://github.com/yourusername/Signoasis.git cd Signoasis
pip install -r requirements.txt
python app.py
