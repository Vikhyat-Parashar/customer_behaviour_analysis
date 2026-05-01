📊 Customer Shopping Behavior Analysis (End-to-End Data Analytics Project)

🔍 Business Problem
A retail company wants to understand customer shopping behavior to improve:

Sales performance
Customer engagement
Long-term loyalty

Key question:
“How can customer data be used to identify trends, improve engagement, and optimize marketing strategies?”

📁 Dataset Overview
Total Records: 3,900 transactions
Columns: 18 features
Includes:
Customer demographics (Age, Gender, Location)
Purchase details (Category, Amount, Season)
Behavior data (Discounts, Frequency, Reviews, Shipping type)
Data Quality
37 missing values in review_rating column
Handled using median imputation (category-wise)
🛠️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn) → Data cleaning & EDA
SQL (MySQL/PostgreSQL) → Business analysis queries
Power BI → Interactive dashboard
Gamma → Report & presentation

⚙️ Project Workflow

1. Data Preparation (Python)
Loaded dataset using Pandas
Performed .info() and .describe() for structure & stats
Handled missing values using median imputation
Standardized column names (snake_case)
2. Created new features:
age_group (customer segmentation)
purchase_frequency_days
Removed redundant columns (promo_code_used)

3. Exploratory Data Analysis (EDA)
Analyzed:
Spending patterns across demographics
Seasonal trends
Product preferences
Created visualizations:
Distribution plots
Correlation heatmaps
Identified anomalies and key behavioral patterns

4. SQL-Based Business Analysis
Executed advanced SQL queries to answer real business questions:
Key Analyses:
Revenue by gender
High-spending discount users
Top-rated products
Shipping type vs spending
Subscription vs non-subscription revenue
Customer segmentation (New / Returning / Loyal)
Discount dependency by product
Revenue contribution by age group

5. Power BI Dashboard
Built an interactive dashboard with:
KPIs (Revenue, Avg Spend, Customer Segments)
Filters (Age group, Category, Subscription)
Visual insights for decision-making

6. Key Insights & Findings
Subscribers contribute higher total revenue and average spend
Discount usage does not always reduce spending — some users still spend above average
Loyal customers (repeat buyers) form a high-value segment
Certain products are highly dependent on discounts
Age group segmentation shows uneven revenue contribution

7. Business Recommendations
🎯 Promote subscription programs for higher revenue
🎯 Build loyalty programs for repeat customers
🎯 Optimize discount strategy to protect margins
🎯 Focus marketing on high-value age groups
🎯 Highlight top-rated & best-selling products

📈 Deliverables
📊 Power BI Dashboard
🧾 Analytical Report
📽️ Presentation (Gamma)
🗄️ SQL Query Scripts
🐍 Python Data Processing Scripts


