# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes retail customer shopping behavior using **Python and MySQL** to derive structured business insights from transactional data.

The workflow includes:
- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory Data Analysis (EDA)  
- Database integration with MySQL  
- SQL-based querying for business insights  

---

## Objectives
- Transform raw customer data into an analysis-ready dataset  
- Standardize column names using snake_case convention  
- Engineer behavioral features (age segmentation, purchase frequency conversion)  
- Load processed data into MySQL  
- Execute SQL queries for structured business analysis  

---

## Technology Stack
- Python (Pandas, NumPy)
- MySQL
- SQLAlchemy
- Jupyter Notebook
- Git & GitHub

---

## Key Transformations
- Converted column names to snake_case
- Created `age_group` using quantile-based segmentation
- Converted categorical purchase frequency into numeric days (`purchase_frequency_days`)
- Cleaned and structured dataset for relational database storage
- Exported processed dataset to MySQL
- Wrote SQL queries for validation and analysis

---

## Repository Structure

```
data_analytics_project/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── README.md
└── LICENSE
```



---

## Key Outcomes
- Prepared structured and analysis-ready dataset  
- Implemented feature engineering for customer segmentation  
- Integrated Python-based processing with SQL-based storage  
- Established reproducible data analytics workflow  

---

## Future Enhancements
- Advanced visualizations (Matplotlib / Seaborn)
- Customer segmentation using clustering
- Dashboard integration (Power BI / Tableau)
- Deployment using Streamlit
