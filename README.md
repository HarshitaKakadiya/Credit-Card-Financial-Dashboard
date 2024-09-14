<!-- Using HTML to specify text size -->
<h1 style="font-size:20px;">🚀 Credit Card Transaction & Customer Analysis Using Power BI, SQL, and Excel 💳  (Size 20)</h1>


🔎 Project Overview
This project analyzes credit card usage patterns using Power BI, SQL, and Excel, with a focus on key customer metrics such as age, income, education level, and more. The objective is to uncover valuable insights that help businesses better understand their customers and make data-driven decisions.

🎯 Problem Statement
The company aimed to optimize its focus areas by gaining deeper insights into credit card usage trends across various customer segments. This analysis provides a data-driven approach that informs business decisions and identifies areas needing the most attention for improvement.

📊 Dashboard Features
Transaction Analysis
KPIs: Revenue, Interest, Transacted Amount, Count of Transactions
Filters: Card Type, Quarter, Age Groups, Gender
Slicer: Week numbers
Customer Analysis
KPIs: Revenue, Interest, Total Income, Customer Satisfaction Score (CSS)
Filters: Gender, Card Type, Quarter, Income Groups
Slicer: Week numbers
🔍 Data Sourcing from SQL
The dashboard uses SQL to seamlessly fetch data from the database. By leveraging SQL queries, the data is automatically updated in Power BI, ensuring the dashboard always reflects the most up-to-date information for timely and accurate decision-making.

💡 Data Processing with DAX
DAX (Data Analysis Expressions) is employed for robust data processing. New columns and calculations are added to track metrics and trends on a weekly basis. This enables a comprehensive view of credit card performance, offering actionable insights into customer behavior.

📊 Key Insights
Total Revenue Generated: $55M
Interest Earned: $8M
Total Transaction Amount: $46M
Revenue by Gender: Male customers contributed $31M; female customers brought in $26M
Income Group Insights: Males in low-income groups showed lower credit card usage, but usage significantly increased in higher-income groups
Top Credit Cards: Blue and Silver cards accounted for 93% of all transactions
Top Performing States: Texas, New York, and California contributed 68% of the total revenue
Card Activation Rate: 57.47%
Delinquency Rate: 6.07%

📅 Weekly Metrics
Several key metrics are tracked weekly to give a granular understanding of performance over time:
Week-over-Week Revenue (WoW)
Customer Satisfaction Score
Transaction Volume and Revenue Growth

🎯 Conclusion
This credit card transaction and customer analysis revealed important trends in customer behavior, allowing for more targeted strategies to boost revenue and improve customer retention. By utilizing these data-driven insights, businesses can make more informed decisions to meet customer needs effectively.


Basics Way:

- data/
  - credit_card.csv
  - customer.csv
- sql_scripts/
  - create_tables.sql
  - data_insertion.sql
- power_bi_dashboard/
  - credit_card_dashboard.pbix
