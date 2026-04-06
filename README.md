# 🧠 Liver Disease Prediction using Machine Learning

## 📌 Overview
This project focuses on building a machine learning model to predict the likelihood of liver disease based on patient health parameters. The goal is to assist in early detection and support data-driven healthcare decisions.

Liver disease is a critical global health issue, and early diagnosis can significantly improve patient outcomes. Machine learning models can help identify high-risk patients using clinical data. :contentReference[oaicite:0]{index=0}

---

## 🎯 Problem Statement
Given patient medical attributes such as age, bilirubin levels, enzyme levels, and protein ratios, the objective is to predict whether a patient has liver disease or not.

This is a **binary classification problem** where:
- 1 → Liver Disease  
- 0 → No Liver Disease  

---

## 📊 Dataset
- Dataset: Indian Liver Patient Dataset (ILPD)
- Contains patient records with medical attributes such as:
  - Age, Gender  
  - Total & Direct Bilirubin  
  - Alkaline Phosphotase  
  - Aminotransferase levels  
  - Albumin & Protein ratios  

These features are commonly used in clinical diagnosis and predictive modeling. :contentReference[oaicite:1]{index=1}

---

## ⚙️ Project Workflow

### 🔹 1. Data Preprocessing
- Handled missing values and inconsistencies  
- Encoded categorical variables  
- Performed data cleaning and transformation  

### 🔹 2. Exploratory Data Analysis (EDA)
- Identified trends, correlations, and outliers  
- Visualized feature relationships using plots  

### 🔹 3. Feature Engineering
- Selected important features impacting prediction  
- Improved model performance through data transformation  

### 🔹 4. Model Building
- Implemented classification models using:
  - Logistic Regression  
  - Random Forest  

### 🔹 5. Model Evaluation
- Evaluated using:
  - Accuracy  
  - Confusion Matrix  
  - Precision & Recall  

Healthcare models prioritize recall to reduce missed diagnoses. :contentReference[oaicite:2]{index=2}

---

## 🚀 Results
- Achieved **~88% accuracy** using Random Forest  
- Improved recall to better identify high-risk patients  
- Successfully built a model capable of predicting liver disease risk  

---

## 💡 Key Outcome
Improved early risk detection with ~88% accuracy, enabling better identification of high-risk patients.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📌 Business Impact
- Enables early detection of liver disease  
- Supports healthcare professionals in decision-making  
- Reduces manual diagnostic effort  
- Demonstrates real-world application of machine learning in healthcare  

---

## 📷 Project Demo (Optional)
_Add screenshots or Streamlit app link here if available_

---

## 🔗 Repository Structure
![Dashboard](images/ss.png)

## 🔗 Repository Structure

├── labelencoder.pkl
├── liverdiseasepredictionNiveditha.ipynb
├── model.pkl
├── app.py 
├── requirements.txt
├── scaler.pkl
└── README.md


---

## 📈 Future Improvements
- Hyperparameter tuning for better accuracy  
- Deployment using Streamlit / Flask  
- Integration with real-time healthcare systems  

---

## 🙋‍♀️ Author
**Niveditha E R**  



