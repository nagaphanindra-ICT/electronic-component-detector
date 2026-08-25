# 📱 Electronic Component Detector

### YOLOv8 + TensorFlow Lite + Flutter

An AI-powered mobile application for detecting and identifying electronic components using computer vision and deep learning.

---

## 👨‍💻 Author

**Naga Phanindra**
Semester 6

---

## 📌 Project Overview

The **Electronic Component Detector** is an AI-powered mobile application that detects and identifies electronic components from images using **YOLOv8 object detection**.

The model is trained using a custom dataset in **Google Colab**, exported to **TensorFlow Lite (TFLite)**, and integrated into a **Flutter mobile application** for offline inference.

The application can detect components such as:

* Resistors
* Capacitors
* LCD displays
* Wires
* Breadboards
* Integrated circuits
* Other electronic components included in the trained dataset

The complete detection process runs locally on the mobile device, so an internet connection is not required.

---

## 🚀 Key Features

* 📷 Capture images using the mobile camera
* 🖼️ Select images from the gallery
* 🤖 Detect multiple electronic components
* 🟩 Display bounding boxes around detected objects
* 🏷️ Show component names
* 📊 Display detection confidence scores
* 🔢 Count detected components
* ⚡ Perform inference directly on the mobile device
* 🌐 Fully offline AI inference
* 📱 Built using Flutter
* 🧠 YOLOv8 object detection model
* 📦 TensorFlow Lite deployment

---

## 🧠 Technologies Used

| Technology      | Purpose                          |
| --------------- | -------------------------------- |
| Python          | Model training and preprocessing |
| YOLOv8          | Object detection                 |
| Google Colab    | Model training                   |
| TensorFlow Lite | Mobile model deployment          |
| Flutter         | Mobile application development   |
| Dart            | Application programming          |
| OpenCV          | Image processing                 |
| Git & GitHub    | Version control                  |

---

## 📂 Dataset

The custom dataset contains images of electronic components used for training and evaluating the object detection model.

Due to GitHub file-size limitations, the dataset is hosted on Google Drive.

### 📦 Dataset Download

👉 https://drive.google.com/file/d/1ZI_zvX8rXeb8RATNIyHMXgDQFyw0nWYH/view?usp=drive_link

**Dataset Size:** ~3 MB

---

## 🤖 AI Model

The object detection model is based on **YOLOv8**.

### Model Pipeline

```text
Dataset
   ↓
Image Annotation
   ↓
Dataset Preprocessing
   ↓
YOLOv8 Training
   ↓
Model Evaluation
   ↓
YOLOv8 Model
   ↓
TensorFlow Lite Conversion
   ↓
Flutter Integration
   ↓
Offline Mobile Detection
```

---

## 📱 Mobile Application

The Flutter application integrates the trained TensorFlow Lite model and performs object detection directly on the mobile device.

### Application Workflow

```text
Camera / Gallery
       ↓
    Input Image
       ↓
Image Preprocessing
       ↓
TFLite Model
       ↓
YOLOv8 Inference
       ↓
Post Processing
       ↓
Bounding Boxes
       ↓
Component Labels
       ↓
Confidence Scores
       ↓
Detection Results
```

---

## 📥 Mobile Application Source Code

Due to the large size of the complete Flutter project (~1.1 GB), the complete source code is hosted on Google Drive.

### Download

👉 https://drive.google.com/file/d/1HP3j4on0und-qIVrQdfwOEixPBER9fiJ/view?usp=sharing

---

## 📂 Project Structure

```text
electronic-component-detector/
│
├── android/
├── ios/
├── lib/
│   ├── main.dart
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   └── utils/
│
├── assets/
│   ├── models/
│   │   └── model.tflite
│   └── labels/
│       └── labels.txt
│
├── test/
│
├── pubspec.yaml
├── README.md
└── .gitignore
```

---

## ⚙️ Requirements

Before running the Flutter application, install:

* Flutter SDK
* Dart SDK
* Android Studio
* Android SDK
* Git
* Android device or emulator

For model training:

* Python
* Google Colab
* Ultralytics YOLO
* TensorFlow / TensorFlow Lite
* OpenCV

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd electronic-component-detector
```

### 2. Install Flutter Dependencies

```bash
flutter pub get
```

### 3. Connect an Android Device

Check whether Flutter detects your device:

```bash
flutter devices
```

### 4. Run the Application

```bash
flutter run
```

---

## 📷 How to Use

1. Open the application.
2. Select **Camera** or **Gallery**.
3. Capture or select an image containing electronic components.
4. The image is processed locally.
5. The YOLOv8 TFLite model detects the components.
6. Bounding boxes are displayed around detected objects.
7. Component names and confidence scores are shown.
8. The application displays the number of detected components.

---

## 🔌 Offline Detection

One of the main features of this project is **offline inference**.

```text
             Mobile Device
                  │
                  ▼
             Input Image
                  │
                  ▼
          YOLOv8 TFLite Model
                  │
                  ▼
           Object Detection
                  │
                  ▼
       Bounding Boxes + Labels
```

No cloud server or internet connection is required during detection.

---

## 📊 Detection Output

The application provides:

* Component name
* Bounding box
* Confidence score
* Number of detected objects

Example:

```text
Detected Components:

Resistor      → 0.94
Capacitor     → 0.91
Breadboard    → 0.88
LCD           → 0.86

Total Objects: 4
```

---

## 🎯 Applications

This project can be useful for:

* Electronics students
* Electronics laboratories
* Component identification
* Educational applications
* Electronics inventory systems
* Automated component inspection
* AI-based electronics learning tools

---

## 🔮 Future Improvements

Possible future enhancements include:

* 🔍 Improve detection accuracy
* 📱 Optimize inference speed
* 🎥 Real-time camera detection
* 🔊 Voice-based component identification
* 📚 Display component specifications
* 💰 Estimate component prices
* 🔧 Provide basic component information
* 📦 Detect a larger number of components
* 🌐 Optional cloud synchronization
* 📈 Add detection history
* 🗂️ Export detection results

---

## ⚠️ Limitations

* Detection accuracy depends on the training dataset.
* Poor lighting can affect detection performance.
* Small or partially hidden components may be difficult to detect.
* Detection is limited to the classes included in the trained dataset.
* Mobile performance depends on the device hardware.

---

## 📜 License

This project is intended for **educational and academic purposes**.

---

## ⭐ Acknowledgements

* YOLOv8 / Ultralytics
* TensorFlow Lite
* Flutter
* Google Colab
* Open-source computer vision community

---

## 👨‍💻 Author

**Naga Phanindra**

AI + Embedded Systems + Flutter

---
