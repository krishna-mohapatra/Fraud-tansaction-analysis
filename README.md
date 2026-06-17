# Fraud-tansaction-analysis
This project focuses on analyzing credit card fraud transactions using Python, SQL, and Power BI. The objective was to identify fraud patterns, measure fraud exposure, analyze high-risk transactions, and provide actionable insights through an interactive dashboard.
<img width="1277" height="720" alt="Frd-1" src="https://github.com/user-attachments/assets/df517a0c-2873-4c5b-9af7-cda3c2036f81" />

# Tools & Technologies
- Python (Pandas, NumPy) 
- SQL Server 
- Power BI 
- Power Query
- DAX

# Project Workflow
## Data Collection
- Imported raw fraud transaction dataset.
- Reviewed data quality and structure.
## Data Cleaning & Transformation (Python)
- Removed duplicate records.
- Handled missing values.
- Standardized column names and formats.
- Corrected inconsistent categorical values.
- Converted data types for accurate analysis.
- Created derived fields for reporting.
## Data Loading (SQL Server)
- Exported cleaned dataset from Python.
- Loaded data into SQL Server.
- Validated record counts and data integrity.
- Created optimized tables for reporting.
## Data Modeling (Power BI)
- Connected Power BI to SQL Server.
- Built star-schema data model.
- Created relationships between tables.
- Developed DAX measures and KPIs.
## Dashboard Development
- Created an interactive multi-page dashboard.
- Added slicers for dynamic filtering.
- Implemented drill-down analysis.
- Designed risk classification and fraud monitoring visuals.

# Key KPIs
- Total Transactions -	1,000
- Total Fraud Transactions -	530
- Total Transaction Amount -	₹12M
- Fraud Amount -	₹7.27M
- Fraud Rate -	53%
- Average Risk Score -	62.66
 
# Dashboard
## Overview Dashboard

Provides a high-level summary of fraud activities.

<img width="1277" height="720" alt="Frd-1" src="https://github.com/user-attachments/assets/5f51a82b-d1f7-4843-9470-f5821e47fe83" />

## Risk Analysis Dashboard

Focuses on identifying fraud concentration across multiple dimensions.
<img width="1280" height="722" alt="Frd-2" src="https://github.com/user-attachments/assets/9d90cbcd-9581-4ae4-834e-c7a49a013c16" />

## Detailed transaction-level investigation dashboard.

<img width="1277" height="717" alt="Frd-3" src="https://github.com/user-attachments/assets/234edb8c-cad7-4bea-9e1c-e09de6b6bd77" />

# Key Insights
## Fraud Trends
- Fraud transactions account for 53% of all transactions.
- Fraudulent transaction value reached ₹7.27 Million.
- December recorded the highest fraud transaction volume.
- September showed the lowest fraud activity.
- Category Analysis
- Transportation and E-Commerce categories contributed the highest fraud share.
- Apparel and Food Delivery also exhibited significant fraud activity.
- Banking Analysis
- Yes Bank and Andhra Bank reported the highest fraud transaction percentages.
- Fraud distribution is relatively spread across banks, indicating systemic risk rather than a single-point concentration.
  
# Merchant Analysis
## Top merchants with high fraud occurrences:
- Zomato
- Lifestyle
- Reliance Digital
- Tata Cliq
- Uber

# State Analysis
## Highest fraud amounts observed in:

- Karnataka
- Uttar Pradesh
- Telangana
- Gujarat
- West Bengal

# Fraud Type Analysis
## Most common fraud categories:

- Identity Theft
- Account Takeover
- Card Not Present Fraud

⭐ Identity Theft contributed the largest share of fraud incidents.

#  Business Recommendations
- Implement enhanced monitoring for high-risk merchants.
- Introduce additional verification for high-risk transactions.
- Strengthen fraud controls in high-risk states.
- Apply stricter rules for Identity Theft and Account Takeover scenarios.
- Monitor transactions with risk scores above 70 in real time.
- Develop predictive fraud detection models for early intervention.

# Conclusion

- This project demonstrates an end-to-end Fraud Analytics solution using Python, SQL Server, and Power BI. By combining data cleaning, database management, risk scoring, and interactive visualizations, the dashboard helps identify fraud patterns, monitor risk exposure, and support data-driven fraud prevention strategies.

- The analysis revealed that Identity Theft, Transportation, E-Commerce transactions, and specific states contribute significantly to fraud exposure, highlighting areas where financial institutions can strengthen fraud detection and mitigation efforts.


# Contact
<p>
📧 Email: <a href="mailto:krishnamohapatra.cs@gmail.com">krishnamohapatra.cs@gmail.com</a><br/>
📞 Phone: +91-9828525337
</p>

<hr/>

<p align="center">
⭐ <i>Open to Data Analyst / Power BI Developer roles, freelance projects, and collaborations.</i>
</p>
















