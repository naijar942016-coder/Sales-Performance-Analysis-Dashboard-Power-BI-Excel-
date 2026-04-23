# Sales-Performance-Analysis-Dashboard-Power-BI-Excel-
Developed an interactive sales dashboard using Power BI, Excel, and DAX to analyze revenue, order patterns, and key performance indicators. Implemented DAX measures for advanced calculations and built dynamic visualizations to deliver meaningful business insights.
# 📊 End-to-End Sales Analytics Dashboard (Power BI + Excel + DAX)

## 📌 Project Overview

This project presents an interactive **Sales Analytics Dashboard** built using Power BI, with Excel datasets as the data source. It focuses on analyzing sales performance, order trends, and business KPIs using powerful data visualization and DAX calculations.

---

## 🎯 Objectives

* Analyze overall sales performance
* Track order trends and patterns
* Measure key business KPIs
* Create interactive and dynamic dashboards
* Use DAX for advanced calculations

---

## 🛠️ Tools & Technologies

* Power BI
* Microsoft Excel
* DAX (Data Analysis Expressions)

---

## 🗂️ Dataset Description

The project uses Excel files containing:

### 1️⃣ Sales Data

* Revenue
* Product details
* Sales amount

### 2️⃣ Orders Data

* Order ID
* Order date
* Customer information

### 3️⃣ Order Details

* Quantity
* Product mapping
* Transaction-level details

---

## 🔧 Data Preparation

* Cleaned and transformed data in Power Query
* Handled missing values
* Removed duplicates
* Established relationships between tables

---

## 📊 Key KPIs (Using DAX)

* Total Sales
* Total Orders
* Total Quantity Sold
* Average Order Value
* Revenue Trends

---

## 🧮 Sample DAX Measures

```DAX
Total Sales = SUM(Sales[Amount])

Total Orders = COUNT(Orders[Order ID])

Total Quantity = SUM(OrderDetails[Quantity])

Average Order Value = DIVIDE([Total Sales], [Total Orders])
```

---

## 📈 Dashboard Features

* Interactive filters and slicers
* Sales trends over time
* Category-wise performance
* Top-performing products
* Region/customer insights

---

## 📊 Key Insights

* Identified top-selling products and categories
* Observed sales trends across different time periods
* Found high-value customers and order patterns
* Highlighted areas with low performance

---

## 💡 Business Recommendations

* Focus on high-performing products
* Improve marketing for low-performing areas
* Use data-driven pricing strategies
* Target repeat customers with offers

---

## 🚀 How to Use the Project

1. Download the Excel dataset
2. Open Power BI Desktop
3. Load the dataset
4. Apply data transformations
5. Use DAX measures
6. Explore the dashboard

---

## 📂 Project Structure

```
PowerBI-Sales-Analytics/
│
├── dataset/
├── dashboard.pbix
├── README.md
└── screenshots/
```

---

## 🌟 Future Enhancements

* Add more advanced DAX measures
* Integrate real-time data sources
* Enhance dashboard UI/UX
* Add forecasting analysis

---

## 🙌 Conclusion

This project demonstrates the ability to transform raw data into meaningful insights using Power BI and DAX. It showcases practical skills in data analysis, visualization, and business intelligence.

---

## 📬 Contact

Feel free to reach out for feedback or collaboration!
