# Face Recognition Attendance System

## 📊 Project Overview

A Python-based face recognition attendance system that uses computer vision to recognize registered individuals and record their attendance.

The application uses a webcam to detect and recognize faces, trains a face recognition model, and generates attendance records with the person's ID, name, date, and time.

## 🔄 Application Workflow

Check Camera  
→ Capture Faces  
→ Train Images  
→ Recognize Face  
→ Record Attendance  
→ Generate Attendance CSV

## 🔍 Key Features

- Webcam camera testing
- Face detection using Haar Cascade
- Face image capture
- Face recognition model training
- Real-time face recognition
- Student ID and name identification
- Automatic attendance recording
- Date and time tracking
- Duplicate attendance prevention
- Attendance export to CSV

## 🛠️ Technologies & Libraries

- Python
- OpenCV
- LBPH Face Recognizer
- Haar Cascade Classifier
- NumPy
- Pandas
- Pillow

## 🎯 Key Skills Demonstrated

- Python Programming
- Computer Vision
- Face Recognition
- Image Processing
- OpenCV
- Machine Learning
- Real-Time Video Processing
- Data Handling with Pandas
- CSV Data Management
- Attendance Automation

## 📁 Project Structure

```text
Face-Recognition-Attendance-System/
│
├── Capture_Image.py
├── Home.py
├── Recognize.py
├── Train_Image.py
├── check_camera.py
├── haarcascade_frontalface_default.xml
├── main.py
└── README.md
