# 🖐️ Real-Time Sign Language Translator  
**AI-powered real-time gesture recognition using Convolutional Neural Networks and OpenCV**

> A deep learning application that translates sign language hand gestures into English alphabets in real-time using a webcam feed.

---

## 🚀 Overview

The **Real-Time Sign Language Translator** captures hand gestures via webcam and predicts the corresponding English alphabet using a **Convolutional Neural Network (CNN)** model trained on the **Sign Language MNIST dataset**.  
The trained model is deployed using **ONNX Runtime** and **OpenCV** for efficient real-time inference.

---

## ✨ Key Features

- 🧠 **Deep Learning Model:** CNN trained on Sign Language MNIST dataset  
- 📸 **Real-Time Detection:** Uses webcam feed for live prediction  
- ⚡ **Fast Inference:** Model deployed with ONNX Runtime for high-speed results  
- 🎯 **High Accuracy:** Achieved 90%+ real-time classification accuracy  
- ♿ **Accessibility Impact:** Enables gesture-based communication for the hearing-impaired  

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Python |
| **Frameworks** | PyTorch, ONNX Runtime |
| **Computer Vision** | OpenCV |
| **Dataset** | Sign Language MNIST |
| **Other Tools** | NumPy, Matplotlib |

---
## ⚙️ How It Works

1. **Data Preparation:** Load and preprocess the Sign Language MNIST dataset.  
2. **Model Training:** Train a CNN to classify hand signs (A–Z).  
3. **Model Conversion:** Export trained model to ONNX format.  
4. **Live Detection:** Use `OpenCV` to capture video frames and run ONNX inference.  

---
##📈 Results

✅ 90%+ accuracy on test dataset

🎥 Real-time translation with minimal latency

📊 Consistent performance across various lighting conditions
