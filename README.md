# Student Dropout and Academic Success Prediction

## Project Overview
- This project focuses on predicting student academic outcomes using Machine Learning.
- The objective is to identify students who are likely to Dropout, remain Enrolled, or Graduate.
- The analysis helps educational institutions identify at-risk students and improve student retention.

## Dataset Description
- **Dataset:** Predict Students' Dropout and Academic Success
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
- **Total Records:** 4,424
- **Total Columns:** 37 (36 features + 1 target)
- **Target Variable:** Dropout, Enrolled, Graduate

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Project Workflow
- **Data Loading:** Imported and explored the dataset.
- **Data Understanding:** Checked data types, statistical summaries, and dataset structure.
- **Exploratory Data Analysis (EDA):** Analyzed student outcomes using different visualizations.
- **Data Preprocessing:** Checked missing values, handled outliers, skewness, and categorical encoding.
- **Feature Selection:** Applied correlation analysis and SelectKBest.
- **Model Building:** Implemented multiple Machine Learning classification algorithms.
- **Model Evaluation:** Compared models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
- **Hyperparameter Tuning:** Applied GridSearchCV and RandomizedSearchCV to improve model performance.

## Data Visualizations
- Pie Chart – Student academic outcomes.
- Bar Chart – Academic outcomes based on scholarship status.
- Scatter Plot – First and second semester approved units.
- Histogram – Student age distribution.
- Count Plot – Academic outcomes across courses.
- Box Plot – Previous qualification grades.
- Histogram – Semester evaluation distribution.

## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- XGBoost Classifier

## Key Findings
- Approximately 49.9% of students graduated.
- Around 32.1% of students dropped out.
- Scholarship holders showed better graduation outcomes.
- Students with higher approved units in both semesters were more likely to graduate.
- Academic performance and financial factors played important roles in student outcomes.

## Model Performance
- **Best Performing Model:** XGBoost Classifier.
- **Test Accuracy:** 73.11%
- **Train Accuracy:** 78.41%
- **Test F1-Score:** 0.6990
- **Generalization Gap:** 5.30%

## Conclusion
- Machine Learning helps identify students who are at risk of dropping out.
- XGBoost provided the best overall balance of performance among the evaluated models.
- Early identification of at-risk students can help institutions provide timely academic and financial support.

## Author
- **Name:** Chenne U.
- **Batch:** DSB04
- **Role:** Data Science Learner
