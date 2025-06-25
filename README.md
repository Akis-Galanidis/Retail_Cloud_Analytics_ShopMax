# Retail Cloud Analytics – ShopMax Case Study

This repository presents a comprehensive analytics and infrastructure evaluation conducted for a fictional e-commerce company, ShopMax. The project assesses the suitability of AWS Redshift and Google BigQuery for migrating ShopMax’s on-premises retail data warehouse to the cloud.

## 📊 Objectives
- Evaluate Redshift vs. BigQuery on performance, elasticity, ease of use, and cost-efficiency
- Build a star-schema for retail data using sales, customer, and promotional data
- Conduct data cleaning, EDA, and sales pattern discovery
- Train and compare predictive models to forecast sales

## 🧠 Key Components
- 📑 **Report**: Business-focused evaluation and modeling results ([see PDF](./report/Big Data Platform Evaluation for a Retail Use Case.pdf))
- ⚙️ **Modeling**: Random Forest and Linear Regression models to predict retail sales
- 🧪 **Insights**: 
  - Region-wise performance
  - Product demand trends
  - Promotion effectiveness
- 📈 **Recommendations**:
  - Personalized campaigns
  - Real-time demand forecasting
  - Time-series and hybrid model enhancements

## 🛠️ Tools & Technologies
- R, Python (Scikit-learn, Pandas)
- AWS Redshift
- Google BigQuery
- Cloud Data Warehousing & Analytics Platforms

## 🔐 Dataset
Due to proprietary data constraints, datasets are not included. Please refer to the report for schema definitions and structure.

## 📌 Future Enhancements
- SHAP-based model interpretability
- AutoML pipelines for feature selection
- LSTM models for sequential demand forecasting
- Integration with BI tools (e.g., Power BI, Looker)
