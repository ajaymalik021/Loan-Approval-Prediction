Loan Status Prediction

Project Overview

This project aims to predict loan approval status using machine learning. The dataset includes various applicant details, and the goal is to classify whether a loan will be approved or rejected based on features like income, credit history, and employment status.

Dataset

The dataset contains the following key features:

  Applicant Details: Income, employment type, number of dependents.

  Loan Information: Loan amount, term, credit history.
  
  Categorical Variables: Education, self-employment status, property area.

Tech Stack

  Programming Language: Python

  Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

  Model Used: Logistic Regression

Project Workflow

  Data Preprocessing

    Handle missing values

    Feature scaling using StandardScaler

    Encode categorical variables

  Model Training

    Train Logistic Regression model

    Split dataset into train/test sets

  Model Evaluation

    Compute accuracy score

    Generate classification report

    Visualize results with a confusion matrix

Results & Insights:
1. Data Preprocessing

    Unnecessary columns (loan_id, no_of_dependents, education, self_employed) were dropped.
    Features were split into X (independent variables) and y (target variable: loan_status).
    The dataset was split into training (80%) and testing (20%) sets.
    Feature Scaling: StandardScaler() was used to normalize numerical features.

2. Model Training

    Algorithm Used: Logistic Regression
    LogisticRegression() was trained on the preprocessed dataset.
    The model was fitted using X_train and y_train, then predictions (y_pred) were generated.

3. Evaluation Metrics

    Accuracy Score: The model's accuracy was calculated.
    Classification Report: Precision, recall, and F1-score were evaluated.
