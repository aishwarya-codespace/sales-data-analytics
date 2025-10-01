# sales-data-analytics
Data analytics project on e-commerce sales dataset using Python.  Includes data cleaning, KPI generation, and visualizations

## Sales Analytics Dashboard (Python + Pandas + Matplotlib)
### Project Overview
This project analyzes retail sales data using Python, Pandas, and Matplotlib to extract key business insights.
The goal is to perform data cleaning, KPI generation, and visualization to understand customer buying behavior, sales trends, and revenue drivers.

### Objectives

- Clean and preprocess raw sales data.
- Create business KPIs (Key Performance Indicators).
- Generate insights about sales performance across products, time, and locations.
- Build visualizations to help decision-making.

### Dataset
- Order ID – Unique identifier for each order
- Product – Name of the product sold
- Quantity Ordered – Number of units sold
- Price Each – Price per unit
- Order Date – Timestamp of the order
- Purchase Address – Customer address

### Key KPIs
- Total Sales Revenue = Quantity × Price
- Total Orders = Unique Order IDs
- Total Quantity Sold = Sum of products sold
- Average Order Value (AOV) = Revenue ÷ Orders
- Top 5 Best-Selling Products (by quantity & revenue)
- Sales by Month (trend analysis)
- Peak Order Hours (time-based purchasing behavior)
- Sales by Weekday vs Weekend (buying patterns)

### Visualizations
The analysis includes:
- Bar Charts → Top products, sales by city, weekday vs weekend
- Line Charts → Monthly trend, hourly trend,sales by day of week
- Pie Charts → Weekday vs weekend distribution
- KPI Plots → Revenue, orders, AOV

### Requirements
- IDE: Visual Studio Code with the Jupyter extension
- Jupyter Notebook
- Python (Pandas, NumPy, Matplotlib, Seaborn)
#### Install all dependencies with:
pip install pandas numpy matplotlib seaborn


### Results & Insights
- Weekdays generated higher sales compared to weekends.
- Evening hours (7–8 PM) showed peak order activity.
- Sales peaked in May and August
