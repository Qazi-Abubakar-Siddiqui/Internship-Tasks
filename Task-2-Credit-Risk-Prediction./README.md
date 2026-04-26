#  Credit Risk Prediction Project

##  Task Objective
The primary objective of this project is to build a predictive model that can identify whether a loan applicant is likely to **default** or **pay back** their loan. By automating this process using Machine Learning, financial institutions can:
* Minimize financial losses by identifying high-risk applicants.
* Speed up the loan approval process for low-risk customers.
* Ensure data-driven decision-making based on historical patterns.

---

##  My Approach
To solve this problem, I followed a structured Data Science pipeline:

### 1. Data Acquisition & Understanding
* Utilized the **Loan Prediction Dataset** (Kaggle).
* Performed initial inspection to understand features like `Gender`, `Married`, `Education`, `ApplicantIncome`, and `Credit_History`.

### 2. Data Cleaning & Pre-processing
* **Missing Value Imputation:** Categorical features were filled with the **Mode**, while numerical features (like `LoanAmount`) were filled with the **Median** to handle skewness.
* **Label Encoding:** Converted categorical data into numeric format so the machine learning model could process it.
* **Feature Selection:** Dropped irrelevant columns (like `Loan_ID`) to improve model efficiency.

### 3. Exploratory Data Analysis (EDA)
* Visualized data distributions using **Seaborn** and **Matplotlib**.
* Analyzed the relationship between `Education` and `Loan_Status`.
* Created a **Correlation Heatmap** to identify features that impact loan approvals the most.

### 4. Model Development
* Split the data into **Training (80%)** and **Testing (20%)** sets.
* Trained a **Logistic Regression** model, which is highly effective for binary classification tasks like this.

---

##  Repository Contents
| File | Description |
| :--- | :--- |
| `cleaned_data.csv` | The dataset after cleaning and encoding. |
| `eda_plots.png` | Visualizations of Loan Amount and Education. |
| `correlation_matrix.png` | Heatmap of feature relationships. |
| `confusion_matrix.png` | Model performance visualization. |
| `evaluation_report.txt` | Accuracy, Precision, and Recall scores. |

---

##  Results and Insights

### 🚀 Model Performance
The model was evaluated using a Confusion Matrix and Accuracy Score:
* **Final Accuracy:** [Yahan apni accuracy likhein, e.g. 81.30%]
* **Confusion Matrix:** Summary of Correct vs. Incorrect predictions.

![Confusion Matrix](outputs/confusion_matrix.png)

###  Key Insights
* **Credit History is King:** Applicants with a clean credit history (`Credit_History = 1`) have an overwhelmingly higher chance of approval.
* **Education Impact:** Graduates tend to apply for higher loan amounts and generally show a better repayment profile.
* **Income Stability:** While high income is a plus, it doesn't guarantee approval if the credit history is poor—making credit history the most vital feature.

---
**Prepared by:** Qazi Abubakar Siddiqui  
**Task:** Credit Risk Prediction (Machine Learning)
