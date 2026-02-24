# 🚀 Network Anomaly Detection using Machine Learning

This project builds a machine learning model to detect anomalous network traffic based on network flow features such as inbound/outbound rate and bandwidth utilization.

The goal is to classify whether a network instance is **normal or anomalous** using supervised learning techniques.

---

## 📌 Project Overview

Network anomaly detection is important in cybersecurity for identifying malicious or abnormal traffic patterns.  
In this project, a classification model is trained on network traffic data to automatically detect anomalies.

The workflow includes:
- Data loading and preprocessing
- Feature and label separation
- Train-test splitting
- Model training using Logistic Regression
- Model evaluation using multiple performance metrics

---

## 🧠 Machine Learning Concepts Used

- Supervised Learning  
- Binary Classification  
- Logistic Regression  
- Train-Test Split  
- Model Evaluation  
- Confusion Matrix  
- Precision, Recall, F1-score  

---

## 📊 Features Used

The model is trained using the following network parameters:

- Inbound Rate (bit/s)
- Outbound Rate (bit/s)
- Inbound Bandwidth Utilization (%)
- Outbound Bandwidth Utilization (%)

Target:
- 0 → Normal traffic  
- 1 → Anomalous traffic  

---

## ⚙️ Model Used

### Logistic Regression
Logistic Regression is used as the primary classification algorithm to predict whether traffic is normal or anomalous.

The model learns relationships between network parameters and traffic labels using supervised learning.

---

## 📈 Model Performance

- Accuracy: ~95%
- High Recall for anomaly detection (captures all attacks)
- Low false negative rate
- Evaluated using confusion matrix and classification report

This ensures that anomalous traffic is detected reliably with minimal missed attacks.

---

## 🧪 Evaluation Metrics

The model was evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-score  

These metrics help assess real-world performance of the anomaly detection system.

---

## ▶️ Run in Google Colab

You can run the full project here:

**Colab Link:**  
PASTE_YOUR_COLAB_LINK_HERE

---

## 💻 Tech Stack

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 📂 Project Structure
