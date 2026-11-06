# 🎓 Student Dropout and Academic Success Prediction

## 📌 Project Overview

This project focuses on predicting student academic outcomes using Machine Learning classification algorithms. The goal is to identify students who are likely to Dropout, remain Enrolled, or Graduate based on their academic performance, demographic, and socioeconomic factors.

## 🎯 Objectives

- Analyze and understand student academic data.
- Perform Exploratory Data Analysis (EDA).
- Identify important factors influencing student academic success.
- Apply data preprocessing and feature selection techniques.
- Build and compare different Machine Learning classification models.
- Identify the best-performing model for predicting student outcomes.
- Analyze overfitting and underfitting.

## 📊 Dataset

- **Dataset:** Predict Students' Dropout and Academic Success.
- **Source:** UCI Machine Learning Repository.
- **File:** `Students academic.csv`
- **Total Records:** 4,424
- **Total Columns:** 37 (36 features + 1 target).
- **Target Variable:** Dropout, Enrolled, Graduate.
- **Dataset Link:** https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🔄 Key Operations Performed

### 1. Data Exploration
- Loaded and examined the dataset.
- Checked dataset shape, columns, and data types.
- Generated descriptive statistical summaries.
- Identified missing values and duplicates.

### 2. Exploratory Data Analysis (EDA)
- Analyzed student academic outcomes using visualizations.
- Studied graduation rates based on scholarship status.
- Examined first and second semester academic performance.
- Analyzed age distribution and course-wise student outcomes.
- Explored relationships between academic and socioeconomic factors.

### 3. Data Preprocessing
- Checked and handled missing values.
- Identified and removed duplicate records.
- Detected outliers using the IQR method.
- Applied outlier capping.
- Handled skewness using transformations.
- Performed Label Encoding.
- Applied Normalization.

### 4. Feature Selection
- Performed correlation analysis.
- Identified important features using SelectKBest.
- Analyzed the relationship between academic, financial, and demographic factors.

### 5. Model Building
Implemented the following Machine Learning algorithms:

- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Naive Bayes
- Support Vector Machine (SVM)
- XGBoost Classifier

### 6. Model Evaluation and Tuning
- Evaluated models using Accuracy, Precision, Recall, and F1-Score.
- Generated confusion matrices.
- Applied Cross-Validation.
- Performed GridSearchCV and RandomizedSearchCV.
- Compared model performance.
- Analyzed overfitting and underfitting.

## 📈 Key Findings

- Approximately 49.9% of students graduated, while 32.1% dropped out.
- Scholarship holders showed better graduation outcomes.
- Students with higher approved units in both semesters were more likely to graduate.
- Academic performance was a major predictor of student success.
- Financial difficulties, including outstanding tuition fees and debt, were associated with student dropout.
- Students' second-semester academic engagement provided important early warning signals.

## 🏆 Model Performance

- **Best Performing Model:** XGBoost Classifier.
- **Training Accuracy:** 78.41%
- **Testing Accuracy:** 73.11%
- **Test F1-Score:** 0.6990
- **Generalization Gap:** 5.30%

XGBoost provided the best overall balance between predictive performance and generalization among the evaluated models.

## 💡 Conclusion

- Machine Learning can help educational institutions identify students at risk of dropping out.
- Academic performance and financial stability are important factors influencing student outcomes.
- XGBoost demonstrated the best overall performance in this project.
- Early identification can help institutions provide timely academic and financial support to students.

## 👩‍💻 Author

- **Name:** Chenne U.
- **Batch:** DSB04
- **Role:** Data Science Learner
