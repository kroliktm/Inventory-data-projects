# Inventory Analysis – Logistics Data Project

## Project Overview
This is my first inventory data analysis project. I used a synthetic warehouse dataset to practice real inventory control and data analysis tasks. The project is based on daily stock levels, inbound and outbound movements and reorder levels.

The main goal of the project was to check which products may go below the safe stock level and how the inventory behaves over time.

---

## Business Questions
- Which products need to be reordered?
- How does inbound compare to outbound over time?
- Which warehouse zones have the highest stock?
- Where is the risk of stock shortage?

---

## Dataset
The dataset contains:
- date  
- sku  
- product_name  
- warehouse_zone  
- stock_on_hand  
- inbound  
- outbound  
- reorder_level  
- inventory_gap  

Additional columns created by me in Excel:
- net_flow  
- projected_stock  
- reorder_status  
- zone_load  

---

## Tools Used
- Excel for data cleaning, formulas, pivot tables and dashboard
- GitHub for saving and sharing the project

---

## Key Findings
- I found several SKUs that require reorder based on projected stock.
- Some warehouse zones are much more loaded than others.
- In some periods outbound was higher than inbound, which increases stock risk.

---

## Output
- Cleaned Excel file with calculations
- Inventory dashboard
- This project summary

---

## Next Steps
- Do the same analysis in SQL
- Create a Power BI dashboard
- Add more KPIs like stock rotation and days of cover
