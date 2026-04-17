# Hospital Readmission Prediction

This project applies predictive analytics techniques to identify patients at risk of hospital readmission within 30 days. The goal is to support better healthcare decision-making by using machine learning to identify high-risk patients and improve outcomes.

---

##  Project Overview

Hospital readmissions are a major challenge in healthcare, leading to increased costs and poorer patient outcomes. This project builds classification models to predict whether a patient will be readmitted within 30 days using demographic, clinical, and hospital utilization data.

---

##  Data

The dataset was obtained from Kaggle and contains over 100,000 patient records with more than 50 variables, including demographic information, medical history, and prior hospital utilization.

The target variable indicates whether a patient was readmitted within 30 days. A binary variable was created to simplify the prediction task.

---

##  Exploratory Data Analysis

Exploratory data analysis revealed key trends in the dataset:

- Patients with more prior inpatient visits were more likely to be readmitted  
- Longer hospital stays were associated with higher readmission risk  
- The dataset was imbalanced, with significantly more non-readmitted patients than readmitted patients  

These findings highlight the importance of healthcare utilization as a predictor of readmission.

---

##  Methodology

The following steps were used to prepare and analyze the data:

- Data cleaning and handling missing values  
- Removal of variables with excessive missing data  
- One-hot encoding of categorical variables  
- Train/test split (80/20)  

Two models were evaluated:

- Logistic Regression (baseline model)  
- Random Forest (final model)  

---

##  Results

The Random Forest model outperformed Logistic Regression and achieved approximately **88.8% accuracy**.

Key insights include:

- Prior inpatient visits, number of medications, and hospital stay duration were the strongest predictors of readmission  
- Model performance was impacted by class imbalance, making it more difficult to identify readmitted patients  

---

## Conclusion

This project demonstrates how predictive analytics can be used to identify patients at higher risk of hospital readmission. These insights can help healthcare providers implement targeted interventions to reduce readmission rates and improve patient outcomes.

---

## Limitations

- Class imbalance affected model performance  
- Some variables contained missing data and were removed  
- Additional clinical features could improve prediction accuracy  

---

## Project Links

- **Live Website:** https://jackiehelle.github.io/-hospital-readmission-prediction/](https://jackiehelle.github.io/-Hospital-Readmission-Prediction/
- **Google Colab Notebook:** https://colab.research.google.com/drive/1RKfinwfG4TOgbECmMwUSImQ3iSg6qttS?usp=sharing

---

## Tools & Technologies

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- GitHub Pages  

---

## Author

Jacqueline Helle  
MBA Candidate, Healthcare concentration
Suffolk University
