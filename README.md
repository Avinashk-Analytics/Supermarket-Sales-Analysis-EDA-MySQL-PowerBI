# 🛒 Supermarket Sales Analysis  
**Data Analytics Project using | Python | MySQL | Power BI**


## 📌 Project Overview  
This project demonstrates a complete **data analytics project** on a **Supermarket Sales** dataset.  
It covers **data exploration, cleaning, and visualization** using **Python (EDA)**,  
**business insights extraction** via **MySQL**, and an **interactive dashboard** in **Power BI**.

The goal was to analyze sales performance, customer preferences, payment trends,  
and revenue distribution to derive **actionable insights**.


## 📂 Project Structure  
```bash
Supermarket_Sales_Analysis/
│
├── Supermarket_Sales_EDA.html       # Python EDA with Pandas, Matplotlib, Seaborn
├── Supermarket_sales_query.sql      # MySQL queries for business analysis
├── dashboard.png                    # Power BI dashboard screenshot
└── README.md                        # Project documentation


## 🛠 Tools & Technologies  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn (Exploratory Data Analysis)  
- **MySQL**: Business queries & insights generation  
- **Power BI**: Interactive dashboard creation  
- **Dataset**: Supermarket Sales (3 cities, multiple product lines)


## 🔍 Data Analysis Workflow  

### 1️⃣ **Exploratory Data Analysis (Python)**  
- **Data loading & inspection**  
- **Missing value handling**  
- **Data type conversion**  
- **Statistical summary & distribution analysis**  
- **Visual analysis for:**  
  - **Revenue trends**  
  - **Product line performance**  
  - **Payment method share**  
  - **City-wise sales**  
  - **Customer type patterns**


### 2️⃣ **Business Analysis (MySQL Queries)**  
**Key SQL queries include:**  
- **City with the highest total revenue**  
- **Most frequently purchased product line**  
- **Average rating by city**  
- **Transactions by payment method**  
- **Gross income by product line**  
- **Top customer type contributing to sales**  
- **Date with highest revenue**  
- **Average unit price per product line**  
- **Top 3 grossing product lines in each city**  
- **Low-profit, high-quantity product lines**  
… and more.  

*(SQL file contains **10+ analytical queries**)


### 3️⃣ **Visualization (Power BI Dashboard)**  
**Dashboard Features:**  
- **KPIs**: Total Revenue, Total Gross, Quantity Sold, Average Rating, Total Transactions  
- **Bar Charts**: Product line gross income, city-wise total revenue  
- **Pie Chart**: Sales by payment method  
- **Line Chart**: Sales trend over time  
- **Filters**: Customer type, city selection


## 📊 Key Insights  
- **Highest revenue city**: Naypyitaw (~111K)  
- **Top product lines by gross income**: Food and Beverages, Sports and Travel  
- **Most used payment method**: E-Wallet (34.5%)  
- **Average customer rating**: 7/10  
- Certain product lines show **high quantity but low profit margin**

## 🚀 How to Run the Project  

### **1️⃣ Python EDA**  
- **Open** the `Supermarket_Sales_EDA.html` file in **Jupyter Notebook** or any HTML viewer.  
- **Command to open in Jupyter**:  
```bash
jupyter nbconvert --to notebook Supermarket_Sales_EDA.html --execute

### 2️⃣ **MySQL Analysis**
- **Import** the dataset into **MySQL**.  
- **Run** all queries from the **`Supermarket_sales_query.sql`** file:

```sql
-- In MySQL CLI or Workbench
source Supermarket_sales_query.sql;

### 3️⃣ **Power BI Dashboard**  
- **Open** the **`Supermarket_Sales.pbix`** file in **Power BI Desktop**.  
- **Refresh** the **data source connection** to link it to your **local** or **remote database**.  




