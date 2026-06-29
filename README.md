# ⚙️ Predictive Maintenance of Gearbox using Vibration Sensors

## 📌 Project Overview

Predictive maintenance is an Industry 4.0 approach that helps detect equipment faults before failure. In this project, vibration sensor data from a gearbox is analyzed to classify the gearbox condition as either **Healthy** or **Broken Tooth** using Machine Learning.

This project demonstrates a complete predictive maintenance pipeline including feature extraction, data preprocessing, model training, evaluation, and visualization.

---

## 🎯 Objectives

- Analyze gearbox vibration signals.
- Extract statistical features from sensor data.
- Build a machine learning model to detect gearbox faults.
- Evaluate the model using standard classification metrics.

---

## 📂 Dataset

The dataset contains vibration signals collected from four sensors mounted on a gearbox under two operating conditions:

- Healthy Condition
- Broken Tooth Condition

Each vibration signal is processed to extract statistical features.

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

---

## ⚙️ Workflow

1. Load vibration sensor data
2. Data cleaning
3. Feature extraction
4. Create feature dataset
5. Exploratory Data Analysis
6. Train-Test Split
7. Random Forest Classification
8. Model Evaluation
9. Save trained model

---

## 📊 Extracted Features

For each vibration channel:

- Mean
- Standard Deviation
- Maximum
- Minimum
- RMS
- Kurtosis
- Skewness

Total Features: **28**

---

## 🤖 Machine Learning Model

Random Forest Classifier

---

## 📈 Evaluation Metrics

- Accuracy
- Classification Report
- Confusion Matrix
- ROC Curve
- Feature Importance

---

## 📁 Project Structure

```
Predictive_Maintenance_Gearbox/
│
├── dataset/
├── notebook.ipynb
├── gearbox_features.csv
├── gearbox_fault_model.pkl
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Results

The Random Forest classifier successfully distinguished healthy and faulty gearbox conditions on the extracted feature dataset.

> Note:
> The extracted feature dataset contains a limited number of samples. Therefore, the obtained accuracy demonstrates the workflow and proof of concept rather than production-scale performance.

---

## 📚 Learning Outcomes

- Industrial Predictive Maintenance
- Feature Engineering
- Statistical Signal Analysis
- Random Forest Classification
- Machine Learning Workflow
- Model Serialization using Joblib

---

## 🙌 Acknowledgement

This project was completed as part of the **UPSKILL Machine Learning Internship**, focusing on industrial predictive maintenance applications.
