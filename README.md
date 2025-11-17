# Candy Company – Power BI Sales Analysis

This project provides a complete Power BI analysis of the sales performance of a global candy company.  
It includes data cleaning (Power Query), data modeling, and interactive dashboards for business insights.

---

## Project Objectives
- Analyze overall company sales performance  
- Identify best-selling and most profitable products  
- Evaluate performance across cities and regions  
- Provide actionable insights for decision-makers  

---

## Project Files
- Power BI project.pbix – Full Power BI report including data model, and dashboards  
- README.md – Project documentation  

---

## Data Model (Tables Overview)

| Table | Description | Key |
|-------|-------------|------|
| Candy Distributor Data Dictionary | Definitions of all table columns | — |
| Candy Factory | Information about production factories | Factory (PK) |
| Candy Products | Product details (brand, category, size) | ProductID (PK) |
| Candy Sales | Sales transactions with revenue, quantity, profit, and city | OrderID (PK) |
| Candy Targets | Yearly revenue targets per division | Division (PK) |
| US ZIP Codes (uszips) | Geographic and demographic ZIP code information | Zip (PK) |

---

## Business Questions Explored
- Which products generate the highest profit?  
- Which cities generate the most revenue?  
- What are the strongest product categories?  
- Which regions should the company focus on?  

---

## Key Insights

### 1. The United States dominates sales  
Approximately 98% of total profit comes from the U.S. market.  
Recommendation: continue focusing operational and marketing efforts in this region.

### 2. Chocolate is the strongest category  
Chocolate-based products account for around 95% of total profit.  
Recommendation: expand product offerings and marketing campaigns in this segment.

### 3. Leading brand: Wonka Bar  
The Wonka Bar product line generates the highest share of revenue.  
Recommendation: expand the product line and support it through targeted marketing.

### 4. Most profitable cities  
New York and Los Angeles lead in total revenue.  
Recommendation: focus regional efforts and campaigns in these key cities.

### 5. Canada shows limited potential  
Canada contributes only a small portion of profit.  
Recommendation: assess whether continued investment in this market is worthwhile.

---

## Tools and Technologies
- Power BI Desktop  
- Power Query  
- Data Modeling (Star Schema)  
- Excel data sources  
