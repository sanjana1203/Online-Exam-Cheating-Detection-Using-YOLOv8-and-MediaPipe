# Online-Exam-Cheating-Detection-Using-YOLOv8-and-MediaPipe

An AI-powered online exam proctoring system that detects suspicious activities during online examinations using **YOLOv8**, **MediaPipe**, **OpenCV**, and **Computer Vision**. The system analyzes live webcam footage to identify potential cheating behaviors such as multiple person detection, face absence, head movement, mobile phone usage, and other abnormal activities, helping improve the integrity of online assessments.

---

## Project Overview

With the rise of online education, maintaining exam integrity has become a significant challenge. This project provides an automated proctoring solution that monitors students through a webcam and detects suspicious activities in real time using advanced computer vision techniques.

The project was developed entirely in **Google Colab** using Python and modern AI libraries.

---

## Features

- Real-time face detection
- Mobile phone detection using YOLOv8
- Multiple person detection
- Face absence detection
- Head pose and face landmark analysis using MediaPipe
- Suspicious activity alerts
- Live webcam monitoring
- Real-time detection visualization
- AI-powered computer vision-based proctoring

---

## Technologies Used

- Python
- Google Colab
- OpenCV
- YOLOv8 (Ultralytics)
- MediaPipe
- NumPy
- Matplotlib
- IPython
- Computer Vision
- Deep Learning

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Online-Exam-Cheating-Detection.git

cd Online-Exam-Cheating-Detection
```

Install the required libraries

```bash
pip install -r requirements.txt
```

---

## Usage

1. Open the notebook in **Google Colab** or Jupyter Notebook.
2. Install the required dependencies.
3. Download the required YOLOv8 model weights if prompted.
4. Enable webcam access.
5. Run all notebook cells sequentially.
6. The system will start monitoring the live video feed and detect suspicious activities in real time.

---

## Workflow

```
Live Webcam Feed
        │
        ▼
Frame Capture
        │
        ▼
YOLOv8 Object Detection
        │
        ▼
MediaPipe Face Landmark Detection
        │
        ▼
Cheating Behaviour Analysis
        │
        ▼
Alert Generation
        │
        ▼
Real-Time Monitoring Output
```

---

## Detection Capabilities

The system can identify:

- Face not visible
- Multiple persons in the frame
- Mobile phone usage
- Excessive head movement
- Suspicious face orientation
- Potential cheating behaviour
- Continuous monitoring throughout the examination

---

## Expected Results

- Accurate real-time object detection
- Fast webcam processing
- Automated cheating alerts
- Improved online exam monitoring
- Reduced manual invigilation effort

---

## Future Enhancements

- Eye gaze tracking
- Voice activity detection
- Browser activity monitoring
- Multi-camera support
- Face recognition for candidate verification
- Cloud-based monitoring dashboard
- Automated report generation
- AI-based behavioural scoring

---

## Applications

- Online University Examinations
- Competitive Exams
- Certification Platforms
- Remote Hiring Assessments
- Online Learning Platforms
- Virtual Classrooms

---


## Author

**Sanjana H. Kurtakoti**
---
