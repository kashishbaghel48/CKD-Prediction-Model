
                                Overview

This project focuses on early detection of Chronic Kidney Disease (CKD) using machine learning techniques.
The model analyzes patient health indicators such as blood pressure, albumin levels, hemoglobin, diabetes history, and kidney function metrics to classify whether a patient is likely to have CKD.

The goal is to help healthcare professionals perform early diagnosis and reduce treatment delays.

                              Dataset Description

The CKD dataset typically includes:

Feature Type	Examples
Clinical Indicators	Serum Creatinine, Hemoglobin, Albumin, Sugar, RBC
Vital Parameters	Blood Pressure, Specific Gravity
Medical Conditions	Diabetes Mellitus, Hypertension
Demographics	Age, Sex
Target Label	CKD (1), Not CKD (0)

Samples: ~400 patient records
Target variable: 1 = CKD, 0 = Not CKD

                             Data Preprocessing

Handled missing values

Converted categorical columns using Label Encoding

Applied scaling to numerical features

Split dataset into training & testing

Balanced dataset (if required)

                               Machine Learning Models Used

These ML models were implemented and compared:

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Logistic Regression (baseline)

                           Model Performance

Model	Accuracy	F1-Score	Recall
Random Forest	95%	0.94	0.95
SVM	92%	0.91	0.90
KNN	88%	0.87	0.84

Best Model → Random Forest (95% accuracy)

                            Project Flow

You can upload this flow later as an image:

Data → Cleaning → Preprocessing → Train/Test Split → Model Training → Evaluation → Prediction

                              Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

                               How to Run

Download or clone this repository

Install dependencies

Run CKD_Prediction.ipynb

Check outputs for accuracy, F1-score, confusion matrix

                               Conclusion

This project highlights how machine learning can assist in early detection of CKD.
Accurate identification of CKD risk can support timely treatment and improve patient outcomes.

