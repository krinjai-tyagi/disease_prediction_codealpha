# Heart Disease Prediction

This is my project for the CodeAlpha Machine Learning Internship (Disease Prediction from Medical Data).

I made a model that tells whether a person may have heart disease or not, using details like age, sex, chest pain type, blood pressure, cholesterol and heart rate.

## What I did

- Loaded the heart disease dataset and checked it
- Removed duplicate rows
- Changed text columns (like Male/Female) into numbers
- Scaled the data and split it into train and test
- Tried 4 models: Logistic Regression, SVM, Random Forest and XGBoost
- Compared them using accuracy, precision, recall, F1 and ROC-AUC
- Picked Random Forest and tuned it with GridSearchCV
- Saved the final model using joblib

I focused on recall because in a medical case, missing a sick patient is worse than a false alarm.

## Result

Random Forest gave Accuracy XX%, Recall XX% and ROC-AUC XX.

## Files

- Heart_Disease_Prediction.ipynb : full code
- HeartDiseaseTrain-Test.csv : dataset
- heart_model.pkl and scaler.pkl : saved model and scaler

## Tools used

Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

This project is only for learning, not for real medical use.
