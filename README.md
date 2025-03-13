# Ai-Fitness-Analyzer

Overview
AI Fitness Trainer is an advanced web application that analyzes squat form in real-time using computer vision and machine learning. The application provides instant feedback on posture, counts correct and incorrect repetitions, and helps users improve their squat technique to prevent injuries and maximize workout effectiveness.

This project transforms the original Python-based Streamlit application into a modern, responsive web application built with Next.js, making it more accessible and user-friendly.

Features
Real-time Pose Detection: Tracks key body points during squats
Form Analysis: Calculates joint angles and provides posture feedback
Rep Counting: Automatically counts correct and incorrect squats
Beginner & Pro Modes: Adjustable difficulty levels with different thresholds
Visual Feedback: Clear visual indicators for form corrections
Responsive Design: Works on desktop and mobile devices
Demo Mode: Watch sample analysis before trying yourself
Technology Stack
Frontend: Next.js, React, Tailwind CSS
Computer Vision: MediaPipe for pose detection
UI Components: shadcn/ui component library
Deployment: Vercel
Original Python Components
This project is a web-based adaptation of a Python application that used:

OpenCV: For image processing
MediaPipe: For pose estimation
NumPy: For numerical operations
Streamlit: For the original UI
How It Works
The application accesses the user's camera (with permission)
Each video frame is processed to detect body landmarks
The system calculates angles between joints (hip, knee, ankle)
Based on these angles and predefined thresholds, the system:
Determines if the squat form is correct
Provides specific feedback on posture issues
Counts repetitions
Displays visual guides and angle measurements

Execution - 
streamlit run 🏠️_Demo.py
