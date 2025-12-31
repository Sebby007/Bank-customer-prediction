Bank Customer Churn Prediction (Supervised ML)
In this project, I developed a supervised machine learning model to predict whether a customer will leave a retail bank (customer churn). Using historical customer behavior and contract termination data, the goal was to identify at-risk customers early and support data-driven retention strategies.

The project involved thorough data preprocessing, including handling missing values, encoding categorical features, and addressing class imbalance using class weighting. Multiple models were trained and evaluated, with systematic hyperparameter optimization performed using GridSearchCV to maximize the F1 score, the primary business metric.

The final model exceeded the project threshold, achieving an F1 score of 0.65 on the test set, along with a strong AUC-ROC score, demonstrating good generalization and reliable classification of churned customers. This solution provides actionable insights for proactive customer retention and highlights the practical business value of supervised learning in financial services.

🧠 Skills Highlighted (useful for README or LinkedIn)

Supervised Machine Learning

Logistic Regression

Class Imbalance Handling (class_weight='balanced')

Feature Engineering

Model Evaluation (F1, AUC-ROC)

Hyperparameter Tuning (GridSearchCV)

Python, Pandas, NumPy, Scikit-Learn
