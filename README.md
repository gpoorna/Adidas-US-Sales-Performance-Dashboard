
# 📊 Adidas US Sales Performance Dashboard

## 📌 Project Overview

Developed an interactive Power BI dashboard to analyze Adidas US sales data and provide business insights into sales performance, profitability, product performance, regional performance, and sales methods.

The dashboard was designed by identifying business questions, selecting appropriate visualizations, and creating interactive reports to support business decision-making.

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## 📂 Dataset

The dataset contains sales information with the following fields:

- Invoice Date
- Region
- State
- City
- Product
- Retailer
- Sales Method
- Units Sold
- Price per Unit
- Total Sales
- Operating Profit
- Operating Margin

---

## 📈 Dashboard Highlights

- Sales and Profit KPI Cards
- Monthly Sales & Profit Trend Analysis
- Product-wise Sales Analysis
- Region-wise Performance Analysis
- Sales Method Comparison
- Interactive Slicers for dynamic filtering

---

## 📊 DAX Measures

### Profit Margin

```DAX
Profit Margin =
DIVIDE(
    SUM('Adidas_Sales_Cleaned'[Operating Profit]),
    SUM('Adidas_Sales_Cleaned'[Total Sales])
)
```

### Average Units Sold Per Day

```DAX
Average Units per Day =
DIVIDE(
    SUM('Adidas_Sales_Cleaned'[Units Sold]),
    DISTINCTCOUNT('Adidas_Sales_Cleaned'[Invoice Date])
)
```

---

## 💡 Key Skills Demonstrated

- Data Cleaning & Validation
- Data Visualization
- Dashboard Development
- DAX Measure Creation
- Business Analysis
- KPI Reporting
- Interactive Dashboard Design

---

## 📷 Dashboard Preview

> Add your dashboard screenshot here.

```markdown
![Dashboard](images/dashboard.png)
```

---

## 📁 Project Structure

```
Adidas-US-Sales-Dashboard/
│
│   └── Adidas_US_Sales_Dashboard.pbix
│
├── Dataset/
│   └── Adidas_US_Sales.xlsx
│
├── Images/
│   └── Dashboard.png
│
└── README.md
```

---

## 👨‍💻 Author

**G Poorna Chandra Rao**
