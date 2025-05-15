# 🏦 Loan Approval Prediction

This project uses machine learning (Support Vector Classifier) to predict loan approval status based on user input. Includes training code, dataset, model, and a demo video.

---

## 📁 Files to Explore

- 📦 [Trained SVC Model (`svc_model_11_features.pkl`)](./svc_model_11_features.pkl)  
  This is the serialized Support Vector Classifier (SVC) model trained using 11 selected features from the dataset. It can be loaded with `joblib` or `pickle` to make predictions without retraining.

- 📊 [Dataset File (`loan_data_set.csv`)](./loan_data_set.csv)  
  This CSV file contains the loan applicant data used for training and evaluating the model. It includes features such as income, credit history, loan amount, etc.

- 🎥 [Demo Video (`demo_video.mp4`)](./demo_video.mp4)  
  A walkthrough demonstration of the project showcasing how the model works and how predictions are made through the frontend or notebook.

- 📱 [Android APK File (`LoanApprovalApp.apk`)](./app-release.apk)  
  An Android application built to provide a mobile-friendly interface for users to input loan-related data and get instant loan approval predictions using the trained model.

---

## 🚀 How to Use

1. Clone this repository
2. Open `SVC_classifier.ipynb` in Jupyter
3. Make sure the `.pkl` and `.csv` files are in the same folder
4. Run the notebook to make predictions

---

