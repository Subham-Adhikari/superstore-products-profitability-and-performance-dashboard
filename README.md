# 📊 Superstore Products Profitability & Performance Analysis
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Analysis](https://img.shields.io/badge/Type-Business%20Analytics-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 🎯 Project Overview
This project analyzes Superstore sales data spanning 2020-2023 to evaluate product profitability, customer segments, return behavior, and year-over-year performance. Using Power BI with custom date modeling and time intelligence DAX measures, the analysis uncovers growth drivers and loss-making areas for informed business decision-making.

---

## 📈 Key Metrics
| Metric | Value |
|--------|-------|
| **Total Sales** | $2.33M |
| **Total Profit** | $292.30K |
| **Overall Return Rate** | 5.79% |
| **YoY Return Improvement** | 2.95% |
| **Time Period** | 2020-2023 (4 years) |
| **Product Sub-Categories** | 17 |

---

## 🔍 Key Findings

### 💡 Customer Segment Concentration
> **Consumer segment contributes 50.21% of total sales ($1.17M)**

This highlights strong dependence on consumer customers, making them the primary revenue driver for the business.

### 📦 Product Profitability Contrast
> **Copiers generate $56K profit**, while **Tables incur an $18K loss**

Indicates uneven profitability across product categories and a clear opportunity for portfolio optimization.

### 📈 Sustained Business Growth
> **47% YoY sales growth and 48% YoY profit growth**

Time intelligence analysis confirms strong upward business momentum over the analyzed period.

### 🔄 Returns Performance Improvement
> **5.79% overall return rate** with **2.95% YoY improvement**

Reflects improving product quality, customer satisfaction, or operational processes.

---

## 💼 Business Recommendations
Based on the analysis, the following strategic actions are recommended:

1. **Optimize Product Portfolio**  
   Re-evaluate loss-making categories like Tables and strengthen investment in high-margin products such as Copiers

2. **Segment-Focused Strategy**  
   Develop retention and upselling strategies for the Consumer segment driving 50.21% of revenue

3. **Return Reduction Initiatives**  
   Analyze sub-categories and regions with higher return rates to further improve the 5.79% return metric

4. **Growth Monitoring with Time Intelligence**  
   Continue YoY tracking using time-based KPIs to sustain 47%+ sales growth momentum

---

## 🛠️ Technical Approach

### Power BI & DAX Techniques Used:
- **Custom Date Table**: Built dedicated calendar table with year, quarter, and month hierarchies for time intelligence
- **Time Intelligence Functions**: Used `SAMEPERIODLASTYEAR`, `CALCULATE` for YoY growth and variance calculations
- **Advanced DAX Measures**: Implemented `DISTINCTCOUNT` for return rate analysis and `DIVIDE` for safe percentage calculations
- **Interactive Dashboard Design**: Created 4 slicers (Date, Region, Segment, Customer) for multi-dimensional filtering
- **Drill-Down Analysis**: Enabled detailed exploration across 17 product sub-categories and geographic regions

---

## 📊 Data Model

### Tables:
**`Orders`** - Order-level transactional data
- `Row ID`, `Order ID`, `Order Date`, `Ship Date`
- `Ship Mode`, `Customer ID`, `Customer Name`
- `Segment`, `Country/Region`, `City`, `State/Province`, `Region`
- `Product ID`, `Category`, `Sub-Category`, `Product Name`
- `Sales`, `Quantity`, `Discount`, `Profit`

**`Returns`** - Order return details
- `Returned`, `Order ID`

**`date_table`** - Custom calendar dimension
- `Date`, `Year`, `Quarter`, `Month Number`, `Month Name`, `Start of Month`

---

## 📧 Contact
For questions or collaboration opportunities, feel free to reach out!
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/subhamad/)
- 📧 [Email](subhamadhikari348@gmail.com)

---

⭐ **If you found this project useful, please consider giving it a star!**
