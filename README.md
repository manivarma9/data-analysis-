🛒 Superstore Sales Analysis
📌 Project Summary
This is a Data Analysis project based on a Superstore sales dataset. The goal is to uncover meaningful business insights by analyzing sales performance, discount effects, regional trends, and product-level profit variations.

🎯 Objectives
Analyze sales and profit patterns

Understand impact of discount on profit

Visualize top/bottom performing categories

Provide suggestions for business optimization

🧰 Tech Stack
Python

Libraries: pandas, numpy, matplotlib, seaborn

Tools: Jupyter Notebook / VS Code

📂 Dataset Overview
Column	Description
Ship Mode	Delivery method (e.g., Standard, Second Class)
Segment	Customer segment (Consumer, Corporate, etc.)
Country, City	Location of customer
State, Region	Area of operation
Category, Sub-Category	Product details
Sales	Revenue from sale
Quantity	Items sold
Discount	Discount percentage applied
Profit	Profit or loss made from sale

📊 Sample Data Preview
Ship Mode	Segment	City	Category	Sub-Category	Sales	Discount	Profit
Second Class	Consumer	Henderson	Furniture	Bookcases	261.96	0	41.91
Standard Class	Consumer	Los Angeles	Technology	Phones	911.42	0.2	68.35
Standard Class	Consumer	Fort Worth	Office Supplies	Appliances	68.81	0.8	-123.85

📈 Visualizations
📷 Screenshots of your plots (example layout):

🔹 1. Category vs Profit (Bar Chart)

🔹 2. Discount vs Profit (Scatter Plot)

🔹 3. Sales by Region (Bar Chart)

🔹 4. Top 10 Sub-Categories by Sales

🔹 5. Correlation Heatmap

✅ Tip: Create an /images folder in your project and save screenshots from your analysis notebook with these names to match the markdown.

🚀 How to Run
Clone or download the repository

Open superstore_sales_analysis.ipynb or .py file

Install requirements:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Load the dataset and run all cells

✅ Key Insights
Some Furniture items like Tables caused major losses due to high discounts.

Phones and Binders are high-profit products.

West Region had the most sales, but discount strategy needs optimization.

High discounts (e.g., 0.8) usually result in losses.

🙋 What I Learned
Cleaned and explored real-world retail data

Visualized and interpreted business KPIs

Understood the effect of discounts on profitability

Improved decision-making skills using data analysis
