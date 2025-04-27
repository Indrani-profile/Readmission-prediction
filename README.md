
# Patient Readmission Risk Prediction

## 📌 Project Overview
This project focuses on predicting hospital readmissions for diabetic patients within 30 days of discharge. The goal is to help healthcare providers identify high-risk patients and enable timely interventions to reduce readmission rates, improve patient care, and optimize hospital resource utilization.

Predicting readmissions can significantly impact healthcare operations by improving discharge planning, ensuring better follow-up care, and reducing unnecessary costs.

## 📂 Dataset
The dataset used for this project contains over 100,000 hospital admissions records for diabetic patients, including:
- Patient demographics
- Diagnosis details
- Admission and discharge types
- Length of stay
- Number of medications
- Comorbidities

The target variable is whether the patient was readmitted within 30 days.

## 🚀 Objective
- Perform Exploratory Data Analysis (EDA) to understand patterns and relationships.
- Preprocess the data (handle missing values, encode categorical variables, remove duplicates).
- Build multiple classification models to predict the likelihood of patient readmission.
- Compare model performance using evaluation metrics like Accuracy, Precision, Recall, F1-Score, and AUC-ROC.
- Visualize feature importance to provide actionable insights for healthcare providers.

## 🛠️ Tech Stack / Libraries
- Python (Pandas, NumPy)
- scikit-learn (Logistic Regression, Random Forest, XGBoost, Decision Trees)
- Matplotlib, Seaborn (for data visualization)
- Airflow (Optional - for pipeline orchestration)
- Jupyter Notebook

## 🧩 Modeling Approach
1. Data Cleaning and Preprocessing
   - Handled missing values.
   - Performed one-hot encoding for categorical variables.
   - Feature scaling where necessary.

2. Exploratory Data Analysis (EDA)
   - Visualized readmission rates across different patient groups.
   - Analyzed correlations between features and the target variable.

3. Model Development
   - Built multiple models:
     - Logistic Regression  
     - Random Forest Classifier  
     - XGBoost Classifier  
   - Performed hyperparameter tuning with GridSearchCV.

4. Model Evaluation
   - Evaluated models using Confusion Matrix, Classification Report, and AUC-ROC curve.
   - Selected the best-performing model based on the business goal of reducing false negatives (patients incorrectly classified as low risk).

## 📊 Key Insights
- Certain discharge types and admission sources show higher readmission rates.
- Number of medications and previous inpatient visits are significant predictors of readmission risk.
- The optimized Random Forest model achieved the best performance in this case.

## ✅ Next Steps / Future Work
- Integrate the model into a real-time hospital dashboard.
- Automate data ingestion and model retraining using Apache Airflow.
- Include additional features like lab test results or follow-up data for better prediction accuracy.
- Explore deep learning models (LSTM) for time-series-based readmission analysis.

## 💡 Conclusion
This project provides a machine learning-based approach to predict hospital readmissions, enabling healthcare professionals to proactively manage high-risk patients. It demonstrates the power of data science and predictive modeling in improving healthcare outcomes and operational efficiency.
# Readmission-prediction
