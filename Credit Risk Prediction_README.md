**Project Description**  
This project predicts whether a loan applicant will be approved based on personal and financial details using logistic regression. The model helps lenders automate and improve approval decisions.

**Dataset Used**  
[Loan Prediction Dataset from Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset) – Contains ~614 applicants with features like income, education, and loan amount, and a binary target `Loan_Status` (Y/N).

**Steps**  
- **Data Cleaning**: Handled missing values by imputing categorical features with mode and numerical features with median.  
- **EDA**: Visualized approval rates by education level and income vs. loan amount to uncover trends.  
- **Model**: Encoded categorical variables, trained a Logistic Regression model on 80% of the data.  
- **Results**: Evaluated performance using accuracy and confusion matrix on the 20% test set.

**Key Insights**  
- Graduates are significantly more likely to get loan approval than non-graduates.  
- The model achieved **82.8% accuracy**, with strong performance in correctly identifying both approved and rejected applications.  
- Confusion matrix shows balanced prediction across classes, indicating reliable generalization.

**Tech Stack**  
Python, Pandas, Scikit-learn (LogisticRegression, train_test_split, metrics), Matplotlib, Seaborn, LabelEncoder
