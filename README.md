Loan Status Prediction
📌 Overview

This project focuses on predicting the status of loan applications using machine learning techniques. By analyzing various features of loan applicants, the model predicts whether a loan will be approved or rejected based on historical data.

The project demonstrates the complete workflow of a machine learning pipeline, from data preprocessing to model evaluation and tuning, ensuring the model is ready for deployment.

🎯 Features

Data Preprocessing & Feature Engineering: Handle missing values, encode categorical variables, scale numeric features, and create relevant features.

Exploratory Data Analysis (EDA): Understand feature distributions, relationships, and patterns affecting loan approvals.

Machine Learning Model Training: Implemented two models — Random Forest Classifier and Support Vector Classifier (SVC).

Hyperparameter Tuning: Used RandomizedSearchCV to optimize model parameters.

Imbalanced Data Handling: Applied SMOTE to balance target classes and improve minority class prediction.

Evaluation: Assessed models using accuracy, precision, recall, and F1-score.

Technologies Used

Python – programming & data analysis

Jupyter Notebook – development & visualization

Pandas & NumPy – data manipulation

Matplotlib & Seaborn – data visualization

Scikit-learn – model training, evaluation, hyperparameter tuning

Imbalanced-learn (SMOTE) – handling class imbalance

📂 Dataset

The dataset contains features such as:

Applicant income

Co-applicant income

Loan amount & loan term

Credit history

Property area

Gender, Marital status, Dependents, Education, Self-employed status

Note: Ensure the dataset is placed in the appropriate directory before running the notebook.

📊 Results
Model	Accuracy
Random Forest Classifier	77.2%
Support Vector Classifier	83.7%

Key Observations:

SVC achieved higher accuracy compared to Random Forest.

Handling missing values with SimpleImputer and scaling numeric features improved model performance.

Applying SMOTE improved minority class predictions, even if overall accuracy slightly changed.

Hyperparameter tuning using RandomizedSearchCV optimized model parameters and improved generalization.

Evaluation metrics include accuracy, precision, recall, and F1-score, providing a full picture of model performance.

🏁 Conclusion

This project demonstrates a complete machine learning workflow for predicting loan approvals. By using preprocessing, handling imbalanced data, and hyperparameter tuning, the models provide reliable predictions.

The SVC model achieved the highest accuracy, making it a strong candidate for deployment.

📧 Contact

For any questions or inquiries:
Email: samahassans73s@gmail.com
