# Loan Status Prediction using Machine Learning

This project predicts whether a loan application will be approved or rejected based on applicant details using machine learning techniques.

# Features

Predicts loan approval status (Approved/Not Approved)

Data preprocessing (handling missing values, encoding categorical variables)

Feature scaling for better model performance

Multiple ML algorithms compared (Logistic Regression, Random Forest, Decision Tree, etc.)

Model evaluation using accuracy, confusion matrix, and classification report

# Technologies Used

Python

Scikit-learn – Model building & evaluation

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

# Installation

Clone the repository:

git clone https://github.com/yourusername/loan-status-prediction.git
cd loan-status-prediction


Install required libraries:

pip install -r requirements.txt

# Usage

Place your dataset (loan_data.csv) in the project folder.

Run the script:

python loan_prediction.py


View the predicted loan status for each applicant.

Dataset

Contains features such as:

Applicant Income

Co-applicant Income

Loan Amount

Loan Term

Credit History

Gender, Education, Marital Status, etc.

# Output Example

Input: Applicant with income 5000, loan amount 100, credit history 1

Prediction: Approved

# Future Enhancements

Deploy as a web app using Flask/Django

Improve accuracy with deep learning

Add automated feature selection
