**Parkinson's Disease Detection using Machine Learning**
**📌 Project Overview**
This project aims to develop a machine learning model to detect Parkinson's Disease (PD) using voice measurement data. The dataset contains biomedical voice recordings from healthy individuals and those with Parkinson's, with the goal of early and accurate diagnosis through computational analysis.

**🎯 Objective**
To build and compare machine learning models that classify whether a patient has Parkinson's Disease based on vocal features, achieving high accuracy and reliability for potential diagnostic assistance.

**📊 Dataset**
Source: UCI Machine Learning Repository - Parkinson's Disease Classification Dataset

Samples: 195 voice recordings

Features: 23 attributes (MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), Jitter(%), Shimmer, HNR, RPDE, DFA, PPE, etc.)

Target Variable: status (1 = Parkinson's, 0 = Healthy)

🛠️ Tools & Technologies
Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Models Used:

Logistic Regression
Random Forest Classifier
Environment: Jupyter Notebook

**📈 Methodology**
**1. Data Exploration & Preprocessing**
Loaded and inspected the dataset for structure and missing values.

Performed exploratory data analysis (EDA) including distribution analysis of the target variable.

Dropped non-predictive columns (name) to focus on biomedical features.

Split data into training and testing sets (80/20 split).

**2. Model Development**
Implemented Logistic Regression with increased max_iter for convergence.

Trained a Random Forest Classifier for improved performance and robustness.

Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.

**3. Results**
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	82.05%	0.82	0.82	0.82
Random Forest	89.74%	0.90	0.90	0.89
Confusion Matrix (Random Forest):

True Negatives: 7
False Positives: 3
False Negatives: 1
True Positives: 28
