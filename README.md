<!-- Using HTML to specify text size -->
<h1 style="font-size:20px;">🚀 Credit Card Transaction & Customer Analysis Using Power BI, SQL, and Excel 💳 </h1>


<h1 style="font-size:10px;">🔎 Project Overview</h1>
This project analyzes credit card usage patterns using Power BI, SQL, and Excel, with a focus on key customer metrics such as age, income, education level, and more. The objective is to uncover valuable insights that help businesses better understand their customers and make data-driven decisions.

<h1 style="font-size:10px;">🎯 Problem Statement</h1>
The company aimed to optimize its focus areas by gaining deeper insights into credit card usage trends across various customer segments. This analysis provides a data-driven approach that informs business decisions and identifies areas needing the most attention for improvement.

<h1 style="font-size:10px;">📊 Dashboard Features</h1>

1. Transaction Analysis
KPIs: Revenue, Interest, Transacted Amount, Count of Transactions
Filters: Card Type, Quarter, Age Groups, Gender
Slicer: Week numbers
2. Customer Analysis
KPIs: Revenue, Interest, Total Income, Customer Satisfaction Score (CSS)
Filters: Gender, Card Type, Quarter, Income Groups
Slicer: Week numbers

🔍 Data Sourcing from SQL
The dashboard uses SQL to seamlessly fetch data from the database. By leveraging SQL queries, the data is automatically updated in Power BI, ensuring the dashboard always reflects the most up-to-date information for timely and accurate decision-making.

💡 Data Processing with DAX
DAX (Data Analysis Expressions) is employed for robust data processing. New columns and calculations are added to track metrics and trends on a weekly basis. This enables a comprehensive view of credit card performance, offering actionable insights into customer behavior.

<h1 style="font-size:10px;">📊 Key Insights</h1>
Total Revenue Generated: $55M.<br>
Interest Earned: $8M.<br>
Total Transaction Amount: $46M.<br>
Revenue by Gender: Male customers contributed $31M; female customers brought in $26M.<br>
Income Group Insights: Males in low-income groups showed lower credit card usage, but usage significantly increased in higher-income groups.<br>
Top Credit Cards: Blue and Silver cards accounted for 93% of all transactions.<br>
Top Performing States: Texas, New York, and California contributed 68% of the total revenue.<br>
Card Activation Rate: 57.47%.<br>
Delinquency Rate: 6.07%.

<h1 style="font-size:10px;">📅 Weekly Metrics</h1>
Several key metrics are tracked weekly to give a granular understanding of performance over time:<br>
Week-over-Week Revenue (WoW)<br>
Customer Satisfaction Score<br>
Transaction Volume and Revenue Growth<br>

<h1 style="font-size:10px;">🎯 Conclusion</h1>
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
