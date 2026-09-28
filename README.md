# YOLO Custom Object Detection (Real-Time)

## 📌 Project Overview
This project demonstrates a complete end-to-end object detection pipeline using YOLOv8.  
The model is trained on a custom dataset and deployed for real-time detection using a webcam.

---

## 🎯 Objectives
- Collect and label custom dataset
- Train YOLOv8 model using Google Colab (GPU)
- Evaluate performance using mAP
- Deploy real-time detection using OpenCV

---

## 🧠 Classes Used
- Bottle
- Book
- Phone

---

## 🗂 Dataset
- Custom dataset created manually
- Labeled using Roboflow
- Format: YOLOv8

---

## ⚙️ Model Training
- Framework: Ultralytics YOLOv8
- Model: yolov8n.pt (pretrained)
- Epochs: 50
- Image Size: 640

---

## 📊 Performance
- mAP50: ~0.23  
- Precision: ~0.60  
- Recall: ~0.08  

*(Performance is limited due to small dataset size)*

---

## 🚀 Real-Time Detection
- Implemented using OpenCV
- Webcam input processed frame-by-frame
- Bounding boxes, class labels, and confidence scores displayed

---

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install ultralytics opencv-python

### Run detection
   python detect.py
   
## PRoject Structure
 yolo-realtime-detector/
│
├── best.pt
├── detect.py
├── yolo_training.ipynb
└── README.md

## Demo Output (Real-Time Detection)
  https://drive.google.com/your-demo-video-link
