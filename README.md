# 📊 Predict Loan Default — Machine Learning Project

## 📌 Project Overview
This project aims to predict whether a loan applicant is likely to default on a loan based on financial, demographic, and employment-related data. It uses machine learning techniques to classify loan applicants and visualize the model's performance through a confusion matrix heatmap and clustering graph.

---

## 🗂️ Dataset Description
The dataset contains information about loan applicants with the following key features:

- **LoanID**
- **Age**
- **Income**
- **LoanAmount**
- **CreditScore**
- **MonthsEmployed**
- **NumCreditLines**
- **InterestRate**
- **LoanTerm**
- **DTIRatio**
- **Education**
- **EmploymentType**
- **MaritalStatus**
- **HasMortgage**
- **HasDependents**
- **LoanPurpose**
- **HasCoSigner**
- **Default** *(Target: 0 = No, 1 = Yes)*

---

## 🛠️ Methodology

1. **Data Loading and Inspection:**  
   Loaded the CSV file using `pandas`, checked the structure, column names, and sample data.

2. **Data Cleaning:**  
   Handled missing or invalid values and encoded categorical variables where needed.

3. **Feature Scaling:**  
   Applied `StandardScaler` to normalize numeric features.

4. **Exploratory Data Analysis (EDA):**  
   Visualized distributions, class balance, and correlations between features.

5. **Model Training:**  
   Created random predictions for demonstration and evaluated using metrics.

6. **Evaluation:**  
   - Calculated **Accuracy** and **Precision**
   - Plotted a **Confusion Matrix Heatmap**
   - Created a **Clustering Graph** using `KMeans` clustering for applicants.

---

## 📈 Results

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures the correctness of positive predictions.
- **Confusion Matrix:** Visual representation of correct and incorrect classifications.
- **Clustering Graph:** Visual grouping of applicants based on income and loan amount.

---

## 📊 Technologies & Libraries Used

- Python 3
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📝 How to Run

1. Install the required libraries:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
