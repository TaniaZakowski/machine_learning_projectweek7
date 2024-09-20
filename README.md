# 🎓 Predicting Student Success Using Machine Learning

## Project Overview:

This project aims to predict student academic success based on various features using machine learning models. By forecasting the likelihood of a student's successful graduation (Pass/Fail), we can help educational institutions identify at-risk students early and provide them with targeted support. 🎯

## 🏆 Objectives:

- Improve decision-making for educators.
- Identify at-risk students and provide timely interventions.
- Enhance student well-being by increasing graduation rates and lowering dropout rates.

## 📊 Data Overview:
- Dataset: The dataset includes academic performance data from 4,424 students, such as grades, attendance, and demographic information.
- Data Cleaning: Removed outliers and handled missing values, resulting in a clean dataset of 4,338 rows.
- Target Variable: Pass/Fail classification for predicting student success.


## 🔧 Methodology:

1. Data Processing
- Replaced or removed missing values.
- Identified and removed outliers.
- Feature engineering was applied to create new features like Average Grades and Pass Rates.

2. Exploratory Data Analysis (EDA)
- Correlation matrix calculated between features and the target variable (Pass/Fail).
- Selected 16 relevant features based on a correlation threshold of 0.1.

3. Model Building
- We developed and compared three machine learning models to predict student success:

- K-Nearest Neighbors (KNN)
  - Best parameters: n_neighbors=9, metric=manhattan, weights=distance.
  - Accuracy: 81.34%
- Random Forest
  - Outperformed KNN.
  - Accuracy: 83.64%
    
- Gradient Boosting
  - Achieved the highest accuracy.
  - Accuracy: 84.10%
    
⚙️ Hyperparameter Tuning: Grid Search was employed to optimize the hyperparameters of KNN and Random Forest models.


## 📈 Results:

Best Model: Gradient Boosting with an accuracy of 84.10%.
Comparison Metrics: We used accuracy and F1 score to evaluate and compare the models.


## 🌍 Real-World Impact:

By predicting student success, this project can:

- Reduce dropout rates and increase graduation rates.
- Improve resource efficiency for educational institutions.
- Offer targeted support to students who need it most.

## 🔮 Future Work:

- Incorporate post-enrollment and behavioral data.
- Experiment with advanced model architectures.
- Implement a real-time early warning system to provide predictions in real time.
  
## 🛠️ Team Members:

Nicole, Mehdi, Tania, Houleye

Feel free to reach out if you have any questions! 😊

