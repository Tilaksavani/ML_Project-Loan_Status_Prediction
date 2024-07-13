# ML_Project-💰Loan_Status__Prediction💰

This project tackles the task of predicting loan status (approved or rejected) using a Support Vector Machine (SVM) classifier. By analyzing a dataset of loan applicants' attributes, the model seeks to identify patterns that distinguish successful borrowers from those unlikely to repay their loans.

 ### Data
This directory stores the loan applicant data in CSV format. It's assumed the dataset contains attributes like:

 - Loan_ID
 - Gender
 - Married
 - Dependents
 - Education
 - Self_Employed
 - ApplicantIncome
 - CoapplicantIncome
 - LoanAmount
 - Loan_Amount_Term
 - Credit_History
 - Property_Area
 - Loan_Status

		
**notebooks**: This directory contains the Jupyter Notebook (`loan_status_prediction.ipynb`) for data exploration, preprocessing, model training, evaluation, and visualization.


### Running the Project
The main script (main.py or similar) typically follows these steps:

1. Load the data: Load the Loan Status dataset using appropriate libraries.
2. Data Preprocessing: Clean and prepare the data for modeling. This might involve handling missing values, scaling numerical features, and potentially encoding categorical features (if present).
3. Split Data: Divide the data into training and testing sets. The training set is used to train the logistic regression model, and the testing set evaluates its performance on unseen data.
4. Model Training: Train the logistic regression model on the training data.
5. Model Evaluation: Evaluate the model's performance on the testing set using metrics like accuracy, precision, recall, and F1-score.
6. (Optional) Model Saving: Save the trained model for future use.

### Additional Notes
 - This project showcases support vector machine using loan status prediction. You can explore other machine learning models and hyperparameter tuning for potentially better results.
 - Feel free to modify the code to experiment with different functionalities, like making predictions for loan status.

By applying machine learning to loan status prediction, we can potentially improve loan approval processes, enhance risk assessment, and promote financial inclusion. This project provides a valuable foundation for further exploration in this domain.
