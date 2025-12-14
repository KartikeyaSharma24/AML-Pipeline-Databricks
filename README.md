# 🛡️ End-to-End Anti-Money Laundering (AML) Pipeline

## 📖 Overview
This project demonstrates a complete **Anti-Money Laundering (AML) pipeline** built on **Databricks Free Edition**, simulating real-world financial compliance workflows. It covers the full lifecycle of AML detection — from synthetic data generation to reporting dashboards — and balances **rule-based transparency** with **machine learning adaptability**.

---

## ⚙️ Key Features
- **Synthetic Data Generation**  
  Created realistic customer and transaction datasets with millions of records, including injected AML typologies (structuring, smurfing, layering).

- **Data Cleaning & Enrichment**  
  Standardized formats, removed duplicates, handled missing values, and joined customer attributes (risk level, KYC status, country) to transactions for compliance-ready inputs.

- **Feature Engineering**  
  Developed binary flags for AML patterns such as large transactions, high-risk countries, structuring, smurfing, and layering.

- **Rule-Based Detection**  
  Applied transparent compliance rules to flag suspicious activity with clear rationales.

- **Machine Learning (scikit-learn)**  
  Trained a Logistic Regression classifier on engineered features, achieving ~99% accuracy. Pivoted from Spark MLlib to scikit-learn due to Databricks Free Edition constraints.

- **Case Management**  
  Aggregated alerts into investigator-friendly cases, prioritizing high-risk customers/accounts.

- **Reporting Dashboards**  
  Built bar, pie, and time series charts to visualize suspicious activity concentration, typology distribution, and transaction trends.

---

## 📊 Reporting Visuals
- **Bar Chart:** Top 10 customers with suspicious activity.  
- **Pie Chart:** Distribution of AML typologies.  
- **Time Series Chart:** Daily suspicious transaction counts.  

These dashboards provide actionable insights for investigators and executives.

---

## 🏗️ Architecture Flow
```
Synthetic Data → Cleaning → Enrichment → Feature Engineering → Rules + ML → Case Management → Reporting
```

---

## 🚀 Business Impact
- Detects suspicious activity aligned with AML compliance requirements.  
- Provides transparency through rules and adaptability through ML.  
- Aggregates alerts into actionable cases for investigators.  
- Delivers dashboards and executive summaries for stakeholder communication.  

---

## 🔮 Future Improvements
- Integrate **Spark Structured Streaming** for real-time detection.  
- Add **explainability tools** (e.g., SHAP) for ML transparency.  
- Enhance case management with **network analysis** of linked accounts.  
- Connect to **BI tools** for live dashboards and reporting.  

---

## 📂 Repository Structure
```
├── notebooks/        # AML pipeline notebook
├── data/             # Synthetic datasets
├── docs/             # Architecture diagrams, documentation
├── assets/           # Dashboard screenshots
├── README.md         # Project overview
└── LICENSE           # Open-source license
```

---

## 📝 Executive Summary
This project showcases expertise in **big data engineering, compliance workflows, and applied machine learning**. It demonstrates how technical solutions can be translated into clear business insights, making it both technically robust and business-ready.
