## Loan-Approval-Prediction-System--Python

### Summary

The project involves building a Loan Prediction System using Python and machine learning. The dataset consists of various customer details, such as income, credit history, education, and loan amount, to predict whether a loan will be approved (Y) or rejected (N).

**1.	Data Preprocessing & Cleaning:**
   
o	Loaded the dataset using pandas.
o	Identified and handled missing values using mean, mode, and log transformations.
o	Created new features like TotalIncome and LoanAmount_Log to improve prediction accuracy.

**2.	Exploratory Data Analysis (EDA):**
   
o	Visualized categorical variables (Gender, Married, Dependents, Credit History) using Seaborn count plots.
o	Analyzed loan distribution patterns based on various factors.
o	Found that credit history plays a significant role in loan approval.

**3.	Feature Encoding & Model Preparation:**
   
o	Converted categorical variables into numerical format using Label Encoding.
o	Split the dataset into training (80%) and testing (20%) using train_test_split.
o	Defined the feature matrix (X) and target variable (y).

**4.	Model Training & Prediction:**
   
o	Implemented a Support Vector Machine (SVM) classifier for loan prediction.
o	Encoded the target variable Loan_Status (Y/N) into binary format (0/1).
o	Trained the model on preprocessed data.
________________________________________

### Outcome & Achievements

•	Successfully preprocessed and cleaned the dataset to handle missing values and categorical data.
•	Gained insights from EDA, revealing key factors affecting loan approval.
•  Applied classification models, including Random Forest, Decision Tree, KNN, and Naive Bayes, to determine the best-performing model. 
•  Achieved the highest accuracy of 83% using the Naive Bayes model, making it the chosen model due to its strong performance in handling the data distribution and 
   categorical features. 
•	The model can now predict whether an applicant will get a loan based on their income, credit history, and other factors.

