## CDC-Diabetic-Health-Indicators

### Overview

This project aims to analyze and predict diabetes-related health indicators using machine learning techniques. Diabetes is a chronic disease affecting millions of individuals worldwide, and understanding its health indicators is crucial for early detection and prevention. By leveraging the CDC Diabetes Health Indicators Dataset, this project explores various statistical insights and applies predictive modeling to identify key risk factors.

### Dataset

The dataset used in this project consists of health indicators collected from multiple respondents across the United States. The key features include:

**Demographics**: Age, Gender, BMI, Physical Activity

**Health Conditions**: Hypertension, High Cholesterol, Stroke, Heart Disease

**Behavioral Factors**: Smoking, Alcohol Consumption, Physical Inactivity

**Medical Conditions**: Diabetes Status (Diagnosed, Undiagnosed, No Diabetes)

### Technologies Used

Python

Jupyter Notebook

Pandas, NumPy (Data Processing)

Matplotlib, Seaborn (Data Visualization)

Scikit-Learn (Machine Learning)

### Exploratory Data Analysis (EDA)

The project begins with data exploration, which includes:

**Handling missing values and outliers**

**Visualizing feature distributions and correlations**

**Identifying patterns in diabetes prevalence**

### Machine Learning Models

The following classification machine learning models were implemented and evaluated:

**Logistic Regression:**	**70.56%**

**Random Forest:** **65.25%**

**Decision Tree:** **65.63%**

**Support Vector Machine:** **62.21%**

**k-Nearest Neighbor:** **80.16%**

**MLP Classifier:** **65.57%**

### Performance Metrics Evaluated:

Confusion Matrix

Classification Report

ROC Curve & AUC Score

### Key Findings

1. Certain behavioral and health factors significantly contribute to diabetes risk.
2. Feature importance analysis shows that BMI, Hypertension, and Physical Inactivity are strong predictors.
3. Machine learning models successfully classify individuals based on diabetes risk.

### Conclusion

This project demonstrates the power of machine learning in predicting diabetes risk using health indicators. The findings can be utilized for public health awareness, preventive measures, and early diagnosis strategies.

### Future Scope

✔ Experimenting with deep learning models for improved accuracy.
✔ Deploying the model as a web-based predictive tool.
✔ Feature engineering for more insightful predictors.
