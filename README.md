```md
# DMart Retail Sales & Operations Analysis (Power BI)

## Project Overview
This project focuses on analyzing retail sales, customer behavior, product performance, and operational efficiency for a DMart-like retail business using Power BI.  
The goal is to transform raw transactional data into actionable business insights through proper data modeling, DAX calculations, and interactive dashboards.

---

## Business Questions Answered

### Sales & Revenue Trends
- How do monthly and yearly sales figures compare?
- What is the revenue contribution of Branded, Local, and Imported products?

### Customer Demographics & Behavior
- What is the distribution of customers by age group and gender?
- How does website engagement (time spent, clicks) influence purchase behavior?

### Product & Pricing Insights
- Which products generate the highest revenue and discounts?
- Do discounted products result in better ratings and repeat purchases?

### Operational Performance
- Which shipping modes are most commonly used?
- What is the order cancellation rate and its probable causes?

### Payment & Order Status
- What is the breakdown of payment modes (COD vs Online)?
- Are certain product types more prone to pending or cancelled orders?

---

## Data Modeling
- Implemented a **Star Schema** with a centralized Fact table and multiple Dimension tables.
- Dimensions include Customer, Product, Date, Payment Mode, and Shipping Mode.
- Ensured optimized relationships for accurate filtering and aggregation.

(Refer to `Data_Model/data_model.png`)

---

## Tools & Technologies Used
- Power BI Desktop
- Power Query (M Language) for data cleaning and transformation
- DAX for KPIs and business metrics
- Structured CSV datasets

---

## Key Learnings
- Importance of dimensional modeling for scalable analytics
- Writing optimized DAX measures for time intelligence and KPIs
- Translating business problems into analytical dashboards
- Building executive-ready visualizations

---

## Dashboard Preview
Dashboard screenshots are available in the `Dashboard_Screenshots` folder.

---

## Author
Tinish
