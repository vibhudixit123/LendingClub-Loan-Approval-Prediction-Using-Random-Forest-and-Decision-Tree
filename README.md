
# LendingClub Loan Approval Prediction

This repository contains the code and documentation for a machine learning project focused on predicting loan approval using Decision Trees and Random Forest algorithms. The dataset used for this project is loan_data.csv from LendingClub. The goal is to build models that predict whether a borrower meets the credit underwriting criteria and whether they will fully repay the loan.

## Screenshots
![Screenshot 2024-01-31 215942](https://github.com/vibhudixit123/DECISION_TREE_AND_RANDOM_FOREST/assets/104568465/c42845ab-5664-4c0e-a312-9cec4af6f39d)
![Screenshot 2024-01-31 215956](https://github.com/vibhudixit123/DECISION_TREE_AND_RANDOM_FOREST/assets/104568465/97513331-da52-4083-8bfa-4426fbf64a11)
![Screenshot 2024-01-31 220022](https://github.com/vibhudixit123/DECISION_TREE_AND_RANDOM_FOREST/assets/104568465/63072058-8238-458f-8ac8-2e070f18fe9f)

## Data
The loan_data.csv dataset includes various features related to borrowers and loans, such as credit policies, loan purposes, interest rates, annual income, debt-to-income ratio, credit scores, and more.
## Machine Learning Models:

The project employs two machine learning algorithms:

Decision Trees:

Decision Trees are used to create a model that predicts loan approval based on various features.
The model recursively splits the dataset into subsets based on the most significant attribute.

Random Forest:

Random Forest, an ensemble method, is utilized to enhance the predictive power.
It consists of multiple decision trees and aggregates their predictions to improve accuracy and reduce overfitting.
## Data Preprocessing:
Various preprocessing techniques are applied to the dataset to prepare it for model training:

Encoding Categorical Variables:

Categorical variables like "purpose" are encoded into numerical format using techniques such as one-hot encoding.

Handling Missing Data:

Missing data is handled using methods like imputation or removal, ensuring the dataset is complete.

Scaling Numerical Features:

Numerical features are scaled to bring them to a similar scale, preventing certain features from dominating the model.
## Target Audience:
This project is particularly relevant for credit approval teams within financial institutions. The machine learning models developed here can assist these teams in automating and enhancing the loan approval process, making it more efficient and data-driven.
## Training and Evaluation:
The models are trained on a portion of the dataset and evaluated on another to ensure robust performance. Performance metrics such as accuracy, precision, recall, and F1 score are calculated.
