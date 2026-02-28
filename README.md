# ✋ Hand Gesture Recognition System

##  Overview
This project implements a real-time Hand Gesture Recognition system using Computer Vision techniques. It leverages the pretrained `Hands` model from MediaPipe to detect and track 21 hand landmarks from live video input.

Custom feature engineering is performed by calculating angles and distances between landmarks to classify gestures using rule-based logic.

---

##  Features
- Real-time hand detection and tracking
- 21 landmark extraction using MediaPipe Hands
- Angle-based feature computation
- Distance-based feature computation
- Rule-based gesture classification
- Live prediction overlay
- Modular utility functions for geometric calculations

---

##  Project Workflow

1. Capture live video using OpenCV  
2. Detect hand landmarks using MediaPipe Hands  
3. Extract 21 (x, y) landmark coordinates  
4. Compute angles between key joints  
5. Compute distances between selected landmarks  
6. Apply rule-based logic to classify gestures  
7. Display prediction in real time  

---

##  System Details
- Number of Gestures: 4  
- Landmark Points Used: 21  
- Feature Engineering: Joint angles + inter-landmark distances  
- Classification Approach: Rule-based geometric logic  
- Inference: Real-time per frame  

---

##  Tech Stack
- Python  
- OpenCV  
- MediaPipe  
- NumPy  

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/ZeeshanHaider16/Hand-Gesture-Recognition.git
cd Hand-Gesture-Recognition
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the project:
```bash
python main.py
```
---

## Why This Project?
This project demonstrates:
- Real-time computer vision pipelines
- Geometric feature engineering
- Landmark-based spatial reasoning
- Modular system design
- Human–Computer Interaction concepts

---

## Future Improvements
- Replace rule-based logic with ML classifier
- Add more gesture classes
- Implement dynamic gesture recognition
- Deploy as a web-based interface

---

## Author
Zeeshan Ali

AI & Data Science Student

