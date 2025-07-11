# CodeAlpha_Object-detection-and-tracking
I developed a real-time object detection and tracking system using the latest Ultralytics YOLOv8 model. This system uses OpenCV to access the webcam and display live detections with class labels and confidence scores.
# 🎯 Task 4: Real-Time Object Detection and Tracking using YOLOv8

This project performs real-time object detection and tracking using a webcam feed, leveraging the YOLOv8 model from the Ultralytics library. It uses OpenCV for video handling and display.

---

## 📦 Features

- Live webcam feed processing
- Object detection using YOLOv8 (`yolov8n.pt`)
- Bounding boxes and labels with confidence scores
- Real-time display with keyboard interrupt

## 🛠 Requirements

Install Python dependencies:
pip install ultralytics opencv-python
🚀 Getting Started
1. Clone or download this repository
Or unzip the provided folder.
2. Run the script
python object_detection.py
This will:
Open your webcam
Detect and label objects in real-time
Show results in a pop-up window

Model
Uses YOLOv8 Nano (yolov8n.pt) for speed and efficiency
You can switch to other variants: yolov8s.pt, yolov8m.pt, etc.
