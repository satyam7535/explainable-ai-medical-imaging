# Explainable AI for Medical Imaging 

This repository contains my  Project focused on applying Explainable Artificial Intelligence (XAI) techniques to medical image analysis.

The objective of this project is to make **deep learning–based medical image classification transparent, interpretable, and reliable, which is critical for clinical decision support systems.
---
## 🔍 Project Overview
The system performs **tumor classification from medical images** using a **transfer learning–based deep learning model** and provides **human-understandable explanations** for its predictions.
A pre-trained convolutional neural network is fine-tuned on a medical imaging dataset to achieve high performance while reducing training time and data requirements.

---

## 🎯 Key Objectives

- Accurate medical image classification using transfer learning
- Visual explanation of model decisions
- Estimation of prediction uncertainty
- Automated clinical-style report generation

---

## 🧠 Key Features

### 🔹 Transfer Learning–Based Classification
- Fine-tuned CNN model pre-trained on large-scale image datasets
- Multi-class tumor classification from medical images

### 🔹 Explainability (XAI)
- Grad-CAM and Grad-CAM++ heatmaps to highlight image regions influencing predictions

### 🔹 Uncertainty Estimation
- Monte Carlo Dropout to quantify prediction confidence and entropy

### 🔹 Automated Case Reports
- AI-generated PDF reports including:
  - Prediction
  - Confidence score
  - Explainability heatmaps
  - Clinical-style suggestions

---

## 📊 Results (Summary)

- Achieved strong classification performance on the test dataset
- Visual explanations align with tumor-relevant regions in medical images
- Uncertainty estimation provides confidence awareness for predictions
- Generated automated case reports for interpretability and analysis

*(Exact metrics and visual outputs are generated dynamically via the notebook.)*

---

## 🛠 Technologies Used

- Python
- PyTorch
- Transfer Learning (Pre-trained CNN models)
- Grad-CAM, Grad-CAM++
- Monte Carlo Dropout
- OpenCV
- NumPy, Matplotlib
- ReportLab (PDF generation)
- Google Colab



