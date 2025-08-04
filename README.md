Phishing Detection System for E-Commerce
A deep learning-based phishing detection framework that accurately classifies malicious and legitimate websites using a robust set of URL-based features. This project was developed as part of a research initiative under the Department of Computer Science and Engineering, NIT Patna.


🔍 Project Overview
Phishing attacks trick users into revealing sensitive personal information (like login credentials, credit card details) through fake websites. Our solution leverages machine learning and deep learning models to detect such threats in real-time by analyzing URLs and associated metadata.

Core Models Used:

K-Nearest Neighbors (KNN)

Artificial Neural Networks (ANN)

Convolutional Neural Networks (CNN)

Recurrent Neural Networks (RNN)

🎯 Objectives
Automatically classify URLs as phishing or legitimate.

Compare the effectiveness of different ML/DL classifiers.

Develop a scalable and real-time phishing detection framework.

Overcome issues such as zero-day attacks and adversarial evasion.

📁 Repository Structure
bash
Copy
Edit
📦 Phishing-Detection
 ┣ 📜 Phishing_detection.ipynb    # Main code (Jupyter notebook)
 ┣ 📄 PhishingGaurd Report.pdf    # Full research report (with results, analysis, etc.)
 ┣ 📄 README.md                   # This file
📊 Dataset Overview
Total Records: 11,054

Features: 32 (URL structure, domain registration, HTTPS presence, JavaScript behavior, etc.)

Label: -1 for phishing, 1 for legitimate

Oversampling was applied using SMOTE to balance the classes during training.

⚙️ Methodology
Feature Extraction

Domain & URL structure

Metadata (SSL, DNS)

JavaScript behavior, redirections

Preprocessing

Data balancing using SMOTE

Feature scaling (Z-score, MinMax)

Feature selection (Variance threshold)

Model Training

Evaluated on KNN, ANN, CNN, RNN

Performance metrics: Accuracy, Precision, Recall, F1-Score

📈 Performance Summary
Model	Accuracy	Precision	Recall	F1-Score
KNN	95.4%	95.2%	95.3%	95.2%
ANN	96.2%	96.6%	95.7%	96.1%
CNN	99.0%	~	~	~
RNN	~96.0%	~96.1%	~95.9%	~96.0%

🚀 Future Enhancements
Deploy as a browser extension or email scanner.

Introduce federated learning for privacy-preserving training.

Incorporate visual phishing detection via page screenshots.

Add online learning capabilities to adapt to new phishing methods.

📄 Report
For a detailed explanation of methodology, model architecture, evaluation metrics, and literature review, refer to PhishingGaurd Report.pdf.

🧠 Team Members
Isha (2247026)

Sakshi Priya (2206274)

Nikita Kumawat (2247027)

Under the guidance of:
Dr. Kakali Chatterjee
Associate Professor, Dept. of CSE
NIT Patna
