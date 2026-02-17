Customer Shopping Behavior Analysis
Project Overview
This project analyzes retail customer shopping behavior using Python and MySQL to derive structured business insights from raw transactional data.
The workflow includes data cleaning, feature engineering, exploratory data analysis (EDA), and database integration for structured querying. The objective is to transform unstructured customer data into an analysis-ready dataset suitable for business decision-making.
Objectives
Perform data preprocessing and standardization
Convert column names to consistent snake_case format
Engineer analytical features (age segmentation, purchase frequency conversion)
Load processed dataset into MySQL
Execute SQL queries for structured analysis
Prepare dataset for downstream reporting and analytics use
Technology Stack
Python
pandas
numpy
sqlalchemy
pymysql
MySQL
Jupyter Notebook
Git & GitHub
Data Processing & Feature Engineering
Key transformations performed:
Standardized column naming convention (snake_case)
Created age_group using quantile-based segmentation
Converted categorical purchase frequency into numeric days (purchase_frequency_days)
Cleaned and structured dataset for relational database storage
Database Integration
The cleaned dataset was exported to MySQL using SQLAlchemy:
engine = create_engine("mysql+pymysql://<username>:<password>@localhost:3306/customer_behavior")
df.to_sql("customer", engine, if_exists="replace", index=False)
Sample SQL queries were written to validate data integrity and support business analysis.
Repository Structure
data_analytics_project/
│
├── data/
│   └── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── README.md
└── LICENSE
Key Outcomes
Prepared structured and analysis-ready customer dataset
Implemented feature engineering for behavioral segmentation
Integrated Python-based processing with SQL-based storage
Established reproducible data analytics workflow
Future Enhancements
Advanced visualization (Matplotlib / Seaborn)
Customer segmentation using clustering techniques
Dashboard integration (Power BI / Tableau)
Deployment using Streamlit
