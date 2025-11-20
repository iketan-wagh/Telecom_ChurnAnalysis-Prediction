# 📊 Telecom Customer Churn Analysis – End-to-End Project

A complete **ETL + Data Engineering + BI Analytics + Machine Learning** project designed for real-world enterprise churn analysis. This repository demonstrates how to ingest, cleanse, transform, visualize, and predict customer churn using SQL Server, Power BI, and Python (Random Forest).

---


## 🚀 Project Overview

<img width="1460" height="816" alt="Dashboard" src="https://github.com/user-attachments/assets/0e903b62-e8b5-4141-b451-1f775a47f506" />


<img width="1460" height="813" alt="Prediction" src="https://github.com/user-attachments/assets/c5dcd4c6-07e8-4bc3-a3e1-a2ec324888ce" />

Customer churn is one of the most critical KPIs in subscription-based industries. This project provides an end-to-end framework that:

* Builds a full **ETL pipeline in SQL Server**
* Creates interactive **Power BI dashboards**
* Trains a **machine learning model** to predict future churners
* Produces actionable insights for business teams to reduce churn

---

## 🧩 Problem Statement

Telecom companies face significant revenue loss due to high customer churn. There is a need for a **centralized analytical system** that can:

* Identify key churn drivers
* Understand demographic, geographic, and service-related patterns
* Predict customers likely to churn in the future
* Support targeted retention campaigns

This project solves this through a unified ETL + BI + ML solution.

---

## 🎯 Project Goals

1. **Analyze Customer Data** across:

   * Demographics
   * Geography
   * Payment & Account Info
   * Services
2. **Study churner profile** to identify marketing intervention areas
3. **Predict future churners** using a Random Forest model
4. **Build enterprise-grade dashboards** for decision-making

---

## 📐 Project Architecture

```
Source CSV → SQL Server Staging → Data Cleaning & Transformations → Production Tables → Views → Power BI → ML Model → Predictions → Final Dashboards
```

---

## 🛠 Tools & Technologies

### **Data Engineering**

* SQL Server
* SQL Server Management Studio (SSMS)
* SSIS (optional)

### **Business Intelligence**

* Power BI
* Power Query (M Language)
* DAX Calculations

### **Machine Learning**

* Python (Jupyter Notebook)
* scikit-learn
* Random Forest Classifier

## 🗄 ETL Framework

### **Primary Framework Used**

* Import data using SSMS Import Wizard
* Clean missing values using SQL
* Load into **prod_Churn** table
* Create analytical views: `vw_ChurnData`, `vw_JoinData`

### **Alternative (Enterprise) Framework**

* Automated SSIS packages for recurring loads

---

## 📊 Power BI Dashboards

### **Dashboard 1: Telecom Customer Churn Analysis**

<img width="1460" height="816" alt="Dashboard" src="https://github.com/user-attachments/assets/0e903b62-e8b5-4141-b451-1f775a47f506" />

Includes:

* KPIs (Total Customers, Total Churn, Churn Rate, New Joiners)
* Churn by Gender, Age, State
* Churn by Contract, Tenure, Payment Method
* Service Usage Analysis
* Churn Category & Reason Breakdown

### **Dashboard 2: Churn Prediction**
<img width="1460" height="813" alt="Prediction" src="https://github.com/user-attachments/assets/c5dcd4c6-07e8-4bc3-a3e1-a2ec324888ce" />
Includes:

* Predicted churner profile (Gender, Age, Tenure, State)
* List of customers at risk
* Churn counts by payment, contract, and referrals

---

## 🤖 Machine Learning – Random Forest

### **Model Steps**

* Data Preprocessing
* Label Encoding Categorical Columns
* Train-test split (80/20)
* Train RandomForestClassifier
* Evaluate using Classification Report & Confusion Matrix
* Feature Importance Visualization
* Predict on `vw_JoinData` customers

### **Output:**

```
Predicted_Churners.csv
```

---

## 📂 Important Queries & Scripts

Full scripts included in repository:

* SQL: Data cleaning, null checks, view creation
* Power Query: Age Groups, Tenure Groups, Unpivoting services
* DAX: KPI calculations
* Python: Random Forest Training & Prediction

---

## 🎨 Dashboard Theme Colors

* `#E63946` – Primary Red
* `#1A1A1A` – Black/Dark Gray
* `#F5F5F5` – Light Gray
* `#FFFFFF` – White

---

## 📝 How to Use This Project

1. Import CSV into SQL Server
2. Run SQL scripts to clean & transform data
3. Connect Power BI to SQL Views
4. Load Prediction CSV for second dashboard
5. Run Python scripts for ML model

---

## 📌 Future Enhancements

* Deploy automations using Azure Data Factory
* Deploy ML model as API using FastAPI
* Add real-time dashboards via Power BI Streaming
* Integrate with CRM systems for automated retention workflows

---

## 📧 Contact

If you want help implementing similar dashboards or projects:
**Ketan Wagh** – Data Analyst / BI Developer
📩 Email: [iketanwagh@gmail.com](mailto:iketanwagh@gmail.com)
💼 LinkedIn: [https://linkedin.com/in/ketan-wagh](https://linkedin.com/in/ketan-wagh)

---

⭐ *If you find this project useful, consider giving the repository a star!* ⭐
