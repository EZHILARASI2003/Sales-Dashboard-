# Sales-Dashboard-
Interactive Sales Dashboard built in Power BI using the Superstore dataset (2019–2022). It visualizes KPIs, sales trends, category and region breakdowns, profitability, and shipping-impact analysis. Designed for quick insights, data-driven decisions, and action recommendations—all easily reproducible.
# Sales Dashboard – Data Visualization & Storytelling

##  Objective
Create an interactive sales dashboard (Tableau or Power BI) that communicates insights from the Superstore dataset through data storytelling.

## Dataset
- **Source**: *Superstore.csv*
- Contains orders with fields such as Order Date, Ship Date, City, Region, Category, Sub-Category, Product Name, Sales, Profit, Quantity, Customer, Ship Mode, etc.

## How to Reproduce
1. Open `Superstore.csv` in Tableau Desktop (or Power BI).
2. Create calculated fields:
   - **Profit Margin** = Profit / Sales
   - **Shipping Days** = DATEDIFF('day', [Order Date], [Ship Date])
3. Build the following sheets:
   - KPI tiles (Total Sales, Profit, Quantity, Customers, Products)
   - Monthly Sales Trend (line chart)
   - Sales by Region (map or bar chart)
   - Category/Sub-category breakdown (bar chart)
   - Profit Margin by Product/Sub-Category (bar with line overlay)
   - Shipping Time vs Profit (scatterplot)
4. Assemble these on a dashboard; apply filters (City, Product, Month, Year) and add tooltips, annotations, and descriptive titles.
5. Export the dashboard as PDF or take screenshots and place them in the repository.

## Main Insights
  Insight 1: Sales peaked in 2021 (~203K), followed by a slight dip in 2022.
  Insight 2: The *Technology* category contributes ~40% of sales, but *Furniture* shows stronger profit margins.
Insight 3: Certain sub-categories (e.g., Appliances) are high in sales but low in profit—highlighting potential margin risks.
Insight 4: Shipping methods with longer delivery often have lower margins—suggesting a need to revisit shipping strategies.

## Recommended Actions
- Review discount policies for low-margin high-volume sub-categories (e.g., Appliances).
- Focus marketing on high-margin categories like Furniture.
- Optimize shipping: encourage faster or more cost-effective modes for margin improvement.
- Leverage region filters to localize promotions and inventory restocking.

## (Optional) Interactive Preview
If available, include a short GIF or video (e.g. `interactivity_preview.gif`) demonstrating dashboard filtering and interactions.

## notes.txt
See below.

## Acknowledgments & References
- Built using  Power BI
- Inspired by best practices from *Storytelling with Data*, Tableau, and NN/g on dashboard design.
