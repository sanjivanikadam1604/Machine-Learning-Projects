#  Glucose Level Prediction using Machine Learning

##  Project Overview

This project uses the Framingham Heart Study dataset to predict glucose-related health outcomes using Machine Learning. Two different approaches were implemented:

1. **Regression Model** – Predicts the exact glucose level of a patient.
2. **Classification Model** – Classifies patients as Normal, Pre-Diabetic, or Diabetic.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation.

---

##  Dataset

**Dataset:** Framingham Heart Study Dataset

### Features Used
- Age
- Gender
- Education
- Current Smoker
- Cigarettes Per Day
- Blood Pressure Medication
- Prevalent Stroke
- Prevalent Hypertension
- Diabetes
- Total Cholesterol
- Systolic Blood Pressure
- Diastolic Blood Pressure
- BMI
- Heart Rate
- Ten-Year CHD

---

#  Regression Model

### Objective
Predict the exact glucose level of a patient.

### Algorithms Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

### Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Key Findings
- Ensemble models outperformed Linear Regression.
- Diabetes, BMI, Blood Pressure, and Age were important predictors.
- XGBoost and Random Forest achieved the best performance.

---

#  Classification Model

### Objective
Classify patients into:

| Category | Glucose Level |
|-----------|--------------|
| Normal | < 100 |
| Pre-Diabetic | 100 – 126 |
| Diabetic | > 126 |

### Algorithms Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gaussian Naive Bayes
- XGBoost Classifier

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Results
- Random Forest and XGBoost achieved the highest accuracy.
- Diabetes status, BMI, Blood Pressure, and Age were among the most influential features.
- The model can assist in early diabetes risk assessment.

---

##  Visualizations Included

- Glucose Category Distribution
- Correlation Heatmap
- Confusion Matrices
- Feature Importance Plot
- Model Comparison Chart

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Google Colab

---

##  Future Improvements

- Hyperparameter Tuning
- Cross Validation
- SMOTE for Class Imbalance
- SHAP Explainability
- Deployment using Streamlit or Flask

---

##  Learning Outcomes

Through this project, I learned:

- Data Cleaning and Preprocessing
- Feature Engineering
- Regression Techniques
- Classification Techniques
- Model Evaluation
- Feature Importance Analysis
- End-to-End Machine Learning Workflow

---

##  Author

**Sanjivani Kadam**  
B.Tech Robotics & Artificial Intelligence  
COEP Technological University
