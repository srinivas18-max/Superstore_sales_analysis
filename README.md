# Sales Performance Dashboard | Power BI

## Project Overview
This project analyzes Superstore sales data using **Microsoft Power BI** to understand sales performance, profitability, product performance, customer segments, regional results, and shipping methods. The report brings key business metrics into one interactive dashboard to make it easier to identify trends and compare performance.

## Dashboard Preview
[Sales Performance Dashboard](dashboard.png)

## Business Objectives
- Monitor overall sales, profit, and order volume.
- Compare sales performance across regions.
- Track monthly sales and profit trends.
- Understand profit contribution by product category.
- Compare sales across customer segments and shipping modes.
- Identify the top five products by sales.

## Key Dashboard Insights
The values below are based on the dashboard shown in the project screenshot and may vary if the report is refreshed or filters are changed.

- **Total Sales:** approximately **2.03M**
- **Total Profit:** approximately **236.19K**
- **Total Orders:** approximately **1K**
- **Regional performance:** East has the highest sales among the regions shown, followed by West, Central, and South.
- **Category profitability:** Office Supplies has the highest profit among the three categories shown, followed by Technology and Furniture.
- **Customer segments:** Corporate contributes the highest sales in the displayed segment comparison.
- **Shipping mode:** Regular Air represents the largest share of sales in the displayed chart.
- **Product performance:** The dashboard highlights the top five products by sales.

These are observations from the current dashboard view, not causal conclusions. Use slicers and visual interactions in Power BI to explore the details.

## Dashboard Components
1. **KPI cards** — Total Sales, Total Profit, and Total Orders.
2. **Manager slicer** — filters the report by manager.
3. **Regional summary table** — compares sales and profit by region.
4. **Monthly Sales Trend** — compares monthly sales and profit.
5. **Sales by Region** — compares sales across regions.
6. **Profit by Category** — compares profit across Office Supplies, Technology, and Furniture.
7. **Sales by Customer Segment** — compares Corporate, Home Office, Consumer, and Small Business.
8. **Sales by Ship Mode** — shows the sales distribution across shipping methods.
9. **Top 5 Products by Sales** — ranks the five leading products by sales.

## Dataset
The source Excel workbook is `SuperStoreUS-2015.xlsx` and contains three sheets:

- **Orders** — order, customer, product, shipping, location, sales, and profit details.
- **Returns** — order IDs and return status.
- **Users** — region-to-manager mapping.

The Orders sheet includes fields such as `Order Date`, `Ship Date`, `Region`, `Customer Segment`, `Product Category`, `Product Sub-Category`, `Product Name`, `Ship Mode`, `Sales`, `Profit`, `Quantity ordered new`, and `Order ID`.

## Tools Used
- **Microsoft Power BI Desktop** — report building and visualization
- **Microsoft Excel** — source data
- **Power Query** — data import and preparation, if used in the report
- **DAX** — measures and calculations, if used in the report

## Workflow
1. Imported the Superstore workbook into Power BI.
2. Reviewed the available order, returns, and manager data.
3. Prepared the data and checked relevant fields for reporting.
4. Built KPI cards and visuals to compare sales and profit.
5. Arranged the visuals into a single-page dashboard.
6. Reviewed the report to identify sales patterns and performance differences.

## How to View the Project
1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, update the source file path to the location of `SuperStoreUS-2015.xlsx`.
4. Refresh the data to load the report.
5. Use the manager slicer and select visuals to explore the dashboard.

## Skills Demonstrated
- Power BI dashboard development
- Data handling and data visualization
- Sales and profitability analysis
- Comparing performance by region, product category, customer segment, and shipping mode
- Presenting business metrics in a single report

## Future Improvements
- Add year, quarter, and date-range filters.
- Add return-rate analysis by region and product.
- Include profit margin and average order value KPIs.
- Add drill-through pages for product and customer details.
- Improve accessibility with descriptive titles, consistent number formatting, and alt text.

---
**Author:** Srinivas  
**Project:** Sales Performance Dashboard using Power BI
