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

## 🧠 System Workflow

```text
Dataset Collection → Training (YOLOv8) → Model Export (TFLite)
→ Mobile App Integration → Real-time Detection
