# Posture Detection System using Computer Vision

## Overview

This project implements a real-time **Posture Detection System** using Python, OpenCV, and MediaPipe. It uses landmark detection to classify a user's sitting or standing posture as either "Good" or "Bad". This project is ideal for applications in ergonomics, workplace safety, fitness tracking, and general health monitoring.

---

## Features

- Detects upper-body posture in real-time via webcam
- Uses **MediaPipe's Pose module** to extract key body landmarks
- Classifies posture as:
  - ✅ Good Posture (aligned neck, shoulders, and back)
  - ❌ Bad Posture (slouching, neck bending, or leaning)
- Displays visual cues and posture classification on-screen
- Logs real-time alerts if poor posture is detected

---

## Technologies Used

- **Python**
- **OpenCV** (for image/video processing)
- **MediaPipe** (for real-time pose detection)
- **NumPy** (for angle calculations)
- **Tkinter** (optional UI for launching webcam)

---

## Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/posture-detection-system.git
cd posture-detection-system

# Install dependencies
pip install -r requirements.txt
How to Run
bash
Copy
Edit
python posture_detection.py
To run with a GUI:

bash
Copy
Edit
python app.py
Folder Structure
graphql
Copy
Edit
posture-detection-system/
│
├── posture_detection.py        # Core logic for posture analysis
├── app.py                      # Tkinter GUI app (optional)
├── requirements.txt            # Python dependencies
├── Posture_Detection_Interview_QA.md  # Interview Q&A for the project
├── README.md                   # Project overview
Use Cases
Remote work setup monitoring

Fitness form correction

Elderly care

Office ergonomics and productivity
