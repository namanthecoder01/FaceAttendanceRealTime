Face Attendance Real-Time System

Description:

This project implements real-time face recognition for attendance tracking using Python, OpenCV, face_recognition, Firebase for database and storage, and CVZone for graphical overlays.

Features:

Real-time Face Recognition: Detects faces using webcam, compares them with known faces stored in Firebase.

Attendance Tracking: Updates attendance records based on recognized faces.

Visual Feedback: Displays graphical overlays indicating face detection and attendance status.

Requirements:

Python 3.x

OpenCV

face_recognition

Firebase Admin SDK

CVZone

numpy

Setup:

Install dependencies:

bash

pip install opencv-python face-recognition firebase-admin cvzone numpy

Add Firebase service account credentials (serviceAccountKey.json) and configure the Firebase database and storage URLs in the code.

Place mode images (background.png and others) in Resources/Modes directory.

Ensure EncodeFile.p contains serialized face encodings and associated student IDs for recognition.

Usage:

Run the script (python face_attendance.py) to start the real-time face attendance system.

Ensure proper lighting and camera positioning for accurate face detection and recognition.

Author:

Naman Jain
