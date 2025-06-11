

📊 Vendor Performance Analysis Project

A comprehensive data analysis project to evaluate and interpret vendor performance using SQL, Python, and Power BI.

📌 About the Project
The Vendor Performance Analysis project aims to solve a business problem by analyzing vendor sales and purchase data. The goal is to uncover meaningful insights about vendor profitability, stock turnover, and sales trends by working with multiple database tables, performing data cleaning, aggregation, statistical testing, and visualization.

❓ Research Questions Answered
1.As part of the analysis, I focused on solving critical business problems to drive actionable insights:
2.Which brands are underperforming and may require promotional or pricing adjustments?
3.Which vendors contribute the most to overall sales and gross profit?
4.What is the impact of bulk purchasing on unit costs and profitability?
5.How can inventory turnover be improved to reduce data hoarding costs and increase efficiency?
6.What is the profitability variance between high-performing and low-performing vendors?

💼 Key Business Insights
Based on the research questions above, I derived the following data-backed insights:

🔻 Underperforming brands with low profit margins and high inventory were flagged for pricing revisions and promotional strategies.

🥇 Identified top vendors contributing the highest to gross profit and sales volume, useful for strengthening partnerships.

📦 Bulk purchasing patterns were linked to lower unit costs, but not always higher profit—highlighting the need for smarter procurement strategies.

🔄 Vendors with low inventory turnover were identified, helping reduce storage costs and improve operational efficiency.

📊 Found significant profitability gaps between vendors using statistical testing (t-tests), supporting data-driven vendor management decisions.



🛠️ Tools & Technologies
 Tools & Technologies
1.SQL – Data cleaning and table aggregation
2.Python (Jupyter Notebook) – Data loading, EDA, and statistical analysis
3.Pandas, NumPy, Matplotlib, Seaborn – Analysis and visualization
4.Scipy.stats – T-tests and Hypothesis Testing to validate findings
5.Python Logging – Used to track data flow and debug issues during processing
6.Power BI – Interactive dashboards with DAX queries to calculate custom KPIs and metrics
7.SQLite – Relational data storage

🗃️Dataset & Tables Used
The data consists of the following interrelated tables:
1.begin_inventory
2.end_inventory
3.purchase_price
4.purchases
5.sales
6.vendor_invoice
7.Vendor_sale_summary – Final Aggregated Table

📊 Final Aggregated Table (Vendor_sale_summary) Columns:
1.VendorNumber
2.VendorName
3.Brand
4.Description
5.PurchasePrice, ActualPrice
6.Volume, TotalPurchaseQuantity, TotalPurchaseDollars
7.TotalSalesQuantity, TotalSalesDollars, TotalSalesPrice
8.TotalExciseTax, FreightCost
9.GrossProfit, ProfitMargin
10.StockTurnover, SalesPurchaseRatio

📈 Project Workflow
1.Understand the Business Problem
2.Explore and Clean Raw Data
-Loaded tables into SQLite
-Cleaned data using SQL queries in Python (Jupyter Notebook)
3.Aggregate Data
-Created a final summarized table Vendor_sale_summary
-Stored in SQLite for further analysis
4.Load Aggregated Table in Python for EDA
-Conducted Exploratory Data Analysis
-Solved key research questions and interpreted findings
5.Visualized Insights
-Built a Power BI dashboard using the final aggregated table with DAX queries to calculate custom KPIs and metrics for better interpretation and reporting

👩‍💻 Author
Mahak Bisht
Aspiring Business Analyst Analyst | Skilled in Python, SQL, and Power BI



