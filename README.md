# Pizza-Sales-Analysis (SQL project)
## 📌 Project Overview

This project focuses on analyzing pizza sales data using SQL (MySQL) to uncover meaningful business insights.
In today’s competitive food industry, data-driven decisions are crucial for improving sales performance, understanding customer behavior, and maximizing revenue.

The analysis explores order trends, product performance, and revenue distribution to help businesses make strategic decisions.
##
🎯 Objectives
📊 Calculate total orders and revenue
🍕 Identify top-selling and highest-priced pizzas
📦 Analyze customer preferences by size and category
⏰ Discover time-based order patterns
💡 Generate actionable business insights
🗂️ Dataset Description

The dataset consists of the following tables:
##
Table Name	Description
orders	Order ID, date, and time
order_details	Quantity of pizzas ordered
pizzas	Pizza ID, size, and price
pizza_types	Name, category, ingredients
🛠️ Tools & Technologies
SQL (MySQL)
Database Management
Data Analysis Techniques
Joins, Aggregations, Window Functions
##
📈 Key Analysis Performed
🔹 Sales & Revenue Analysis
Total revenue calculation using SUM(quantity * price)
Revenue contribution by pizza type
🔹 Product Insights
Highest-priced pizza: The Greek Pizza
Top 5 most ordered pizzas:
Classic Deluxe Pizza
Barbecue Chicken Pizza
Hawaiian Pizza
Pepperoni Pizza
Thai Chicken Pizza
🔹 Category Analysis
Comparison of pizza categories (Classic, Chicken, Veggie, Supreme)
Category-wise quantity distribution
🔹 Time-Based Trends
Hourly order distribution
Daily order patterns using window functions
🔹 Advanced Analysis
Top 3 pizzas by revenue per category
Percentage contribution to total revenue
Cumulative revenue over time
##
📊 Key Insights
🍗 Chicken and Classic pizzas generate the highest revenue
🥦 Veggie pizzas lead in overall order quantity
⭐ A small group of pizzas contributes significantly to total sales
⏰ Peak ordering time is afternoon to evening
📈 Consistent daily order trends enable better forecasting
✅ Conclusion
##
This project demonstrates how SQL can transform raw data into actionable business insights.
By analyzing customer preferences, sales patterns, and revenue drivers, businesses can:

Improve menu strategy
Optimize pricing
Enhance customer satisfaction
Increase overall profitability
##
🚀 Future Improvements
Build an interactive dashboard using Power BI / Tableau
Implement predictive analysis for demand forecasting
Add customer segmentation analysis
📷 Project Preview


## 📁 Project Structure

```
Pizza-Sales-Analysis/
│
├── 📂 data/
│   ├── raw/
│   │   └── pizza_sales.csv
│   └── processed/
│       └── cleaned_pizza_sales.csv
│
├── 📂 sql/
│   ├── schema.sql
│   ├── data_import.sql
│   ├── analysis_queries.sql
│   └── advanced_queries.sql
│
├── 📂 docs/
│   ├── project_presentation.pptx
│   ├── dataset_description.md
│   └── data_dictionary.md
│
├── 📂 outputs/
│   ├── query_results/
│   │   ├── top_pizzas.csv
│   │   ├── revenue_analysis.csv
│   │   └── category_distribution.csv
│   └── screenshots/
│       ├── query_execution.png
│       └── results_preview.png
│
├── 📂 dashboard/   (optional)
│   ├── powerbi_dashboard.pbix
│   └── dashboard_screenshots.png
│
├── 📄 README.md
├── 📄 LICENSE
└── 📄 requirements.txt   (optional)
```

---

## 📌 Folder Explanation

* **data/** → Contains raw and cleaned datasets used for analysis
* **sql/** → All SQL scripts including schema creation and analysis queries
* **docs/** → Project documentation and presentation files
* **outputs/** → Results generated from SQL queries and screenshots
* **dashboard/** → (Optional) Power BI or Tableau dashboard files
* **README.md** → Project overview and documentation
* **LICENSE** → Open-source license (recommended: MIT)

---

## 💡 Best Practices

* Keep raw data untouched in `/data/raw`
* Store cleaned data separately in `/data/processed`
* Write modular SQL queries (basic → advanced)
* Add screenshots to improve project presentation
* Keep documentation clear and beginner-friendly

---

##
(Add screenshots of your SQL queries, outputs, or dashboard here)

👨‍💻 Author

Rahul Gore
📌 Data Analyst | SQL | Data Visualization  

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!
