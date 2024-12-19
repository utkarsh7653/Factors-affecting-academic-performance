# Factors-affecting-academic-performance
Objective:
The primary goal of the study was to identify and analyze key contributors to student performance, such as study habits, attendance, socio-economic factors, and other personal and institutional variables. By understanding these relationships, the project aims to provide insights for educators, policymakers, and students to enhance educational outcomes.

Dataset:
The study utilized a synthetically generated dataset representing real-world scenarios:

Source: Kaggle - Student Performance Factors Dataset
Key Variables: Exam scores, study hours, attendance, socio-economic indicators, teacher quality, and more.
Methodology:
Exploratory Data Analysis (EDA): Unveiled relationships between variables using visualizations and statistical summaries.
Modeling Techniques:
Linear Regression
Reduced Models (using stepwise selection)
Lasso Regression (selected as the final model)
Model Evaluation: Compared models using AIC, adjusted R-squared, and RMSE for train-test split data validation.

Key Findings:
Attendance and hours studied showed the strongest correlation with exam scores.
Socio-economic factors such as family income and access to resources significantly impacted performance.
The Lasso model emerged as the best balance between predictive power, interpretability, and generalization, with an RMSE of ~1.74 on the test set.

Limitations and Future Work:
While the synthetic dataset allowed for exploratory analysis, future work could integrate real-world data to enhance generalizability. Additionally, incorporating factors like mental health and advanced non-linear models could improve predictions.
