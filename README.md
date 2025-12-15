# Vendor Performance Analysis  
**Sales, Margin & Inventory Optimization**

## Business Problem
Retail and wholesale businesses often struggle with inconsistent profitability, vendor dependency, and inefficient inventory management.  
This project analyzes vendor performance to identify revenue concentration risk, pricing inefficiencies, and capital locked in unsold inventory, enabling data-driven procurement and pricing decisions.

---

## Dataset Overview
The analysis is based on an integrated retail dataset containing:
- Sales transactions
- Purchase and vendor invoice data
- Product pricing information
- Inventory movement data  

The final analysis uses a consolidated vendor–brand summary with **10,000+ records** representing end-to-end vendor performance.

---

## Key Business Insights
- **$441.41M** in total sales generated **$134.07M** gross profit  
- Overall profit margin of **38.7%**
- **Top 10 vendors contribute 65.7%** of total purchase value, indicating dependency risk
- **198 brands** show high profit margins but low sales volumes, signaling pricing and promotion opportunities
- **$2.71M** in capital tied up in unsold inventory, impacting cash flow
- Bulk purchasing results in **72% lower unit cost** compared to smaller orders

---

## Business Recommendations
- Diversify vendor partnerships to reduce procurement and supply-chain risk  
- Leverage bulk purchasing selectively to improve margins without increasing inventory risk  
- Re-price or promote high-margin, low-volume brands to unlock incremental revenue  
- Optimize inventory planning to reduce slow-moving stock and free working capital  

---

## Tools Used
- **SQL** – data extraction and aggregation  
- **Python (Pandas, NumPy)** – analysis and validation  
- **Power BI** – interactive dashboard and visualization  

---

## Repository Structure

vendor-performance-analysis/
├── data/
│   └── vendor_sales_summary.csv
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb
│   └── Vendor Performance Analysis.ipynb
├── scripts/
│   ├── get_vendor_summary.py
│   └── ingestion_db.py
├── dashboard/
│   └── vendor_performance.pbix
├── reports/
│   └── Vendor Performance Report.pdf
└── README.md



---

## Outcome
This analysis demonstrates how vendor-level analytics can directly support profitability improvement, risk mitigation, and cash-flow optimization by aligning procurement, pricing, and inventory decisions with data-driven insights.

---

### 🔒 Final Note
This project focuses on **business impact and decision-making**, not just technical execution, and reflects the analytical approach expected in real-world Data Analyst and Business Analyst roles.
