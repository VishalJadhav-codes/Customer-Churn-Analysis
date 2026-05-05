# 📊 Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer churn behavior using the IBM Telco dataset to identify key factors influencing customer retention. The goal is to uncover actionable insights that help businesses reduce churn and improve customer lifetime value.

---

## 🎯 Objective
- Understand patterns and drivers behind customer churn  
- Perform data cleaning, transformation, and feature engineering  
- Conduct exploratory data analysis (EDA) using visualizations  
- Generate business insights and recommend retention strategies  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 Dataset
- IBM Telco Customer Churn Dataset  
- Contains customer demographics, services, billing details, and churn status  

---

## 🔧 Data Processing
- Handled missing values and corrected data types (e.g., Total Charges)
- Performed feature engineering:
  - Created **tenure bands** for lifecycle segmentation  
  - Created **charge bands** using quantiles  
  - Grouped contract types into meaningful categories  
- Removed irrelevant columns for analysis  

---

## 📊 Exploratory Data Analysis (EDA)

Key visualizations performed:
- Churn distribution analysis  
- Churn by contract type  
- Tenure vs churn (boxplot)  
- Monthly charges vs churn  
- Internet service & payment method analysis  
- Correlation heatmap for numeric features  

---

## 🔍 Key Insights

- Customers on **month-to-month contracts show the highest churn (~43%)**, indicating lack of long-term commitment.  
- **New customers (0–1 year) exhibit the highest churn (~48%)**, showing that churn is concentrated in early lifecycle stages.  
- Approximately **27% of churned users are early-stage (<3 months) month-to-month customers**, highlighting onboarding gaps.  
- **Higher monthly charges increase churn probability**, though impact is moderate compared to contract and tenure.  
- Customers using **electronic check show significantly higher churn (~45%)**, indicating payment-related friction.  
- **Contract type is the strongest churn driver**, with short-term users showing significantly higher churn than long-term users.  

---

## 🚀 Business Recommendations

- Implement **early engagement strategies** during the first 90 days  
- Encourage migration to **long-term contracts** through incentives  
- Improve **value proposition for high-paying customers**  
- Promote **automatic payment methods** to reduce churn risk  
- Use churn indicators to design **targeted retention campaigns**  

---

## 📈 Project Outcome
This analysis provides a clear understanding of churn behavior and highlights key areas where businesses can intervene to improve retention and revenue.

---

## 📁 Project Structure
Customer-Churn-Analysis/
│
├── Notebooks/
│ └── Churn_Analysis.ipynb
│
├── Data/
│ └── Telco_customer_churn.xlsx
│
├── README.md

---

## 🙋‍♂️ Author
**Vishal Jadhav**

---

## ⭐ If you found this project useful, consider giving it a star!
