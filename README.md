# Brest_cancer_mode
🔬 Breast Cancer Detection using ResNet50 Transfer Learning |  BreakHis Dataset | TensorFlow 2.x | 95%+ Accuracy |  Benign vs Malignant Classification

# 🔬 Breast Cancer Detection Using ResNet50 Transfer Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-95%25+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Overview
A Deep Learning model that automatically detects 
breast cancer from histopathological images using 
ResNet50 Transfer Learning. The model classifies 
breast tissue images as **Benign** or **Malignant** 
with 95%+ accuracy.

---

## 📂 Dataset
- **Name:** BreakHis (Breast Cancer Histopathological)
- **Source:** [Kaggle](https://www.kaggle.com/datasets/ambarish/breakhis)
- **Total Images:** 7,909
- **Classes:** Benign (2,480) | Malignant (5,429)
- **Format:** PNG | RGB | 700×460px

---

## 🧠 Model Architecture
- **Base Model:** ResNet50 (ImageNet pretrained)
- **Framework:** TensorFlow 2.x / Keras
- **Training Strategy:** Two Phase Transfer Learning
  - Phase 1: Frozen base, train custom head
  - Phase 2: Fine-tune last 50 layers
