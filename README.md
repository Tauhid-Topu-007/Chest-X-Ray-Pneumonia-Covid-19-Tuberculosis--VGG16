# 🩺 Chest X-Ray Multi-Class Classification  
### **COVID-19 • Normal • Pneumonia • Tuberculosis**

This repository contains a deep learning-based chest X-ray classifier capable of identifying **four medical conditions**:  
**COVID-19**, **Normal**, **Pneumonia**, and **Tuberculosis**.  
The project demonstrates the full workflow — from dataset acquisition to model training, transfer learning, and evaluation.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Setup and Installation](#setup-and-installation)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Transfer Learning and Fine-tuning](#transfer-learning-and-fine-tuning)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)
- [License](#license)

---

## 📘 Project Overview

This project uses **Convolutional Neural Networks (CNNs)** to classify chest X-ray images. It features:

### ✔️ Data Acquisition
Automatic Kaggle dataset download using the **Kaggle API**.

### ✔️ Preprocessing
- Image resizing (224×224)  
- Normalization  
- Data augmentation (flip & rotation)

### ✔️ Model Development
Two VGG16-based approaches:
1. **Custom VGG16 (built from scratch)**
2. **Transfer Learning using ImageNet weights**

### ✔️ Evaluation
- Model accuracy  
- Confusion matrix  
- Performance comparison

---

## 📂 Dataset

**Kaggle Dataset:**  
[Chest X-Ray (Pneumonia, COVID-19, Tuberculosis)](https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis)

### Details:
- **Classes**: COVID-19, NORMAL, PNEUMONIA, TUBERCULOSIS  
- **Splits**: Pre-divided into `train`, `val`, and `test`  
- **Size**: ~1.74 GB

---

## ⚙️ Setup and Installation

### Requirements
- Python 3.7+
- TensorFlow 2.x
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  
- Kaggle API  

### Install Dependencies
```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn kaggle
