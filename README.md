# Fraud Detection in Loan Applications Using Machine Learning

## Project Overview
This project detects fraudulent loan applications using machine learning techniques. It analyzes user behavior patterns such as device changes, IP mismatch, application frequency, and browser fingerprint changes to classify applications as fraud or genuine.

---

## Objective
- Detect fraudulent loan applications
- Identify unusual user behavior patterns
- Build an automated fraud detection system
- Reduce financial risk for institutions

---

## Dataset Features

- ip_region_mismatch
- device_change_rate
- application_frequency
- loan_amount
- institution
- loan_type
- session_duration
- geo_location_consistency
- previous_defaults
- time_between_apps
- browser_fingerprint_change
- fraudulent (Target Variable)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

### 1. Isolation Forest
Used for anomaly detection to identify unusual applications.

### 2. K-Means Clustering
Groups similar applications and detects abnormal clusters.

### 3. Random Forest Classifier
Supervised model used for final fraud prediction.

---

## Project Workflow

Data Collection  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis (EDA)  
↓  
Feature Encoding  
↓  
Isolation Forest (Anomaly Detection)  
↓  
K-Means Clustering  
↓  
Random Forest Model  
↓  
Evaluation  
↓  
Fraud Alert System  

---

## Model Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

## Fraud Alert System
- ⚠ Fraud Alert → Suspicious application detected
- ✅ Genuine → Safe application

---

## Model Files
- random_forest_model.pkl
- isolation_forest_model.pkl

---

## How to Run

### 1. Install dependencies
pip install -r requirements.txt

### 2. Run notebook
jupyter notebook

### 3. Run Streamlit app (optional)
streamlit run app.py

---

## Key Insights
- Device changes strongly indicate fraud
- IP mismatch increases fraud probability
- High application frequency is suspicious
- Random Forest gives best accuracy

---

## Future Improvements
- Add deep learning models
- Deploy on cloud (AWS / Render / Streamlit Cloud)
- Real-time fraud detection API
- Improve feature engineering

---

## Author
Areeba Imtiaz
Aspiring data analyst

---

## Project Status
Completed ✔  
Portfolio Project ✔
