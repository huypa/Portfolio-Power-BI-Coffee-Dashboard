# ☕ Portfolio – Power BI Coffee Shop Dashboard
## Overview
I designed and developed an interactive **Power BI dashboard** to analyze and visualize the performance of three key coffee stores — **Astoria**, **Hell’s Kitchen**, and **Lower Manhattan**. The dashboard highlights **daily, weekly, and categorical sales performance**, enabling business users to monitor revenue trends, identify high-performing stores, and understand customer purchasing patterns.

## Project Details

- **Tool:** Power BI  
- **Data Source:** [Point-of-Sale Transaction Data (Kaggle)](https://www.kaggle.com/code/ahmedabbas757/coffee-shop-sales/input)  
- **Goasl Focus:** Revenue, Product Mix, Store & Time Analysis  
- **Technical Focus:** Power Querry / DAX / Database Design

    The data model follows a star schema with Transaction as the central fact table connected to key dimensions — Dim_product, Dim_type, Dim_location, and Dim_Date. It supports time-based, product, and store-level analysis. Supporting tables like Measure Table and Parameter enable dynamic KPI calculations and interactive Power BI reports for revenue, quantity, and transaction insights.

<img width="876" height="926" alt="Screenshot 2025-10-29 at 12 18 34" src="https://github.com/user-attachments/assets/bd1826e8-94a8-4ebb-a711-ca26870ad551" />

## Key Features & Insights
### Revenue & Trend Analysis
- Interactive **line and bar charts** showing total revenue and growth trends by store and week, with **hover-enabled tooltips** displaying detailed metrics (e.g., daily revenue, % change vs. previous period).

### Store Comparison
- Visualized each store’s contribution using **dynamic comparison visuals** and **share indicators**, providing instant insights into performance balance.

### Product & Category Breakdown
- Ranked **top product types** (*Barista Espresso, Chai Tea, Gourmet Coffee*) and **categories** (*Coffee, Tea, Bakery*, etc.) using horizontal bar charts for intuitive readability. I also added filter options for quickly 

### Weekday vs. Weekend Performance
- Displayed **customer traffic and sales volume** differences between weekdays and weekends to support staffing and promotional strategy planning.

## Color & Design System

- **Palette:** Warm, coffee-inspired tones — *espresso browns*, *latte beige*, and *cream neutrals* for visual comfort.  
- **Highlights:** Accent colors applied strategically to emphasize KPIs and positive/negative performance trends.  
- **Layout:** Balanced visual hierarchy and clean typography for readability and user engagement.  

## Interactivity & Usability

- **Dynamic Filters:** Select by *Month*, *Store*, or *Metric* (Revenue, Quantity, Transactions).  
- **Hover Cards:** Reveal contextual data such as *percentage change*, *total contribution*, and *performance vs. prior month*.  
- **Drill-down Features:** Allow users to explore data from overall trends down to daily performance.  
- **Responsive Design:** Optimized layout for both large and compact screen views.

## Results

Delivered an **insight-driven dashboard** that enhanced:
- Business **visibility into store-level performance**  
- **Operational efficiency** in sales tracking and forecasting  
- **Data-driven decision-making** through clear, actionable insights  

The refined design and interactivity empowered stakeholders to **explore performance trends intuitively** and **respond rapidly** to market changes.

