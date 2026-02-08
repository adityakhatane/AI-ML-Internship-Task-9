# AI-ML Internship – Task 9  
## Credit Card Fraud Detection using Random Forest

---

## 📌 Objective  
The objective of this task is to build and evaluate machine learning models to detect **fraudulent credit card transactions** using a highly imbalanced dataset, with a focus on appropriate evaluation metrics.

---

## 📂 Dataset  
**Fraud Detection Dataset (`fraud_data.csv`)**

- Contains transaction-related features
- Target variable indicates fraud status:
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

- Dataset is **highly imbalanced**, with very few fraud cases compared to normal transactions.

---

## 🛠 Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Joblib  
- Jupyter Notebook  

---

## 🔍 Steps Performed

### 1. Dataset Loading  
- Loaded the fraud dataset using Pandas
- Inspected dataset shape, columns, and data types

---

### 2. Data Cleaning  
- Standardized column names
- Removed non-numeric columns such as date/time features
- Ensured dataset compatibility with machine learning models

---

### 3. Feature and Target Selection  
- Separated independent features (`X`) and target variable (`y`)
- Verified severe class imbalance in the target variable

---

### 4. Train–Test Split  
- Split dataset into training and testing sets (80% train, 20% test)
- Stratified split was **not possible** due to only one fraud sample, so a standard split was used

---

### 5. Baseline Model – Logistic Regression  
- Trained a Logistic Regression model as a baseline
- Observed poor fraud detection performance due to class imbalance

---

### 6. Random Forest Model  
- Trained a Random Forest Classifier
- Utilized ensemble learning to improve fraud detection capability

---

### 7. Model Evaluation  
Models were evaluated using:
- **Precision**
- **Recall**
- **F1-score**

These metrics are more reliable than accuracy for imbalanced datasets.

---

### 8. Feature Importance  
- Analyzed feature importance from the Random Forest model
- Visualized top contributing features affecting fraud prediction

---

### 9. Model Saving  
- Saved the trained Random Forest model using Joblib
- Model file can be reused for deployment or further analysis

---

## 📦 Deliverables  
- ✔ Jupyter Notebook (`.ipynb`)  
- ✔ Random Forest trained model (`.pkl`)  
- ✔ Evaluation report  
- ✔ Feature importance visualization  

---

## 🎯 Final Outcome  

The intern successfully implemented a Random Forest model for fraud detection, handled severe class imbalance, evaluated models using appropriate metrics, and gained hands-on experience with ensemble learning techniques.


---

## ✅ Conclusion  
This task strengthened understanding of fraud detection, class imbalance challenges, ensemble models, and the importance of selecting correct evaluation metrics in real-world machine learning problems.

---


## 📁 Repository Structure
