# Retail Sales Analysis — Problem Statement

## Business Objective  
A **retail analyst** wants to understand **monthly sales patterns** and **store performance** in order to support effective **stock planning** and **promotional strategies**.

The goal is to perform **Exploratory Data Analysis (EDA)** on the retail sales dataset to uncover trends, growth patterns, and operational insights.

---

## Key Analytical Questions  

### 🔹 1. Data Understanding  
- Load the dataset and inspect:
  - Data types  
  - Shape (rows × columns)  
  - Missing values  

---

### 🔹 2. Date-Time Processing  
- Convert the `Month` column to a proper **datetime** format.  
- Extract:
  - **Year**
  - **Month name**

---

### 🔹 3. Descriptive Statistics  
- Compute key sales metrics:
  - **Total Sales**
  - **Average Monthly Sales**
  - **Median Sales**

---

### 🔹 4. Category & Contribution Analysis  
- Identify which **store type/category** contributes the most to **annual sales**.

---

### 🔹 5. Trend Visualization  
- Plot a **monthly sales trend line chart** to visualize patterns and seasonality.

---

### 🔹 6. Top Performance  
- Identify the **Top 5 months** with the highest total sales.

---

### 🔹 7. Growth Analysis  
- Calculate **Month-over-Month (MoM)** percentage change in sales.

---

### 🔹 8. Seasonality Visualization  
- Create a **heatmap** of total sales by **Year** and **Month**.

---

### 🔹 9. Outlier Detection  
- Detect **outlier months** using the **Interquartile Range (IQR)** method.

---

### 🔹 10. Correlation Study  
- Calculate correlation between:
  - `Sales`
  - `Inventory`
  - `Revenue`

---

### 🔹 11. Regional Performance  
- Build a **pivot table** showing **total sales by Region and Year**.

---

### 🔹 12. Underperforming Periods  
- Identify months where sales are **below the yearly mean**.  
- Count how many such months exist.

---

### 🔹 13. Feature Engineering  
- Create a new feature:
  ```python
  Sales_Per_Store = Total_Sales / Num_Stores

  ### 🔹    14. Category Visualization 
- Visualize total sales per store category using a bar plot.

---

### 🔹 15.Growth Flag  
- Create a binary feature:
  ```python
  Sales_Growth_Flag = 1 if MoM_Change > 0 else 0


### Expected Insights
- Detect seasonal sales trends and high-performing months.
- Identify top-performing store categories and regions.
- Discover growth or decline patterns across months.
- Engineer features for forecasting and performance modeling.