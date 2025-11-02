# 🚗 FASTag Fraud Detection System

## 📘 Overview
The **FASTag Fraud Detection System** is a **Data Science project** designed to identify and prevent fraudulent FASTag transactions using advanced machine learning and data analytics techniques.  
FASTag, being an electronic toll collection system in India, has seen a rise in misuse and data anomalies. This project aims to **analyze transactional patterns** and **detect fraudulent behavior** proactively.

---

## 🎯 Objectives
- Detect and classify fraudulent FASTag transactions  
- Explore transaction trends and identify suspicious patterns  
- Build a predictive model for real-time fraud alert generation  
- Provide insights into key fraud indicators for toll authorities  

---

## 🧠 Key Features
- **Data Preprocessing:** Cleansing, handling missing values, encoding categorical data, and feature engineering  
- **Exploratory Data Analysis (EDA):** Visual analysis to identify correlations, anomalies, and transaction distributions  
- **Model Building:** Trained multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost, etc.) to detect fraud  
- **Model Evaluation:** Accuracy, Precision, Recall, F1-score, and Confusion Matrix metrics to ensure reliability  
- **Fraud Insights Dashboard (optional):** Summary of findings and fraud trends visualization  

---

## 📂 Project Structure
- **Fastag-Fraud-Detection/**
- │
- ├── Fastag_Fraud.ipynb # Main Jupyter Notebook (code & analysis)
- ├── FastagFraudDetection.csv # Dataset used for training and analysis
- ├── README.md # Project documentation (this file)
- └── requirements.txt # Dependencies

---

## 🧩 Dataset Description

**File:** `FastagFraudDetection.csv`  
This dataset contains anonymized FASTag transaction records used to train and evaluate fraud detection models.  
Each record represents a single toll transaction captured from FASTag systems across different toll plazas.

---

### 📁 Columns Overview

| Column Name       | Description |
|--------------------|-------------|
| `Transaction_ID`   | Unique identifier for each FASTag transaction |
| `Vehicle_Number`   | Encoded vehicle registration number |
| `Vehicle_Type`     | Type of vehicle (e.g., Car, Truck, Bus, etc.) |
| `Toll_Location`    | Name or ID of the toll plaza |
| `Amount`           | Transaction amount deducted from the FASTag account |
| `Timestamp`        | Date and time of the transaction |
| `Payment_Mode`     | Method of payment (e.g., FASTag, Cash, etc.) |
| `Trip_Distance`    | Distance between two consecutive tolls (if applicable) |
| `Account_Balance`  | Remaining balance in the FASTag account after deduction |
| `Fraud_Flag`       | Target label — `1` indicates a fraudulent transaction, `0` indicates a legitimate one |

---

### 📊 Dataset Summary
- **Total Records:** ~*depends on your dataset rows*  
- **Total Features:** *10 (or as per actual dataset)*  
- **Target Variable:** `Fraud_Flag`  
- **Data Type Mix:** Numerical + Categorical + Temporal  

---

### ⚠️ Notes
- Data has been **anonymized** to ensure privacy and compliance.  
- Missing or inconsistent values were handled during preprocessing.  
- The dataset was split into **training** and **testing** sets for model evaluation.  

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  
- **Tools:** Jupyter Notebook, Git, GitHub  
- **Domain:** Data Science, Machine Learning, Fraud Detection

  ---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/Fastag-Fraud-Detection.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Fastag-Fraud-Detection
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook Fastag_Fraud.ipynb
   ```

5. **Run all cells** to execute data analysis and model training.

---

## 📊 Results
- Built ML models achieved strong performance in identifying fraudulent transactions.  
- Discovered significant patterns such as unusual toll locations, abnormal transaction times, and suspicious repeat entries.  
- Feature importance analysis revealed top predictors influencing fraud detection.  

---
