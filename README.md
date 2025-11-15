# 📊 **Amazon Sales Data Analysis — Marketing Insights Project**
## 🔍 Overview

This project analyzes Amazon’s sales data from March to June 2022 to uncover the root causes behind a significant revenue decline after the April sales peak.
Using Exploratory Data Analysis (EDA) and business insight generation, this project identifies key product, region, and customer behavior drivers to support data-driven marketing and operational decisions.

## 🎯 Project Background

As one of the world’s largest e-commerce platforms, Amazon produces extensive sales data covering:

* Product performance

* Customer shopping behavior

* Shipping preferences

* Geographic distribution

Analyzing this data allows businesses to identify top-performing categories, understand shifts in demand, and design targeted marketing strategies to increase revenue.

## 🚨 Business Problem

Monthly sales trends show:

* Peak sales in April

* Significant drop in May and June

The decline may be influenced by:

* Reduced promotional effectiveness

* Shifts in consumer demand

* Changes in shopping behavior

* Region-specific purchasing power

To uncover the root cause, a deeper analysis is required across:

* Best-selling & profitable product categories

* Sales changes in specific time periods

* Customer purchase & shipping preferences

* Geographic sales patterns

## 📦 Dataset Information

Source: Kaggle — Amazon Sales Report
Period: March–June 2022
Size: 128,976 rows → cleaned to 124,634 rows
Features: 21 columns → 17 after preprocessing

Includes:
✔ Transaction details
✔ Product details
✔ Customer demographics
✔ Shipping information
✔ Logistics data

# 🛠️ Data Preprocessing

Key steps:

* Data type conversion (e.g., date to datetime)

* Handling duplicates (removed 1,507 duplicates)

* Handling missing values (drop >20% missing columns, fill with mode/median)

* Outlier treatment (trim extreme values for Amount)

## 📈 Data Analysis & Key Insights
### 1️⃣ Weak performance in core categories drives revenue decline

* T-shirts & Shirts are the highest contributors to total sales.

* Their sales dropped dramatically from April → June:

* T-shirt sales ↓ 44.75%

* T-shirt orders ↓ 33.15%

* Shirt orders ↓ 40%

* Shirt sales ↓ 17.83%

👉 These two categories are the primary root cause of the revenue dip.

### 2️⃣ Post-peak sales momentum fails to sustain

* April 13: highest daily sales (1.12M)

* After mid-April: consistent downward trend

* May 2: early spike but followed by another steady decline

* June: strong fluctuations, ending with sharp drops

👉 Issue is not constant low demand, but failure to maintain momentum after promotions.

### 3️⃣ Shipping & Fulfillment are NOT the cause

* No major changes in customer preferences

* Expedited and Amazon channels remained dominant

👉 Logistics do not explain the revenue decline.

### 4️⃣ Decline concentrated in the largest market: Bengaluru

* April: 2.5M

* May–June: stagnant at ~2.3M

👉 Bengaluru is the priority region for recovery.

### 5️⃣ City-level product preferences are dynamic

* Not the root cause of decline

* But provide actionable insight for targeted marketing

Examples:

* Mumbai: T-shirts popular early, then reversed in June

* Bengaluru & Hyderabad: Shirts dominate consistently

👉 Useful for city-specific marketing strategies.

## 🧩 Conclusion

* Root Cause: Decline in T-shirt & Shirt categories

* Timing: Clear post-peak effect

* Logistics Impact: None

* Geography: Decline centered in Bengaluru

* Customer Preference: Dynamic but not causal

## 🎯 Recommendations: Marketing Strategy
### 1️⃣ Revitalize Core Categories

* Highlight best-selling Shirt & T-shirt designs

* Launch post-peak flash sales

### 2️⃣ Post-Promotion Retention

* Personalized retargeting

* 14-day loyalty vouchers

* Encourage faster repeat purchases

### 3️⃣ Geographic Focus on Bengaluru

* Region-exclusive promotions

* Premium Shirt collections

### 4️⃣ City-Specific Targeting

* Mumbai & New Delhi → promote T-shirts

* Bengaluru & Hyderabad → strengthen Shirt promotions

### 5️⃣ Short-Term Offers to Accelerate Purchase Cycle

* Countdown deals

* Rotating weekly promos

## 📊 Dashboard

Dashboard built using Power BI to explore:

* Revenue trends

* Product category performance

* City-level insights

* Customer behavior

🔗 Interactive Streamlit Dashboard

If you'd like to explore the interactive version of the dashboard, you can access it here:
👉 https://amazon-sales-dashboard-2022.streamlit.app/
