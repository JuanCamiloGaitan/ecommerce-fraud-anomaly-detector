# E-commerce Fraud & Anomaly Detector

![Python](https://img.shields.io/badge/Python-3.0%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://completed-shield.svg)

[Read in Spanish / Leer en español](#-español)

---

### 🔍 Project Overview
This project simulates and detects fraudulent transactions in an e-commerce platform using Machine Learning. Real-world fraud detection deals with heavily imbalanced datasets (where fraud accounts for less than 2% of total transactions). This project compares two different approaches to tackle this challenge:
1. **Unsupervised Learning (Isolation Forest):** Detecting anomalies without prior historical labels.
2. **Supervised Learning (Random Forest):** Training a classifier with balanced class weights to predict fraudulent behavior on unseen data.

### 📊 Key Results & Insights
* **Isolation Forest:** Useful when historical fraud labels are scarce, though it yielded higher false positives in this synthetic setup.
* **Random Forest:** Achieved high precision (1.00) on the test set by handling class imbalance with `class_weight='balanced'`, significantly reducing false alarms while catching core patterns.

### 🚀 Getting Started & Replication
Clone this repository and install the required dependencies to run the Jupyter Notebook:

```bash
git clone [https://github.com/JuanCamiloGaitan/ecommerce-fraud-anomaly-detector.git](https://github.com/JuanCamiloGaitan/ecommerce-fraud-anomaly-detector.git)
cd ecommerce-fraud-anomaly-detector
pip install -r requirements.txt
