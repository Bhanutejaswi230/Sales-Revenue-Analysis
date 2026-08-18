# 📊 Sales & Revenue Analysis Dashboard

An interactive **Sales & Revenue Analysis Dashboard** developed using **Microsoft Power BI** to analyze sales performance, revenue trends, profitability, product performance, and regional sales.

The project transforms raw sales data into an interactive business intelligence dashboard that helps users understand key business performance indicators and make data-driven decisions.

---

## 📌 Project Overview

The **Sales & Revenue Analysis Dashboard** provides a centralized view of important sales metrics and business performance.

The dashboard allows users to:

* Track total revenue and profit
* Monitor orders and quantity sold
* Analyze profit margin
* Identify top-performing products
* Compare revenue across product categories
* Analyze regional sales performance
* Study monthly revenue trends
* Filter the analysis by category, region, customer segment, and date

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze overall sales and revenue performance
* Track important business KPIs
* Identify high-performing products and categories
* Compare sales performance across regions
* Analyze revenue trends over time
* Provide interactive filtering capabilities
* Generate meaningful business insights from sales data

---

## 📂 Dataset

The project uses a sales transaction dataset containing information about:

* Order ID
* Order Date
* Product
* Category
* Sub-Category
* Customer Segment
* Region
* City
* State
* Quantity
* Unit Price
* Revenue
* Cost
* Profit
* Discount
* Payment Mode
* Salesperson

---

## 🛠️ Tools & Technologies

| Tool                   | Purpose                          |
| ---------------------- | -------------------------------- |
| **Microsoft Power BI** | Dashboard and data visualization |
| **Power Query**        | Data cleaning and transformation |
| **DAX**                | Calculated measures and KPIs     |
| **Excel / CSV**        | Data source                      |

---

## 🔄 Project Workflow

The project followed these major steps:

### 1. Data Import

The sales dataset was imported into Microsoft Power BI.

### 2. Data Preparation

The data was checked and prepared for analysis by:

* Checking data types
* Preparing numerical fields
* Preparing categorical fields
* Structuring date information
* Creating a Date Table
* Establishing table relationships

### 3. DAX Measures

Important measures were created using DAX.

#### Total Revenue

```DAX
Total Revenue = SUM(Sales_Data[Revenue])
```

#### Total Profit

```DAX
Total Profit = SUM(Sales_Data[Profit])
```

#### Total Quantity

```DAX
Total Quantity = SUM(Sales_Data[Quantity])
```

#### Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Sales_Data[Order_ID])
```

#### Profit Margin

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)
```

### 4. Dashboard Development

Interactive visuals and KPI cards were created to present the analysis clearly.

---

## 📊 Dashboard Features

### KPI Cards

The dashboard tracks five important KPIs:

* **Total Revenue:** 38.11M
* **Total Profit:** 10.22M
* **Total Orders:** 600
* **Total Quantity:** 2K
* **Profit Margin:** 26.82%

### Monthly Revenue Trend

A line chart shows how revenue changes over time and helps identify periods of high and low sales performance.

### Revenue by Category

A bar chart compares revenue across different product categories.

**Electronics** is the leading category with approximately **28.4M** in revenue.

### Top 10 Products by Revenue

A Top N analysis identifies the products generating the highest revenue.

This can support:

* Inventory planning
* Product promotion
* Marketing decisions
* Sales strategy

### Revenue by Region

A donut chart compares revenue across regions.

Approximate revenue distribution:

| Region | Revenue |
| ------ | ------: |
| South  |   13.5M |
| West   |   9.12M |
| North  |   7.82M |
| East   |   7.68M |

---

## 🎛️ Interactive Features

The dashboard includes interactive slicers for:

* **Category**
* **Region**
* **Customer Segment**
* **Date Range**

Selecting a filter automatically updates the KPI cards and visualizations, allowing users to perform customized analysis.

---

## 💡 Key Business Insights

### 1. Electronics is the leading category

Electronics generates approximately **28.4M** in revenue and is the strongest revenue-generating category.

### 2. South is the leading region

The South region contributes approximately **13.5M** in revenue, making it the highest-performing region.

### 3. Overall revenue and profit

The business generates approximately:

* **38.11M Total Revenue**
* **10.22M Total Profit**

### 4. Profitability

The overall profit margin is approximately **26.82%**.

### 5. Revenue trends

Monthly revenue shows noticeable fluctuations, including a significant peak around **October 2025**.

### 6. Product performance

The Top 10 Products analysis highlights products that make the largest contribution to overall revenue.

---

## 📸 Dashboard Preview

Add your final Power BI dashboard screenshot here.

```text
![Sales & Revenue Analysis Dashboard](dashboard_screenshot.png)
```

---

## 📁 Project Structure

```text
Sales-Revenue-Analysis/
│
├── PowerBI/
│   └── Sales_Revenue_Dashboard.pbix
│
├── Documentation/
│   └── Sales_Revenue_Project_Report.pdf
│
├── Presentation/
│   └── Sales_Revenue_Analysis.pptx
│
├── Dashboard/
│   └── dashboard_screenshot.png
│
└── README.md
```

If you are not uploading the PDF report or PPT to GitHub, remove those folders from the structure.

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. If required, update the dataset source location.
4. Refresh the data.
5. Use the slicers to interact with the dashboard.
6. Explore revenue, profit, product, category, regional, and time-based analysis.

---

## 📈 Future Enhancements

The project can be extended with:

* Sales forecasting
* Year-over-year growth analysis
* Customer retention analysis
* Product-level profitability analysis
* Drill-through pages
* Geographic map analysis
* Automated data refresh
* Predictive analytics

---

## 🎓 Learning Outcomes

This project provided practical experience in:

* Data cleaning and preparation
* Power Query
* DAX
* Power BI visualization
* KPI development
* Interactive dashboard design
* Sales and revenue analysis
* Business insight generation
* Data-driven decision-making

---

## 🏁 Conclusion

The **Sales & Revenue Analysis Dashboard** demonstrates how raw sales data can be transformed into meaningful business insights using Power BI.

The dashboard combines KPI tracking, trend analysis, product analysis, category comparison, regional analysis, and interactive filtering in a single solution.

This project demonstrates practical skills in **Data Analytics, Business Intelligence, Power BI, Power Query, and DAX** and can be used as a portfolio project for data analytics and business intelligence opportunities.

---

## 👤 Author

**Garine Bhanu Tejaswi**

**Project:** Sales & Revenue Analysis Dashboard
**Domain:** Data Analytics / Business Intelligence
**Technology:** Microsoft Power BI

