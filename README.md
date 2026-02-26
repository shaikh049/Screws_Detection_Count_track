# 🔩 Screw Classification, Detection & Counting (Computer Vision Case Study)

## 📌 Project Overview
This project focuses on building an automated computer vision system that can detect, classify, and count different types of screws from images. The system is designed for industrial visual inspection where multiple screws of varying lengths and types appear in a single image.

The model identifies each screw, classifies it into its respective category (Type A, Type B, Type C), and provides the total count per class along with the overall screw count from validation images.

---

## 🎯 Problem Statement
In manufacturing and quality inspection, manual screw counting and classification is time-consuming and error-prone.  
This project solves the problem by automating:
- Screw detection
- Screw type classification
- Screw counting per category
- Total screw quantification from images

---

## 🧠 Key Features
- Detects multiple screws in a single image
- Classifies screws into 3 different types
- Handles screws with different lengths and sizes
- Provides class-wise and total screw count
- Works on plain background industrial images
- End-to-End Object Detection Pipeline

---

## 🗂️ Dataset Details
- Training Images: 31
- Validation Images: 6
- Background: Plain
- Classes:
  - Screw_Type_A
  - Screw_Type_B
  - Screw_Type_C
- Annotation Format: YOLO (Bounding Boxes)

---

## 🛠️ Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Matplotlib
- Roboflow (for annotation)
- VS Code (Development Environment)

---

## 🏗️ Project Workflow
1. Data Collection
2. Image Annotation (Bounding Box Labeling)
3. Dataset Preparation (YOLO Format)
4. Model Training using YOLOv8
5. Object Detection on Validation Data
6. Screw Classification per Type
7. Automated Counting & Final Report Generation

---

## ⚙️ Model Used
YOLOv8 Nano (Pretrained) was fine-tuned on a custom screw dataset to perform real-time object detection and classification.

Why YOLOv8?
- Fast and accurate
- Suitable for small datasets
- Real-time industrial inspection capability
- Easy deployment

---

## 📊 Output Example
