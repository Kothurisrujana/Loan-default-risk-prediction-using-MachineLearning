# 💰 Loan Default Prediction — Machine Learning Project

## 🧩 Project Overview
This project predicts the likelihood of a loan **not being fully paid** based on a borrower's financial and credit information.  
Using machine learning techniques, the goal is to help financial institutions **identify high-risk applicants** and make smarter loan decisions.

---

## 🎯 Objective
To build a classification model that predicts whether a borrower will **fully repay the loan (0)** or **default on it (1)** using various financial features.

---

## 📊 Dataset Overview
Each row in the dataset represents a loan record.  
**Target Column:** `not.fully.paid`

**Features:**
| Feature | Description |
|----------|--------------|
| `int.rate` | Interest rate of the loan |
| `installment` | Monthly payment made by the borrower |
| `log.annual.inc` | Log-transformed annual income |
| `dti` | Debt-to-income ratio |
| `fico` | Borrower’s FICO credit score |
| `days.with.cr.line` | Number of days borrower had a credit line |
| `revol.bal` | Revolving balance |
| `revol.util` | Revolving utilization rate |
| `inq.last.6mths` | Credit inquiries in last 6 months |
| `delinq.2yrs` | Number of delinquencies in past 2 years |
| `pub.rec` | Number of public derogatory records |
| `purpose` | Purpose of the loan (categorical feature) |

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Encoded categorical feature `purpose`
   - Scaled numerical columns
   - Handled missing/outlier values

2. **Exploratory Data Analysis (EDA)**
   - Visualized correlations and feature distributions  
   - Analyzed how credit scores and interest rates impact loan repayment

3. **Model Building**
   - Split dataset into training and testing sets  
   - Applied multiple algorithms:
     - Logistic Regression  
     - Random Forest Classifier  
     - Gradient Boosting (XGBoost)

4. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Visualized confusion matrix and ROC curves

---

## 🧠 Key Insights
- Lower **FICO scores** and higher **interest rates** are strong indicators of default.  
- **Debt-to-income ratio** and **revolving utilization** impact repayment ability.  
- Ensemble models (Random Forest, Gradient Boosting) perform best overall.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Gradientboost 
- **Tools:** Google collab & streamlit
- **Version Control:** Git & GitHub  

---

## ✅ Results
- Achieved an accuracy of around **84%** using ensemble learning.  
- The model can be used to predict loan repayment outcomes effectively.

---

## 🚀 Future Improvements
- Include additional borrower data (employment, home ownership, etc.)  
- Handle class imbalance using SMOTE or other techniques  
- Deploy the model as a **Streamlit web app** for real-time prediction

---

👩‍💻 **Author:** [KOTHURI SRUJANA]  
📧 **Contact:** [kothurisrujana@gmail.com]  
⭐ *If you liked this project, don’t forget to star the repo!*
