# Student Performance Prediction
📌 Project Overview

This project builds a machine learning model to predict student academic performance (Pass/Fail) using academic, behavioral, and socio-economic factors. The goal is to identify key drivers of student success and demonstrate an end-to-end machine learning workflow.

🎯 Objective

* Predict whether a student will Pass or Fail

* Analyze the impact of study habits, attendance, past exam scores, parental education, internet access, and extracurricular activities

* Compare multiple models and select the best-performing one

📊 Dataset

* Records: 500 students (after cleaning)

* Target Variable: Pass_Fail (Pass = 1, Fail = 0)

* Features: Study hours, attendance rate, past exam scores, parental education, internet access, extracurricular activities, gender

🔍 Key EDA Insights

* Higher study hours, attendance, and past exam scores strongly correlate with passing

* Students with internet access and extracurricular involvement perform better

* Dataset is class-imbalanced, requiring evaluation beyond accuracy

🤖 Models Trained

* Logistic Regression

* Random Forest

* Gradient Boosting

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

🏆 Best Model

Threshold-Optimized Logistic Regression;

* Accuracy: 78%

* ROC-AUC: 0.837

* Pass Recall: 83%

Chosen for its strong minority-class performance and interpretability.

🛠️ Tools & Technologies

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn

* Jupyter Notebook

🚀 Key Takeaways

* Threshold optimization significantly improves performance on imbalanced data

* Simpler models can outperform complex ones when properly tuned

* Academic behavior and prior performance are the strongest predictors of success
