# 🧠 YOLO Object Detection Projects

This repository contains multiple object detection mini-projects using the YOLO (You Only Look Once) family of models — including real-time video detection, PPE compliance monitoring, and object counting.

---

## 📁 Project Structure

Object-detection-Yolo/


├── Project-1/

│ ├── car-counter.py # Counts vehicles using YOLO

│ ├── sort.py # Tracking logic using SORT

│ └── mask.png # Sample overlay image



├── Project-2/

│ ├── PPE-detection.py # Detects hard hats, vests, masks, etc.

│ └── ppe.pt # Custom-trained YOLO model for PPE
│


├── videos/ # Sample input videos for both projects

│ ├── bikes.mp4

│ ├── cars.mp4

│ ├── ppe1.mp4

│ ├── ppe2.mp4

│ └── ppe3.mp4
│


├── Yolo-weights/

│ └── yolov8l.pt # YOLOv8 pre-trained weights

├── requirements.txt

└── .gitignore

-------

## 🧪 Project Highlights


### 🔸 **1. Car Counter with SORT**
- Files: `car-counter.py`, `sort.py`
- Detects and tracks cars in `cars.mp4`
- Draws bounding boxes and counts passing vehicles.

---

### 🔸 **2. PPE Detection System**
- File: `PPE-detection.py`
- Uses a custom-trained YOLOv8 model (`ppe.pt`) to detect:
  - Hardhats
  - Face masks
  - Safety vests
- Tested on `ppe1.mp4`, `ppe2.mp4`, and `ppe3.mp4`.

---

## 🧠 Model Details

- `yolov8l.pt` is the standard Ultralytics model
- `ppe.pt` is a fine-tuned YOLO model for PPE detection

---

## 🎥 Sample Input Videos

- `cars.mp4`: For count -- 
https://github.com/user-attachments/assets/50bbdba9-a0d6-4e7f-a8fa-d658aac9b198


- `ppe1.mp4`, `ppe2.mp4`, `ppe3.mp4`: For PPE testing

> Videos and model weights are not pushed to GitHub if they are too large (ignored via `.gitignore`), but are part of the local project.

---
