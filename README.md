# Intrusion detction in IoT Networks using ML


📌 Project Overview

This project aims to build an Intrusion Detection System (IDS) for IoT networks using XGBoost, a powerful machine learning algorithm. We leverage the RT-IoT2022 dataset, which contains network traffic data from real IoT environments, to classify traffic as normal or attack.

By applying data preprocessing, feature selection, and handling class imbalance, our model improves cybersecurity by accurately detecting cyber threats in IoT systems.



📂 Dataset

RT-IoT2022 Dataset from Kaggle
Contains 123,117 instances and 83 features (normal + attack traffic)
Features captured using Zeek network monitoring tool
🛠 Technologies Used

Machine Learning Model: XGBoost
Preprocessing: Pandas, NumPy, Scikit-Learn
Feature Selection & Scaling: Label Encoding, Min-Max Scaling
Imbalanced Data Handling: SMOTE (Oversampling), Undersampling
Performance Evaluation: Confusion Matrix, Precision-Recall, ROC-AUC
🚀 Methodology

Data Preprocessing
Convert categorical features (e.g., protocols) using Label Encoding
Normalize continuous variables using Min-Max Scaling
Handle missing values efficiently
Handling Imbalanced Data
Use SMOTE (Synthetic Minority Over-sampling) to generate synthetic attack samples
Apply undersampling to balance the dataset
Training the XGBoost Model
Optimize model parameters using Grid Search & Random Search
Train XGBoost on the processed dataset
Evaluation Metrics
Confusion Matrix: Tracks correct vs incorrect classifications
Precision & Recall: Ensures minimal false alarms and high attack detection
ROC-AUC Score: Measures how well the model distinguishes attacks from normal traffic
🔥 Results & Impact

✅ High Accuracy: XGBoost efficiently detects attacks, outperforming traditional classifiers
✅ Improved Security: Enhances real-time threat detection for IoT networks
✅ Feature Importance Analysis: Identifies key indicators of cyber threats

