# customer-behavior-Analysis-
Analysis on Customer Behaviour Using Python + SQL + Power BI
# 📊 Customer Shopping Behavior Analysis

---

## 📌 Overview
This project analyzes customer shopping behavior to uncover meaningful patterns, trends, and insights that support data-driven business decisions.

The workflow covers the complete data analytics lifecycle—from data loading and cleaning to exploratory analysis, SQL-based querying, and interactive dashboard creation.

---

## 📁 Dataset
- ~3,900 customer records  
- 18 features including:

### Key Feature Groups
- **Demographics:** Age, Gender, Location, Subscription Status  
- **Transactions:** Item Purchased, Category, Purchase Amount  
- **Behavior:** Frequency of Purchases, Discounts, Review Ratings, Shipping Type  

- Missing values were identified in the **Review Rating** column and handled during preprocessing.

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning & EDA  
- **MySQL Workbench** – SQL analysis and business queries  
- **Power BI** – Interactive dashboard creation  
- **Gamma** – Presentation (PPT) creation  

---

## 🔄 Project Steps

### 1. Data Loading & Cleaning (Python)
- Imported dataset using Pandas  
- Handled missing values using median imputation  
- Standardized column names (snake_case)  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of spending and ratings  
- Identified trends, patterns, and outliers  
- Performed feature-level analysis  

### 3. SQL Analysis (MySQL Workbench)
- Revenue analysis by gender and age group  
- Customer segmentation (New, Returning, Loyal)  
- Discount vs spending behavior  
- Product performance and rating analysis  

### 4. Dashboard Development (Power BI)
- Built interactive dashboards to visualize:
  - Customer segments  
  - Revenue trends  
  - Product/category performance  
- Enabled filtering and drill-down capabilities  

### 5. Reporting & Presentation
- Created a structured analytical report  
- Designed a professional presentation using Gamma  

---

## 📊 Dashboard
The Power BI dashboard provides:
- Customer segmentation insights  
- Revenue and spending trends  
- Category-level performance  
- Interactive filters for deeper analysis  

---

## 📈 Results & Insights
- Loyal customers contribute significantly to total revenue  
- Discounts influence purchasing behavior but vary across segments  
- Certain product categories consistently perform better  
- Customer satisfaction varies across products  

---

## 🚀 How to Run the Project

### 1. Python Analysis
Install required libraries:
pip install pandas numpy matplotlib seaborn

- Open the Jupyter Notebook  
- Run all cells for data cleaning and EDA  

### 2. SQL Analysis
- Import dataset into **MySQL Workbench**  
- Run queries from the `.sql` file  

### 3. Power BI Dashboard
- Open `.pbix` file in Power BI Desktop  
- Refresh data if required  

### 4. Presentation
- View the PPT created using Gamma  

---

## 💡 Business Value
This project demonstrates how data analytics can:
- Improve customer targeting  
- Enhance retention strategies  
- Support data-driven decision making  
- Optimize marketing and pricing strategies  

---
