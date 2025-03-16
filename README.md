🏦 Loan Approval Classifier

Hey there! 👋

Welcome to my Loan Approval Classifier project! This project is all about predicting whether a loan application will get approved or not based on the applicant's financial and personal details. I built this to simplify the loan approval process and make it faster and more accurate using machine learning.

🚀 Why This Project?
Loan approval decisions can be tricky — banks need to balance between approving more loans and minimizing the risk of defaults. That's where machine learning comes in! By analyzing past data and recognizing patterns, the model can predict whether an applicant is likely to get their loan approved or not.

🎯 What This Project Does
✅ Predicts loan approval status based on applicant details
✅ Reduces manual effort and speeds up the approval process
✅ Helps financial institutions make better, data-driven decisions

🧠 How I Built It
I used Python and some of the most popular ML libraries:

Scikit-learn – For training and evaluating the model
Pandas – For handling and cleaning the data
NumPy – For numerical computations
Matplotlib & Seaborn – For plotting cool visualizations
The model is based on a Random Forest Classifier — it turned out to be the most accurate after testing different approaches!

📊 The Data
Here’s a quick overview of the key features in the dataset:

🆔 Loan ID – Unique identifier for each loan
👨‍👩‍👧‍👦 Dependents – Number of dependents the applicant has
🎓 Education – Applicant’s education level
💼 Self Employed – Whether the applicant is self-employed
💰 Income Annum – Annual income of the applicant
🏠 Loan Amount – The requested loan amount
⏳ Loan Term – Duration of the loan
📉 CIBIL Score – Credit score of the applicant
🏡 Asset Values – Value of residential, commercial, and luxury assets
✅ Loan Status – Whether the loan was approved or not
🏆 How Well It Works
After some tweaking and testing, the model hit an impressive 98% accuracy on the test data! 🎯

Classification Report:

Metric	Value:-

Accuracy	98%
Precision	98%
Recall	98%
F1-Score	98%
Macro Avg	97%
Weighted Avg	98%
Confusion Matrix:

Actual/Predicted	0	1
0 (Not Approved)	527	9
1 (Approved)	12	306
