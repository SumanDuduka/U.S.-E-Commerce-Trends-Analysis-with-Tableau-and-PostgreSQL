# U.S. E-Commerce Analysis

## Project Overview
This project analyzes U.S. e-commerce sales trends using **Tableau** and **PostgreSQL** to identify high-performing states, seasonal sales patterns, and customer demographics. The insights guide strategic store setup and inventory planning.The dataset used in this project contains **286,393** rows and **36** columns.

## Tools Used
- **Tableau** (Data Visualization)
- **PostgreSQL** (Database Management)
- **Excel** (Data Preparation)

## Approach
1. **Data Acquisition:** Downloaded the *"Online Sales in USA, 2023"* dataset from Kaggle.
2. **Data Preparation:**
   - Converted **XLSX** file to **CSV** for easier import into PostgreSQL.
   - Imported the **CSV** dataset into PostgreSQL.
3. **Data Analysis:**
   - Connected PostgreSQL to Tableau.
   - Wrote **SQL queries** in Tableau to filter, join, and organize the data.
   - Created **interactive dashboards** to visualize key insights.

## Key Findings
### Top U.S. States by Order Value
![States and Order Values](https://github.com/user-attachments/assets/6188b8ed-1e6e-4ca0-a64c-7861a766ddc5)
- **Texas:** Highest sales value at **$16.72M**.
- **California:** Second highest sales at **$15.30M**.

### Top 3 U.S. States by Orders Per Month
![Total Number of Orders Per State](https://github.com/user-attachments/assets/465488e1-77b2-42ee-b915-7e402373a16f)
- **Texas:** 50.91K orders
- **California:** 49.83K orders
- **New York:** 48.07K orders

### Seasonal Discount Trends
![Month and Discount Percentage](https://github.com/user-attachments/assets/49ca6ede-afde-40df-9201-a71e3208e509)
- Discounts peak from **November to January**, highest in **December**.

### Top-Selling Product Categories
![Category and Quantity Ordered](https://github.com/user-attachments/assets/f4d7e4be-0f0d-4fb9-9da5-9a1e68e3a8ee)
- **Mobiles & Tablets**
- **Men’s Fashion**
- **Appliances**

### Customer Demographics
- **Male Customers:** 52.31%
- **Female Customers:** 47.69%

## Conclusion
- Businesses should **prioritize Texas, California, and New York** for sales expansion.
- **Mobile phones** are the top-selling category—focus on this segment for higher revenue.
- Providing a **Cash-on-Delivery (COD)** option can increase conversions in key states.

## Dataset
The dataset contains **286,393 rows** and **36 columns** covering e-commerce sales in the U.S.

## 📎 Resources
- [Kaggle Dataset](https://www.kaggle.com/datasets/ytgangster/online-sales-in-usa)
