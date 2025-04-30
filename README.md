# AI Fitness Trainer 🏋️‍♂️

A real-time exercise tracking application using pose estimation and AI feedback. Tracks push-ups and squats with form analysis using MediaPipe and Gemini AI.



## Features ✨

- **Real-time Pose Tracking**: MediaPipe for body landmark detection
- **Exercise Counting**: Push-ups and squats counter
- **Form Analysis**: Joint angle calculations for form feedback
- **AI Feedback**: Gemini API for personalized exercise tips
- **Web Interface**: Flask-based video streaming dashboard
- **REST API**: Endpoints for exercise control and data

## Technologies 🛠️

- **Computer Vision**: MediaPipe, OpenCV
- **AI**: Google Gemini API
- **Backend**: Flask, REST API
- **Frontend**: MJPEG streaming, JavaScript

## Installation 💻

1. **Clone Repository**

Split Terminal

Teminal 1: 


cd .\aifeatures\


 npm install

 
 npm run dev


Terminal 2: 


 cd '.\py pushups\'

 
 pip install flask flask-cors opencv-python mediapipe numpy google-generativeai

 
 python app.py


open  http://localhost:5173/
