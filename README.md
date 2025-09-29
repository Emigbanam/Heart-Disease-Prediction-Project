# ❤️ Heart-Disease-Prediction-Project

This project examines machine learning techniques to predict the likelihood of heart disease using patient data.  
It covers the complete ML workflow — from data preprocessing and exploratory analysis to model training, evaluation, and comparison — using **multiple classification algorithms** in Python.

---

## 📊 Project Overview

Heart disease is one of the leading causes of death globally. Early prediction can help medical professionals take preventive action.  
In this project, we build and evaluate classification models that predict whether a patient is likely to develop heart disease (**1**) or not (**0**) using health-related features.

---

## 🧠 Workflow

1. **Data Collection**  
   - Load and inspect the dataset (`heart_disease_data.csv`).

2. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Explore and visualize features  
   - Encode categorical variables  
   - Standardize or scale numerical features (if required)

3. **Train-Test Split**  
   - Split the dataset into training and testing sets to evaluate generalization performance.

4. **Model Training**  
   - Train multiple classification models, such as:
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Random Forest  
     - K-Nearest Neighbors (KNN)  
     - Gradient Boosting / XGBoost

5. **Model Evaluation**  
   - Compare model performance using:
     - Accuracy  
     - Precision, Recall, F1-score  
     - Confusion Matrix  
     - ROC-AUC Curve

6. **Prediction**  
   - Test the trained models with new or sample patient data.

---

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook

---

## 📁 Dataset Description

Each row represents a patient record with features used to predict heart disease risk.  
Below are key columns:

| Feature       | Description                                   |
|---------------|-----------------------------------------------|
| age           | Age of the patient                            |
| sex           | Gender (1 = male, 0 = female)                |
| cp            | Chest pain type                              |
| trestbps      | Resting blood pressure                       |
| chol          | Serum cholesterol (mg/dl)                    |
| fbs           | Fasting blood sugar > 120 mg/dl (1 = true)  |
| restecg       | Resting ECG results                          |
| thalach       | Maximum heart rate achieved                 |
| exang         | Exercise-induced angina (1 = yes, 0 = no)   |
| oldpeak       | ST depression induced by exercise           |
| slope         | Slope of the peak exercise ST segment       |
| ca            | Number of major vessels (0-3)               |
| thal          | Thalassemia type                            |
| target        | **Target label** (1 = heart disease, 0 = no) |

---

## 📈 Expected Results

- Build several classification models and compare their performance.  
- Identify which algorithm works best for this dataset.  
- Understand how different health features contribute to heart disease prediction.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
