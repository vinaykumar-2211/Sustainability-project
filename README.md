# 🌞 Solar Panel Damage Detection using Deep Learning (CNN)

## 📘 Project Overview
This project focuses on detecting damages, dust, and cracks on solar panels using **Convolutional Neural Networks (CNN)**.  
The system classifies images of solar panels into three categories — **Healthy**, **Dusty**, and **Damaged** — to support maintenance teams in monitoring solar farms efficiently.  
A **Streamlit web application** is also integrated for real-time detection and user-friendly visualization.

---

## 🎯 Objectives
- Automate the process of identifying damaged or dusty solar panels.
- Improve accuracy and reduce manual inspection efforts.
- Support sustainability by maintaining optimal solar energy generation.
- Deploy a CNN model using Streamlit for real-time image-based classification.

---

## 🧠 Model Architecture
- Framework: **TensorFlow / Keras**
- Architecture: Custom **CNN** with Conv2D, MaxPooling, Dropout, and Dense layers.
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Evaluation Metrics: Accuracy, Precision, Recall

---

## 🗂 Dataset
- **Primary Source**: [Solar Panel Images (Clean and Faulty) – Kaggle](https://www.kaggle.com/datasets/pythonafroz/solar-panel-images)
- **Additional Data**: [PVMD Dataset – Mendeley](https://data.mendeley.com/datasets/5ssmfpgrpc)
- Classes: `Healthy`, `Dusty`, `Damaged`
- Image Size: 224x224 pixels (standardized)
- Augmentation: Rotation, Zoom, Flip, and Brightness adjustments.

---

## 🖥️ Streamlit Web App
The trained CNN model is deployed using **Streamlit**.  
Users can upload an image of a solar panel, and the app predicts its condition in real time.

Run the app locally:
```bash
streamlit run app.py

