# YOLOv8 Object Detection App

This repository demonstrates real-time object detection using Ultralytics YOLOv8
It includes:
- Live webcam detection (OpenCV)
- Streamlit app for image upload and inference

## 🚀 Features
- Run YOLOv8 (nano or large models) on your webcam in real-time
- Upload an image and run inference in a web app (Streamlit)
- Adjustable confidence threshold to filter detections

## 📦 Installation

Clone the repo and install dependencies:

git clone https://github.com/RishiSrivastava17/Object-Detection-Using-Open-CV-StreamLit-etc.git
cd Object-Detection-Using-Open-CV-StreamLit-etc


# Install dependencies
pip install -r requirements.txt

requirements.txt
```bash
ultralytics
opencv-python
streamlit
pillow
matplotlib
numpy
```

## ▶️ Usage
1. Webcam Detection (OpenCV)
```bash
python webcam_detect.py
```
Press q to quit the webcam stream

2. Streamlit App (Image Upload)
```bash
streamlit run app.py
```
- Opens a browser at http://localhost:8501
- Upload an image and view YOLO detections

## 📂 Project Structure
├── app.py              # Streamlit app for image detection
├── webcam_detect.py    # OpenCV webcam detection script
├── requirements.txt    # Dependencies
├── test.jpg            # Sample image (optional)
└── README.md

## ⚡ Example
Webcam Detection
Running YOLOv8-L on webcam. Press 'q' to exit.

Streamlit
Upload an image → see bounding boxes drawn on detected objects:

## 🛠 Troubleshooting
- If you see ModuleNotFoundError: No module named 'streamlit', ensure you’re installing packages with the same Python executable
- YOLO model weights will auto-download (e.g. yolov8n.pt, yolov8l.pt)

## 📜 License
MIT License – free to use and modify.
