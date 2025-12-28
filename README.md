Heart Disease Prediction Project
📌 Overview
This project aims to predict the 10-year risk of developing Coronary Heart Disease (CHD) using machine learning classification algorithms. The analysis is based on the Framingham Heart Study dataset, utilizing various patient health metrics to train and evaluate predictive models.

📂 Dataset
The dataset (framingham.csv) contains 4,238 records and 16 attributes. It includes demographic, behavioral, and medical risk factors.

Key Features:
Demographic: male, age, education

Behavioral: currentSmoker, cigsPerDay

Medical History: BPMeds (Blood Pressure meds), prevalentStroke, prevalentHyp (Hypertension), diabetes

Clinical Measures:

totChol (Total Cholesterol)

sysBP (Systolic Blood Pressure)

diaBP (Diastolic Blood Pressure)

BMI (Body Mass Index)

heartRate

glucose

Target Variable: TenYearCHD (Binary: 1 = Risk of CHD, 0 = No Risk)

🛠️ Technologies Used
Language: Python

Libraries:

pandas, numpy (Data Manipulation)

matplotlib, seaborn (Visualization)

ydata_profiling (Exploratory Data Analysis)

scikit-learn (Modeling & Preprocessing)

xgboost (Gradient Boosting)

⚙️ Project Workflow
Exploratory Data Analysis (EDA):

Generated a comprehensive profile report using ydata_profiling.

Analyzed distributions, missing values, and correlations (e.g., high correlation between sysBP and diaBP).

Data Preprocessing:

Handling missing values.

Feature Scaling: Applied StandardScaler to normalize features for distance-based algorithms.

Train-Test Split: Split data into 80% training and 20% testing sets.

Model Training: Implemented and compared 7 different classification algorithms:

Logistic Regression

Naive Bayes (GaussianNB)

Random Forest Classifier

Decision Tree Classifier

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

XGBoost Classifier
