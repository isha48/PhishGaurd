 Phishing Detection System for E-Commerce

> A machine learning and deep learning-based project for detecting phishing URLs, developed as part of a research project at **NIT Patna**.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Used-in Project-orange?logo=tensorflow)](https://www.tensorflow.org/)

 Overview

Phishing is a major cybersecurity threat, especially in **e-commerce**, where users share sensitive data like login credentials and financial details. This project aims to **detect phishing websites in real time** using advanced machine learning and deep learning models.

The system works by analyzing URL-based features and classifying them as either **phishing** or **legitimate** using models like **ANN, CNN, RNN, and KNN**.

 Files Included

| File | Description |
|------|-------------|
| `Phishing_detection.ipynb` | Jupyter Notebook with complete code |
| `PhishingGaurd Report.pdf` | Full research report with methodology and results |
| `README.md` | You're reading it |

 Models Used

- ✅ K-Nearest Neighbors (KNN)
- ✅ Artificial Neural Network (ANN)
- ✅ Convolutional Neural Network (CNN)
- ✅ Recurrent Neural Network (RNN)

 Dataset

- **Total Samples:** 11,054
- **Classes:** Phishing (-1), Legitimate (1)
- **Features:** 30+ extracted from URL structure, domain metadata, content behavior

 Pipeline

1. **Data Preprocessing**
   - SMOTE for balancing
   - Correlation removal
   - Normalization & Scaling

2. **Model Training**
   - Evaluated with Accuracy, Precision, Recall, F1-score

3. **Model Evaluation**
   - ANN achieved best accuracy (96.2%)
   - CNN achieved near-perfect performance (99%)

 Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| KNN   | 95.4%    | 95.2%     | 95.3%  | 95.2%    |
| ANN   | 96.2%    | 96.6%     | 95.7%  | 96.1%    |
| CNN   | 99.0%    | ~         | ~      | ~        |
| RNN   | ~96.0%   | ~96.1%    | ~95.9% | ~96.0%   |

---

 Key Features

- ✅ Deep learning-based phishing detection
- ✅ Feature engineering from URLs (no third-party APIs)
- ✅ Balanced training using SMOTE
- ✅ Real-time classification-ready architecture
- ✅ Interpretable outputs (confusion matrices, ROC curves)


 Future Enhancements

 Browser extension for real-time detection
 Federated learning for privacy-preserving detection
Adaptive models to learn new phishing techniques
 Screenshot-based CNN for visual phishing detection

---

 Report

For full methodology, literature survey, architecture diagrams, and more:
📄 **[PhishingGaurd Report.pdf](./PhishingGaurd%20Report.pdf)**

---

Contributor

| Name | Roll Number |
|------|-------------|
| **Isha** | 2247026 |
| **Sakshi Priya** | 2206274 |
| **Nikita Kumawat** | 2247027 |

 **Supervisor:** Dr. Kakali Chatterjee, Associate Professor, Dept. of CSE, NIT Patna




