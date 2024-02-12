# Early-Stage-Diabetes-EDA-Prediction
INTRODUCTION

In this project, the objective was to predict the risk of early-stage diabetes using a dataset specifically curated for this purpose. Initially, my efforts were directed towards cleaning the data, a fundamental step where I identified and rectified any duplicates or missing values.

Age was categorized into distinct groups to better understand its influence on diabetes risk, acknowledging that age is a significant factor in health risk assessment. Furthermore, I conducted a thorough examination of categorical variables to determine their correlation with diabetes risk.

For visualization, pie charts were employed to represent the distribution of responses clearly. Special attention was given to ensure that positive responses, such as 'Yes' and 'Positive', were consistently highlighted for easy identification.

The preprocessing phase involved One-Hot Encoding to handle categorical variables and scaling to normalize the data, preparing it for effective model training. I evaluated a variety of models, including Logistic Regression and RandomForestClassifier, to identify the most accurate predictor of diabetes risk.

The RandomForestClassifier emerged as the most effective model, demonstrating superior performance on both the training set and the test set. It was notably proficient in correctly identifying individuals without diabetes (achieving high recall) and in accurately detecting patients with diabetes (achieving high precision) in the test set.

To gain deeper insights into the model's performance, I analyzed the classification reports and confusion matrices for both the training and test sets. This allowed me to assess the model's effectiveness across different classes meticulously. Additionally, I explored the feature importance to pinpoint the variables most impactful in predicting diabetes risk.
