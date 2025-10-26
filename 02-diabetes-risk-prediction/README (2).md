# Diabetes Risk Prediction (Machine Learning)

**Objective:**  
Develop and evaluate machine learning models to predict diabetes risk based on clinical and lifestyle features, using statistical and model-based approaches to identify key risk factors.

**Tech Stack:** Python (`pandas`, `NumPy`, `matplotlib`, `seaborn`, `scikit-learn`)  
**Notebook:** [`diabetes_risk_prediction.ipynb`](./diabetes_risk_prediction.ipynb)

---

## Data Preparation
- Imported and cleaned the **diabetes examination dataset**, handling missing and inconsistent values.  
- Normalized numeric variables and encoded categorical features for model compatibility.  
- Performed feature inspection and correlation analysis to identify potential predictors of diabetes.

---

## Modeling Process
- Split data into **training and testing** subsets to ensure unbiased evaluation.  
- Trained multiple models including **Logistic Regression** and **Random Forest Classifier**.  
- Tuned hyperparameters and compared metrics such as accuracy, precision, recall, and AUC.  
- Visualized feature importance to interpret the impact of key predictors.

---

## Key Results
- **Logistic Regression** achieved an AUC of approximately **0.84** on the test set.  
- **Random Forest** improved recall while maintaining similar precision levels.  
- Identified **BMI, glucose level, and age** as the top predictors of diabetes risk.

---

## Outcome
This project demonstrates the application of machine learning to healthcare data analysis — bridging clinical insights with predictive modeling.  
The results can support early screening initiatives and guide patient lifestyle recommendations.

---

*Note:*  
The dataset is for educational and analytical purposes. Only processed and derived data are included in this repository.
