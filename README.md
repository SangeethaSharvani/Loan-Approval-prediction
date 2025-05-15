# loan-approval-prediction
Loan Prediction System using Support Vector Machine (SVM)
The Loan Prediction System is a machine learning-based project designed to predict the approval status of loan applications using applicant data. The system is built using the Support Vector Machine (SVM) algorithm, a robust and widely-used supervised learning method for binary classification tasks. This system helps financial institutions automate the decision-making process and evaluate loan eligibility more efficiently.

The dataset used contains features such as gender, marital status, education level, self-employment status, applicant income, co-applicant income, loan amount, loan term, credit history, and property area. The target variable is Loan_Status, indicating whether the loan was approved or not.

To prepare the data, missing values were handled using appropriate imputation techniques. Categorical variables were encoded using label encoding and one-hot encoding, while numerical features were standardized to improve the model’s performance. The data was then split into training and testing sets in an 80:20 ratio.

The SVM classifier was trained on the processed training data using a linear kernel. SVM works by finding the optimal hyperplane that best separates the data points into their respective classes—in this case, approved or rejected loan applications. After training, the model was evaluated on the test set using metrics such as accuracy score, which measures the proportion of correct predictions.

The trained model achieved an accuracy of approximately 83% , demonstrating its capability to generalize well on unseen data. In addition to performance evaluation, the model was used to predict the loan approval status of new applicants based on their input features. These predictions can assist banks in making fast and reliable loan decisions.

The entire system was implemented using Python, with libraries like Pandas, NumPy, and Scikit-learn for data handling and machine learning. This project showcases the practical application of SVM in financial analytics and provides a foundation for integrating more advanced models or real-time deployment in future work.

