# 🧠 Comparative Analysis of Deep Learning Models for Alzheimer’s Disease Classification

## 📌 Overview

This project focuses on building and evaluating multiple deep learning models to classify Alzheimer’s disease stages using brain MRI images. The goal is to identify the most effective model for accurate and early-stage prediction.

---

## 🚀 Key Features

* End-to-end deep learning pipeline
* Image preprocessing and normalization
* Data augmentation for improved generalization
* Model training and evaluation
* Comparative analysis of multiple architectures

---

## 🧠 Models Implemented

* Convolutional Neural Network (CNN)
* MobileNet
* EfficientNet
* ResNet
* Hybrid Model: **ResNet18 + GhostNet**

---

## 📊 Dataset

* Total Images: **9,766**
* Training Set: **8,663 (89%)**
* Testing Set: **1,103 (11%)**

### Classes:

* No Impairment
* Very Mild Impairment
* Mild Impairment
* Moderate Impairment

---

## ⚙️ Workflow

1. Data Collection
2. Image Preprocessing (Resize & Normalize)
3. Data Splitting
4. Data Augmentation
5. Model Selection
6. Model Training
7. Model Testing
8. Evaluation & Classification

---

## 📈 Model Performance

| Model                   | Precision | Recall   | F1-Score | Accuracy |
| ----------------------- | --------- | -------- | -------- | -------- |
| CNN                     | 0.81      | 0.81     | 0.81     | 0.81     |
| MobileNet               | 0.91      | 0.91     | 0.91     | 0.91     |
| EfficientNet            | 0.90      | 0.90     | 0.90     | 0.90     |
| ResNet                  | 0.93      | 0.93     | 0.93     | 0.93     |
| **ResNet18 + GhostNet** | **0.95**  | **0.95** | **0.95** | **0.95** |

---

## 🏆 Results

The hybrid **ResNet18 + GhostNet** model achieved the best performance with **95% accuracy**, demonstrating the effectiveness of combining architectures for medical image classification.

---

## 💡 Key Learnings

* Transfer learning significantly improves performance
* Hybrid architectures outperform standalone models
* Data preprocessing and augmentation are critical for accuracy

---

## 🔮 Future Work

* Use larger and more diverse datasets
* Integrate Explainable AI (XAI) techniques
* Optimize models for real-time deployment

---

## 🛠️ Tech Stack

* Python
* PyTorch / TensorFlow
* OpenCV
* NumPy, Pandas
* Matplotlib / Seaborn


---

## 📬 Contact

For any queries or collaborations, feel free to connect!
