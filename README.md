# Loan Approval Prediction System

## Project Overview

The **Loan Approval Prediction System** is a Machine Learning project developed to predict whether a loan application should be **Approved (Y)** or **Rejected (N)** based on the applicant's personal and financial information.

This project uses supervised machine learning classification algorithms to analyze applicant data and identify the most suitable model for loan approval prediction. Multiple machine learning models were trained and compared, with **Logistic Regression** achieving the highest accuracy.

---

## Objective

The primary objective of this project is to build a predictive model that helps financial institutions automate the loan approval process by predicting loan eligibility based on applicant details.

---

## Dataset

- **Dataset:** Loan Prediction Dataset
- **Source:** Kaggle
- **Training Data:** `train.csv`
- **Testing Data:** `test.csv`

The dataset contains applicant information such as:

- Gender
- Marital Status
- Dependents
- Education
- Self Employment
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status (Target Variable)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## Machine Learning Concepts Used

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- Classification
- Feature Selection
- Model Evaluation
- Model Comparison
- Prediction on Unseen Data

---

## Models Implemented

The following machine learning algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost Classifier

---

## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **86.18%** |
| Support Vector Machine | 85.37% |
| Random Forest | 82.93% |
| XGBoost | 82.93% |
| Decision Tree | 76.42% |

**Best Model:** Logistic Regression

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis
4. Handle Missing Values
5. Encode Categorical Variables
6. Feature Selection
7. Train-Test Split
8. Feature Scaling
9. Train Multiple Models
10. Compare Model Performance
11. Evaluate Best Model
12. Save Trained Model
13. Predict Loan Approval for Test Dataset
14. Generate Prediction File

---

## Folder Structure

```
Loan_Approval_Prediction/
│
├── Dataset/
│   ├── train.csv
│   ├── test.csv
│   └── Loan_Predictions.csv
│
├── Notebook/
│   └── Loan_Approval_Prediction.ipynb
│
├── Model/
│   ├── loan_approval_model.pkl
│   └── scaler.pkl
│
├── Streamlit_App/
│
├── Documentation/
│   ├── Project_Report.pdf
│   ├── Presentation.pptx
│   └── Screenshots/
│
└── README.md
```

---

## Results

- Successfully cleaned and preprocessed the dataset.
- Compared five machine learning classification models.
- Logistic Regression achieved the highest accuracy of **86.18%**.
- Generated predictions for unseen loan applications.
- Saved the trained model for future use.

---

## Future Enhancements

- Hyperparameter tuning
- Cross-validation
- Feature engineering
- SMOTE for class balancing
- Streamlit web application deployment
- Cloud deployment using Render or Streamlit Cloud

---

## How to Run the Project

1. Clone this repository.

```
git clone <repository-link>
```

2. Install the required libraries.

```
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
```

3. Open the notebook.

```
Notebook/Loan_Approval_Prediction.ipynb
```

4. Run all cells sequentially.

5. The trained model will be saved inside the **Model** folder.

6. Predictions for the test dataset will be generated as:

```
Loan_Predictions.csv
```

---

## Project Outputs

- Trained Machine Learning Model (`loan_approval_model.pkl`)
- Feature Scaler (`scaler.pkl`)
- Loan Predictions (`Loan_Predictions.csv`)
- Google Colab Notebook
- Project Report
- Presentation
- Screenshots

---

## Author

**Tulika Malviya**

Summer Internship Project 2026

---

## License

This project is developed for educational and internship purposes.
