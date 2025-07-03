#  Credit Risk Classification Model (Good / Bad)

This project involves building a supervised machine learning classification model to predict whether a borrower's credit risk is **"Good"** or **"Bad"**, based on historical loan applicant data. The goal is to assist financial institutions in making more informed lending decisions and minimizing defaults.



##  Problem Statement

Financial institutions face significant risk when lending to borrowers who may default. Accurately predicting whether a borrower is likely to repay (good risk) or default (bad risk) is critical. This project uses machine learning to classify credit risk using demographic and financial attributes.

---

## Dataset Overview

The dataset typically includes the following features:

| Feature             | Description                              |
|---------------------|------------------------------------------|
| Age                 | Applicant’s age                          |
| Job                 | Employment category                      |
| Credit Amount       | Total loan amount                        |
| Duration            | Duration of credit in months             |
| Credit History      | Record of past credit behavior           |
| Purpose             | Reason for loan (car, education, etc.)   |
| Housing             | Housing status (own, rent, free)         |
| Employment Duration | Length of employment                     |
| Saving Accounts     | Type of savings account                  |
| Existing Credits    | Number of current loans                  |
| Target (`credit_risk`) | **Good** or **Bad** credit risk       |


##  Tools & Technologies

- **Programming Language**: Python 3.x
- **Libraries Used**:
  - `pandas` – Data loading & manipulation
  - `numpy` – Numerical operations
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Model building & evaluation

##  Exploratory Data Analysis (EDA)

- Checked for missing values and outliers
- Visualized correlations and class balance
- Performed feature encoding (e.g., One-Hot or Label Encoding)


##  Machine Learning Models Used

| Model                 | Description                              |
|----------------------|------------------------------------------|
| Logistic Regression   | Baseline binary classifier               |
| Decision Tree         | Simple rule-based classification         |
| Random Forest         | Ensemble of decision trees               |
| Support Vector Machine (SVM) | Max-margin classifier            |


##  Evaluation Metrics

- **Accuracy**
- **Precision / Recall / F1-Score**
- **Confusion Matrix**
- **ROC-AUC Curve**

---

##  Results

- The best-performing model achieved an accuracy of **~X%** (replace with actual).
- It successfully identified high-risk applicants with a balance between precision and recall.

---

##  Key Learnings

- Importance of preprocessing categorical data
- Handling imbalanced datasets
- Model selection and hyperparameter tuning
- Business impact of classification accuracy

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-classification.git
   cd credit-risk-classification
