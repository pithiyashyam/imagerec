<div align="center">

# 🧠 VisionForge AI

### Intelligent Image Classification Platform

A modern AI-powered image recognition system built with **Python, Flask, TensorFlow, OpenCV, and Keras** that classifies images using state-of-the-art pretrained deep learning models with an intuitive web interface and REST API.

<br>

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.19-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.1-000000?style=for-the-badge&logo=flask&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.11-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)

<br>

**Deep Learning • Computer Vision • REST API • Real-Time Prediction • Modern UI**

</div>

---

# 🚀 Overview

**VisionForge AI** is a production-ready image recognition platform that leverages powerful pretrained Convolutional Neural Networks (CNNs) to identify and classify images instantly.

Designed for developers, students, and AI enthusiasts, the application combines deep learning, computer vision, and a clean web interface into a complete end-to-end image classification solution.

No API keys or cloud services are required—everything runs locally on your machine.

---

# ✨ Features

## 🧠 Multiple AI Models

Choose between multiple pretrained CNN architectures:

- MobileNetV2
- ResNet50
- EfficientNetB0

✔ Dynamically switch models without restarting the application.

---

## 🖼 Flexible Image Input

- Upload images from your computer
- Drag & Drop interface
- Predict directly from Image URL

---

## 📊 Smart Prediction Results

- Top-5 ImageNet predictions
- Confidence percentages
- Fast inference time
- Beautiful prediction visualization

---

## 🔍 Image Analysis

Automatic image statistics including:

- Brightness Detection
- Contrast Measurement
- Edge Density
- Dominant Color Extraction
- Image Dimensions

Powered by OpenCV.

---

## 🌐 REST API

Available API Endpoints:

| Endpoint | Description |
|-----------|-------------|
| `/predict` | Predict uploaded image |
| `/predict/url` | Predict image from URL |
| `/api/models` | Available AI models |
| `/api/switch-model` | Switch model instantly |
| `/api/health` | Health check |

---

# 🛠 Technology Stack

| Layer | Technology |
|--------|------------|
| Backend | Flask |
| AI Framework | TensorFlow / Keras |
| Image Processing | Pillow |
| Computer Vision | OpenCV |
| Numerical Computing | NumPy |
| HTTP Requests | Requests |
| Testing | Pytest |
| Deployment | Gunicorn |

---

# 📂 Project Structure

```text
VisionForge-AI/
│
├── app.py
│
├── src/
│   ├── config.py
│   ├── model_manager.py
│   ├── preprocessor.py
│   └── utils.py
│
├── static/
│
├── templates/
│
├── uploads/
│
├── tests/
│
├── requirements.txt
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/VisionForge-AI.git
```

```bash
cd VisionForge-AI
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Open your browser:

```
http://localhost:5000
```

---

# 🖥 Application Modules

### 🏠 Dashboard

- Model Information
- Prediction Summary
- Performance Metrics

### 🖼 Image Upload

- Drag & Drop
- Local Upload
- URL Prediction

### 🤖 AI Prediction

- Top-5 Results
- Confidence Scores
- Inference Time

### 📊 Image Analytics

- Brightness
- Contrast
- Dominant Color
- Edge Detection

### 🌐 REST API

- JSON Responses
- Dynamic Model Switching
- Health Monitoring

---

# 🏗 System Architecture

```text
                User Browser
                     │
                     ▼
              Flask Web Server
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
 Image Upload   URL Handler   REST API
        │            │
        └──────┬─────┘
               ▼
      Image Preprocessing
               │
               ▼
      TensorFlow Model Manager
               │
               ▼
     CNN Prediction Engine
               │
               ▼
     OpenCV Image Analytics
               │
               ▼
      Prediction & Results
```

---

# 📈 Performance Highlights

- Fast Real-Time Prediction
- Multiple CNN Architectures
- Dynamic Model Switching
- Local Inference
- REST API Integration
- Modular Project Structure
- Responsive Web Interface
- Production Ready

---

# 🚀 Future Enhancements

- YOLO Object Detection
- Grad-CAM Visualization
- Batch Image Prediction
- Face Recognition
- Custom Model Upload
- Image History Dashboard
- PDF Prediction Reports
- Cloud Deployment

---

# 🧪 Testing

Execute all unit tests:

```bash
pytest tests/ -v
```

Tests cover:

- API Routes
- Image Preprocessing
- Model Loading
- Configuration
- Prediction Pipeline

---

# 🐳 Docker Support

```dockerfile
FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 5000

CMD ["python", "app.py"]
```

---

# 🤝 Contributing

Contributions are welcome!

```bash
Fork the repository

Create a feature branch

git checkout -b feature/NewFeature

Commit your changes

git commit -m "Added New Feature"

Push your branch

git push origin feature/NewFeature

Create a Pull Request
```

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## **Shyam**

AI Developer • Python Developer • Computer Vision Enthusiast

GitHub: https://github.com/yourusername

---

<div align="center">

## ⭐ Star this repository if you found it helpful!

Built with ❤️ using Python, TensorFlow, Flask & OpenCV

</div>
