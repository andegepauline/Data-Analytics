#  🛒 Retail Sales Performance Dashboard – Power BI Project 📊

## Project Overview 🎯

This is a Power BI project I created to analyze sales performance for a retail company.  
The goal was to understand:

- 🏷️ Which products and categories sell the most  
- 🌎 Which regions are performing well  
- 💸 How discounts affect profit  
- 📈 Sales trends over time  
- 🧑‍💼 Top-performing sales reps  

The dashboard helps the manager make better business decisions based on sales data.

---

##  📂 Dataset

The project uses a dataset with 5 tables:

- **Sales** – contains all orders, revenue, profit, discounts, and quantities  
- **Products** – product details like category, sub-category, and cost price  
- **Customers** – customer information, region, and segment  
- **Stores** – store details and location  
- **Sales_Reps** – sales representatives and their regions  

---

## Data Cleaning & Modeling 🧹💻

I cleaned the data using Power Query by:

- Removing duplicates  
- Fixing missing values  
- Standardizing categories and names  
- Converting dates and percentages to the right formats  

For data modeling, I created relationships between the fact table (`Sales`) and dimension tables (`Products`, `Customers`, `Stores`, `Sales_Reps`) so I could analyze sales by any attribute.

---

## Measures & Calculated Columns

**Calculated columns I added:**

- Order year and month (to analyze trends)  
- Shipping days (to track delivery performance)  
- Profit margin per order  

**Measures I created using DAX:**

- Total Sales, Total Profit, Total Orders  
- Average Discount  
- Profit Margin %

These measures are used in the dashboard visuals.

---

## 🖼️ Dashboard Visuals

- **KPI Cards** – Revenue, Profit, Orders, Profit Margin  
- **Line Chart** – Monthly Sales Trend  
- **Bar Chart** – Sales by Category  
- **Table** – Top Products   
- **Bar Chart** – Sales by Sales Representative  
- **Scatter Chart** – Discount vs Profit  
- **Slicers** – Filter by Region, Category, Year  

The dashboard is interactive and lets the user explore data by region, product, or time period.

---

## 💡 Key Insights

- Electronics is the top-selling category  
- West region has the highest sales; South is underperforming  
- Discounts above 15% reduce profit  
- A few top sales reps drive most of the revenue  
- Sales peak during November–December  

---

## ✅ Recommendations

- Reduce very high discounts on popular products  
- Focus marketing efforts on low-performing regions  
- Reward top-performing sales reps  
- Prepare inventory for holiday season based on sales trends  

---

## How to Use

1. Open `UrbanCart_Retail_Sales_Performance.pbix` in Power BI Desktop  
2. Explore the dashboard using slicers for Region, Category, or Year  
3. Review KPIs, trends, and visual insights  

---

## 📁Files

- `UrbanCart_Retail_Sales_Performance.pbix` – Power BI report  
- `UrbanCart_PowerBI_rawdata.xlsx` – Dataset  

---

## Skills Practiced 🛠️

- 🧹 Data cleaning and transformation (Power Query)  
- 🔗 Data modeling and relationships  
- 🧮 DAX calculations (measures & columns)  
- 📊 Creating interactive dashboards  
- 💡 Data analysis and insight generation   

---

## 🔗 Author
Pauline Andege Omondi  
Data Analyst | Excel | SQL | Data Cleaning | Business Analysis

- 🔗 LinkedIn: https://www.linkedin.com/in/pauline-andege-/  
- ✍🏽 Medium: https://medium.com/@paulineandege  
- 💼 Portfolio Website: https://andegepauline.github.io/portfolio