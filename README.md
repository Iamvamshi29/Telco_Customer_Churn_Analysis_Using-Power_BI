# Telco Customer Churn Analysis Using Power BI

## 🎯 Project Overview  
This project performs a customer churn analysis for a telecom company using the publicly available “Telco Customer Churn” dataset and visualizes insights via a Power BI dashboard. The aim is to identify customer segments at high risk of churn and understand the key factors driving churn to support retention strategies.  

## 📁 Project Contents  
- `Telco_Customer_Churn.csv` — The raw dataset containing customer demographics, account information, service subscriptions, churn status, and other relevant attributes.  
- Power BI report file: `Intern.pbix` — The main Power BI file containing data modelling, measures, and dashboard visualizations.  
- Dashboard screenshot images: `Page 1.png`, `Page 2.png`, … `Page 8.png` — Preview pages of the Power BI report for quick overview without opening Power BI.
-

## 📊 Data Description  
The dataset includes several features per customer such as:  
- Demographics: gender, senior citizen status, dependent/partner status, etc.  
- Account details: tenure, contract type (month-to-month, etc.), payment method, monthly charges, total charges, paperless billing, etc.  
- Service subscriptions: phone, multiple lines, internet service type, online security/backup, device protection, tech support, streaming services, etc.  
- Churn label: whether the customer has churned (“Yes” / “No”).  

## 🧰 Data Preparation & Modeling (in Power BI)  
- Cleaned and transformed the data using Power Query: e.g. handled missing values, renamed columns, corrected data types, standardised categorical values (e.g. payment methods).  
- Created useful conditional/derived columns (e.g. customer tenure group, churn status label).  
- Built a star schema model where needed (if using multiple dimension tables or splitting data, depending on your approach).  
- Defined DAX measures for key metrics: total customers, number of churned customers, churn rate (%), revenue loss from churned customers, etc.  

## 📈 Dashboard & Insights  
The Power BI dashboard includes multiple report pages — covering:  
- **Overview / Summary**: high-level KPIs and overview of churn metrics.  
- **Customer Demographics Analysis**: churn distribution by gender, age (senior vs non-senior), dependents, partner status, etc.  
- **Account & Contract Analysis**: churn by tenure group, contract type, payment method, monthly charges, paperless billing, etc.  
- **Service & Subscription Analysis**: churn distribution across different service combinations (phone, internet type, streaming, add-on services), and assessment of which services correlate with higher churn.  

From the analysis you can derive actionable business insights — e.g. identifying segments with higher churn risk, services or contract types that may be contributing to churn, potential revenue impact, and recommendations for retention strategies.  

## ✅ Usage / How to Run / View the Dashboard  
1. Download or clone the repository.  
2. Open `Intern.pbix` using Microsoft Power BI Desktop.  
3. Load the data from `Telco_Customer_Churn.csv`.  
4. Use the report pages (or the provided screenshots) to explore insights.  
5. (Optional) Update data, adjust filters or DAX measures as needed for deeper/custom analysis.  

## ℹ️ Notes & Assumptions  
- The dataset is assumed to be clean enough for analysis; minimal missing data handling was applied.  
- Payment methods and categorical fields were standardized (e.g. “Electronic check” → “Electronic Check”, etc.) to ensure consistency.  
- Customer tenure groups / derived columns may be defined based on arbitrary thresholds — adjust as per business context.  

## 🔗 References  
- The “Telco Customer Churn” dataset (publicly available — often used in churn analysis tutorials).  
- Common industry practices for churn analysis: using demographic, contract, service usage data + churn label to identify churn drivers and compute churn rate & revenue impact.  

---

**Author:** (Iamvamshi29)   
Sademoni Vamshi
