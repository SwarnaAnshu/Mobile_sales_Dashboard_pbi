# 📱 Mobile Sales Analysis Dashboard | Power BI

<p align="center">
  <b>Interactive Business Intelligence Dashboard for Mobile Sales Analysis</b>
</p>

---

## 📊 Project Overview

The **Mobile Sales Analysis Dashboard** is an interactive **Power BI Business Intelligence project** developed to analyze mobile sales performance and generate actionable business insights.

The dashboard transforms raw transaction data into meaningful visualizations that help understand **revenue, quantity sold, brands, mobile models, cities, customer ratings, payment methods, and sales trends**.

### 🎯 Main Objective

To build an interactive dashboard that enables businesses to:

- Monitor overall sales performance
- Identify high-performing brands and mobile models
- Analyze city-wise sales
- Understand customer rating patterns
- Analyze payment preferences
- Track sales trends over time
- Compare current performance with previous periods

---




# 📌 Business Problem

Raw sales data contains thousands of transactions, making it difficult to identify important business trends.

This dashboard answers key questions such as:

| Business Question | Dashboard Analysis |
|---|---|
| 💰 How much are we selling? | Total Sales KPI |
| 📦 How many units are sold? | Total Quantity |
| 🧾 How many transactions occurred? | Transaction KPI |
| 🏷️ Which brand performs best? | Brand Analysis |
| 📱 Which models generate more revenue? | Mobile Model Analysis |
| 🌍 Which cities perform best? | City-wise Analysis |
| 💳 Which payment method is preferred? | Payment Analysis |
| ⭐ How are customers rating products? | Rating Analysis |
| 📅 How are sales changing over time? | Time Trend Analysis |
| 🔄 How does performance compare with last year? | Same Period Last Year |

---

# 📊 Key KPIs

| KPI | Value |
|---|---:|
| 💰 Total Sales | ~₹76.92 Cr |
| 📦 Total Quantity Sold | 19,150 |
| 🧾 Total Transactions | 3,835 |
| 💵 Average Price | ~₹40,114 |

These KPIs provide a quick overview of the overall business performance.

---

# 🔎 Key Business Insights

### 🏷️ Brand Performance

**Apple** generated the highest total sales among the major brands.

| Brand | Approx. Sales |
|---|---:|
| 🥇 Apple | ₹16.16 Cr |
| 🥈 Samsung | ₹16.00 Cr |
| 🥉 OnePlus | ₹15.37 Cr |
| Vivo | ₹15.01 Cr |
| Xiaomi | ₹14.38 Cr |

**Insight:** Apple has a slight lead over Samsung, indicating strong revenue contribution from the brand.

---

### 📱 Mobile Model Performance

**iPhone SE** was one of the top-performing mobile models by revenue, generating approximately **₹5.96 Cr**.

**Business Value:**
- Helps identify high-performing products
- Supports inventory planning
- Helps optimize promotions
- Supports product-level sales strategies

---

### 🌍 City-wise Sales

**Delhi** recorded the highest sales among the analyzed cities, generating approximately **₹20.39 Cr**.

**Business Value:**
- Identify strong markets
- Plan regional marketing
- Optimize inventory distribution
- Identify potential expansion opportunities

---

### 💳 Payment Method Analysis

| Payment Method | Transactions |
|---|---:|
| 🥇 UPI | 1,011 |
| Debit Card | 948 |
| Credit Card | 947 |
| Cash | 929 |

**Insight:** UPI is the most frequently used payment method, showing a strong preference for digital payments.

---

### ⭐ Customer Rating Analysis

| Rating | Transactions |
|---|---:|
| ⭐⭐⭐⭐⭐ 5 | 1,488 |
| ⭐⭐⭐⭐ 4 | 843 |
| ⭐⭐⭐ 3 | 652 |
| ⭐⭐ 2 | 543 |
| ⭐ 1 | 309 |

**Insight:** 5-star ratings represent the largest customer-rating category, indicating a strong concentration of highly rated transactions.

---

### 📅 Sales by Day

**Saturday** recorded the highest sales among the days analyzed, with approximately **₹11.44 Cr**.

**Business Value:**
- Helps plan weekend promotions
- Supports inventory planning
- Helps optimize staffing
- Identifies high-demand periods

---

# 📈 Time Intelligence Analysis

The dashboard includes dedicated time-based analysis using DAX.

## 📅 Month-to-Date (MTD)

MTD calculates sales from the beginning of the selected month up to the selected date.

```text
Beginning of Month
        ↓
   Daily Sales
        ↓
   Selected Date
        ↓
     MTD Sales
