# Walmart-Sales-Project-
 In this project, you will clean a dataset containing Walmart sales data and analyze  sales, unemployment rate, CPI, fuel price, and other fields.
#  Walmart Sales Data Analysis Project

##  Overview
This project involves cleaning and analyzing Walmart’s weekly sales dataset using Python. The goal is to uncover insights related to holiday effects, unemployment, CPI, and fuel price relationships with sales. It’s a medium-level project focused on business understanding and data storytelling.

---

##  Dataset Source
- **Kaggle:** [Walmart Sales Data](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)
---

##  Data Cleaning Tasks
Data was cleaned using **Pandas** in Python and included the following steps:

- Sorted data by `Store` (ascending) and then `Date` (ascending)
- Converted `Date` to format: **MM-DD-YYYY**
- Rounded key columns:
  - `Weekly_Sales` to 2 decimal places
  - `Temperature` to nearest whole number
  - `Fuel_Price` to 2 decimal places
  - `CPI` to 3 decimal places
  - `Unemployment` to 3 decimal places
- Removed rows with missing values

##  Business Questions Answered with Insights

### 1.  Which holidays affect weekly sales the most?

**Insights:**
- **Thanksgiving** had the **highest sales spike**, followed closely by **Christmas**.
- **Super Bowl** week also showed significant increases in weekly sales.
- **Labor Day** had moderate effects, but not as impactful.
- Increased promotions and foot traffic contributed to these trends.

---

### 2.  Which stores have the lowest and highest unemployment rate?

**Insights:**
- **Store 10** had the **lowest average unemployment rate**, indicating a stable regional economy.
- **Store 20** had the **highest unemployment**, potentially located in a more economically challenged area.
- **Influencing factors** include population density, access to jobs, urbanization, and economic development.

---

### 3.  Is there any correlation between CPI and Weekly Sales?

**Insights:**
- Overall correlation between **CPI** and **Weekly Sales** is **very weak**.
- During **holiday weeks**, there is a **slight negative correlation**, possibly due to inflation affecting purchase power.
- Suggests CPI alone does not significantly drive Walmart’s weekly sales.

---

### 4.  What conclusions can be made about Fuel Price?

**Insights:**
- Slight **negative correlation** between **Fuel Price** and **Weekly Sales**.
- Rising fuel costs may reduce:
  - Customer mobility
  - Delivery efficiency
  - In-store visits
- Reflects economic conditions and shopper behavior.

---

##  Tools and Libraries Used
- **Python**
  - `pandas`
  - `matplotlib`
- **Jupyter Notebook**

---

##  Key Insights

- **Holiday Impact:** Thanksgiving, Christmas, and Super Bowl weeks significantly boost weekly sales.
- **Unemployment:** Stores with higher unemployment tend to have lower or more inconsistent sales.
- **CPI:** Weak overall correlation with sales; slight negative effect during holidays.
- **Fuel Price:** Slight negative correlation—higher prices may deter store visits and impact logistics.

---

##  Recommendations

- **Maximize Holiday Campaigns:**
  - Focus marketing and inventory on key holidays.
  - Offer targeted promotions to capture peak spending.

- **Support Economically Challenged Stores:**
  - Launch community outreach and regional promotions.
  - Tailor offers to customer demographics in high-unemployment areas.

- **Monitor Economic Indicators:**
  - While CPI has a weak effect, watch for inflation periods to adjust pricing strategies.

- **Fuel Price Strategy:**
  - Encourage online shopping and delivery options when fuel costs are high.
  - Optimize supply chains to minimize transportation expenses.


