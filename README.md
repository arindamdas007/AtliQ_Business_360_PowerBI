# Business Insights 360 – AtliQ Hardware Power BI Project

## 📌 Project Overview

**AtliQ Hardware** has experienced rapid growth in recent years. To surpass competitors and make **data-driven decisions**, the company decided to implement **Power BI analytics** for the first time.  

This project aims to provide insights across **Finance, Sales, Marketing, and Supply Chain**, answering key stakeholder questions and supporting strategic decision-making. 

**Live Report:** [View Dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiODA0OTIzYjMtNzI0Zi00OTMxLWIxYjUtOWFmNTVjYTMwMWY3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 🛠 Technical Tools

- **Power BI Desktop**  
- **SQL**  
- **Excel**  
- **DAX Language & DAX Studio** (for report optimization)  
- **Power BI Service**  
- Project documentation / charter files  

---

## 💡 Power BI Techniques Learned

- Defining **project questions before starting**  
- Creating **calculated columns** and **measures** using DAX  
- Data modeling (Snowflake method)  
- Using **bookmarks** for switching visuals  
- **Page navigation** with buttons  
- Preventing zero division using the `DIVIDE()` function  
- Creating **date tables** using M language  
- Dynamic titles based on filters  
- Using **KPI indicators**  
- Conditional formatting with icons and background colors  
- Data validation techniques  
- Publishing to **Power BI Service**  
- Personal gateway setup for **auto refresh**  
- Power BI App creation  
- Workspace collaboration and access permissions  

---

## 📊 Business Terms

- Gross Price  
- Pre-Invoice Deductions  
- Post-Invoice Deductions  
- Net Invoice Sale  
- Gross Margin  
- Net Sales  
- Net Profit  
- COGS (Cost of Goods Sold)  
- YTD (Year to Date)  
- YTG (Year to Go)  
- Direct, Retailer, Distributors, Consumer  

---

## 🏢 Company Background

**AtliQ Hardware** sells **computers and accessories** globally via:

- Retailers  
- Direct channels  
- Distributors  

The company faced unforeseen losses in America and lacks a strong analytics team, while competitors already leverage data-driven insights. This project helps establish a **foundation for analytics-led decision-making**.

---

## 📋 Questions to Ask Before Starting a Dashboard

1. What is the objective of the dashboard?  
2. How will project success be measured?  
3. What is the project timeline?  
4. Are stakeholders expecting previews?  
5. What are stakeholder hopes and fears?  
6. Who will use the dashboard and for what purpose?  
7. What expectations exist upon completion?  
8. What risks exist during development?  
9. What data and resources are needed?  
10. Are there stakeholder inputs for design or visuals?  

---

## 🗂 Dataset Understanding

**Dimension Tables** – Static data like customer and product details  

- `dim_customer` – 27 markets, 75 customers, 2 platforms (Brick & Mortar, E-commerce), 3 channels  
- `dim_market` – 27 markets, 7 sub-zones, 4 regions  
- `dim_product` – Divisions: P&A, Peripherals, Accessories, PC, Notebook, Desktop, Networking, Storage; 14 categories  

**Fact Tables** – Transactional and forecast data  

- `fact_forecast_monthly` – Forecasted customer demand  
- `fact_sales_monthly` – Actual sales data  
- `freight_cost` – Market-wise travel and logistics cost  
- `gross_price`, `manufacturing_cost`, `pre_invoice_deductions`, `post_invoice_deductions`  

> Data imported from **MySQL database** using credentials provided by the Data Engineering team.

---

## 🗄 Data Modeling

- Followed **Snowflake modeling method**  
- Ensured **good practices** to optimize report performance  
- Data model forms the **foundation of all visuals**  
<img width="1200" height="335" alt="Data Model" src="https://github.com/user-attachments/assets/5bdd809f-6619-456d-82eb-6e68e63c6162" />

---

## 🎨 Dashboard Design

### Home View
- Navigation buttons to different report views  
  - Info  
  - Finance  
  - Sales  
  - Marketing  
  - Supply Chain  
  - Executive  
  - Products  
  - Support  

### Views

- **Home Page** – Project details and context
- **Finance View** – Gross/Net sales, margins, and profitability analysis
- **Sales View** – Sales trends, top customers, and channels
- **Marketing View** – Campaign and market analysis
- **Supply Chain View** – Forecast vs. actual, inventory insights
- **Executive View** – High-level KPIs for management
- **Products View** – Product-wise sales and performance  

> Visual previews available in the `Documentation/` folder  

---

## ✅ Project Outcome

- Enabled **data-driven decision-making**  
- Provided insights for finance, sales, marketing, and supply chain  
- Supported **“why” analysis** for unexpected trends and performance gaps  
- Built foundation for **analytics-led culture** at AtliQ Hardware  

---

## Overall Report

HomeView

<img width="668" height="373" alt="Home" src="https://github.com/user-attachments/assets/d2b0396e-dd9e-4398-b3cb-9d24e21cd96f" />

FinanceView

<img width="665" height="373" alt="Finance View" src="https://github.com/user-attachments/assets/5c5638db-05d0-402f-bb67-c5d47cc7463d" />

SalesView

<img width="665" height="368" alt="Sales View" src="https://github.com/user-attachments/assets/6ff46582-0fa4-45c2-b0fa-3389635e4a21" />

MarketingView

<img width="667" height="371" alt="Marketing View" src="https://github.com/user-attachments/assets/e3b48d26-bcb4-469a-8fcf-bf29c563c017" />

SupplyChainView

<img width="662" height="376" alt="Supply Chain View" src="https://github.com/user-attachments/assets/8adf5ce3-4ac5-4567-b822-fb27017c0889" />

ExecutiveView

<img width="667" height="373" alt="Executive View" src="https://github.com/user-attachments/assets/3e97bccd-5f42-49da-a8c1-ae2b7dee6163" />

ProductsView

<img width="665" height="371" alt="Top   Bottom Product View" src="https://github.com/user-attachments/assets/65b661e6-98de-4042-ab49-6403e80921f1" />


## 🖊 Author

**Arindam Das** – Aspiring Data Analyst  
🔗 [LinkedIn](linkedin.com/in/arindamdas007)

---

## ✅ Project Outcome

The dashboard enables AtliQ Hardware to make data-driven decisions, monitor performance across all business functions, and gain actionable insights for strategic growth.

## ⚡ Acknowledgement

Inspired by **Codebasics Power BI course** and the **Business Insights 360 methodology**, integrating **finance, sales, marketing, and supply chain analytics**.
