# Automating Checkout Process in Retail

## 📌 Project Overview
This project implements **YOLOv11** for **real-time object detection** in retail checkout systems. It automates product recognition, eliminating **manual barcode scanning** and improving efficiency.

## 🏆 Objectives
- **Real-time object detection** for checkout counters.
- **Fine-grained product recognition** despite visual similarities.
- **Handle dataset imbalances** and **domain shifts** for real-world robustness.

## 🔍 Problem Statement
- **Manual barcode scanning** is time-consuming and prone to errors.
- **Retail products** have **subtle visual differences**, making detection challenging.
- **Lack of diverse datasets** affects real-world generalization.

## 📊 Dataset Details
- **500+ images** annotated with bounding boxes.
- **Types of Images:**
  - **Single-product images** (controlled setup).
  - **Real-world checkout images** (cluttered environment).
- **Challenges Addressed:**
  - Balanced **class distribution**.
  - **Domain adaptation** for real-world accuracy.

## 🚀 Methodology
### **Model Training**
- **YOLOv11 trained for 200 epochs**.
- **Evaluation Metrics:**
  - Precision: **95%**
  - Recall: **89%**
  - F1-Score: **86%**
  - mAP@0.5: **83.3%**

### **Optimization Strategies**
- **Data Augmentation** (to handle dataset imbalance).
- **Hyperparameter tuning** (to minimize overfitting).

## 📊 Visualizations
- **Confusion Matrix**
- **Precision-Recall Curve**
- **F1-Confidence Curve**
- **Loss Curves**

## 🏆 Key Activities
- **Dataset annotation** & augmentation.
- **Training YOLOv11** on large-scale product categories.
- **Performance evaluation** in real-world checkout environments.
- **Optimizing detection models** for speed and accuracy.

## 💡 Challenges & Learnings
- **Challenges:**
  - Tool integration & compatibility.
  - Managing large-scale datasets.
  - Handling subtle product differences in cluttered images.
- **Key Learnings:**
  - **Balanced datasets improve fine-grained detection**.
  - **YOLOv11 performed well in real-world scenarios**.


