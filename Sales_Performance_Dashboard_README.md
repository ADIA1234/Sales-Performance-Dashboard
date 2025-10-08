# 📊 Sales Performance Dashboard (Power BI)

## 🧠 Project Overview
An interactive Power BI dashboard built to analyze **sales performance**, **profit trends**, and **regional insights**.  
This dashboard helps business stakeholders track KPIs and identify growth opportunities using real-time visual analytics.

---

## 🛠️ Tech Stack
- **Power BI Desktop**
- **Excel / CSV Dataset**
- **Power Query (ETL)**
- **DAX (Data Analysis Expressions)**

---

## 📂 Folder Structure
```
Sales-Performance-Dashboard/
│
├── data/
│   └── superstore_sales.csv
│
├── reports/
│   └── Sales_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 📈 Key Features
✅ Created KPIs for **Total Sales**, **Profit Margin**, and **Customer Count**  
✅ Built **YoY Growth** & **Running Totals** using DAX  
✅ Added **interactive slicers** for Region, Category, and Month  
✅ Designed **Line & Clustered Column Chart** comparing this year vs last year  
✅ Optimized dashboard layout for professional presentation  

---

## 💡 Insights Discovered
- **West Region** contributed the highest sales in 2024  
- **Technology Category** showed the largest profit margin  
- Detected a **15% YoY growth** in total sales  

---

## ⚙️ Example DAX Measures
```DAX
Total Sales = SUM(Sales[Sales Amount])

YoY Growth % =
VAR CurrentYear = CALCULATE(SUM(Sales[Sales Amount]), YEAR(Sales[Order Date]) = 2024)
VAR PreviousYear = CALCULATE(SUM(Sales[Sales Amount]), YEAR(Sales[Order Date]) = 2023)
RETURN DIVIDE(CurrentYear - PreviousYear, PreviousYear, 0)
```

---

## 📸 Dashboard Preview
![Dashboard Preview](images/dashboard_preview.png)

---

## 🚀 Business Impact
This dashboard empowered stakeholders with data-driven insights, improving decision-making and helping identify top-performing regions & categories.

---

## 👤 Author
**Aditya Kumar**  
📍 Bengaluru, India  
📧 [adityaku1133@gmail.com](mailto:adityaku1133@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/adityakumar1109) | [GitHub](https://github.com/ADIA1234)
