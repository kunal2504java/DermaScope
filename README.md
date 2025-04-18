A deep learning-powered diagnostic tool that classifies 7 types of skin diseases from dermoscopic images using Convolutional Neural Networks and Transfer Learning (MobileNetV2).
.

📌 Project Description
DermaScope is a skin disease detection system that helps classify dermatoscopic images into seven distinct categories:

Actinic Keratoses

Basal Cell Carcinoma

Benign Keratosis-like Lesions

Dermatofibroma

Melanoma

Melanocytic Nevi

Vascular Lesions

It leverages the power of TensorFlow/Keras, computer vision, and pretrained models to accurately predict skin conditions, potentially aiding early diagnosis.

🔍 Features
🧠 CNN + Transfer Learning: Uses MobileNetV2 or a custom CNN for image classification

📊 Visualization: Displays prediction confidence for top classes

🌐 REST API: A Flask API for real-time prediction through an endpoint

🧼 Dataset Cleaning: Automatically removes corrupted or invalid images before training

📁 Directory-based Training: Uses ImageDataGenerator with augmentation

📷 Batch Prediction: Processes multiple test images in one go

🛠️ Tech Stack
Python 3.7+

TensorFlow / Keras

OpenCV, PIL

Flask (for REST API)

Matplotlib, NumPy

MobileNetV2 (Pretrained on ImageNet)

Backend 
Node.js

Frontend
HTML , CSS , React 
