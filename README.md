# 📱 Electronic Component Detector (YOLOv8 + TFLite + Flutter)

## 👨‍💻 Author
Naga Phanindra  
Semester 6  

---

## 📌 Project Overview

This project is an AI-powered mobile application that detects and identifies electronic components such as resistors, capacitors, LCDs, wires, breadboards, and more using computer vision.

The system is built using **YOLOv8 for object detection**, trained in Google Colab, and deployed as a **TensorFlow Lite model inside a Flutter mobile application** for fully offline inference.

---

## 🚀 Key Features

- 📷 Capture image using mobile camera  
- 🖼️ Upload image from gallery  
- 🤖 Detect multiple electronic components  
- 🟩 Draw bounding boxes with labels  
- 📊 Display confidence scores  
- 🔢 Count number of detected components  
- 🌐 Fully offline (no internet required)

---
## 📂 Dataset

Due to GitHub file size limitations, the dataset is hosted on Google Drive.

👉 **Dataset Download Link:**  
https://drive.google.com/file/d/1ZI_zvX8rXeb8RATNIyHMXgDQFyw0nWYH/view?usp=drive_link

📦 Dataset Size: ~3MB

## 📱 Mobile Application Source Code

Due to large file size (~1.1GB), the complete Flutter application is hosted on Google Drive.

👉 **Download Mobile App Code:**  
https://drive.google.com/file/d/1HP3j4on0und-qIVrQdfwOEixPBER9fiJ/view?usp=sharing



## 🧠 System Workflow

```text
Dataset Collection → Training (YOLOv8) → Model Export (TFLite)
→ Mobile App Integration → Real-time Detection
