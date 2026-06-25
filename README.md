# Sales-Dashboard-mob
An interactive Power BI Sales Dashboard that analyzes Samsung sales performance using dynamic KPIs, revenue trends, category analysis, regional insights, and interactive filters to support data-driven business decisions.
# 📊 Samsung Sales Dashboard - Power BI

## 📌 Project Overview

The **Samsung Sales Dashboard** is an interactive Business Intelligence dashboard developed using **Microsoft Power BI** to analyze Samsung product sales across different regions, categories, and years. The dashboard provides real-time insights into revenue, sales trends, product performance, and regional distribution, enabling better business decision-making.

This project demonstrates skills in **Data Visualization, Data Modeling, Power Query, DAX, and Business Intelligence Reporting**.

---

## 🚀 Features

- 📈 Interactive KPI Cards
  - Total Revenue
  - Units Sold
  - Maximum Sales
  - Minimum Sales
  - Average Revenue
  - Previous Year Sales

- 📊 Revenue Analysis by Category

- 🌍 Revenue Analysis by Region

- 📅 Year-wise Sales Trend Analysis

- 📋 Detailed Sales Report Table

- 🎯 Interactive Filters (Slicers)
  - Year
  - Product Category
  - Region

- ⚡ Dynamic Dashboard with Cross Filtering

---

## 🖼 Dashboard Preview

> *(Upload your dashboard screenshot in the repository and replace the file name below.)*

```markdown
![Samsung Sales Dashboard](Dashboard.png)
```

---

## 📌 Dashboard Insights

The dashboard helps answer important business questions such as:

- Which product category generates the highest revenue?
- Which region contributes the most sales?
- How have sales changed over different years?
- What are the highest and lowest sales values?
- How many units have been sold?
- What is the average revenue generated?
- Compare current sales with previous year performance.

---

## 📂 Dashboard Components

### KPI Cards

- Total Revenue
- Units Sold
- Maximum Sales
- Minimum Sales
- Average Revenue
- Previous Year Sales

### Visualizations

- Revenue by Category (Bar Chart)
- Revenue by Region (Donut Chart)
- Year Sales Trends (Line Chart)
- Sales Details (Table)

### Interactive Slicers

- Year
- Category
- Region

---

## 🛠 Tools & Technologies Used

| Technology | Purpose |
|------------|----------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Calculated Columns & Measures |
| Data Modeling | Relationship Building |
| Excel / CSV Dataset | Data Source |

---

## 📊 Key Performance Indicators (KPIs)

- 💰 Total Revenue
- 📦 Total Units Sold
- 📈 Maximum Sales
- 📉 Minimum Sales
- 📊 Average Revenue
- 📅 Previous Year Sales

---

## 📈 Business Insights

- Identifies top-performing product categories.
- Tracks yearly revenue growth.
- Compares regional sales performance.
- Monitors sales trends over time.
- Supports data-driven business decisions.
- Provides interactive filtering for customized analysis.

---

## 📁 Project Structure

```
Samsung-Sales-Dashboard/
│
├── Samsung Sales Dashboard.pbix
├── Dataset.xlsx
├── Dashboard.png
├── README.md
└── Screenshots/
    ├── Dashboard1.png
    ├── Dashboard2.png
```

---

## ⚙️ Power BI Features Used

- Power Query Editor
- Data Modeling
- Relationships
- DAX Measures
- Cards
- Bar Chart
- Line Chart
- Donut Chart
- Table Visual
- Slicers
- Conditional Formatting
- Interactive Filtering

---

## 📌 DAX Measures Used

Examples include:

```DAX
Total Revenue = SUM(Sales[Revenue])

Total Units Sold = SUM(Sales[Units])

Average Revenue = AVERAGE(Sales[Revenue])

Maximum Sales = MAX(Sales[Revenue])

Minimum Sales = MIN(Sales[Revenue])

Previous Year Sales =
CALCULATE(
    SUM(Sales[Revenue]),
    SAMEPERIODLASTYEAR(Calendar[Date])
)
```

---

## 🎯 Skills Demonstrated

- Business Intelligence
- Power BI Dashboard Development
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Data Visualization
- KPI Design
- Interactive Reports
- Business Analytics

---

## 📊 Dashboard Workflow

```
Raw Dataset
      │
      ▼
Power Query
(Data Cleaning)
      │
      ▼
Data Modeling
(Relationships)
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
```

---

## 🎯 Project Objectives

- Analyze Samsung sales performance.
- Monitor revenue and quantity sold.
- Compare yearly sales trends.
- Identify high-performing categories.
- Analyze regional sales contribution.
- Enable interactive business reporting.

---

## 📸 Dashboard Screenshot

*(Replace with your uploaded dashboard image.)*

```markdown
![Dashboard](Dashboard.png)
```

---

## ⭐ Future Enhancements

- Profit Analysis
- Customer Segmentation
- Forecasting
- Sales Prediction
- Drill-through Reports
- Mobile Dashboard Layout
- Dynamic Tooltips
- Geographic Map Visuals

---

## 👩‍💻 Author

**Suganthi Johnmark**

- Data Analyst
- Power BI Developer
- AI & Data Science Student

---

## 📜 License

This project is created for educational and portfolio purposes.

---

## ⭐ If you found this project useful, don't forget to Star ⭐ the repository.
