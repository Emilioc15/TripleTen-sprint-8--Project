# TripleTen-sprint-8--Project
🏦 Supervised Learning: Customer Churn Prediction — Beta Bank
📝 Project Overview

This project focuses on building a supervised machine learning model to predict customer churn at Beta Bank. Since retaining existing customers is more cost-effective than acquiring new ones, the bank aims to proactively identify customers who are likely to terminate their contracts.

Using historical customer behavior data, the objective is to train and evaluate classification models that accurately predict churn while accounting for class imbalance. The primary evaluation metric is F1 score, with a required minimum threshold of 0.59 on the test dataset. The AUC-ROC metric is also used to compare model performance.

📊 Dataset Description

The dataset contains historical information about Beta Bank customers, including:

Demographic information

Account and financial behavior

Contract status (active or terminated)

The target variable indicates whether a customer has left the bank.

This is a binary classification problem with an imbalanced class distribution.

🎯 Objectives

Load and preprocess customer data

Analyze and address class imbalance

Train multiple supervised learning models

Apply at least two techniques to handle imbalanced data

Optimize model performance using validation data

Evaluate the final model using F1 score and AUC-ROC

Provide insights to support customer retention strategies

🔍 Key Tasks Performed
🧹 Data Preparation

Loaded and cleaned the dataset

Handled missing values and data types

Split data into training, validation, and test sets

⚖️ Class Imbalance Analysis

Examined class distribution in the target variable

Trained baseline models without correcting imbalance

Evaluated baseline performance and limitations

🔧 Model Improvement

Applied multiple techniques to address class imbalance, including:

Class weighting

Resampling methods

Trained and tuned multiple classification models

Selected optimal hyperparameters using validation data

🧪 Model Evaluation

Evaluated models using F1 score as the primary metric

Compared results with AUC-ROC

Performed final testing on unseen data

🛠️ Models & Tools Used

Logistic Regression

Decision Tree

Random Forest

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Jupyter Notebook

📈 Final Deliverables

Fully documented Jupyter Notebook

Model comparison and evaluation results

Final model meeting the F1 score requirement

Performance comparison using F1 and AUC-ROC

Clear conclusions and recommendations

✅ Success Criteria

A successful project demonstrates:

Proper handling of imbalanced classification problems

Effective model selection and tuning

Clear understanding of evaluation metrics

Strong predictive performance on test data

Actionable insights for customer retention

📌 Conclusion

This project demonstrates how supervised learning techniques can be applied to real-world business problems involving customer churn. By addressing class imbalance and optimizing model performance, the final solution provides a reliable method for identifying customers at risk of leaving and supports data-driven retention strategies.
