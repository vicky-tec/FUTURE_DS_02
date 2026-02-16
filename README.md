# 📊 Telco Customer Churn Analysis  
### FUTURE_DS_02 – Data Science & Analytics Internship  
**Organization:** Future Interns  
**Intern:** Vicky Razz  

---

## 📘 Project Overview  

This project analyzes customer churn behavior in a subscription-based telecom company using the Telco Customer Churn dataset.

The objective of this analysis was to:

- Measure overall churn and retention performance  
- Identify key behavioral and contractual churn drivers  
- Perform tenure-based retention analysis  
- Estimate Customer Lifetime Value (CLV)  
- Develop a predictive model to estimate churn probability  

The project combines business analytics, retention strategy insights, and foundational machine learning.

---

## 📊 Dataset  

**Dataset:** WA_Fn-UseC_-Telco-Customer-Churn.csv  

The dataset includes:

- Customer demographics  
- Service subscriptions  
- Contract details  
- Monthly charges & total charges  
- Tenure  
- Churn status  

---

## 🎯 Key KPIs Analyzed  

- 📌 Churn Rate (~26%)  
- 📌 Retention Rate (~74%)  
- 📌 Average Monthly Charges  
- 📌 Average Customer Tenure  
- 📌 Customer Lifetime Value (CLV)  
- 📌 Churn by Contract Type  
- 📌 Churn by Tenure Group  

---

## 🔍 Key Insights  

### 1️⃣ Churn Rate  
The company experiences approximately **26% churn**, indicating a significant retention challenge.

---

### 2️⃣ Contract Type Impact  
- Month-to-month customers show the highest churn.  
- One-year and two-year contracts significantly reduce churn risk.  

**Insight:** Long-term contracts improve retention stability.

---

### 3️⃣ Tenure-Based Retention  
- Highest churn occurs within the first 12 months.  
- Retention stabilizes after 24 months.  

**Insight:** Early onboarding and engagement are critical.

---

### 4️⃣ Monthly Charges & Churn  
- Customers with higher monthly charges show increased churn probability.  
- Pricing sensitivity plays an important role in attrition.

---

### 5️⃣ Customer Lifetime Value (CLV)  

CLV was estimated using:


Retained customers generate significantly higher lifetime revenue compared to churned customers.

**Insight:** Improving early retention directly increases long-term profitability.

---

## 🤖 Predictive Modeling – Logistic Regression  

A Logistic Regression model was implemented to predict churn probability.

### Key Influential Features:
- Contract Type  
- Tenure  
- Monthly Charges  
- Internet Service  

The model enables proactive identification of high-risk customers and supports targeted retention strategies.

---

## 📈 Visual Analysis Performed  

- Churn distribution analysis  
- Contract vs churn comparison  
- Tenure group segmentation  
- Monthly charge distribution by churn  
- Correlation heatmap  
- Confusion matrix for model evaluation  
- CLV comparison (Churn vs Non-Churn)  

---

## 🛠 Tools & Technologies  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Repository Structure  

FUTURE_DS_02/
│
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│ └── FUTURE_DS_02.ipynb
│
├── report/
│ └── FUTURE_DS_02_Concise_Report.pdf
│
└── README.md


---

## 📌 Strategic Recommendations  

1. Promote long-term contracts through loyalty incentives.  
2. Improve onboarding during the first 12 months.  
3. Monitor high monthly charge customers for churn risk.  
4. Implement predictive churn monitoring.  

---

## 🏁 Conclusion  

This project demonstrates applied:

- Retention Analytics  
- Cohort-style Tenure Analysis  
- Customer Lifetime Value Estimation  
- Predictive Modeling  
- Insight-driven Decision Making  

The findings highlight clear opportunities to reduce churn and improve long-term revenue sustainability.
