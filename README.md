# Customer Shopping Behavior Analysis

##  Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 🛠️ Tech Stack
- **Data Cleaning & EDA:** Python (Pandas, NumPy)
- **Database & Analysis:** PostgreSQL (SQL)
- **Visualization:** Power BI
- **Version Control:** Git & GitHub

## 📊 Project Steps

### 1. Data Preparation (Python)
- Loaded and explored the dataset (3,900 rows, 18 columns).
- Handled missing data by imputing the median rating for the `Review Rating` column.
- Standardized columns to snake_case and performed data consistency checks (dropped redundant `promo_code_used`).
- Engineered new features: `age_group` and `purchase_frequency_days`.
- Loaded the cleaned data into PostgreSQL for advanced analysis.

### 2. Data Analysis (SQL)
Performed structured analysis in PostgreSQL to answer key business questions, including:
- Revenue comparison by Gender and Age Group.
- Identifying high-spending discount users and discount-dependent products.
- Customer segmentation (New, Returning, and Loyal).
- Analyzing the impact of subscriptions and shipping types on revenue.

### 3. Dashboard & Visualization (Power BI)
Built an interactive Power BI dashboard to present the insights visually, making it easy for stakeholders to track KPIs and customer behavior.

## 💡 Key Business Recommendations
Based on the data analysis, I recommend the following strategic actions:
1. **Boost Subscriptions:** Promote exclusive benefits to convert non-subscribers.
2. **Customer Loyalty Programs:** Reward repeat buyers to move them into the "Loyal" segment.
3. **Review Discount Policy:** Balance sales boosts with margin control for discount-dependent products.
4. **Product Positioning:** Highlight top-rated and best-selling products in marketing campaigns.
5. **Targeted Marketing:** Focus ad spend on high-revenue age groups and express-shipping users.

## 🚀 How to Run
1. Clone the repository.
2. Open `EDA_and_Data_Cleaning.ipynb` in Jupyter Notebook to view the Python data cleaning process.
3. Run the SQL queries in `business_analysis.sql` using your PostgreSQL database.
4. Open `powerbi_dashboard.pbix` in Power BI Desktop to explore the interactive dashboard.

##  Repository Structure
- `/data`: Raw CSV dataset.
- `/python_notebooks`: Python code for EDA and cleaning.
- `/sql_queries`: SQL scripts for business analysis.
- `/dashboard`: Power BI file and dashboard screenshots.

---
*Built by Thanu D L| (https://www.linkedin.com/in/thanudl/)*
