# 📊 Superstore Products Profitability & Performance Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Analysis](https://img.shields.io/badge/Type-Business%20Analytics-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 🎯 Project Overview

This project analyzes **Superstore sales data (2020–2023)** to evaluate **product profitability, customer segments, return behavior, and year-over-year performance**.  
Using **Power BI**, the analysis applies **custom date modeling, time intelligence DAX measures, and interactive dashboards** to uncover growth drivers and loss-making areas for informed business decision-making.

---

## 📈 Key Metrics

| Metric | Value |
|------|------|
| **Total Sales** | $2.33M |
| **Sales Growth (YoY)** | 47% |
| **Profit Growth (YoY)** | 48% |
| **Overall Return Rate** | 5.79% |
| **YoY Return Improvement** | 2.95% |
| **Time Period** | 2020–2023 |
| **Product Sub-Categories** | 17 |

---

## 🔍 Key Findings

### 💡 Segment Contribution
> **Consumer segment contributes 50.21% of total sales ($1.17M)**

This highlights strong dependence on consumer customers, making them the primary revenue driver for the business.

---

### 📦 Product Profitability Contrast
> **Copiers generate $56K profit**, while **Tables incur a $18K loss**

Indicates uneven profitability across product categories and a clear opportunity for **portfolio optimization**.

---

### 📈 Sustained Business Growth
> **47% YoY sales growth and 48% YoY profit growth in the most recent years**

Time intelligence analysis confirms strong upward business momentum over the analyzed period.

---

### 🔄 Returns Performance
> **5.79% overall return rate with 2.95% YoY improvement**

Reflects improving product quality, customer satisfaction, or operational processes.

---

## 💼 Business Recommendations

Based on the analysis, the following strategic actions are recommended:

1. **Optimize Product Portfolio**  
   Re-evaluate loss-making categories like Tables and strengthen investment in high-margin products such as Copiers

2. **Segment-Focused Strategy**  
   Develop retention and upselling strategies for the Consumer segment driving 62% of revenue

3. **Return Reduction Initiatives**  
   Analyze sub-categories and regions with higher return rates to further improve the 5.79% return metric

4. **Growth Monitoring with Time Intelligence**  
   Continue YoY tracking using time-based KPIs to sustain 47%+ sales growth momentum

---

## 🛠️ Technical Approach

### Power BI & DAX Techniques Used:

- **Custom Date Table**  
  Built a dedicated calendar table to enable advanced time intelligence analysis

- **Time Intelligence Functions**  
  Used `SAMEPERIODLASTYEAR`, YoY Growth, and variance calculations

- **Advanced DAX Measures**  
  - `DISTINCTCOUNT` for return rate analysis  
  - `DIVIDE` for safe percentage and ratio calculations

- **Interactive Dashboard Design**  
  Implemented **4 slicers**:
  - Date  
  - Region  
  - Segment  
  - Customer  

- **Drill-Down Analysis**  
  Enabled detailed exploration across **17 product sub-categories** and geographic regions

---

## 📊 Data Model

### Tables Used:

**`Fact_Sales`** – Transaction-level data  
- `order_number`, `order_date`, `shipping_date`, `due_date`  
- `sales_amount`, `quantity`, `price`  
- `customer_key`, `product_key`

**`Dim_Customers`** – Customer attributes  
- `customer_id`, `customer_number`  
- `segment`, `region`, `country`  

**`Dim_Products`** – Product hierarchy  
- `product_name`, `category`, `subcategory`  
- `cost`, `maintenance`

**`Dim_Date`** – Custom calendar table  
- Date attributes for year, quarter, month  
- Supports time intelligence calculations

---

## 📊 Dashboard Preview
_Add screenshots here to improve visual impact_
